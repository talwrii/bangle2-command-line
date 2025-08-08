# Connecting to the bangle.js from the command-line
The [suggested mode](https://www.espruino.com/Bangle.js+Development) of development for the bangle.js 2 is the espruino web IDE - but I tend to dislike developing browser and like the command-line.

You can, instead, use espruino from the command-line to bring up a shell to your bangle device.


To do this run:

```
mkdir bangle
cd bangle
npm install espruino
npx espruino -d Bangle.js
```

This will bring up a REPL with tab completion. The Bangle object represents your watch.
