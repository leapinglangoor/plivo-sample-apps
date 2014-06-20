Conference App

Conference App made with Plivo.
Sends sms to the moderator everytime a user enters the conference, which the moderator can respond to.

To run in heroku:

git init
git add .
git commit -m "init"

heroku create
->put in the output that looks like git@heroku.com:soaring-plimbs-1234.git in the next line
git remote add heroku  git@heroku.com:soaring-plimbs-1234.git
git push heroku master
