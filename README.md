# instagram-api.js

## Instalation
To Use Api Install Package First
```bash
npm install instagram-api.js
yarn add instagram-api.js
```
A instagram api wrapper
## Usage
```js
const InstaClient = require("instagram-api.js")
const api = new InstaClient()
(async() => {
const userinfo = await api.user("mrbeast")
console.log(userinfo)
}()
