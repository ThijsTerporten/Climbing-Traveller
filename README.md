# The Climbing Traveller

This project will cover the best places available to climb outdoors, covering bouldering and lead-climbing in Europe.
The idea behind the project is to inform visitors and give them idea's about where to go on their next climbing trip.
While providing them different links to purchase any new gear and give them the option to subscribe to a newsletter to recieve monthly updates
about new locations to consider for their next trip.

## Showcase

A deployed version of my website can be found [here.](https://thijsterporten.github.io/Milestone-1/index.html)

## UX

The end user of this project can be anyone interested in finding a location to go on holiday and climb at the same time, or even someone that already
booked a holiday and is looking for a location near that place to go on a climbing trip.
The end user of this project would like to find clear descriptions of the locations listed:
* Type of climbing.
* Level of climbing in the area.
* Country.
* Accomodations. 
* Other things to do in the area.

The end goal of the project is to get people excited about climbing and inform them about outdoor climbing.

### UX stories

* As a user I want to learn more about outdoor climbing locations.
* As a user I would like to get inspiration for my next climbing trip.
* Do I need permits or certificates to climb outdoors?
* What equipment do I need to climb outdoor?
* Is there any way to learn more about climbing outdoor in general?
* As a user I would like to be updated about more locations I could visit in the futere.
* I already booked my holiday, is there a location I could go and climb near me.

## Strategy

### User Needs

As a user the site has to be accessible on mobile, tablet and all browsers. Information should be clearly laid out, informative and easy to read.
The site navigation needs to be optimal to move to the preferred section of the user.

### Business vision

The purpose of this project is to give users new idea's and a clear overview of the area of their next climbing trip.
The site also gives the users easy acces to external sites to buy new gear or an option to subscribe to a newsletter to 
give them updates about cool new climbing locations.

## Scope

I want my users to easily learn about outdoor climbing and some cool locations to check out. While having the option to find gear needed to start 
climbing outside available on a different page of the website.

## Structure

This project is a multi page website. Due to the large amount of information it wouldn't be smart to lay everything out in a single page.
It was originally designed as a single page project but after having the mentoring session with Antonija this was quickly changed.
For clarity and overview the project is divided in 4 pages. One for each type of climbing, one for the Home page, and one for the gear links.
On entering the landing page the user is greeted by a stunning image one might expect when going on a climbing trip. The user will then naturally find a small description 
of what the site is about and then naturally find a form to allow the user to subscribe to a newsletter. To get to the different parts the user can use the navigation
menu to easily find the type of climbing they are interested in or the section of the site to find new gear. 
Every other page is designed keeping this layout in mind as this provides intuitve learning for the user. 

## Skeleton

## Features

This section contains some of the features this project contains:
* The homepage will be the landing page showing a stunning image to instantly draw the users attention.
* The about section describes in a small paragraph what the site is about.
* The subscribe section gives the user the option to subscribe to a newsletter, or give feedback.
* Using the nav bar the user can navigate between pages for the type of climbing they are interested in.
* The user can use the gear up part of the website to find new gear they are looking for.
* The user can find full descriptions of the location using a link to the app "27-Crags".


### Existing Features

* The navbar collapses in a burger menu when viewed on an mobile device or a tablet.
* The user is able to fill in a form to sign up to a newsletter (not linked as of now).
* The user is able to use the website 'Gear Up!' page to find links to different websites that open up in new tabs.
* The user is able to move to a more detailed description about a location they are interested in by clicking on the link to 27 Crags at the end of the description.
* 
### Future Features

* In a future release the subscribe form will be linked to a mailing server.
* In a future release there will be a news page that will give updates about everything in the climbing world.
* In future updates there will be new sections added to each category of climbing. 

## Technologies

This project was build using the following technologies:

* HTML5
* CSS3
* Bootstrap: for grid and flexbox.
* Google Chrome Dev Tools: for testing purposes.
* Lighthouse: Used for testing website performence.
* Jquery: to simplify DOM manipulation.
* Prettier: to beautify code. 

## Testing

### Testing Plan

Starting this project I know what my target audience would like to see on a website with climbing as its topic (I'm a climber as well).
I took into consideration on what devices my users would like to see the website on. 
For testing I designed the website mobile first, with extensive testing using Chrome DevTools for all Iphone's.
Using DevTools I continued testing the website using settings for the Ipad and a 15.6 inch laptop screen.
For large screens I used a 24 inch monitor.
I wanted my page to be seen in a horizantel manner on larger screens a vertical manner for small screens, and on medium sized screens
I am aiming to be in the middle of these two.

### Implementation

As this is the first website that I created on my own I had no experience debugging on my own. Testing was mainly done using DevTools in google chrome. 
Starting mobile first then working my way up to bigger screen sizes. 
Whenever an element wasn't located where I wanted it to be I would use the element.style box in DevTools to find a solution. 
The element.style box was also used to pick color's for the navbar, the button underneath the subscribe form, the color of the footer and the opicity on top of the images.

I used Lighthouse in the DevTools as well to check the performance of my website and find errors in my code, for example I didn't have any rel="noopener noreffer" tags in 
my links that have target="_blank". Lighthouse made it clear to me why these tags are important to include. 

I used the WC3 code validators to check my code for mistakes as well. 

Testing is done in the following way: 

1. Scroll up and down the page checking for overflow and general positioning of items.
2. Use navigation bar to move to section of the page. -This is where the problem was found when on different pages for the subscribe link-. 
3. In the form, try and click the button to check wether all fields are required to be filled in, check as well wether the e-mail part was set to e-mail.
4. Check all links in the footer and on the gear-page wether they react as intended by opening in a new tab (for links section in footer).
5. Check wether the navigation part in the footer works correctly as intended. 
6. Rinse and repeat step 1 to 5 for each page.
7. Run through all of these steps for each different screen size.
8. Check each page whether breakpoints respond as intended using 'responsive' in DevTools.
9. Use HTML and CSS validators from W3C schools to find mistakes in code.

Note: For the gear.html page check whether all logo links open up in a new tab. 

### Results

Once I had a general idea on how to run testing I followed all steps for each of my pages which gave me the following results:

* While testing on the smallest mobile devices in DevTools I noticed that there was a slight overflow on the right. 
* When using the links in the navbar I noticed that the navbar would not automatically close when using a link once the navbar became a burger icon.
  This led to a poor UX since the dropdown menu would cover the text it was meant to navigate to.
* When using the dropdown menu links hovered over would remain black and the dropdown menu color was white, this didn't match with the design I had in mind using 
  my picked color scheme. 
* Scrolling through index.html it caught my attention that the subscribe form looked 'off'. It would fill the entire screen in width and since everything was centered
  it looked all over the place which led to a bad UX.
* While going through bouldering.html and lead-climbing.html I noticed that on medium and large screens the logo's underneath the text were going all over the place.
* When looking at the image on the gear.html page on smaller screens I noticed that the position of the image was a little bit off. This was an easy fix by positioning the image slightly different
  than the others.
* I noticed in gear.html that because I used the same color for the navbar and background-color in the logo-section, the navbar would look like it was being absorbed 
  by the section.
* After checking for breakpoints I realised that it would be better to show the items in a vertical manner as well. I noticed that the text would be too cropped causing bad UX.
  This was easily corrected by removing bootstrap-grid classes for medium sized screens.

Running my code in lighthouse I was able to see the performance, accessibillity, best practices and SEO of the website.
The overall score of each of the pages can be found here: 

Using lighthouse I was able to optimise the performance of the website given my current knowledge. (Some performance enhancements require JavaScript: Creating responsive images)
I was made aware that when using target="_blank" links I should include rel="noopener noreffer" as well to prevent the JavaScript function window.opener from stealing data
from my website by running the exact same process. Whereas noreffer ensures the target website can't see where the referral is coming from.

While running my code through the HTML-validator on W3C-schools I was made aware that I used blockquote in an incorrect way and that there was no heading to define the 
section that contains the articles in bouldering.html and lead-climbing.html.

Running my code through the CSS-validator on W3C-schools (Jigsaw) no errors where found.

HTML-validator results:
Jigsaw-result:


### Bugs

#### Overflow on smaller screens

During testing for smaller screens I noticed that there was a overflow on the right side of the screens.
First I checked whether I had all bootstrap included correctly, which I had since there where no issues on the other two pages. 
After disabling elements of the website that could cause the problem at first I thought it was the size of some words on my webpage that would break and cause the overflow, making some words
smaller fixes the issue for the time being but that should only be a temporary solution.
After further looking into this I realised it didn't have anything to do with the size of the words but my font-size was causing the problems (Set to 8vh at that moment) of the overflow on my page.
After doing further research on the matter I found that it is possible to fix this by using SASS. (Will be done this way in the future.)
For the time being I removed all styling regarding font-size in my css and instead set the font-size in the general styling-section of my CSS code. To accomodate the sizes properly on smaller screens
I added custom media queries for the font-size to balance it out within the limits of my current knowledge on the matter.

#### Images

Early on I was having a hard time getting the images to display properly. A quick google search told me to set a height of 100% to the element using css in order for it 
to display as intended. After telling my mentor what my issue was she send me a lot of links to articles and explained to me in detail how a background-image should be implemented
properly which gave me a clear understanding and prevented me from making the mistake later on. 
In the gear section the image had to be positioned further because the center of the image would go underneath the navbar on larger screens.

#### Bootstrap grid

I made a mistake while using bootstrap grid early on with the images, navbar and form part of index.html. Which made it quite difficult implementing it later on. 
Even though I was able to fix it, it learned me an important lesson to implement the correct classes in the proper order early on. Which made making the footer and the remaining
pages significantly faster. 
Furthermore the mistake made implementing the bootstrap grid would lead to a lot of unneccesary css which could have been avoided if the grid was implemented earlier on in development.
After doing testing I found out that this affected the targets of my links using the navigation as well. This has since been fixed.

#### Dropdown burger menu not collapsing when clicking on a link

During testing I noticed that the burger menu wouldn't collapse when using the links thus covering the content it is navigating to. This was fixed by going
through bootstrap documentation and using google. The terms 'data-target' and 'data-toggle' came up. Adding the data-target:"navbar.collapse.show" to al nav-items fixed
the issue.

#### Colors of nav-items in navbar and dropdown-menu

While testing I noticed that it was a bad UX to have the nav-items remain in the same color while hovering on them with the mouse.
Using dev-tools I was able to find out what classes to target in CSS this however didn't fix my problem immediatly, after doing some googling I found out that 
bootstrap classes had to be overwritten. 
I did this by using !important in my CSS code.

#### 27-crags link icons in bouldering and lead.html

While screen testing these pages I realised that the links underneath the text would not allign properly on the larger and medium size screens. 
After discussing this issue in a mentoring session, I got the idea to create new rows and cols using the bootstrap grid and using media-queries to make sure they are always shown
in a straight line related to each other.

#### Subcribe in navbar and footer when on a different page from index.html

Whenever I would click on the subscribe navigation it would not take me to the part of the page where you should be able to fill in the form. A quick google search and I was
able to find a fix for this. Where I was using index.html/#subscribe it should've been index.html#subscribe. After thinking about it this makes sense to me now, 
since you are searching for an ID on the same level and not in an underlying folder. 

#### Navbar blending in with color on gear.html page

While testing I noticed that the background-color on the gear.html page where the logo's for the brands are made the navbar fade away slightly. This caused a bad UX and made that part of the page appear kind of one-
dimensional. This led to the decision to give my navbar the illusion that it was 'floating'. After doing some googling on the subject I found a website with some cool designs for this. (link is included in acknowledgements)
I used the CSS snippet and modified it to my liking, which gave the scrolling through the pages a better visual experience.

## Deployment



## Credits 

## Content

## Media 

## Acknowledgements 
