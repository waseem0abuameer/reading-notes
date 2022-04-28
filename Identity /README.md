# Introduction to Identity on ASP.NET Core


## ASP.NET Core Identity:
- Is an API that supports user interface (UI) login functionality.
- Manages users, passwords, profile data, roles, claims, tokens, email confirmation, and more.


Users can create an account with the login information stored in Identity or they can use an external login provider. Supported external login providers include  __Facebook, Google, Microsoft Account, and Twitter__ .


## Microsoft identity platform is:

- An evolution of the Azure Active Directory (Azure AD) developer platform.
- Unrelated to ASP.NET Core Identity.


### ASP.NET Core Identity adds user interface (UI) login functionality to ASP.NET Core web apps. To secure web APIs and SPAs, use one of the following:

1. Azure Active Directory
2. Azure Active Directory B2C (Azure AD B2C)
3. IdentityServer4

### IdentityServer4 is an OpenID Connect and OAuth 2.0 framework for ASP.NET Core. IdentityServer4 enables the following security features:

a. Authentication as a Service (AaaS)
b. Single sign-on/off (SSO) over multiple application types
c. Access control for APIs
d. Federation Gateway


==========================================================
# ASP.NET Core 2.0 Authentication and Authorization System Demystified

There is a component that exists in ASP.NET Core that conjures up an enchanted shield that protects portions (or all) of your website from unauthorized access. Like many people, I have used this component from the beginning of my journey, but have never understood it. It was conjured up by a wizard and provided a magical barrier between my website and the world. That’s not how it really works, of course, but without the right knowledge, it might as well.

## Identity
Key to understanding how authentication works is to first understand what an identity is in ASP.NET Core 2.0. There are three classes which represent the identity of a user: Claim, ClaimsIdentity, and ClaimsPrincipal
## Claims
A Claim represents a single fact about the user. It could be the user's first name, last name, age, employer, birth date, or anything else that is true about the user. A single claim will contain only a single piece of information. A claim representing something about a user John Smith could be his first name: John. A second claim would be his last name: Smith.

``` C#
//This claim uses a standard string
new Claim("FullName","Dark Helmet");

//This claim type expands to 'http://schemas.xmlsoap.org/ws/2005/05/identity/claims/emailaddress'
new Claim(ClaimTypes.Email, "dark.helmet@spaceballs.com");

```
## ClaimsIdentity
An Identity represents a form of identification or, in other words, a single way of proving who you are. In real life this could be a driver's license. In ASP.Net Core, it is a ClaimsIdentity. This class represents a single form of digital identification.



![image](1.0.svg)