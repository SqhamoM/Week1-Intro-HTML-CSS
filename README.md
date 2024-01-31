# Week1-Intro-HTML-CSS
HTML is everywhere, used in websites, apps, and various software whenever web technology is involved. It serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences. Essentially, it forms a solid foundation for everything else in the digital realm. 
HTMLelements 
HTML document is basically a bunch of HTML elements nested inside each other
Document Object Model.(DOM TREE)
The last paragraph has some emphasized text. To close the article, you use a closing article tag
HTML Paragraphs
 There are three chunks of text. Have Notepad++ open on the left with an HTML window and Chrome on the right for the results. However, these text chunks do not really resemble paragraphs.

HTML Headlines
The HTML elements used for marking up headlines come in six different types: h1, h2, h3, h4, h5, and h6
HTML Bold and Italics
There are four HTML elements related to this, two for bold and two for italic
<em>
<strong> which convey a specific meaning of the text
HTML Lists
wrapped as <li>
Unordered lists are the most commonly used type  <ul>
Ordred Lists
 Instead of using <ul> to wrap the list items, we use <ol>. The term "ol" stands for ordered list, indicating that there is a specific order to the items on the list.
 Definition lists
  Unlike unordered or ordered lists with their list items, the definition list is used when we want to create a list that resembles a key-value pair in computer science. Instead of just items, we have terms and their corresponding descriptions.
  We have <dt>, <dd>, <dl>
  HTML Quotes
These quotes help us format text on a webpage, like paragraphs, headlines, bold and italic styles, and lists but what about including a quote? 
<blockqoute> <cite>
Let's talk about quotes that are not block quotes and instead appear within the text. These quotes are simply typed in, but we believe they should be curly quotes, not straight ones. However, different languages and regions have their own conventions for displaying quote marks. 

To make things easier, we can use the "<q>" element in HTML, which stands for quote. By using this element, the browser will automatically provide the appropriate quote marks for us. In the example, the quote has been translated to different languages to show you how the quote marks differ. Comparing the block quote element to the "<q>" element is a good example of understanding HTML. Some HTML elements, like <strong>, <b>, <I>, and <em>, are called "inline" because they are meant to wrap around phrases of text that are inline with other content. They serve a similar purpose as the "<q>" element. There are many more inline elements that you can use in HTML.

There are certain elements in HTML known as block-level elements, like block quotes, paragraphs, and unordered lists. These elements essentially create separate blocks on the page. You can think of them as standalone entities that can be followed by another block. Some of this relates to CSS, where you can switch the layout behavior of elements from block to inline or vice versa. However, before you dive into thinking about layout or CSS, it is important to understand the inherent nature of these HTML elements. 

Some elements serve as markers for something that is part of a larger entity, while others represent the larger entity itself. Let's take the example of block quotes and the "<q>" element. They may seem similar, but they serve different purposes. One is used for inline phrases, while the other creates a block context. These are the ways to markup quotes using the block quote, "<q>", and cite elements.
USING TIME DATE
We write it like this: <time datetime="2025-05-08">May 8, 2025</time>
USING DATE ELEMENTS
 HTML Code, pre and br
 HTML Entity called &lt and will be dispalyed as less than < sign
 HTML Entiy called &gt which will be displayed as greatert than > sign
 Using Br element 
 Imagine we have a poem that we want to display properly on the webpage. Right now, the browser is ignoring the line breaks in the poem, and it looks all jumbled up. On the left, you can see how the formatting adds meaning to the poem. We do not want to treat each line as a separate paragraph because it is not. We simply want a line break at the end of each line that the browser will recognize. 
 <pre></pre>
HTML Superscripts, Subscripts and Small Text
Subscripts are characters that are set below the normal baseline for text. 
Superscripts are characters that are set above the normal baseline of text. <sup>
Troubleshooting and Debugging HTML Code UNIT 3

In the right pane, you can find additional tabs with layout tools, a list of CSS changes made, and information about fonts. For now, concentrate on the left pane, which displays our HTML. Here, we can see the Document Object Model (DOM) created by the browser. When we sent the HTML to Firefox, it read it and made its own version of it, trying to fix any mistakes we may have made along the way."
eview this problematic code. There is an unordered list with four items that should be numbered one, two, three, four. But if you check the results, there is a blank one in there, messing up the count and giving us five items. Why is this happening? 
Review this problematic code. There is an unordered list with four items that should be numbered one, two, three, four. But if you check the results, there is a blank one in there, messing up the count and giving us five items. Why is this happening? 

Well, open the developer tools by right-clicking and take a closer look. It turns out the browser is doing some fixing to the HTML it received while building the DOM tree. It believes there should be five items: one, two, empty, three, four. The browser is adding an extra set of tags. 

Return to the original HTML code, and before the third item, the mistake occurred. Instead of ending the previous list item, we mistakenly started a new one. Correct this by adding the missing slash. This will fix the DOM. Whenever you are unsure about what is happening, just turn to the developer tools in your browser to figure things ou
The <img> tag is used to embed an image in an HTML page
<img src="img_girl.jpg">
The width and height Attributes
The <img> tag should also contain the width and height attributes, which specify the width and height of the image (in pixels)
<!DOCTYPE html>
<html>
<body>

<h2>Width and Height Attributes</h2>

<p>The width and height attributes of the img tag, defines the width and height of the image:</p>

<img src="img_girl.jpg" width="500" height="600">

</body>
</html>

THE ALT ATTRIBUTE 
<img src="img_girl.jpg" alt="Girl with a jacket">
THE STYLE ATTRIBUTE 
The style attribute is used to add styles to an element, such as color, font, size, and more.

<p style="color:red;">This is a red paragraph.</p>
<!DOCTYPE html>
<html>
<body>

<h2>The style Attribute</h2>
<p>The style attribute is used to add styles to an element, such as color:</p>

<p style="color:red;">This is a red paragraph.</p>

</body>
</html>

THE LANG ATTRIBUTE 
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
THE TITLE ATTRIBUTE






HTML HEADINGS
BIGGER HEADINGS-SPCIFY THE FONT SIZE AND STYLE THE HEADING 
<h1 style="font-size:60px;">Heading 1</h1>

The title attribute defines some extra information about an element.

lINK ELEMENTS 
<a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
<p title=About W3Schools>
The href attribute of <a> specifies the URL of the page the link goes to
The src attribute of <img> specifies the path to the image to be displayed
The width and height attributes of <img> provide size information for images
The alt attribute of <img> provides an alternate text for an image
The style attribute is used to add styles to an element, such as color, font, size, and more
The lang attribute of the <html> tag declares the language of the Web page
The title attribute defines some extra information about an element

