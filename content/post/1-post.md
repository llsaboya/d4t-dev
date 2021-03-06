---
title: Hello World
description: meta description
image: images/post/post-2.png
date: 2019-01-24T12:19:25.000Z
categories:
    - notas
type: "regular" # available types: [featured/regular]
draft: true
slug: world

---

{{< image title="Titulo da imagem" w="" h="" o="webp q100" p="center" c="rounded" src="images/post/post-5.png" alt="texto alt" >}}




{{< image src="images/post/post-1.png" caption="Image Caption" alt="alter-text" h="100" w="200" p="right" command="fit" option="q10 r90" class="img-fluid" title="Image Title" webp="true" >}}

- src is the source of the image. You can use a local image [assets/static/content] or an external image.
- caption is the caption of the image. When you put a caption, then the image will wrap in a figure element.
- alt is the alter text for the image. It helps to describe the image.
- height can specify the height of the image.
- width can specify the width of the image.
- position can be set to left, right, center, float-left, float-right.
- command can be used to implements the Resize, Fit, or Fill. Learn more about commands here
- option can specify the image options like background color, quality, hint, rotate, anchor, and resample filter. Learn more about options here
- class can add classes to the image. If you need to add any classes, then you can use the class attribute.
- title can add a title attribute to the image.
- webp can be set to true or false (default is true). If false it will not convert image into webp format.

Teste

<a href="/portifolio/demo-delegacao/story.html" class="btn btn-sm btn-outline-primary btn-lg me-2 mb-lg-3 mb-xl-0 active" target="_blank">Experimente o projeto completo</a>

{{< button "click-me" "https://examplesite.com/" >}}

{{< tweet user="SanDiegoZoo" id="1453110110599868418" >}}

{{< gist johndoe 12345 >}}

{{< youtube w7Ft2ymGmfc >}}

{{< youtube id="w7Ft2ymGmfc" title="A New Hugo Site in Under Two Minutes" >}}

{{< vimeo 146022717 >}}



#### Heading example

Here is example of hedings. You can use this heading by following markdownify rules. For example: use `#` for heading 1 and use `######` for heading 6.

# Heading 1 
<br>

## Heading 2 

<br>

### Heading 3 

<br>

#### Heading 4 

<br>

##### Heading 5 

<br>

###### Heading 6


<hr>

##### Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~

<hr>

##### Link
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.themefisher.com
[1]: https://gethugothemes.com
[link text itself]: https://www.getjekyllthemes.com

<hr>

##### Paragraph

Lorem ipsum dolor sit amet consectetur adipisicing elit. Quam nihil enim maxime corporis cumque totam aliquid nam sint inventore optio modi neque laborum officiis necessitatibus, facilis placeat pariatur! Voluptatem, sed harum pariatur adipisci voluptates voluptatum cumque, porro sint minima similique magni perferendis fuga! Optio vel ipsum excepturi tempore reiciendis id quidem? Vel in, doloribus debitis nesciunt fugit sequi magnam accusantium modi neque quis, vitae velit, pariatur harum autem a! Velit impedit atque maiores animi possimus asperiores natus repellendus excepturi sint architecto eligendi non, omnis nihil. Facilis, doloremque illum. Fugit optio laborum minus debitis natus illo perspiciatis corporis voluptatum rerum laboriosam.

<hr>

##### Ordered List

1. List item
2. List item
3. List item
4. List item
5. List item

<hr>

##### Unordered List

* List item
* List item
* List item
* List item
* List item

<hr>

##### Code and Syntax Highlighting

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```
 
```python
s = "Python syntax highlighting"
print s
```

<hr>

##### Blockquote

> This is a blockquote example.

<hr>

##### Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
  <dt>Definition list</dt>
  <dd>Is something people use sometimes.</dd>

  <dt>Markdown in HTML</dt>
  <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>


<hr>

##### Tables

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

There must be at least 3 dashes separating each header cell.
The outer pipes (|) are optional, and you don't need to make the 
raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

<hr>

##### Image

![image](../../images/blog/post-6.jpg)

<hr>

##### Youtube video

{{< youtube C0DPdy98e4c >}}