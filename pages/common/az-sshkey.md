# az sshkey

> Manage ssh public key with vm.
> Part of `azure-cli`.
> More information: <https://docs.microsoft.com/cli/azure/sshkey>.

- Create a new SSH key:

`az sshkey create --name {{name}} --resource-group {{resource_group}}`

- Upload an existing SSH key:

`az sshkey create --name {{name}} --resource-group {{resource_group}} --public-key "{{@path/to/key.pub}}"`

- List all SSH public keys:

`az sshkey list`

- Show information about an SSH public key:

`az sshkey show --name {{name}} --resource-group {{resource_group}}`
