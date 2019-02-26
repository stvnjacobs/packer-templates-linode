# packer-templates-linode

Packer templates to build Linode images.

## Usage

```sh
export LINODE_API_TOKEN=k33pItL1k3s3cr3t
```

Depending on the image you are building, there may be `files` or `secrets`.
These are stored under their named subdirectory under `files` or `secrets`.

For `secrets`, there are example files that you can copy and modify.

```sh
cp secrets/user/variables.example.json secrets/user/variables.json

# edit secrets/user/variables.json

packer build --var-file secrets/user/variables.json templates/user/debian9.json
```
