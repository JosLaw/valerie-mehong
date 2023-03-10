# <center> **Valérie Mehong - Tattoo Artist** </center>

This website is for and about London based tattoo artist Valérie Mehong. The site is targeted towards tattoo enthusiasts who have an interest in japanese style tattoos. The user may be looking for a tattoo artist based in London.

Access the site here: https://joslaw.github.io/valerie-mehong/

![website on different devices](/assets/images/readme_docs/devices_ss.jpg)

## **Goals/Expectations**
1. Provide information about the artist, and the location of her workplaces
2. Showcase the artist's work through a picture gallery
3. Provide a method of contact in order to make enquires

---

## **Design**
The website utilises a minimalistic colour pallete of black and white tones for background colours. The font is an imported font called BenchNine. All headings are in a light colour called Aliceblue #F0F8FF, with the font colour of the paragraphs being black. The links, excluding the header title, change colour to Aqua on hover action.

The initial layout was planned using a programme called Balsamiq to create the wireframes. This end product adapted over time whilst creating it, and elements were changed or ommitted due to the circumstances at the time. You can find the wireframes here: [wireframes](https://github.com/JosLaw/valerie-mehong/blob/main/assets/images/readme_docs/wireframes.jpg) 

### **Future Updates**
 - The initial plan was to have a video within the gallery showcasing the artist working. This will be added at some point once the footage has been obtained.
 - Link the form submission to an email address so that the data collected can be seen by the owner of the email address (artist).
 - Convert and reupload all images to a webp format for faster loading and increased performance.

---

## <center> **Features** </center>

 ### **Navigation**
 The navigation bar is fixed to the viewpoint so as the user scrolls it will remain in view at all times. This is so the user can navigate the site easily without needing to scroll to the top of the page. To differeniate it from the background, it has a slightly translucient background colour with light text. When the curser/mouse hovers over any of the sections, the background and text colour changes to signify which section you have selected. Each navigation title is a link to the named page.

![screenshot of navigation bar](/assets/images/readme_docs/nav_ss.jpg)

 ### **Header**
 The header contains the name of the artist for whom the website is for. This is fixed to the viewpoint across all pages. The text is large in a light colour to make it stand out from the black banner background of the block. It is also linked to the landing/index page. This will keep the artist's name at the forefront of the user's mind whilst interacting with the site

![screenshot of header stating "Valérie Mehong"](/assets/images/readme_docs/header2_ss.jpg)

 ### **Shop Locations**
 Embedded google maps have been placed on the page along with the written address of the tattoo studios. The maps are interactive and will open to full size on a new tab when clicked.

![screenshot of a Google Map](/assets/images/readme_docs/map_ss.jpg)

 ### **Gallery**
 Pictures of the artist's work have been presented within scrolling galleries. One gallery showcases Japanese style work, whereas the other gallery showcases work in other styles. The user can scroll through the gallery by moving the cursor onto the gallery and dragging it left or right. There is also a scroll bar underneath the galleries to assist with the scroll function. The user can also click on the image and use keyboard arrow keys to move between images. As it is a snap scroll, the next image will snap to the centre of the viewport within its container.

![screenshot of a picture gallery](/assets/images/readme_docs/gallery_ss.jpg)

 ### **Contact**
 A form has been created on the contact page for tattoo enquires. All of the boxes must have an input in order to be submitted. It includes a variety of input options including email to ensure a standard format email address is entered, radio buttons, free text with drop down suggestions, and a larger free text box for a description. The submit button is linked to another page which opens in a new tab when clicked. As this project is for educational purposes only at this point, the method attribute and subsequent "post" value has been omitted. ***No user input will be collected or forwarded to the artist***.

![screenshot of form](/assets/images/readme_docs/form_ss.jpg)
 
 ### **Footer**
 A clickable icon has been added to the footer of each page. The icon is linked to the artist's instagram page which will open in a new tab when clicked.

![screenshot of website footer](/assets/images/readme_docs/footer_ss.jpg)

---

## **Testing**

The site has been tested on a variety of devices and browsers to check all functions work correctly. These include the following:
 - Laptop on Google Chrome and Microsoft Edge browsers
 - Android mobile phone on Google Chrome browser
 - Iphone mobile phone on Safari broswer
 - Kindle tablet on Silk on browser

 The deployed site was shared amongst friends and family to obtain user experience feedback. Overall the feedback was positive and the set expectations listed above were met. As a result of feedback on the gallery, the tiptool has been amended to include a directional arrow to avoid confusion on how to use the snap scroll. In addtion, the font size on the form has been increased so all sections are clear to read.

---

## **Bugs**

On deploying the site, the link to the submission page stopped working. On reflection it was noted the location link was incorrect. Location path corrected and link now working as planned.

---

## **Validator Testing**
 - HTML - No errors returned through official W3C validator
 - CSS - No errors returned through official Jigsaw validator
 - Accessibility - Each page has been checked via lighthouse confirming over 60/100 across all areas tested

 ![screenshot of lighthouse test results](/assets/images/readme_docs/lighthouse_test.jpg)

---

## **Technologies**
 - HTML - Core structure and functionality of the site
 - CSS - Styling of the site
 - Gitpod - Code editor used to write/design the site
 - Github - Stores the site code and logged versions
 - Gitpages - Hosts the live site

---

## **Deployment**

The project was deployed to GitHub Pages. The steps below explain the process.

 - Log in to GitHub and locate the GitHub Repository
 - At the top of the Repository (not top of page), locate the "Settings" button on the menu
 - Scroll down the Settings page until you locate the "GitHub Pages" section
 - Under "Source", click the dropdown called "main" and select "root"
 - Click save
 - Scroll back down through the page to locate the now published site link in the "GitHub Pages" section

 Forking the GitHub Repository makes a copy of the original repository on the GitHub account to view and/or make changes without affecting the original repository. The steps below explain the process

 - Log in to GitHub and locate the GitHub Repository
 - At the top of the Repository just above the "Settings" button on the menu, locate the "Fork" button
 - You should now have a copy of the original repository in your GitHub account

Use the below steps to make a Local Clone
 - Log in to GitHub and locate the GitHub Repository
 - Under the repository name, click "Clone or download"
 - To clone the repository using HTTPS, under "Clone with HTTPS", copy the link
 - Open Git Bash
 - Change the current working directory to the location where you want the cloned directory to be made
 - Type git clone, and then paste the URL you copied in Step 3
 - Press Enter. Your local clone will be created

---

## **References/Credits**
1. [Code Institute](https://github.com/Code-Institute-Org/gitpod-full-template) - Initial framework used from template
2. [Ninetails Tattoo Studio](https://www.ninetailstattoo.com/) - Picture and bio information for Valérie Mehong
3. [Google maps](https://google.co.uk/maps) - Embedded maps
4. [Code Institute (love running)](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode/tree/main/06-site-footer) - Instagram icon code 
5. [Font Awesome](https://fontawesome.com/) - Instagram icon on footer
6. [Imarketinx](https://www.imarketinx.de/artikel/responsive-image-gallery-with-css-scroll-snap.html) - Scrolling gallery framework
7. Code Institute Coder's Coffeehouse - Aspects used for form on Contact page
8. [Pavel Danilyuk via Pexels](https://www.pexels.com/photo/close-up-shot-of-a-vintage-tattoo-machine-6593371/)- Hero image stock photo
9. [Am I Responsive](https://ui.dev/amiresponsive) - Responsive Screen Mockup
10. [Google fonts](https://fonts.google.com/) - Imported font BenchNine used across the site
