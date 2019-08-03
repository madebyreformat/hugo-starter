# Notes

```hugo server -D``` run server and show draft pages

## Types

- list
  - lists other content eg. blog, projects, people (wp = archive.php, home.php, category.php etc)
  - *how to select whats listed, how to order, how to ignore*
- single
  - item eg. page, post, project, profile etc
- homepage (_default/index.html)

## Creating content

- will create a list page at root level, override with _index.md

### Archetypes

These are the default items for content eg. default.md

If you create one same name as a directory then it will use that for any default files in directory of the same name eg. archetypes/project.md -> content/project/test.md

## Hierarchy

Anything inside layouts on root with override anything in themes

## Ideas
- [shortcode](https://gohugo.io/content-management/shortcodes/) for mixin type stuff, custom
- add different templates for different taxonomies?
- is it possible to pass variables into blocks apart from content?
