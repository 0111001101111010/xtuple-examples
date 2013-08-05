xTuple REST API PHP Client Example
==================================

A Basic xTuple REST API PHP Client example that uses [Google's APIs Client library]
(http://code.google.com/p/google-api-php-client/) and [JSON-Patch PHP library]
(https://github.com/bendiy/json-patch-php) to interface with xTuple's REST API.

These are some very basic DELETE, GET, PATCH and POST request examples.

WARNING: These examples are in no way secure or using best practices
for PHP application. This is meant for educational purposes only.

There is a lot more that could be done to expand on these examples.
TODO: Create a basic user interface.
TODO: Change POST into an add form that creates fields from the JSON-Schema.
TODO: Change PATCH into an edit form that creates fields from the JSON-Schema.

Install and Run the Client
--------------------------
1. Clone or download this repo and copy this directory "php-client-example" to
a path exposed by your PHP server. For example:

```
/var/www
```

2. Register for an OAuth 2.0 "Services Account" Client in your xTuple Mobile
Client's "OAUTH2" interface. You will be prompted to download a PK12 keystore
file.
3. Save the PK12 keystore file in the same directory as this file and the
"index.php" file.
3. Edit the "local_config.php" file and set all of your environment and OAuth
2.0 client specific settings.
4. Visit the "index.php" file on your PHP server. For example:

```
https://localhost/php-client-example/index.php
```

Note, make sure your xTuple Mobile Client is running before loading "index.php".

Using the Example
-----------------
You should be presented with a list of contacts. Initially, at the bottom of
the list, there is a link to "Add Contact 42". You can click on a contact's
number to view it. Each contact has links to "Delete" it or "Add a comment".

## Credits

  - [bendiy](http://github.com/bendiy)

## License

[The MIT License](http://opensource.org/licenses/MIT)

Copyright (c) 2012-2013 xTuple [http://www.xtuple.com/](http://www.xtuple.com/)
