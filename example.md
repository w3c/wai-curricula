---
title: "Page Title"
permalink: /curricula/example-page/
ref: /curricula/exapmple-page/
lang: en
status: draft
github:
  repository: w3c/wai-curricula
  path: example.md
footer: > # Text in footer in HTML
  <p> This is the text in the footer </p>
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod architecto excepturi incidunt, odit modi quidem deserunt doloremque molestias saepe. Iste dolor non repellendus laudantium! Nihil velit mollitia voluptatem ullam libero.

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{::nomarkdown}
{% include toc.html type="start" title="Page Contents" %}
{:/}

- This will be replaced by an automatically generated TOC when using Markdown formatting.
{:toc}

{::nomarkdown}
{% include toc.html type="end" %}
{:/}

## Heading Level 2

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. **Assumenda aut, praesentium (bold)** commodi _nesciunt natus (italic)_ ipsum fugiat [voluptates nisi ipsam voluptas (Link)](https://example.com) recusandae, a. [Sunt eos veritatis numquam (Internal link)]({{ "/permacurricula/" | relative_url }})!

### Heading Level 3

1. This is
2. a nice
3. ordered
4. list.

#### Heading Level 4


* And this is a
* bullet list

- You can use asterisks
- or dashes. Whatever floats
- your boat :-)

##### Heading Level 5

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. Assumenda aut, praesentium commodi nesciunt natus ipsum fugiat voluptates nisi ipsam voluptas recusandae, a. Sunt eos veritatis numquam!

## Heading Level 2

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. Assumenda aut, praesentium commodi nesciunt natus ipsum fugiat voluptates nisi ipsam voluptas recusandae, a. Sunt eos veritatis numquam!

### Heading Level 3

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. Assumenda aut, praesentium commodi nesciunt natus ipsum fugiat voluptates nisi ipsam voluptas recusandae, a. Sunt eos veritatis numquam!

{% include excol.html type="start" id="optional_id" %}

### Heading Level 3 as expand/collapse

{% include excol.html type="middle" %}

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. Assumenda aut, praesentium commodi nesciunt natus ipsum fugiat voluptates nisi ipsam voluptas recusandae, a. Sunt eos veritatis numquam!

#### Heading Level 4 inside the excol 

Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ratione placeat ab laboriosam. Assumenda aut, praesentium commodi nesciunt natus ipsum fugiat voluptates nisi ipsam voluptas recusandae, a. Sunt eos veritatis numquam!

{% include excol.html type="end" %}