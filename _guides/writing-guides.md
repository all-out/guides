---
layout: guide
title: All-Out Guide to Writing All-Out Guides
shorttitle: Writing Guides (in progress)
author: Mussah Yacoub
excerpt: >
  Rundown of format and style guidelines for guides, and instructions for how
  to submit them so that they show up on this site.
---

## Formatting

### File

Guides are written as **plain-text files** with the extension `.md` (for
Markdown). The URL of the page comes from the filename - for example, this
sourcefile for this page is named `writing-guides.md` and its URL is at
`/guides/writing-guides/`.

Where possible, keep line length in the sourcefile under 80 characters.  This
mostly applies to text paragraphs; if your links, lists, or codeblocks make
this tricky, don't sweat it.  This is mainly to simplify resolving merge
conflicts later.

### Content

#### Front Matter

The first section of every guide is called the **front matter** and is enclosed
by two `---` lines.  This is in the YAML format, and it's used for defining the
metadata of the document. Example:

{% highlight yaml %}
---
layout: guide                       # renders page using the "guide" template
title: All-Out Guide to Something   # big title at the top of the page
shorttitle: Something               # small title in list of guides
author: John Doe                    # your character's name
excerpt: >                          # note the space between the : and the >
  Words words words                 # everything that is indented from here
  words words words                 # on is shown in the list of guides and
  words words words.                # in the tagline if you link it somewhere
---
{% endhighlight %}

#### Markdown

Everything after the front matter block (that is to say, most of the content in
a guide) is written in a variant of Markdown.  If you've formatted Slack posts,
this is very similiar.

- [kramdown quick-ref](http://kramdown.gettalong.org/quickref.html): List of
syntax you can use

- [writing-guide.md](https://raw.githubusercontent.com/all-out/guides/master/_guides/bookmarks.md):
the source file of this page, for examples and reference

#### Notes about Content:

- Don't use level 1 headers (that is, `=======` or `#`).  Any given
webpage should only use one of these elements, and that's what the `title`
attribute defined in the front matter will be rendered as.  Level 2 and below
headers are fine.

- The `shorttitle` element in your front matter should match or be very close
to your filename/URL, so that the title looks like the link.

## Style

- Try to keep your `title` in the form of "All-Out Guide to Something" and your
`shorttitle` to something short, snappy, and evocative.

- Think carefully about the order in which you introduce concepts.  You should
define basic concepts for your reader before using them to refer to something
else.

- If there is already good resource somewhere else on the web that touches on
the thing you are describing, go ahead and link it!

- Make use of formatting.  Headers, subheaders and subsubheaders are helpful,
but don't forget lists (bullets and numbers), tables, images, and `code
blocks`. Bold **key words**.  Italicize for *emphasis*.

- If you use an abbreviation like SAAR or XLASB or POS, please use the abbreviation
syntax of Markdown to define it so that hovering it shows what it is.

*[SAAR]: small ancillary armor repair
*[XLASB]: extra-large ancillary shield booster
*[POS]: player-owned starbase
