# Welcome to FABadminPortal &middot; [![v 0.1.0](https://img.shields.io/badge/version-0.1.0-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

FABadminPortal is a web application built completely with React-Typescript.

## Order of Contents:
- [Welcome to FABadminPortal · ](#welcome-to-fabadminportal--)
  - [Order of Contents:](#order-of-contents)
  - [Getting Started :](#getting-started-)
  - [Dependencies](#dependencies)
  - [Setting Up on your Local `[For Windows]` :](#setting-up-on-your-local-for-windows-)

## Getting Started :

Tools/Environments used as at writing:
- [`python --version`](https://www.python.org/ftp/python/2.7.18/python-2.7.18.amd64.msi)
```
Python 2.7.15 
```


- [`nvm --version`](https://github.com/coreybutler/nvm-windows/releases/download/1.1.10/nvm-setup.exe)
```
Running version 1.1.10.
```


## Dependencies
The needed dependencies and their versions can be found in the package.json file.



## Setting Up on your Local `[For Windows]` :
- Switch to the Most updated Branch `develop` in most cases.
- The Python version needs to be added to the environment variable path after which a window build tool will be installed. Run the following command as a powershell Admin,
  `npm install --global --production windows-build-tools`

   `npm install --global node-gyp`
- This project has node-saas as one of its dependencies which depends on nodeJS version.
- You can use `nvm current` to check the version of node you are using and `nvm use latest` to use the latest node version. 
- Ensure to have deleted the node modules and package lock files, then run `npm install --global npm@7` to use npm version 7 for this project. 
- Reinstall the node modules by running `npm install --legacy-peer-deps` to ignore peer dependencies and proceed with the installation.
- This project also expects postcss version 8 as peer dependency, run `npm install -D postcss@8` to insatll and save as a dev-dependency.

