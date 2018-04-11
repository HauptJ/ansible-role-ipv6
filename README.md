# ansible-role-ipv6
Ansible role to enable IPv6 on CentOS 7

The ```ansible-role-ipv6``` role is only necessary if your host supports IPv6 but does not provide an image that supports it out of the box without custom configuration.  To use this role you need to specify the ipv6 address and gateway in ```all.yml```. DigitalOcean supports IPv6 out of the box, while OVH's Cloud and OpenStack require it to be enabled manually.
