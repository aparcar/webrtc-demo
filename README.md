# WebRTC Video Chat Demo

This project tries to create a simple video chat application using WebRTC and a Node.js server for signaling.

The code is based on [Google Codelabs webrtc-web
repository](https://github.com/googlecodelabs/webrtc-web), specifically
`step-05`. Some modification are added to have less critical security issues and
a slightly more realistic web interface for video chat.

## Server Installation

Run `npm install` to install the `socket.io` dependency.

## Usage

Modify the `config.js` to your needs. The default configuration uses a
`localhost` setup, however it's also possible to reach the signaling server over
the network.

Once the server is running, open the `index.html` file in a browser.

## License

Since this is based on Google Codelabs, the original license is Apache 2.0.
