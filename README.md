# Tour Golf

3D championship golf in the browser: three-click full swing, touch-and-feel chipping, green reading. Six courses, 9 or 18 holes, up to four players online.

## Play locally

No build step. Serve the folder and open it:

```
python3 -m http.server 8000
```

Then visit http://localhost:8000. (Opening `index.html` straight from disk won't work, because ES modules need a server.)

Online rooms run over Supabase Realtime (`relay-peer.js`); three.js loads from a CDN.

Split out of [MiniGolf](https://github.com/DoubleA-Digital/MiniGolf).
