## My Portfolio  

Welcome to my portfolio website. This website was created for my Code Insitute User-Centric Front-End Development Milestone Project. Here's a sneak preview: 

![my portfolio](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/my-portfolio-mockup.png)

This static wesbite is designed to act as an online portfolio that can be used during and after my time learning and creating with the Code Institute. Right now it's primary purpose is to submit as my User Centric Front-End Development project (Milestone 1) but eventually it will serve as a landing page for potential employers and clients. 



## UX
This website was primarily designed with prospective clients in mind. I envisioned my ideal client to be a small business owner looking for a website tailored to their business needs and ethos. 

The design of my site really needed to show them that I can design clean, responsive websites - it needed to showcase a range of skills without bombarding users. I needed it to be easy to navigate, and to speak to any prospective clients, and this needed to be true whether they viewed my website on a mobile device, tablet or computer. 

As my prospective clients scrolled through my site, I wanted them to get an overview of myself, my ethos and my history. I also wanted them to be able to download my CV if they wanted a more formal representation of this. By using project cards, I wanted to show off some of the projects I have done. For potential clients and employers that are more technical, I wanted them to be able to access the GitHub repositories for these projects. By using client stories, I wanted them to get a sense of the impact these projects had on the individuals and businesses they were designed for. Finally, I wanted users to have a way to contact me so we could chat about any potential projects. In the footer I have external links to my GitHub, LinkedIn, Twitter and Facebook page, as well as another link to download my CV. 

#### User Stories 
- As a small business owner in need of a website, I want to view a website where I can really get a sense of the designer, what they have done for other businesses and what they can do for me. I want a sense that a I will be working with a real person who really cares about the website they will build for me and the impact it will have on my business. 
- As a prospective employer, I just want a way to see my potential employee can develop a good website, view a portfolio of their work, and then download and print their CV, so I can assess their skills and experience and decide on whether to contact them for an interview.

#### Wireframes
Two wireframes guided the end design of this project, the first is for mobile devices, and the second scales up this layout for larger devices. I made both using [MockFlow](https://mockflow.com).

- [Wireframe for mobile devices](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/mobile-wireframe.png)  
- [Wireframe for larger devices](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/desktop-wireframe.png)

#### Colour Scheme 
I chose the two core colours for my website: #cccccc and #006666, which contrast well and look clean. All colours used are based around these, being either tints or shades and provide consistency that ties together all sections of the website. [color-hex](https://www.color-hex.com/) proved a very useful resource in this respect. 

![websafe-066666](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/websafe-006666.png)
![websafe-cccccc](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/websafe-cccccc.png)

## FEATURES
**Bootstrap ScrollSpy** aids navigation throughout the page by changing the font colour of the active nav link.  
**Navbar Collapse & Toggle** for smaller screen sizes.  
**Download CV** downloads my cv to a users default download file.   
**Call to Action Buttons** located throughout the page, prompting users to contact me and download cv.   
**Section Collapse & Expand** for client stories on mobile devices.   
**Contact Form** with fields for Name, Phone Number, Email Address and Message. All require an input and phone and email fields require this in the correct format.   
**Social links** to my Github, LinkedIn, Twitter and Facebook profiles, displayed as icons in the footer and open in a new tab, along with another link to download my CV.

#### Future Features 
- [ ] Add the jQuery that will make the contact form work 
- [ ] Include real projects and real client stories

## Technologies
- HTML5
    - This project uses HTML to build the building blocks of the website. 
- CSS3
    - This project uses CSS3 to style the website's HTML.
- [Bootstrap v4.4](https://www.bootstrapcdn.com). 
    - This project uses Bootstrap to render it fuller responsive across a range of devices. 
    - The project also uses BootstrapCDN to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [Google Fonts](https://fonts.google.com)
    - This project uses Google Fonts to provide the Rubik font style used throughout the website.
- Gitpod
    - This project was built using the GitPod IDE to develop the code, which was then pushed to GitHub for Deployment.



## Testing
-The HTML was tested using the [W3C Markup Validation Service](https://validator.w3.org/) which showed an error where the button tags were nested inside anchor tags. This has been fixed by nesting them inside form tags instead. The validation service now shows no errors or warnings. 
  
**Responsive Bootstrap Grid** tested using Chrome Developer tools, responsive on all devices from the smallest, Iphone SE, to tablets and then on a wide screen device. All elements respond to col-* classes as expected.  
    - When tested on an Iphone SE, the client-title in the collapsable client-stories expanded wider than the client-header element and caused a marign on the right-hand side of the page. This was fixed by applying the style "width: 100%" to the client-title element. 
    - I used WhatIsMyScreenResolution's [MultiScreenTest](http://whatismyscreenresolution.net/multi-screen-test) to test my websites responsiveness on screen sizes much larger than my own 14inch laptop screen. This showed me that I needed to fix the position of the skills list and buttons inside the project cards as they were moving outside of them on xl screen sizes. I have done this and they now scale properly.
  
**ScrollSpy** works regardless of the order sections are viewed in. Testing showed a delay in the nav link becoming active. I fixed this by setting a ScrollSpy data offset of 50. Now each navlink changes to active at the correct position.   
  

**target_blank** successfully opens all links in a new tab and leaves the website visible in its existing tab.  
  
**Download CV** opens up a PDF of my CV in a new tab and leaves the website visible in its existing tab.  

**Contact Form** validates input the phone and email fields. It displays an error message if all forms are not filled in. 

## Deployment 
This project is deployed using GitHub and hosted using GitHub Pages. The only project branch for this repository is the master branch and it is this branch which was used to deploy the project. The intended landing page has been titled index.html to ensure this site deploys correctly with GitHub Pages.  

For the project submitted to the Code Institute for assessment, the Master Branch and the project deployed to GitHub pages are identital.  

To run my project locally, select "Clone or Download" at the top of this GitHub repository. Select and copy the HTTPs URL provided. This URL can be used to clone my project by opening your Git Bash Terminal and using the command "git clone" followed by the URL.  
For any problems or questions relating to creating a local clone of my project, please refer to [GitHub's FAQ](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

## CREDITS 

#### Content
All text content was written by myself.  
The downloadable CV is a mock-up version of my own cv using a Word Template. The paragraph template text on the CV has been let unedited. 

#### Media
All backgrounds were made using [SiteOrigin](http://bg.siteorigin.com).
All images other than the Education image came from [Unsplash](https://unsplash.com/).  
The Education image is my own.    
The project mockups used in the portfolio section were made using [SmartMockups](https://smartmockups.com). The projects featured in these are either Code Institute projects that I have completed, or projects of my own.

#### HTML & CSS
The CSS for the radial background for the skills banner was generated using [CSSGradient](https://cssgradient.io/). 

