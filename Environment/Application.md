Environment setup - Application
=========

Here we expose the specific tools and technologies **needed** for developing the [client app](https://github.com/AdrianDeLasSierras/Application).

Setup
-------------

1. Install [Node.js](https://nodejs.org/en/).

2. Clone the [client app](https://github.com/AdrianDeLasSierras/Application) repo.

3. From the command line execute:
  ```shell
  $ npm config set spin=false
  $ npm config set loglevel=http
  $ npm install -g gulp
  $ npm install -g bower
  $ cd [Client app root folder]
  $ npm install
  $ bower install
  ```

License
-------------

Copyright (c) 2015 - 2015 Augusto Altman Quaranta <augusto.altman@gmail.com>, Julia Lima <julia.lima.dg@gmail.com>, Ricardo Fretes <rgfretes@gmail.com> et al Licensed under the MIT license.
