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

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/1.jpg)

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

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/2.png)


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

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/3.jpg)


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

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/4.jpg)

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
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/5.jpg)

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
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/6.jpg)

## 7. Basic HTML and HTML5: Delete HTML Elements

Our phone doesn't have much vertical space.

Let's remove the unnecessary elements so we can start building our CatPhotoApp.

________________________________________________________________________________________________________________________________________________________________________________

Delete your h1 element so we can simplify our view.

```html
<h2>CatPhotoApp</h2>

<p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/7.jpg)

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
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/8.jpg)

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
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/9.jpg)

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
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/10.jpg)

## 11. Basic HTML and HTML5: Link to Internal Sections of a Page with Anchor ElementsPassed

```a``` (anchor) elements can also be used to create internal links to jump to different sections within a webpage.

To create an internal link, you assign a link's ```href``` attribute to a hash symbol ```#``` plus the value of the ```id``` attribute for the element that you want to internally link to, usually further down the page. You then need to add the same ```id``` attribute to the element you are linking to. An ```id``` is an attribute that uniquely describes an element.

Below is an example of an internal anchor link and its target element:

```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```
When users click the Contacts link, they'll be taken to the section of the webpage with the <strong>Contacts</strong> header element.

________________________________________________________________________________________________________________________________________________________________________________

Change your external link to an internal link by changing the ```href``` attribute to "#footer" and the text from "cat photos" to "Jump to Bottom".

Remove the ```target="_blank"``` attribute from the anchor tag since this causes the linked document to open in a new window tab.

Then add an ```id``` attribute with a value of "footer" to the ```<footer>``` element at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>

  <a href="#footer" >Jump to Bottom</a>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer id="footer">Copyright Cat Photo App</footer>
```
![img](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/11.jpg)

## 12. Basic HTML and HTML5: Nest an Anchor Element within a Paragraph

You can nest links within other text elements.

```html
<p>
  Here's a <a target="_blank" href="http://freecodecamp.org"> link to freecodecamp.org</a> for you to follow.
</p>
```
Let's break down the example: Normal text is wrapped in the ```p``` element:
```<p> Here's a ... for you to follow. </p>``` Next is the anchor element ```<a>``` (which requires a closing tag ```</a>```):
```<a> ... </a> target``` is an anchor tag attribute that specifies where to open the link and the value ```"_blank"``` specifies to open the link in a new tab ```href``` is an anchor tag attribute that contains the URL address of the link:
```<a href="http://freecodecamp.org"> ... </a>``` The text, <strong>"link to freecodecamp.org"</strong>, within the ```a``` element called ```anchor text```, will display a link to click:
```<a href=" ... ">link to freecodecamp.org</a>``` The final output of the example will look like this:

Here's a link to freecodecamp.org for you to follow.
_________________________________________________________________________________________________________________________________________________________________________________

Now nest the existing ```a``` element within a new ```p``` element (just after the existing ```main``` element). The new paragraph should have text that says "View more cat photos", where "cat photos" is a link, and the rest of the text is plain text.

```html
<h2>CatPhotoApp</h2>
<main>

<p>View more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a></p>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/12.jpg)

## 13. Basic HTML and HTML5: Make Dead Links Using the Hash Symbol

Sometimes you want to add <code>a</code> elements to your website before you know where they will link.

This is also handy when you're changing the behavior of a link using <code>JavaScript</code>, which we'll learn about later.
  
_________________________________________________________________________________________________________________________________________________________________________________

The current value of the <code>href</code> attribute is a link that points to "https://freecatphotoapp.com". Replace the <code>href</code> attribute value with a <code>#</code>, also known as a hash symbol, to create a dead link.

For example: <code>href="#"</code>

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>

  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/13.jpg)

## 14. Basic HTML and HTML5: Turn an Image into a Link

You can make elements into links by nesting them within an <code>a</code> element.

Nest your image within an <code>a</code> element. Here's an example:

```html
<a href="#"><img src="https://bit.ly/fcc-running-cats" alt="Three kittens running towards the camera."></a>
```

Remember to use <code>#</code> as your <code>a</code> element's <code>href</code> property in order to turn it into a dead link.

_________________________________________________________________________________________________________________________________________________________________________________

Place the existing image element within an <code>a</code> (anchor) element.

Once you've done this, hover over your image with your cursor. Your cursor's normal pointer should become the link clicking pointer. The photo is now a link.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

<a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/14.jpg)

## 15. Basic HTML and HTML5: Create a Bulleted Unordered List

HTML has a special element for creating unordered lists, or bullet point style lists.

Unordered lists start with an opening ```<ul>``` element, followed by any number of ```<li>``` elements. Finally, unordered lists close with a ```</ul>```

For example:

```html
<ul>
  <li>milk</li>
  <li>cheese</li>
