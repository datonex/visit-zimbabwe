# Visit Zimbabwe

## Overview

### What is this website for?

This is a website for people to learn about Zimbabwe and show places they can visit.

### What does it do?

This website will show the different locations they can visit ranging from national parks to national history. it also provides travel information, how to reach the country and any important documemnts and medical issues that need to be address before entering the country

### How does it work

This website uses generic **HTML** and **CSS** animations to route viewers through the site. View the website in the browser [**here**](https://datonex.github.io/visit-zimbabwe/) 

### UX

Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.

### Existing Features

- Feature 1 - allows users X to achieve Y, by having them fill out Z
- ...

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

- Eye catching front page
  - Sliding picture box
- Information page.
  - Sidebar to navigate to different parts of the information
- Media page with plenty of pictures and a video
- Links page to other sites with information about Hippopotami
- Quiz page for viewers to test their knowledge
  - Form for viewers to input their answers or check the correct box
  - Submit button so viewers can see how they scored on the quiz

### Features Left to Implement

- Add a page where you can make a booking for a particular destinations. this includes adding a vitual online basket so that users can see what they have already selected (requires **Javascript** knowledge) Fore this reason I decided to removing the booking page from the website becaue it would be too incomplete and not provide a positive user experience.

## Technologies Used

n this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- **HTML** and **CSS** 
  - Base languages used to create website
- [Fontawesome *v.5.15.3*](https://fontawesome.com/)
  - We use **Font Awesome** javascript link to insert icons in the website to make site more visually appealing and easy to navigate.

## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

- Prototype code was written and tested using jasmine
- All code used on the site has been tested to ensure everything is working as expected
- Site viewed and tested in the following browsers:
  - Google Chrome
  - Opera
  - Microsoft Edge
  - Mozilla Firefox

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.

### Contribution

1. Firstly you will need to clone this repository by running the ```git clone <project's Github URL>``` command
2. After you've that you'll need to make sure that you have **npm** installed
3. You can get **npm** by installing Node from [here](https://nodejs.org/en/)
4. After those dependencies have been installed you'll need to make sure that you have **http-server** installed. You can install this by running the following: ```npm install -g http-server # this also may require sudo on Mac/Linux```
5. Once **http-server** is installed run ```http-server -c-1```
6. The project will now run on [localhost](http://127.0.0.1:8080)
7. Make changes to the code and if you think it belongs in here then just submit a pull request

## Credits

### Content

- The information used to create this site was from a number of sources
  - Zimbabwe tourism page on [Zimbabwe tourism](https://www.zimbabwetourism.net/)
  - The Lonely Planet [Lonely Planet](https://www.lonelyplanet.com/zimbabwe)

### Media

- The photos used in this site were obtained from [Pixabay](https://pixabay.com/)
- Flame lily obtained from [Unsplash](https://unsplash.com/)
- The video used on to show overview of Zimbabwe belongs to Dillan Prinsloo on [Youtube](https://www.youtube.com/watch?v=9xbVx9GmbpY)

### Acknowledgements

I received inspiration for this project from following tourists sites

-Official Qatar tourism [Visit Qatar](https://www.visitqatar.qa/en/home)
- A generic parallax website by Jolly Kalam [Parallaxsite](https://jolly-kalam-23776e.netlify.app/parallaxsite/)
