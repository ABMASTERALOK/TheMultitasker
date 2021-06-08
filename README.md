<div align="center">

# The Multitasker

##### A WhatsApp bot written in JavaScript and Node.js.

![forthebadge](https://img.shields.io/badge/Made%20with-Node.js-green)
![forthebadge](https://img.shields.io/badge/Made%20with-🥚-blue)


</div>


## Features

| (⌐■_■)☞|                Feature           |
| :-----------: | :--------------------------------: |
|       ✅       | Send Red Alerts 🚀 as message with (or without) location on GoogleMaps. |
|       ✅       | Owner can add and remove senders from sending groups (senders.json) straight from Whatsapp.     |
|       ✅       |     Create stickers from image 📷, video 🎥, gif 👾 or URL 🔗 just by sending them to the bot.          |
|       ✅       |     Send a random message from a given group to your chat.          |
|       ✅       |     Download content from Instagram straight to the chat          |
|       ✅       |     Download videos from Twitter straight to the chat          |
|       ✅      |     Get a random 🎲 meme from a set of subreddits you choose          |
|       ✅       |     Kick 🦶 a participant or all participants from group          |
|       ✅       |     Tag everyone in the group          |
|              |     More to come...?          |
<!-- |              |      | -->
## Dependencies
- [node.js](https://nodejs.org/en/download/) v14.16.0
- [wa-automate](https://github.com/open-wa/wa-automate-nodejs) v3.16.1
- [AbortController](https://github.com/mysticatea/abort-controller#readme) v3.0.0
- [hjson](https://hjson.github.io/) v3.2.2
- [puppeteer](https://github.com/puppeteer/puppeteer#readme) v9.1.1
- [video-url-link](https://github.com/catcto/video-url-link#readme) v0.1.4

## Installation
clone the project:
```
git clone https://github.com/eyalmichon/TheMultitasker.git
```
then inside the project folder use the following command to install required packages:
```
npm install
```
next, you'll need to create a sender file in json format and a config file in [.hjson](https://hjson.github.io/) format (exactly the same as JSON but lets you add comments) which you can use to save your group/private numbers and the URLs/Data for different functions safely without being part of the code.

## Running & Usage

```
npm start
```
scan the QR code and wow, you're done!
