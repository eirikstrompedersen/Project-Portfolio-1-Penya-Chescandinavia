# Penya Chescandinavia - homepage
(Developer: Eirik Strøm Pedersen)

![Mockup image](/docs/am-i-responsive.jpg)

[Live webpage](https://eirikstrompedersen.github.io/Project-Portfolio-1-Penya-Chescandinavia/contact.html)

## Table of Contents

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements amd Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Color](#colors)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks & Tools](#frameworks-&-tools)
5. [Features](#features)
6. [Testing](#validation)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
8. [Unfixed Bugs](#Bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals

### User Goals
- Find the Scandinavian supporter organization for Valencia CF
- Get information about the supporter club
- Find events
- Link up with social media platforms

### Site Owner Goals
- Provide users with information about the suppoter club 
- Connect users to the social media platforms
- Inform users of our events
- Provide and store the history of Penya Chescandinavia

## User Experience

### Target Audience 
- Inhabitants in Scandinavia interested in Valencia CF
- People who wish to connect with the community

### User Requirements and Expectations
- Clean design with a color theme familiar to people who follows Valencia CF
- Easy to access information
- Links to social media platforms
- Responsive design
- Accessibility

### User Storiess

#### First-Time User
1. As a first time user, I want to get information about Penya Chescandinavia
2. As a first time user, I want to be able to connect with the social media platforms offered
3. As a first time user, I want to get information about upcoming events

#### Returning User
4. As a returning user, I want to learn more about the organization
5. As a returning user, I want to follow team news
6. As a returning user, I want to learn more about the supporter club

#### Site Owner
7. As the site owner, I want users to follow news and upcoming events
8. As the site owner, I want users to learn more about the organization
9. AS the site owner, I want users to be able to contact the organization 

## Design

### Design Choices
The website is designed with easy design, which make information easy to access for the user.

### Color
Colors is picked on the basis on familiarity to the football team and the region flag. The football team plays in white shirts, with black shorts. 
This is to give the user a sense of familiarity with the website.

![Color scheme1](docs/color-inspiration1.jpg)

### Fonts
Roboto is used for the logo as it is an elegant font. Merriweather used for the text content on the page, mainøy for it readability. Merienda One used in h2 to add some dynamic to the site.

### Structure
The page use a common design well know the for most users. With navigation bar at the top of the site and a footer at the bottom. In between the content are designed differently for every site.
The site cosist of 4 pages
- The homepage provide basic information about the supporter club and upcoming events
- The about page is a long read page with the history of the supporter club
- The news page consist of News notices. A quick read to get updated
- The contact page provides a form for the user. The "submit-button" will open the users mail client.

### Wireframes
<details><summary>Index - Desktop</summary>
<img src="docs/wireframes/wireframes-index-desktop.jpg">
</details>
<details><summary>Index - Mobile</summary>
<img src="docs/wireframes/wireframes-index-mobile.jpg">
</details>
<details><summary>About - Desktop</summary>
<img src="docs/wireframes/wireframes-about-desktop.jpg">
</details>
<details><summary>About - Mobile</summary>
<img src="docs/wireframes/wireframes-about-mobile.jpg">
</details>
<details><summary>News - Desktop</summary>
<img src="docs/wireframes/wireframes-news-desktop.jpg">
</details>
<details><summary>News - Mobile</summary>
<img src="docs/wireframes/wireframes-news-mobile.jpg">
</details>
<details><summary>Contact - Desktop</summary>
<img src="docs/wireframes/wireframes-contact-desktop.jpg">
</details>
<details><summary>Contact - Mobile</summary>
<img src="docs/wireframes/wireframes-contact-mobile.jpg">
</details>

## Technologies Used

### Languages
- HTML
- CSS

### Frameworks and Tools
- Git
- GitHub
- GitPod
- Fontawesome
- Balsamiq
- Google Fonts
- Favicon
- VS Code
- W3C Validator
- W3C CSS Validator
- Google Lighthouse
- Chrome DevTools

## Features

### Navigation bar and logo
- features on all pages, and is identical across  the pages. The navigation bar give the user access to navigate through all sites, and it's responsive. The logo is also a link that taks the user back to the landing page.
   
![Logo](/docs/features/logo.jpg)

![Navbar](/docs/features/navbar.jpg)

### Intoduction
- landing page image is the first the user sees when visitin the site. The image represent what Penya Chescandinavia is.

![Intro-Image](/docs/features/intro-image.jpg)

- introduction text feature on landing page. Gives the user basic information about the site and the organization.

![Into](/docs/features/intro.jpg)

### Events
- This section informs the user of upcoming events and gatherings.
- The section gives the user a overview of events in the different nations

![Events](/docs/features/events-section.jpg)


### Footer
- Gives copyright information
- Provides the user with links to the different social media platform the organization uses
- Anchored to the bottom of the page

![Footer](/docs/features/footer.jpg)

### News
- Section with News Notices, to provide a quick update for the user
- The section is devided in blocks for better overview

![News](/docs/features/news-frame.jpg)

### About
- The section gives the user information about the organization and it's history
- This page also works as a safe space to save the history for the organization

![About](/docs/features/about.jpg)

### Form
- The form page gives the user access to contact the organization via mail
- The submit buttom opens the mail client on the user device

![form](/docs/features/form.jpg)

## Testing

### HTML Validation
- The HTML came through the validation process with no issues with the html-structure
- The validation was done with [Jigsaw HTML Validator](https://validator.w3.org/)

![html Validation](/docs/validation/html-validation.jpg)

### CSS Validation
- The CSS came through the validation process with no issues with the html-structure
- The validation was done with [Jigsaw HTML Validator](https://jigsaw.w3.org/css-validator/#validate_by_uri+with_options)

![CSS Validation](/docs/validation/css-validation.jpg)

### Accessibility
- the site came through the accessibility validation with 1 alert, refering to copyright text in the footer being small. Minor issue as it's not crucial information for the user of the page
- The validation was done through [WAVE WebAim](https://wave.webaim.org/)

![Accessibility Validation](/docs/validation/accessibility-validation.jpg)

### Performance Validation
- The site generated good score on both desktop performance, and mobile performance
- The validation was done with [Chrome DevTools Lighthouse](https://developers.google.com/web/tools/lighthouse)

![Performance Validation Desktop](/docs/validation/performance-validation-desktop.jpg)

![Performance Validation Mobile](/docs/validation/performance-validation-mobile.jpg)


### Unfixed Bugs
- There is a bug I cannot fix, as my mentor asked me to change name on my project repository because it was 'too long'. After name was changed all the images in assets folder would not link up with the deployed site.

- Actions done to solve issue, without success:
    - rename repository back to orginal name
    - rename folder with images from "img" to "images"
    - delete image folder and images from repository and upload it again

- Eventually I came up with a solution which work, but it's not 100% ideal. But this issue is beyound my current knowledge, and I don't want to destroy my entier project right before the project deadline.

I manage to discover that the images address was broken on the deployed site. The folder seems not to be connected to the holder anymore.

In my html you won't find links like "/assets/images/image_name-jpg", since the folder is disconnected from the project repository for some reason. 
What I did to solve the problem was to hard code the links directly from github to the project

![Error Example 1](/docs/bugs/error-example-1.jpg)

![Error Example 2](/docs/bugs/error-example-1.jpg)

## Deployment
- I deployed the project via GitHub
- GitHub -> Project repository -> Settings -> pages
- Be sure that the "main" branch is the one choosen in the dropdown menu.
- Click save
- Go to action tab to follow the deployment progess
- Test site after deployment

## Credits

### Content

- The text content I got from the existing [Penya Chescandinavia site](http://www.cerveras.es/chescandinavia/about-2/)
- The rest of the text content I wrote myself
- The social media icons and the icons used in the news page was imported from [FontAwesome](https://fontawesome.com)
- The template for the Readme.md file was provided by my mentor Mo Shami, but was made by GitHub user and former CI-student [4n4aru](https://github.com/4n4ru/CI_MS1_BodelschwingherHof)

### Media
Some images are my own, and I wont credit them in the list below.

- The [Youtube Video](https://www.youtube.com/watch?v=CP4tQeoz_PU) used on About.html is property of Penya Chescandinavia
- The Logo is a property of Penya Chescandinavia, and they allowed me to use it in this procjet (I'm a board member in the organization)
- "bg-form.jpg": Photo by [Guzmán Barquín](https://unsplash.com/@guzmanbarquin) on [Unsplash](https://unsplash.com/)

### Code
- The 'send email'-functionality was made following [W3schools Guide](https://www.w3schools.com/html/tryit.asp?filename=tryhtml_form_mail)

## Acknowledgements
- My mentor Mo Shami for his support
- Code Insititute and their slack community
- My girlfriend for her patience
- Penya Chescandinavia and the wonderfull community around it