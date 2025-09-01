---
tags:
  - NodeJS
  - JavaScript
  - Programming
  - server
topics: NodeJS
---
- what is node?
	- Node definition
	- node is a runtime environment.
- what can node do?
- what can you build with node?
- JS
	- [String Interpolation](https://github.com/KvasirSG/node-notes/blob/master/String%20Interpolation%20in%20js.md)
	- string literals
	- datatypes
		- strings
		- no int
		- boolean
		- number
		- Object
		- BigInt
		- Symbol
		- Undefined
		- null

Js object example:
```js
const person = {
	name:"Jens" // key-value pair, key:value
}
```

[There is only one true way for RestFull](https://en.wikipedia.org/wiki/Richardson_Maturity_Model) -> [Richardson Maturity Model](https://github.com/KvasirSG/node-notes/blob/master/Richardson%20Maturity%20Model.md)

# What is Node.js
- JavaScript runtime built on Chrome’s V8 engine
- Lets you run JS **outside the browser**
- Event-driven, non-blocking I/O → great for I/O-heavy apps
## 🔹 How to run files
```bash
$ node app.js
```
Useful commands:
```bash
node -v
npm -v
npm init -y
```
## 🔹 Common use cases
- Web servers & REST APIs
- CLI tools
- Real-time apps (websockets)
- Microservices
## 🔹 Quick example (Express)
```js
import express from "express";
const app = express();

app.get("/health", (req, res) => res.json({ ok: true }));

app.listen(3000, () => console.log("Server on :3000"));
```
