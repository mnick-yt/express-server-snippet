# express-snippet README

This is the README for your extension "express-snippet". 

## Features

This extension will generate Boilerplate code for Express JS server.
Just Type ```!express``` and press enter.
it will generate :

```
const express = require('express');
const app = express();
const port = 3000;

app.use(express.json());

app.get('/', (req, res) => res.send('Hello World!'));

app.post('/', (req, res) => {
  console.log(req.body);
  res.json({ success: true });
});

app.listen(port, () => console.log(`Example app listening at http://localhost:3000`));

```

## Requirement


## Known Issues

none
