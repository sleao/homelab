# Homelab

Self-hosted personal infrastructure running on Docker containers, with Ansible automation for provisioning and configuration.

## Overview

This repository contains all the configuration for my homelab environment, from initial machine provisioning to the containerized services running on it. The goal is to have a complete, versioned, and reproducible environment for hosting personal services focused on automation, media, productivity, and monitoring.

### Structure

```
├── ansible/          # Playbooks and provisioning configuration
└── services/         # Docker Compose files organized by category
    ├── applications/ # General applications and tools
    ├── arr-apps/     # Media automation stack
    ├── databases/    # Databases and storage
    ├── messaging/    # Messaging and communication
    ├── nginx/        # Reverse proxy and routing
    └── portainer/    # Container management
```

### Tech Stack

- **Containerization**: Docker + Docker Compose
- **Automation**: Ansible for provisioning and configuration
- **Networking**: Nginx as reverse proxy
- **Organization**: Services categorized for easy maintenance
- **Version Control**: Git for infrastructure as code

### How to Use

If you want to replicate this setup, adjust the Ansible variables at `ansible/group_vars/all/vars.yml` according to your environment.

## TODO

Install zsh, omz, zsh-autosuggestions and zsh-syntax-highlightning, copy .zshrc
