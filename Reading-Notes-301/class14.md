# Authentication
![](https://www.okta.com/sites/default/files/styles/1640w_scaled/public/media/image/2020-10/Authentication_vs_Authorization.png?itok=uBFRCfww)

## What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization. The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another websiteâ€™s/serviceâ€™s logon. You then click on the button linked to the other website, the other website authenticates you, and the website you were originally connecting to logs you on itself afterward using permission gained from the second website.

## Give an example of what using OAuth would look like.
User AuthenticationÂ 
## How does OAuth work? What are the steps that it takes to authenticate the user?
The User Shows Intent.

- The Consumer Gets Permission.

- The User Is Redirected to the Service Provider.

- The User Gives Permission.

- The Consumer Obtains an Access Token.
![authorization & authentication](https://miro.medium.com/max/413/0*nrG185aDIksAga3W.jpg)

- The Consumer Accesses the Protected Resource.
## What is OpenID?
OpenID allows you to use an existing account to sign in to multiple websites, without needing to create new passwords

## What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?

>The Authorization Code Flow + PKCE is an OpenId Connect flow specifically designed to authenticate native or mobile application users. This flow is considered best practice when using Single Page Apps (SPA) or Mobile Apps. PKCE, pronounced â€œpixyâ€ is an acronym for Proof Key for Code Exchange.

## Authorization and Authentication flows
![](https://miro.medium.com/max/1838/1*ULF38OTiNJNQZ4lHQZqRwQ.png)


## What is Device Authorization Flow?

>The OAuth 2.0 Device Authorization Grant (formerly known as the Device Flow) is an OAuth 2.0 extension that enables devices with no browser or limited input capability to obtain an access token. This is commonly seen on Apple TV apps, or devices like hardware encoders that can stream video to a YouTube channel.

## What is the difference between authorization and authentication?
Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.