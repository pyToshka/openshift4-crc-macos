Openshift4 and CodeReady Containers on macOS
# Prerequisities
Clone repository:

```bash
git clone https://github.com/pyToshka/openshift4-crc-macos.git
cd openshift4-crc-macos
```
You should to download pull secret file from https://cloud.redhat.com/openshift/install/crc/installer-provisioned and put pull-secret.txt to directory with playbook

# Setup and start CRC for running OpenShift cluster

Run ansible playbook 


```bash
ansible-playbook -vvv -c local -i localhost, ./openshift4-installer.yaml
```
Have a fun

