# Workbot chat client

This client is designed to suit a server like https://github.com/Citizen-AI/workbot-webchat-server.

I find [autoreload-server](https://www.npmjs.com/package/simple-autoreload-server) a convenient way of hosting the client locally.

Use the `server` parameter to override the hardcoded (in `client.js`) server url. E.g.:

> `http://localhost:8080/index.html?server=localhost:3000`

Use the `query` parameter to start the conversation from a particular point. E.g.:

> `http://localhost:8080/index.html?query=What do I do if I've been fired?`


## Thanks to

* https://github.com/howdyai/botkit-starter-web, which this is based on
* http://showdownjs.com/, which turns in-message links into clickable links
* [Patricia Goldweic](https://github.com/howdyai/botkit-starter-web/issues/35#issuecomment-425201475), for a work-around for the [Firefox column-reverse bug](https://bugzilla.mozilla.org/show_bug.cgi?id=1042151)