# hub

All your notifications in one place. **hub** is an only platform which serves you all the notification and messages you are getting from all the different services and sites. **hub** also strictly differentiates between spaces you create. You can for example create a space "Business" and a "Private" space. 

Sadly this project of mine is very new and still in development. However, as soon as it is live, you will find a link here.

PS: **hub** won't be the final name for publishing either.

## Motivation

The motivation of this project was the wish for a location, where you have all your notifications and messages. Including from your phone, from work, from an RSS feed or whatever. It should all be in one place.

## Security

I know what you're thinking: "That sounds great and all but it isn't secure to store everything in one place."
And you are absolutely right. That's why **hub** doesn't save the notifications and information that you are recieving and sending. The application directly contacts the API of the service provider for you. Now you might say: "What about my login credentials and contacts that I will be saving?" Good question. The app encrypts everything important on your own device with your credentials and then sends the encrypted data to our servers to store. Your configuration, that is the way that you personalised your **hub** is stored without credentials and unecrypted. That you can still have your old hub and you can save your config to disk or share if you'd like to. The credentials however, are only stored encrypted. That way no one can read your data, except they have your login information. Which also means that it is so secure, that when you forget your login you will have to connect all the accounts again by reentering all the logins to your services.

This is the current plan. Most of it is not implemented yet. Heck I don't even have a server.
But I will go more into detail once it's all set and done.

It is also planned that your login is not just username and password, but also two-factor authentication when wanted or even fingerprint and facial recognition where it is possible.

## Contributors

In the future I am definately looking to collaborate with some colleagues of mine, but at the moment I would like to start this project myself.

## Tools

This web applicaiton was built with the following tools:



## License

This software is opensource and is provided as is.

