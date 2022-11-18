# Contributing

## Build and deploy

```bash
rockcraft pack -v
sudo skopeo --insecure-policy copy oci-archive:free5gc-upf_1.1.1_amd64.rock docker-daemon:free5gc-upf:1.1.1
docker run free5gc-upf:1.1.1
```
