FROM openshift3/apb-base

LABEL "com.redhat.apb.spec"=\
"dmVyc2lvbjogMS4wCm5hbWU6IGJpdG5hbWktZHJ1cGFsLWFwYWNoZS1waHA3LW15c3FsCmRlc2Ny\
aXB0aW9uOiBCaXRuYW1pIERydXBhbCB3aXRoIEFwYWNoZSwgUEhQNyBhbmQgTXlTUUwgQW5zaWJs\
ZSBQbGF5Ym9vayBCdW5kbGUKYmluZGFibGU6IEZhbHNlCmFzeW5jOiBvcHRpb25hbAptZXRhZGF0\
YToKICBkaXNwbGF5TmFtZTogQml0bmFtaSBEcnVwYWwgd2l0aCBBcGFjaGUsIFBIUDcgYW5kIE15\
U1FMIChBUEIpCiAgZGVwZW5kZW5jaWVzOgogICAgLSAncmVnaXN0cnkuYWNjZXNzLnJlZGhhdC5j\
b20vcmhzY2wvbXlzcWwtNTctcmhlbDcnCiAgICAtICdkb2NrZXIuaW8vamF2c2FsZ2FyL2JpdG5h\
bWktZHJ1cGFsLXJoZWwtYXBhY2hlLXBocDcnCiAgZG9jdW1lbnRhdGlvblVybDogaHR0cHM6Ly9k\
b2NzLmJpdG5hbWkuY29tL2luc3RhbGxlci9hcHBzL2RydXBhbC8KICBpbWFnZVVybDogaHR0cHM6\
Ly9kMzNucDluMzJqNTNnNy5jbG91ZGZyb250Lm5ldC9hc3NldHMvc3RhY2tzL2RydXBhbC9pbWcv\
ZHJ1cGFsLXN0YWNrLTExMHgxMTctOWY5MzkxMWRhMmYyNjJlYzBhMmU1ZDQ5Y2RiZDU1NmYucG5n\
CiAgcHJvdmlkZXJEaXNwbGF5TmFtZTogQml0bmFtaQpwbGFuczoKICAtIG5hbWU6IGRlZmF1bHQK\
ICAgIGRlc2NyaXB0aW9uOiBUaGlzIGRlZmF1bHQgcGxhbiBkZXBsb3lzIERydXBhbCB3aXRoIHBo\
cC1mcG0gNy4yLCBBcGFjaGUgYW5kIG15c3FsCiAgICBmcmVlOiBUcnVlCiAgICBtZXRhZGF0YTog\
e30KICAgIHBhcmFtZXRlcnM6CiAgICAgIC0gbmFtZTogZHJ1cGFsX2VtYWlsCiAgICAgICAgZGVm\
YXVsdDogdXNlckBleGFtcGxlLmNvbQogICAgICAgIHR5cGU6IHN0cmluZwogICAgICAgIHRpdGxl\
OiBVc2VyIGVtYWlsCiAgICAgICAgZGVzY3JpcHRpb246IFVzZXIgZW1haWwKICAgICAgLSBuYW1l\
OiBkcnVwYWxfdXNlcm5hbWUKICAgICAgICBkZWZhdWx0OiB1c2VyCiAgICAgICAgcGF0dGVybjog\
Il5bYS16QS1aMC05X10qW2EtekEtWl9dK1thLXpBLVowLTlfXSokIgogICAgICAgIHR5cGU6IHN0\
cmluZwogICAgICAgIHRpdGxlOiBEcnVwYWwgYWRtaW4gdXNlcm5hbWUKICAgICAgICBkZXNjcmlw\
dGlvbjogRHJ1cGFsIGFkbWluIHVzZXJuYW1lCiAgICAgICAgcmVxdWlyZWQ6IHRydWUKICAgICAg\
LSBuYW1lOiBkcnVwYWxfcGFzc3dvcmQKICAgICAgICBwYXR0ZXJuOiAiXlthLXpBLVowLTlfXSpb\
YS16QS1aX10rW2EtekEtWjAtOV9dKiQiCiAgICAgICAgdHlwZTogc3RyaW5nCiAgICAgICAgdGl0\
bGU6IERydXBhbCBhZG1pbiBwYXNzd29yZAogICAgICAgIGRlc2NyaXB0aW9uOiBEcnVwYWwgYWRt\
aW4gcGFzc3dvcmQKICAgICAgICBkaXNwbGF5X3R5cGU6IHBhc3N3b3JkCiAgICAgICAgcmVxdWly\
ZWQ6IHRydWUKICAgICAgLSBuYW1lOiBkYl9uYW1lCiAgICAgICAgZGVmYXVsdDogZGF0YWJhc2UK\
ICAgICAgICB0eXBlOiBzdHJpbmcKICAgICAgICBwYXR0ZXJuOiAiXlthLXpBLVowLTlfXSpbYS16\
QS1aX10rW2EtekEtWjAtOV9dKiQiCiAgICAgICAgdGl0bGU6IERhdGFiYXNlIG5hbWUKICAgICAg\
ICBkZXNjcmlwdGlvbjogRGF0YWJhc2UgbmFtZQogICAgICAtIG5hbWU6IGRiX3VzZXIKICAgICAg\
ICBkZWZhdWx0OiBkYnVzZXIKICAgICAgICB0eXBlOiBzdHJpbmcKICAgICAgICBwYXR0ZXJuOiAi\
XlthLXpBLVowLTlfXSpbYS16QS1aX10rW2EtekEtWjAtOV9dKiQiCiAgICAgICAgdGl0bGU6IERh\
dGFiYXNlIHVzZXIKICAgICAgICBkZXNjcmlwdGlvbjogRGF0YWJhc2UgdXNlcgogICAgICAtIG5h\
bWU6IGRiX3Bhc3N3b3JkCiAgICAgICAgdHlwZTogc3RyaW5nCiAgICAgICAgdGl0bGU6IERhdGFi\
YXNlIHBhc3N3b3JkCiAgICAgICAgZGVzY3JpcHRpb246IERhdGFiYXNlIHBhc3N3b3JkCiAgICAg\
ICAgZGlzcGxheV90eXBlOiBwYXNzd29yZAogICAgICAgIHJlcXVpcmVkOiB0cnVlCiAgICAgIC0g\
bmFtZTogdm9sdW1lX3NpemUKICAgICAgICB0eXBlOiBlbnVtCiAgICAgICAgZGVmYXVsdDogJzFH\
aScKICAgICAgICBlbnVtOiBbJzFHaScsICc1R2knLCAnMTBHaSddCiAgICAgICAgdGl0bGU6IERh\
dGFiYXNlIHZvbHVtZSBzaXplCiAgICAgICAgcmVxdWlyZWQ6IHRydWUK"

COPY playbooks /opt/apb/actions
COPY roles /opt/ansible/roles
RUN chmod -R g=u /opt/{ansible,apb}
COPY licenses /licenses
USER apb
