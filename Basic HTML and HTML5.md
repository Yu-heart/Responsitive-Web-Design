## Basic HTML and HTML5
`HTML` is a markup language that uses a `special syntax` or `notation` to describe the `structure of a webpage` to the `browser`. `HTML` elements usually have `opening and closing tags` that surround and give meaning to content. For example, different elements can describe text as a `heading`, `paragraph`, or `list item`.  
In this course, you'll build a `cat photo app` to learn some of the most common HTML elements — the `building blocks` of any webpage.  

### 01. **Say Hello World to HTML Elements**  
```html
<h1>Hello World</h1>    
<!-- 
    This is an HTML element. Most HTML elements have an opening tag and a closing tag.
    -->
```  
### 02. **Headline with the h2 Element**  
```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<h3>this is a heading 3 element</h3>
<!--The h2 element you will be adding in this step will add a level two heading to the web page.  
This element tells the browser about the structure of your website.      
h1 elements are often used for main headings, while h2 elements are generally used for subheadings.   
There are also h3, h4, h5 and h6 elements to indicate different levels of subheadings.
-->
```
### 03. **Inform with the Paragraph Element**  
`p` elements are the preferred element for paragraph text on websites. `p` is short for "paragraph".  
You can create a paragraph element like this:    
```html
<p>Hello Paragraph</p>
```
### 04. **Fill in the Blank with Placeholder Text**  
Web developers traditionally use `lorem ipsum text` as `placeholder text`. The `lorem ipsum text` is randomly scraped from a famous passage by Cicero of `Ancient Rome`.  
`Lorem ipsum` text has been used as placeholder text by typesetters since `the 16th century`, and this tradition continues on the web.  
Learn more about `lorem ipsum`: [lorem ipsum Wikipedia](https://en.wikipedia.org/wiki/Lorem_ipsum)  
Well, `5 centuries` is long enough. Since we're building a CatPhotoApp, let's use something called `"kitty ipsum"` text.  
```html
<h1>Hello World</h1>
<h2>CatPhotoApp</h2>
<p>kitty ipsum</p>  
<!--kitty ipsum replace the text inside p element with the first few words of this kitty ipsum text: Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.-->
```  
### 05. **HTML Comments**  
Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.  
Commenting is also a convenient way to make code inactive without having to delete it entirely.  
`Comments` in HTML start with `<!-- `and end with a `-->`

### 06. **Introduction to HTML5 Elements**  
HTML5 introduces more descriptive HTML tags. These include `main`, `header`, `footer`, `nav`, `video`, `article`, `section` and others.  
These tags give a descriptive structure to your HTML, make your HTML easier to read, and help with `Search Engine Optimization (SEO)` and `accessibility`.    
The main HTML5 tag helps search engines and other developers find the main content of your page.  
Example usage, a `main` element with two child elements nested inside it:  
```html
<h2>CatPhotoApp</h2>
<main> 
    <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
    <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```  
Note: Many of the new HTML5 tags and their benefits are covered in the `Applied Accessibility` section.

### 07. **Add Images to Your Website**  
You can add images to your website by using the `img` element, and point to a specific image's URL using the `src` attribute.  
An example of this would be:  
```html
<img src="https://www.freecatphotoapp.com/your-image.jpg">
<!--Note that img elements are self-closing.-->
```  
All `img` elements must have an `alt` attribute. The text inside an alt attribute is used for screen readers to improve accessibility and is displayed if the image fails to load.  
Note: If the image is `purely decorative`, using an `empty alt attribute` is a best practice. Ideally the `alt` attribute should not contain `special characters` unless needed.  
Let's add an alt attribute to our img example above:  
```html
<img src="https://www.freecatphotoapp.com/your-image.jpg" alt="A business cat wearing a necktie.">
```
Here's the `HTML code` about `CatPhotoApp project`.       
```html
<h2>CatPhotoApp</h2>
<main>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```  
### 08. **Link to External Pages with Anchor Elements**  
You can use `a` (anchor) elements to link to content outside of your web page.  
`a` elements need a `destination web address` called an `href` attribute. They also need anchor text. Here's an example:  
```html
<a href="https://www.freecodecamp.org">this links to freecodecamp.org</a>
```  
Then your browser will display the text `this links to freecodecamp.org` as a link you can click. And that link will take you to the web address `https://www.freecodecamp.org`.  

Here's the `HTML code` about `CatPhotoApp project`.
```html
<h2>CatPhotoApp</h2>
<main>

  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a> <!--`target="_blank"` attribute causes the linked document to open in a new window tab.-->

  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer>Copyright Cat Photo App</footer>
```  
### 09. **Link to Internal Sections of a Page with Anchor Elements**  
`a` (anchor) elements can also be used to create `internal links` to jump to different sections within a webpage.  
To create an internal link, you assign a link's `href` attribute to a hash symbol `#` plus the value of the `id` attribute for the element that you want to internally link to, usually further down the page. You then need to add the same `id` attribute to the element you are linking to. An `id` is an attribute that uniquely describes an element.  
Below is an example of an internal anchor link and its target element:  
```html
<a href="#contacts-header">Contacts</a>
...
<h2 id="contacts-header">Contacts</h2>
```  
When users click the `Contacts` link, they'll be taken to the section of the webpage with the **Contacts** heading element.

Here's the `HTML code` about `CatPhotoApp project`.  
```html
<h2>CatPhotoApp</h2>
<main>

  <a href="#footer">Jump to Bottom</a>

  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer id="footer">Copyright Cat Photo App</footer>
```  
### 10. **Nest an Anchor Element within a Paragraph**  
You can nest links within other text elements.  
```html
<p>
  Here's a <a target="_blank" href="https://www.freecodecamp.org"> link to www.freecodecamp.org</a> for you to follow.
</p>
```  
Let's break down the example. Normal text is wrapped in the `p` element:  
```html
<p> Here's a ... for you to follow. </p>
```  
Next is the anchor element `<a>` (which requires a closing tag `</a>`):  
```html
<a> ... </a>
```  
`target` is an anchor tag attribute that specifies where to open the link. The value `_blank` specifies to open the link in a new tab. The `href` is an anchor tag attribute that contains the URL address of the link:  
```html
<a href="https://www.freecodecamp.org" target="_blank"> ... </a>
```  
The text, `link to www.freecodecamp.org`, within the `a` element is called anchor text, and will display the link to click:  
```html
<a href=" ... " target="...">link to freecodecamp.org</a>
```  
The final output of the example will look like this:  
Here's a [link to www.freecodecamp.org](https://www.freecodecamp.org) for you to follow.  

Here's the `HTML code` about `CatPhotoApp project`.  
```html
<h2>CatPhotoApp</h2>
<main>
  <p>View more cat photos, where  
  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a> is a link, and the rest is plain text.
  </p>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
 
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```   
### 11. **Make Dead Links Using the Hash Symbol**  
Sometimes you want to add `a` elements to your website before you know where they will link.  
This is also handy when you're changing the behavior of a link using `JavaScript`, which we'll learn about later.  
The current value of the `href` attribute is a link that points to "`https://www.freecatphotoapp.com`". Replace the `href` attribute value with a `#`, also known as a hash symbol, to create a `dead link`.  
For example: `href="#"`
```html
<p>Click here to view more <a href="#" target="_blank">cat photos</a>.</p>
```  
### 12. **Turn an Image into a Link**  
You can make elements into links by nesting them within an `a` element.  
Nest your image within an `a` element. Here's an example:  
```html
<a href="#"><img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="Three kittens running towards the camera."></a>
```  
Remember to use `#` as your a element's `href` property in order to turn it into a `dead link`.  

Once you've done this, `hover` over your image with your `cursor(光标)`. Your cursor's normal pointer should become the link clicking pointer. `The photo is now a link`.

### 13. **Create a Bulleted Unordered List**  
HTML has a special element for creating `unordered lists`, or `bullet point style lists`.  
Unordered lists start with an opening `<ul> `element, followed by any number of `<li>` elements. Finally, unordered lists close with a `</ul>`.  
For example:  
```html
<p>Things cats love:</p>
  <ul>
    <li>cat nip</li>
    <li>laser pointers</li>
    <li>lasagna</li>
  </ul>
```  
### 14. **Create an Ordered List**  
HTML has another special element for creating `ordered lists`, or `numbered lists`.  
Ordered lists start with an opening `<ol>` element, followed by any number of `<li>` elements. Finally, ordered lists are closed with the `</ol>` tag.  
For example:  
```html
<p>Top 3 things cats hate:</p>
  <ol>
    <li>flea treatment</li>
    <li>thunder</li>
    <li>other cats</li>
  </ol>
```  
### 15. **Create a Text Field**  
Now let's create a web form.  
`input` elements are a convenient way to get input from your user.  
You can create a text input like this:  
```html
<input type="text">
```  
Note that `input` elements are `self-closing`.

### 16. **Add Placeholder Text to a Text Field**
`Placeholder text` is what is displayed in your `input` element before your user has inputted anything.  
You can create placeholder text like so:  
```html
<input type="text" placeholder="this is placeholder text">
```  
Note: Remember that `input` elements are `self-closing`.  

### 17. **Create a Form Element**  
You can build web forms that actually submit data to a server using nothing more than `pure HTML`. You can do this by specifying an `action` attribute on your `form` element.  
For example:  
```html
<form action="/url-where-you-want-to-submit-form-data">
  <input type="text" placeholder="cat photo URL">
</form>
```  
### 18. **Add a Submit Button to a Form**  
Let's add a `submit` button to your form. Clicking this button will send the data from your form to the URL you specified with your form's `action` attribute.  
Here's an example submit button:  
```html
<button type="submit">this button submits the form</button>
``  
Here's HTML code about CatphotoApp.  
```html
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL">
    <button type="submit">Submit</button>
</form>
```  
### 19.**Use HTML5 to Require a Field**  
You can require specific form fields so that your user will not be able to submit your form until he or she has filled them out.  
For example, if you wanted to make a text input field required, you can just add the attribute `required` within your `input` element, like this: `<input type="text" required>`  
Here's an example:  
```html
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
</form>
```  
### 20. **Create a Set of Radio Buttons**  
You can use `radio buttons` for questions where you want the user to only give you one answer out of multiple options.

Radio buttons are a type of `input`. 

Each of your radio buttons can be nested within its own `label` element. By wrapping an `input` element inside of a `label` element it will automatically associate the radio button input with the label element surrounding it.  

All related radio buttons should have the same `name` attribute to create a radio button group. By creating a radio group, selecting any single radio button will automatically deselect the other buttons within the same group ensuring only one answer is provided by the user.  

Here's an example of a radio button:  
```html
<label> 
  <input type="radio" name="indoor-outdoor">Indoor 
</label>
```
It is considered best practice to set a `for` attribute on the `label` element, with a value that matches the value of the `id` attribute of the `input` element. This allows assistive technologies to create a linked relationship between the label and the related input element.  
For example:  
```html
<input id="indoor" type="radio" name="indoor-outdoor">
<label for="indoor">Indoor</label>
```  
We can also nest the `input` element within the `label` tags:  
```html
<label for="indoor"> 
  <input id="indoor" type="radio" name="indoor-outdoor">Indoor 
</label>
```  
Here's HTML code about CatphotoApp.   
```html
<form action="https://www.freecatphotoapp.com/submit-cat-photo">
    <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"> Indoor</label>
    <label for="outdoor"><input id="outdoor" type="radio" name="indoor-outdoor"> Outdoor</label><br>

    <input type="text" placeholder="cat photo URL" required>
    <button type="submit">Submit</button>
</form>
```  
### 21.**Create a Set of Checkboxes**




### Basic CSS  
### Applied Visual Design  
### Applied Accessibility  
### Responsive Web Design Principles  
### CSS Flexbox  
### CSS Grid  
### Responsive Web Design Projects  
