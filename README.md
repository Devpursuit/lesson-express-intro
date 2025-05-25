# 🌐 Spin Up an Express Server

Now that Node is set, let’s create a web server using Express!

## 🔧 What You’ll Do

- Install Express.
- Create a basic HTTP server.
- Return a simple message in the browser.

## ✅ Activity Instructions

1. Run `npm init -y` to create a package.json.
2. Install Express:

```
npm install express
```

3. Create a file called `server.js` and add:

```js
const express = require('express');
const app = express();

app.get('/', (req, res) => {
  res.send('Hello, world from Express!');
});

app.listen(3000, () => console.log('Server running on http://localhost:3000'));
```


4.Run the server:

```
node server.js
```

5. Use the Gitpod Preview Tab or open port 3000 in a new tab.

## 🎯 Success Criteria

* You installed and imported Express.

* You created a working server.

* You saw your message in the browser!

# ⚠️ Tip
If port 3000 doesn’t open automatically, look for the "Ports" tab in Gitpod and open it manually.
