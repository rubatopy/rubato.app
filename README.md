# rubato.app

This is the main site + the blog site. Anything here will be published to rubato.app

### Development info

This project uses a Jekyll with a themed bootstrap 5.

Draft posts are in the `_drafts` folder. In this folder is a markdown example to show you how to make a post. Post files' names follow the format `YEAR-MONTH-DAY-short-title.md`. Once a post is ready, move it to the `_posts` folder and it will get automatically published at the date specified.

To get started, first install the latest version of ruby. Then run this command:

```shell
gem install bundler
```

Next in the project directory run:

```
bundle config set --local path 'vendor/bundle'
bundle install
```

You may need to add the ruby bin folder to your path (run the gem install command again and it will tell you where the bin folder is)

Finally, to locally host the project:

```
bundle exec jekyll serve
```

or to see and draft posts:

```
bundle exec jekyll serve --drafts
```
