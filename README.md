1. 安装插件
```shell
packer plugins install github.com/hashicorp/proxmox
```

2. 创建模板
```shell
packer build --var-file='../credentials.pkr.hcl' ./ubuntu-server-jammy-docker.pkr.hcl
```