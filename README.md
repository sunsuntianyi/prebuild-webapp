# prebuild-webapp
This is a pre-build version of the mlWebapp.

Installation Instruction:

Step 1: Install Docker

Mac: https://docs.docker.com/docker-for-mac/install/

Windows: https://docs.docker.com/docker-for-windows/install/

Ubuntu: https://docs.docker.com/install/linux/docker-ce/ubuntu/


Step 2: Install Docker-Compose

    sudo apt install docker-compose 


Step 3: Open Terminal, cd to the and file dir, run the "docker-compose.yml" file in this respo

    docker-compose build
    docker-compose up -d


# Your local webapp can then be accessed at 0.0.0.0:3000
