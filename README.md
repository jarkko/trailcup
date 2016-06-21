```
git fetch origin
git rebase origin/master
bundle

bundle exec middleman -p 4570

[open browser in localhost:4570]

[make edits, browser should auto-refresh]

git add .
git ci -m "Message about edits"

bundle exec rake publish                 # pushes changes to GitHub pages
