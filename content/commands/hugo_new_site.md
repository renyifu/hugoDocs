---
date: 2016-04-09T23:00:06+02:00
title: "hugo new site"
slug: hugo_new_site
url: /commands/hugo_new_site/
---
## hugo new site

Create a new site (skeleton)

### Synopsis


Create a new site in the provided directory.
The new site will have the correct structure, but no content or theme yet.
Use `hugo new [contentPath]` to create new content.

```
hugo new site [path]
```

### Options

```
      --force           Init inside non-empty directory
  -f, --format string   config & frontmatter format (default "toml")
```

### Options inherited from parent commands

```
      --log              Enable Logging
      --logFile string   Log File path (if set, logging enabled automatically)
  -s, --source string    filesystem path to read files relative from
  -v, --verbose          verbose output
      --verboseLog       verbose logging
```

### SEE ALSO
* [hugo new](/commands/hugo_new/)	 - Create new content for your site

###### Auto generated by spf13/cobra on 9-Apr-2016