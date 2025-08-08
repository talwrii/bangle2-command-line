# Connecting to the bangle.js from the command-line
**@readwithai** - [X](https://x.com/readwithai) - [blog](https://readwithai.substack.com/) - [machine-aided reading](https://www.reddit.com/r/machineAidedReading/) - [📖](https://readwithai.substack.com/p/what-is-reading-broadly-defined
)[⚡️](https://readwithai.substack.com/s/technical-miscellany)[🖋️](https://readwithai.substack.com/p/note-taking-with-obsidian-much-of)

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

## Running a script
You can write code in a script and send the entire script to the bangle with:

```
espruino -d Bangle.js script.js
```

## About me
I am **@readwithai**. I create tools for reading, research and agency sometimes using the markdown editor [Obsidian](https://readwithai.substack.com/p/what-exactly-is-obsidian).

I also create a [stream of tools](https://readwithai.substack.com/p/my-productivity-tools) that are related to carrying out my work.

I write about lots of things - including tools like this - on [X](https://x.com/readwithai).
My [blog](https://readwithai.substack.com/) is more about reading and research and agency.