</ul>
```
would create a bullet point style list of "milk" and "cheese".

_________________________________________________________________________________________________________________________________________________________________________________

Remove the last two <code>p</code> elements and create an unordered list of three things that cats love at the bottom of the page.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <ul>
    <li>Sleep</li>
    <li>Scratch</li>
    <li>Eat</li>
  </ul>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/15.jpg)

## 16. Basic HTML and HTML5: Create an Ordered List

HTML has another special element for creating ordered lists, or numbered lists.

Ordered lists start with an opening ```<ol>``` element, followed by any number of ```<li>``` elements. Finally, ordered lists are closed with the ```</ol>``` tag.

For example:

```html
<ol>
  <li>Garfield</li>
  <li>Sylvester</li>
</ol>
```
would create a numbered list of "Garfield" and "Sylvester".
_________________________________________________________________________________________________________________________________________________________________________________
Create an ordered list of the top 3 things cats hate the most.

_________________________________________________________________________________________________________________________________________________________________________________
```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>Other cats</li>
    <li>Being picked up</li>
    <li>Axe deodorant</li>
  </ol>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/16.jpg)

## 17. Basic HTML and HTML5: Create a Text Field

Now let's create a web form.

<code>input</code> elements are a convenient way to get input from your user.

You can create a text input like this:

```<input type="text">```

Note that <code>input</code> elements are self-closing.

_________________________________________________________________________________________________________________________________________________________________________________

Create an <code>input</code> element of type <code>text</code> below your lists.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text">

</main>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/17.jpg)

## 18. Basic HTML and HTML5: Add Placeholder Text to a Text Field

Placeholder text is what is displayed in your <code>input</code> element before your user has inputted anything.

You can create placeholder text like so:

```<input type="text" placeholder="this is placeholder text">```

<strong>Note:</strong> Remember that <code>input</code> elements are self-closing.

Set the <code>placeholder</code> value of your text <code>input</code> to "cat photo URL".

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <input type="text" placeholder="cat photo URL">
</main>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/18.jpg)

## 19. Basic HTML and HTML5:  Create a Form Element

You can build web forms that actually submit data to a server using nothing more than pure HTML. You can do this by specifying an action on your <code>form</code> element.

For example:

```<form action="/url-where-you-want-to-submit-form-data"></form>```
_________________________________________________________________________________________________________________________________________________________________________________

Nest the existing input element inside a <code>form</code> element and assign ```"https://freecatphotoapp.com/submit-cat-photo"``` to the <code>action</code> attribute of the <code>form</code> element.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo" ><input type="text" placeholder="cat photo URL"></form>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/19.jpg)

## 20. Basic HTML and HTML5: Add a Submit Button to a Form

Let's add a <code>submit</code> button to your form. Clicking this button will send the data from your form to the URL you specified with your form's <code>action</code> attribute.

Here's an example submit button:

```html
<button type="submit">this button submits the form</button>
```
_________________________________________________________________________________________________________________________________________________________________________________

Add a button as the last element of your <code>form</code> element with a type of <code>submit</code>, and "Submit" as its text.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>
</main>
```

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/20.jpg)

## 21. Basic HTML and HTML5: Use HTML5 to Require a FieldPassed

You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.

For example, if you wanted to make a text input field required, you can just add the attribute <code>required</code> within your input element, like this: 
```html<input type="text" required>```
_________________________________________________________________________________________________________________________________________________________________________________

Make your text <code>input</code> a <code>required</code> field, so that your user can't submit the form without completing this field.

Then try to submit the form without inputting any text. See how your HTML5 form notifies you that the field is required?

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <input type="text" required placeholder="cat photo URL">
    <button type="submit">Submit</button>
  </form>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/21.jpg)

## 22. Basic HTML and HTML5: Create a Set of Radio Buttons

You can use radio buttons for questions where you want the user to only give you one answer out of multiple options.

Radio buttons are a type of <code>input</code>.

Each of your radio buttons can be nested within its own <code>label</code> element. By wrapping an <code>input</code> element inside of a <code>label</code> element it will automatically associate the radio button input with the label element surrounding it.

All related radio buttons should have the same <code>name</code> attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.

Here's an example of a radio button:

```html<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
```

It is considered best practice to set a <code>for</code> attribute on the <code>label</code> element, with a value that matches the value of the <code>id</code> attribute of the <code>input</code> element. This allows assistive technologies to create a linked relationship between the label and the child <code>input</code> element. For example:

```html
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```

Add a pair of radio buttons to your form, each nested in its own <code>label</code> element. One should have the option of <code>indoor</code> and the other should have the option of <code>outdoor</code>. Both should share the <code>name</code> attribute of <code>indoor-outdoor</code> to create a radio group.

![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/22.jpg)

## 23. Basic HTML and HTML5: Create a Set of Checkboxes

Forms commonly use checkboxes for questions that may have more than one answer.

Checkboxes are a type of <code>input</code>.

Each of your checkboxes can be nested within its own <code>label</code> element. By wrapping an <code>input</code> element inside of a <code>label</code> element it will automatically associate the checkbox input with the label element surrounding it.

All related checkbox inputs should have the same <code>name</code> attribute.

It is considered best practice to explicitly define the relationship between a checkbox <code>input</code> and its corresponding <code>label</code> by setting the <code>for</code> attribute on the <code>label</code> element to match the <code>id</code> attribute of the associated <code>input</code> element.

Here's an example of a checkbox:

```html
<label for="loving"><input id="loving" type="checkbox" name="personality"> Loving</label>
```
_________________________________________________________________________________________________________________________________________________________________________________

Add to your form a set of three checkboxes. Each checkbox should be nested within its own <code>label</code> element. All three should share the <code>name</code> attribute of <code>personality</code>.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
    <label for="grumpy"><input id="grumpy" type ="checkbox" name="personality">Grumpy</label>
    <label for="snuggly"><input id="snuggly" type="checkbox" name="personality">Snuggly</label>
    <label for="adorable"><input id="adorable" type="checkbox" name="personality">Adorable</label>
  </form>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/23.jpg)

## 24. Basic HTML and HTML5: Use the value attribute with Radio Buttons and Checkboxes

When a form gets submitted, the data is sent to the server and includes entries for the options selected. Inputs of type <code>radio</code> and <code>checkbox</code> report their values from the <code>value</code> attribute.

For example:

```html
<label for="indoor">
  <input id="indoor" value="indoor" type="radio" name="indoor-outdoor">Indoor
