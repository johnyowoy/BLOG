# LXD Guides
###### tags: `DevOps`, `lxd`, `lxc`

# Requirements
OS Ubuntu 20.04
# Install LXD
## Choose release
* Long term support (LTS) releases: currently LXD 5.0.x and LXD 4.0.x
## Installing a package
### Snap package
```bash=
# the latest feature release
sudo snap install lxd
# the LXD 5.0 LTS release
sudo snap install lxd --channel=5.0/stable
```

```bash=
lxd launch
```
```bash=
lxd exec
```
# Storage
```bash=
# List available storage pools
lxc storage list
```
```bash=
# Show storage pool configurations and resources
lxc storage show <pool name>
```
[Storage](https://linuxcontainers.org/lxd/docs/master/storage/)
###### 參考資料
[Installation LXD](https://linuxcontainers.org/lxd/getting-started-cli/)
[How to install LXD](https://linuxcontainers.org/lxd/docs/master/installing/)
[How to create instances](https://linuxcontainers.org/lxd/docs/master/howto/instances_create/)
[Image server for LXC and LXD](https://uk.lxd.images.canonical.com/)
[How to initialize LXD](https://linuxcontainers.org/lxd/docs/master/howto/initialize/)