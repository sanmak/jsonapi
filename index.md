# jsonapi.co

# https://www.jsonapi.co/

### [jsonapi](https://www.jsonapi.co/) is a Hosted API's platform with 24 * 7 availability to test your code for free 🙌

### Why do world need such platform ?

Yes, definitely. As a developer/programmer/coder when i'm developing any frontend or mobile app, we need api's to integrate. 
Generally developer uses mock json structure in place of api's or create local server's to test end-to-end integration.

Problem with this approach is, there can be tons of issues that can pop up while deploying this app. Because it was never tested with a hosted api, things are bound to break.

### Solution

To solve it, [jsonapi](https://www.jsonapi.co/) is developed to save time, effort and energy. With our hosted api's which covers extensively all set of HTTP methods, error handling, datasets, json structure, it helps to keep our focus more on app development and api painpoints is handled by [jsonapi](https://www.jsonapi.co/). Code snippets added in website to help understand api's better

### Api's

Visit [jsonapi.co](https://www.jsonapi.co/)

## Code snippet

```
Request
var settings = {
  "url": "https://api.jsonapi.co/rest/v1/user/register",
  "method": "POST",
  "timeout": 0,
  "headers": {
    "Content-Type": "application/json"
  },
  "data": JSON.stringify({"name":"abc","email":"abc@gmail.com","password":"password"}),
};

$.ajax(settings).done(function (response) {
  console.log(response);
});
```
```

Response 
{
    "success": true,
    "data": { 
      "token": "8ef2fe1b-b6cd-4395-9cb4-9810050bb2e2"
    },
    "error": null
}
```


### What do we offer
- It's free
- Use it for demo / tutorial / prototyping
- API's with most commonly used functionalities
- Faker data which covers all the possible use cases
- HTTP status codes
- GET, POST, PUT, PATCH, DELETE, covered it all
- Use it for Frontend, Microservice or App development
- Ready API's with 24 * 7 availability to test your code

### Security

We do not store any data you send us in API's. Running on HTTPS from day 1.

### Our Environment

We are running on [AWS](https://aws.amazon.com/). Implies, high availability. Domain from [GoDaddy](https://in.godaddy.com/)

### About Us
jsonapi.co is designed for the developers by the developers. We believe any sort of web/app development should always prosper and enrich with all the data around us. We will take care of data, and continue to add more for the society, and developers like you will keep building super apps that our world needs

### Get Help
For any help, feeback, feature requirement or even for a sip of coffee / tea  / beer , we are here to serve you.
- [Gitter chat](https://gitter.im/jsonapiapp/community#)
- [Twitter](https://twitter.com/jsonapiapp)
- [Mail](mailto:jsonapiapp@gmail.com)

### Support us with your love
[Buy Me A coffee](https://www.buymeacoffee.com/jsonapi)
