# Recommended Assignment - That Portfolio Though

## Overview

In this assignment, you'll build a professional portfolio site using HTML/CSS. These instructions include a short style guide; follow it to design an aesthetically pleasing layout while creating different kinds of complex HTML elements.

### Before You Begin

* Welcome to your first opportunity as a front-end web designer. You will be advocating for your most important client—yourself! By making a portfolio, you'll take your first step toward building your web development brand.

* This will be one of your harder assignments, if only because you're just getting your feet wet in web design. Trust us, though; it will get easier. Invest your time in this assignment, and it will pay dividends!

### Commits

Having an active and healthy commit history on GitHub is important for your future job search. It is also extremely important for making sure your work is saved in your repository. If something breaks, committing often ensures you are able to go back to a working version of your code.

* Committing often is a signal to employers that you are actively working on your code and learning.

  * We use the mantra “commit early and often.”  This means that when you write code that works, add it and commit it!

  * Numerous commits allow you to see how your app is progressing and give you a point to revert to if anything goes wrong.

* Be clear and descriptive in your commit messaging.

  * When writing a commit message, avoid vague messages like "fixed." Be descriptive so that you and anyone else looking at your repository knows what happened with each commit.

* We would like you to have well over 200 commits by graduation, so commit early and often!

### Submission on BCS

* Please submit the link to the Github Repository!

### Instructions

1. Create a new repository in GitHub called `Basic-Portfolio`.

2. Clone this repository to your computer using the process we went over in class.

3. Navigate to the `Basic-Portfolio` folder that you just cloned onto your machine. Inside this folder, create the following:

   * 3 HTML documents: `index.html`, `contact.html` and `portfolio.html`.
   * A folder called `assets`.
   * Inside the assets directory, make two additional folders: `css` and `images`.
     * In the `css` folder, make a file called `style.css`.
     * In the `images` folder, save the images you plan on using (like your profile image and the placeholder images for the portfolio).

4. Push the above changes to GitHub.

   * Make sure to `git add .` and `git commit -m "initial site files"`. Then type `git push origin master` to push your changes to your GitHub repo.

5. Reference these screenshots for your site:

   ![Portfolio About](Images/portfolio-about-me.png)

   ![Portfolio Contact](Images/portfolio-contact.png)

   ![Portfolio Gallery](Images/portfolio-gallery.png)

   * **IMPORTANT** Your site's layout must match the designs in these screenshots. You'll find the specs for these designs below.

6. When you create a website, it's standard practice to code your HTML files before writing any CSS and to write up one HTML file before moving onto the next. Write your HTML semantically, too:

   * If something is a heading, you use a heading tag.
   * If something is a list, you use an unordered or ordered list tag.
   * So on and so forth.

7. The content for the `index.html` should be unique to **you**.

   * Write a paragraph or two about yourself. Make it fun, show your personality!
   * The main logo where it says "Your Name" should say your name. This may make the logo section smaller or wider depending on how long your name is—that is fine and expected.
   * Add, commit, and push your code to GitHub often, especially when you complete a page.

