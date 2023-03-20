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

  Why are we so special? What sets us apart?  
  - *It’s a unique website for the fictitious gamer.*

  Tech considerations?  
  - *Site is being made for the general public so will definitely have to be responsive as most will be viewing on mobile devices.*

  Why would a user want this?  
  - *For a more personal experience, the ability to watch their favourite fictitious gamer showcase gaming content and sign up for a personalised newsletter.*

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

## Google Chrome Inspector
- The website has been tested using the Google Chrome Inspector and is very responsive across all devices.

## Header
- All bookmark links work correctly and as expected. The dropdown menu works well, as does the burger menu on smaller screen devices.

## Home
- The external links all work as expected.

## CyberPunk 2077
- The CyberPunk 2077 logo link works as expected. (Would link to a playlist on Youtube if this was a real website).
- The CyberPunk 2077 video works as expected. Autoplay is off and the video controls all work.
- The CyberPunk 2077 carousel works as expected (auto rotations at a nice pace) and the navigation arrows work correctly.

## Red Dead Redemption 2
- The RD2 logo link works as expected. (Would link to a playlist on Youtube if this was a real website).
- The RD2 video works as expected. Autoplay is off and the video controls all work.
- The RD2 carousel works as expected (auto rotations at a nice pace) and the navigation arrows work correctly.

## State of Decay 2
- The SOD2 logo link works as expected. (Would link to a playlist on Youtube if this was a real website).
- The SOD2 video works as expected. Autoplay is off and the video controls all work.
- The SOD2 carousel works as expected (auto rotations at a nice pace) and the navigation arrows work correctly.

## The Witcher 3
- The TW3 logo link works as expected. (Would link to a playlist on Youtube if this was a real website).
- The TW3 video works as expected. Autoplay is off and the video controls all work.
- The TW3 carousel works as expected (auto rotations at a nice pace) and the navigation arrows work correctly.

## Newsletter Signup
- The form works as expected, each field is required and the form can not be completed unless it's filled out correctly.

## Footer
- The external links work as expected.

## Google Lighhouse Testing
![](https://github.com/SteveBesgrove/MileStoneProject-TheGamer/blob/main/assets/images/LighthouseDesktop.jpg?raw=true)

## Validator Testing (the code, before going live)
- W3C Markup Validator
  - Flagged the following: Duplicate ID carouselExampleIndicators.  (which was being used by my four carousels, I changed their Id's to make them individual solving the validator error).
  <br>
- W3C CSS Validator
  - Was clean.

## Validator Testing (live cloud)
- [W3C Markup Validator] **Document checking completed. No errors or warnings to show.** (https://validator.w3.org/nu/?doc=https%3A%2F%2Fstevebesgrove.github.io%2FMileStoneProject-TheGamer%2F/)
  <br>
- [W3C CSS Validator] **Congratulations! No Error Found.** (https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fstevebesgrove.github.io%2FMileStoneProject-TheGamer%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en/)

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


