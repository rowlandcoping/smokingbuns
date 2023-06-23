# Testing Documentation
([return to README](README.md))

## Contents

### Audit and Validation

[HTML Validation](#html-validation)\
[CSS Validation](#css-validation)\
[Lighthouse Audit](#lighthouse-audit)

### User Story Validation

[Restauranteur User Stories](#restauranteur-user-stories)\
[Customer User Stories](#customer-user-stories)

### Technical Testing

[Error Testing](#error-testing)\
[Manual Testing](#manual-testing)

## Code Validation

### HTML Validation
([back to top](#testing-documentation))

I have completed a final validation of all HTML pages using the [W3C HTML validator](https://validator.w3.org/).\
I found two errors on the 'book.html' page:
 - The empty option element did not have a label for screen-readers.
 - There was a stray end tag for an anchor element on the page.

Both errors were easily rectified; all other pages showed no errors.

### CSS Validation
([back to top](#testing-documentation))

I have completed a final validation of my 'style.css' file using the [W3C CSS validator](https://jigsaw.w3.org/css-validator/).\
No errors were found.

### Lighthouse Audit
([back to top](#testing-documentation))

The Lighthouse audits I initially ran had one common theme, that I needed to add meta-descriptions and reduce image sizes across the board.  The background and footer images in particular were over-sized and needed serious slimming down. On the 'about' and 'menu' page I did not have header elements in correct sequential order.

IMAGES:

I scaled images to more appropriate sizes and compressed anything that wasn't a vector in a .webp format.

META DESCRIPTIONS:

I added meta descriptions to all pages.

HEADERS:

I ensured that header tags were ordered sequentially, without skipping.  This involved a great deal of work adjusting their associated media queries, esepecially on the 'about' page.

RESULTS:

Here are the Lighthouse results following my remedial work:

![image](/assets/images/testing/home-lighthouse.png)
![image](/assets/images/testing/menu-lighthouse.png)
![image](/assets/images/testing/about-lighthouse.png)
![image](/assets/images/testing/book-lighthouse.png)

## User Story Validation

### Restauranteur User Stories
([back to top](#testing-documentation))

*"Grow online presence: The website must be highly compliant and SEO friendly..."*\
Site uses semantic elements throughout, contains appropriate meta elements, clean code and looks great on any device.

*"Drive home brand identity: The website must be consistent with the restaurant's branding..."*\
The site had a very strong and consistent Western theme throughout and showcases the venue and staff.

*"...Allow users quick access to information about what is on the menu"*\
The website's navigation is obvious and not hidden or cluttered, and the menu.html page contains clear and comprehensive menu information.

*"The website needs to be effective at turning customer interest into bookings and revenue"*\
The option to book is part of the menu structure, and thus this call to action appears througout.  The booking page contains all the infomration needed to plan a visit, prominently displayed.

*"Grow social presence: The website needs to provide access to the restaruant's social accounts so that the people can share and the business can grow. It would also be useful to link review sites such as Google, Tripadvisor and Trustpilot."*\
The footer on every page not only contains social links but also contains links to tripadvisor and google for peer review.

*"Create positive engagement... It should be a place which users enjoy visiting and wish to return to, just like the restaurant itself!"*\
The eyecatching logos and fun 'sheriff star' menu backgrounds along with the attractive fonts, eyecatching images and intuitive layout ought to result in people coming to visit the site even when they're not hungry!

### Customer User Stories
([back to top](#testing-documentation))

*"Mobile Functionality: ... They need the site to look just as good on their mobile devices whilst retaining full functionality."*\
The site was build mobile upwards, starting in all cases with a 360px screen width and then adjusting upwards to desktop screen sizes.  This is reflected in some of the design choices - for example to kepe the site clean there are no transitions or features that would not be functional on mobile.

*"Easy to Navigate... Links to various areas of the site should be obvious, responsive and consistent."*\
The navigation is clear and obvious on all device sizes, with additional immidiacy through having no additional widgets to open. The navigation is the core of the site.

*"What do they sell? users... want as much info as they can get online, as fast as they can get it. This includes the menu, which they want to be able to access and read quickly and in full."*\
The main homepage callout immediately details what the restaurant sells, its theme and where it is located.  Navigation is immediate and clear, with the Menu page the first option.

*"Clear branding: This userbase needs to know what is on offer, as well as getting a feel for the theme and style or the restaurant, from the very first page."*\
The homepage styling and callout text provides and immediate overview of the restaruant and what it sells, whilst clearly communicating the theme through styling and fonts. The big picture of a tasty burger gets home what they can expect to eat when they visit!

*"X-factor: The target audience wants, for want of a better word, cool stuff."*\
Although more limited in scope than I would like to implement various CSS effects because of the limitations of mobile, the unique menu visuals, entertaining fonts and eye-catching theming set this website apart from others.

*"Contact Information: As important as the menu, they want to know where this place is, how to get there, and how to book it."*\
This was a trade-off, and in the end a matter of balancing the need to drive bookings against providing more general information.  However the Homepage Callout makes clear where the restaurant is located, which means the call to action to book is on every page via the navigation.  The booking page contains full contact and booking information prominently displayed.

*"Peer review: As a social generation, it is very important what their cohorts think. Our users need validation to help their purchasing decisions, in the form of reviews and testimonials."*\
The Homepage provides immediate validation in the form of positive customer reviews, and the footer contains links to social and review platforms.

*"Venue Information: Very much on a theme, they want to see what the place looks like to make sure it's sufficiently Instagramable."*\
The about section contains appropriate images of the venue food as well as the staff to provide all the information people need.

## Technical Testing

### Error Testing
([back to top](#testing-documentation))

I've documented here the major problems I encourtered during the course of building and testing the site, and the measures I have taken to overcome them.

The website has been tested throughout on Firefox and Chrome, in both Linux and Windows using the responsive mode in developer tools to trigger all the break points up to my full-screen desktop resolution of 1920px. It has also been tested on a Samsung Galaxy S8 in Chrome with a CSS screen width of 360px.

GENERAL:

- Horizontal scrolling issue:
  - There was a small horizontal scroll across all pages. I traced the issue to the footer using web developer tools. One by one I eliminated all the child elements as the cause and found the source of the problem to be a bootstrap row element taking up more than the viewport's width across all screen sizes.  This was fixed by setting the width of the row to 100%.                     

HEADER / FOOTER / HOMEPAGE:

- Background Hover Image not centered in element
  - There were a number of issues centering the background hover image (sheriff star) over the text of the menu options.  This was eventually solved by setting the width of the image to 100% and the height to auto, to keep the aspect ratio.  I foudn that I was then able to adjust the size of the image by setting a fixed height for the parent element.  Final adjustments were made by adjusting the size of the menu text.  All these values are then adjusted according to screen width.

- Callout image positioning:
  - I found that on larger screen sizes the hero image in the callout section focussed on the chips rather than the burger as intented.  This was overcome in 2 ways - firstly by changing the absolute positioning of 0 to the bottom of the element to a percentage, to ensure the image was focussed on the correct area even as the screen size grew.  I also reduced the size of the image so that you could see more of it on larger screen sizes.

- Footer background positioning:
  - I found that the background change on hover wasn't encompassing the whole height of the element.  I fixed this by changing the display property of the container to flex.  I was also then able to justify and align the various icons.

- Footer sizing (part 2):
    - After discussions with my mentor I re-built the footer to stop the images scaling with the screen width to become outsized on larger desktop monitors.  I achived this by setting fixed values for the image height and wrapping the container to the image.  This was unfortunately not compatible with the previous fix. The solution I came upon was expanding the padding for the hover pseudo element until the background took up the desired amount of space.  This is not a solution I'm particularly happy with but I think it may be the best one as long as the footer is built in Bootstrap.

- Footer sizing (part 3):
    - I made a final attempt to have consistancy with the hover image in the footer.  I discovered the image wasn't centred in the anchor element which was causing the problwm, and solved it by settnig the anchor display property to flex and centering the content.  This also meant I could consistently control the padding by setting a height and width for the anchor element, and it didn't break the layout.  I am still unable to centre the anchor within the list element, but on substantial review I'm not sure that's possible with this site layout.

ABOUT PAGE:

- Images overflowing their containing elements:
  - I had a number of issues caused by the main image of each section overflowing its container, which revealed itself as I scaled up the site.  I noticed that it only applied to the lower resolutuion of the images, and so was able to resolve it by setting by fixed sizes for the container.

BOOK PAGE:

- Flex Container not working as expected:
  - On expanding to the landscape break point (where the main axis should have reverted to column) the booking elements remained in rows.  The mistake I made was positioning the form element as the first child of the flexbox container.  By moving the form element outside of the container and ensuring the flex elements were the only children I resolved this.

SUBMISSION PAGE:

- Footer was stranded halfway up the page, relative/absolute positioning did not solve the problem.
  - Setting the body display properties to flex and the footer's top margin to auto solved this.

### Manual Testing
([back to top](#testing-documentation))

I have conducted error:
 - 360px to represent a smaller screen sizes, for which I will use Chrome on Android (Samsung Galaxy S8)
 - 768px to represent larger phones or tables, for which I will use Chorme and Firefox in responsive mode via their respective developer tools.
 - 1200px to represent desktop screen sizes, for which I will use Chorme and Firefox in responsive mode via their respective developer tools.

360px (Chrome on Samsung Galaxy S8)

([return to README](README.md))