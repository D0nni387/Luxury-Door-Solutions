<div style="text-align:center;">
<img src="https://i.ibb.co/mcbmG7g/logo.png"></img>
</div>

# Bringing Luxury Home

---

<div style="text-align:center;">
<img src="https://i.ibb.co/FX80jnh/readme-splash.png"></img>
</div>

## Aim of the site

The client has stated they are unhappy with their current website and have asked for this to be redesigned to the follow specification;

A website to showcase the offerings of a door and doorset manufacturer based in Barnsley, UK. 
The primary aim of the website is to one showcase the types of craftsmanship available and products that can
be designed and produced within the factory.

The primary customer will be a joinery contractor or architect working on the refurbishment or new build project in areas such as high end hotels, listed buildings or direct to their private client.
As this is a niche market with very little competition the main requirement of the site is to drive awareness of Luxury Door Solutions as a new business.

As a business, they have provided me with the following goals for the site.

1. A simple but professional design.
2. A colour pallet to reflect the logo and current physical marketing material.
3. An form to pass potential customer details across to the estimating team.
4. Clear and upfront showing of what they offer beyond just the product.

---

## UX

As the company is newly established the existing client base is small and obtained through previous working relationships. the main aim is to draw new clients that meet the below criteria 

1. Based within the UK & Channel Islands.
2. Is working within the construction industry.
3. Works with wealthy clients on high end projects.
4. Focus on quality over quantity

To help this site stand out from the other door and door set manufacturers based in the UK it needs to ensure it
* Is easy to use.
* Doesn't overload the user with too many 'walls of text'.
* Reminds the user to start building a relationship with the company.

---

## Client stories

"As a visitor to the site i want to be met with clear to the point information to allow me to understand what the business can do for me and how i can get the product i want to complete my project"

"As a visitor I want to ensure i feel confident that the company can provide the products to ensure my client is beyond satisfied with their final product"

"As a visitor I want to be able to easily find contact information so i can discuss my project with an estimator"

"As a vistor The site needs to explain that we can product fire rated and acoustic rated doors"

---

## Wireframe Mockups:

