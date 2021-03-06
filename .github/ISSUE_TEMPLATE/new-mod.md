---
name: New Mod
about: Issue to ADD or UPDATE a Mod on the Index.
title: "[MOD-NEW]"
labels: mod-new
assignees: AdrianoCahete

---

<!-- **IMPORTANT!**  

Delete this comment block after filling the template. The template accepts markdown on the body.  
Leave the `[MOD-NEW]` before the title and add your mod name after.  
To Update mod, change the title to `[MOD-UPDATE]` and just fill in the update values.

** On FrontMatter (header, between the ---): `int` values are unquoted (for now, only the version value). `String` values are quoted.**

- `title` and `description` are strings. You don't need to put between quotes. The description is a small description.
- `type` is the type of mod. Accepts `map`, `admin` and `gameplay`
- `version` is the mod's version. Accepts any number on version schema (`x.y`)
- `sourceUrl` is the URL to mod's source code
- `author` is the Author nickname.
- `downloadURL` is the URL to download the mod itself. If you are using some Git service, you can create a `Release` and point to that file.
- `faqUrl` is the URL to mod's thread on the Venice Unleashed forum. It's good to help users in there.

There are no "default" values. If you don't fill in the value, the key will be ignored on the website. The same occurs if the value is in an invalid schema.

-->

```
---
title: 'Your mod name'
description: 'Your description'
type: 'admin'
version: 0.1
author: 'AuthorName'
sourceUrl: 'url-to-source-files'
downloadUrl: 'url-to-zip-files'
faqUrl: 'url-to-venice-unleashed-thread'
---
   
# Requirements
If your mod has any requirements, like other mods, link them here.  

# Limitations
Just run on specifc maps? Note it here!

# How to install
If the installation is different than the default (unzip the archive to mods folder), explain here.

# How to Use
If isn't just unzip and run, explain here how to use/configure it.

# Support the Author
If you want to ask for some support, you can do in this body too.
```
