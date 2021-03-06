# Scratch_Auth

By [Andrew Thul](github.com/adthul).

## Description
**scratch_auth** is a simple application that includes the basic architecture allowing users to sign up, sign in, remain logged into a session, and logout. There are authentications in place checking for validations of user generated content for length and uniquness in the appropriate forms. there is also user authentication in place defining certain actions to only be available to currently logged in users.


## Installation

clone project from github

cd the 'store' folder in your command line:

```console
cd store
```

Run bundler to install necessary gems:

```console
bundle install
```

Push to Heroku or other hosting site to go live:
https://devcenter.heroku.com/articles/quickstart

Or run a local server on your own computer:

```console
rails server
```

Open a browser and search for URL:

localhost:3000

Otherwise put into production with whetever public server you prefer, [Heroku](https://devcenter.heroku.com/articles/quickstart) for instance.


## Usage

Please use as a template for your own authentications!


### Known Issues

If you discover any bugs, feel free to create an issue on GitHub fork and
send us a pull request.


## Authors

* Andrew Thul

...based on RailsCasts #250


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## License

[MIT License](http://adthul.mit-license.org)