During the design process sitting with the client we drew up wireframes using [Balsamiq](https://balsamiq.com/) Upon initial completetion minor adjustments were made to allow the page to flow better for the user.

### Desktop
<div style="text-align:center;">
<img src="https://i.ibb.co/y02dgXL/luxury-doors-desktop.png"></img><br>
</div>

### Tablet

<div style="text-align:center;">
<img src="https://i.ibb.co/Hxnzh3G/luxury-doors-tablet.png"></img><br>
</div>

### Mobile

<div style="text-align:center;">
<img src="https://i.ibb.co/tmCngvw/luxury-doors-mobile.png"></img>
</div>

---

## Features

### About us

A brief introduction to the company showcasing 2 finished doors with a brief to the point introduction text

### What We Do

A deeper breakdown of the processes used to manufacture our doors and the labour and love that goes into each one

### Fire & Acoustics

A descriptive section to inform on the fire ratings and acoustic ratings the doors can be made to

### The Finishing Touches

3 Cards to describe the additional products that can be installed or supplied with the doors to help upselling

### Contact Us

A contact us form to allow for lead generation through the site, a map to the showroom and general contact information.

---

## Future Goals

### Document Uploading

The client has requested in future that documents for larger projects could be submitted for tender with potential job management through the site?

### Interactive Gallery

When the company has completed more projects they have said an easy to update gallery would be a good feature.

### Blog

As the director is keen to portray the ongoing jobs and completed works he has discussed the idea of doing a blog and maybe intergrating within the site.

---

## Technology Used

* HTML & CSS programming languages
* [Bootstrap](https://getbootstrap.com/) - to easily adapt the website to be responsive for all users
* [Google Fonts](https://fonts.google.com/) - Quicksilver & Roboto Styles
* [Font Awesome](https://fontawesome.com/) - Social Media Logos
* [jQuery](https://jquery.com/) - Javascript needed for navbar.
* [Popper.js](https://popper.js.org/) - Javascript needed for navbar.
* [VSCode](https://code.visualstudio.com/) - IDE for local developement
* [GIT](https://git-scm.com/) - Version Control
* [GitHub](https://github.com/) - to host the repositories for this project and the live website preview

---

## Testing

Testing was initial carried out using Chromes developer tools to ensure that the site scaled correctly on each screen size.

I frequently used the below tools to help ensure no issues as i progressed through my build.

- [W3C Markup Validation](https://validator.w3.org/) to validate HTML.

- [W3C CSS validation](https://jigsaw.w3.org/css-validator/) to validate CSS

- [Lighthouse Chrome](https://chrome.google.com/webstore/detail/lighthouse/blipmdconlkpinefehnmjammfjpmpbjk?hl=en) to audit best security practice and reduce loading times

- [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB) to help locate overflow issues


During my mid point review me and my mentor listed bugs that required fixing and features to add. On my mentors advice i produced a list of issues with expected time taken to fix on the following scale

* 1 - Will take a couple of minutes to fix or implement
* 3 - Will take approx 15 minutes to fix or implement
* 5 - Will take approx 1 hour to fix or implement
* 8 - Will take 4 - 8 hours (a working day) to fix or implement

My list is detailed below

<div style="text-align:center">
<img src="https://i.ibb.co/8b0BWZc/to-do-list.jpg" style"max-height:300px;">
</div>

### Issues and resolutions

During build the following issues were raised

-Collapse Icon Not Showing On Mobile Devices.

During my build the 'hamburger' icon failed to display when switching to mobile devices, this was resolved by adding the navbar-dark theme to the navbar class allowing me then to edit the perameters.

-Navbar not sticking to the top of the page as expected

This was resolved by removing the nav bar from the container which allowed this to function as expected.

- all text input on forms flagging as needing @ symbol

in the form parameters each was set to "type=email" instead of being "type=text"

- form allowing a blank form to be submitted 

Added required to the input tags to ensure core information has to be inputted.

- Nav menu scrolling to incorrect position

When using the nav menu items scrolling was taking the user to the content of the section instead of the header, this was resolved by moving the section ID to the title of the page instead of the content containers

- Nil links for social media icons opening new tab

As social media pages are not available at the moment clicking the icons opened a new browser with no address when click, this was resolved by removing "target=_blank" from the link code

- Fire & Acoustic Section text too cramped on tablets

Reduced padding from the card tiles to allow the text to have more room to display making this easier to read.

### Known Issues

Below are a list of problems that are known without resolution

- Smooth Scrolling not functioning on Safari or IE:E

This issue is unresolved as this is a browser issue not a site issue.

- Title font contast on white backgrounds doesn't meet readability guidelines

The issue has been raised with the client and a mid ground has been established as the client doesn't want to stray too far away from the logo colour.


---

## Deployment

To deploy this page to GitHub Pages from its [GitHub repository](https://github.com/D0nni387/Luxury-Door-Solutions), the following steps were taken: 

1. From the menu items near the top of the page, select **Settings**.
2. Scroll down to the **GitHub Pages** section.
3. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
4. On selecting Master Branch the page is automatically refreshed, the website is now deployed. 
5. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.
 

### How to run this project locally

To clone this project from GitHub:

1. Under the repository name, click "Clone or download".
2. In the Clone with HTTPs section, copy the clone URL for the repository. 
3. In your local IDE open Git Bash.
4. Change the current working directory to the location where you want the cloned directory to be made.
5. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/D0nni387/Luxury-Door-Solutions.git
```
6. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

---

## Credits

### Content
All images provided by the client from their existing website & test shots taken on site.

The initial paragraph of text was also reused from the existing site, all other text has been rewritten with the client. 

### Acknowledgements

Last of all i would like to thank my fellow students and everyone on the code institute slack channels for all their help with special mention to the below.

https://github.com/Eventyret - Simen Daehlin (mentor) for his invaluable input and advice

and my peers for their input in #peer-review-code

https://github.com/bennettpe - Bennettpe_alumni

https://github.com/wings30306 -JoWings

https://github.com/debrawolford/ - Debra Walford

## Disclaimer
Please note the content and images on this website are for educational purposes only.
