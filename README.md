<h1>Sirjays Car Rentals</h1>

<p>Sirjays Car Rentals website is a webpage dedicated to serving the everyday car rental needs of the general public.
</p>
<h3>User</h3>
<ul>
<li>As a user, i want to be able to find a car rental company in my locality to rent a car.</li>
<li>As a user, i want to be able to see what offers the car rental company have.</li>
<li>As a user, i want to be able to learn more about the company's history.</li>
<li>As a user, i want to be able to see virtual evidence of the company's business environment.</li>
<li>As a user, i want to be able to reserve a car online.</li>
<li>As a user, i want to be able to contact the car rental company online.</li>
<li>As a user, i want to be able to see the categories of cars in the company's fleet.</li>
<li>As a user, i want to be able to find out the business hours of the company.</li>
</ul>
<h3>Business Owner</h3>
<ul>
<li>As a business owner, i want to be able to showcase my business to the general public.</li>
<li>As a business owner, i want to be able to clearly present the various services my business is into.</li>
<li>As a business owner, i want to be able to assure prospective customers of the stability of my business through the company's history.</li>
<li>As a business owner, i want to be able to share pictorial evidence of the company's business environment and friendly/assist-ready staff.</li>
<li>As a business owner, i want to be able to provide a fast and easy means of contacting the company.</li>
<li>As a business owner, i want to be able to avail users of information of the categories of cars in the company's fleet.</li>
<li>As a buisness owner, i want to be able to present my business opening hours to users.</li>
</ul>

<img src="docs/readme.images/testing.images/jpeg-optimizer_Capture.PNG" alt="A screen shot from amiresponsive website confirming the responsiveness of the project on all screens">
<br>

<h3>Features</h3>
<p>In achieving the user and business owner goals, i have created a four pages website consisting of: Home, About Us, Portforlio and Contact Us.</p>

<p><strong>Home page</strong></p>
<img src="docs/readme.images/jpeg-optimizer_HomePage.PNG" alt="Screen shot of the 'Home page' of Sirjays Car Rental project">
<ul>
<li>The Home page section clearly details the essence and purpose of the company in the header.</li>
<li>A navigation section to access the pages of the website is nested in the header of the homepage.</li>
<li>The services the company offer are detailed in the body of the home page.</li>
<li>At the bottom of the page is the company's contact details, social media channels and business hours.</li>
</ul>
<br>

<p>Navigation</p>
<img src="docs/readme.images/jpeg-optimizer_Navigation.PNG" alt="Screen shot of the 'Navigation section' of Sirjays Car Rental project">
<ul>
<li>The Navigation section of the project sits at the top of all file pages and houses the logo/company's name - Sirjays Car Rentals - on the left. This logo is clickable and brings users back to the home page.</li>
<li>On the right of the logo are the other navigation links to the other pages of the website. These include the About us, Portfolio and Contact sections.</li>
<li>The navigation appears at the top of all file pages and aids users to smoothly interact with all pages by simply clicking on any section they desire to visit.</li>
</ul>
<br>

<p>The Header</p>
<img src="docs/readme.images/jpeg-optimizer_Header1.jpg" alt="Screen shot of the 'Header' of Sirjays Car Rental project">
<ul>
<li>The Header houses the hero image and a pink overlay with content that summarizes the essence and purpose of the webpage.</li>
<li>Users are also able to access directly the contact/reserve form from the header via a reserve button inserted in the overlay</li>
<li>To ensure user accessiblity, the header has been clearly set on a white background using black font colour.</li>
</ul>
</li>
<br>

<li>
<p><strong>The About Us Section</strong></p>
<img src="docs/readme.images/jpeg-optimizer_AboutUs.PNG" alt="Screen shot of the 'About Us section' of Sirjays Car Rental project">
<ul>
<li>The About section tells the history of the company.</li>
<li>At the bottom of the page is the company's contact details, social media channels and business hours.</li>
</ul>
</li>
<br>

<li>
<p><strong>The Portfolio Section</strong></p>
<img src="docs/readme.images/jpeg-optimizer_Portfolio.PNG" alt="Screen shot of the 'Portfolio section' of Sirjays Car Rental project">
<ul>
<li>The Portfolio section gives users a virtual tour of the company's customer-friendly business environment while displaying a couple of car varieties in its fleet.</li>
<li>At the bottom of the page is the company's contact details, social media channels and business hours.</li>
</ul>
</li>
<br>

