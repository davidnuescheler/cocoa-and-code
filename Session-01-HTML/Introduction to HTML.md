# Tools of the Trade

To get started with coding, you need three things, 

1. a browser (Chrome)
2. an internet connection and Google
3. a text editor

as for the text editor i am using http://brackets.io/

# Your first HTML document

HTML is the first of three main languages that your browser understands.
Create an HTML document with the extension .html and paste:

~~~~ html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
~~~~

open in browser by double clicking, and see via "view source".

## Tags

The stuff inside brackets are called tags and they really are the instructions to browser. just think of `<!DOCTYPE html>` as something that tells that computer what language this file is in, and as `<html>` as your beginning of your documents.

Most HTML tags have closing tags that start with a `/`, which indicate the end of a section. So `<html>` pairs up with the corresponding `<\html>` at the very end of the document, or `<h1>` and `</h1>`. 

Brackets (your text editor) will help you with this a little bit, and whenever you write an opening tag, it will automatically provide a closing tag.

To make things simple, always lowercase your tags.

## White space and formatting

HTML ignores all white space (more than one space, linefeed, tabs, etc.) are all just considered one space. This means that you can layout your code in your text editor however you want without impacting the result.

Try to add some blank lines into you document possibly between the words `first` and `paragraph`, save, reload your browser window (or reopen your document) and you will see that this has no impact. 


## Headings

Headings are using `<h1>` ... `</h1>`, `<h2>` ... `</h2>`, `<h3>` ... `</h3>` tags. The number indicates the importance of the heading an is not an enumeration of the heading. `<h1>` indicates the most imporant, top heading of a document, `<h2>` the second most important. Use this to structure your document, and create a couple of headings, save and reload in your browser.

## Text

To define that you have some text you can use the `<p>` ... `</p>` tag. `p` stands for "Paragraph". Just try it out, and add some more paragraphs to your document, hit save and reload in the browser to see the effect.

## Images & Attributes

Images are added with the `<img>` tag. The image tag doesn't have a closing tag, as it is not possibly to nest something inside and image. Copy an image next to your `.html` file and reference it using the filename. So something like `<img src="bread.jpg">`, where `bread.jpg` would be replaced with your image name.

`src="bread"` inside the `<img ... >` tag is called an "attribute" and attributes are common in many tags, and give the browser additional information on what to do with the tag, in the case of the `<img ...>` it tells the browser which image you want.

## Links

One of the most important features of the web is to be able creat links. To create a link you use the `<a>` ... `</a>` tag (stands for "Anchor"), with a `href=` attribute that specifies the destination URL (Web Address) of your link. So for example `<a href="https://unsplash.com/collections/358125/bread">` ... `<\a>` brings you to: https://unsplash.com/collections/358125/bread when you click on the link

## Lists

There are two popular lists, ordered lists and unordered list. It is pretty easy to guess what they do, the tags are `<ol>` ... `</ol>` and `<ul>` ... `</ul>`. Nested in there every list item is separated with `<li>` ... `</li>` tags. Try it out, save and reload in your browser.

## Tables

Tables are a more complicated construct. Here is an example, easy to figure out:

~~~~ html
<table>
    <tr>
        <td>Flour</td>
        <td>1000g</td>
    </tr>
    <tr>
        <td>Water</td>
        <td>700ml </td>
    </tr>
    <tr>
        <td>Salt</td>
        <td>25g</td>
    </tr>
    <tr>
        <td>Yeast</td>
        <td>7g</td>
    </tr>
</table>
~~~~

`tr` stands for "table row", `td` stands for "table data". have fun playing with it.

## Homework

Create a tic-tac-toe board using the `x.png` and `o.png` in this [folder](https://github.com/davidnuescheler/cocoa-and-code/blob/master/Session-01-HTML/). When someone clicks on the `x` it should link to a page, that says "you clicked on x" and when someone clicks on the `o` it should link to a page, that says "you clicked on o".
