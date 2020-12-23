---
name: New Mod
about: Issue to ADD or UPDATE a Mod on the Index.
title: "[MOD-NEW]"
labels: mod-new
assignees: AdrianoCahete

---

<-- 

Delete this comment block after filling the template. The template accepts markdown on body.  
Leave the `[MOD-NEW]` before the title and add your mod name after.  
To Update mod, change the title to `[MOD-UPDATE]` and just fill the update values.

- `title` and `description` are strings. You don't need to put between quotes. Description is a small description.
- `releaseStatus` is the status of the mod. `alpha`, `beta` or `released` are accept.
- `type` is the type of mod. Accepts `map`, `admin` and `game`
- `version` is the mod's version. Accepts any number on version schema (`x.y.z`)
- `sourceUrl` is the URL to mod's source code
- `downloadURL` is the URL to download the mod itself. If you are using some Git service, you can create a `Release` and point to that file.
- `faqUrl` is the URL to mod's thread on Venice Unleashed forum. It's good to help users in there.

There's no "default" values. If you doesn't fill the value, the key will be ignored on website. Same occurs if the value is in a invalid schema.

-->

---
title: Your mod name
description: Your description
releaseStatus: alpha
type: admin
version: 0.1
sourceUrl: url-to-source-files
downloadUrl: url-to-zip-files
faqURL: url-to-venice-unleashed-thread
---
   
# Requirements
If your mod has any requirement, like other mods, link them here.  

# How to install
If the installation is different than the default (unzip the archive to mods folder), explain here.

# Support the Author
If you want to ask for some support, you can do in this body too.
