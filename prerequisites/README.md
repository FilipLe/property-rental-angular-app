# Prerequisites
## node.js & npm Installation
### Checking version
Run the following command in Terminal to check node.js version:
```
node --version
```
If a version number is displayed, then node.js is <u>already installed</u> on the device.

### Installation
Otherwise, check [node.js documentation](https://nodejs.org/en/download/package-manager) for the installation links for select operating system <br>(or as attached in the link below).
```
https://nodejs.org/en/download/package-manager
```

### Alternative

Alternatively, run the following commands in Terminal:

#### MacOS
```
brew install node
```
#### Windows
```
winget install OpenJS.NodeJS
```

## Angular Installation
Once node.js and npm are installed, to install Angular run the following command in Terminal:
```
npm install -g @angular/cli
```

## Dependencies Installation
Run the following command in Terminal to install the dependencies needed to run the app:
```
npm install
```

## Installation for HTTP Communication
Use npm in Terminal command and install the following to configure HTTP:
```
npm install -g json-server
```

## Running the App
Please follow the following steps:
1. Terminal command to start build program:
```
ng serve
```
2. Terminal command to fire up database:
```
json-server --watch db.json
```
3. On web browser, open the following link:
```
http://localhost:4200
```