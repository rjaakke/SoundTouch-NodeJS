#Bose SoundTouch

Service to let all soundtouch devices in a network play the same music all the time. When a soundtouch device is turned on all other soundtouch devices is turned on and join a common group. Later if any device is turned off, all are turned off.

## Installation
Include this project into your project. 
```bash
npm install soundtouch --save
```
Start the server to make use of the HTTP API
```bash
git clone https://github.com/tibnor/SoundTouch-NodeJS.git
cd SoundTOuch-NodeJS
npm install
node persistantGroup.js
```

## Usage
Use for example forever to make it run forever (https://www.npmjs.com/package/forever)
