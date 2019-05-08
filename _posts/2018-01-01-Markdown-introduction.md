---
layout: articles
title: "Markdown introduction"
categories: Markdown introduction
permalink: Markdown-introduction.html
tags: [Markdown introduction]
sidebar: 
  nav: docs-en
---

## What is markdown?
>Markdown is a lightweight markup language with plain text formatting syntax. Its design allows it to be converted to many output formats, but the original tool by the same name only supports HTML.[8] Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Example

Note that there is also a [Cheatsheet specific to Markdown Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet) if that&#39;s what you&#39;re looking for. You can also check out [more Markdown tools](https://github.com/adam-p/markdown-here/wiki/Other-Markdown-Tools).


## Headers

    # H1
    
    ## H2
    
    ### H3
    
    #### H4
    
    ##### H5
    
    ###### H6
    
    Alternatively, for H1 and H2, an underline-ish style:
    
    Alt-H1
    
    ======
    
    Alt-H2
    
    ------

# H1

## H2

### H3

#### H4

##### H5

###### H6

Alternatively, for H1 and H2, an underline-ish style:

# Alt-H1

----------

**Alt-H2**

----------


## Emphasis

    Emphasis, aka italics, with *asterisks* or _underscores_.
    
    Strong emphasis, aka bold, with **asterisks** or __underscores__.
    
    Combined emphasis with **asterisks and _underscores_**.
    
    Strikethrough uses two tildes. ~~Scratch this.~~

Emphasis, aka italics, with *asterisks* or _underscores_.
    
Strong emphasis, aka bold, with **asterisks** or __underscores__.
    
 Combined emphasis with **asterisks and _underscores_**.
    
Strikethrough uses two tildes. ~~Scratch this.~~

Strikethrough uses two tildes.

## Lists

(In this example, leading and trailing spaces are shown with with dots: ⋅)
    
    1. First ordered list item
    
    2. Another item
    
    ⋅\* Unordered sub-list.
    
    1. Actual numbers don&#39;t matter, just that it&#39;s a number
    
    ⋅⋅1. Ordered sub-list
    
    1. And another item.
    
    ⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we&#39;ll use three here to also align the raw Markdown).
    
    ⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
    
    ⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
    
    ⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)
    
    \* Unordered list can use asterisks
    
    - Or minuses
    
    + Or pluses

1. First ordered list item
2. Another item

* Unordered sub-list. 

1. Actual numbers don't matter, just that it's a number
2. Ordered sub-list
4. And another item.

You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

