# Learning log

## Git 

- GitHub no longher accepts account passwords for Git Pushes. 
- Configured SSH autheticationusing an Ed25519 key. 
- Learned the difference between local and remote branches. 
- Used git pull --rebase to reconcile diverget history. 

## Docker

- Dockkerfile defines how an image is built. 
- Docker image vs container. 
- Port mapping: 8080:80.
- Rebuilt and replaced containers.

## Linux

- SSH access to Ubuntu server.
- Linux filesytem structure. 
- File permissions. 
- systemd services

## GitHub Actions 

- YAML workflow symtex.
- Sel-hosted runners. 
- Workflow triggers.
- Jobs and steps.
- Automated Docker deployment. 

## Trubbleshooting 

- Workflow inicially failed because of YAML indentation. 
- Workflow inicially queued because the runner process wasn't running (listening). 
- COnverted the runner to a systemd service so it starts automatically.  