To make this repo template a reality, we'd need to do the following things:

1. Add support for the `workspaceFolder` property in `devcontainer.json`, so that Visual Studio would automatically open the sub-module folder upon connecting to the Codespace

1. Add support for the `codespaces.recurseSubmodules` property, to indicate that we need to initialize git submodules after cloning.

    > We should discuss with VS Code if this makes sense as a general property.

1. Ensure that the Git credentials proxying works for Azure DevOps in Visual Studio. This should work, but there may be bugs 😄

In order to make this flow a little bit nicer, we could also do the following things over time:

1. Enhance GitHub repo templates to accept parameters when creating a derived repo. This would allow the Azure DevOps repo to be specified via a web form, as opposed to manually editing the `.gitmodules` file directly.