# Brilliant Vision

## Introduction

The “Brilliant Vision” is a small business website of a local opticians in Killarney, Ireland. 
The site targets anyone needing opticians services and provides essential information for potential customers such as a list of services offered, the appointment booking form, location of the store with its opening hours and a google map. It also contains a ‘Gallery’ page showcasing glasses and sunglasses.

[View the live project here](https://walczakw.github.io/p1-brilliant-vision/)

![Responsive Mockup](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/responsive-mockup.png)

## Index
1. [**Introduction**](#introduction)
2. [**UX**](#UX)
   * [***Site Objectives***](#site-objectives)
   * [***User stories & Project board***](#user-stories-&-project-board)
   * [***Wireframes***](#wireframes)
   * [***Color palette choice and Accessibility***](#color-palette-choice-and-accessibility)

## UX

### Site Objectives 
The following information was gathered to find common goals and then to form the site requirements.

#### Main external user's goals
- To find information about services offered.
- To find information about location, phone number, email and opening hours.
- To find information about how to book an appointment.

#### Main site owner's goals
- To provide location information together with a google map to help potential customers with finding the store more easily.
- To provide a way of booking an appointment for the customers.
- To provide a way of sending online queries for the customers.
- To show examples of glasses and sunglasses offered in the form of 'Gallery' page.
- To provide all site elements in an accessible way, especially for people with visual impairments.

### User stories & Project board
- The site requirements were put into user stories. [Link to a separate document listing all user stories](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/user-stories/USER-STORIES.md)
- The user stories were then converted into issues for development. The Github Project was created to manage the issues. [Link to Project's board](https://github.com/walczakw/p1-brilliant-vision/projects/1)
  - Four columns were added to the Project's board: 'To do', 'In progress', 'Testing' and 'Done'.
  - A label was assigned to each issue for easier identification on a board.
  - Once the issue was developed and tested it went to a 'Done' column and status changed to 'closed'.

### Wireframes
The wireframes were created using the [Balsamiq](https://balsamiq.com/) tool. [Link to all wireframes in .pdf format](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframes.pdf)
- Firstly, the basic concept was added to display the site on mobile devices (phones and tablets). The goal was to show the layout of each element on the site. [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-mobile-and-tablet.png)
- Secondly, a separate wireframe was added to show how images on the 'Gallery' page will be displayed on bigger screens (e.g. tablets). [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-gallery-page-tablet.png)
- Lastly, the wireframes for the desktop were added together with more details such as potential color choice or sample images. These wireframes also include additional pages: 'Query form', 'Thank you' and '404 error'. [Link to wireframe](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/wireframes/wireframe-desktop.png)
- During the development stage, some changes were made to the initial concept. Main changes:
  - The decision has been made to put sections of the website into separate pages rather than to have a one scrollable page. This was to reduce the number of nav bar menu items by one so that there would be more space on smaller screens. This would not be necessary if a 'hamburger' type of menu was planned.
  - The landing page ('Hero' section) now has a background image visible at 100% screen width and 85% view height. This change was applied after receiving feedback from a test user who looked at the wireframes and suggested it for a more "professional" look.


### Color palette choice and Accessibility
- When choosing the color pallete, Accessibility  played a big role. The colors had to be visible to people with different visual impairments as much as possible. 
- The color 'red' was picked as the main color and then the right shade of 'red' has been chosen to correspond well with the main 'Hero' image and company's logo. 
- Then, colors for main text, background colors and links were picked to match the site's design and also to be WCAG 2.0 compliant at the same time. 
- Each color was checked using different contrast checking tools, e.g. [WebAIM](https://webaim.org/resources/contrastchecker/)
- The Contrast Grid was also generated to only show AAA compliant color combinations:
![Color Contrast Grid](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/validators-screenshots/contrast-grid-wcag.png)

## Features 

In this section, you should go over the different parts of your project, and describe each in a sentence or so. You will need to explain what value each of the features provides for the user, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

### Existing Features

- __Header with Navigation__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Header](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/header.png)

- __The landing page image__

  - The landing includes a photograph with text overlay to allow the user to see exactly which location this site would be applicable to. 
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![Hero](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/hero.png)

- __Services section__

  - The club ethos section will allow the user to see the benefits of joining the Love Running meetups, as well as the benefits of running overall. 
  - This user will see the value of signing up for the Love Running meetups. This should encourage the user to consider running as their form of exercise. 

![Services](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/services.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Love Running. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/footer.png)

- __Gallery__

  - The gallery will provide the user with supporting images to see what the meet ups look like. 
  - This section is valuable to the user as they will be able to easily identify the types of events the organisation puts together. 

![Gallery](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/gallery.png)

- __Location Page__

  - This section will allow the user to see exactly when the meetups will happen, where they will be located and how long the run will be in kilometers. 
  - This section will be updated as these times change to keep the user up to date. 

![Location](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/location.png)

- __Contact Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Contact](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/contact.png)

- __Thank You Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![Thank You](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/thank-you.png)

- __404 Page__

  - This page will allow the user to get signed up to Love Running to start their running journey with the community. The user will be able specify if they would like to take part in road, trail or both types of running. The user will be asked to submit their full name and email address. 

![404](https://github.com/walczakw/p1-brilliant-vision/blob/main/docs/docs-images/website-screenshots/404.png)

For some/all of your features, you may choose to reference the specific project files that implement them.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement

- Another feature idea

## Testing 

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your project’s features and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

### Manual Testing

### Testing User Stories

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fwalczakw.github.io%2Fp1-brilliant-vision%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fwalczakw.github.io%2Fp1-brilliant-vision%2Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Accesibility
- Performance

### Responsiveness 

### Unfixed Bugs

You will need to mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. 

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://walczakw.github.io/p1-brilliant-vision/


## Credits 

In this section you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 

You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign up page are from This Open Source site
- The images used for the gallery page were taken from this other open source site
