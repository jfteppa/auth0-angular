# Auth0 and AngularJS

This AngularJS module will help you implement client-side and server-side (API) authentication. You can use it together with [Auth0](https://www.auth0.com) to add username/password authentication, support for enterprise identity like Active Directory or SAML and also for social identities like Google, Facebook or Salesforce among others to your web, API and mobile native apps.

[Auth0](https://www.auth0.com) is a cloud service that provides a turn-key solution for authentication, authorization and Single Sign On.

## Client Side Authentication

There are two ways of implementing signin/singup. One is using our [JavaScript SDK](https://github.com/auth0/auth0.js) which is just a wrapper to our API so you can build your UI on top or the other one is using [Login Widget](https://docs.auth0.com/login-widget2), which is a complete Login UI ready. You can check the following getting started guides:

 * [Getting Started: Javascript SDK](docs/jssdk.md)
 * [Getting Started: Login Widget](docs/widget.md)
 * [Getting Started: Redirect Mode](docs/redirect.md)

## Documentation
 * [Consuming a REST API](docs/backend.md)
 * [Advanced Routing Scenarios](docs/routing.md)
 * [FAQ](docs/faq.md)

### Development 
 * [How to run auth0-angular tests](docs/testing.md)


### Examples

The following [examples](examples) offer a good starting point for including Auth0 in your AngularJS application:

 * [Custom Login](examples/custom-login): Custom login form that uses Auth0 to authenticate.
 * [Custom Signup](examples/custom-signup): Custom signup plus extra fields added to the user profile on creation.
 * [Widget](examples/widget): A simple angular app doing auth with social and username/password using the Login Widget.
 * [API Authentication](examples/api-authentication): Call your protected API in the technology you want (Java, .NET, [Node.js](examples/api-authentication/nodejs) using Auth0 generated tokens.

Advanced scenarios:
 * [UI Router](examples/ui-router): A full featured example of ui-router with auth0-angular.
 * [Delegation Token](examples/delegation-token): Call two different APIs (with different client ids) from a single Angular App.
 * [RequireJS](examples/requirejs): An example of how to integrate auth0-angular with RequireJS.


## What is Auth0?

Auth0 helps you to:

* Add authentication with [multiple authentication sources](https://docs.auth0.com/identityproviders), either social like **Google, Facebook, Microsoft Account, LinkedIn, GitHub, Twitter, Box, Salesforce, amont others**, or enterprise identity systems like **Windows Azure AD, Google Apps, Active Directory, ADFS or any SAML Identity Provider**.
* Add authentication through more traditional **[username/password databases](https://docs.auth0.com/mysql-connection-tutorial)**.
* Add support for **[linking different user accounts](https://docs.auth0.com/link-accounts)** with the same user.
* Support for generating signed [Json Web Tokens](https://docs.auth0.com/jwt) to call your APIs and **flow the user identity** securely.
* Analytics of how, when and where users are logging in.
* Pull data from other sources and add it to the user profile, through [JavaScript rules](https://docs.auth0.com/rules).

## Create a free account in Auth0

1. Go to [Auth0](https://auth0.com) and click Sign Up.
2. Use Google, GitHub or Microsoft Account to login.
