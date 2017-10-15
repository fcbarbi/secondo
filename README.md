# README

This is a lab project to keep updated with the latest version of Ruby on Rails (RoR). I am using tips from Rob Race's book **Build a SaaS App in Ruby on Rails 5** (https://buildasaasappinrails.com/).

Introduction
============

I had some issues with the Rails installation as I could not even get "rails -v" to work:
```
/usr/local/bin/rails:22:in `<main>': undefined method `activate_bin_path' for Gem:Module (NoMethodError)
```
The first solution `sudo gem update --system` resulted in more errors.

I recommend the use of **rbenv** (an alternative to RVM) to manage the environment for gem installation. According to https://github.com/rbenv/rbenv "at a high level, rbenv intercepts Ruby commands using shim executables injected into your PATH, determines which Ruby version has been specified by your application, and passes your commands along to the correct Ruby installation."

To install it I used Homebrew and then the latest Ruby (2.4.2) by issuing the commands 

```
$ brew install rbenv
$ rbenv install 2.4.2
$ rbenv global 2.4.2
```

Setup 
=============

This README documents steps to configure the Application environment:

* Ruby 5.1.4. I had to install *Ruby*, *gem* and *bundler*

* PostgreSQL 10. I am using Mac OSX so the simple way is to download and run *postgreapp* from http://postgresapp.com/ 

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


