# The Final Frontier

The Final Frontier is a site that hopes to bring people enjoy talking, watching and discussing space together. It strives to create meetups for observatory purposes almost any day of the week. In those meetups, it goes out of it's way to create beautiful stories and captains about the stars and space objects that are observed. It will be fun and useful for anyone who loves space as a hobby.

![responsive mockup](/assets/images/Responsive.jpg)

## Features

### Existing Features

- __Navigation Bar__

- Featured on all three pages. Includes links to the Home Page, About and Contact page. It is the same in each page and allows for easy navigation

- This section removes the need to use the "back" button. It will always work for the user to navigate.

![Nav Bar](/assets/images/navbar.jpg)

- __The landing page image__

- the "hero" image includes a nice picture of space with some text to make the user feel like they entered a website for those who love space as they do.

![Landing Page](/assets/images/heroimage.jpg)

 __Favorite Stars Section__

- This section shows some stars the club loves to observe in a fun and interactive way. It lets the user see the results of fun activities the club engages in.

![Favorite Stars](/assets/images/favorite%20stars.jpg)

- __The Footer__

- The footer section does very little. But it does explain the purpose of the website clearly.

![Footer](/assets/images/footer.jpg)

- __About us__

- Tells the user more about the clubs reason to exist, and it's passion. It gives the user something to read and get attracted to.

![aboutus](/assets/images/about%20us.jpg)

- __Contact Page__

- Has a contact form and a table with opening hours for the user.

- This section is very valuable to the user. It helps them become part of the club.

![Contact](/assets/images/contact.jpg)

## Testing

This is my first project. As such, the first error I made was leave the README to the end. I must acknowledge this here and inform I realized this needed to be made side by side with the website I created. In my time making the website I have learned a lot, and some of them so fast and in such a high quantity, they needed to be detailed immediately. With that said, I will do what I can to detail what was done.

- Tested header position and found it bunched up. Used float to correct.

- Added home page pictures and text to it. In test found them needed to be aligned correctly. Used inline-block.

- added background picture and text to the about us section. In testing found the text on top of the header. Used a div with margins to  ensure center. 

- added table and form to the contact page. Used absolute position to center.

- When attempting responsive design, found that large margins on the about us section and absolute positioning on the form section caused it to never appear well on mobile. reused flexbox and flexwrap instead to position elements leaving only the about us margin in.

- in responsiveness testing, learned that float, absolute position and large margin setting makes it very diffcult to create responsive design. Replaced floats with flexbox on the header and index.html as well. 

- added media queries for the margin and some different display properties for mobile. Appeared good at testing this time.

- After contrast critique to the form area, found that the wrong color was set in CSS. adjusted to the right one. 

- While looking at the form section also found it to not validate input, added the required attribute to the elements(minus favorite star) to validate.

- The contact form also had open elements, cuasing error returns and also difficulty in styling and adding contract. the main and container div have now been closed. 

| Test | Action| Expectation | Result |
|------|-------|-------------|--------|
|Home page|Responsive to 320|Elements size to 320px|Works as intended|
|Home page|Responsive to 1920|Elements size to 1920px|Works as intended|
|Home page|Click button without data in form fields|cannot submit form|Work|
|Nar Bar - home page|Each Nav element navigates to the correct page|That each Nav element takes the user where they want to go|Works as intended|

## Validator Testing

- HTML

- No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fredsskull.github.io%2FThe-Final-Frontier%2Findex.html)

- No errors were found in the Abous Us section when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fredsskull.github.io%2FThe-Final-Frontier%2Fabout-us.html)

- No errors were found in the Contact section when passing through the offical [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fredsskull.github.io%2FThe-Final-Frontier%2Fcontact.html)


- CSS

- No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator?lang=en&profile=css3svg&uri=https%3A%2F%2Fredsskull.github.io%2FThe-Final-Frontier%2F&usermedium=all&vextwarning=&warning=1)

## Wireframes
I was not able to use Balsamiq well enough in the time I had. Thus, my Wireframe, or really, desgin idea was relegetaed to me and a marker. 

![Wireframe](/assets/images/Wireframe.jpg)

## User Stories
 - As a user, I want to fill in the contact form so that I can contact the sites administrator for more information.
 - As a user, I want to hover of the star images so that I can learn more about each star. 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:

- in Github repository settings, the live site was deployed from the main branch.

- The live link can be found here - https://redsskull.github.io/The-Final-Frontier/

## Credits

### Content

- The text for the About Us page was randomly generated by me.

### Media

- The photo used on the Header are from the open Source website Pixabay

- The star phones are as follows:

- Alpha Centauri is ESO/Digitized Sky Survey 2 Acknowledgement: Davide De Martin. found in various locations on the internet.

- Antares is Image credit: M. Kornmesser / ESO. fair use image made by said artist used commonly.

- Sirius was taken from NASA and ESAs database

- Pistol Star was taken from Wikipedia

- the image used in "comet" was made by https://www.linkedin.com/in/anouk-wilbrink-043bb0198/

- favicon is from Pexels.com

##Special Thanks

- I'd like to thank my mentor Lauren(https://www.linkedin.com/in/lauren-nicole-popich-1ab87539/) for all that you've taught me along the way. You always took the time to help me.

- I'd like to thank my friend Bogdan(https://www.linkedin.com/in/bogdan-paul-paduraru-b49b8998/) who always took the time to help me on a personal level even understand what coding is. This senior developer stopped what he was doing to helped me not make my computer explode learning to use Git and CSS.