# Azure DevOps in GitHub Codespaces

This repo template is built to help you get started developing your Azure DevOps-based codebases using GitHub Codespaces. To get started, simply perform the following steps:

**From GitHub:**
1. Click the `Use this template` button in order to create a new repo from this template 👍
1. Open up the `.gitmodules` file and replace the `url` property to point at your Azure DevOps repo

  ```ini
  [submodule "workspace"]
	path = workspace
	url = https://dev.azure.com/<organization>/<project>/_git/<repo>
  ```
  
**From Visual Studio:**
1. Create a new Codespace using the repo you created above
1. If needed, you'll be prompted to sign into Azure DevOps
1. Connect to the Codespace, and start coding in the cloud 🚀 
