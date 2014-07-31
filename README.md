# Parent Helpdesk

Helpdesk is a multilingual static site generated using [Jekyll](http://jekyllrb.com/).
Content is written in [Markdown](https://guides.github.com/features/mastering-markdown/).


## Installing

Clone this repo.
Install dependencies.

```
$ bundle install
```

## Writing content

Content structure is `_i18n/{lang}/_posts/questsions/{yyyy-mm-dd}-{english question}.md`.
You can view your changes using

```
$ jekyll serve --watch
```

## Deploying

Use jekyll to build the site `jeklyl build`.
Then upload the generated `_site` directory a production server to be hosted.
