# vfox-azure-functions-core-tools

[vfox](https://github.com/version-fox/vfox) plugin for [Azure Functions Core Tools](https://github.com/Azure/azure-functions-core-tools).

Azure Functions Core Tools provides a local development experience for creating, developing, testing, running, and debugging Azure Functions.

## Usage with mise

```bash
# Install a specific version
mise install azure-functions-core-tools@4.5.0

# Use in current shell
mise use azure-functions-core-tools@4.5.0

# Run func
func --version
```

## Usage with vfox

```bash
# Add the plugin
vfox add azure-functions-core-tools

# Install a version
vfox install azure-functions-core-tools@4.5.0

# Use the version
vfox use azure-functions-core-tools@4.5.0
```
