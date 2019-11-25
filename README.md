# @KL_Projects : Telegram Torrent Drive Bot

Original Docs by Creator


## Deployment to Heroku

* Download and Install Heroku CLi and Bash.
* Create Account at Heroku and Create an App. (Note down Name you given it)
* Assuming Heroku App Name as xxxx
* Download your Repo after editing has been done of Token and Client ID and Secret.
* Extract it and Open bash by right clicking on that folder.
* Paste it in .constants.js file GDrive Directory Value.
* Download repo to your drive locally. (for windows right click in directory and open bash)
* Login to Heroku CLI
* `cd /d d:`    to change directory in windows here d: is D Directory changing from C.
* `heroku login`
* `heroku git:remote -a xxxx`
* `heroku stack:set container`
* `git add -f credentials.json src/.constants.js aria.sh client_secret.json`
* `git commit -m 'try commit'`
* `git commit -am "make it better"`    commit any changes
* `git push heroku HEAD:master --force`
* `heroku ps:scale worker=0`
* `heroku ps:scale worker=1`
* Check your bot.
