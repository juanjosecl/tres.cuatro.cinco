# TRES CUATRO CINCO STEAKHOUSE

TRES CUATRO CINCO STEAKHOUSE in Bogota, Colombia, is a charming family-owned restaurant specializing in imported American Angus Beef. We take pride in using ingredients from local small producers, ensuring a delightful dining experience that´s as fresh as it is flavorful.

This website serves as a digital gateway, purposefully designed to elevate our restaurant's online presence. Here, we invite you to explore not only our delectable gastronomic offerings but also to discover our versatility in hosting a diverse range of corporate events.

![Site view across devices](assets/readme_images/responsive_text_screenshot.png)

The TRES CUATRO CINCO STEAKHOUSE website, can be found here, followingthis link [here](https://juanjosecurreal.github.io/tres-cuatro-cinco/).

## Table of Content

+ [UX](#ux)
+ [Design](#design)
+ [Features](#features)
+ [Testing](#testing)
+ [Technologies Used](#technologies_used)
+ [Deployment](#deployment)
+ [Credits](#credits)

## UX

### Site Purpose and goal

The website was designed designed with a clear purpose: to provide prospective clients with comprehensive information about our restaurant. Here, you can explore our enticing gastronomical offerings and, if corporate events are of your interest, easily submit your contact information for personalized assistance.

### Audience

Our website caters to two audiences: beef enthusiasts seeking exquisite cuts and businesses in search of the ideal venue for meetings and events.

### Current User Goals

Keeping up to date with new information posted on the website.

### New User Goals

+ Ability to get a general understanding of the restaurant food and drink offerings
+ Contact the restaurant by filling out the form and explaining your desired type of event
+ Visit the company's social media

## Design

### Color Scheme

Our choice of a black and white color scheme isn't just about simplicity; it's a deliberate alignment with our brand's aesthetics. While it may seem easy, this classic combination is remarkably effective in enhancing user experience. The timeless elegance of black and white underscores our commitment to providing a seamless and visually appealing journey on our website.

### Typography

the font was not changed for this project.

### Imagery

All the images used for the website are images taken directly in the restaurant. No images were used from an outside source.

## Features

### Exisiting features

#### Navigation bar

 the navigation bar ensures effortless browsing. The choice of fonts and colors provide good readability and visual comfort. On larger screens, our navigation bar boasts the restaurant's logo on the left, exuding our brand identity, while neatly organized links to various sections of the page reside on the right, granting direct access to your desired content. 

![navigation bar](assets/readme_images/navbar_fullscreen.png)

For smaller screens, i have maintained this user-friendly approach by placing the logo on the left, accompanied by a sleek hamburger menu on the left.

![Hamburger menu nav bar](assets/readme_images/navbar_smaller_screen.png)

#### Home Page

On the homepage, I decided to keep it simple and created a banner. This banner displays a picture of one of our famous dishes, which is the hamburger. On the right side, you'll find the restaurant's logo. At the top of the image, there is a subtitle with the name of the restaurant and a brief explanation.

![Home page about us](assets/readme_images/banner_home.png)

#### About Us Page

This page offers users a glimpse into the essence of TRES CUATRO CINCO. It begins with a "HISTORY" section, delving into the restaurant's origins and our gastronomic philosophy, providing a comprehensive understanding of our journey and culinary approach.

![About us information](assets/readme_images/about_us_history.jpg)

Right Below the "HISTORY" section, you will encounter a circular image of the restaurant´s main salon. In my opinion it gives style to the site. By mixing pictures and text we are giving a better user experience.

![Mission and vision statements](assets/readme_images/circle_about_us.jpg)

The "About Us" section also includes a dedicated working hours section. It is imperative for users visiting the webpage to know when they can enjoy lunch or dinner. This information is clearly presented in a list right below the salon image.

![Company values](assets/readme_images/working_hours_aboutus.jpg)

#### Services Page

This page provides detailed information about the company's services, with each section featuring a title, highlighted text, and a few paragraphs of content. Users can easily request a quote or seek additional information about the company or a specific service by clicking the designated button within each section.

![Services page](assets/readme_images/services_readme_image.png)

#### Gallery Page

The purpose of this page is to showcase the company's portfolio of work. It provides a brief description of the project locations. Given the extensive number of projects undertaken by the company, there is a link to the contact page for obtaining specific information about individual projects.

![Gallery description](assets/readme_images/gallery_description_readme_image.png)

The subsequent section consists solely of a series of pictures showcasing the company's activities and projects.

![Gallery](assets/readme_images/gallery_readme_image.png)

#### Contact Page

Lastly, the contact page features a form on the right-hand side that allows users to provide the following information:
+ First Name
+ Last Name
+ Email
+ Phone Number
+ Project location
+ Interested service (as a dropdown)
+ Information requested about a quote or the company.

![Form](assets/readme_images/form_readme_image.png)

Furthermore, this section incorporates the contact information of the company, facilitating direct communication between users and the company for any inquiries or communication requirements.

![Contact details](assets/readme_images/contact_info_readme_image.png)

#### Form Sent page

This page follows the same layout as the contact page, but it serves solely to provide feedback to the user, acknowledging the receipt of the form submission.

![Landing page message](assets/readme_images/form_feedback_readme_image.png)

### Future features

As previously mentioned in this document, this project represents a prototype website for an actual company based in Colombia. As a result, there are specific features and enhancements that are planned to be implemented by the company over the next six months.

+ Enhancements to the dropdown navigation menu to align with best practices and improve user experience.
+ Transformation of the gallery page into a dedicated projects page, featuring individual pages for each project.
+ Introduction of a downloads page, enabling users to access and download technical information about the company, road standards, and other relevant documentation.
+ Addition of a WhatsApp link, providing users with quick access to send inquiries directly to the company.

Furthermore, it is important to note that the previous name of the company was Seprocivil Colombia SAS, which is reflected in the repository name and title of the HTML pages. However, prior to the official launch of the website, these details will be updated to reflect the current name of the company.

## Testing

The positioning of elements has been the most challenging aspect of this project. To address this, the use of flexbox has been crucial in positioning elements across all pages of the website. In order to ensure responsiveness without distorting the images, I employed viewport units to maintain their proportions effectively. This approach helped overcome the issues encountered and maintain a visually appealing and responsive design throughout the website.

To achieve the gallery display, I utilized flexbox and resized the images accordingly. All the images were standardized to a size of 350x350px, ensuring a consistent and visually appealing image display. This approach allowed for a cohesive and uniform presentation of the gallery images.

Another challenge I encountered was implementing an industry-standard "hamburger" menu for smaller viewports. After conducting extensive research on JavaScript dropdown menus, I arrived at the following solution:

![JavaScript code](assets/readme_images/js_script_readme_image.png)

By delving into the Code Institute topics of variables in JavaScript and Python and utilizing the document.querySelector method, I defined specific classes as JavaScript variables to introduce dynamic functionality.

Next, by combining these variables with CSS, I implemented a toggle system that allows for the opening and closing of the menu. This combination of JavaScript and CSS enables seamless interaction with the menu, providing a smooth user experience.

The project faced challenges in positioning form input items effectively. To address this, I grouped each label with its corresponding input element in individual div containers and utilized flexbox to arrange them. The form layout was further enhanced by implementing a max-width property, resulting in two adaptable layouts based on available space. This approach achieved a visually pleasing and responsive form design, elevating the overall user experience.

### Validatior testing

+ All html files pass through the [W3C validator](https://jigsaw.w3.org/css-validator/#validate_by_input) with no issues. ![html validator result](assets/readme_images/html_validator_readme_image.png)
+ All CSS files pass through the [Jigsaw Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) with no issues. ![CSS validator result](assets/readme_images/css_validator_readme_image.png)
+ Page has an excellent Accessibility rating in Lighthouse. ![Lighthouse report](assets/readme_images/lighthouse_readme_image.png)
+ Tested the site opens in Chrome, Safari and Mozilla.
+ No broken links

### Unfixed bugs

Additionally, it is worth noting that the website encountered an unfixed bug, which was unrelated to the code itself but rather caused by the hosting service. This bug prevented the execution of the JavaScript code, resulting in the unavailability of the dropdown menu and Font Awesome logos. The error message indicated was: "Cross-Origin Request Blocked: The Same Origin Policy disallows reading the remote resource at <https://kit.fontawesome.com/3156a2e938.js>. (Reason: CORS header ‘Access-Control-Allow-Origin’ missing). Status code: 530."

## Technologies used

### Programming langauges used

- HTML5
+ CSS
+ JavaScript

### Frameworks, Libraries & Programs used

- Google Fonts - for the font families: Roboto and Lato. San-serif was used as a default font.
+ Font Awesome - to add icons for the home services section, about us values section and the social media links in the footer.
+ GitPod/CodeAnywhere - to creat my html files & styling sheet before pushing the project to Github.
+ GitHub - to store my repository for submission.
+ Am I Responsive? - to ensure the project looked good across all devices.

### Deployment

The site was deployed to GitHub pages. The steps to deploy are as follows:

+ In the GitHub repository, navigate to the Settings tab
+ On the left hand side menu, navigate to the pages tab user code and automation.
+ In build and deplyment, under branch, select the main Branch
+ Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
+ The live link can be found [here - Infrastructura y Senalizacion](https://juanovt10.github.io/seprocivilCO/).

## Credits

### Design

The company provided all the information regarding the content information. The design was inspired by various type of engineering websites of multinational companies, including:

+ [Arup](https://www.arup.com/)
+ [AECOM](https://aecom.com/)
+ [eyrise B.V.](https://www.eyrise.com/)
+ [Henstaff Construction](https://www.henstaff.co.uk/)

### Code

From the very beginning, my mentor Martina Terlevic advised me to utilize flexbox for element positioning. However, as I encountered challenges in this area, I sought further guidance. I found the [flexfrog tutorial](https://flexboxfroggy.com/) and [flexbox guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/), which proved invaluable in helping me understand the workings of flexbox, its various applications, and any limitations it may have. These resources provided me with the necessary knowledge and skills to overcome my struggles and effectively utilize flexbox for optimal element positioning.

The standout feature of the project is the implementation of the "hamburger" menu. This menu type is well-suited for smaller devices due to best practices and a large navigation bar. To accomplish this, I referred to the full stack development lessons on [Code Institude](https://codeinstitute.net/global/) to grasp the principles of variables in JavaScript and learn how to transform HTML ids and classes into JavaScript variables. The resources utilized for this purpose were:

+ [W3C schools](https://www.w3schools.com/jsref/met_document_queryselector.asp)
+ [Tahmid Ahmed youtube tutorial](https://www.youtube.com/watch?v=VRrEquQfh88)

Furthermore, I drew inspiration for form styling and interaction from the following source:
+ [CodingLab](https://www.youtube.com/watch?v=okbByPWS1Xc)

### Media

The hero image was the only image taken from a free stock page:
+ [Road avenue with adjacent trees from Pixabay](https://pixabay.com/photos/asphalt-street-trees-avenue-2178703/)

The rest of the picture where provided directly from the existing company in Colombia. The contact details are the follwoing:
+ Eduardo Velasquez
+ eaduardoantoniovelasquezv@gmail.com