</label>
<label for="outdoor">
  <input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor">Outdoor
</label>
```
Here, you have two <code>radio</code> inputs. When the user submits the form with the <code>indoor</code> option selected, the form data will include the line: <code>indoor-outdoor=indoor</code>. This is from the <code>name</code> and <code>value</code> attributes of the "indoor" input.

If you omit the <code>value</code> attribute, the submitted form data uses the default value, which is <code>on</code>. In this scenario, if the user clicked the "indoor"
option and submitted the form, the resulting form data would be <code>indoor-outdoor=on</code>, which is not useful. So the <code>value</code> attribute needs to be set to something to identify the option.

_________________________________________________________________________________________________________________________________________________________________________________

Give each of the <code>radio</code> and <code>checkbox</code> inputs the <code>value</code> attribute. Use the input label text, in lowercase, as the value for the attribute.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <label for="indoor"><input id="indoor" value="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" value="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>
    <label for="loving"><input id="loving" value="loving" type="checkbox" name="personality"> Loving</label>
    <label for="lazy"><input id="lazy" value="lazy" type="checkbox" name="personality"> Lazy</label>
    <label for="energetic"><input id="energetic" value="energetic" type="checkbox" name="personality"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/24.jpg)

## 25. Basic HTML and HTML5: Check Radio Buttons and Checkboxes by Default

You can set a checkbox or radio button to be checked by default using the <code>checked</code> attribute.

To do this, just add the word "checked" to the inside of an input element. For example:

```html
<input type="radio" name="test-name" checked>
```
_________________________________________________________________________________________________________________________________________________________________________________

Set the first of your radio buttons and the first of your checkboxes to both be checked by default.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label><br>
    <label for="loving"><input id="loving" type="checkbox" name="personality" value="loving" checked> Loving</label>
    <label for="lazy"><input id="lazy" type="checkbox" name="personality" value="lazy"> Lazy</label>
    <label for="energetic"><input id="energetic" type="checkbox" name="personality" value="energetic"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
```
![image](https://raw.githubusercontent.com/ARBUCHELI/RESPONSIVE-WEB-DESIGN-CERTIFICATION-/master/Pictures/25.jpg)

## 26. Basic HTML and HTML5: Nest Many Elements within a Single div Element

The <code>div</code> element, also known as a division element, is a general purpose container for other elements.

The <code>div</code> element is probably the most commonly used HTML element of all.

Just like any other non-self-closing element, you can open a div element with ```html<div>``` and close it on another line with ```html</div>```.

_________________________________________________________________________________________________________________________________________________________________________________

Nest your "Things cats love" and "Things cats hate" lists all within a single <code>div</code> element.

Hint: Try putting your opening <code>div</code> tag above your "Things cats love" <code>p</code> element and your closing <code>div</code> tag after your closing <code>ol</code> tag so that both of your lists are within one <code>div</code>.

```html
<h2>CatPhotoApp</h2>
<main>
  <p>Click here to view more <a href="#">cat photos</a>.</p>

  <a href="#"><img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back."></a>

<div>
  <p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
  <p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
</div>
  <form action="https://freecatphotoapp.com/submit-cat-photo">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor" value="indoor" checked> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor" value="outdoor"> Outdoor</label><br>
    <label for="loving"><input id="loving" type="checkbox" name="personality" value="loving" checked> Loving</label>
    <label for="lazy"><input id="lazy" type="checkbox" name="personality" value="lazy"> Lazy</label>
    <label for="energetic"><input id="energetic" type="checkbox" name="personality" value="energetic"> Energetic</label><br>
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
  </form>
</main>
```
![image]()






## Adaptation as a repository: Andrés R. Bucheli.





