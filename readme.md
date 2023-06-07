# vscode-server-template
this template will install 
- VS-Code
- R-studio
- jupyter-lab or server (depending on user choice). 

## Gitlab Setup

The startup script included in this template streamlines the process of setting up GitLab access with SSH and the GitLab plugin. Here's what it does:

1. Generates an SSH key specific to your system.
2. Adds the generated SSH key to your GitLab account.
3. Uses the SSH key to create a personal access token for the GitLab plugin.

## Rstudio

To facilitate the setup of RStudio without the need for a subdomain, Nginx is installed and utilized to serve RStudio.
 
***📝 Note :*** 

The start script set password user coder password to coder that means you can access the R studio as :
```
user: coder ;
pass: coder ;
```
## Usage:

First compress the files
```
tar -cvf coder_template.tar main.tf rstudio.tpl start_script.tpl
```
Then add the template using the interface or use the cli as you want.