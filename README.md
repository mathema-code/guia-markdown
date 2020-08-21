# Guia Markdown


Seu guia completo de Markdown para Jupyterlab e Google Colab.



## Editores de Markdown

* Você pode usar Markdown em qualquer lugar. Inclusive este arquivo foi editado em Markdown.
* Editores que recomendamos:
    - [Dillinger](https://dillinger.io/)
    - [IA Writer](https://ia.net/writer)

Sobre o histórico do Markdown

https://dillinger.io/

https://remarkjs.com/#18 (slide)

http://jdan.github.io/cleaver/#4 (slide)

https://markdown-here.com/ (email)

#


# H1
## H2
### H3

----------------
### Bold

**bold text**
I love __boldtext__.
----------------
### Italic

*italicized text*
The _cat's meow_
----------------

### Bold and Italic
1 ***Important***text. 2
3 ___Important___text. 4
5 __*Important*__text. 6
7 **_Important_**text.

----------------
### Blockquote

> blockquote

1 >Thisthefirstparagraph. 
2 >
3 >Andthisisthesecondparagraph

### Nested Blockquotes
1 >Thisthefirstparagraph. 
2 >
3 >>Andthisisthenestedparagraph
----------------
### Ordered List

1. First item
2. Second item
3. Third item
	1. aa
	1. bb
	1. cc
----------------
### Unordered List

- First item
- Second item
- Third item

* First item
+ Second item
- Third item
----------------
### Code

`code`

```code```
----------------
Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```
----------------
### Horizontal Rule
---
-----------------
### Link

[title](https://www.example.com)
-----------------
### Url e email
1 <https://eff.org>
2 <fake@example.com>
-----------------
### Image

![alt text](image.jpg)
<img src="images/tux.png" alt="Tux" />
-----------------
## Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.
-----------------
### Table

| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
-----------------
### Fenced Code Block

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}

### Footnote

Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.

### Heading ID

### My Great Heading {#custom-id}

### Definition List

term
: definition

### Strikethrough

~~The world is flat.~~

### Task List

- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

### Strikethrough
The worl dis~~flat~~round.
