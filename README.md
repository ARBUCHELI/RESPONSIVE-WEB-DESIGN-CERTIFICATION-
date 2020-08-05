# RESPONSIVE-WEB-DESIGN-CERTIFICATION-

## Solution to the problems of the Responsive Web Design Certification of www.freecodecamp.org 

## This material was created by www.freecodecamp.org and adapted as a repository for academic and self-consultation purposes.

## RESPONSIVE WEB DESIGN CERTIFICATION:

## BASIC HTML AND HTML5

## Introduction to Basic HTML & HTML5

HTML, or HyperText Markup Language, is a markup language used to describe the structure of a web page. It uses a special syntax or notation to organize and give information about the page to the browser. Elements usually have opening and closing tags that surround and give meaning to content. For example, there are different tag options to place around text to show whether it is a heading, a paragraph, or a list.

For example:
```html
<h1>Top level heading: Maybe a page title</h1>
<p>A paragraph of text. Some information we would like to communicate to the viewer. This can be as long or short as we would like.</p>
<ol>
  <li>Number one on the list</li>
  <li>Number two</li>
  <li>A third item</li>
</ol>
```

Becomes:

## Top level heading: Maybe a page title
A paragraph of text. Some information we would like to communicate to the user. This can be as long or short as we would like.
  1. Number one on the list
  2. Number two
  3. A third item

The HyperText part of HTML comes from the early days of the web and its original use case. Pages usually contained static documents that contained references to other documents. These references contained hypertext links used by the browser to navigate to the reference document so the user could read the reference document without having to manually search for it.

As web pages and web applications grow more complex, the W3 Consortium updates the HTML specification to ensure that a webpage can be shown reliably on any browser. The latest
version of HTML is HTML5.

This section introduces how to use HTML elements to give structure and meaning to your web content.

## 1. Basic HTML and HTML5: Say Hello to HTML ElementsPassed
Welcome to freeCodeCamp's HTML coding challenges. These will walk you through web development step-by-step.
First, you'll start by building a simple web page using HTML. You can edit code in your code editor, which is embedded into this web page.
Do you see the code in your code editor that says ```<h1>Hello</h1>```? That's an HTML element.

Most HTML elements have an opening tag and a closing tag.

Opening tags look like this:

```<h1>```

Closing tags look like this:

```</h1>```

The only difference between opening and closing tags is the forward slash after the opening bracket of a closing tag.

Each challenge has tests you can run at any time by clicking the "Run tests" button. When you pass all tests, you'll be prompted to submit your solution and go to the next coding challenge.

________________________________________________________________________________________________________________________________________________________________________________

To pass the test on this challenge, change your h1 element's text to say "Hello World".

```<h1>Hello World</h1>```

OUTPUT:

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/1.jpg)

## 2. Basic HTML and HTML5: Headline with the h2 ElementPassed
Over the next few lessons, we'll build an HTML5 cat photo web app piece-by-piece.
The ```h2``` element you will be adding in this step will add a level two heading to the web page.

This element tells the browser about the structure of your website. ```h1``` elements are often used for main headings, while ```h2``` elements are generally used for subheadings. There are also ```h3```, ```h4```, ```h5``` and ```h6``` elements to indicate different levels of subheadings.

________________________________________________________________________________________________________________________________________________________________________________

Add an ```h2``` tag that says "CatPhotoApp" to create a second HTML element below your "Hello World" ```h1``` element.

```html
<h1>Hello World</h1>
<h2>"CatPhotoApp"</h2>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/2.png)


## 3. Basic HTML and HTML5: Inform with the Paragraph Element

```p``` elements are the preferred element for paragraph text on websites. ```p``` is short for "paragraph".

You can create a paragraph element like this:

```<p>I'm a p tag!</p>```

________________________________________________________________________________________________________________________________________________________________________________

Create a ```p``` element below your ```h2``` element, and give it the text "Hello Paragraph".

<strong>Note:</strong> As a convention, all HTML tags are written in lowercase, for example ```<p></p>``` and not ```<P></P>```.

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>"Hello Paragraph"</p>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/3.jpg)


## 4. Basic HTML and HTML5: Fill in the Blank with Placeholder Text

Web developers traditionally use lorem ipsum text as placeholder text. The lorem ipsum text is randomly scraped from a famous passage by Cicero of Ancient Rome.

Lorem ipsum text has been used as placeholder text by typesetters since the 16th century, and this tradition continues on the web.

Well, 5 centuries is long enough. Since we're building a CatPhotoApp, let's use something called "kitty ipsum text".

