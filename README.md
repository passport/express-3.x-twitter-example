## Sign in with Twitter using Express 3.x and Passport

This example demonstrates how to use [Express](http://expressjs.com/) 3.x and
[Passport](http://passportjs.org/) to authenticate users using Twitter.  Use
this example as a starting point for your own web applications.

## Install

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:passport/express-3.x-twitter-example.git
$ npm install
```

## Start

The example uses environment variables to configure the consumer key and
consumer secret needed to access Twitter's API.  Start the server with those
variables set to the appropriate credentials.

```bash
$ CONSUMER_KEY=__TWITTER_CONSUMER_KEY__ CONSUMER_SECRET=__TWITTER_CONSUMER_SECRET__ node server.js
```

You can see the example in action by opening a web browser and navigating to
[http://127.0.0.1:3000](http://127.0.0.1:3000/)
