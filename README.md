# Emily Cribbs Portfolio

## Local Development

To start the jekyll serve,r run:

```bash
bundle exec jekyll serve
```

If you get an error like `gem not installed`, update the local gems, run:

```bash
bundle install
```

## Fetching New Changes

To pull in new changes from github, run:

```bash
# make sure your local version is up to date
git pull --rebase
# If this produces a merge conflict, shoot me a message :)
```

## Saving Your Work

To save your changes to github, run:

```bash
# make sure your local version is up to date
git pull --rebase
# add all the changes
git add -A
# add a message describing the changes
git commit -m "$YOUR_COMMMIT_MESSAGE"
# push them to github
git push
```
