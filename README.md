## My Portfolio  

Welcome to my portfolio website. This website was created for my Code Insitute User-Centric Front-End Development Milestone Project. Here's a sneak preview: 

![my portfolio](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/my-portfolio-mockup.png)

This static wesbite is designed as an online portfolio that can be used during and after my time learning and creating with the Code Institute. It utilises my HTML, CSS and Bootstrap skills to serve as a landing page for potential clients and employers. It highlights my education and employment history, technical skills, and showcases projects I have created for local groups, small businesses and solo entrepreneurs. Potential clients are able to read client stories reflecting on how the projects I have created for them have had a positive impact and helped their ventures to flourish. After their journey thorugh my page, the end goal is that potential clients are persuaded to get in touch using the contact form so we can explore any potential projects. 


## UX
This website was primarily designed with prospective clients in mind. I envisioned my ideal client to be a small business owner looking for a website tailored to their business needs and ethos. My users needed to experience a website that had a clean, responsive design and showcased a range of skills, but didn't bombard them with effects. They needed to find navigating the site an easy and intuitive experience, and this needed to be true whether they viewed my website on a mobile device, tablet or computer. 

As my prospective clients scrolled through my site, I wanted them to get an overview of myself, my ethos and my employment and education history. I also wanted them to be able to download my CV if they wanted a more formal representation of this. By using project cards, I wanted to show off some of the projects I have done. For potential clients and employers that are more technical, I wanted them to be able to access the GitHub repositories for these projects. By using client stories, I wanted them to get a sense of the impact these projects had on the individuals and businesses they were designed for.  

Finally, at the end of a user's journey through my webpage, I needed them to have a way to contact me so we could chat about any potential projects. In the footer I needed icons that would link the user to my external social media sites, including GitHub, LinkedIn and Twitter, while keeping my own webpage visible. At the close here, in case the user had not done so already, I also needed to prompt users with another opportunity to download my CV. 

#### User Stories 
- As a small business owner in need of a website, I want to view a website where I can really get a sense of the designer, what they have done for other businesses and what they can do for me. I want a sense that a I will be working with a real person who really cares about the website they will build for me and the impact it will have on my business.  

- As a prospective employer for a web development company, I just need a way to see that my potential employee can develop a good website, view a portfolio of their work, and then download and print their CV, so I can assess their skills and experience and decide on whether to contact them for an interview.

