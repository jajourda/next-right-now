---
layout: default
title: Getting started
nav_order: 20
has_children: true
has_toc: false
---

<<<<<<< HEAD

# Getting Started


## Setup Next-Right-Now

### Get Your Environment and Equipment Ready 
- Next-right-now is a repo that requires Node.js to be installed on your system.
- You will need a text editor to write code
- You will need a Terminal application to invoke some commands.
<div class="tip">
<strong>Environment</strong>
i am a tip
</div>

<hr/>

### Clone the Next-Right-Now Repo to your Local Machine





## Inline code

Code can be rendered inline by wrapping it in single back ticks.

<div class="code-example" markdown="1">
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
</div>
```markdown
Lorem ipsum dolor sit amet, `<inline code snippet>` adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
```

---

## Syntax highlighted code blocks

Use Jekyll's built-in syntax highlighting with Rouge for code blocks by using three backticks, followed by the language name:

<div class="code-example" markdown="1">
```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
</div>
{% highlight markdown %}
```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```
{% endhighlight %}

---

## Code blocks with rendered examples

To demonstrate front end code, sometimes it's useful to show a rendered example of that code. After including the styles from your project that you'll need to show the rendering, you can use a `<div>` with the `code-example` class, followed by the code block syntax. If you want to render your output with Markdown instead of HTML, use the `markdown="1"` attribute to tell Jekyll that the code you are rendering will be in Markdown format... This is about to get meta...

<div class="code-example" markdown="1">

<div class="code-example" markdown="1">

[Link button](http://example.com/){: .btn }

</div>
```markdown
[Link button](http://example.com/){: .btn }
```

</div>
{% highlight markdown %}
<div class="code-example" markdown="1">

[Link button](http://example.com/){: .btn }

</div>
```markdown
[Link button](http://example.com/){: .btn }
```
{% endhighlight %}
=======
# Getting started

This section contains everything about how to get started with NRN. Here is the order we recommend:

1. [Video tutorials](./video-tutorials): Check our video tutorial to get an overview of what using NRN really looks like, from a developer point of view
1. [Quick start](./quick-start): Quickly get started with the most simple variant and run it on your own computer under 5mn
1. [Pick your variant](./pick-variant): **Advanced** - Find the variant that fits your needs through a comprehensive list of all possibilities _(make sure you are familiar with the basic [NRN concepts](../concepts) first!)_

## Want more?

- [Folder structure](../reference/folder-structure): Understand the boilerplate folder structure in a breeze
- [Demo DB structure](../reference/demo-database-structure): Understand the database structure used for the demo
- [Vendors pricing](../reference/vendors): Overview of the vendors pricing and what you should be aware of

## Want some real fun?

- [Dependencies documentation](../reference/vendors): Overview of NRN dependencies (enjoy!)

---

<div class="pagination-section">
    <span class="fs-4" markdown="1">
    [< Introduction](../){: .btn }
    </span>
    <span class="fs-4" markdown="1">
    [Watch video tutorials >](./video-tutorials){: .btn .btn-purple }
    </span>
</div>
>>>>>>> docs-massive-rewrite
