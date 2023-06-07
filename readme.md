# vscode-server-templatev
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
