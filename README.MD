# Episode 002: A Simple Node Deployment

This video has us deploying our first Node.js application to Azure using VS Code and the Azure App Service Extension. We're deploying the code from the Node.js getting started guide...

```js
const http = require('http');

const hostname = '0.0.0.0';
const port = process.env.PORT || 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader('Content-Type', 'text/plain');
  res.end('Hello World!\n');
});

server.listen(port, hostname, () => {
  console.log(`Server running at http://${hostname}:${port}/`);
});
```

## The Video

You can watch this video on YouTube. A written transcript is also availale in this repo along with the video in the code.

## Questions? Concerns?

Feel free to ask questions in our Issues List but please please include which episode you're referring to.

