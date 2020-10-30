## Google Home Starter Guide

### Getting Started
If you haven't already, install git and node.js on your device.

1. Fork or clone this repository onto your device. 
2. In your console, run `npm install` to install the required components.
3. Run `touch .env` to create your hidden, gitignored environment config file.
4. In .env, configure your environment as follows:
    * `DEV=`  `TRUE` if you are on desktop, or `FALSE` if you are on your raspberry pi
    * `PORT=` `8000` for development, `80` or `443` for HTTP or HTTPS
    * `PASS=` Whatever you want your password to be
5. Run `npm start` to launch the server

When you make a POST request to the server, follow this structure: 
`http://ipaddresshere/API/switches/sw1?password=yourpasswordhere`
