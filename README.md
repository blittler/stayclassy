# Stay Classy

##Raison d'etre

Helping the world stay classy.

## Setup

### Project

`bundle install`

`rake db:create`

`rake db:migrate`

### Heroku

`heroku keys:add`

`heroku create`

`heroku run rake db:migrate`

`heroku config:set AWS_BUCKET=xx AWS_ACCESS_KEY_ID=xx AWS_SECRET_ACCESS_KEY=xx`