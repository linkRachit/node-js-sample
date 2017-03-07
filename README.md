# Node.js Sample [Project live link](http://node-js-sample-linkrachit.herokuapp.com/)

## Sample

This Sample of a web server written in Node.js to setup/start project in raw Node.js.

```console

  const http = require('http');

  const hostname = '127.0.0.1';
  const port = 3000;

  const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Sample Test\n');
  });

  server.listen(port, hostname, () => {
    console.log(`Server running at http://${hostname}:${port}/`);
  });

```

## Usage

```console

  > node [options] [v8 options] [index.js | -e "index"] [arguments]

```
In this case:

```console

  > node index

```
not compulsary, to use .js extension while running node.js application. 

## User entry required

```console

  const hostname = '127.0.0.1';
  const port = 3000;
  -----------------------------
  res.end('Sample Test\n');
  -----------------------------
  console.log(`Server running at http://${hostname}:${port}/`);

```