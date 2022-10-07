# portfolio-page

## Description

The purpose of this repository is to prepare not only for our future portfolios that we will use to sell ourselves to potential employers, but to teach us the fundamentals of CSS and applying them firsthand to create a basic portfolio page. 

We will create a more refined one later on, but this is a test to showcase what you have learned in the bootcamp thus far. 

No installation required. 

## User Story

* **AS** AN employer
* **I** WANT to view a potential employee's deployed portfolio of work samples
* **SO** THAT I can review samples of their work and assess whether they're a good candidate for an open position

## Acceptance Criteria

* **GIVEN** I need to sample a potential employee's previous work
* **WHEN** I load their portfolio
* **THEN** I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
* **WHEN** I click one of the links in the navigation
* **THEN** the UI scrolls to the corresponding section
* **WHEN** I click on the link to the section about their work
* **THEN** the UI scrolls to a section with titled images of the developer's applications
* **WHEN** I am presented with the developer's first application
* **THEN** that application's image should be larger in size than the others
* **WHEN** I click on the images of the applications
* **THEN** I am taken to that deployed application
* **WHEN** I resize the page or view the site on various screens and devices
* **THEN** I am presented with a responsive layout that adapts to my viewport

## Project Completion

To complete this projec, there are a lot of steps to reach the end. 

In order of acceptance criteria:
* Using simple HTML tools, we can easily apply the developer's name and links to the various sections below in the <header> of the index.html. For the picture, I found there were a couple of different ways of approaching it, but the easiest was to use an img src element in the "About Me" section, and then use CSS to adjust its properties appropriately. 
* Using the previous assignment as an example, you can use id selectors so that the navigation panel can find the required category. For example, <a href="#work">Work</a> can find the <div id="work"> later in the HTML document. It is important to make sure that the flex parent and children are not tampered with, which is why I insert the div id into the header of the section. 
* This is a challenging category, but it is the one that most utilizes your flexbox knowledge. As far as navigation, please refer to the previous list item. 
* The sizing is a challenge, but it is easy once you remember to use flex-basis. 
* Using the anchor tag <a href>, you can plant a URL into an image. Using :hover, I was able to change the items whenever a user hovers over them. 
*The responsive layout is interesting, in that you can add media screen functions in a multitude of ways. Since this webpage is simple, I want to make sure the width of boxes and images shrinks along with the page, so I includ width=100%. I also change the borders on the headers from the right to the bottom, so when everything is organized into columns, it looks a bit more presentable. 


## Screenshot

Here is the screenshot of the deployed webpage.

![Portfolio Page Screenshot](./Assets/Images/_Users_connorbazil_Desktop_portfolio-page_index.html%20(1).png)

## Link

The deployed application can be accessed here: https://cbazil114.github.io/portfolio-page/

## Credits

* Credits to the learning assistants who helped me along the way!