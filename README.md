# Docker-and-Linux-Security-Lab
This repository contains the scripts and configurations used in the lab where I learned to manage Docker containers and configure Linux security settings with PAM.
Lab Details:

Task 1: Docker Container Management

Created and ran a Docker container based on the nginx image.

Mapped port 80 on the host to port 80 on the container.

Developed bash scripts to start and stop the container (container-start.sh and container-stop.sh).

Task 2: PAM Configuration for User Access

Edited the PAM configuration for the su utility.

Restricted access to the su command to members of the wheel group.

Allowed users in the wheel group to use su without entering a password.

Files Included:

container-start.sh - Bash script to start the myapp container.

container-stop.sh - Bash script to stop the myapp container.

su PAM configuration - The configuration file for PAM (/etc/pam.d/su), modified to restrict su to the wheel group.
