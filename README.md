# JDK 9 Example on Heroku

A barebones Java app, which can easily be deployed to Heroku with the latest JDK 9 Early Access version.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

For more info see [my blog post on testing JDK 9 EA on Heroku](http://jkutner.github.io/2015/07/16/test-jdk9-heroku.html).

Once you've deployed, run this command to get a JShell:

```
$ heroku run jshell
Running jshell on ⬢ pure-gorge-42130... up, run.8624
May 26, 2016 12:17:37 AM java.util.prefs.FileSystemPreferences$1 run
INFO: Created user preferences directory.
|  Welcome to JShell -- Version 9-internal
|  For an introduction type: /help intro


jshell>
```