# packing_vm
This repository provides some scripts to automate the VM building process from scratch.

# Personal notes
```bash
packer validate ubuntu_18.04.3_amd64.json
packer build ubuntu_18.04.3_amd64.json
packer build -only=virtualbox-iso debian_base.json
```


Check https://github.com/quarkslab/packer-debian