#### Wireframes
Two wireframes guided the end design of this project, the first is for mobile devices, and the second scales up this layout for larger devices. I made both using [MockFlow](https://mockflow.com).

- [Wireframe for mobile devices](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/mobile-wireframe.png)  
- [Wireframe for larger devices](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/desktop-wireframe.png)

#### Colour Scheme 
I chose the two core colours for my website: #cccccc and #006666, which contrast well and look clean. All colours used are based around these, being either tints or shades and provide consistency that ties together all sections of the website. [color-hex](https://www.color-hex.com/) proved a very useful resource in this respect. 

![websafe-066666](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/websafe-006666.png)
![websafe-cccccc](https://github.com/mvmolloy/milestone-project-1/blob/master/assets/readme-images/websafe-cccccc.png)

## FEATURES
The page is headed by a navigation bar which is responsive to screen size. My name in the top left corner acts as a Navbar Brand and returns a user to the top of the page when clicked. The page is footed by a footer which contains social icons to my GitHub, LinkedIn and Twitter pages and a download icon to download my CV. 

The contact button and navigation bar collapses into a toggle menu on smaller screen sizes. 

Bootstrap ScrollSpy aids navigation throughout the page by changing the font colour of the active nav link. 

A centered hero image at the top of presents an image of a local cafe with a text overlay promoting my focus on designing websites for small businesses. A call to action button provides a directly targets the contact form at the bottom of the page. 

#### About & CV
Three blocks provide information about myself and my recent employment and education history. Each block contains a photographic image relating to the section. 

A banner separated into three parts with a radial background lists my front-end, back-end and data analysis skills.

Filler text at the bottom of the section prompts the user to read my CV. The user is then presented with a call-to-action button which opens a PDF of my CV in a new tab. When this is opened, my website remains visible in its existing tab. 

The user is then prompted by the filler text to scroll down to view the portfolio section. 

#### Portfolio 

The portfolio section presents users with six project cards. Each project card displays a mockup of my projects on different devices, gives a title for the project and a brief description, as well as an inline list stating the technologies used to create it. 

The final project card presents the user with a mockup prompting them to consider if their project could be next and a call-to-action button takes them to the contact form at the bottom of the page. 

#### Client Stories 
Four client stories are featured in four separate blocks. These include a photo of the client, the client's name and job title and the client story.

On smaller devices, these stories collapse. The first is expanded by default. Users can then expand and collapse the stories as they scroll through them. 

#### Contact Form 
The contact form has input fields for a user's name, email address, phone number and message. All fields require a valid input. The form contains a send button, which currently triggers a modal explaining the form does not work yet and providing my email address instead.
 

#### Future Features 
- [ ] Add the jQuery that will make the contact form work 
- [ ] Include real projects and real client stories

## Technologies
- HTML5
    - This project uses HTML to build the building blocks of the website. 
- CSS3
    - This project uses CSS3 to style the website's HTML.
- [BootstrapCDN v4.4](https://www.bootstrapcdn.com). 
    - This project uses Bootstrap to render it fuller responsive across a range of devices. 
    - The project also uses BootstrapCDN to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [Google Fonts](https://fonts.google.com)
    - This project uses Google Fonts to provide the Rubik font style used throughout the website.
- Gitpod
    - This project was built using the GitPod IDE to develop the code, which was then pushed to GitHub for Deployment.



## Testing
The HTML code was tested using the [W3C Markup Validation Service](https://validator.w3.org/) which showed an error where the button tags were nested inside anchor tags. This has been fixed by nesting them inside form tags instead. The validation service now shows no errors or warnings. 

The CSS was tested using the [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/) which showed one parsing error. This has been fixed by removing it. 
  
The responsiveness of the Bootsrap Grid was tested using Chrome Developer tools, responsive on all devices from the smallest, Iphone SE, to tablets and then on a wide screen device.
- On an Iphone SE device, the client-title in the collapsable client-stories expanded wider than the client-header element and caused a marign on the right-hand side of the page. This was fixed by applying the style "width: 100%" to the client-title element.
- I used WhatIsMyScreenResolution's [MultiScreenTest](http://whatismyscreenresolution.net/multi-screen-test) to test my websites responsiveness on screen sizes much larger than my own 14inch laptop screen. This showed me that I needed to fix the position of the skills list and buttons inside the project cards as they were moving outside of them on xl screen sizes. I have done this and they now scale properly.
  
Testing ScrollSpy showed a delay in the nav link becoming active. I fixed this by setting a ScrollSpy data offset of 50. Now each navlink changes to active at the correct position.   

All elements with a blank target attriute attribute correctly open links in a new tab and leaves the website visible in its existing tab.  
  
Both links to download a PDF of my CV in a new tab and leaves the website visible in its existing tab.  

The contact form validates input the phone and email fields. It displays an error message if all forms are not filled in. 

## Deployment 
This project is deployed using GitHub and hosted using GitHub Pages. The only project branch for this repository is the master branch and it is this branch which was used to deploy the project. The intended landing page has been titled index.html to ensure this site deploys correctly with GitHub Pages.  

For the project submitted to the Code Institute for assessment, the Master Branch and the project deployed to GitHub pages are identital.  

To run my project locally, select "Clone or Download" at the top of this GitHub repository. Select and copy the HTTPs URL provided. This URL can be used to clone my project by opening your Git Bash Terminal and using the command "git clone" followed by the URL.  

For any problems or questions relating to creating a local clone of my project, please refer to [GitHub's FAQ](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository). 

## CREDITS 

#### Content
All text content was written by myself.  

The downloadable CV is a mock-up version of my own CV using a Word Template. The paragraph template text on the CV has been let unedited. 

#### Media
All backgrounds were made using [SiteOrigin](http://bg.siteorigin.com).  

All images other than the Education image came from [Unsplash](https://unsplash.com/).  

The Education image is my own.  

The project mockups used in the portfolio section were made using [SmartMockups](https://smartmockups.com). The projects featured in these are either Code Institute projects that I have completed, or projects of my own.

#### HTML & CSS
The CSS for the radial background for the skills banner was generated using [CSSGradient](https://cssgradient.io/). 

