# Heimdallr
[read about the name on wikipedia](https://en.wikipedia.org/wiki/Heimdallr "Heimdallr")

User authorization and social integration framework for [Phoenix](http://phoenixframework.org "Phoenix").

---
### Roadmap

1. Throw in idears suggestions and needs
2. Investigate what is there and can it be used
3. Find a starting point and make something simple stupid


Should be composed of multiply modules: (Inspired by devise)


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

---
### To do

1. Get some advice, I know nothing about running an opensource project
2. Make sure not to reinvent the wheel. What's out there and what can be used
3. Draft up the ERD and get some feedback
4. Draft up some sequence diagrams
5. Get names on models and functions that totaly rocks
6. How should it be packaged
7. Make it extenciable
8. Make an API to other aps can registere true Heimdallr


### Suggestions
1. Don't make the GUI a part of the project, but make real great cook-book style guides
2. Build it on top of existing frameworks


---
### Resources
[oauth2](https://github.com/scrogson/oauth2 "oauth2") for Elixir  
[guardian](https://github.com/hassox/guardian "guardian") for Elixir  

http://www.linuxfromscratch.org/blfs/view/7.5/postlfs/acl.html





