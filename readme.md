# WhatsMyPC

(Developer: Robin Bosch)

![Mockup image](docs/)

[Live webpage](https://alphaclass6143.github.io/WhatsMyPC/)

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colors](#colors)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks](#frameworks)
    3. [Tools](#tools)
    4. [Pages](#pages)
5. [Features](#features)
6. [Validation and Testing](#validation-and-testing)
    1. [HTML Validation](#html-validation)
    2. [CSS Validation](#css-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#device-testing)
    6. [Browser compatibility](#browser-compatibility)
    7. [Testing user stories](#testing-user-stories)
7. [Bugs](#bugs)
8. [Deployment](#deployment)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)
11. [License](#license)

## Project Goals

### User Goals

- Get to learn what components are in a PC.
- Get to learn what a component does in a PC.
- See PC components location
- Have a reference to use again
- Have a PC parts overview

### Site Owner Goals

- Educate people about PC components
- Share knowledge of PC components
- Promote social media
- Use it as a portfolio project

## User Experience

### Target Audience

- People who have little knowledge of PC components
- People who need a reference page for PC components to look back to
- People who want to know what's in their PC.
- Teachers who would like to introduce students to PC components

### User Requirements and Expectations

- Simple navigation between PC components
- Introduction on how to start learning
- Links and videos need to work as expected
- Easy and short explanations on PC components
- Clear defined structure on how to read the page
- Readability and Accessibility on every device

### User Stories

## Design

### Design Choices

This website design was kept simple to not distract from all the information. The width of the website was limited to make it more readable and pictures have been added to aid the text and not make it boring.

### Colors

The color palette was used from a website. [Link to color palette](<https://colorhunt.co/palette/f2f7ff0b409c10316bfdbe34>). Orange and blue are on the opposite of their color spectrum, which makes them good for color blind people. They also harmonise well together. A black text color has been added to compliment the white text color, mainly for the text on orange.

### Fonts

The Ubuntu font from Google Fonts was chosen because it is visually a good looking and clear font, that is easily readable. It was also chosen because of the fitting name for the project (Ubuntu is also an Operating System). The second font is sans-serif if the font is not loading.  
[Link to Ubuntu font](<https://fonts.google.com/specimen/Ubuntu>)

### Structure

The page is structured in an easy way with a header, the informational content in the middle and a footer at the bottom.  
The header has a burger button which expands the navigation menu.  
The footer has the social media buttons as well as the link to the feedback page.  
A single component page is meant to cover the questions: “What is it and what does it do?” and “Where is it?”. Sometimes there is additional information or videos.  

The pages of the website are:  

- The homepage with an introduction and component overview
- The feedback page with a form
- The single pages that cover the components:
  - Processor page
  - Motherboard page
  - Memory page
  - Power Supply page
  - Graphics card page
  - Storage page
- A 404 page that redirects back to the start page if anything goes wrong

### Wireframes

<details>
 <summary>Home</summary>
 <img src="docs/wireframes/home.png">
</details>

<details>  
  <summary>Open menu state</summary>
  <img src="docs/wireframes/open-menu-state.png">
</details>

<details>  
  <summary>Processor page</summary>
  <img src="docs/wireframes/processor.png">
</details>

<details>  
  <summary>Motherboard page</summary>
  <img src="docs/wireframes/motherboard.png">
</details>

<details>  
  <summary>Memory page</summary>
  <img src="docs/wireframes/memory.png">
</details>

<details>  
  <summary>Storage page</summary>
  <img src="docs/wireframes/storage.png">
</details>

<details>  
  <summary>Power Supply page</summary>
  <img src="docs/wireframes/power-supply.png">
</details>

<details>  
  <summary>Graphics Card page</summary>
  <img src="docs/wireframes/graphics-card.png">
</details>

<details>  
  <summary>Feedback page</summary>
  <img src="docs/wireframes/feedback.png">
</details>

<details>  
  <summary>404 page</summary>
  <img src="docs/wireframes/404.png">
</details>

## Technologies Used  

### Languages

- HTML  
- CSS

### Frameworks

- Font Awesome
- Google Fonts

### Tools

- Git
- GitHub
- Visual Studio Code
- Balsamiq
- PC Building Simulator 2
- Adobe Photoshop

### Pages

- [Colorhunt](<https://colorhunt.co/>)
- [CSS Generators](<https://html-css-js.com/css/generator>) (to generate effects like drop shadows)

## Features

## Validation and Testing

### HTML Validation

All HTML validation tests have been passed.  

<details>
 <summary>Home</summary>
 <img src="docs/validation/html/home.png">
</details>

<details>
 <summary>Processor page</summary>
 <img src="docs/validation/html/processor.png">
</details>

<details>
 <summary>Motherboard page</summary>
 <img src="docs/validation/html/motherboard.png">
</details>

<details>
 <summary>Memory page</summary>
 <img src="docs/validation/html/memory.png">
</details>

<details>
 <summary>Storage page</summary>
 <img src="docs/validation/html/storage.png">
</details>

<details>
 <summary>Power Supply page</summary>
 <img src="docs/validation/html/power-supply.png">
</details>

<details>
 <summary>Graphics Card page</summary>
 <img src="docs/validation/html/graphics-card.png">
</details>

<details>
 <summary>Feedback page</summary>
 <img src="docs/validation/html/feedback.png">
</details>

<details>
 <summary>404 page</summary>
 <img src="docs/validation/html/404.png">
</details>

### CSS Validation

The full website gets errors in the CSS validation test from the font awesome framework.  
Validating the single files passes the tests.  
Variables can't be validated, they show up as warnings.  

<details>
 <summary>Whole website CSS</summary>
 <img src="docs/validation/css/website.png">
</details>

<details>
 <summary>Reset CSS</summary>
 <img src="docs/validation/css/reset.png">
</details>

<details>
 <summary>Styles CSS</summary>
 <img src="docs/validation/css/styles.png">
</details>

<details>
 <summary>Header CSS</summary>
 <img src="docs/validation/css/header.png">
</details>

<details>
 <summary>Footer CSS</summary>
 <img src="docs/validation/css/footer.png">
</details>

### Accessibility

All Wave accessibility tests pass.  
9 Alerts per page are from the navbar, which uses p elements.  

<details>
 <summary>Home</summary>
 <img src="docs/validation/wave/home.png">
</details>

<details>
 <summary>Processor page</summary>
 <img src="docs/validation/wave/processor.png">
</details>

<details>
 <summary>Motherboard page</summary>
 <img src="docs/validation/wave/motherboard.png">
</details>

<details>
 <summary>Memory page</summary>
 <img src="docs/validation/wave/memory.png">
</details>

<details>
 <summary>Storage page</summary>
 <img src="docs/validation/wave/storage.png">
</details>

<details>
 <summary>Power Supply page</summary>
 <img src="docs/validation/wave/power-supply.png">
</details>

<details>
 <summary>Graphics Card page</summary>
 <img src="docs/validation/wave/graphics-card.png">
</details>

<details>
 <summary>Feedback page</summary>
 <img src="docs/validation/wave/feedback.png">
</details>

<details>
 <summary>404 page</summary>
 <img src="docs/validation/wave/404.png">
</details>

### Performance

The lighthouse tests were good. The performance section was a little weak on pages with youtube videos embedded.  
Some performance issues were due to the images not being served in next gen formats.  
Below are all reports to every page.

<details>
 <summary>Home page</summary>
 <img src="docs/validation/lighthouse/summary/home.png">
 <br>
 <a href="docs/validation/lighthouse/report/home.pdf">Read full report to Home page (PDF)</a>
</details>

<details>
 <summary>Processor page</summary>
 <img src="docs/validation/lighthouse/summary/processor.png">
 <br>
 <a href="docs/validation/lighthouse/report/processor.pdf">Read full report to Processor page (PDF)</a>
</details>

<details>
 <summary>Motherboard page</summary>
 <img src="docs/validation/lighthouse/summary/motherboard.png">
 <br>
 <a href="docs/validation/lighthouse/report/motherboard.pdf">Read full report to Motherboard page (PDF)</a>
</details>

<details>
 <summary>Memory page</summary>
 <img src="docs/validation/lighthouse/summary/memory.png">
 <br>
 <a href="docs/validation/lighthouse/report/memory.pdf">Read full report to Memory page (PDF)</a>
</details>

<details>
 <summary>Storage page</summary>
 <img src="docs/validation/lighthouse/summary/storage.png">
 <br>
 <a href="docs/validation/lighthouse/report/storage.pdf">Read full report to Storage page (PDF)</a>
</details>

<details>
 <summary>Power Supply page</summary>
 <img src="docs/validation/lighthouse/summary/power-supply.png">
 <br>
 <a href="docs/validation/lighthouse/report/power-supply.pdf">Read full report to Power Supply page (PDF)</a>
</details>

<details>
 <summary>Graphics Card page</summary>
 <img src="docs/validation/lighthouse/summary/graphics-card.png">
 <br>
 <a href="docs/validation/lighthouse/report/graphics-card.pdf">Read full report to Graphics Card page (PDF)</a>
</details>

<details>
 <summary>Feedback page</summary>
 <img src="docs/validation/lighthouse/summary/feedback.png">
 <br>
 <a href="docs/validation/lighthouse/report/feedback.pdf">Read full report to Feedback page (PDF)</a>
</details>

<details>
 <summary>404 page</summary>
 <img src="docs/validation/lighthouse/summary/404.png">
 <br>
 <a href="docs/validation/lighthouse/report/404.pdf">Read full report to 404 page (PDF)</a>
</details>

### Device testing

The website was tested on the following devices:

- Windows 11 PC (Screen resolution: 2560x1440)
- Xiaomi MI 9 with Android 11 (Screen resolution: 1080x2280)

Other screen resolutions were tested in the browser with dev tools from 2560x1440 down to 320x568.

### Browser compatibility

The following browser were tested:

- Microsoft Edge (Chromium based version)
- Google Chrome
- Mozilla Firefox

Webkit based browser (Safari) could not be tested. Chromium based and Quantum based browser should be working.

### Testing user stories

## Bugs

|Status|Bug|Fix|
|---|---|---|
|Fixed|Menu burger button is inconsistently disappearing on smaller screen sizes. Update: The button is only disappearing on one page: motherboard|Fixing a table for mobile layout brought the button back. Table extended the layout and took the button further out of the screen.|

## Deployment  

The website was deployed using GitHub Pages by following these steps:  

1. In the GitHub repository navigate to the "Settings" tab
2. On the left hand menu select "Pages"
3. For the source select Branch: master
4. After the webpage refreshes automatically you will see a box at the top saying: "Your site is live at <https://alphaclass6143.github.io/WhatsMyPC/>"

You can fork the repository by following these steps:

1. Go to the repository on GitHub  
2. Click on the "Fork" button in the upper right hand corner

You can clone the repository by following these steps:

1. Go to the repository on GitHub
2. Locate the "Code" button above the list of files and click it  
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the "copy" button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone <https://github.com/YOUR-USERNAME/YOUR-REPOSITORY>)  
7. Press Enter to create your local clone.

## Credits

## Acknowledgements

## License
