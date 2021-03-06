# Openstack OVH Analytics images

![Travis](https://travis-ci.com/Hugoch/ovh-analytics-openstack-images.svg?branch=master)

Packer and Ansible scripts to build Openstack base images for cluster deployment.


## Build

Export your Openstack credentials as environment variables.

```
export OS_PROJECT_ID=xxxxx
export OS_USERNAME=xxxxx
export OS_PASSWORD=xxxxx

export OS_AUTH_URL=xxxxx
export OS_REGION_NAME=xxxx
```

Build Analytics base images used by Terraform for cluster deployment on OVH
Public Cloud infrastructure:

```./packer.sh```


# Credits

This work is inspired by:
- https://github.com/gautamborad/hdp-ansible/tree/master/playbooks
- https://github.com/hortonworks/cloudbreak-images
- https://github.com/joe-speedboat/ansible.guacamole