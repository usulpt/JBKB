# Ethernet restore

When for some reason the adapter seems to be disconnecting automatically:

```shell
netsh interface set interface "Ethernet 2" disable
netsh interface set interface "Ethernet 2" enable
```
