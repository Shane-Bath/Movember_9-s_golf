

# MO 9's - 9 HOLE GOLF CHARITY EVENT

[View the live site here](https://shane-bath.github.io/movember-golf-project/)

![Cover image for readme](/assets/readme-images/display.jpg)

## Goals for this project
The site is to promote an annual local charity nine-hole golf event to raise money for the Movember men’s health charity. The Website main purpose is to provide information on the event and to allow individuals to book a place. A promotional website to sell to tickets to a 9 hole golf event to  raise money for Movember.

#  UX

## Site owner objectives

- Promotion of the event. 
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
I have taken inspiration from the Movember charity website and decided to adopt a similar style and tone, because of the association between the two.  There is a strong black and white theme throughout the site. It is a single page scrollable website, with three sections. I have used pop windows (modals) for booking and contact pages. The site is navigable via buttons and links. 

## Structure
The site uses CSS grid and flexbox. Grid provides the main the structure of the site, making use of gird areas to lay out the page. I used flex to control the content within each grid. This was not a straightforward process, and it took a number of versions of the site before I started to feel comfortable with the process. The key for me was when I began to understand how to use flex to control the content within the grid areas.  There are number of examples of this within the site.
### Navigation

![navigation bar](/assets/readme-images/navigation.jpg)

   The Movember moustache image has been incorporated into the navigation bar, clicking the moustache will bring the user back to the home page. TheLogo has been created using the a moustache image and the google font Anton. The navigation bar will be responsive to various screen sizes.

  Each section will have a hover effect.

  ![hover effect navigation bar](/assets/readme-images/nav-style.jpg)

   On smaller devices the Navigation Bar the logo and the navigation bar move to a column structure.

  ![Mobile navigation bar](/assets/readme-images/mobile-nav.jpg)

  The navigation bar and logo went through a few iteration and was a source of a number of issues for me attempting a responsive design. I attempted several styles, including hamburger, with and without java script, drop down menu and a button style. In the end I settled on this simple button style. 
  
### Colours 
  The main colors will be black and white The Navigation bar transitions from white to a grey (#f7f7f7) and border-bottom of dark grey (#808080).
  Sponsors logo will be in grey scale with a hover effect to revert to original colour scheme. 

### Fonts
  Main text will be a google font 'overpass', inspired by the original movember website. Headings, logo text and promotion will be a google font 'Anton' inspired by the original movember website.

### Images
  I have used a few photographs from my personal photographs and a free resource
  [unsplash](https://unsplash.com/s/photos/golf)
  I also used the [Movember moustache](https://ie.movember.com/get-involved/host)  from movember.com resources. 

### Icons
  I have used the font awesome collection for the social media logos and arrows in the side banner. 

### Layout 
  The site will be scrollable from header to footer, the only pages that will be separate will the contact us page and the gallery page. They will be accessible via buttons and navigation within the main body of the site. The user will be able to navigate to each section with the page. 


### Effects
  I have used hover effect to add interactivity and fun. The moustache and logo shake  when hovered over. The sponsor logo will transition from grey to the original colours when hovered over. The social media logo have a hover effect from light to a dark grey.

 ## Pages
### Landing page

![landing page](/assets/readme-images/landing%20page.jpg)

This page consist of text and images, and a side section encouraging user to donate to the Movember organisation. This page will inform the user about the event, direct them book a place. 

### Banner

The banner was created using text, font awesome icon and image. Creating the banner helped me understand flexbox, as I use flex to change the banner in smaller screens, from vertical to horizontal. 

![banner vertical](/assets/readme-images/banner-v.jpg), ![banner horizontal](/assets/readme-images/banner-h.jpg)

There are a number of hover effects, when you hover over the banner, the colors invert. If you hover over the moustache image, it wiggles and expands. If you click on the moustache, it will bring you to the movember website on a new tab.

![banner inverted colors](/assets/readme-images/banner-w.jpg)


### Locations

![locations page](/assets/readme-images/locations.jpg)

This page consists of image and text with a button. In larger screen to the two locations are side by side. They stack on top each other in smaller screens. The button brings the user to a pop-up page booking page (modal). 

### About us, Gallery, Contact and Sponsors 
  Information about the organisation and sponsors of the event
- Gallery 

    A mix of different sizes of images in a grid structure. I  assigned grid position and span instruction to each image, in order to fit the grid. This would probably not be the most effective way to display images but I found that it was a good exercise to learn how to use grid. I decided to retain the page. 

- Contact us

  I used a pop up window or modal for the contact page. If the user user click contact in the navigation bar, it will bring you to a separate contact-us page. I keep this page to demonstrate both techniques.

- Sponsor and footer

  Sponsor's images are greyed out until the user hover over the page, transition to the original colour of the image. If you click on the page it will bring you to the sponsors's websites in a separate tab. The Footer
  page consists of Social media icons with hover effect which transition from a light grey to a dark grey. I used font awesome. 

## Wireframes

I used Balsamiq to build the wireframes of the site. I found the wireframing process useful as it provided me with a visual reference point.

 ![wireframe](/assets/readme-images/wireframe.jpg)

 ## Technical 
 ### Grid and Flexbox
 I grid to provide structure to the site and flexbox to control the content of each grid.  Used the following resources to learn about grid and flexbox.

  - Responsive Web Design with HTML 5 and CSS - Ben Frain
  - [Kevin Powell](https://www.youtube.com/kevinpowell)
  - [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified)
  - [css tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)

 ### Buttons
 My button when through a number of versions over the project. On the main page they are divs and in the booking and contact forms I integrated submit buttons. I experimented with images, transitions, colors etc. Currently there are three effects on the buttons, drop shadow to give a sense depth , a change and invert of colors, finally a sheen effect. I used a number of sources, including. 

 [w3school](https://www.w3schools.com/css/css3_buttons.asp)

 [codepen](https://codepen.io/dmensinger/pen/PPRzpK)

 [MDN Webdocs](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow)

### Modal (pop-up windows)

To maintain the scrollable single page, I have used a modal's for the booking and contact us form. The modal in the page does not require Javascript. 

![modal](/assets/readme-images/modal.jpg)

I used a number of sources to for the modal's. 

[w3school](https://www.w3schools.com/howto/howto_css_modals.asp)

[getbootstrap](https://getbootstrap.com/docs/4.0/components/modal/)

[codepen](https://codepen.io/timothylong/pen/AJxrPR)

[Kevin Powell](https://www.youtube.com/watch?v=TAB_v6yBXIE)

[codepen](https://codepen.io/peiche/pen/kQwYVJ)


### Effects and Transition

I used and discarded a number of effect during this project, my sources and inspiration come from w3school, MSN Webdocs, CSS-tricks, and movember website itself. 


### Media query 

I used media quires for small and medium size screens. The site was completely reconfigured to accommodate small screens. Moved from two column grid to a single column grid.

![iphone](/assets/readme-images/iphone-screen.jpg)

The modal's and forms had to be reduced in sized. 

- Responsive Web Design with HTML 5 and CSS - Ben Frain
- [Kevin Powell](https://www.youtube.com/kevinpowell)
- [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified)
- [CSS-tricks](https://css-tricks.com/a-complete-guide-to-css-media-queries/)

## Tools
- GitHub
- Gitpod
- Devtools
- Photoshop
- W3C Mark-up validator
- W3C Jigsaw validator

### Future

I would like to a payment function to the page. 

## Testing 

A lot of my development took place within Chrome Devtools. Devtools allowed me to deconstruct the issues and experiment with fixes. The Devtools overlay for grid and flexbox gave a visual prospective that I found very helpful. I also used background colour and colour outlines as another way of visualizing the layout of the page. 

I also tested the html and css in the W3C validator. My html code has no error or warnings. 

CSS code has no errors but a number of warning I will discuss below. 

Finally I continued to use the site, to find bugs, change of screen sizes, broken links and image sizing issues. I would make changes in devtool before I would change my CSS or HTML.

### Html and CSS Validation
[W3C Validator](https://validator.w3.org/nu/)
All html pages passed with out errors 

[W3C CSS Validator](https://jigsaw.w3.org/css-validator/)
Passed with no errors.

## Unfixed bugs
In the CSS code I received a number of the same warning "Due to their dynamic nature, CSS variables are currently not statically checked". After researching the issue it appears that it not a really a problem and should have no impacted on the site. 

A warning for using auto in pointer-events, I referred to w3school and MDN webdocs- auto appears to be valid according to documentation. 

## Deployment 

The site was deployed to Github. 
  - Github repository [github](https://github.com/Shane-Bath?tab=repositories)
  - Select movember-golf-project [movember golf](https://github.com/Shane-Bath/movember-golf-project)
  - Settings - pages - source- deploy from branch- main - root - save 
  - Once the main branch has been selected, the page will deploy. 

The live site can be found here: [movember-golf-project](https://shane-bath.github.io/movember-golf-project/)

## Credit

A big thank you to Simen Dehlin for his support and guidance. 

The following is the list of resources I used in this project.
  - HTML & CSS - Jon Duckett
  - Responsive Web Design with HTML 5 and CSS - Ben Frain
  - [Kevin Powell](https://www.youtube.com/kevinpowell)
  - [Web Dev Simplified](https://www.youtube.com/@WebDevSimplified)
  - [w3school](https://www.w3schools.com/)
  - [MDN Web Doc](https://developer.mozilla.org/en-US/)
  - [Stack overflow](https://stackoverflow.com/)
  - [Google fonts](https://fonts.google.com/about)
  - [Font awesome](https://fontawesome.com/)
  - [MDN Web Doc](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
  - [pencode](https://codepen.io/onediv/pen/AWGZEe)
  - [W3cschool](https://www.w3schools.com/html/html_forms.as)
  - [w3school](https://www.w3schools.com/howto/howto_css_modals.asp)
  - [getbootstrap](https://getbootstrap.com/docs/4.0/components/modal/)
  - [codepen](https://codepen.io/timothylong/pen/AJxrPR)
  - [Kevin Powell](https://www.youtube.com/watch?v=TAB_v6yBXIE)
  - [codepen](https://codepen.io/peiche/pen/kQwYVJ)
  - [w3school](https://www.w3schools.com/css/css3_buttons.asp)
  - [codepen](https://codepen.io/dmensinger/pen/PPRzpK)
  - [MDN Webdocs](https://developer.mozilla.org/en-US/docs/Web/CSS/filter-function/drop-shadow)
  - [unsplash](https://unsplash.com/)
  - [balsamiq](https://balsamiq.com/)
  - [balsamiq course](https://www.youtube.com/watch?v=9Pv002d0Kls&list=PLVlyYfbClWxQDCGC-A1FkbGyIxtuIN5IM&index=1)
  - [movember.com](https://ie.movember.com/)
  - [CSS-tricks](https://css-tricks.com/a-complete-guide-to-css-media-queries/)
  - [CSS tricks](https://css-tricks.com/snippets/css/complete-guide-grid/)



  



