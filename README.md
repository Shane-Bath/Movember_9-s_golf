

# MO 9's - 9 HOLE GOLF CHARITY EVENT

[View the live site here](https://shane-bath.github.io/movember-golf-project/)

![Cover image for readme](/assets/readme-images/display.jpg)

# Table of Contents
- UX
  - Site owner objectives
  - User Experience
  - Goals of the site
- Design and Features
  - Structure
  - Colours
  - Fonts
  - Images 
  - Layout
  - Transitions
- Wireframes
- Technical
  - Tools and Libraries
- Testing 
  - Unfixed Bugs 
- Deployment
- Credit 

## Goals for this project
The site is to promote an annual local charity nine-hole golf event to raise money for the Movember men’s health charity. The Website main purpose is to provide information on the event and to allow individuals to book a place. A promotional website to sell to tickets to a 9 hole golf event to  raise money for Movember.



#  UX

## Site owner objectives

- Promotion of Event. 
- Provide up to date information. 
- Point of sale for tickets. 
- Celebrate the event and the cause.

## User Experience  

- Visually appealing.
- Easy Navigation.
- Provide appropriate information.
- Point of contact.
- Secure transaction.
- Up to date information.

## Goals of the site 

- Accessible on all screen sizes.
- visually pleasing presentation
- User friendly and enjoyable

## Design
I have taken inspiration from the Movember charity website and decided to adopt a similar style and tone, because to of the association between the two.  There is a strong black and white theme throughout the site, along with an irreverent style of communication.

## Structure
The site use CSS grid and flexbox. Grid provide the main the structure of the site, making use of gird areas to lay out the page. I used flex to control the content within each grid. This was not a straight forward process, and it took a number versions of the site to start to feel comfortable with the process. The key for me was whn I began to understand how to use flex to control the content within the grid areas.  There are number of example of this within the site
### Navigation

![navigation bar](/assets/readme-images/navigation.jpg)

   The Movember moustache image is incorporated  in the navigation bar, clicking the   moustache will bring the user back to the home page. Logo has been created using the a moustache image and the font Anton. Navigation bar will be responsive to various screen sizes

  Each section will have a hover effect.

  ![hover effect navigation bar](/assets/readme-images/nav-style.jpg)

   On smaller devices the Navigation Bar the logo and the navigation bar move to a column structure.

  ![Mobile navigation bar](/assets/readme-images/mobile-nav.jpg)

  The navigation bar and logo went through a few iteration and was source of a  number of issues for me attempting a responsive design. I attempted a number of   styles, including hamburger, with and without java script, drop down menu and a button style. In the end i settled on this simple button style.  I will discuss the issues of fixing the navigation bar to the top of the page in the bugs and fixes section. 
  
### Colours 
  The main colors will be black and white The Navigation bar transitions from white to a grey (#f7f7f7) and border-bottom of dark grey (#808080).
  Sponsors logo will be in grey scale with a hover effect to revert to original colour scheme 

### Fonts
  Main text will be a google font 'overpass', inspired by the original movember       website. Headings, logo text and promotion will be a google font 'Anton' inspired by the original movember website

### Images
  I have used a few photographs from my personal photographs and a free resource
  [unsplash](https://unsplash.com/s/photos/golf)

### Icons
  I have used the font awesome collection for the social media logos and arrows in the side banner. 

### Layout 
  The site wil be scrollable from header to footer, they only pages that will be separate will the contact us page and the gallery page. They will be accessible via buttons and navigation within the main body of the site. The user will be able to navigate to each section with the page. 


### Effects
  I have used hover effect to add interactivity and fun. The moustache and logo shake  when hovered over. The sponsor logo will transition from grey to the original colours when hovered over. The social media logo have a hover effect from light to a dark grey.

 ## Pages
### Landing page

![landing page](/assets/readme-images/landing%20page.jpg)

This page consist of text and images, and a side section encouraging user to donate to the Movember organisation. This page will inform the user about the event, direct them book a place. 

### Banner

The banner was created using text, font awesome icon and image. Creating the banner help me understand flexbox, as I use flex to change the banner in smaller screens, for vertical to horizontal. 

![banner vertical](/assets/readme-images/banner-v.jpg), ![banner horizontal](/assets/readme-images/banner-h.jpg)

There are a number of hover effects, when you hover over the banner, the colors invert. If you hover over the moustache image, it wiggles and expands. If you click on the moustache, it will bring you to the movember website on a new tab.

![banner inverted colors](/assets/readme-images/banner-w.jpg)


### Locations

![locations page](/assets/readme-images/locations.jpg)

This page consists of image and text with a button. In larger screen to the two locations are side by side. They stack on top each other in smaller screens. The button brings the user to a pop-up page booking page (modal). 

### About us, Gallery, Contact and Sponsors 
  Information about the organisation and sponsors of the event
- Gallery 

    A mix of different sizes of images in a grid structure. I  assigned grid position and span instruction to each image, in order to fit the grid. This would probably not be the most effective to display images but i found that it was a good exercise to learn how to use grid. I decided to retain the page. 

- Contact us

  I used a pop up or modal for the contact page. If the user user click contact in the navigation bar, it will bring you to a separate contact-us page. I keep this page to demonstrate both techniques.

- Sponsor and footer

  Sponsor image are greyed out until the user hover over the page, transition to the original colour of the image. If you click on the page it will bring you to the sponsors website in separate tab. The Footer
  page consists of Social media icons with hover effect which transition from a light grey to a dark grey. I used font awesome. 

## Wireframes

I used Balsamiq to build the wireframes of the site. I found the wireframing process useful as it provided me with a visual reference point.

 ![wireframe](/assets/readme-images/wireframe.jpg)

 ## Technical 
 ### Grid and Flexbox
 I used to grid to provide structure to the site and flexbox to control the content of each grid. 

 ### Buttons
 My button when through a number version over the project. On the main page they are divs and in the booking and contact forms I integrated submit buttons. I experimented with images, transitions, colors etc. Iam using three effects on the buttons, drop shadow to give a sense depth , a change and invert of colors, finally a sheen effect. I used a number of sources, including. 

 [w3school](https://www.w3schools.com/css/css3_buttons.asp)

 [codepen](https://codepen.io/dmensinger/pen/PPRzpK)

 [MDN Webdocs](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow)

### Modal (pop-up windows)

To maintain the scrollable single page, I have used a modal's for the booking and contact us form. The modal I am using does not require Javascript. 

![modal](/assets/readme-images/modal.jpg)

I used a number of sources to for the modal's. 

[w3school](https://www.w3schools.com/howto/howto_css_modals.asp)

[getbootstrap](https://getbootstrap.com/docs/4.0/components/modal/)

[codepen](https://codepen.io/timothylong/pen/AJxrPR)

[Kevin Powell](https://www.youtube.com/watch?v=TAB_v6yBXIE)

[codepen](https://codepen.io/peiche/pen/kQwYVJ)


### Effects and Transition

I used and discarded a number of effect during this project, my sources and inspiration come from w3school, MSN Webdocs, CSS-tricks, and movember website itself. 


## Testing 

A lot of my development took place within Chrome Devtools. Devtools allowed me to deconstruct issues and experiment with fixes. The overlay for grid and flexbox gave visual prospective that I found very helpful. I also used background colour as another what of visualizing the layout of the page. 




## Unfixed bugs

## Deployment 

## Credit