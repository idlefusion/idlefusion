Email Landing Page
============

A simple, customizable landing page for email signup, based on Rack and Sinatra. The current version has MailChimp and Google Analytics integration.

Please visit the [live demo](http://landingpages.herokuapp.com/) on Heroku and join the project mailing list

# Instructions

1. `$ git clone git://github.com/quartzmo/email-landing-page.git`
1. `$ cd email-landing-page`
1. `$ rm -rf .git`
1. `$ bundle install`
1. Register for a free MailChimp account and generate an API key (required).
1. Edit `app.rb`, adding your MailChimp API key and list name (required).
1. Modify `public/index.html`, replacing sample content with your own.
1. If you want Google Analytics, edit `config.ru`, uncomment the indicated lines, and add
   your Google Analytics account ID (optional).
1. `$ bundle exec rackup` to start the app locally on port 9292.
1. Test locally.
1. Register for a free Heroku account (optional).
1. Follow instructions to deploy to Heroku, using the Cedar stack if desired (optional).
1. Configure custom domain name with Heroku.

Todo: Full instructions including Heroku deployment

# Credits

Inspired by [alphabetum/landing-page](https://github.com/alphabetum/landing-page).