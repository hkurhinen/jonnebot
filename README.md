# JonneBot
Simple IRC-bot framework

## Features
* Plugin based system (see wiki)
* Users database
* More to come

## Todo
* This Todo
* Documentation & examples

## Plugins (see the wiki)
* Basic (this MUST be enabled)
* User
* Reddit link poster

## Installing
1. `git clone https://github.com/jeeukko/jonnebot`
2. `npm install`
3. Rename `jonnebot-template.db` to `jonnebot.db` and add users
4. Rename `config-template.json` to `config.json` and edit to wanted
5. If you want use plugins, add them to `config.json` file (and edit `plugins/<plugin name>/config.json` file if needed)
6. `node index.js` or `nodejs index.js` or PM2 etc...
