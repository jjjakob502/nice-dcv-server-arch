# nice-dcv-server-arch
3 arch packages:

- https://github.com/aws/efs-utils
   - amazon-efs-utils
```

```
- https://www.amazondcv.com/
```console
# using: x86_64 + Ubuntu 24.04:

wget https://d1uj6qtbmh3dt5.cloudfront.net/2025.0/Servers/nice-dcv-2025.0-20103-ubuntu2404-x86_64.tgz

$ tar -xzf nice-dcv-2025.0-20103-ubuntu2404-x86_64.tgz 
cd nice-dcv-2025.0-20103-ubuntu2404-x86_64/

ls | grep -i -e server -e xdcv

nice-dcv-server_2025.0.20103-1_amd64.ubuntu2404.deb
nice-xdcv_2025.0.688-1_amd64.ubuntu2404.deb

```
   - nice-dcv-server
   - nice-xdcv

## Install
0. ensure you are using Arch Linux
1. git clone
2. cd into folder (e.g. `nice-dcv-server-bin`)
3. run : `makepkg -si`

## 