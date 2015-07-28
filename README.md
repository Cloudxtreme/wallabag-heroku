# Wallabag Heroku

Template for installing and running [Wallabag](https://www.wallabag.org/) on [Heroku](http://www.heroku.com/)

Wallabag version: 1.9.0


## Installation

Create app with Heroku gem

    $ cd wallabag-heroku/
    $ heroku create

    Creating glacial-anchorage-4861... done, stack is cedar-14
    http://glacial-anchorage-4861.herokuapp.com/ | https://git.heroku.com/glacial-anchorage-4861.git
    Git remote heroku added


Create database

$ heroku addons:create heroku-postgresql:hobby-dev

    Creating walking-sweetly-1136... done, (free)
    Adding walking-sweetly-1136 to glacial-anchorage-4861... done
    Setting DATABASE_URL and restarting glacial-anchorage-4861... done, v6
    Database has been created and is available
     ! This database is empty. If upgrading, you can transfer
     ! data from another database with pgbackups:restore
    Use `heroku addons:docs heroku-postgresql` to view documentation.



Deploy to Heroku

$ git push heroku master

Access wallabag from your browser e.g.: `glacial-anchorage-4861.herokuapp.com/`

Select `postgresql` and fill the information about the database


## Info

http://doc.wallabag.org/en/index.html

https://devcenter.heroku.com/articles/php-support


## License

Copyright © 2013-2014 Nicolas Lœuillet <nicolas@loeuillet.org>
This work is free. You can redistribute it and/or modify it under the
terms of the MIT License. See the COPYING file for more details.
