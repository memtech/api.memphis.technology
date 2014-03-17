## api.memphis.technology

Based on [Larastrap](https://github.com/memphisphp/larastrap)

-----

## Included
* Laravel 4.1.x
* Twitter Bootstrap 3.0.3
* jQuery 2.1.0
* Font-Awesome 4.0.3
* HTML5 Shiv 3.7.0

## Requirements
* PHP 5.3.7 or later
* MCrypt PHP Extension
* [Composer](http://www.getcomposer.org)
* [Bower](http://bower.io/)
  * [Node.js](http://nodejs.org/)

## Installation
* Run composer install
```
composer install
```

* Run bower install. Edit .bowerrc if you want to change the assets folder.
```
bower install
```

You will need to [register an oath consumer](https://secure.meetup.com/meetup_api/oauth_consumers/create/) and add the keys to the application.

Currently Meetup's API does not recgonize .technology TLDs. I've raised an [issue](https://github.com/meetup/api/issues/23). Looks like this is on hold for now.

Might be able to put the API on another domain and still consume it via json on http://memphis.technology