# Start checklist

1. Linux (ubuntu, mint or other debian distribution)
2. [Google Chrome](#Google Chrome)
3. [Git](#Git)
4. [Code](#Code)
5. [Gimp](#Gimp)
6. [NVM](#NVM)
7. [Mongo](#Mongo)

# Git

## Installation

    sudo apt-get install git

## Configuration

    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
    git config --global push.default simple

# Gimp

## Installation

    sudo add-apt-repository ppa:otto-kesselgulasch/gimp
    sudo apt update
    sudo apt install gimp
    sudo apt install gimp-plugin-registry gimp-gmic

# NVM

## Installation

1. Install NVM `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash`
2. After installation close the terminal and open again
3. Verify installation with `command -v nvm`
4. Install the latest version of node `nvm install node`
5. For more info visit the [github repo](https://github.com/creationix/nvm)