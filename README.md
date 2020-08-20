# Azure DevOps in GitHub Codespaces

This repo template is built to help you get started developing your Azure DevOps-based codebases using GitHub Codespaces and Visual Studio ([context](https://gist.github.com/lostintangent/6f1841c965c9818bcf8a929acff4c799#file-readme-md)). To get started, simply perform the following steps 👍

**From GitHub:**
1. Click the `Use this template` button in order to create a new repo from this template. Name it whatever you'd like!
1. Open up the `.gitmodules` file and replace the `url` property to point at your Azure DevOps repo

  ```ini
  [submodule "workspace"]
	path = workspace
	url = https://dev.azure.com/<organization>/<project>/_git/<repo>
  ```
  
**From Visual Studio:**
1. Sign in with your GitHub account
1. Create a new Codespace using the repo you created above
1. If needed, you'll be prompted to sign into Azure DevOps
1. Connect to the Codespace, and start coding in the cloud 🚀 
