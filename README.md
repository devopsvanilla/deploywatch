# DeployWatch

## Description

**DeployWatch**🚀 is a Bash script designed to facilitate the deployment of `docker-compose.yml` files in the background while displaying the progress on the screen. It allows the user to decide whether to continue waiting, specify more time, stop monitoring (while the deployment continues in the background), or remove the deployment.

## Features

- **Background Deployment**: Runs the `docker-compose.yml` with the `-d` option to run in the background.
- **Progress Monitoring**: Displays the deployment progress on the screen.
- **Interactivity**: After a specified time, it asks the user whether to continue waiting, specify more time, stop monitoring, or remove the deployment.
- **Flexibility**: Allows the user to make decisions during the deployment process.
