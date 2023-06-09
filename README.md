# Elijah Fernandez T1A2 Portfolio README

## Important Links:

---

- [Published portfolio webiste](https://elijahfernandez.netlify.app)
- [Github repo](https://github.com/elijahjf/elijahfernandez_T1A2)
- [Presentation video](https://vimeo.com/834644742?share=copy)

## Purpose

---

The purpose of my portfolio is to have a public display of my professional capacity as a web developer to a prospective employer. I express my personailty, capability and experience in an accessible way that compliments my resume.

## Functionality / features

---

### **Typeface**
The font family used on the website is the google font: Poppins, fallback is Sans Serif

Styles:
- Light 300
- Regular 400
- Bold 700

### **Color**
I use a primary and secondary version of light, dark, and an accent color:
- Light Primary: #F8F5F2
- Light Secondary: #FFFFFE
- Dark Primary: #232323
- Dark Secondary: #222525
- Accent-Primary: #078080
- Accent-Secondary: #F45D48

### **Breakpoints**
Breakpoints are used to createa responsive design. I targeted Mobile, Tablet, and Desktop devices. I altered my breakpoints to specifically suit the needs and movement of my design elements at various sizes. This resulted as the following breakpoints:
- Small screen: 35.5em / 568px
- Medium screen: 48em / 768px 
- Medium-large screen: 49.5em / 792px
- Large screen: 72.5 / 1160px
- Extra-large screen: 80em / 1280px

### **Navigation bar**
The Navigation bar located at the top of every page. It is always visible, even when the page scrolls.

To the right, the navigation bar includes a square terminal logo. When clicked this returns the user to the homepage - `index.html`

To the left is where the user navigates between the pages of the website. This is displayed in two different ways depending on the size of the display. On larger displays, pages to navigate to are listed horizontally across the navigation bar. On smaller displays the navigation bar includes a hamburger menu. When clicked a list of pages to navigate to are drops down under the navigation bar and are listed vertically. These pages are:
1. Home - `index.html`
2. About Me - `about.html`
3. Projects - `projects.html`
4. Blog - `blog.html`
5. Contact - `contact.html`

When a page is hovered over it changes to the primary accent color.

### **Footer**
The footer is located at the bottom of every page, it is only visible when the bottom of the page is visible.

To the right, there is a copyright marking. 

To the left are three font awesome icons for social media links. The links are for:
1. Instagram
2. Linkedin
3. Github

These three icons open a link to the associated website in a new tab.

While the content of the footer does not change on different displays, the spacing is responsive. The larger the display, the larger the icons and the more spacing they have between each other compared to a smaller display.

### **Homepage**
`index.html` is the homepage of the website. This is the first page the user will see.

The components of this page are:
- Hero section
- Skills section
- About me short section
- Contact section

_The hero section includes:_
- A hero image. This is a memoji avatar of myself.
- The H1 title. This is the only H1 in the whole website to make it easy for screen readers to understand.
- Under the H1 is small pargraph that gives a small sense of; my occupation, interests, and passions.

_The skills section includes:_
- H2 Skills heading
- Rectangular tags for each of my technical skills. The tags are in the primary accent color.

_The About me short section includes:_
- H2 About Me heading
- A short about me paragraph

_The contact section includes:_
- H2 Contact heading
- A gradient button named "Reach out". The gradient button changes color on hover from a red to a yellow, and back to red off hover. The button redirects to the `contact.html` page.
- A mailto link for my email address.

![home-gif](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/gradient-button-reachout.gif)

### **About Me**
`about.html` is the About Me page of the website.

The components of this page are:
- A hero image. This is a memoji avatar of myself.
- Skills section, the same style as the homepage
- H2 About Me heading
- A longer about me paragraph
- A gradient button named "Reach out". The gradient button changes color on hover from a red to a yellow, and back to red off hover. The button redirects to the `contact.html` page. 
- A gradient button named "Resume". The gradient button changes color on hover from a red to a yellow, and back to red off hover. The button opens a new tab with a pdf of my resume. 

![about-gif](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/gradient-button-reachout-resume.gif)

### **Projects**
`projects.html` is the Projects page of the website.

The components of this page are:
- H2 Projects heading
- Three cards, one for each blog post. These cards have an opaque version of the secondary accent color and a subtle unique fun shape texture background.

Each card contains:
- Author name
- H3 Project name
- Paragraph short description
- A gradient button named "Coming soon". The gradient button changes color on hover from a a light color to the accent color, and back to light off hover. This button does not currently go anywhere as the "Coming soon" name sugests.

### **Blog**
`blog.html` is the Blog page of the website.

The components of this page are:
- H2 Blog heading
- Five cards, one for each project. These cards have an opaque version of the primary accent color and a subtle unique tech shape texture background.

Each card contains:
- Author name
- H3 Blog name
- Paragraph short description
- A gradient button named "Read post". The gradient button changes color on hover from a a light color to the accent color, and back to light off hover. This button goes to the corresponding full blog post.

![blog-gif](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/blog.gif)

### **Blog Posts**
`blog-post-1.html` to `blog-post-5.html` are the Blog Post pages of the website.

The components of each of these pages are:
- An Image
- H2 Blog Post heading
- A paragraph with the article content
- A gradient button named "Back". The gradient button changes color on hover from a a light color to the accent color, and back to light off hover. This button goes to the `blog.html` page.

### **Contact**
`contact.html` is the Contact page of the website.

The components of this page are:
- H2 Thank you heading
- Paragraph to wrap up the users experience on the website as well as calls to action
- A mailto link for my email address.
- Font awesome icons for Github and Linkedin links
- A form to fill out to contact me.


The form contains:
- First name label and input
- Last name label and input
- Email label and input
- Message label and input. This box is larger to contain a message of a few lines.
- A gradient submit button, similar aesthetically to the "reach out" button. This button is to submit the form, however it is currently does not have the functionality to do so.

![form-gif](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/form.gif)

## Sitemap

---

![sitemap](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/Sitemap.png)

## Screenshots

---

#### Walkthrough Video
Please Download: https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenrecord-mobile-site-walkthrough.mp4

#### Final Homepage
##### Mobile
![screenshot-mobile-home](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-home.jpg)
##### Tablet
![screenshot-tablet-home](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-home.png)
![screenshot-desktop-home](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-home.png)

#### Final About Me
##### Mobile
![screenshot-mobile-about](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-about.jpg)
##### Tablet
![screenshot-tablet-about](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-about.png)
![screenshot-desktop-about](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-about.png)

#### Final Projects
##### Mobile
![screenshot-mobile-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-projects.jpg)
##### Tablet
![screenshot-tablet-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-projects.png)
##### Desktop
![screenshot-desktop-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-projects.png)

#### Final Blog
##### Mobile
![screenshot-mobile-blog](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog.jpg)
##### Tablet
![screenshot-tablet-blog](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-blog.png)
##### Desktop
![screenshot-desktop-blog](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-blog.png)

#### Final Blog Post 1
##### Mobile
![screenshot-mobile-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog-post-1.jpg)
##### Tablet
![screenshot-tablet-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-blog-post-1.png)
##### Desktop
![screenshot-desktop-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-blog-post-1.png)

#### Final Blog Post 2
##### Mobile
![screenshot-mobile-blog-post-2](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog-post-2.jpg)

#### Final Blog Post 3
##### Mobile
![screenshot-mobile-blog-post-3](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog-post-3.jpg)

#### Final Blog Post 4
##### Mobile
![screenshot-mobile-blog-post-4](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog-post-4.jpg)

#### Final Blog Post 5
##### Mobile
![screenshot-mobile-blog-post-5](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-blog-post-5.jpg)

#### Final Contact
##### Mobile
![screenshot-mobile-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-mobile-contact.jpg)
##### Tablet
![screenshot-tablet-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-tablet-contact.png)
##### Desktop
![screenshot-desktop-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/img/screenshot-desktop-contact.png)

### **Mockup iteration**

#### Mockup V1
![mockup-v1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Mockups/phone_mockup_v1.png)

#### Mockup V2
![mockup-v2](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Mockups/phone_mockup_v2.png)

#### Mockup V3
![mockup-v3](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Mockups/phone_mockup_v3.png)

#### Mockup V4
![mockup-v4](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Mockups/phone_mockup_v4.png)

#### Mockup V5 - FINAL
![mockup-v5](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Mockups/phone_mockup_v5.png)

### **Wireframe Mobile**

#### Wireframe Mobile Homepage
![phone-wireframe-homepage](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Homepage.png)

#### Wireframe Mobile Navigation
![phone-wireframe-navigation](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Navigation.png)

#### Wireframe Mobile About Me
![phone-wireframe-about-me](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_About_Me.png)

#### Wireframe Mobile Projects
![phone-wireframe-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Projects.png)

#### Wireframe Mobile Project Post 1
![phone-wireframe-projects-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Project_Post_1.png)

#### Wireframe Mobile Project Post 2
![phone-wireframe-projects-post-2](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Project_Post_2.png)

#### Wireframe Mobile Project Post 3
![phone-wireframe-projects-post-3](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Project_Post_3.png)

#### Wireframe Mobile Project Post 4
![phone-wireframe-projects-post-4](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Project_Post_4.png)

#### Wireframe Mobile Blogs
![phone-wireframe-blogs](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blogs.png)

#### Wireframe Mobile Blog Post 1
![phone-wireframe-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blog_Post_1.png)

#### Wireframe Mobile Blog Post 2
![phone-wireframe-Blog-post-2](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blog_Post_2.png)

#### Wireframe Mobile Blog Post 3
![phone-wireframe-Blog-post-3](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blog_Post_3.png)

#### Wireframe Mobile Blog Post 4
![phone-wireframe-Blog-post-4](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blog_Post_4.png)

#### Wireframe Mobile Blog Post 5
![phone-wireframe-Blog-post-5](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Blog_Post_5.png)

#### Wireframe Mobile Contact
![phone-wireframe-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Mobile/Phone_Wireframe_Contact.png)

### **Wireframe Tablet**

#### Wireframe Tablet Homepage
![Tablet-wireframe-homepage](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_Homepage.png)

#### Wireframe Tablet About Me
![Tablet-wireframe-about-me](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_About_Me.png)

#### Wireframe Tablet Projects
![Tablet-wireframe-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_Projects.png)

#### Wireframe Tablet Blogs
![Tablet-wireframe-blogs](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_Blog.png)

#### Wireframe Tablet Blog Post 1
![Tablet-wireframe-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_Blog_Post.png)

#### Wireframe Tablet Contact
![Tablet-wireframe-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Tablet/Tablet_Wireframe_Contact.png)

### **Wireframe Desktop**

#### Wireframe Desktop Homepage
![Desktop-wireframe-homepage](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_Homepage.png)

#### Wireframe Desktop About Me
![Desktop-wireframe-about-me](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_About_Me.png)

#### Wireframe Desktop Projects
![Desktop-wireframe-projects](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_Projects.png)

#### Wireframe Desktop Blogs
![Desktop-wireframe-blogs](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_Blog.png)

#### Wireframe Desktop Blog Post 1
![Desktop-wireframe-blog-post-1](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_Blog_Post.png)

#### Wireframe Desktop Contact
![Desktop-wireframe-contact](https://github.com/elijahjf/ElijahFernandez_T1A2/blob/main/docs/Wireframes/Desktop/Desktop_Wireframe_Contact.png)

## Target Audience

---

The target audience is a recruiter seeking a developer. I have made the website cohesive and easy to navigate. 

I have respected the WCAG four guiding principles of an accesbile website; perceivable, operable, understandable, and robust. 

I present myself if a professional way, via the use of design priciples and copywriting. I use easy to read colors and fonts that are pleasing yet not distracting. I keep my writing susinct, positive and with a professional tone.

I positition myself a an expert, learner, leader, part of the community via my blog posts on fundamental topics of my field.

## Tech stack

---

- Website Front End: HTML5, CSS3, SCSS
- Readme: MD
- Git: Github
- IDE: VSCode
- Deployment: Netlify
- Sitemap: Octopus.do
- Wireframing: Figma
- Font: Google Fonts - Poppins
- Icons: Font Awesome - Github, Instagram, Linkedin
- Video Presentation: Vimeo
- Slide Deck: Google Slides
- Video editing: Canva
- Images: Unsplash


## References

---
“Beautiful CSS Box-Shadow Examples - CSS Scan,” n.d. https://getcssscan.com/css-box-shadow-examples.

Code, Seconds Of. “CSS - Show Additional Content on Hover.” 30 Seconds of Code, October 11, 2021. https://www.30secondsofcode.org/css/s/hover-additional-content/.

“ColorSpace - Color Palettes Generator and Color Gradient Tool,” n.d. https://mycolor.space/.

Color Hunt. “Red Green Color Palettes - Color Hunt,” n.d. https://colorhunt.co/palettes/red-green.

Contrast-finder.org. “Contrast Finder, Find Correct Color Contrasts for Web Accessibility (WCAG).” Contrast-Finder, n.d. https://app.contrast-finder.org/.

“Converting Colors - Hex - C672F4,” n.d. https://convertingcolors.com/.

Florczak, Łukasz. “Breakpoints and Media Queries in SCSS - Florczak.Dev - Medium,” June 21, 2018. https://medium.com/codeartisan/breakpoints-and-media-queries-in-scss-46e8f551e2f2.

FollowAndrew. “Responsive Pure CSS Menu Tutorial (No Javascript),” May 8, 2019. https://www.youtube.com/watch?v=sjrp1FEHnyA.

Font Awesome. “Font Awesome Icons,” n.d. https://fontawesome.com/icons/.

Google Fonts. “Poppins - Google Fonts,” n.d. https://fonts.google.com/specimen/Poppins.

Hameed, By Sharqa. “CSS Background vs Background-Color,” n.d. https://linuxhint.com/css-background-vs-background-color/.

Happy Hues. “Happy Hues - Curated Colors in Context.,” n.d. https://www.happyhues.co/palettes/8.

“Hex Color to Rgb, Hex to Cmyk and Hex to Hsl Conversion.,” n.d. https://www.colorbook.io/.

Kevin Powell. “Build a Responsive Website with HTML & CSS | Part Two: Writing the HTML,” July 7, 2022. https://www.youtube.com/watch?v=3K6zr1CdZy8.

Kevin Powell. “Fun Ways to Animate CSS Gradients,” August 7, 2019. https://www.youtube.com/watch?v=f3mwKLXpOLk.

Kudamatsu, Masa. “Don’t Nest  inside . Do Nest the Hamburger Menu Button inside .” DEV Community, October 20, 2022. https://dev.to/masakudamatsu/don-t-nest-nav-inside-header-do-nest-the-hamburger-menu-button-inside-nav-6cp#:~:text=3.-,Don't%20nest%20inside,the%20content%20of%20.

LearnUI. “The Responsive Website Font Size Guidelines,” n.d. https://www.learnui.design/blog/mobile-desktop-website-font-size-guidelines.html.

LekoArts. “Digital & Website Accessibility Solutions | AudioEye.” AudioEye, April 6, 2023. https://www.audioeye.com/accessible-web-design/colors/.

Netlify. “Develop and Deploy Websites and Apps in Record Time | Netlify,” n.d. https://www.netlify.com/.

Pickle, Ux. “Hamburger Menu Icon: Should It Be on the Left or Right? - UX Pickle.” UX Pickle, April 10, 2022. https://uxpickle.com/hamburger-menu-icon-should-it-be-on-the-left-or-right/.

“Sass: Syntactically Awesome Style Sheets,” n.d. https://sass-lang.com/.

Stack Overflow. “Stack Overflow - Where Developers Learn, Share, & Build Careers,” n.d. https://stackoverflow.com/.

THE NO.1 CHANNEL. “Viewing Your Project with Live Server on Your Android Phone,” October 5, 2021. https://www.youtube.com/watch?v=t7rFCTTWWC8.

Wade, Naja. “How to Design a Modern Website (in 9 Simple Steps).” Webflow, April 5, 2023. https://webflow.com/blog/how-to-design-a-website?utm_source=google&utm_medium=search&utm_campaign=Google-Search-Dynamic-Search-Ads-Core-BBSS&utm_term=aud-519773332254:dsa-1967776691993___585270939521___ss_paid-bb&gclid=CjwKCAjwq-WgBhBMEiwAzKSH6IJSsp-yMsJ-qTyhCTlFWhU_yuG0sYCXmT2X34XKJ5Qe4NDar2SDyBoCW_sQAvD_BwE.

Webdevetc. “How to Add a Gradient Overlay to a Background Image Using Just CSS and HTML - Web Dev Etc - My Software Development Blog,” June 16, 2021. https://webdevetc.com/blog/how-to-add-a-gradient-overlay-to-a-background-image-using-just-css-and-html/.

Weiler, Samuel. “World Wide Web Consortium (W3C),” n.d. https://www.w3.org/.

“W3Schools Free Online Web Tutorials,” n.d. https://www.w3schools.com/.
