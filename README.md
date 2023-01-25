# Software Engineering at Montreal (SE@MTL) Website

This website is forked from [Project Pages](https://github.com/projectpages/project-pages/wiki/). It uses jekyll, and [is hosted by github pages](https://semtl.github.io/).

## Contribute

Please make pull requests to contribute events or members. For all other concerns, use the issue tracker.

### To add a new event

Create a Markdown page under the `_posts` folder.

Note that in the metadata for a post, `event_date` is the actual date for the event, while `date` is the date that the post will be made visible on the website.

### Add a new member

Add the member to the `members.yml` file in the `_data` folder.

### Producing a visualization of attendee keywords

There is a [Jupyter notebook](https://github.com/SEMTL/semtl.github.io/blob/gh-pages/scripts/KeywordViz.ipynb) for producing keyword visualization from the spreadsheet of attendee RSVPs. Instructions are included in the notebook itself.