8. After all of your HTML is written, you can begin styling your pages using the `style.css` file you created.

   * Be sure to [validate your html](https://validator.w3.org/#validate_by_input).
   * Consult the specs below these instructions for advice on styling your CSS files.

9. Push your changes to Github.

### Additional Specifcations

1. Colors _Pro-tip: Use the [Eye Dropper](https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka) Chrome extension to find the colors used on web pages._
   * Teal color (used for headings and backgrounds): `#4aaaa5`
   * Regular font color (used for paragraphs and all text besides the headings): `#777777`
   * Main header background color: `#ffffff`
   * Main header border color: `#cccccc`
   * Footer background color: `#666666`
   * Main content background color: `#ffffff`
   * Main content border color: `#dddddd`

2. Fonts:
   * For heading fonts use `font-family: 'Georgia', Times, Times New Roman, serif;`.
   * For all other fonts use `'Arial', 'Helvetica Neue', Helvetica, sans-serif;`.

3. Profile Image Found on `index.html`:
   * Use a picture of yourself.
   * If you don't have a picture, you can grab a placeholder image from [LoremPixel](http://lorempixel.com/). Save the images to your `images` folder.

4. Portfolio Images:
   * Placeholder images can be found at [LoremPixel](http://lorempixel.com/).
   * Save the images to your `images` folder.

5. Background Images:
   * The background pattern used was found on [Subtle Patterns](https://subtlepatterns.com/). You can browse through that site and find whichever pattern you like.

6. Dimensions:
   * The entire content and the main section content area is `960px` wide.

   ![Recommended Dimensions](Images/Recommended-Dimensions.png)

### Bonus

1. Make your pages more sophisticated by adding style to text links, to image links, and to buttons for when a user hovers their cursor over them. A CSS hover tutorial can be found [here](http://www.codeitpretty.com/2013/06/how-to-use-css-hover-effects.html).

2. You can use [Adobe Kuler](https://color.adobe.com/create/color-wheel/) to find colors that match the theme (in this case, the primary color is Teal `#4aaaa5`).

3. Make a "sticky footer." You will notice the dark grey footer will always rest just below the content. This is fine whenever your site has enough content to push it down past the height of most monitors. But if there isn't much content in the body, the footer could rest in the middle of the page:
   * Try to code the footer in a way that it will always remain at the bottom of the page, no matter how short the content is. A sticky footer tutorial can be found [here](https://css-tricks.com/couple-takes-sticky-footer/).
   * Give the Footer the following CSS:
   * border-top: 8px solid #4aaaa5;

### Helpful Hints

* For help with Git and GitHub, be sure to consult the GitHub Supplemental Guide sent to you in class.

* Don't forget to look into these concepts: `float`, `padding`, `margin`, `display`, `overflow`, `clear` and `text-align`.

* This will be a tough assignment, but towards the end of the course, you'll look back to this exercise and realize just how much you've grown as a developer. Stay positive! You've got this!

### Reminder: Submission on BCS

* Please submit the link to the Github Repository!

- - -

### Minimum Requirements

Attempt to complete homework assignment as described in instructions. If unable to complete certain portions, please pseudocode these portions to describe what remains to be completed.

- - -

### One More Thing

If you have any questions about this project or the material we have covered, please post them in the community channels in slack so that your fellow developers can help you! If you're still having trouble, you can come to office hours for assistance from your instructor and TAs.

**Good Luck!**
.container {
    width: 100%;
    max-width: 60px;
    margin: 0 auto;
    clear: both;
}

h1, h2, h3, p {
    margin-bottom: 0;
}


/* Header */

#masthead {
    background: #ffffff;
    margin: 0 0 30px;
    z-index: 99;
    color: #ffffff;
    overflow: auto;
    border-bottom: 2px solid #cccccc;
    position: fixed;
    width: 100%;
}

#logo {
    width: 250px;
    height: 90px;
    background: #4aaaa5;
    float: left;
    font-family: Georgia, 'Times New Roman', Times, serif;
    text-align: center;
    line-height: 90px;
    color: #fff;
    font-weight: 700;
    font-size: 30px;
    text-decoration: none;
}

nav {
    float: left;
    margin-top: 25px;

}

nav a {
    color: #999999;
    text-decoration: none;
    margin-left: 15px;
    display: inline-block;
    border-left: 1px solid #efefef;
    padding-left: 15px;
    line-height: 18px;
}

nav a:first-child {
    border-left: 0 none;
} 


 <h1>Gallery</h1>
       
        <div class="work">
                <img src="assets/images/blur-communication-computer-3.jpg" class="auth-image" alt="Technology">
                <h3>Technology</h3>
        </div>
        <div class="work">
                <img src="assets/images/beach-beautiful-bridge-3.jpg" class="auth-image" alt="Travel">
                <h3>Travel</h3>
        </div>
        <div class="work">
                <img src="assets/images/boutique-clothes-indoors-3.jpg" class="auth-image" alt="Fashion">
                <h3>Fashion</h3>
        </div>
        <div class="work">
                <img src="assets/images/dumbbells-equipment-gloves-3.jpg" class="auth-image" alt="Fitness">
                <h3>Fitness</h3>
        </div>
        <div class="work">
                <img src="assets/images/air-jordan-design-footwear-3.jpg" class="auth-image" alt="Shoes">
                <h3>Shoes</h3>
        </div>
        <div class="work">
                <img src="assets/images/bread-delicious-egg-3.jpg" class="auth-image" alt="Food">
                <h3>Food</h3>
        </div> 




        <form id="contac-form">
            <ul>
                <li>
                    <label for="name"></label>
                    <input type="text" name="name" id="name"
                    placeholder="John Smith" required="required"> 
                </li>
                <li>
                    <label for="email">Email</label>
                    <input type="text" name="email" id="email"
                    placeholder="example@gmail.com" required="required"> 
                </li>                
                <li>
                    <label for="message">Message</label>
                    <textarea id="message" name="message"
                    required="required"></textarea>
                </li>            
            </ul>
            <input type="submit">
        </form>