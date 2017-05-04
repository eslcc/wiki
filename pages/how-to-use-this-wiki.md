---
title: How to use this wiki
category: Meta
---

## Editing

Next to every page's title, you can see a `edit this page` link. Click that, and you'll be taken to the page's source
in GitHub. Pages are written in [markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

If you're a member of the eslcc org, you can edit it directly. If not, submit a pull request.

Edits will take a few seconds to show up in the site itself once they are made on GitHub.

## Creating new pages

To create a new page, click the link below the table of contents.

A couple of things you need to keep in mind, otherwise the wiki will break:

1. Make sure the page's extension is `.md`.
2. Make sure the page starts with the following front matter: **note: the `---` triple-dashes are required**
```
---
title: <insert page title here>
category: <insert category here>
---
```

Pages with the same category will be grouped together on the sidebar. **Note: the category must be *identical*, down to the capitalisation, or it will not be grouped.**
