# AWX Cluster Monitoring

WIP


## Hosts

```ini
[monitoring]
172.27.11.10

[awx]
172.27.11.11
172.27.11.12

[postgres]
172.27.11.13

[node:children]
monitoring
awx
postgres
```
