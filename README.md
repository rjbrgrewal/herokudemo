# herokudemo
Getting Started on Heroku with Node.js

## Heroky and git commands
heroku create
git remote -v
heroku buildpacks:set heroku/nodejs
git add <filename>
git commit -m "Heroku Demo"
git push heroku main
heroku ps:scale web=1
heroku open
heroku logs --tail