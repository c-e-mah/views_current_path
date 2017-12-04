28 November 2017

I produced this module last week because I wanted a Drupal 8 version of the Drupal 7 module [Views Current Path](https://www.drupal.org/project/views_current_path).

It is just a quick re-write of that module. I've never upgraded anyone's D7 module before, so I'm sure I made a bunch of mistakes, but it works for what I want locally, so it's a start.

Specifically, the things that seem to have changed from D7 to D8 and are not well-documented from a developer standpoint, I skipped, such as `locale_language_url_rewrite_url` which seems like a defunct construct in D8.

Defines a views field that prints the path of the page currently being viewed.
