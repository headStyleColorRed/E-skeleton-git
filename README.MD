# E-skeleton-git


E-skeleton-git is a docker project that will deploy in seconds a git/register system with Node.js and MongoDB so you can use it for your projects.

In order to acces this git Api the endpoint should be:
- http://git:8888

You can search more of my E-skeletons docker projects and try to combine them in order to create a complete backend for your apps.
  - E-skeleton-IOs
  - E-skeleton-git
  - E-skeleton-web

### API use

Down here you have example code for the events that this server provides:



### Tech

E-skeleton-git uses a number of open source projects to work properly:

* [node.js] - Evented I/O for the backend
* [Express] - Fast node.js network app framework 
* [MongoDB] - Classified as a NoSQL database program

### Installation

E-skeleton-git requires [Docker](https://www.docker.com/) to run.

If you have Docker already installed in your pc, then proceed with this commands:

```sh
$ git clone https://github.com/headStyleColorRed/E-skeleton-git.git
$ cd E-skeleton-git
$ docker-compose up --build -d
```

For personal environments you may want to run

```js
$ npm run dev
// Instead of :
$ npm start
```

### Todos

 - Add testing
 - Add Load Balancer
 - Add Oauth
 - Add Recovery

License
----

MIT


**Free Software, Hell Yeah!**