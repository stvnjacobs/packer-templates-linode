# packer-templates-linode

Packer templates to build Linode images.

## Usage

```sh
export LINODE_API_TOKEN=k33pItL1k3s3cr3t

cp secrets/variables.example.json secrets/variables.json

# edit secrets/variables.json

packer build --var-file secrets/variables.json templates/user-debian9.json
```
