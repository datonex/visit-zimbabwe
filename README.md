# Visit Zimbabwe

## Overview

### What is this website for?

This is a website for people to learn about Zimbabwe and show places they can visit.

### What does it do?

This website will show the different locations they can visit ranging from national parks to national history. it also provides travel information, how to reach the country and any important documemnts and medical issues that need to be addressed before entering the country

### How does it work

This website uses generic **HTML** and **CSS** animations to route viewers through the site. View the website in the browser [**here**](https://datonex.github.io/visit-zimbabwe/)

## UX

### User Stories

- #### Things are slowly getting back to normal due to the pandemic, I want to plan my next holiday

  1. I want to easily navigate the site relatively easily

  2. I want to be able to see a balance of text, images and some video to get a glimpse of where I will be visiting

  3. I want to be able to access links that direct me to important websites easily

  4. I want some clicking interaction with the page so that I don't get bored

- #### As a previous who is using the website for reference

  1. I want to have access to the website on any device and on the go

  2. I want the navigation bar easily accessible so that I can get where I want quickly

### Design

#### Colour Scheme

Initialy the colour scheme of the website was supposed to represent the national colours of the zimbabwean flag. However the colours were too bright and did not blend well together.

Instead, I used the idea that Zimbabwe has a lot of wild life, the colour was meant to mimic the savannah during a sunset. The colour is subtle without grabbing to much attention while giving more focus to the images. The main colour was picked using the colour picker on the header websight to obtain the colour light salmon (#fdcba6) The buttons were matched using the compound approach from [adobe color wheel](https://color.adobe.com/create/color-wheel). to obtain the colour (#71C9A2)

<img src="./assets/images/readme-images/colour-scheme.png" height="100px"/>

#### Typography

- Font used for headings was Lobster with a back-up font of sans-serif. The font is eye catching and decorated white still easy to read.

<img src="./assets/images/readme-images/lobster-font.png" height="50px" />

- Font used for main text was Open Sans with a back-up font of sans-serif. The font is easy to read and well spaced out.

<img src="./assets/images/readme-images/open-sans-font.png" height="50px"/>

#### Imagery

- Images on the website were the top if not second priority on the website. They needed to supplement the text and offer visiual aid to illustrate favourable tourist locations.

#### Mockups

Mockups were made using Balsamiq Wireframes

[Mockup](./assets/planning/mockup-1.pdf)

### Existing Features

#### Common Features Across All Pages

- [x] **Header** - allows user to easily navigate across all pages

  - Header is fixed to top of page for easy access (desktop and large tablets)
  - Zimbabwe logo and text are positioned on the left and are links that take you to the homepage
  - Navigation is place on the right on the logo for easy access (under logo for mobile)
  - Navigation links change colour when hovered over. This lets the visitor know that it is clickable.
  - Navagation link is underlined to let user know what page they are on
  - Entire header disappears for mobile devices
  - Colors have been chosen with optimum contrast in mind to be pleasant to the eye.
- [x] **Links** that are hovered over
  - All links that are surrounding text have been underlined and change color when hovered over. This helps the user to identify external links. (except logo)
- [x] **Navigation banner**
  - Navigation banner is the same across all pages to give uniformity and familiarity
  - bacground image on home is scrorable to give a more fun user experience
- [x] **Accessibility**
  - All images have aria labels in case they don't load and for the visually impared
- [x] **Buttons**
  - All buttons have the same styling and they invert colours when hovered (except for scroll to top button)
- [x] **Responsiveness**
  - All pages work well with many screen sizes
- [x] **Footer**
  - Footer sticks to the bottom of the page, regardless of the amount of content. This aids the overall user experience.
  - All content have near uniform layout to give a nice and enganging flow of text and images
  - Social links have been grouped together
  - 'Contact us' is form for feedback and any question the user might have 

### Specific to Pages

- [x] **Home Page**

  - Image grid to easily see a handfull of places the user can visit. When the mouse hover's you get addition information about the location

### Features Left to Implement

- Add a page where you can make a booking for a particular destinations. this includes adding a vitual online basket so that users can see what they have already selected (requires **Javascript** knowledge) For this reason I decided to remove the booking page from the website becaue it would be too incomplete and not provide a positive user experience.

- hide the scroll to top button at the beginning of page

## Technologies Used

- [**HTML**](https://en.wikipedia.org/wiki/HTML5) and [**CSS**](https://en.wikipedia.org/wiki/CSS)
  - Base languages used to create website

- [Fontawesome *v.5.15.3*](https://fontawesome.com/)
  - We use **Font Awesome** javascript link to insert icons in the website to make site more visually appealing and easy to navigate.

- [Favicon](https://favicon.io/)
  - Favicon.io was used to generate favicon and provided syntax and

- [Google Fonts](https://fonts.google.com/) 
  - Google Fonts was used to import 'Lobster' and 'Open Sans' fonts in the style.css stylesheet.

- [Visual Studio Code](https://code.visualstudio.com/) 
  - Source-code editor optimised fro debugging, syntax hylighting and extenstion support

- [Git](https://git-scm.com/)
  - Git was used to allow for tracking of any changes in the code and for the version control.

- [Github](https://github.com/)
  - GitHub is used to host the project files and publish the live website by using Git Pages.

- [TinyPNG](https://tinypng.com/)
  - Used to reduce resolution on images

## Testing

- ### Navigation bar

  - When the logo or 'Zimbabwe' text is clicked, the user is redirected to the home page
  - All links are working and have been tested.
  - navigation bar is aligned vertically and under the logo for screens smaller than 660px
  - The navigation bar stays at the top of the page for screens larger than 660px only

- ### Footer

  - Footer always sticks to the bottom of the page and was tested by removing all content from the page.
  - social media link open in a new tab when clicked
  - When user accesses the 'Contact us' page
    - Name is required to continue submition
    - Email field is required and has to be in the correct format.
    - Text field has to contain at least two characters.
    - terms and conditions have to be agreeed and clicked on
    - When 'Submit' is clicked (given all fields have been filled out) the form will be sent

- ### The Image grid

  - Any image that is hovered on (desktop only) the text is uniformly aligned and shows correct information for other deviced the grid is hidden and a continuous prose is displayed instead.

- ### External links

  - All social links in the footer bring the user to the relevant social pages
  - Links to external websites, the booking and visa button bring the user to the right website in a new tab.


- ### Internal Links

  - Logo and text all lead to hompe page
  - Navigation links lead to relavant pages
  - Contact us link leads to the correct page for all web pages

### CSS3 validator

Pass

  <a href="http://jigsaw.w3.org/css-validator/check/referer"><img style="border: 0; width: 88px; height: 31px;" src="http://jigsaw.w3.org/css-validator/images/vcss-blue" alt="Valid CSS!" /></a>

### HTML5 Validator

**Home Page** - Pass
**About Page** - Pass
**Contact Us** - Pass
**Travel Information Page** - 2 Errors

1. Error: The element a must not appear as a descendant of the button element.

    From line 345, column 63; to line 345, column 118

    `="button"><a href="https://www.evisa.gov.zw/home" target="_blank">Apply`

2. Error: The element a must not appear as a descendant of the button element.

    From line 376, column 38; to line 376, column 89

    `="button"><a href="https://www.expedia.co.uk" target="_blank">Book f`

### Compatibility Testing

- Browser Compatibility

    | Screen size\Browser | Safari           | Opera            | Microsoft Edge   | Chrome           | Firefox          | Internet Explorer |
    | --------------------|:----------------:|:----------------:|:----------------:|:----------------:|:----------------:|:-----------------:|
    | Mobile              |:heavy_check_mark:|Not Tested        |Not Tested.       |:heavy_check_mark:|:heavy_check_mark:| Not Tested        |
    | Desktop             |:heavy_check_mark:|Not Tested.       |Not Tested.       |:heavy_check_mark:|:heavy_check_mark:| Not Tested        |
    | Tablet              |:heavy_check_mark:|Not Tested.       |Not Tested.       |:heavy_check_mark:|:heavy_check_mark:| Not Tested        |

- OS Compatibility was tested on iOS 14.5.1, MacOS Catalina, iPadOS 14.5 It is yet to be tested on Unix, Linux, Windows or Solaris Operating Systems.
- The devices used in this testing include Macbook Pro, iPad Pro, iPhone 12 Pro Max, Iphone 7 Plus.

- The website was exhaustively tested for responsiveness on [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools). Different viewport sizes were simulated ranging from as small as iPhone 5 (320px) to large desktop sizes (1200px and above).

## Deployment

This website was published using [GitHub Pages](https://pages.github.com/). 

1. Go to the GitHub.com and log in.
2. On the left-hand side, you'll see all your repositories, select the appropriate one.
3. Under the name of your chosen Repository you will see a ribbon of selections, click on 'Settings' located on the right hand side.
4. Scroll down till you see 'Pages' heading.
5. Under the 'Source' click on the dropdown and select 'master branch'
6. The page will reload and you'll see the link of your published page displayed under 'GitHub' pages.
7. It takes a few minutes for the site to be published, wait until the background of your link changes to a green color before trying to open it.

### Contribution

1. Firstly you will need to clone this repository by running the ```git clone <https://github.com/datonex/visit-zimbabwe/>``` command
2. If using VS Code type make sure you have th Git extension installed then type about code into your terminal
3. Download the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension, one installed find the go live button at the bottom right of your vscode window
4. The project will now run on [localhost](http://127.0.0.1:5500/)
5. If using Gitpod use the command `python3 -m http.server` 
6. Make changes to the code and if you think it belongs in here then just submit a pull request

## Credits

### Content

The information used to create this site were from a number of sources

- Travel information page
  - [Zimbabwe tourism](https://www.zimbabwetourism.net/)
  - [Lonely Planet](https://www.lonelyplanet.com/zimbabwe)

- About Zimbabwe section copied from [Wikipedia](https://en.wikipedia.org/wiki/Zimbabwe)
  - [Chapungu Sculpture Park](https://en.wikipedia.org/wiki/Chapungu_Sculpture_Park)
  - [Mt Nyangani](https://en.wikipedia.org/wiki/Mount_Nyangani)
  - [Lake Chivero National Park](https://en.wikipedia.org/wiki/Lake_Chivero_Recreational_Park)
  - [Victoria Falls](https://en.wikipedia.org/wiki/Victoria_Falls)
  - [National Gallery of Zimbabwe](https://en.wikipedia.org/wiki/National_Gallery_of_Zimbabwe)
  - [Hwange National Park](https://en.wikipedia.org/wiki/Hwange_National_Park)
  - [Chiremba Balancing Rocks](https://zimfieldguide.com/harare/chiremba-epworth-balancing-rocks)

  - [10 Facts on Zimbabwe](https://en.uitm.edu.eu/news/10-facts-about-zimbabwe/)
  - [Elephant Hunting](https://qz.com/africa/2005322/zimbabwe-looks-to-elephant-hunting-for-revenue-lost-during-covid/#:~:text=the%20coronavirus%20pandemic.-,With%20an%20estimated%20100%2C000%20elephants%2C%20Zimbabwe%20has%20the%20second%20biggest,Wildlife%20Management%20Authority%20(Zimparks))
  - [Mana Pools](https://en.wikipedia.org/wiki/Mana_Pools_National_Park)
  - [Tobacco](https://en.wikipedia.org/wiki/Tobacco_in_Zimbabwe)
  - [Lake Kariba](https://en.wikipedia.org/wiki/Lake_Kariba)


- Climate information copied from
  - [Britanica](https://www.britannica.com/place/Zimbabwe/Climate)
  - [Wikipedia](https://en.wikipedia.org/wiki/Zimbabwe)

### Media

- The photos used in this site were obtained from
  - [Pixabay](https://pixabay.com/)
  - [Unsplash](https://unsplash.com/)
  - "What to pack section images" from [Pexels](https://pexels.com)
  - Mt Nyangani summit taken by [Seabifar](https://commons.wikimedia.org/w/index.php?curid=76195310) Own work, under CC BY-SA 4.0 [license](https://creativecommons.org/licenses/by-sa/4.0/)
  - Wild seed pod sculpture by Arthur Fata photographed by [Zaian](https://commons.wikimedia.org/w/index.php?curid=3618743) under CC BY-SA 3.0 [license](https://creativecommons.org/licenses/by-sa/3.0/)
  - National Gallery of Zimbabwe taken by [Awinda under](https://commons.wikimedia.org/w/index.php?curid=22137862) CC BY-SA 3.0 [license](https://creativecommons.org/licenses/by-sa/3.0/)

- The video used on to show overview of Zimbabwe belongs to Dillan Prinsloo on [Youtube](https://www.youtube.com/watch?v=9xbVx9GmbpY)

### Acknowledgements

I received inspiration for this project from following tourists sites

- Official Qatar tourism [Visit Qatar](https://www.visitqatar.qa/en/home)

- A generic parallax website by Jolly Kalam [Parallaxsite](https://jolly-kalam-23776e.netlify.app/parallaxsite/)

