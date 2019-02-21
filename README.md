# packer-templates-linode

Packer templates to build Linode images.

## Usage

```sh
cp /secret/variables.example.json /secret/variables.json
```

Edit variables

```sh
packer build --var-file /secret/variables.json debian9.json
```
