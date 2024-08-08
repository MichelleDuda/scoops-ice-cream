# Scoops Homemade Ice Cream Website

![Scoops](documentation/scoops.jpg)

## Index - Table of Contents
* [Introduction](#introduction)
* [User Experience (UX)](#user-experience-ux) 
* [Target Audience](#target-audience) 
* [Site Goals](#site-goals) 
* [Design](#design)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Testing](#testing)
* [Deployment](#deployment)
* [Credits](#credits)

## Introduction
This website is for SCOOPS, a fictional artisan ice cream company located in Beale, County Kerry, Ireland. The company is focused on creating small batches of handmade quality product with fresh local ingredients. 

The website is targeted to users who want to purchase artisan ice cream made with quality ingredients. The site exhibits the various flavors offered as well as other important information to help users locate the business and purchase our product.  

## User Experience (UX)

### Site Goals

  #### Site Owner Goals
  As the site/business owner I want to:
  - create an online presence to promote my business.
  - grow my customer base.
  - provide my customers with important information about my business, such as menu and opening hours.
  - provide my customers with a quick and easy means to contact us with any questions or concerns. 

  #### First Time Visitor Goals
  As a First Time User I want to:
  - easily navigate the website.
  - find out the location and opening hours.
  - easily understand the purpose of the site.
  - find the menu and prices.

  #### Returning Visitor Goals
  As a Returning User I want to:
  - easily find the menu and new offerings.
  - quickly access the opening hours.
  - provide feedback or ask questions.


## Design

### Colour
The colour scheme for this website is pink with white and black accents. The pink colour was extracted from the hero image using Microsoft Paint and various hues of that colour were used throughout the site. The colour scheme helps to provide a bright vibrant site that lifts the users mood as they navigate through it. 

<img src="documentation/colorpallete.jpg">

### Fonts
Google Fonts was used to import the Lato and Oswald fonts. These were chosen as they compliment each other well and have a simple and modern aesthetic. 

### Wireframes

<details><summary>Home</summary>
<img src="documentation/wireframes/mobile-phone-home.png">
<img src="documentation/wireframes/tablet-home.png">
<img src="documentation/wireframes/laptop-home.png">
</details>
<details><summary>Menu</summary>
<img src="documentation/wireframes/mobile-phone-menu.png">
<img src="documentation/wireframes/tablet-menu.png">
<img src="documentation/wireframes/laptop-menu.png">
</details>
<details><summary>Contact</summary>
<img src="documentation/wireframes/mobile-phone-contact.png">
<img src="documentation/wireframes/tablet-contact.png">
<img src="documentation/wireframes/laptop-contact.png">
</details>


## Features

### Logo and Navigation Bar
- A simple and interactive Logo and Navigation Bar is located at the top of each page. 
- The Logo links back to the homepage from any page throughout the site as this is a behaviour that would be expected by the user. 
- The navigation bar is located in the same position on each page and provides links to the three pages in the website (Home, Menu, Contact Us). 
- The page that the user is actively using is underlined in the navigation bar to provide a clear view as to which page they are currently on. 
- A thicker underline appears under each page name as the mouse hovers over it to assist in easy navigation for the user.
- The navigation bar is fully responsive on all screen sizes and collapses to a toggler on smaller screen sizes for ease of use. 

<img src="documentation/navigationbar.jpg">
<img src="documentation/navigationbar-small.jpg">

### Landing Image and Call to Action
- The Landing page contains a hero image and text overlay that clearly communicates the purpose of the website.
- A  button stating "View Menu" is also included in the text overlay as a call to action for the user. This serves as a quick link to the menu page. 
<img src="documentation/landingimage.jpg">

### About Us Section
- The About Us section is located on the main page under the hero image. It contains plain black text on a white background to maintain a clean and simple appearance, mimicing the clean simplicity of the ingredients we utilize.
- This section gives the user a clear description of what the company does and what its main ideals are. 
<img src="documentation/aboutus.jpg">

### Footer
- The Footer section contains 3 separate sections with imporatant information that a user could need easy access to - Opening Hours, Social Media Links, and Address/Telephone Number.
- The Footer is the same on all 4 pages of the website - Home, Menu, Contact, and Confirmation pages.
- The footer is placed on a pale pink background in keeping with the overall color scheme and to distinguish it from the rest of the page. 

<img src="documentation/footer.jpg">

### Page Heading
- Each page contains a heading element that lies over the same background image that was utilized as the hero image on the landing page. This allows all pages of the website to maintain a consistent look. 

<img src="documentation/menuheading.jpg"> 
<img src="documentation/contactheading.jpg">

### Menu Page - Flavors and Price List
- The Flavors section contains the current flavor options available to customers. Each flavor block contains the flavor name, a description, and a photo that relates to the flavor. This section is fully responsive and the blocks resize and wrap depending on the screen size. 
- The Price List section allows users to see the cost of our products and what sizes and options are availble to them - cups/cones to enjoy now, milkshakes for something a bit different, or a various size cartons to take back home to enjoy!

<img src="documentation/menupage.jpg">

### Contact Us Page
- The contact section of the page contains both a Contact Us section and a Find Us section. 
- The contact Us section contains a form that prompts users to enter their name, email address, and a message. Clicking the send button results in the user being brought to the confirmation page. 
- The Find Us section contains a map embedded from [Google Maps](https://maps.google.com) which the user can interact with along with our address and telephone number.

<img src="documentation/contactus.jpg">

### Future Features
- A feature that allows users to place an order online by adding items to a cart and paying.
- An additional section on the contact us form to allow users to sign up for discounts or a mailing list. 


## Technologies Used

### Languages
- HTML
- CSS

### Frameworks, Libraries & programs Used
- [Google Fonts:](https://fonts.google.com) was used for the fonts: Oswald and Lato.
- [Font Awesome:](https://fontawesome.com/) was used for various icons in the footer and headings of the pages. 
- [Google Maps:](https://maps.google.com/) was used for the locaiton map. 


## Testing

### Validator Testing
- [HTML Validator](https://validator.w3.org/)

  - Result for index.html
      ![HTML results index](documentation/validation-results/validation-no-error.jpg)
  - Result for menu.html
      ![HTML results menu](documentation/validation-results/validation-no-error.jpg)
  - Result for contact.html
      ![HTML results contact](documentation/validation-results/validation-no-error.jpg)
  - Result for confirmation.html
      ![HTML results confirmation](documentation/validation-results/validation-no-error.jpg)


  - Full Validation Results available:
    - <a href="https://github.com/michelleduda/scoops-ice-cream/blob/main/documentation/validation-results/html-validation-index.pdf" target="_blank">HTML Results - Home Page</a>
    - <a href="https://github.com/michelleduda/scoops-ice-cream/blob/main/documentation/validation-results/html-validation-menu.pdf" target="_blank">HTML Results - Menu Page</a>
    - <a href="https://github.com/michelleduda/scoops-ice-cream/blob/main/documentation/validation-results/html-validation-contact.pdf" target="_blank">HTML Results - Contact Us Page</a>
    - <a href="https://github.com/michelleduda/scoops-ice-cream/blob/main/documentation/validation-results/html-validation-confirmation.pdf" target="_blank">HTML Results - Confirmation Page</a>

- [CSS Validator](https://jigsaw.w3.org/css-validator)
  - Result for style.css
      ![CSS results](documentation/validation-results/css-no-errors.jpg)

  - Full Validation Results available:
    - <a href="https://github.com/michelleduda/scoops-ice-cream/blob/main/documentation/validation-results/css-validation-results.pdf" target="_blank">CSS Results</a>

### Lighthouse Testing
- Lighthouse result for index.html
    ![Lighthouse results index](documentation/lighthouse/lighthouse_index.jpg)
- Lighthouse result for menu.html
    ![Lighthouse results menu](documentation/lighthouse/lighthouse_menu.jpg)
- Lighthouse result for contact.html
    ![Lighthouse results conatct](documentation/lighthouse/lighthouse_contact.jpg)
- Lighthouse result for confirmation.html
    ![Lighthouse results confirmation](documentation/lighthouse/lighthouse_confirmation.jpg)

### Browser Compatibility
This website was tested on the following browsers:
- Google Chrome Version 127.0.6533.89 (Official Build) (64-bit)
- Microsoft Edge Version 127.0.2651.86 (Official build) (64-bit)
- Mozilla Firefox Version 128.0.3 (64-bit)

### Bugs
1. HTML Validator found stray end tag of for main element at line 155. Fixed.
### Known Bugs


## Deployment

### How This Site Was Deployed

This site was deployed via GitHub
1. Log into [GitHub](https://github.com).
2. Navigate to the repository [MichelleDuda/scoops-ice-cream](https://github.com/MichelleDuda/scoops-ice-cream).
3. Navigate to the [Settings Tab](https://github.com/MichelleDuda/scoops-ice-cream/settings).
4. Click on the [Pages](https://github.com/MichelleDuda/scoops-ice-cream/settings/pages) option in the left-hand pane. 
5. Select the main branch from the source dropdown menu.
6. Once the main branch has been selected the page will refresh automatically with a ribbon displaying that the deployment has been successful.
7. Any changes pused to the main branch will now take effect in the live project. 

Link to the live project: [SCOOPS Homemade Ice Cream](https://michelleduda.github.io/scoops-ice-cream/index.html)

## Credits

### Photos

1. [hero.webp](https://www.pexels.com/photo/sweet-ice-cream-with-fruit-16560507/) by David Disponett from Pexels. 
2. [applepie.webp](https://www.pexels.com/photo/delicious-ice-cream-on-plate-with-apple-pie-4340676/) by Spencer Davis from Pexels. 
3. [cookiesandcream.webp](https://www.pexels.com/photo/close-up-photo-of-cookies-and-cream-flavor-ice-cream-5060452/) by Roman Odintsov from Pexels.
4. [bananaicecream.webp](https://www.pexels.com/photo/ice-cream-with-chocolate-glaze-20683687/) by Ali Dashti from Pexels. 
5. [smores.webp](https://www.pexels.com/photo/chocolate-cake-with-vanilla-ice-cream-9500627/) by Gustavo Peres from Pexels. 
6. [strawberry.webp](https://www.pexels.com/photo/close-up-photo-of-strawberry-ice-cream-2161649/) by David Disponett from Pexels.
7. [caramelmacchiato.webp](https://www.pexels.com/photo/close-up-of-ice-cream-with-caramel-sauce-and-nuts-on-top-5060454/) by ROman Odintsov from Pexels. 
8. [birthdaycake.webp](https://www.pexels.com/photo/ice-cream-in-cone-16560569/) by David Disponett from Pexels. 
9. [sweetnsalty.webp](https://www.pexels.com/photo/tasty-desserts-served-on-table-in-cafe-6025811/) by Piotr Arnoldes from Pexels. 

### Code

1. Dynamic Resizing of iframe from [Stack Overflow](https://stackoverflow.com/questions/21868789/dynamically-resize-iframe).
2. The concept for the navbar toggler and the hero-image with cover-text was adapted from the Code Institute Love Running Walkthrough Project. 


### Acknowledgements

1. My mentor Dick Vlaanderen for all his helpful advice, guidance, and support.