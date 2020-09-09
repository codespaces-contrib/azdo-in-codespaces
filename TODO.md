To make this repo template a reality, we'd need to do the following things (all of which is work we want to do anyways):

1. :runner: Add support for the `workspaceFolder` property in `devcontainer.json`, so that Visual Studio would automatically open the sub-repo folder upon connecting to the Codespace

In order to make this flow a little bit nicer, we could also do the following things over time:

1. Enhance GitHub repo templates to accept parameters when creating a derived repo. This would allow the Azure DevOps repo to be specified via a web form, as opposed to manually editing the `devcontainer.json` file directly.

1. Provide some tooling (perhaps inside of Visual Studio?) to allow you to create new GitHub repos from a template

1. Provide a Git credential manager ("GitHub Keychain") in github.com to allow management of the Codespace from the web
