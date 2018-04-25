0.0.6
-----
Release Date: April 25th, 2018

* Catch HTTPErrors, and try to display what the error response was


0.0.5
-----
Release Date: January 22th, 2018

* Trim quotes from env vars, to prevent variables from having extra quotes in
  them


0.0.4
-----
Release Date: December 7th, 2017

* Prevent false positives on checking if build was triggered, by only checking
  that a few ghprb env vars that show up in Jenkins are verified


0.0.3
-----
Release Date: December 7th, 2017

* Prevent optional env vars from causing ``KeyErrors`` by using ``.get('ENV_VAR')``

0.0.2
-----
Release Date: December 7th, 2017

* ``github-status create`` will execute the sub-command, vs. displaying help.


0.0.1
-----
Release Date: December 6th, 2017

* Initial release.
