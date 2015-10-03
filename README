# UnhostedJS

Experimental runtime for unhosted javascript applications.

# How it works

Apps are being passed in URL query param and evaluated by the runtime.

# How to test

Encode your application with base64 and pass it on `run` query param to v1.html.

Example application:

```js
console.log('Hello world');
```

Encoded app should look like this: `Y29uc29sZS5sb2coJ0hlbGxvIHdvcmxkJyk6`

So UnhostedJS URL path is: `/v1.html?run=Y29uc29sZS5sb2coJ0hlbGxvIHdvcmxkJyk6`


# WARNING

It is unsafe to use this application. It uses Javascript eval and opens your
browser for XSS attacts.
