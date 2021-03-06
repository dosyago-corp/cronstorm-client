# Pocketwatch.js

Node.js client library for the Pocketwatch Timer API.

Pocketwatch Timers expose recurrent job scheduling as a service. 

You can use Pocketwatch Timers to create schedulers to issue HTTP requests at intervals as fine as 1 second, or as long as forever. Duration can be from 1 second to forever.

## Installing

```shell
  npm i --save @dosy/pocketwatch
```

If you're interested, you can take a look [at the package page on NPM](https://www.npmjs.com/package/@dosy/pocketwatch)

## Using

```js
  const pocketwatch = require('@dosy/pocketwatch');
```

## Provided functionality

The client library provides full access to the Pocketwatch API.

You can create and delete timers, refresh your API key and cancel your subscription.

Find out more about using the client library, or the API, [at our documentation portal](https://dosyago-corp.github.io/pocketwatch-api/)

## Getting access

If you haven't already, head to our [developer portal](https://api.pocketwatch.xyz/) to choose a monthly plan and generate a new secret API key. 

## Show HN

[Just posted it](https://news.ycombinator.com/item?id=17353486)

## Wrappers & Related Projects

- [kairoi](https://github.com/dosyago-corp/kairoi) Time-as-a-Service CLI (for Pocketwatch API)

