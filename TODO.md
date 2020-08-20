To make this repo template a reality, we'd need to do the following things:

1. Add support for the `workspaceFolder` property in `devcontainer.json`, so that Visual Studio would automatically open the sub-module folder upon connecting to the Codespace

1. Add support for the `codespaces.recurseSubmodules` property, to indicate that we need to initialize the submodules after cloning.

    > Note: We should discuss with VS Code if this makes sense as a general property.

1. Ensure that the Git credentials proxying works for Azure DevOps in Visual Studio

In order to make this flow a little bit nicer, we could also do the following things:

1. Enhance GitHub repo templates to accept parameters, so that the Azure DevOps repo could be specified in a nice "form", as opposed to manually editing the `.gitmodules` file