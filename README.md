# Greenwood's Arborist Services
Greenwood's Arborist Services is a tree surgery company based in South West London, England.

The client Sam Greenwood had been working for another tree surgery company for the past 10 years. Over the past few months he has decided to start up his own buisness and work for himself alongside other tree surgeons he has met throughout his career.

Sam doesn't currently have social media platforms set up for his buisness, so he is quite keen to get a website up and running for his customers to see what they offer.

<!-- Live website image-->

<!-- Table of contents-->

## Client Expectations

Features the client wants on the website:

- Details of the areas that the company works in.
- A section for customers to get to know greenwoods team members.
- photos of previous work done by the company.
- A list of all of the services the company can provide.
- A form for clients to contact Greenwoods services.

The client want the website to be easy to use as they often get older clients, so the site should be simple and easy to work your way around, not over complicated.

## User Expectations

- As a user, I want to be able to easiy navagate through the website.
- As a user, I want to see the staff before they arrive at my property to do a job, so i have a   better idea of who I am inviting into my home.
- As a user, I want to see the quality of their work before booking them to do a job.
- As a user, I want to easily see if they can offer the service im looking for. 
- As a user, I want to be able to easily get in contact with the company to book a job.

## Wireframes

### Home Page

<img src="assets/images/home-mobile-wireframe.png" alt="wireframe for mobile version of the homepage">

<img src="assets/images/home-wireframe-1.png" alt="wireframe for the homepage">
<img src="assets/images/home-wireframe-2.png" alt="wireframe for the homepage">

### Services Page

<img src="assets/images/services-mobile-wireframe.png" alt="wireframe for mobile version of the services page">

<img src="assets/images/services-wireframe.png" alt="wireframe for the services page">

### Contact Us Page

<img src="assets/images/contact-us-mobile-wireframe.png" alt="wireframe for mobile version of the contact us page">

<img src="assets/images/contact-us-wireframe.png" alt="wireframe for the contact us page">

## Features

### Navigation Bar

- The Navigation bar is fully responsive and identical on all three pages this helps give the site a common theme.

- The company logo is also part of the naviagtion bar, this also acts as a link back to the home page.

- The home page has multiple sections so the navigation bar has links to the 'About Us' and 'Gallery' sections on the home page to make them easier to find.

### The Landing Page Image

- The landing page image with overlay text is there to introduce the user to the company 

- the overlay text also states that the company is London based so users are aware of the area in which the company operate. 

### About Us Section

- The About Us section gives teh users a little bit of background on who the company are and how they started up.

- It also includes a map of the areas that the company works in.

### Meet The Team Section

- This section is very important for making customers feel comfortable inviting workers into their homes. A large majority of Greenwoods Arborist Services customers are age 70+ and no longer want to or are able to take care of their gardens themselves, It is important that the customer can see who they are inviting into their homes to make it a more relaxing experience. 

- This section will include a description of each staff member and what they do for the company.

- An image of the staff member is also included so the customers know who to expect.

### Gallery Section

- The Gallery will provide the user with images that show what their work looks like.#

- This section can help customers make a quicker decition on if this is the company they want to go with. 

### Services Page

- Each section on the services page has a short description of what the service is.

- These descriptions come alsongside an image of the sevice to make it easier and faster for customers to identify which service it is that they require.

### Contact Us Page

- The contact us page has the companies information (email address and phone number) if the user would like to talk directly to a member of staff.

- The page also incudes a form that enables the user to leave a message for client. This form allows the user to leave a description of their request but also takes certain information to allow the client to get in contact via either email or phone with the user to answer any questions.

### Footer

- The footer includes important documentation like the terms and conditions of their services.

- The footer also has the companies email and phone number so that their contact information can be found easily on and page on the site. 

## Testing

### Validator Testing

### HTML

HTML was tested using the offical [W3C validator] (https://validator.w3.org/nu/) 
<!-- sort out link -->

The following errors/warnings were found:

 <img src="assets/images/test-contact-result-1.png" alt="A warning that the contact info section has no heading">

 <img src="assets/images/test-contact-result-2.png" alt="An error with the text-input class">

 <img src="assets/images/test-contact-result-3.png" alt="A warning that the form section has no heading">

### Errors/Warnings Fixed:

  1. contact information heading missing.
     - A heading was not needed so i changed the contact information section into a div inside 
       a main section on the contact us page.

Retested: Warning cleared

  2. Two classes were entered seperatly into the input elements in the form div.
     - I added the second class into the first as two were not needed. 
     - Originally it  looked like: class="form-input" class="text-input"
     - Now looks like: class="form-input text-input"

Retested: Error paassed

  3. form heading missing 
     - A heading was not needed so i changed the form section into a div inside 
       a main section on the contact us page.

Retested: Warning cleared

The HTML was then re-tested and results came back with no errors.

<img src="assets/images/html-test.png" alt="image showing errors are cleared">

### CSS
 
 CSS was tested using the the official [(Jigsaw) validator] https://jigsaw.w3.org/css-validator/
 <!-- Sort out link -->

 One error was found:

 <img src="assets/images/css-test.png" alt="Miss spelling of the word left causing an error">

  1. Miss spelling of the word left as a value for text-align. 
     -corrected spelling.

  Retested: Error Passed

  The CSS was then re-tested and results came back with no errors.

   <img src="assets/images/css-test-corrected.png" alt="CSS test showing no error">  

 ## Deployment

 <!-- the process you went through to deploy the project to a hosting platform (e.g. GitHub) -->
 ## Credits

 ### Content
programs used: gitpod/github, Balsamiq Wireframes, Procreate.
https://www.graftingardeners.co.uk/tree-surgery-services-london/ - inspiration for descriptions
https://www.codingnepalweb.com/scroll-to-top-button-html-css/ -scroll button
 ### Media
https://stock.adobe.com/ -images gallery services
https://unsplash.com/ - main tree image, team memebrs

