Name: Mariam Rasheed
Course: INFR3120U - Web and Script Programming
Assignment 1: Personal Website 

Portfolio Website:
This website is my personal portfolio created using HTML5 and CSS3. Its purpose is to introduce myself, display projects I have completed in previous semesters, and provide a way for visitors to contact me. 
The website contains exactly four separate HTML pages: Home, About Me, Projects, and Contact Me. It uses responsive design and is hosted using GitHub Pages.

Live Website: https://mariam-rasheed13.github.io/Portfolio/

GitHub Repository: https://github.com/Mariam-Rasheed13/Portfolio

File Names and Their Purposes:
index.html - Home page
about.html - About Me page
projects.html - Projects page
contact.html - Contact Me page
style.css - Main stylesheet for the website 
laptop.css - Styling for laptop and larger screens
tablet.css: Styling for tablet screens 
phone.css - Styling for phone screens
mariam.jpg - My photo, used in the header, footer, and About Me page
introduction.mp4 - Introduction video on the About Me page
poster.png - Poster image displayed before the introduction video plays
README.md - Documentation explaining the website, design choices, and testing

Website Pages

Home:
The Home page contains a welcome card that introduces visitors to my portfolio. The navigation menu allows visitors to access the other three pages.

About Me:
The About Me page contains my photo, a short introduction about me, and an introduction video. 
The video uses HTML5 video controls and a poster image.

Projects:
The Projects page displays five projects from previous semesters. Each project has a heading and a short description explaining what I created.

Contact Me:
The Contact Me page contains a form where visitors can enter their first name, last name, email address, and cell phone number. It also includes radio buttons to give feedback about the website, a comments field, an "I am not a robot" checkbox, a reset button, and a submit button.  
HTML form validation is used to require the necessary fields and check the email and phone number formats.

Header, Navigation, and Footer:
All four pages use a consistent header, navigation menu, and footer.
The header contains my photo and navigation links to Home, About Me, Projects, and Contact Me. Each link opens a separate HTML page.
The footer contains my contact email address and copyright information. The email link uses the mailto: scheme so visitors can open their email application.

HTML5 and Semantic Elements:
HTML5 is used to structure all four pages.
Semantic elements used in the website include:
<header>
<nav>
<section>
<article>
<figure>
<footer>
<address>
These elements help organize the content and give the pages a clear structure. HTML5 video and form elements are also used.

Responsive Design:
The website uses a fluid responsive design so that the content adjusts to different screen sizes. The main stylesheet is connected to three separate CSS files using media queries.

Laptop:
Viewport: 960px and wider
File: laptop.css
This stylesheet adjusts the layout for larger laptop and desktop screens.

Tablet:
Viewport: 481px to 959px
File: tablet.css
This stylesheet adjusts spacing, image sizes, navigation, and project cards for medium sized screens.

Phone:
Viewport: 480px and below
File: phone.css
This stylesheet adjusts the layout for smaller screens. Content and project cards are arranged to fit the available screen width, and the navigation adjusts to fit mobile devices.

CSS Styling and Gradients:
The website uses CSS3 for colours, backgrounds, borders, spacing, project cards, forms, and responsive layouts.

Regular Linear Gradient:
The Home page background uses: linear-gradient(to bottom, #D8EEFF 0%, #7CB7E8 100%)
This creates a vertical colour transition from very light blue at the top to light blue at the bottom. 

Angled Linear Gradient:
The Welcome section uses: linear-gradient(135deg, #7CB7E8 0%, #2B6EA6 50%, #123C69 100%)
The 135-degree angle creates a diagonal colour transition through the Welcome section.

Adobe Color Scheme:
The website uses a custom blue colour palette created using Adobe Color. The palette is called "Mariam's Blue Theme."
The five colours used are:
#123C69
#2B6EA6
#7CB7E8
#D8EEFF
#FFFFFF
The colours are used consistently throughout the website to create a coordinated blue theme. Darker blues help important elements stand out, while lighter blues and white keep the website clean and easy to read across all four pages. 

Testing and Validation

HTML Validation:
Tool: W3C Markup Validation Service 
Website: https://validator.w3.org/
All four HTML pages were checked: index.html, about.html, projects.html, contact.html
All four HTML pages were checked using the W3C Markup Validation Service. In index.html, the home_main element was changed from a <section> to a <div> because it did not have a heading. In about.html, the about_main and about_intro elements were changed from <section> to <div> elements, and an <h1> heading titled "About Me" was added. In projects.html, the project_grid element was changed from a <section> to a <div> because it did not have a heading. In contact.html, the extra space in the email link's mailto: address was removed. After these corrections, all four HTML pages were validated again and showed no errors or warnings.

CSS Validation:
Tool: W3C CSS Validation Service
Website: https://jigsaw.w3.org/css-validator/
The four CSS files were checked: style.css, laptop.css, tablet.css, phone.css
All four files passed validation.

Link Validation:
Tool: W3C Link Checker
Website: https://validator.w3.org/checklink
The live website was checked for broken links. The internal navigation links, CSS files, and image link were fetched successfully.
The checker reported that access to the mailto: link was disabled. This was an expected limitation of the checker and did not mean that the email link was broken.

Spelling Check:
Tool: Grammarly
The spellings were checked using Grammarly.

Accessibility Testing:
Tool: Wave Web Accessibility Evaluation Tool
Website: https://wave.webaim.org/

The website was tested using WAVE. The initial report identified a contrast issue with the footer email and two alerts related to the radio button group on the Contact Me page.
To fix these issues, the footer email link colour was changed to white to improve contrast, and the radio buttons were grouped using <fieldset> and <legend>. CSS is used to remove the default border.
After these changes, the latest WAVE check showed no errors or alerts on the page tested. 

GitHub Pages Deployment:
The website is hosted using GitHub Pages. 
The repository is public and contains the HTML pages, CSS files, and media files required for the website.
Git commits were made during development to save and track changes.

Conclusion:
This portfolio demonstrates my use of HTML5, CSS3, semantic elements, responsive design, gradients, forms, and accessibility improvements. It presents my background and previous projects through four separate pages and provides visitors with a way to contact me.