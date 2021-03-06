---
title: How to edit this site
---

## Edit existing pages
1. Create a [GitHub](https://github.com/) account if you do not already have one. You will need this in order to edit this Zettelkasten.
    - Your GitHub will also allow us to give you the necessary rights in the future.
1. In order to edit a zettel, click the edit icon (paper and pencil) in the top left side of a zettel (bottom, on mobile). 
   1. It will you take to GitHub wherein you can make the edits, and create what is known as a "PR" (pull request).
   1. See [complete walkthrough of this process here](https://help.github.com/en/github/managing-files-in-a-repository/editing-files-in-your-repository).
1. When a PR is created /u/srid- or /u/EyebrowHairs will "accept" it
1. Once accepted, the site is updated within a minute.

If you are a frequent editor, we can even give you access, so that step 3 & 4 are obviated.


## Create new pages

1. Go to the repository: <https://github.com/srid/reddit.zettel.page>
2. Click the "Create new file" button
3. Copy the paste the following template

**Tip**: It helps to have the list of all the file names handy in case you want to link to any of them.

### Template for new Zettel

Note: in the metadata, `title` is required; but `date` and `tags` are optional.

```markdown
---
title: Our first zettel
---

Hello world!
```

## How to link to other Zettel

Linking to a file within a Zettel indicates that it is branching off from it. Backlinks are automatically shown on the web browser. 

See [Neuron documentation](https://neuron.zettel.page/2011504.html) on how to link between zettels.

```markdown
<file-name> --> This links (and branches) to the zettel named "file-name.md"
```

For example: using `<examples>` will link to the <examples?cf> note. If you woud like to link only, but not branch off, use `<examples?cf>`.

## Markdown guidelines

* Markdown is a way to format text that is easier to read and write (compared to HTML).
* Notes in this Zettelkasten should be formatted in Markdown.
* Link to a basic Markdown [primer](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* Notes (specific to Neuron)
  * The title of the Zettel will be a first level heading.
  * URL's must be enclosed in angle brackets to be formatted as a link `<url-example>`
  * To add headings to your zettel start from level 2 (`## Heading`) headers, as level 1 heading is used for the Zettel title.
* Full list of features supported by Neuron, [see here](https://neuron.zettel.page/2011404.html)
