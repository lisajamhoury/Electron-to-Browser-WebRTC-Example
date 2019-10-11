# Electron to Browser Connection with WebRTC

This combines the [Electron Quick Start](https://electronjs.org/docs/tutorial/quick-start) with the [Realtime Communication with WebRTC](https://codelabs.developers.google.com/codelabs/webrtc-web/#0) tutorial from Codelabs.

It runs a Socket.io signal server, then a peer connection over webRTC between Electron and the browser. Electron serves the signal server. This currently runs over localhost. 

## To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/lisajamhoury/Electron-to-Browser-WebRTC-Example
# Go into the Electron application folder
cd Electron-to-Browser-WebRTC-Example/electron_app
# Install dependencies
npm install
# Run the Electron app — this will start the signaling server in Electron
npm start
# In a new command line window, go into the client folder
cd Electron-to-Browser-WebRTC-Example/browser_client
# Run a simple python server on your localhost 
# If python 2
python -m SimpleHTTPServer 
# If python 3
python -m http.server
```

## License

[CC0 1.0 (Public Domain)](LICENSE.md)
