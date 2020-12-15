# Carol's Kitchen

Carol's Kitchen is a site that offers Spanish recipes in English. The website is designed to be easy to navigate. 
 
A live version of the site is available [here](https://carolinacobo.github.io/CarolsKitchen/)

For this project it was required to create a user centric website using HTML5, and CSS supported by other libraries as Bootstrap. 

# Table of contents
1.  [UX](#ux)
    * [User stories](#user-stories)
2. [Structure](#structure)
* [Design process](#design-process)
    * [Page structure](#page-structure)
    * [Home page](#home-page)
    * [Recipes page](#recipes-page)
    * [Contact page](#contact-page)
3. [Styling](#styling)
* [Colours](#colours)
* [Fonts](#fonts)
* [Features](#features)
    * [Existing features](#existing-features)
    * [Future features](#future-features)
4. [Technologies used](#technologies-used)
* [Languages](#languages)
* [Libraries](#libraries)
* [Tools](#tools)
5. [Testing](#testing)
* [User stories](#user-stories)
* [Testing responsiveness](#testing-responsiveness)
* [Browsers](#browsers)
* [HTML and CSS validation](#html-and-css-validation)
* [Tools for testing](#tools-for-testing)
6. [Tests](#tests)
* [Bugs found and fixed](#user-stories)
* [Deployment](#deployment)
7. [Credits](#credits)
* [Content](#content)
* [Media](#media)
* [Acknowledgements](#acknowledgements)
* [I received advice and support from](#user-stories)


## UX
### User stories:
- As a user I want to find Spanish recipes. 
- As a user I want to easily navigate the site. 
- As a user I want to contact the site owner.
- As the site owner I want people to find recipes and navigate them easily.

The wireframes for this project can be find [here](https://github.com/CarolinaCobo/CarolsKitchen/tree/master/assets/wireframes). 

# Structure
## Design process
### Page structure 

- My aim was to make the site simple and easy for the user to navigate it.
- All pages follow the same style (other than the main page) being simple and easy to read. 
- The navbar on top of the page is static and have the links to the main three areas of the site. It also has the logo and a slight different color, that is the same as the footer. It's responsive and the items collapse on smaller devices. 
- The home page is the main area where the recipes are listed and are linked so the user can find on a glance what is looking for. It's responsive depending on the device tha page is viewed. 

### Home page
It features two areas of content and links to the third one on the Navbar. 
- First section is the cards containing the recipes. 
- Second section is a carousel with more recipes (this is a future feature).

### Recipes page
The recipe sites follow the same structure and picture (same as the home page one) with the Ingredients and Steps. 

### Contact page
The contact page has three boxes with name, email, question and button to submit a question. Once the question is submited the user will be redirected to a Thank you page and a Home button. 

# Styling

## Colours
Using [Colorhunt.co](https://colorhunt.co) I chose a palette with complementary colours that could be found in different sites: 
- ![#16697a](https://via.placeholder.com/15/16697a/000000?text=+) `#f03c15` - Cover text and when the user hover on the icons. 
- ![#fafafa](https://via.placeholder.com/15/fafafa/000000?text=+) `#fafafa` - Header, footer, icons and buttons text. 
- ![#8f8f8f](https://via.placeholder.com/15/8f8f8f/000000?text=+) `#8f8f8f` - Buttons when they are not hovered on. 

## Fonts 

Anton is used for the site logo and Favicon. Noto Sans JP is used site wide. Both imported from Google fonts and the Favicon from Favicon.io. Used on the Universal selector to format the entire site. 

## Features
 
### Existing Features
- Feature 1 - Allows users to see all the available recipes.

    * Used HTML and CSS for the Hero-Image and site structure. 
    * Used Bootstrap to add a responsive and collapsable Navbar, cards with recipes, carousel and footer. 

- Feature 2 - Allows users to click and see the ingredients and steps for the recipes. 
    * Used HMTL and CSS for the page structure. 

- Feature 3 - Allows users to send a message with a question. 
    * Used Bootstrap to create the form and CSS to format both the form and the button. 
 
- Feature 4 - Redirects the user to a thank you site after submiting a form.
    * CSS to format the message, button and positioning them. 

- Feature 5 - Footer with links to different social networks. 

### Future features: 
- Recipes linked to the carousel.
- Video explanation in the different steps of the recipes. 
- Ranking most shared recipes. 

## Technologies Used

### Languages 
- HTML - language for the structure of this site. 
- CSS - to style and fix media queries and the max width.

### Libraries
- [Bootstrap (4.5.3)](https://getbootstrap.com/docs/4.5/getting-started/introduction/) - with supporting JS Script and tooltips. Used for the responsive grid system, styling elements and navbar creation.
- [FontAwseome (5.6.3)](https://fontawesome.com/)- used for the footer icons.
- [Google Fonts](https://fonts.google.com) - used for fonts on the site.
- [Hover.css](https://ianlunn.github.io/Hover/) - used for animation effects on social icons and various buttons throughout the site.
- [TailwindCSS](https://tailwindcss.com/docs/box-shadow) - For inspiration on the 
- [CSS Variables](https://developer.mozilla.org/en-US/)
    - This project uses **CSS Variables** to avoid reusing properties. I've seen them on the console and wanted to try them as well to help the site to be responsive. In the root and in different places to give the site a max widht. 

### Tools

[Gitpod](https://www.gitpod.io/) - used as IDE for the project.

[Git](https://git-scm.com/) - used for version control.

[Github](https://github.com/) - used to host repository and to generate the live website.

Balsamiq - used to create the wireframes.

## Testing

### User stories

- As a user I want to find Spanish recipes. 
    * This site offers recipes to the user to cook Spanish recipes.

- As a user I want to easily navigate the site. 
    * The site is easy to use and visual so things can be seen on a glance. 

- As a user I want to contact the site owner.
    * The site has on the Navbar the Contact site that can be accessed from all pages and shows a message when a question is submitted so the user is sure the question has been sent. 
- As the site owner I want people to find recipes and navigate them easily.
    * Information is clear and easy to read for the users. 



### Testing responsiveness
- With Google Developer Tools in Chrome in all screen sizes.

### Browsers

Manually tested: 
- Chrome.
- Safari.

Tested on the following devices:
- Iphone XS.
- Samsung.
- Ipad.

Tested in desktop, phone and tablet sizes.

### HTML and CSS validation

Code has tested and passed: 

[W3C Markup Validation Service - HTML](https://validator.w3.org/)

[W3C Markup Validation Service - CSS](https://jigsaw.w3.org/css-validator/)

Screenshots following this [link](https://github.com/CarolinaCobo/CarolsKitchen/tree/master/assets/tests).

### Tools for testing: 

Chrome Extension - Responsive viewer. Picture of the site in different screen sizes [here](https://github.com/CarolinaCobo/CarolsKitchen/tree/master/assets/tests)

[Am I Responsive](http://ami.responsivedesign.is/) - for testing purposes. 

[Google Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools) - used for testing and debugging.

[w3 html validator](https://validator.w3.org/) - used to test and validate my html code.

[w3 css validator](https://jigsaw.w3.org/) - used to test and validate my css code.

# Tests 
The following manual tests have been performed, link video at the end. 

1. Open all the links available: 
    1. Click Navbar. 
    2. Click recipes link.
    3. Click recipes picture. 
    4. Click social media icons.

2. Carousel. 
3. Contact form:
    1. Go to the "Contact" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.
    5. Click home button and come back to home 


Below a table with a list of the test performed: 

What do you do? | Expected Behaviour | Pass/Fail  |
| ------------- |-------------| -----|
| Click picture to open recipe| Open recipe in a new tab | Pass |
| Click link to open recipe| Open recipe in a new tab | Pass |
| Click Recipes on navbar | Scroll down to Recipe section | Pass |
| Click left carousel arrow| Slide to the left |   Pass |
| Click right carousel arrow| Slide to the right |   Pass |
| Contact the site owner | Request a name, email with the correct format and the question | Pass |
| Submit a question | Redirect to a new site | Pass |
| Open Facebook footer link | Open link in a new page | Pass |
| Open Twiter footer link | Open link in a new page | Pass |
| Open LinkedIn footer link | Open link in a new page | Pass |
| Open Pinterest footer link | Open link in a new page | Pass |
| Open Instagram footer link | Open link in a new page | Pass |
| Open Youtube footer link | Open link in a new page | Pass |



Video testing the site in the following [link](https://www.loom.com/share/d0486bb5644848f4a9adae4a688c12ba)



### Bugs found and fixed
- Hero image was not taking full width. To fix that I added a CSS variable so it's easily used accross the code. 
- Footer icons broken, updated the link to a newer version. 
- Card border one of the sides of the cards was not appearing as I modified the style so I looked for inspiration in other sites and changed it. 
- Links on the footer were not properly added to the code. 
- Made images smaller to make them load faster. 
- While using the Chrome tools I changed the size of the screen so it was not behaving as expected, it's not a proper bug but it took my a while to figure it out. 
- Images not being responsives, I added a media query to change that when it was a mobile size. 

- Not commiting properly at the beginning as I was doing it after a big few changes, started to do it more frequently since then. If you see that at the beginning the commits level is too low that is the reason. 

## Deployment

### GitHub pages

My site is hosted on GitHub pages, deployed directly from the master branch. 
The steps to complete the hosting process: 
1. Log into GitHub.
2. Pick the respository. 
3. Go to settings. 
4. Scroll down to GitHub Pages section.
5. Select as a source "master branch". 
6. The page refreshes automatically and the project is deployed. 
7. The URL for the page will be public automatically.


### Cloning
To run this code locally, you can clone this repository directly into the editor of your choice by following the steps below:

1. Open Terminal.
2. Change the current working directory to the location when you want the cloned directory.
3. Type the following into your Terminal:
git clone https://github.com/CarolinaCobo/CarolsKitchen.git
5. Press Enter to create a local clone.

To cut ties with this GitHub repository, type git remote rm origin into the terminal.
For more information regarding cloning of a repository click [here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).


## Credits

### Content
All the content on this site is my own.

### Media
- The photos used in this site were obtained from [Pixabay](https://pixabay.com/)
- The color palette used in this site was obtained from [Colorhunt.co](https://colorhunt.co)
- Size of the pictures of this site have been reduced using [Tiny Png](https://tinypng.com/)
- The favicon for this site has been made in [Favicon.io](https://favicon.io/)
- The Library Tailwind has been used for inspiration on styles. 


### Acknowledgements

I received inspiration for this project from: 
* [Donal Skehan](https://donalskehan.com/recipes/)
* [MDN Documentation](https://developer.mozilla.org/en-US/)
* [W3Schools](https://www.w3schools.com/)
* [CSS-Tricks](https://css-tricks.com/)
* [StackOverflow](https://stackoverflow.com/)
* [Codú Community](https://www.youtube.com/channel/UCvI5azOD4eDumpshr00EfIw)
* [FreeCodeCamp](https://www.freecodecamp.org/)


### I received advice and support from
My mentor Dick Vlaanderen

Code Institute - Slack Community.