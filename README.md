# Stockholm Floristry School
[View live project here!](https://alexdotrud.github.io/floristry_school_project/)

Welcome to the Floristry School Website, a demo project created to showcase the design and functionality of a floristry school platform.
This is a fictional website designed for educational and portfolio purposes. It serves as an example of how a floristry school website could be structured, offering information about courses, student works, and sign-up options for updates.

## Content:
  <ul>
    <li><a href="#user-goals">User Goals</a></li>
    <li><a href="#business-goals">Business Goals</a></li>
    <li><a href="#developer-goals">Developer Goals</a></li>
    <li><a href="#user-stories">User Stories</a></li>
    <li><a href="#design-choices">Design Choices</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#UX-design">UX Design</a></li>
    <li><a href="#testing">Testing</a></li>
    <li><a href="#technologies">Technologies Used</a></li>
    <li><a href="#bugs">Bugs</a></li>
    <li><a href="#deployment">Deployment</a></li>
  </ul>
</nav>

## User Goals
The website is designed to provide an engaging and informative experience for users who are passionate about floristry. Users should be able to:

* Explore educational possibilities by checking information about courses and programs on Home page.
* Explore floral arrangements created by students on Gallery Page.
* Sign up to receive updates about upcoming courses, events, and news.
* Navigate the website easily with a visually appealing and user-friendly design.

## Business Goals
This project simulates the online presence of a floristry school, focusing on key business objectives:

* Attract Potential Students – Provide an engaging platform that encourages users to explore courses and sign up for updates.
* Showcase Student Work – Build credibility and inspire future students by displaying high-quality floral arrangements.
* Improve Lead Generation – Use the sign-up feature to simulate how a real business would collect user interest and expand its audience.

## Developer Goals
This project serves as an opportunity to demonstrate web development skills and improve technical expertise:

* Build a Responsive and User-Friendly Website – Ensure a seamless experience across all devices.
* Implement a Functional Sign-Up System – Simulate real-world user interaction by collecting email subscriptions.
* Showcase Frontend Development Skills – Use HTML, CSS, and JavaScript to create an aesthetically pleasing and interactive interface.

## User Stories
* As a visitor (potential student), I can navigate a well-designed Home page, so that I can quickly understand what the school offers and find relevant information.
* As a visitor (potential student), I can browse available classes, so that I can explore different options and choose one that suits my interests.
* As a visitor (potential student), I can see the gallery, so that I can see examples of floral designs created by students and results of the classes.
* As a visitor (potential student), I can sign up for updates, so that I receive notifications about new courses and upcoming programs.
* As a visitor (potential student), I can find a contact section easily, so that I can quickly reach out to the school for inquiries or to reserve a spot in a course.

 ## Design Choices
 
 Wireframes:

* [Home](#home)
* [Gallery](#gallery)
* [Sign Up](#sign-up)
* [Success Page](#success-page)

 ### Home:

<img src="image/wireframes/Home Page.png" alt="drawing" width="600"/>

### Gallery:

<img src="image/wireframes/Gallery Page.png" alt="drawing" width="600"/>

### Sign Up:

<img src="image/wireframes/Sign Up Page.png" alt="drawing" width="600"/>

### Success Page:

<img src="image/wireframes/Success Page.png" alt="drawing" width="600"/>

## Features

### Home Page
Visually appealing design with easy navigation for users to explore the site.
#### Introduction section
General information about the floristry school, including its mission and offerings.
#### Courses section
Provides detailed information about courses and programs available at the school. Includes a sign-up button for easy access to the Sign-Up Page.

### Gallery Page
Showcases a variety of floral arrangements created by students.
Displays examples of completed work to inspire prospective students.

### Sign Up Page
#### Sign Up Introduction
Provides an overview of the benefits of signing up for updates, including information about upcoming courses and school news.
#### Form
Simple form for users to sign up for updates on upcoming courses and news.
Fields to collect user information such as name, email, username, and specific areas of interest in floristry.

### Success Page
Confirmation message displayed after users successfully submit their details via the sign-up form.
Thanks the user for signing up and confirms that they will receive updates.
Provides a smooth transition back to the main site, inviting further exploration of courses or gallery.

## UX Design
The UX design of the floristry school website is focused on simplicity, clarity, and accessibility, ensuring a smooth and enjoyable experience for all users. Key design principles include:

### User-Centered Design: 
The site is tailored to the needs of users, with a clear structure and easy navigation to help them quickly find information and engage with key features.
### Responsive Layout: 
The website is fully responsive, providing a seamless experience across all devices, from mobile phones to desktops.
### Clear Navigation: 
A straightforward menu and intuitive layout make it easy for users to explore different sections, such as the Home, Gallery, and Sign-Up pages.
### Visual Design: 
Floral imagery and a soft, nature-inspired color palette help immerse users in the theme of floristry. Key elements are highlighted with vibrant yet calming colors for a balanced, artistic experience.
### Mobile-First: 
The design is optimized for mobile devices, ensuring users enjoy a smooth experience on all screen sizes.
Forms & Feedback: The sign-up form is simple and user-friendly, with clear instructions and error messages. A confirmation page reassures users that their submission was successful.

### Color Scheme:
Primary Color: #43540d (green)
Secondary Color: #43372e (brown)
Highlight Color: #866FAC (purple)
Highlight Color (Light): #D4D3D3 (light grey)

### Fonts:
Primary Font: "Delius Swash Caps", serif
Secondary Font: "Delius Swash Caps", sans-serif

## Technologies used

- HTML
- CSS
- Bootstrap
- JavaScript
- Github (for deployment)
- Font Awesome
- Google Fonts
- Visual Studio Code

## Testing 
Testing was an essential part of the development process to ensure that the website functions correctly across different browsers and devices. Below are the various testing methods and results for the floristry school website:

### Manual Testing
#### Functionality Testing:

Ensured that all links, buttons, and form inputs work as expected.✅ 
Verified that the Sign-Up form successfully collects user data and redirects to the Success Page after submission.✅ 
Confirmed that the Gallery Page displays images and content properly.✅ 

#### Responsive Design Testing:
Tested the website across different screen sizes (mobile, tablet, desktop) to ensure the layout adjusts appropriately.✅ 
Verified that all content, images, and forms remain usable and visually appealing on all devices.✅ 

#### Navigation Testing:
Ensured that the navigation menu is easily accessible and functions correctly across all pages.✅ 
Checked that the Home, Gallery, Sign-Up, and Success pages are all linked properly.✅ 

#### Accessibility Testing:
Color Contrast: Verified that the text color contrasts sufficiently with the background for readability, adhering to accessibility standards.✅ 
Screen Reader Testing: Checked the website's compatibility with screen readers to ensure that users with visual impairments can navigate the site.✅
Keyboard Navigation: Ensured that all interactive elements are navigable via keyboard for users with limited mobility.✅
#### Performance Testing:


## Bugs

### Solved bugs
On the Home and Gallery pages, I was using Bootstrap Grid, so containers content were aligned more on the right. I rewrites margins and padding rules for the rows and divs and set it to 0.

For the courses card was used container, but on screen size 1200 it is showing 2 card on one row, and 1 on another.
Navigation on Gallery page for Courses and Contact were not functionoing- needed to add index.html to the link as well.
Low perfprmance on Gallery Page. https://www.optimizeyourimage.com/ - convert for webp format. and to compress - https://tinypng.com/, https://imageresizer.com/ -for resize the images
https://developer.chrome.com/docs/lighthouse/performance/uses-rel-preconnect/, https://expertbeacon.com/the-ultimate-guide-to-preloading-google-fonts-for-optimal-web-performance/ - to improve web perfomance, optimize google fonts loading.

### Unfixed Bugs

- No unfixed bugs found.

### Validator Testing 

- HTML 

On sign up page use (fieldset) element inside div with radio-buttons and checkboxes - fixed.
No other errors or warnings found.


- CSS

No errors found


## Deployment
Live project can be found here - https://alexdotrud.github.io/floristry_school_project/

The project was deployed using GitHub Pages, which allows for easy hosting of static websites directly from a GitHub repository.
 Below are the steps taken to deploy the website.

 ### Steps to Deploy:

#### Push to GitHub Repository:
First, the project files were committed to a GitHub repository. All HTML, CSS, JavaScript, and image files were uploaded and organized within the repository.
#### GitHub Pages Setup:
Once the repository was set up, the GitHub Pages feature was enabled. This is done through the repository's settings.
In the repository’s settings, navigate to the "Pages" section.
Select the main branch (or the branch containing your index.html file) as the source for GitHub Pages.
Choose the root directory as the source if the index.html file is located in the main directory.
#### Accessing the Live Site:
After enabling GitHub Pages, GitHub generates a URL where the project can be viewed live. This URL is shared and accessible by anyone with the link.
The live project can be accessed here: Live Project URL.
#### Continuous Updates:
Any future changes or updates made to the website can be easily deployed by committing changes to the repository, which automatically updates the live site.

## Publishing
We welcome contributions to floristry_school_project! Follow these steps:
### Forking
1. Fork the repository.  

2. Create a feature branch:  
   ```bash
   git checkout -b feature-name
   ```

3. Make your changes and commit:  
   ```bash
   git commit -m "Add feature description"
   ```

3. Push the changes and open a pull request:
   ```bash
   git push
   ```



## Credits 

### Content 
#### Text Content: 
All the content provided on this website is fictional and created for demonstration purposes only.
#### Images:
<ol> 
<li>Picture from Home Page are from- (https://pixabay.com/).</li>
<li>Pictures from Gallery Page and picture from Sign Up Page are from - (https://www.pexels.com/).</li>
<li>Logo was created on - (https://www.designevo.com/logo-maker/).</li>
</ol>

### Media
#### Fonts: 
The website uses the Delius Swash Caps font, available from Google Fonts.
#### Icons: 
Icons used in the site were sourced from FontAwesome (https://fontawesome.com/).
#### Other tools:
<ol>
<li>Stack Overflow: Used for troubleshooting and seeking solutions to development challenges (https://stackoverflow.com/).</li>
<li>CodeWithAnbu: Resource for learning and improving web development techniques (https://codewithanbu.com/).</li>
<li>W3Schools: Used for reference and tutorials on HTML, CSS, JavaScript, and more (https://www.w3schools.com/).</li>
<li>Chrome DevTools Lighthouse: Used to test and improve web performance (https://developer.chrome.com/docs/lighthouse/performance/).</li>
<li>ExpertBeacon: Helped in learning how to optimize Google Fonts loading for better performance (https://expertbeacon.com/the-ultimate-guide-to-preloading-google-fonts-for-optimal-web-performance/).</li>
</ol>