# Start checklist

1.  Linux (ubuntu, mint or other debian distribution)
2.  [Google Chrome](#google-chrome)
3.  [Git](#git)
4.  [Code](#code)
5.  [Gimp](#gimp)
6.  [NVM](#nvm)
7.  [Mongo](#mongo)

# Google Chrome

## Installation

1.  Download the latest version [from website](https://www.google.es/chrome/browser/desktop/index.html)
2.  Install from package manager

# Git

## Installation

    sudo apt-get install git

## Configuration

    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"
    git config --global push.default simple

# Code

## Installation

## Configuration

Pluggins to add:

* Wakatime
* vscode-icons
* Cobalt2
* Prettier
* Emmet
* npm intellisense
* path intellisense
* nodejs
* Auto Rename Tag
* Editor Config
* Eslint
* Gitlens
* React Frood Truck
* vscode-styled-components

## Settings

```javascript
{
    "files.autoSave": "onFocusChange",
    "vsicons.projectDetection.disableDetect": true,
    "workbench.colorTheme": "Cobalt2",
    "workbench.iconTheme": "vscode-icons",
    "editor.fontFamily": "'Droid Sans Mono', 'monospace', monospace, 'Droid Sans Fallback'",
    "editor.tabSize": 4,
    "vsicons.dontShowNewVersionMessage": true,
    "window.zoomLevel": 0.3,
    "path-intellisense.autoSlashAfterDirectory": true,
    "editor.wordWrap": "on",
    "editor.fontSize": 12,
    // "editor.fontFamily": "Fira Code",
    // "editor.fontLigatures": true,
    "editor.lineHeight": 20,
    "editor.letterSpacing": 0.3,
    "files.trimTrailingWhitespace": true,
    "editor.fontWeight": "400",
    "prettier.eslintIntegration": true,
    "editor.cursorStyle": "line",
    "editor.cursorBlinking": "blink",
    "editor.renderWhitespace": "all",
    "workbench.startupEditor": "newUntitledFile",
    "[javascript]": {
        "editor.tabSize": 2
    },
    "editor.formatOnSave": true
}
```

# Gimp

## Installation

    sudo add-apt-repository ppa:otto-kesselgulasch/gimp
    sudo apt update
    sudo apt install gimp
    sudo apt install gimp-plugin-registry gimp-gmic

# NVM

## Installation

1.  Install NVM `curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash`
2.  After installation close the terminal and open again
3.  Verify installation with `command -v nvm`
4.  Install the latest version of node `nvm install node`
5.  Install nodemon global `npm install -g nodemon`

For more info visit the [github repo](https://github.com/creationix/nvm)

# Mongo

## Installation

1.  Download the latest version of Mongo DB from [the website](https://www.mongodb.com/download-center#community)
2.  Extract MongoDB - change the name to mongodb (usually comes with a long name after extracting)
3.  Get inside the folder. You will see a folder called bin and files. At this level, create a folder called data and inside another one called db (data/db).
4.  From the folder /mongodb execute `$ ./bin/mongod --dbpath ./data/db --directoryperdb`
5.  Posible problems that appear: error code 38: https://stackoverflow.com/questions/6478113/unable-to-start-mongodb-local-server

## Shortcut

After installation, to start easily mongodb it's good to create a sh shortcut in the same folder where it's mongo:

1.  `$ nano start.sh`
2.  Paste `./bin/mongod --dbpath ./data/db --directoryperdb`
3.  Execute `$chmod +x start.sh`
4.  Form this moment you can just use the command to launch mongodb:
    `$./start.sh`

## Robo3T

Download the latest version of Robo 3T from [the website](https://robomongo.org/download)
