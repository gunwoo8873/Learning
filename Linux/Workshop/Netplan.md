# Ubuntu Network
```yaml
network:
  version: 2
  renderer: networkd
  ethernets:
    enp0s3:
      dhcp4: no
      addresses:
        - 192.168.*.*/24 # Want to static ipaddress
      routes:
        - to: default
          via: 192.168.*.1
      nameservers:
        addresses: [8.8.8.8, 8.8.4.4]
```