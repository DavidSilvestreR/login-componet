# \<login-component\>

This is the first element created with polymer 
This component simulates the authentication and sign-in of a user in a web application


## Functions
`userAuthentication(username,password) :`
	this function simulates the login of a user, the function compares hard-coding data, if username and password match with hard-coding data, the function return true
	the hard-coding:
	 username: _DavidSilvestre_
	 password: _polymer_
`comparePasswords()`
	This function compares two passwords and returns true if the passwords are the same or false if the passwords are different

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
