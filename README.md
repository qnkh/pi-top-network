# pi-top-network
 a website i once wanted to host

# setup

## reasonable setup
clone the repo. host the files with the static web server of your choice. if you're stupid, have node.js installed and do:
```
git clone https://github.com/qnkh/pi-top-network.git
cd pi-top-network
npm i -g http.server
http-server
```
your server will now be running at localhost:8080.

## unreasonable setup
the website was intended to be hosted on old hardware, so...
1. clone the repo somehow to your pi-top.
2. go to the directory of the repo in a terminal.
3. run `python3 -m http.server`.
4. your server is now running at localhost:8000.