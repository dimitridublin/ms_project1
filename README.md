# Student: Dimitrios Paraskevas
## Project: MS Project 1 - Build a Gym Website (March 2021)

### Booterstown Fitness - Your local fitness partners in South County Dublin
[View the live website here](https://dimitridublin.github.io/ms_project1/)

For my first Milestone Project I chose to build a five page website for an imaginary gym and fitness club, based in Booterstown, Co Dublin (i.e. project example idea 2 in the course assessment handbook). Roboto fonts were used for navigation and headings, Lato fonts were used for paragraph text. Verdana and sans serif fonts were also chosen as fallback in case Google fonts do not load. The website has been designed to be responsive for desktop, tablet, mobile and small screen mobile.

#### User Stories
As a prospective client I want to find out more about this establishment: its location, its opening hours, its membership options, its classes, its prices,
its parking facilities and I would also like to view photos from the club to get an indication of its facilities' range and quality. This would help me decide whether this gym offers good value for money, covers my work-out needs and whether it suits me to commit to a long-term membership. Easy to access links of the establishment's social media pages would also be welcome as they can provide additional info on the above.

As a current client I want to be able to easily find the organised classes schedule, pay for my membership and extras so that I can maximise my available time for working out and getting the most out of my subscription. I also want to have quick access to the business' contact details for when I am on the go and need to get in touch with them.

As the site owner I want to attract new members by providing information that would entice them to do so. I also want to facilitate my existing clients in being able to pay for their membership online, and in as few user steps as possible. In addition, I want to advise clients on the club's procedures for booking classes, provide them with links to my business' social media pages, and finally, I want to have a photo gallery to provide additional motivation to members to sign-on for classes and use the gym facilities. 

#### Features
##### Existing Features
* Header and footer maintain their style across website to provide a smooth navigating experience for users. 
* Company logo on top of page also functions as a navigation link back to the homepage.
* Homepage as well as every other page provide a direct link (i.e. "join now" button) to the membership page, where a "buy now" button would take user directly to the online payment page (payment page not developed as it was outside the scope of this project). This allows user reaching the online payment page in a maximum of two steps/clicks from anywhere on the website thus maximising user experience and achieving the respective site owner's requirement. 
* Homepage provides a "teaser" of up to four photos (depending on screen size) that showcase the establishment's excellent facilities, further enticing users to visit the gallery page for additional motivation to sign-up and/or attend.
* A page dedicated to the organised classes schedule, as required by both prospective and current members.
* Photo gallery showcasing the club's facilities as well as people using such in order to inform and create interest for potential members to join, and to motivate current members to attend.
* A contact page with a FAQs section and a contact form in case query not covered by FAQs, giving clients the option to submit their questions online (in case they prefer such). Giving users the option to phone, email, write, contact through social media or using the online form (and being able to review the business' private policy before committing to such) offers clients an enhanced user experience.
* A Google map iframe (in the contact page), which enhances user experience by allowing clients to connect to Google Maps' functionalities in terms of accessing the location as well as obtaining info on the nearby amenities.
* Footer provides a concise guide to the establishment's opening hours, location, public transport info, social media links and contact details. As such, user experience is further enhanced as their requirements are easily met from any web page.

##### Features to be Implemented
* Hero image to vary on each page to match more closely the respective page content (without compromising the website's smooth navigating experience).
* An online payments page to be developed so that clients can pay online for individual classes, day-passes and annual memberships.
* A Log-In area to be developed for existing members (accessible from the navigation menu) allowing them to view availability and book classes online instead of having to contact the gym's reception for such. 
* Logged-in members should also be able to view their existing booking history, details of their existing membership (e.g. contract remaining time, etc.) and also be provided with an option to upgrade to gold membership.
* Website to support the "POST" method once user fills all sections of the query form. Currently, user gets an error message when form is submitted fully filled as the posting function has not been developed (being outside the project's scope).
* Business could partner with a gymwear manufacturer/vendor to provide a link to their website so that BTF clients can purchase clothing/equipment at discounted prices, increasing both the gym's membership attractiveness and company revenue stream (as potentially gym will also be on a commission for each sale achieved through its website).

#### Technologies Used
* HTML
* CSS
* [Google fonts](https://fonts.google.com/)
* [Awesome fonts](https://fontawesome.com/)
* [Favicon](https://favicon.io/)
* Hex2rgba was used to [convert hex values to rgba](http://hex2rgba.devoth.com/)
* [Material Design's colour tool](https://material.io/resources/color/) was used to assess the accesibility of colour combinations used
* [Github](https://github.com/) and [Gitpod](https://gitpod.io/) were used for website development and version storage
* [Online HTML validator](https://validator.w3.org/)
* [Online CSS validator](https://jigsaw.w3.org/css-validator/)
* All images were reduced in size (“tinified”) without loss of quality using [tinypng](https://tinypng.com/)
* Wireframes were created using [Balsamiq Wireframes](https://balsamiq.com/wireframes/desktop/)

As this is the very first website i have ever developed I chose not to utilise any external frameworks, libraries or other tools as part of my coding with the exception of creating the company logo on favicon.io, importing the Google fonts Roboto and Lato as well as importing the awesomefonts v5.14.0 stylesheet for the membership page's trophy images and for the social media icons in the footer. This decision was made in order to:
  * Showcase my ability to develop a website using only HTML and CSS and without external aids (e.g. Bootstrap, etc.)
  * Allow me to devise original code for ms-project 2 onwards without needing to constantly cross check if chunks of code had already been used in ms-project 1 (as i expect/plan to extensively use Bootstrap in future ms projects)
  * Minimise any risk of appearing to plagiarise external chunks of code

#### Testing
Successfully tested user stories for compliance with requirements as follows:
* Prospective clients can effortlessly find out the information they have requested, either within the respective and intuitively named web page or by scrolling down to the footer area of any such page. Easy to access links of the establishment's social media pages have also been provided as required.
* Current clients can easily find the organised classes schedule and pay for their membership online with a couple of quick clicks from anywhere on the website. As requested, they also have quick access to the business' contact details at the bottom of each page.
* As the site owner I am satisfied that users can easily find the information they are looking for, thus increasing prospects of attracting new members. I am also satisfied that the needs of my current clients have been met as they can pay for their membership online, with a couple of easy clicks. In addition, the intuitive website layout allows for finding information quickly and effortlessly thus enhancing the user experience and meeting my business' needs. 

Automation of tests was not possible on this project. Manual testing confirmed compliance with user stories and intended function of features as follows:
* Clicked on company logo on each web page and navigated directly to the homepage as expected
* Clicked on the "join now" button on each page and navigated directly to the membership page as expected
* Navigation links worked as expected when clicked on each web page moving user directly to the respective web page
* Navigation links and all buttons/button type items changed appearance when hovered over as expected
* Active navigation links were indicated by their changed appearance as planned
* Clicked on each of the different photos on homepage and navigated to the gallery page as expected
* Homepage photos and gallery photos respond to different screen sizes as expected, i.e. rows of four images get progressively reduced to rows of three, two and one image depending on the screen size. At this point, i would like to draw attention to the fact that two different methods were used to achieve this result (i.e. the first by removing from the display the relevant image(s) on the homepage and the second through reducing the number of columns in the gallery page)
* Query form on contact page:
  * Tried to submit the form without all fields completed and verified that an error message regarding each missing field appears
  * Tried to submit the form with an invalid email address and verified that a relevant error message appears
  * Try to submit the form with all inputs valid and verified that form was looking to post the data ("405 Not Allowed" error page appeared as expected as form submission function was not due to be developed during this project)
   * Clicked on "Privacy Policy" and pdf with required info opened in a new tab as expected
   * Clicked on the "reset form" button and observed all fields clearing up
* Clicked on each social media icon on each page and they opened correctly in a new tab
* Successfully tested responsiveness for different screen sizes: desktop, tablet, mobile and small screen mobile (as i am using a laptop with a small screen i was not able to set up responsiveness/check such for extra-large screens). Page elements rearrange themselves according to the current browser screen width and site maintains consistency of design and information without any elements overlapping on screen
* Page layout largely complied with original wireframe designs for different screen sizes as planned. Wireframes created for desktop, tablet, mobile and small screen mobile (as per site's responsiveness set up). See respective [wireframe images pdf](assets/docs/wireframes.pdf) (20 frames in total covering the four designs).
* The above tests were carried out on Firefox and Chrome browsers to also verify browser compatibility (used respective dev tools i.e. responsive design mode on Firefox and toggle device toolbar/Lighthouse on Chrome, to check the responsiveness for different screen sizes)
* Ran the Lighthouse report on Chrome, with the following results: Performance: 95, Accessibility: 98, Best practices: 87, SEO: 96. Details of Lighthouse report confirmed that any issues identified were minor and not significantly affecting overall user experience or website performance
* Accesibility of colour combinations used was verified using the respective color tool from https://material.io/resources/color/
* The only HTML code errors when code is being validated correspond to the iframe code copied from Google Maps. As this was directly imported code from Google and iframe element performed as expected these error messages were not addressed and code was not amended. All other elements were successfully validated by the the course prescribed [HTML validator](https://validator.w3.org/)
* CSS coding was validated without any errors using the course prescribed [CSS validator](https://jigsaw.w3.org/css-validator/)

##### Interesting bugs or problems worth reporting
* Elements within the hero image (i.e. company logo, navigation menu, internal image container and join button) do not fully align in the centre of the screen for some mobile screen sizes
* "Buy now" buttons on membership page may appear slightly misaligned on some mobile screen sizes
* On homepage and under facilities, when the number of images is reduced to one that image may appear slightly stretched on some mobile screen sizes
* At the development stage, an X-Frame-Options blocker plugin had to be installed on to Firefox as browser was preventing the embedded Google map iframe from loading on to the page

#### Deployment
* Logged into my github account and from the [project page](https://github.com/dimitridublin/ms_project1) I clicked on settings and scrolled down to "GitHub Pages"
* Under "Source" I changed the default "none" to "master" so that my site's deployed code feeds from the my project's master branch 
* I saved the above change and my site was published at https://dimitridublin.github.io/ms_project1/

#### Credits
##### Content
FAQs were inspired and/or copied from https://westwood.ie/members-faq/

Private policy wording was adapted from http://www.formschool.ie/

##### Media
Image credits:
* All photos taken from Unsplash.com. The photographs used are credited to Mor Shani, Cathy Pham, Taiki Ishikawa, Arthur Edelmans, Danielle Cerullo, George Pagan III, Sam Moqadam, Bruce Mars, Sriyoga Ashram, Jamie Ginsberg, Jordan Nix, Jan Laugesen, HUUM, Bence Balla-Schottner, Nelka, Marcelo Uva, and Asaal Meher (please see in-code HTML comments for more details).
* Iframe code copied in its entirety from Google Maps, with height and width properties adjusted accordingly.

##### Acknowledgments
I would like to thank my mentor Akshat Garg for his useful tips and comments.

Many thanks to tutor Igor for resolving my github username issue and adding me to the unlimited team on gitpod.

I would also like to thank my class peers for their encouragement on the respective Slack channels.

And of course, thanks goes to my wife and children for keeping as quiet as possible while "daddy was coding"!