________________________________________________________________________________________________________________________________________________________________________________

Replace the text inside your ```p``` element with the first few words of this kitty ipsum text: ```Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.```

```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/4.jpg)

## 5. Basic HTML and HTML5: Uncomment HTML

Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.

Commenting is also a convenient way to make code inactive without having to delete it entirely.

Comments in HTML start with ```<!--``` and end with a``` -->```

________________________________________________________________________________________________________________________________________________________________________________

Uncomment your ```h1```, ```h2``` and ```p``` elements.

```html
<h1>Hello World</h1>

<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/5.jpg)

## 6. Basic HTML and HTML5: Comment out HTML

Remember that in order to start a comment, you need to use ```<!--``` and to end a comment, you need to use ```-->```

Here you'll need to end the comment before your ```h2``` element begins.

________________________________________________________________________________________________________________________________________________________________________________

Comment out your ```h1``` element and your ```p``` element, but not your ```h2``` element.

```html
<!--
<h1>Hello World</h1>
-->
<h2>CatPhotoApp</h2>
<!--
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
-->
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/6.jpg)

## 7. Basic HTML and HTML5: Delete HTML Elements

Our phone doesn't have much vertical space.

Let's remove the unnecessary elements so we can start building our CatPhotoApp.

________________________________________________________________________________________________________________________________________________________________________________

Delete your h1 element so we can simplify our view.

```html
<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/7.jpg)

## 8. Basic HTML and HTML5: Introduction to HTML5 Elements

HTML5 introduces more descriptive HTML tags. These include ```main```, ```header```, ```footer```, ```nav```, ```video```, ```article```, section and others.

These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with Search Engine Optimization (SEO) and accessibility. The ```main``` HTML5 tag helps search engines and other developers find the main content of your page.

Example usage, a``` main``` element with two child elements nested inside it:

```html
<main> 
  <h1>Hello World</h1>
  <p>Hello Paragraph</p>
</main>
```
<strong>Note:</strong> Many of the new HTML5 tags and their benefits are covered in the Applied Accessibility section.

________________________________________________________________________________________________________________________________________________________________________________

Create a second ```p``` element after the existing ```p```element with the following kitty ipsum text: ```Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.```

Then, create a main element and nest the two p elements inside the main element.

```html
<h2>CatPhotoApp</h2>
<main>
<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
<p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/8.jpg)

## 9. Basic HTML and HTML5: Add Images to Your Website

You can add images to your website by using the ```img``` element, and point to a specific image's URL using the ```src``` attribute.

An example of this would be:

```html
<img src="https://www.your-image-source.com/your-image.jpg">
```

Note that ```img``` elements are self-closing.

All ```img``` elements <strong>must</strong> have an ```alt``` attribute. The text inside an ```alt``` attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.

<strong>Note:</strong> If the image is purely decorative, using an empty ```alt``` attribute is a best practice.

Ideally the ```alt``` attribute should not contain special characters unless needed.

Let's add an ```alt``` attribute to our ```img``` example above:

```html
<img src="https://www.your-image-source.com/your-image.jpg" alt="Author standing on a beach with two thumbs up.">
`````````
________________________________________________________________________________________________________________________________________________________________________________

Let's try to add an image to our website:

Within the existing ```main``` element, insert an ```img``` element before the existing ```p``` elements.

Now set the ```src``` attribute so that it points to this url:

```html
https://bit.ly/fcc-relaxing-cat
```

Finally, don't forget to give your ```img``` element an ```alt``` attribute with applicable text.

```html
<h2>CatPhotoApp</h2>
<main>
<img src="https://bit.ly/fcc-relaxing-cat" alt="Cute kitten.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/9.jpg)


## 10. Basic HTML and HTML5: Link to External Pages with Anchor Elements

You can use ```a``` (anchor) elements to link to content outside of your web page.

```a``` elements need a destination web address called an ```href``` attribute. They also need anchor text. Here's an example:

```html
<a href="https://freecodecamp.org">this links to freecodecamp.org</a>
```

Then your browser will display the text <strong>"this links to freecodecamp.org"</strong> as a link you can click. And that link will take you to the web address <strong>https://www.freecodecamp.org.</strong>

________________________________________________________________________________________________________________________________________________________________________________
Create an ```a``` element that links to ```https://freecatphotoapp.com``` and has "cat photos" as its anchor text.

```html
<h2>CatPhotoApp</h2>
<main>
<a href="https://freecatphotoapp.com">cat photos</a>
  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```






## Adaptation as a repository: Andrés R. Bucheli.





