# BotFramework WebChat IE11 Bug Sample Project
This project is built to reproduce the issue of the BotFramework Webchat embed not working with IE11

To reproduce: replace the placeholders in botframework-ie11-bug.html with your user name and direct line secret.  Opening in Chrome or FireFox, the component works without issue.  In IE11 there are a number of console errors:

```
TypeError: Object doesn't support property or method 'startsWith'
   {
      [functions]: ,
      __proto__: { },
      description: "Object doesn't support property or method 'startsWith'",
      message: "Object doesn't support property or method 'startsWith'",
      name: "TypeError",
      number: -2146827850,
      stack: "TypeError: Object doesn't support property or method 'startsWith'
   at Anonymous function (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:109302)
   at Anonymous function (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:109283)
   at R (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:109264)
   at Anonymous function (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:942537)
   at Anonymous function (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:943694)
   at h (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:941412)
   at Yi (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:293385)
   at Anonymous function (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:328146)
   at Ha (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:327525)
   at Ga (https://cdn.botframework.com/botframework-webchat/latest/webchat.js:1:332528)"
   }
```
