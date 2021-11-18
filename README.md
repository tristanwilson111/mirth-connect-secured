# Mirth Connect / MariaDB / Vault

This project contains development files to create a secure Mirth environment capable of storing credentials securely while using Mirth.

## Requirements

To start ensure you have Docker Desktop installed and working on your machine. For development, VSCode and Git (Especially Git Bash) is highly recommended.

## Usage

To see this file in action, open this project in VSCode, hit "Ctrl+`" to open a new terminal session, and run "docker-compose up -d" to run our docker-compose.yml file. This will start downloading the official Mirth Connect, MariaDB, and Vault docker images to your machine, and run them in generated containers.

To watch the logs of all three services, use "docker-compose logs -f". This should allow you to view the running logs of each service combined. To exit the logs, use "Ctrl+C".

To kill and remove the services/containers, use "docker-compose down".

To view current running docker containers, use "docker ps".