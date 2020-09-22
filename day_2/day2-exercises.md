## Ch 3-4: Lists and Links  

**1. There are three main types of lists in HTML: ordered, unordered, and definition. What are their differences?**  
Ordered lists are lists where each item is numbered. Unordered lists are bullet points that don't necessarily indicate order. Definition lists are a set of terms and their definitions.  

**2. What is the basic structure of an element used to link to another website?**  
`<a href="">TEXT</a>`  

**3. What attribute should you include in a link to open a new tab when the link is clicked?**  
`target="_blank"`  

**4. How do you link to a specific part of the same page?**  
Give id attributes to the elements you want to jump to using a letter or an underscore, then use `<a href="#id">TEXT</a>`.  

## Ch 10-12: CSS, Color, and Text

**1. What is the purpose of CSS?**  
CSS allows you to create rules that specify how the content of an element should appear.  

**2. What does CSS stand for? What does cascading mean in this case?**  
Cascading Style Sheets   

**3. What is the basic structure of a CSS rule?**  
```CSS
selector {
  declaration;
};
```   

**4. How do you link a CSS stylesheet to your HTML document?**  
Put a `<link>` element inside of the `<head>` element:  
```HTML
<link href="css/styles.css" type="text/css" rel="stylesheet" />
```  

**5. When is it useful to use external stylesheets as opposed to using internal CSS?**  
You should use external stylesheets when building a site with more than one page because:  
* It allows all pages to use the same style rules instead of repeating them for each page.
* It keeps the content separate from how the page looks.
* It means you can change the styles used across all pages by altering just one file rather than each individual page.   

**6. Describe what a color hex code is.**  
6-digit codes that represent the amount of red, green, and blue in a color, preceded by a pound or hash sign.  

**7. What are the three parts of an HSL color property?**  
Hue, saturation, lightness.  

**8. In the world of typeface, what are the three main categories of fonts? What are the differences between them?**  
* Serif: has extra details on the ends of the main strokes of letters.
* Sans-serif: has straight ends to letters (cleaner design).
* Monospaced: every letter has fixed width (commonly used for code because they align nicely).  

**9. When specifying font-size, what are the main three units used?**  
Pixels, percentages, ems.  

**CodePen Link:** https://codepen.io/tashia-davis/pen/ExKGgqe
