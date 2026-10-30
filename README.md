# Project Title: Terra Coffee Website #
# Welcome #
[Terra Coffee](https://a-kiera.github.io/terra-coffee/) is a website for a fictional local cafe business that needs to showcase their unique selling points, menus and products. Created to submit as a second practical project for Learning People UK.

# Description #
Terra Coffee is an environmentally-friendly local cafe business that provides an array of drinks and snacks and encourages its customers to enjoy a beverage that is good for both the soul and the Earth.
Visitors to the site can peruse all the useful information they need to know about the business on the landing page and decide whether they would like to frequent the cafe or not.

# Features #
It exists on two pages (the main page as well as a product page with prices and "add to cart" buttons). 

*Here is the navbar and landing img on the main page

![welcome-terra](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/welcome-terra.png)

*There were problems with the appearance of both when Chrome Devtools were used to check responsiveness to different screen sizes.

![navbar-bad-big](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/navbar-bad-big.png)
![landing-bad-big](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/landing-bad-big.png)

*However these errors were resolved by adding media queries to css that adjusted font size and width.

![pixel-10-good](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/pixel-10-good.png)

*This method also helped to create a fully responsive products section

![shop-full](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/shop-full.png)
![shop-responsive-good](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/shop-responsive-good.png)

*On smaller screen sizes I noticed a break in the Menu title of the main page

![gap-menu](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/gap-menu.png)

*And found that this was resolved by decreasing the font size, however upon reflection I should have organised this div differently to keep a consistent design with the rest of the page.

![gap-menu-good]()

*With this project there are certainly improvements that can be made, unfortunately for lack of time they will have to be reserved for a later date. For example, even though the navbar was made responsive the text size isn't very clear to read.

![samsung-55-text-small](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/samsung-55-text-small.png)

**Note*: this is one of the smallest possible screen sizes 

*Similarly, I would like to go back and improve on the uniformity of the product card gallery on the main page, as according to different screen sizes the boxes change size

![wonky-product-index-row](https://github.com/a-kiera/terra-coffee/blob/main/assets/documentation/wonky-product-index-row.png)

# Future Improvements #
- [ ] More interactivity: "scroll to top" button and "add to cart" functionality
- [ ] Expand to multiple pages
- [ ] Perfect media queries - e.g. adjust small link text on navbar when viewed on smaller screens, fix product gallery cards to not vary in size
- [ ] Experiment with design - use this as a base to explore other interesting web design features, e.g. parallax scrolling and animations

# Technologies #
* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) was used to build the structure of the site.
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) was used to add styles and adjust layout.
* [CSS Flexbox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox) was used to arrange elements symmetrically in columns.
* [VSCode](https://code.visualstudio.com/) was used as the main tool to write and edit code.
* [Git](https://git-scm.com/) was used for the version control of the website.
* [GitHub](https://github.com/) was used to host the code of the website.

# Deployment #
## Deployment to GitHub Pages ##
The site was deployed to GitHub pages. The steps to deploy are as follows:

* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Main Branch, then click "Save".
* The page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found [here](https://a-kiera.github.io/terra-coffee/)

# Contact #
Let me know if you have any feedback or suggestions!
Thank you for visiting Terra Coffee!

# Credits # 
External tutorials/credits used for project:
W3Schools Image Gallery - [https://www.w3schools.com/howto/howto_css_image_gallery.asp]

W3Schools Product Card - [https://www.w3schools.com/howto/howto_css_product_card.asp]

# License #
MIT License

Copyright (c) [2026] [Amy Kiera Macleod]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.