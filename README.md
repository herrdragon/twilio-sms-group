twilio-sms-group
================

A quickie PHP script for managing a moderated Twilio SMS group chat.

License
-------

LICENSE file

Requirements
------------

* PHP 5.3 and the [Twilio SDK](https://github.com/twilio/twilio-php)
* A [Twilio](http://twilio.com/) account and number.

Installation
------------

* Update the configuration settings and the list of known users.
* Grant your web server permissions to `feed.log`.
* Point your Twilio number at the index.php instance's public URL.

Usage
-----

* Any text from the moderator is passed along to the group of users.
* Any text from users is passed back to the moderator and all users.