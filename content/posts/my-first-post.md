---
title: "Code highlighting"
date: 2023-10-27T11:09:53+09:00
# bookComments: false
# bookSearchExclude: false
---
Supported languages: bash/shell, css, clike, javascript, apacheconf, actionscript, applescript, c, csharp, cpp, coffeescript, ruby, csp, css-extras, diff, django, docker, elixir, elm, markup-templating, erlang, fsharp, flow, git, go, graphql, less, handlebars, haskell, http, java, json, kotlin, latex, markdown, makefile, objectivec, ocaml, perl, php, php-extras, r, sql, processing, scss, python, jsx, typescript, toml, reason, textile, rust, sass, stylus, scheme, pug, swift, yaml, haml, twig, tsx, vim, visual-basic, wasm.

Improved RSS Feed 
Some enhancements have been made to Hugo’s internal RSS generation code.

A page’s cover image now appears at the top of its feed display. This image is set manually using the cover params. If unset, the RSS generator searches for the first image file in the page bundle whose name includes ‘featured’, ‘cover’, or ’thumbnail’.

You can optionally display the full page content in your RSS feed (default is Description or Summary data from Front Matter). Set rssFullText = true in your config.toml file to enable this option.

You can choose a site image to be displayed when searching for your RSS feed. Set rssImage = "image/url/here" in your config.toml file to enable this option.
