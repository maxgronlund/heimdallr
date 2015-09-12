# Heimdallr
[Heimdallr](https://en.wikipedia.org/wiki/Heimdallr "Heimdallr")

* Heimdallr makes it easy to build phoenix web applications with features related to user accounts
* Heimdallr is a user authorization and social integration framework for [Phoenix](http://phoenixframework.org "Phoenix").
* Heimdallr is easy to customize and style

### Background / need
I'm planning to make a port of DigiRAMP. On DigiRAMP users can signup with social accounts like Facebook Twitter etc
Users can also link multiply signups to one account. This way they can post directly to their social accounts and receive money true Stripe. I have riped off the specs from Devise.

---
### Roadmap

1. Throw in idears suggestions and needs
2. Investigate what's out there and can it be used (addict)
3. Find a starting point and make something simple stupid


Should be composed of multiply modules: Inspired by Devise (Rails gem)


* Encrypts and stores a password in the database to validate the authenticity of a user while signing in. The authentication can be done both through POST requests or HTTP Basic Authentication.
* oAuth2  support.
* Sends emails with confirmation instructions and verifies whether an account is already confirmed during sign in.
* Resets the user password and sends reset instructions.
* Handles signing up users through a registration process, also allowing them to edit and destroy their account.
* Manages generating and clearing a token for remembering the user from a saved cookie.
* Tracks sign in count, timestamps and IP address.
* Expires sessions that have not been active in a specified period of time.
* Provides validations of email and password. It's optional and can be customized, so you're able to define your own validations.
* Locks an account after a specified number of failed sign-in attempts. Can unlock via email or after a specified time period.
* Connect multiply authorization providers to the same user, Facebook, Twitter 
* Handle role based permissions
* Handle user based permissions 
* Let other apps authorize true an api (oauth2)
* Two-factor authentication


### To do

- [ ] Get some advice, I know nothing about running an opensource project
- [ ] Make sure not to reinvent the wheel. What's out there and what can be used
- [ ] Draft up the ERD and get some feedback
- [ ] Draft up some sequence diagrams
- [ ] Get names on models and functions that totaly rocks
- [ ] How should it be packaged
- [ ] Make it extendable
- [ ] Make an API to other aps can registere true Heimdallr
- [ ] Make demo projects with automated test


### Suggestions
1. Don't make the GUI a part of the project, but make real a great cook-book style guides
2. Build it on top of existing frameworks



### Contributing

I hope that you will consider contributing to Heimdallr.  
Please drop me an e-mail max@digiramp.com  
I have also started a #Slack team https://heimdallr.slack.com



### Resources
[oauth2](https://github.com/scrogson/oauth2 "oauth2") for Elixir  
[guardian](https://github.com/hassox/guardian "guardian") for Elixir   
[addict](https://github.com/trenpixster/addict "addict") User registration lib for Elixir   

http://www.linuxfromscratch.org/blfs/view/7.5/postlfs/acl.html





