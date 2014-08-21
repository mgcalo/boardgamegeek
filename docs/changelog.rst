Changelog
=========

0.0.13
------

Features

  * Improved code for fetching an user's buddies and guilds
  * Improved code for fetching guild members
  * Added support for listing Plays by user and by game


0.0.12
------

Features

  * Added some basic argument validation to prevent pointless calls to BGG's API
  * When some object (game, user name, etc.) is not found, the functions return None instead of raising an exception


0.0.11
------

Features

  * Collections and Guilds are now iterable

Bugfixes

  * Fixed __str__ for Collection

0.0.10
------

Features

  * Updated documentation
  * Improved Python 3.x compatibility (using unicode_literals)
  * Added Travis integration

Bugfixes

  * Fixed float division for Python 3.x

0.0.9
-----

Features

  * Added support for retrieving an user's buddy and guild lists
  * Started implementing some basic unit tests

Bugfixes

  * Fixed handling of non-existing user names
  * Properly returning the maximum number of players for a game