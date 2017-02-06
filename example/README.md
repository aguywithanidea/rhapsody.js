## napster.js example app using Jook.me

### Getting Started

You must have a developer account to continue.  Go to [developer.napster.com](https://developer.napster.com) and register for an account if you don't already have one.  

Once logged in, create your application and set the following as the callback url for your application:

```
http://localhost:2000/authorize
```

In `server.js` replace the `apiKey` and `apiSecret` variable placeholder values with your application's credentials.  In `client.html` replace the `API_KEY` variable placeholder value with your application's API Key.

This application requires node.js. If you have not previously installed it please follow the instructions at [nodejs.org](https://nodejs.org). Then run the following commands in the example app directory.

```
npm install
```

### Running the Application

Ensure that `napster.js` is copied into the sample app directory, or update `client.html` to point to where you''ve installed `napster.js` file.

Now you should be ready to run the app. From inside the example app directory run:

```
node server.js
```

That's it! Once the application is running you can navigate in the browser to [localhost:2000](http://localhost:2000).

NOTE: Make sure Flash is supported in your browser.
