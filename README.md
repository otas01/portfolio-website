# My Portfolio Website - First Milestone Project

This project is for my first milestone project with The Learning People. It is a portfolio website and I would certainly be improving the site as I progress in my web development journey. Being a portfolio website, it is meant to showcase my work to prospective clients and also to let them know a little more about my personal life. It also provides an easy way for me to be contacted for business consultations.

# Technologies used

- [Visual Studio Code](https://code.visualstudio.com)
  - The IDE used for this project was Visual Studio Code. For this project, I made commits and pushed my code to GitHub using this IDE.
- HTML
  - HTML was use to create the elements across the entire website before styling with CSS3 and Bootstrap 5.
- CSS3
  - A few elements were personally styled by me using CSS3
- Javascript
  - Minimal javascript was used in this project and it was entirely from Bootstrap 5. It was used to make the navbar collapsible.
- [Bootstrap 5.1.0](https://getbootstrap.com)
  - The bulk of the styling in this project was from Bootstrap version 5. This helped with a responsive design, navbar and general page structure.
- Git
  - The project uses Git for version control through regular commits.
- GitHub
  - I regularly pushed my code to GitHub.

# UX

- I wanted a simple yet sophisticated website that would describe what I do at first glance and this was why I went with the style and colours I used. A website should be easy to navigate and I ensured this was the case. There are direct links to the about me, contact and portfolio sections and this is accessible throughout the page thanks to the fixed navbar. I also included a "back to top" link at the bottom of the page to further ease navigation through the site.

# HTML and CSS Validation

- I used the [W3C HTML Validator tool](https://validator.w3.org/#validate_by_input) to validate my HTML code.
- I used the [W3C CSS Validator tool](https://jigsaw.w3.org/css-validator/#validate_by_input) to validate my CSS code.

# Mock up design

- The [mock up for my website](https://xd.adobe.com/view/eefe92c6-f2c1-4662-8fa0-469f645a1d98-bbad/) was designed using AdobeXD before starting to write out the code for it. This was mainly for the landing page. I stuck with a simple white/black background for the other pages.

# Features

- # Navbar

  - I used bootstrap 5's navbar and made it collapsible on smaller screens to keep the page neat. Each link targeted the desired area of the website. There is a logo as well which links to the landing page.

- # Social media icons

  - These link directly to my profiles on Twitter and LinkedIn and I could easily be contacted there as well.

- # Contact form

  - Again, I created the contact form with a snippet of Bootstrap 5 code from mdbootsrap.com . I used formspree to make the contact form work so I can receive the data entered.

- # Portfolio

  - There are a number of dummy images in the form of cards in the portfolio section just to show an example of how that section would look when it is populated with actual projects. Since this is my first ever website, there was no real project to include there.. for now...

# Potential improvements

- A better looking logo. I intend to get a more representative logo after I learn a bit about graphic design particularly for this logo.
- Background image in landing page may be changed to a brighter, sharper image, even though this may necessitate modifying a few colours
- When I learn a bit more about javascript and some back end, I would use a proper method in getting form data and also to get the navbar style to change after scrolling to a certain point on the website to improve visibility.

# Responsive testing

- I used Google chrome developer tools to test the responsiveness of the site for different screen sizes to ensure it appeared how I wanted and to make sure it was a consistent appearance. I also checked it out on mobile phones in portrait and landscape views.

# Interesting challenges

- The greatest challenge was actually coming up with a design. I looked at a million other portfolio websites just to get an idea. I would probably still overhaul this website in the new future but it was indeed a challenge coming up with the final design and sticking with it.
- Another challenge was getting to keep the logo on the left and the nav link items on the right. Got the fix and couldn't believe it was that simple. Fixed it by adding Bootstrap 5 "ms-auto" class to the "ul" wrapper of the navigation links.
- Getting my contact form to actually work posed a bit of a challenge but this was fixed following advice from my mentor. Got it work using [formspree](https://formspree.io).
- Another thing I struggled with was preventing my social media icons from getting pushed below the landing page in landscape view. This was caused by some padding and margins I used. I fixed it by putting the items of interest into a flexbox container and used the "justify-content-around" class in Bootstrap 5 to ensure responsive spacing.

# Deployment

- GitHub pages was the platform I used to deploy this website. I regularly committed by code on git and also kept pushing to GitHub. I began with an initial commit and several other commits followed until the website was finished. Summarised below are the steps involved in deployment from start to finish
  - Created a repository called "portfolio-website" on GitHub
  - Linked the repository to my local IDE(Visual Studio Code) with the following steps;
    - Opened up Visual Studio Code and clicked on clicked on ???explorer??? on the side bar
    - Clicked on ???Clone Repository??? and then pasted the GitHub repository URL in the input area provided when prompted
    - I then selected the preferred location to save the cloned repository locally on my computer
  - I then made the initial commit using the source control feature using "init" as the commit message
  - I kept pushing my code to GitHub regularly by using the "push" function in Visual Studio Code's source control.
  - When the website was complete, I pushed the final code to GitHub and deployed using GitHub pages as outlined below;
    - Signed into my GitHub account and opened the repository for the project
    - Clicked on settings and then into pages in the settings menu
    - Selected the main branch and also the root folder and clicked on save
    - Tried to see if it worked by entering the url into a browser

# Repository link

https://github.com/otas01/portfolio-website

# Website link

https://otas01.github.io/portfolio-website/

# Running code locally

To get a copy of my code to run on your system, follow the steps below;

- Go to [my project repository](https://github.com/otas01/portfolio-website)
- Click on "code" dropdown and then "download zip"
- Extract files from download and run code locally

# Credits

- # Content

  - The content of the website was largely mine as it had to be.
  - The background image of the landing page was downloaded from www.unsplash.com
  - The contact form was downloaded from https://mdbootstrap.com/docs/b4/jquery/forms/contact/ and modified by me
  - The template for the cards in the portfolio section was downloaded from bootstrap website and the images downloaded from www.unsplash.com

- # Media

  - The media for this project were entirely copyright-free, dowloaded from www.unsplash.com, www.pexels.com and also my personal photo.

# Acknowledgements

- I got a lot of initial advise from my first mentor, Sophie Wickham. She sent me links to very useful videos on Git and GitHub, AdobeXD, how to compress images and sample Bootstrap websites. She was of immense help in starting off this project.
- This project wouldn't be complete without critical input from my present mentor, Sunny Hebbar. He became my mentor in the middle of my project and took on the role seamlessly. He helped simplify my code in a number of areas and also is the inspiration behind this detailed ReadMe document. I also learned how to test for responsiveness of my website from him using Google Chrome developer tools
