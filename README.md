# Node Boilerplate
A template I use for Node projects. It comes with Swig, Mongoose, and Express already included. This is modified from the default Express project generator. To run:

```bash
$ npm install
$ npm start
```

It also comes with support for Nodemon, which will monitor code changes and automatically restart the server. To use Nodemon, run this:

```bash
$ npm install nodemon -g
$ nodemon
```

The project defaults to run on port 3000. If you'd like to change it, simply set the environment variable:

```bash
export PORT=8000
```