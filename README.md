# Dowlais Fitness Gym
![image](https://user-images.githubusercontent.com/85559896/125904146-2d3fa7ef-b060-4d0c-b500-bdd6aad2f952.png)



![image](https://user-images.githubusercontent.com/85559896/125904016-89fec847-0159-4816-8681-4a443c29799a.png)


## Objectives of the project
The client is launching a fitness gym and wanted to showcase the facilities and classes available. To attract members from the local community and have their curiosity nudged.  

## UX

As a new business and all members will be new and likely to be from the local area. A website with the following features to attract them.


## User Goals

1. A website with appealing visual content.
2. An accessible website on a desktop, tablet and mobile.
3. Displaying the classes and equipment available at the gym.
4. Clear and easily found contact details.
5. Contact form available to contact the gym for additional information.



## User Stories
  * As a user, I want to know the location and opening times of the gym.
  * As a user, I want to find information about classes and equipment.
  * As a user, I want to able to contact the gym.
  * As a user, I want to see images from the gym of classes and the facilities.
  * As a user, I want to find a website that is easy to navigate.
  * As a user, I want the website to be intuitive as this will leave me with positive attude towards earning more.
  * As a user, I want to feel that i will get a swift response from the contact form inquiry submission.
  * As a user, I want the social media links to open in a new browser.
  * As a user, I want the classes timetable pdf to open in a new browser.
  * As a user, I want to feel this is the gym I want to be a part of.


## Site Owners Goals

* Promote a fitness gym in the local area.
* Create interest and new membership.
* Stand out from the competition.


## User Requirements and Expectations
### Requirements
  *  Relevant content about the gym
  *  A navigation menu that is easy to use.
  *  Appealing visual elements.
  *  Access to contact gym.
  *  information about classes and equipment.

### Expectations
  * Links opening in a new browser, such as social media links and timetable pdf.
  * A response when the contact form input has been submitted successfully.
  * Clear information of classes and facilities.
  * The customer successfully obtains the required information to make a positive judgement.

## Design Choices
### Fonts
I have used the "Roboto" font from [Google Fonts](https://fonts.google.com/) and liked the way it presents although I did explore the website for other fonts and have noted other styles for future projects.

### Icons
The use of icons has been kept the minimum and from the [Fontawesome](https://fontawesome.com/) library and use them for social media and a download option.


### Colours
The colour scheme used for the website was a green background with golden lettering. I chose these colours because i wanted the user to feel an air of quality and exclusivity, from previous subconscious experience. This colour scheme is similar to that used by Rolex and Wimbledon tennis tournament (this was underway during the design process). I hoped the clientele for the gym would be fimiliar with these and connect those entities of quality and would also be associated with the gym.
The background was #277676 and the text was #EC9209 but after runner a colour contrast test on the [Coolors](https://coolors.co/) website it scored badly and with a subtle change from green background a better scored was achieved without losing the "quality" look of the website.

### Structure
For my website I chose to use [Bootstrap](https://getbootstrap.com/). Bootstrap is a library of HTML, CSS & Javascrpit, focused on mobile first. As this is the primary format for the website to be displayed it improves that this website will work well on mobile.

## Wireframes

### Desktop
![desktop](https://user-images.githubusercontent.com/85559896/125909143-f2728b60-4191-43da-8956-6d0d1ce58dae.png)

### Tablet
![tablet](https://user-images.githubusercontent.com/85559896/125909187-759cce5f-41fa-40a9-8add-a47c3690f588.png)

### Mobile
![mobile](https://user-images.githubusercontent.com/85559896/125909154-0219138c-b365-4ec1-91ba-b043f1349590.png)

## Features
### Existing Features

#### About Us
 In bootstrap a single column has been created and a brief statement about the gym.

#### Gallery
A header and sub-header have been added to display some text, in this section bootstrap generates two each sized columns with two rows with a total of 4 images displayed within these. 

#### Classes
 A header is above three equal sized columns with three rows. In column 1 is the text describing classes held at the gym with a sub-header. In columns 2 and three are images reflective of the text beside them.

#### Schedule
A header is above three columns and a single row. The first column (col-md-6) and the further two columns Col-md-3), The first column has the download link with the two other columns have the buttons for booking classes and member login. These features are to be implemented at a later point.  Currently the buttons when actioned will take the user to the contact page using a link until these features have been created.

#### Facilities
A header is above two columns, in column one (col-md-8) and the column two Col-md-4). In column is the text detailing the gyms eqipment and facilities, with images supporting this text in column 2.

#### Contact Us
A header is above two columns and a single row. In column one is the address of the gym with a google map of its location below this. Below the map are the opening times of the gym. In column two the gym's telephone is again shown to allow the user an opportunity to note the number or to contact the gym using the contact forms provided.


### Features to be implemented
 * A member's login that allows direct booking of classes or personal trainer sessions.
 * Data submitted by the contact form is correctly actioned.
 * Monthly timetable that can be scrolled through.
 * All customer information is dealt with in accordance of GDPR regulations.
 * Booking classes via online booking.


## Technologies Used
### Languages
 * [HTML](https://en.wikipedia.org/wiki/HTML)
 * [CSS](https://en.wikipedia.org/wiki/CSS)
 * [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
 
 ### Libraries
 
 * Bootstrap
 * Google fonts
 * Font awesome
  
 ### Tools
 * Git
 * GitPod
 * Balsamic
 * W3C HTML Validation
 * W3C CSS Validation
 * TinyPNG
 * coolors.co
 * Chrome Dev Tools (incl Lighthouse)
 * Unicorn Revealer (extension on Chrome Development Tools)


## Testing

During testing I extensively used Chrome Developer Tools, ensuring the website acted correctly with various screen sizes.
I also used the following to fine tune the process;
 * W3C Markup validator tool for HTML.
 * W3C CSS validator tool for CSS
 * Lighthouse (chrome developer tools) for security and load times.

Button for member's Login, this feature is to follow at a later date. AS a temorary solution when the button is pressed the user is relocated to the website contact page.
Unfortunately this solution as it is correctly coded raises an error in the W3C markup validator. I will look into the adding a link to the button advising the feature is currently unvailable. This will resolve the issue with he W3C markup validator report. This also applies to the book classes button feature. This solution will be added to the website by the close of play on the 15th July 2021.

As discussed in ## Design Choices above whilst using coolors to find a better colour contrast the new choice of coloyrs but after changing the colour in the logo but reverted to the previous scheme because I felt it gave a bodlder aesthetic style to the website.

Whilst using Chrome's Lighthouse there was a slight overflow issue using the extension Unicorn Revealer showed all what was required to resolve the issue swiftly.

The download in the Schedule section works correctly opening a pdf in new page with the local environment but the 

During testing to make the contact form to standing out a bit more an off-white was decide upon and actioned.

The contact form will not submit untill the required fields have been populated but the feature to send to the gym will follow later so when submitted the user is returned to the top of the page. This will decided upon during testing not to leave the user with a broken feature, also the contact form requires a reset function. This is available in javascript and will be implemented later in development of the project after 18th July 2021.

The google map used in the contact us section does locate the gym's location correctly because I have used the map from the previous business's map and when launhed in a new paged gives this not dissolved business details. This is not ideal and going forward a new google map unique to the gym will be generated from the google map application.

## Deployment


The project after the completed code was commited and pushed to GitHub could be deployed and [found here.](https://davej66.github.io/dfg/). This is achieved by navigating to the page holding the project repository and executing the following steps:

1. From the menu select **Settings**.
2. Scrolling down the vertical menu (topped by Options) select **Pages** which leads to the **Source section**.
3. 



## Credits

I have used the following 4 websites to gather inspiration for content.

- https://www.villagegym.co.uk/
- https://www.aspirefitness.co.uk/classes
- https://atlanticsuiteshealthclub.gi/
- https://www.daves-gym.co.uk/
- https://pxhere.com/

I used pxhere to obtain commercially free to use images for this site.
The code for the "Jumbotron" was taken from the codeinsitute as was much of the remaining coding used in this project.


## Acknowledgements


Thanking my mentor [Richard Wells](https://github.com/D0nni387/) for his guidance and support. His suggestions during the mid-review led to improvements to website.

Support from the slack community when seeking assistance.







