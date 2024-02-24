# Getting Started with npm

npm (Node Package Manager)! npm is a powerful tool for managing 
* JavaScript packages
* dependencies
* Node.js development.

This guide will cover installation, basic commands, and common use cases.

## Installation

### Windows

To install npm on Windows, use npm's official installer, which comes bundled with Node.js.

1. Download the latest version of Node.js from [nodejs.org](https://nodejs.org).
2. Run the downloaded installer and follow the installation instructions.
3. Time to varify, open a command prompt or PowerShell window and verify npm installation by running:

```bash
npm --version
```


### macOS

On macOS, you can install npm using Homebrew, a popular package manager for macOS.

1. Homebrew installation instructions a [brew.sh](https://brew.sh).
2. Open Terminal and run the following command to install Node.js and npm:

```bash
brew install node
```

### Linux
On linux, you can use ur system package manager. very ezzz


#### distros like Ubuntu
```bash
sudo apt install nodejs npm
```

#### arch
i use arch btw.

```bash
sudo pacman -S nodejs npm
```

* varify installation by runing
```bash
npm varsion
```

### android/termux
android is basically a closed linux. You can execute commands on android using termux (u dont need to root)
you can practice node or npm even if you are out, you dont need to carry laptop everywhere

1. learn basic termux
2. use pkg install:
```bash
pkg install nodejs npm
```
remember Errors may Occur



## Basic Commands

### Initializing a Project

To initialize a new npm project, create a new directory for your project and run:

```bash
npm init
```

it will create a ```package.json``` file, used for
* Dependency Management
* Setting-up Dev env
* Version management
* many more


### Installing Packages

To install packages, use the `npm install` command followed by the package name. For example:

```bash
npm install jest
```
