# NO LONGER MAINTAINED/FUNCTIONAL

Chatterino no longer supports adding IRC channels and Kick has likely changed their API. This repo is archived and will receive no more support.

# KickProxy

Scuffed IRC Kick Proxy. Only supports reading messages and **not sending** them. xQc's stream is hardcoded in,
so the provided channel for the IRC connection does nothing. Meant to be used in Chatterino:

---

## How to setup

1. Install [Node.js](https://nodejs.org/en/download/)
2. Download the zip file

   ![image](download.png)

3. Extract the zip file
4. Open a terminal in the extracted folder
5. Run `npm install`
6. Run `npm start`
7. Add a new IRC connection in Chatterino with the following settings:

   **MAKE SURE SSL IS UNCHECKED**

   ![image](chatterino.png)

---

## Its not working!

1. Make sure you have the latest version of Node.js installed
2. Make sure you have IRC connections enabled in Chatterino (in settings)
3. Make sure you have the correct settings in Chatterino (see above)
4. If you stop recieving messages, restart the proxy and reconnect in Chatterino with CTRL + F5

## I can't see emotes

Unfortunately Chatterino's IRC channels do not allow for emotes (https://github.com/Chatterino/chatterino2/issues/1378), so Kick and 7TV emotes cannot be  viewed through the proxy
