# Node.js Sample 

## Sample

This Sample of a web server written in Node.js to setup/start project in raw Node.js.

```console

  const http = require('http');

  const hostname = '127.0.0.1';
  const port = (process.env.PORT || 3000);

  const server = http.createServer((req, res) => {
    res.statusCode = 200;
    res.setHeader('Content-Type', 'text/plain');
    res.end('Sample Test\n');
  });

  server.listen(port, () => {
    console.log(`Server running at port:${port}`);
  });

```

## Usage

```console

  > node [options] [v8 options] [index.js | -e "index"] [arguments]

```
In this case:

```console

  > node index
      or
  > npm start    

```
not compulsary, to use .js extension while running node.js application. 

## User entry required

```console

  const hostname = '127.0.0.1';
  const port = (process.env.PORT || 3000);
  -----------------------------
  res.end('Sample Test\n');
  -----------------------------
  console.log(`Server running at port:${port}`);

```

[## Click here to see the live project](http://node-js-sample-linkrachit.herokuapp.com/)