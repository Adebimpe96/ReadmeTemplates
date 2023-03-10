# Welcome to FABadminPortal &middot; [![v 0.1.0](https://img.shields.io/badge/version-0.1.0-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

FABadminPortal is a web application built completely with React-Typescript.

## Order of Contents:
- [Getting Started :](#getting-started-)
- [Project Setup `[For Windows users]` :](#project-setup-for-windows-users-)
- [Installation: ](#Installation-)

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
- [`node --version`](https://nodejs.org/en/download/)
  
  ```
  v18.14.2
  ```
- `npm --version`
  
  ```
  7.24.2
  ```
## Installation

Make sure you have the latest version of npm installed. 
Create ".env" configuration file from ".env.dist".
Create ".env.development", ".env.staging" and ".env.production" files with env variables if needed.
Go to the ```app``` directory, run ```npm install``` & then ```npm start``` and navigate to the development server:
 ```(http://localhost:3000/)```
Use "npm run build" script for making production build.
Use "npm run build:staging" script for making build for staging.


## Project Setup `[For Windows users]` :
- After cloning repo, switch to `develop` branch.
  
- Run these commands as an [`admin`](https://support.microsoft.com/en-us/windows/how-do-i-log-on-as-an-administrator-63267a09-9926-991a-1c77-d203160c8563#:~:text=An%20administrator%20is%20someone%20who,changes%20to%20other%20user%20accounts.) :
  - Install [windows build tool](https://www.npmjs.com/package/windows-build-tools).
    ```
    npm install --global --production windows-build-tools
    ```
  - Install [node-gyp](https://www.npmjs.com/package/node-gyp).
    ```
    npm install --global node-gyp
    ```
- Reinstall the node modules ignoring [peer dependencies](https://indepth.dev/posts/1187/npm-peer-dependencies)
    - ```
      npm install --legacy-peer-deps
      ```
- Run this command to install [`postcss`](https://www.npmjs.com/package/postcss).
    - ```
      npm install -D postcss@8
      ```
  

