# LEMP-APB

LEMP Ansible Playbook Bundle

## Test it

```
git clone https://github.com/bitnami/LEMP-APB.git
cd LEMP-APB
```

Prepare the ansible-container project for APB packaging:

```
apb prepare
```

Build and package APB container:

```
apb build
```

Push the new APB image to the local OpenShift registry:

```
apb push --push-to-broker
```

Relist the APBs available within the Service Catalog:

```
apb relist
```

### Using docker run to quickly test a Service Bundle

While developing Service Bundles, you may want to quickly test a Bundle without involving the Automation Broker or Service Catalog. This can be accomplished by using a `docker run` command.

Before continuing, run `oc login` and provide credentials for a cluster-admin user. This method of Service Bundle invocation mounts `~/.kube` into the Bundle container for authentication.

The example below shows a generic docker run command with placeholders for an `$SB_IMAGE_NAME`, `$ACTION_NAME`, and `extra-vars`.

```
docker run --rm --net=host -v $HOME/.kube:/opt/apb/.kube:z -u $UID \
$SB_IMAGE_NAME \
$ACTION_NAME \
--extra-vars 'namespace=sample-namespace' \
--extra-vars 'example_param_1=foo' \
--extra-vars 'example_param_2=bar'
```

The next example shows a `docker run` command which will perform the `provision` action of this Service Bundle, with necessary values substituted in.

```
docker run --rm --net=host -v $HOME/.kube:/opt/apb/.kube -u $(id -u) \
bitnami-lemp \
provision \
--extra-vars 'namespace=php-nginx' \
--extra-vars db_user=bitnami \
--extra-vars db_password=Bitnami1234 \
--extra-vars db_name=testdb \
--extra-vars git_repo=https://github.com/carrodher/sample-PHP-app
```

This will provision the Ansible Playbook Bundle in your OpenShift cluster. In order to deprovision it, replace provision with deprovision in the command above.
