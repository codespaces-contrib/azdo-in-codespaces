To make this repo real, we'd need to do the following things:

1. Add support for the `workspaceFolder` property in `devcontainer.json`, so that Visual Studio would automatically open the sub-module folder upon connecting to the Codespace
1. Add support for the `codespaces.recurseSubmodules` property, to indicate that we need to initialize the submodules after cloning