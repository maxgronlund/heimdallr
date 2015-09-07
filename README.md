# Heimdallr

User authorization for Phoenix

### Roadmap

* Throw in idears suggestions and needs
* Investigate what is there and can it be used
* Find a starting point and make something simple stupid


It's composed of 10 modules: (Inspired by devise)

* Encrypts and stores a password in the database to validate the authenticity of a user while signing in. The authentication can be done both through POST requests or HTTP Basic Authentication.
* oauth2  support.
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



[oauth2](https://github.com/scrogson/oauth2 "oauth2") for Elixir
[guardian](https://github.com/hassox/guardian "guardian") for Elixir

http://www.linuxfromscratch.org/blfs/view/7.5/postlfs/acl.html





