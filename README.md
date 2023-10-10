# TrojanSourceDetection
Trojan Source UTF Vulernability Detection for CS4371 


## Setup

Download [Node.js](https://nodejs.org/)

Run `npm install -g yo generator-code`

Check VSCode version in settings or by running `code -v` in the terminal then navigate to `/trojansourced/package.json`

Find the part that looks like below
```json
  "name": "trojansourced",
  "displayName": "TrojanSourced",
  "description": "",
  "version": "0.0.1",
  "engines": {
    "vscode": "^1.82.3" 
  },
  "categories": [
    "Other"
  ],
```

Change `"vscode": "^1.82.3` to whatever version of VSCode you have, then navigate to `/trojansourced/extension.js`

Press the `F5` key and if prompted select `Extension Development Host`

A new VSCode instance should open, this instance has the extension loaded onto it. To test if this works as of now open the command pallet by going to the `View` tab and clicking `Command Palette`, then type: `>Hello World`. 

If everythings is done correctly you should see a message pop up in the bottom right saying `Hello World from HelloWorld!`

I used the VSCode [docs](https://code.visualstudio.com/api/get-started/your-first-extension) they are pretty good. The part about changing the vscode version I found online as mine was not working. I have added `package.json` to the `.gitignore`.