---
"layout": "page",
"title": "Usage",
"use": [ { "uri": "navigation.md" } ],
"permalink": true
---

# Usage

## Create Pages

Create arbitrary pages with following metadata:

```
---
"layout": "page",
"title": "Usage",
"use": [ { "uri": "navigation.md" } ],
"permalink": true
---
```
Here the entries `layout` and `use` are important. Then create your content while structuring it by meaningful headings. It is recommended to not use headings more than three levels deep. 

Create some or all pages this way.

## Create Navigation Sidebar

Create a markdown file named according your pages `use` metadata entry.
```
"use": [ { "uri": "navigation.md" } ],
```
So we are creating file `navigation.md`.

In every page file, you previously created, generate a *table of content* snippet via <kbd>Ctrl</kbd>&nbsp;+&nbsp;<kbd>K</kbd>&nbsp;&nbsp;<kbd>T</kbd> (see [microjam.keybord commands](file:///C:/git/microjam/docs/usage.html#keyboard-commands)).

With this markdown file you would get 

```
- [Usage](installation.html#usage)
  - [Create Pages](installation.html#create-pages)
  - [Create Navigation Sidebar](installation.html#create-navigation-sidebar)
  - [Modify Header](installation.html#modify-header)
```

Now edit this markdown list snippet as you like and then copy and paste it into the file `navigation.md` .

## Modify Header

You can modify the pages header as well as the first sidebar entry manually directly inside of `docs/theme/template.js`.