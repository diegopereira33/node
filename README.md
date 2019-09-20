# NODE

Testing Technology Applicability. 



#### HELLO WORLD

###### 1. Crie arquivo .js

```js
var http = require('http');

http.createServer(function (req, res) {
  res.writeHead(200, {'Content-Type': 'text/plain'});
  res.end('Hello World!');
}).listen(8080);
```

###### 2. Instala npm

*npm install*

###### 3. Execute o arquivo .js

*node app.js* 

