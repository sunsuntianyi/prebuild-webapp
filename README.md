# prebuild-webapp
This is a pre-build version of the mlWebapp. You just have to download from the docker respo and start using it.

Installation Instruction:

Step 1: Install Docker

Mac: https://docs.docker.com/docker-for-mac/install/

Windows: https://docs.docker.com/docker-for-windows/install/

Ubuntu: https://docs.docker.com/install/linux/docker-ce/ubuntu/


Step 2: Install Docker-Compose version 1.22.0 

    curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" > ./docker-compose
    sudo mv ./docker-compose /usr/bin/docker-compose
    sudo chmod +x /usr/bin/docker-compose


Step 3: Open Terminal, cd to the and file dir, run the "docker-compose.yml" file in this respo

    sudo docker-compose build
    sudo docker-compose up -d


# Your local webapp can then be accessed at 0.0.0.0:3000
