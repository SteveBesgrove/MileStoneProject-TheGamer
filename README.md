# **The Gamer**

The fictitious website of a popular Twitch streamer and Youtuber. The site will contain
links to Twitch, Youtube and Patreon. As well as showcase some of his favourite games using images and video clips, with the option to sign up to a newsletter.

[Link to THEGAMER](https://stevebesgrove.github.io/MileStoneProject-TheGamer/)

![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/THEGAMER-HomeCROP.jpg?raw=true)

# User Experience (UX)

## Goals

As a New Visitor:

  - I would like to understand the purpose of the site from the start of the landing page.
  - I would like to be able to easily navigate around the site and quickly find the content I'm looking for.
  - I would like to find social media links to other content created by the author.

As a Returning Visitor:

  - I would like to navigate to required information with ease.
  - I would like to navigate to relevant links to external sites with ease.

## Design (UXD)

### **Strategy**

The strategy plane looks at what and why we want to build something by asking the following questions.

Is the content culturally appropriate?  
  - *Yes. Content is targeted to fans of the fictional gamer.*

Is the content relevant?  
  - *Yes. Content is game based and about the fictional gamer.*

Can we track and catalogue the content in an intuitive way?  
  - *Yes. The site contains links with easy to understand text and images.*

Is the technology appropriate?  
  - *Yes. The website contains game content that you would expect from a gaming website.*

### **Scope**

The Scope plane defines the wants and needs of the user by asking the following questions.

What does the user want to accomplish?  
  - *Watch/learn about their favourite fictional gamer*

What does the user need to do in order to achieve their objective?  
  - *Navigate around the website, click on links and imagery.*

What constraints does the site have to conform within?  
  - *To be built with HTML and CSS.*

What dynamic constraints do we have to meet?  
  - *Make sure it’s game appropriate content.*

### **Structure and Skeleton**

A rough wireframe blueprint of the website was created showing an interpretation of all three platforms and showcasing its responsive design.

The wireframes were created using Balsamiq. [View wireframes here.](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/THEGAMER%20wireframes.png?raw=true)

### **Surface (the design)**

I wanted to make a fun and visually attractive website allowing usability for all.

**Colour Palette**  
I decided you use darker background colours with white-out type for the easiest viewability.

**Typography**  
All fonts have been imported from [Google Fonts.](https://fonts.google.com/).  
I decided to use Open Sans for all of my copy, as it's an easy to read font with plenty of weights.

**Imagery**  
The images and video clips have been sourced from the [Steam website](https://store.steampowered.com/) and the relevant games.  
The gaming man image was creating using [Midjourney](https://www.midjourney.com/home/?callbackUrl=%2Fapp%2F).

**Iconography**  
Icons have been sourced from [fontawesome](https://fontawesome.com/).

# Features

- ## Navigation Bar
    The navigation bar is fixed to the top of the page at 63.5px in height, containing a home bookmark, a game drop down menu and a newsletter signup bookmark. Its responsiveness can be seen as it changes between media sizes eventually becoming a burger menu.
    <br><br>
    Media devices 768px and above.
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/Header.jpg?raw=true)

    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/GameDropDown.jpg?raw=true)
    <br><br>
    Media devices 576px to 767.98px. **The signup section has been shrunk to save space.**  
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/HeaderSM.jpg?raw=true)
    <br><br>
    Media devices up to 575.98px. **The burger menu has been applied.**  
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/HeaderXSM.jpg?raw=true)  
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/HeaderXSMDropdown.jpg?raw=true)

- ## Home
    The home section contains an image of the fictitious gamer and a small description about him with this Twitch, Youtube and Patreon links.
    <br><br>
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/HomePage.jpg?raw=true)

- ## The Games
    Each game section contains a logo which is linked to Youtube (would be the corresponding playlist if it existed). A small description, a teaser video clip (Autoplay is on, but it's muted) and image carousel.
    <br><br>
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/CyberpunkPage.jpg?raw=true)
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/RedDeadPage.jpg?raw=true)
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/SOD2Page.jpg?raw=true)
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/TW3Page.jpg?raw=true)

- ## Sign up form
    Is a basic form using required fields that would link to a newsletter subscription (currently a thank you page).
    <br><br>
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/Form.jpg?raw=true)

- ## Footer
    The footer is fixed at the bottom of the screen, always allowing access to its containing links (Twitter, Twitch, Youtube and Patreon).
    <br><br>
    ![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/Footer.jpg?raw=true)

# Future Features
- Popup image carousel
    - I would like to make the current image carousel into a pop-up (knowledge of JavaScript would be needed for this).

- Popup modal for the newsletter signup
    - I would like to make the “thank you for subscribing” pop-up in a linked form required modal, rather than opening in a new page (knowledge of JavaScript would be needed for this).

# Testing

## General Testing
- The website had been tested on several browsers and my Samsung mobile phone. All internal bookmarks and external links work as expected. There appears to be a slight glitch on larger screen sizes when video clips begin to play (screen distortion that only effects Red Dead and State of Decay) not sure what causes it, but it rights itself when you navigate up or down the page. 

## Google Lighhouse Testing
![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/LighthouseDesktop.jpg?raw=true)

## Validator Testing
- W3C Markup Validator
  - Flagged the following: Duplicate ID carouselExampleIndicators.  (which was being used by my four carousels, I changed their Id's to make them individual solving the validator error).
  <br>
- W3C CSS Validator
  - Was clean.

# Deployment

The site was deployed to Github pages using the following steps:
- On the GitHub repository, click on "Settings" tab.
- Go to the "Pages" tab on the left-hand sidebar.
- Under "Source" click the "None" dropdown and select the "main" or "master" branch.
- Click "Save".
- The page will update and show: "Your site is live at https://stevebesgrove.github.io/MileStoneProject-TheGamer/".

# Code  
The website code been written using the Bootstrap framework, [the Code Institutes lessons](https://codeinstitute.net/) and [w3schools](https://www.w3schools.com/).  
The header was adapted from the Code Institute Whiskey Drop mini project.