<li>
<p><strong>The Contact Us Section</strong></p>
<img src="docs/readme.images/jpeg-optimizer_ContactUs.PNG" alt="Screen shot of the 'Contact Us section' of Sirjays Car Rental project">
<ul>
<li>The Contact us section avails users of a contact/reservation form to use to do their bookings and contact the company.</li>
<li>At the bottom of the page is the company's contact details, social media channels and business hours.</li>
</ul>
</li>
</ul>
<br>

<h3>Testing</h3>
<ul>
<li>I tested and confirmed that the page works on different browsers; Chrome, Firefox and Safari.</li>
<li>I confirmed that the links in all the pages work.</li>
<li>I have confirmed that the contact/reserve form requires entries in every field and uses the reserve button to send.</li>
<li>I debuged the contact/reserve form so that empty values usually created with keyboard space key would be detected and invalidated.</li>
</ul>
<br>

<h3>Bugs</h3>
<p>Solved bugs</p>
<ul>
<li>After deployment, my logo won't stop wrapping on mobile screens of width of 315px and below. I created a new media query for screens of max-width 315px and below to debug the problem</li>
<li>Navbar items kept wrapping on tablet screens even after i reduced it's font size. I debuged it using the code - whitespace : nowrap; - on the media query of tablets</li>
<li>Reserve forms could be submitted with no values using the space key. I debuged the issue using the code - pattern="[A-Za-z0-9]{1,20}"</li>
</ul>
<br>

<h3>Validator Testing</h3>
<ul>
<li><p>HTML</p>
<ul>
<li>The W3C validator-detected errors were corrected.</li>
<li>No errors were returned when re-ran on W3C validator after correction was effected.</li>
</ul>
</li>

<li><p>CSS</p>
<ul>
<li>No errors were returned when css style sheet was run on the official (Jigsaw) validator.</li>
</ul>
</li>

<li><p>Accessibility</p>
<ul>
<li>I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighhouse in devtools.</li>
<img src="docs/readme.images/testing.images/jpeg-optimizer_Lighhouse1.PNG" alt="Screen shot of 'lighthouse accessibility diagnosis' of Sirjays Car Rental project">
</ul>
</li>

</ul>
<br>

<h3>Unfixed Bugs</h3>
<p>No unfixed bugs</p>
<br>

<h3>Deployment</h3>
<p>The site was deployed to GitHub pages using the following steps:</p>
<ul>
<li>Go to the settings tab of GitHub repository page</li>
<li>On the left-hand sidebar in the code and automation section, select pages</li>
<li>Set 'Source' to 'Deploy from Branch', select 'Main branch', set 'Folder' to 'Root', then click save</li>
<li>Click the 'Code<>' tab and wait a few minutes and then refresh repository</li>
<li>Go to the 'Environments' section on the right-hand side and click on 'github-pages'</li>
<li>Click on the URL displayed to see the live deployed site</li>
</ul>
<p>The live link can be found here - https://sirjay009.github.io/Sirjays-Car-Rentals/index.html</p>
<br>
<h3>Credits</h3>
<p>Credit</p>
<ul>
<li>The favicon link code was taken from https://www.w3schools.com</li>
<li>The navbar link code was taken from the CI love Running Project - https://sirjay009.github.io/love-running/</li>
<li>The code to debug navbar items that kept wrapping on tablet screen was taken from https://css-tricks.com</li>
<li>The code to debug contact/reserve form from accepting empty values was taken from https://stackoverflow.com</li>
<li>The code to make the reserve button in hero's overlay was taken from Alan Bushell's Belfast Auto Repairs project - https://alan-bushell.github.io/belfast-auto-repairs/index.html</li>
<li>The code to create space between text and font icons and debug footer was taken from https://wwwshecodes.io</li>
<li>The code to make the social media links was taken from both the CI Love Running Project and Alan Bushell's Belfast Auto Repairs project</li>
<li>Pieces of code for the general styling of the project was also taken from https://www.w3schools.com , https://www.codedamn.com , https://www.keentodesign.com and https://www.youtube.com/channel/UCvCyHScz5b1atuGYOQG_W8g</li>
</ul>

