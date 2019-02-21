# packer-templates-linode

Packer templates to build Linode images.

## Usage

```sh
export LINODE_API_TOKEN=k33pItL1k3s3cr3t

cp secret/variables.example.json secret/variables.json

# edit variables

packer build --var-file secret/variables.json debian9.json
```