To have a line break without a paragraph, you will need to use two trailing spaces.
Note that this line is separate, but within the same paragraph.⋅⋅
(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses



## Links

There are two ways to create links.

    [I&#39;m an inline-style link](https://www.google.com)
    
    [I&#39;m an inline-style link with title](https://www.google.com &quot;Google&#39;s Homepage&quot;)
    
    [I&#39;m a reference-style link][Arbitrary case-insensitive reference text]
    
    [I&#39;m a relative reference to a repository file](../blob/master/LICENSE)
    
    [You can use numbers for reference-style link definitions][1]
    
    Or leave it empty and use the [link text itself].
    
    URLs and URLs in angle brackets will automatically get turned into links.
    
    http://www.example.com or \&lt;http://www.example.com\&gt; and sometimes
    
    example.com (but not on Github, for example).
    
    Some text to show that the reference links can follow later.
    
    [arbitrary case-insensitive reference text]: https://www.mozilla.org
    
    [1]: http://slashdot.org
    
    [link text itself]: http://www.reddit.com

[I&#39;m an inline-style link](https://www.google.com/)

[I&#39;m an inline-style link with title](https://www.google.com/)

[I&#39;m a reference-style link](https://www.mozilla.org/)

[I&#39;m a relative reference to a repository file](https://github.com/adam-p/markdown-here/blob/master/LICENSE)

[You can use numbers for reference-style link definitions](http://slashdot.org/)

Or leave it empty and use the [link text itself](http://www.reddit.com/).

URLs and URLs in angle brackets will automatically get turned into links. [http://www.example.com](http://www.example.com/) or [http://www.example.com](http://www.example.com/) and sometimes example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

## Images

    Here's our logo (hover to see the title text):
    
    Inline-style:
    
    ![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png &quot;Logo Title Text 1&quot;)
    
    Reference-style:
    
    ![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png &quot;Logo Title Text 2&quot;

Here&#39;s our logo (hover to see the title text):

Inline-style:  ![此处输入图片的描述][2]

Reference-style:  ![此处输入图片的描述][3]



## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn&#39;t. However, many renderers -- like Github&#39;s and _Markdown Here_ -- support syntax highlighting. Which languages are supported and how those language names should be written will vary from renderer to renderer. _Markdown Here_ supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the [highlight.js demo page](http://softwaremaniacs.org/media/soft/highlight/test.html).

    Inline `code` has `back-ticks around` it.

Inline `code` has `back-ticks around` it.

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they&#39;re easier and only they support syntax highlighting.

    ```javascript
    var s = "JavaScript syntax highlighting";
    alert(s);
    ```
     
    ```python
    s = "Python syntax highlighting"
    print s
    ```
     
    ```
    No language indicated, so no syntax highlighting. 
    But let's throw in a <b>tag</b>.
    ```
    
    var s =&quot;JavaScript syntax highlighting&quot;;alert(s);
    
    s =&quot;Python syntax highlighting&quot;print s
    
    No language indicated, so no syntax highlighting in Markdown Here (varies on Github). 
    But let's throw in a <b>tag</b>.



## Tables

Tables aren&#39;t part of the core Markdown spec, but they are part of GFM and _Markdown Here_supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

    Colons can be used to align columns.
    
    | Tables        | Are           | Cool  |
    
    | ------------- |:-------------:| -----:|
    
    | col 3 is      | right-aligned | $1600 |
    
    | col 2 is      | centered      |   $12 |
    
    | zebra stripes | are neat      |    $1 |
    
    There must be at least 3 dashes separating each header cell.
    
    The outer pipes (|) are optional, and you don&#39;t need to make the
    
    raw Markdown line up prettily. You can also use inline Markdown.
    
    Markdown | Less | Pretty
    
    --- | --- | ---
    
    \*Still\* | `renders` | \*\*nicely\*\*
    
    1 | 2 | 3

Colons can be used to align columns.

| **Tables** | **Are** | **Cool** |
| --- | --- | --- |
| col 3 is | right-aligned | $1600 |
| col 2 is | centered | $12 |
| zebra stripes | are neat | $1 |

There must be at least 3 dashes separating each header cell. The outer pipes (|) are optional, and you don&#39;t need to make the raw Markdown line up prettily. You can also use inline Markdown.

| **Markdown** | **Less** | **Pretty** |
| --- | --- | --- |
| _Still_ | renders | **nicely** |
| 1 | 2 | 3 |



## Blockquotes

    > Blockquotes are very handy in email to emulate reply text.
    > This line is part of the same quote.
    
    Quote break.
    
    > This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.

>Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.

Quote break.

>This is a very long line that will still be quoted properly when it wraps. Oh boy let&#39;s keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_  **Markdown**  into a blockquote.

## Inline HTML

You can also use raw HTML in your Markdown, and it&#39;ll mostly work pretty well.

    <dl>
      <dt>Definition list</dt>
      <dd>Is something people use sometimes.</dd>
    
      <dt>Markdown in HTML</dt>
      <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
    </dl>

_Definition list_

Is something people use sometimes.

_Markdown in HTML_

Does \*not\* work \*\*very\*\* well. Use HTML _tags_.


## Horizontal Rule
    
    Three or more...
    
    ---
    
    Hyphens
    
    ***
    
    Asterisks
    
    ___
    
    Underscores

Three or more...
    
---------------

Hyphens
    
************

Asterisks
    
_____________

Underscores


## Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover -- hit \&lt;Enter\&gt; once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You&#39;ll soon learn to get what you want. &quot;Markdown Toggle&quot; is your friend.

Here are some things to try out:

    Here's a line for us to start with.
    
    This line is separated from the one above by two newlines, so it will be a *separate paragraph*.
    
    This line is also a separate paragraph, but...
    
    This line is only separated by a single newline, so it&#39;s a separate line in the *same paragraph*.

Here&#39;s a line for us to start with.

This line is separated from the one above by two newlines, so it will be a _separate paragraph_.

This line is also begins a separate paragraph, but...
This line is only separated by a single newline, so it&#39;s a separate line in the _same paragraph_.

(Technical note: _Markdown Here_ uses GFM line breaks, so there&#39;s no need to use MD&#39;s two-space line breaks.)


[1]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png
[2]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png
[3]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png

  
