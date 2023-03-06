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
- Run the following command as a powershell Admin to install a windows build tool.
  `npm install --global --production windows-build-tools`

   `npm install --global node-gyp`
- Check [(https://github.com/coreybutler/nvm-windows#overview)] to learn more about using nvm to switch node versions.
- Run `npm install --global npm@7` to use npm version 7 for this project. 
- Reinstall the node modules by running `npm install --legacy-peer-deps`.
- Run `npm install -D postcss@8` to install postcss.

