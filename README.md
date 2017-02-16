# Node.js Sample

##Sample

Sample of a web server written in Node.js to setup project raw Node.js.

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

##Usage

```console

node [options] [v8 options] [index.js | -e "index"] [arguments]

```
In thus case:

```console

node index

```