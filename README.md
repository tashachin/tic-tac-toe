# tic-tac-toe
Test project for studying React &amp; Node.js

## Installation Notes
I tried to set up my env to follow [React's tutorial](https://reactjs.org/tutorial/tutorial.html) but could not figure out how to install Node.js.
Whenever I entered `npm install -g create-react-app`, I'd get the following error log:

`npm ERR! Error: EACCES: permission denied, access '/usr/lib/node_modules'
npm ERR!     at Error (native)
npm ERR!  { Error: EACCES: permission denied, access '/usr/lib/node_modules'
npm ERR!     at Error (native)
npm ERR!   errno: -13,
npm ERR!   code: 'EACCES',
npm ERR!   syscall: 'access',
npm ERR!   path: '/usr/lib/node_modules' }`

This may have been due to trying to access something in Vagrant.

I found [Jean-Michel Feurprier's post](https://jmfeurprier.com/2015/10/02/how-to-install-node-js-with-ubuntu-and-vagrant-in-a-synced-folder/) on installing Node.js on Ubuntu/Vagrant but still ran into issues with it.