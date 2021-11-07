## **Responsive Web Design**(响应式Web设计)
在响应式Web设计课程中，你将学习开发者搭建网站的两种语言`HTML`和`CSS`：
* `HTML (Hypertext Markup Language)` for `content`.  
* `CSS (Cascading Style Sheets)` for `design`.  
首先，你将通过建立一个 `cat photo app`来学习基础的`HTML`和`CSS`;  
然后，你将通过建立一个`penguin`来学习`CSS variables`等现代技术，并通过构建`Web form`来学习`accessibility`技术.  
最后，你将通过使用`Flexbox`构建`Twitter card`,`CSS Grid`构建`complex blog layout(复杂的博客布局)`来学习制作`respond to different screen sizes(响应不同屏幕尺寸)`的网页.  

### Basic HTML and HTML5
`HTML` is a markup language that uses a `special syntax` or `notation` to describe the `structure of a webpage` to the `browser`. `HTML` elements usually have `opening and closing tags` that surround and give meaning to content. For example, different elements can describe text as a `heading`, `paragraph`, or `list item`.  
In this course, you'll build a `cat photo app` to learn some of the most common HTML elements — the `building blocks` of any webpage.  

#### 01. **Say Hello World to HTML Elements**  
```html
<h1>Hello World</h1>    
<!-- 
    This is an HTML element. Most HTML elements have an opening tag and a closing tag.
    -->
```  
#### 02. **Headline with the h2 Element**  
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
#### 03. **Inform with the Paragraph Element**  
`p` elements are the preferred element for paragraph text on websites. `p` is short for "paragraph".  
You can create a paragraph element like this:    
```html
<p>Hello Paragraph</p>
```
#### 04. **Fill in the Blank with Placeholder Text**  
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
#### 05. **HTML Comments**  
Commenting is a way that you can leave comments for other developers within your code without affecting the resulting output that is displayed to the end user.  
Commenting is also a convenient way to make code inactive without having to delete it entirely.  
`Comments` in HTML start with `<!-- `and end with a `-->`    
#### 06. **Introduction to HTML5 Elements**  
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
#### 07. **Add Images to Your Website**  
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
Here's the complete html code about `CatPhotoApp project`.       
```html
<h2>CatPhotoApp</h2>
<main>
  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">
  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>
```  
#### 08. **Link to External Pages with Anchor Elements**  
You can use `a` (anchor) elements to link to content outside of your web page.  
`a` elements need a `destination web address` called an `href` attribute. They also need anchor text. Here's an example:  
```html
<a href="https://www.freecodecamp.org">this links to freecodecamp.org</a>
```  
Then your browser will display the text `this links to freecodecamp.org` as a link you can click. And that link will take you to the web address `https://www.freecodecamp.org`.  
Here's the complete html code about `CatPhotoApp project`.
```html
<h2>CatPhotoApp</h2>
<main>

  <a href="https://www.freecatphotoapp.com" target="_blank">cat photos</a>

  <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched. Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff. Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
  <p>Meowwww loved it, hated it, loved it, hated it yet spill litter box, scratch at owner, destroy all furniture, especially couch or lay on arms while you're using the keyboard. Missing until dinner time toy mouse squeak roll over. With tail in the air lounge in doorway. Man running from cops stops to pet cats, goes to jail.</p>
  <p>Intently stare at the same spot poop in the plant pot but kitten is playing with dead mouse. Get video posted to internet for chasing red dot leave fur on owners clothes meow to be let out and mesmerizing birds leave fur on owners clothes or favor packaging over toy so purr for no reason. Meow to be let out play time intently sniff hand run outside as soon as door open yet destroy couch.</p>

</main>

<footer>Copyright Cat Photo App</footer>
```  
#### 09. **Link to Internal Sections of a Page with Anchor Elements**  





### Basic CSS  
### Applied Visual Design  
### Applied Accessibility  
### Responsive Web Design Principles  
### CSS Flexbox  
### CSS Grid  
### Responsive Web Design Projects  
