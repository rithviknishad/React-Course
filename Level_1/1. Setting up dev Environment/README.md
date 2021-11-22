# Setting up the Development Environment

- [Setting up the Development Environment](#setting-up-the-development-environment)
  - [Getting Started](#getting-started)
  - [Install Git](#install-git)
  - [Install Node.js](#install-nodejs)
      - [For Mac](#for-mac)
      - [For Ubuntu](#for-ubuntu)
      - [All Users](#all-users)
  - [Install VSCode | IDE](#install-vscode--ide)
  - [Install VSCode Extensions](#install-vscode-extensions)

## Getting Started

We recommend using a Linux or Mac OS X machine for development. If you're on Windows you can use WSL (Windows Subsystem for Linux) to run Linux commands on Windows. 

## Install Git

To install git on your system, follow the instructions on the [git website](https://git-scm.com/downloads).

If you are on a Mac, you can also install git using [Homebrew](https://brew.sh/).

If you are on Ubuntu or any other Debian based OS, you can install git using the following command:

``` 
    sudo apt-get install git 
```


## Install Node.js

#### For Mac

If you have home brew installed, you can install node using the following command:

    brew install node

This would install nodejs and npm. npm stands for node package manager and is used to install node packages.

#### For Ubuntu

You can simply use the apt-get command to install node.

    sudo apt-get install nodejs

This will install nodejs and npm. npm stands for node package manager and is used to install node packages.

#### All Users

You can verify that node and npm are installed correctly by running the following commands:

    node -v
    v15.2.0

    npm -v
    7.0.10

Your version might vary slightly.

## Install VSCode | IDE

We reccommend you to use [VSCode](https://code.visualstudio.com/) as your development environment, but you can use any other editor or IDE you like. Other recommended IDEs for React include:  
- [WebStorm](https://www.jetbrains.com/webstorm/)
- [Atom](https://atom.io/)
- [Sublime Text](https://www.sublimetext.com/) etc.

You can download and install the [latest version of VSCode](https://code.visualstudio.com/Download) for your platform.


## Install VSCode Extensions

To install VSCode extensions, open the VSCode menu (`cmd + ,` on Windows, `ctrl + ,` on Linux/Mac). Then, search for the extension you want to install and click the install button.

For your React development environment, we recommend the following extensions:
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [ESLint React](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint-react)
- [ESLint React JSX](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint-react-jsx)

## Install React Dev Tools

You can optionally Install React Developer Tools using the following command:

- [React Developer Tools for Chrome](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
- [React Developer Tools for Firefox](https://addons.mozilla.org/en-US/firefox/addon/react-developer-tools/)