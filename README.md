# my-openstack-element


## 🚀 Usage


```
sudo su

pip install python-openstackclient
pip install install diskimage-builder

apt update
apt install -y debootstrap kpartx qemu-utils

openstack image create --disk-format qcow2 --container-format bare   --file ./debian-kubernetes.qcow2 debian-kubernetes
```
