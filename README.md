# Smoking Buns

Welcome to the documentation for 'Smoking Buns', a responsive mobile-first website built in HTML and CSS.

## Contents:

### UX Design

[UX - Strategy](#ux---strategy)\
[UX - Scope](#ux---scope)\
[UX - Structure](#ux---structure)\
[UX - Skeleton](#ux---skeleton)\
[UX - Surface](#ux---surface)

### Testing and Deployment

[Testing Documentation](#testing-documentation)\
[Deployment](#deployment)

### Credits and Technical

[Credits](#credits)\
[Technical Information](#technical-information)

## UX - Strategy 
([back to top](#smoking-buns))

### 1) Project Goals

The goal of Smoking Buns is to provide a simple, coherently branded and easy to navigate way for customers to quickly find out 
more information about the restaurant of the same name.  With its strong Western theme and high quality products it is 
targeted at diners in their 20s-30s looking for a memorable dining experience.

### 2) Developer Goals

 - Build portfolio:  But keep in mind that whilst it is important to build a quality, feature-rich offering, superfluous elements should be avoided.
 - Build customer base:  Local business is a small community.  Do a great job here, referrals are inevitable.
 - Use available technologies: Much as it is tempting, avoid re-inventing the wheel.
 - Stay focussed on the brief: The downfall of so many projects.

### 3) Restauranteur - User Story

The business owner, Smoke Brannigan, is a first time restauranteur with a clear vision for his business.  After an initial meeting he has outlined his requirements:

 - Grow online presence: The website must be highly compliant and SEO friendly, to provide as strong an online presence as possible.  
 This is particularly important given the number of real or fake directory sites out there which might potentially steal search rankings.
 - Drive home brand identity: The website must be consistent with the restaurant's branding to enhance the customer experience and help 
 build a memorable brand.  The owner is very proud of the theming inside and wants to showcase it online.
 - Provide menu information:  Allow users quick access to information about what is on the menu.
 - Increase bookings: The website needs to be effective at turning customer interest into bookings and revenue.
 - Grow social presence:  The website needs to provide access to the restaruant's social accounts so that the people can share and the business
 can grow.  It would also be useful to link review sites such as Google, Tripadvisor and Trustpilot.
 - Create positive engagement:  Representing a restaurant that prides itself in how the venue itself is part of the experience, the website needs to reflect this.
 It should be a place which users enjoy visiting and wish to return to, just like the restaurant itself!

 ### 4) Customer - User Story

The customer base will be people looking for a unique, high quality dining experience. It is anticipated that users of the website will have found it
 either through google or searching a review platform (particularly that on Google Maps), with the intention of dining out. As such their requirements are clear:

  - Mobile Functionality: The majority of users will be accessing the website on the go, either actively seeking a 
  restautant table in the immediate future or looking a day or two ahead. Indeed, many users in their 20s will 
  not own any device other than a mobile or tablet. They need the site to look just as good on their mobile devices whilst retaining full functionality.
  - Easy to Navigate: Millennials and Gen Z are all about immediacy, and they want to be able to find information quickly. Links to various areas of the site should be obvious, responsive and consistent.
  - What do they sell? Because it is likely users will be looking at multiple restaurants, they want as much information as they can get online, as fast as they can get it.  This includes the menu, which they want to be able to access and read quickly and in full.
  - Clear branding: As with any site, the purpose needs to be immediately apparent. This userbase needs to know what is on offer, as well as getting a feel for the theme and style or the restaurant, from the very first page.
  - X-factor: The target audience wants, for want of a better word, cool stuff. They are interested in fancy lighting, interesting gadgets, unusual effects. They would like a bit of pizzaz.
  - Contact Information: As important as the menu, they want to know where this place is, how to get there, and how to book it. Our user base does not want to mess around.
  - Peer review: As a social generation, it is very important what their cohorts think. Our users need validation to help their purchasing decisions, in the form of reviews and testimonials.
  - Venue Information:  Very much on a theme, they want to see what the place looks like to make sure it's sufficiently Instagramable.

  I think it should be clear from the above that many of the Business and Customer interests are aligned. 
  This will make identifying essential elements for the website relatively straightforward.

## UX - Scope
([back to top](#smoking-buns))

### Core Elements

Whilst brand and theming are obviously key to the success of the project, the overriding take-away from the user stories is the importance of immediacy. This is not a complicated project, so it needs to deliver core areas first, and with that in mind:

 - Static HTML and CSS page.  Firstly as a constraint of this project but even so I would suggest it because of load times on mobile and the nature of the project. It doesn't require anything more.
 - Bootstrap: I am in two minds about Bootstrap, as whilst it eases building out a site structure it can also cause complications with a bespoke site like this one. Ultimately I think it is worth using, mainly because it is built to be mobile compliant; the idiosyncracies of building a site for mobile cannot be overestimated! Any inconveniences or constraints would compromise elements beyond the core of the site, and therefore constitute an acceptable risk. 
 - Whilst it is tempting (and not impossible even given this constraint) to do something fancy on the homepage, the navigation menu should be clear, obvious and consistently sited throughout the website, most likely as part of a header element.  As a web designer it hurts to say this, because I'd love to build something unique and shiny (see additional elements).
 - Clear call to action in order to book, linking to a seperate booking/contact page. I believe it is worth including this call to action on every page and possibly in the menu, but this is something to be explored elsewhere!
 - The full restaurant menu needs to be somewhere on the site, boldly but clearly laid out.  Again I think it's wise to keep this simple and in keeping with the brand. There may be room to have some fun with it (for users as well) as the project develops.
 - There needs to be some section of a page or the site where there is peer review, be it links to review platforms or personal testimonials. This has come up as both key to the user base and as a factor for the owner in building brand awareness.
 - Restaurant overview:  On the homepage, ideally in a callout, people need to know what the restaruant is and what it sells. This will provide immediacy.
 - Restaurant information:  This can consist of a gallery, or series of images, showing the theming clearly and what the place is like in order to establish brand as well as showcasing the restaurant theme.
 - Social platforms need to be linked to the website, I would suggest most likely in the footer, but also on the contact page. Thought needs to be given to how prominent we make this element.
 - 404 page.

 ### Additional elements

 These aspects of the site are subject to time and technical constraints.  I think each one of these would 
 add value, and would like to incorporate them all if at all possible.

- With load times on mobile in mind I am of a mind to reduce dependencies as much as possible - so for example importing fonts, icons and libraries into the site structure rather than relying on a CDN.  For the site owner it also reduces risk of new versions of libraries etc deprecating and ultimately invalidating existing code. When it comes to bootstrap in particular I will need to further my knowledge before attempting this!
- More elaborate menu links (as part of a homepage callout): I have several design ideas as to what this might look like and the type of transitions or css tricks that might make it happen.  Whilst it is not an essential element  I think it would add the interactivity and pizzaz that the target demographic craves, and help re-inforce the restaurant's brand identity.
- More interactive menu elements: whilst not essential to get the core message across, adding another layer of engagement to the menu and focring users to linger there might well lead to the dwell time to pick out a favourite and decide they're going to eat it.

### Future improvements

These elements are beyond the scope of this project, but I would definitely like to include them were this a live site

- Active contact form:  This would be a simple matter.
- Online booking system:  Absolutely essential element of any modern restaurant site, either imported from a widget or built ground-up.
- Customer registration / rewards system:  Can track customer visits, offer things like loyalty rewards, birthday specials, generic offers, etc.

## UX - Structure 
([back to top](#smoking-buns))

### Header and Navigation (Core)

 - Given how key mobile compliance and responsiveness will be, the navigation will consist of a single 
layer menu, with every page on the site available through a single tap or click.
 - Menu elements will appear consistently at the top of the screen, along with the corporate logo.  There are multiple design possiblities for this, and in all likelihood I will produce more than one version - either the logo appearing above the menu and the menu at the top left, or as is conventional the logo at the top left and the menu at the top right, or vice versa.  The reason I am leaning towards the first option is I want to build a mobile first website.  All user stories converge on the importance of navigation being immediately avaliable.  Having an additional menubar to open would counteract this, and to be honest is a personal bug-bear of mine. With only 4 menu options there is no reason not to display them all on any size of screen. Positioning the logo above them would enable them to be made more prominent and accessible. This could of course be adjusted for larger screen 
 sizes but mobile considerations have to come first.
 - On hover/active menu buttons will show some form of transition to add interactivity and positive user feel.  This needs to be in keeping with the theme of the restaurant.

 ### Header and Navigation (Additional)

 - There is potential to include additional links to core site areas (menu, restaurant, contact) on the homepage with heightened interactivity.  This would take the form of either an old school shooting gallery with rotating images or bullet holes in a wooden wall, using CSS transitions. Edited:  as this would be desktop only and this site is mobile led it is unlikely this will be happening. Less elaborate options may need to be reverted to (not so much technically, but because these options may be reliant on audio to actually be any good.)
 - The mouse pointer could change to a cross-hair on mousing over these elements (or indeed the permanent navigation elements). Edited -  This would not work on mobile, which would lead to inconsistent experiences.

 ### Footer (core)

 - Social media icons
 - Call to action (book here)
 - Any legal schtick

 NB: As the project developed it became clear the footer needed to be kept as simple as possible, and would be the main site to access social sites.  As such the other elements were either moved elsewhere or (in the case of legal information) omitted altogether.

 ### Homepage (core)

 - Reastaurant elevator pitch and description - The main callout has to first and foremost let everyone know what the site is about.
 - Main background image - In keeping with restaurant theming, without compromising readability or visual integrity.  This may require some trial and error.
 - Testimonials or selected online reviews:  peer review seen as crucial in adding value at the outset.

 ### Homepage (additional)

 - Fancy navigation elements outlining different key areas of the site (see navigation).  My big question mark is whether there is room for this. Even though it's a nice to have, it may just end up pushing far too much below the fold on a mobile device to the point where it is detrimental. I do not want to put anything on the desktop site that is not on the mobile site.

 ### Menu (core)

 - Information about what is on the menu, themed.
 - The food menu must be easily digestible, but it can't take up too much space either.  People don't want to be scrolling down forever to find out what's for pudding, or transitioning through multiple pages.

 ### Menu (additional)

 - Active / Mouse-over (on desktop) transitions.  The vision is to have some kind of image of a cowboy making suitably cowboyish comments on the indicated menu item.  This is technically easy enough, but the menu might not be the best place for it.

 ### Our Restaurant (core)

 - Some images of different areas of the restaruant, showing the theming.  3 maximum with descriptions, or a gallery. Given the lack of appropriate collateral, less is probably more.

 ### Our Restaurant (additional)
 - This may actually be a better place for the talking cowboy head concept.
 Edited to add: Representations of various members of the team is the design concept I decided on - how it is represented will be dependent on the image work.

 ### Contact (core)

 - A contact form for bookings is the most prominent part of this page, and the 'book here' button will link here.
 - Add tripadvisor etc links to this page, along with the address.  

 NB it was ultimately decided that, with the tripadvisor and google links appearing everywhere in the footer there was no need to duplicate this information.

 ### Contact (additional)

 - Could add a Google Map widget, or failing that I like the idea of a map drawn in the western style.  My imagework may or may not be up to that!
 - May be worth adding the social links again, but it should not be necessary because I expect them to be very prominent in the footer.

 ## UX - Skeleton
 ([back to top](#smoking-buns))

 ### Design Choices

  - This is imagined as a site predominently used on mobile and will be programmed with Bootstrap with that in mind, therefore I began with the mobile layout and scaled from there.
  - I have attempted to keep the layout as consistent as possible with some amends for the landscape format of most desktop devices, keeping in mind people may well access the site on multiple devices and familiarity is important.
  - In line with the gathered requirements, the menu is prominent on the screen and visible at all times; nothing is hidden behind sub-menus or drop-downs.
  - I have kept the content of each page very simple and precisely on point with the menu descriptions.  The only doubt is the 'about' section which for me doesn't describe the content well enough.  Unfortunately longer alternatives may break the layout.
  - Main content layout on each page is consistent with no more than two vertical sections.
  - The homepage is kept the simplest of all; as the landing point it is intended to provide instant value with clear descriptions of what the site is about, re-inforced by the visual style and independent reviews.
  - I have re-named the contact button 'book'. This means the main call to action tops every page and does not need to be placed elsewhere. Likewise the first thing on that page will be a form to book a table.  
  - As identifying the restaruant location could be considered important information, this should be included in the callout considering the 'contact' section is a call to action to book. Likewise it may be worth including the address beneath the social and review links in the footer.
  - In order to retain clarity of content for each page, I have decided it would be best to include links to tripadvisor etc in the footer.  This is possible with the call to action in the header and groups well with the social links.
  - I chose 4 sections in the 'about restaurant' section to ensure balance on larger screens where they may be displayed side-by-side (Bootstrap XXL).
  - All the pages are designed so that the main information the page needs to get across is displayed above the fold.
  - As I developed the site, I discovered that different CSS methods would suit the various page layouts I proposed in my wireframes.  As such I used the following:
      - Bootstrap for the Header, Footer and Homepage.
      - Grid for the 'Menu' Page content (very structured content)
      - Flexbox for the 'About' and 'Book' pages. (I discovered that using nested flexboxes and changing the axis made for great responsiveness.)
  - Booking form button - In a full deployment I would use a POST method to process the form using PhP, Javascript or such like, then write the contents to a relational database (potentially integrated with an online booking system). Keeping in mind the limited scope of this project, for the purposes of this deployment I have used a GET method to ensure the form will not work unless filled out correctly.  The page the values are passed to does nothing to process them, but it does link to a static page with a success message and route back to the homepage.  Keep in mind that this is not a secure solution, and therefore do not enter any sensitive data through the 'Book' page on this website.  Please note that this page does not feature in the wireframes because it was not conceived of until later in the project's development cycle.

### Wireframes

Please find the wireframes [HERE](WIREFRAMES.md).

## UX - Surface
([back to top](#smoking-buns))

### Color Palate

Because most of the backgrounds consist of images there is a very limied color palate on the site, outlined below:

#48290A (dark brown):  Background transparencies, text and spacers.\
#fff (white): Text, logos and spacers.\
#000 (black): Text.\
silver: borders / dividers.

### Color - backgrounds

The color scheme is intended to be evocative of the Wild West. For me the idea of a wood background began with the header but made sense as a background for the page from both a design and technical standpoint. I made sure it was a dark brown and actually darkened the wallpaper image I initially downloaded using GIMP to ensure legiblity of text and to ensure the look and feel was as I intended.  The general style of all pages is intended to invoke either text embossed in a wooden frame or messages pinned to a noticeboard- hence the cream colored old-style parchment which works excellently with the dark brown.  The transparency is intended to help readability of other sections of the site.  The footer uses a white transparency to differentiate itself from the main sections.

### Text and Fonts

To keep things simple and readable I opted for white text against the dark brown background.  This is inverted to black text upon the various noticeboard sections.

The main font was chosen for its legibility above some of the alternatives.  It is intended to represent a classic Western Style script and to be instantly recognisable as such.  The title font is a more eloborate extension of the theme - because of the larger font size using a more intricate font does not affect its legibility and I think adds greatly to the look and feel.  All fonts are stored locally with future-proofing in mind.  Additionally I feel like using fonts outside of Google significantly increased my options.

### Images

The various images used are influenced by there being little collateral for the (fictional) venue.  The logos either side of the title and the smoking gun spacer were built in Inkscape, using various sources as inspiration.  I chose to use vector images where possible because of how easily and cleanly they scale to different screen sizes without loss of resolution. 

I felt the main stock image had to represent the product, and whilst the look and feel of the site gets the theme across thoughout, in the end it would be nothing without a tasty burger.  I re-used this image for the about section. I wanted to get across all aspects of the restaurant and give it some real personality in this section, hence the theme of introducing various members of staff and presenting the information as a quote from them.  Of the other images on this page, the various portraits, images and text are mostly placeholders but I think also get across very well how it is intended to be a fun venue.  I kept the menu page as simple as possible, as this page is simply about providing information as clearly as possible.  

Initially the footer logos were based on the color schemes of the various brands;  I scaled this back to black and white in keeping with the mouse-over effects and the general look and feel of the site.

### Navigation/Effects

I immediately settled on a sheriff star to act as a visual indicator of a state change on the menu - the gold star indicates a hover/active state and the silver star indicates the current page.  I believe this gives tremendous clarity of what is going on for the user, and adds to the overall theme as well as adding value to the page.

Within the footer I opted for a white background in an active/hover state, to provie a contrast to both the black icons and the background wood effect/transparency.

I have not added any CSS transitions or effects, for the main reason that I don't believe they would add a lot of value to the target audience, ie users on mobile devices with smaller screens. I also think the look and feel of the site has a strong enough identity already.

### Responsiveness

In addition to basic Bootstrap classes, I relied heavily upon media queries to hone page design and layout as the website scaled to different screen sizes. Given that the venerable Samsung Galaxy S8 has a CSS screen width of 360 pixels, In order to be safe I designed the site with page sizes from 320px to 1800px in mind.  

Generally speaking as the pages scaled up, I increased margins and padding, and increased font and image sizes to maintain optimal look and feel.  On desktop I used Bootstrap to change the position of content on the page.  The Header and Footer were also structured using Bootstrap.  I used Flexbox to adjust the desktop layout for the 'About' and 'Book' pages.

NB: On reviewing the requirements and how the site scaled up I decided to add additional media queries at 2500px, 3200px and 3840px in order to support HD displays. I do not have access to an HD display on which to test this thoroughly but it looks a lot in various developer tools.

## Testing Documentation
([back to top](#smoking-buns))

Please find all testing documentation [HERE](TESTING.md).

## Deployment
([back to top](#smoking-buns))

### Initial Deployment

The website has been deployed [HERE](https://rowlandcoping.github.io/smokingbuns/) via github pages, using the method below:

- I logged in to my github account.
- I opened the Smoking Buns repository.
- From within the repository I selected 'Settings'
- From the settings page I selected 'Pages' from the 'Code and automation' section of the left menu.
- I selected 'deploy from a branch' from the 'source menu' and then select the 'main' branch of the repository, along with 'root' as the folder.
- On pressing 'Save' the site deployed.

### Deployment Instructions

If you wish to deploy this website yourself, here is how to go about it.

1:  Using github pages

- Log in to or create your own github account [HERE](https://github.com/).
- Go to the Smoking Buns repository [HERE](https://github.com/rowlandcoping/smokingbuns) and select 'Fork' to create your own snapshot of the repository.
- From the forked repository select 'Settings'
- From the settings page select 'Pages' from the 'Code and automation' section of the left menu.
- Select 'deploy from a branch' from the 'source menu' and then select the 'main' branch of the forked repo, along with 'root' as the folder.
- Press save.  The site will now be deployed from your own forked repository!

2:  Using source files

Because this website is built using nothing but html and css you can deploy it in any web browser from local files.

- Go to the Smoking Buns repository [HERE](https://github.com/rowlandcoping/smokingbuns) 
- Download all the files in the repository except for the '.devcontainer' folder and the '.gitignore' file to a folder on your local machine.
- In your local folder, right click the 'index.html', select 'Open With' and then select any web browser.

NB If you wish you could also deploy these files by copying and pasting them to the 'www' folder of your own web host, but keep in mind that the method of deployment will vary depending on the web hosting package you use.

NNB If you are using a Linux operating system running Apache you can simply save the files in your local '/var/www/html' folder and deploy by typing 'localhost' into a browser window. Please see instructions for installing Apache [HERE](https://ubuntu.com/tutorials/install-and-configure-apache#1-overview) if you haven't already.

THE 404 PAGE:

On Github the server is pre-configured to display a 404.html page whenever a page is not found, but that may not be the case in all deployments.  Depending on the server you are deploying from, there are a number of steps you may need to take.  In Apache, one way is using an .htaccess file, however it is preferable where possible to directly configure the server.  In most cases this is straightforward; I have sourced guides below to the more popular servers:
  - Click [HERE](https://www.msnoob.com/how-to-redirect-404-error-page-to-another-url-in-iis-server.html) for Microsoft IIS Server.
  - Click [HERE](https://www.ionos.com/digitalguide/server/configuration/configure-apache-to-use-custom-error-pages/) for Apache servers.
  - Click [HERE](https://www.cyberciti.biz/faq/howto-nginx-customizing-404-403-error-page/) for NGINX servers.

### Continuing This Project

If you are a developer and wish to extend this project further, there are a number of development environments I have used, which I have outlined below.  All suggestings make the assumption you have already forked the github repository as outlined above, and don't have access to any paid-for IDEs:

1: Text Editor

The simplest method is to use a basic text editor.  I use notepad++ on Windows or Geany on Linux, but even something as simple as Windows Notepad will do.

 - Download all files from your forked repository except for the '.devcontainer' folder and the '.gitignore' file to a folder on your local machine.
 - Right click the file you wish to edit, select 'Open With' and then select your text editor of choice.

 2: Github Codespaces and VS Code, Windows

 I have used VS Code throughout, either via Codespaces or directly.  The easiest way to edit the code is by creating a codespace in Github, which will provide you with a limited number of hours of development time free of charge.  To create a codespace in VS Code for your forked repository:
 
  - Download VS Code [HERE](https://code.visualstudio.com/download)
  - Follow the instructions linked [HERE](https://docs.github.com/en/codespaces/developing-in-codespaces/using-github-codespaces-in-visual-studio-code)

 Please note when using this method I found some issues connecting to the codespace in VS Code once it had been created due to the template I have used.  To counteract this you can manually select the workspace in VS code using /workspaces/--name of workspace--

 3: VS Code on Linux using local files

 I have found this to be the best solution by far, on account of not being beholden to any limitations on minutes or such like, and the files being stored locally which means the project could be worked on more or less under any circumstances (barring catastrophic failure of my own machine).  Even in this scenario I recommed regular commits to mitigate against the worst case scenario.  I set up my development environment on Linux using the guide [HERE](https://www.theodinproject.com/).

  - Create an account at The Odin Project.
  - Navigate to 'Installation Guides' at the bottom of the page.
  - When it guides you on how to download the repo locally, be sure to clone the forked repository of Smoking Buns.
  - Once you have followed the guide you will have your own local development environment!

## Credits
([back to top](#smoking-buns))

Please see below for sources, inspirations and any other credits for the creative and technical work on this website:

### Fonts

Both fonts downloaded from Fontspace:
- [Carnivale Freakshow](https://www.fontspace.com/carnivalee-freakshow-font-f5278)
- [Maiden Orange](https://www.fontspace.com/maiden-orange-font-f11465)

### Main Logo

The Smoking Buns logo was created from scratch using Inkscape, but drew heavy inspiration from multiple sources:
- [Pistol](https://www.dreamstime.com/western-pistol-revolver-vector-illustration-western-pistol-revolver-vector-illustration-detailed-monochrome-style-image201452854#_)
- [Burger bun](https://www.alamy.com/burger-vector-icon-fast-food-sign-graph-symbol-for-cooking-web-site-and-apps-design-logo-app-ui-image398212071.html)
- [Smoke](https://www.shutterstock.com/image-vector/steam-vector-symbol-on-white-600w-1554375650.jpg)

### Menu 'Sheriff Star' background

This image was created using Inkscape, but the design for a Sheriff badge seems to be universal:
- [Sheriff Badge array](https://www.google.com/search?q=sheriff+badge&tbm=isch&ved=2ahUKEwig4I_9hNP_AhUunCcCHd1vAH4Q2-cCegQIABAA&oq=sheriff+badge&gs_lcp=CgNpbWcQAzIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQ6BwgAEIoFEEM6BAgAEAM6CAgAEIAEELEDOggIABCxAxCDAToKCAAQigUQsQMQQzoLCAAQgAQQsQMQgwFQAFjME2D0FWgAcAB4AIABYIgBmAmSAQIxM5gBAKABAaoBC2d3cy13aXotaW1nwAEB&sclient=img&ei=MDuSZKCIC664nsEP3d-B8Ac&bih=782&biw=1501&client=firefox-b-d)

### Hero Image

This image (also used in the 'About Our Food' section) was found on rawpixel - the image was itself taken from Wikimedia commons which attributes it to Unsplash (originally published before 05/06/17 and therefore not licensable).
- [Hero Image](https://www.rawpixel.com/image/3286349/free-photo-image-burger-french-fries-food)

### Main Background

The wood background is derived from the following Shutterstock image - I compressed it significantly for web use and darkened it in GIMP.
- [Wood background](https://image.shutterstock.com/image-photo/old-wood-texture-background-wooden-260nw-1405830665.jpg)

### About Page

This page contains multiple images that whilst not licensed for use on Smoking Buns are in the public domain.  Of course were this a commercial site I wouldn't use any of them; they are there at present to add completeness and colour.
- [Clint Eastwood](https://www.google.com/imgres?imgurl=https%3A%2F%2Fm.media-amazon.com%2Fimages%2FM%2FMV5BMTc1ODA2MzQyNV5BMl5BanBnXkFtZTcwODQ5MjkzNA%40%40._V1_.jpg&tbnid=cfR8oA2Z00bSiM&vet=12ahUKEwjKtJHfgtP_AhXDsEwKHStwD0oQMygAegUIARCUAQ..i&imgrefurl=https%3A%2F%2Fwww.imdb.com%2Ftitle%2Ftt0061747%2F&docid=wkGvtJr-oClWIM&w=804&h=1023&q=clint%20eastwood%20hang%20em%20high&client=firefox-b-d&ved=2ahUKEwjKtJHfgtP_AhXDsEwKHStwD0oQMygAegUIARCUAQ) image copyright Metro-Goldwyn-Mayer Studios Inc, found on IMDB.
- [Jamie Oliver](https://i.guim.co.uk/img/media/5a5250cd6c465b13d9f6fa6766f037aedee0abd0/0_0_1382_922/master/1382.jpg?width=620&quality=85&dpr=1&s=none) image found on the Guardian website, courtesy of Ella Miller/jamieoliver.com.
- [Barbara Windsor](https://i2-prod.mirror.co.uk/incoming/article22393553.ece/ALTERNATES/s1200d/0_MAIN-Barbara-Windsor.jpg) image was found on the Mirror website, courtesy of the PA/bbc.
- The Restaurant image is a screengrab taken from the video game 'Red Dead Redemption 2' by Rockstar Games.
- The [staff image](https://dl6pgk4f88hky.cloudfront.net/2021/09/peggy2-1038x778.jpg) is taken from a New Statesman online tribute to the late Barbara Windsor.

### Logos

I have listed the sources for the logos in the footer below.  They are not as downloaded; all logos listed were amended to ensure they were the same shade of black and to replace any internal transparencies with a white background.  The Tripadvisor and Google logo backgrounds were amended so that both logos are the same size.  All this imagework was undertaken using GIMP.
- [Facebook](https://www.clipartmax.com/download/m2i8A0m2m2N4i8b1_facebook-icon-facebook-logo-black-vector/) - clipartmax.com
- [Instagram](https://www.pngegg.com/en/png-kzypz/) - pngegg.com
- [Snapchat](https://pngtree.com/freepng/snapchat-icon_3584910.html) - pngtree.com
- [Tripadvisor](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRfMgn4ae09WcEjCXwyPaZ7zH_M_6p-AIi_AQ&usqp=CAU) - found on the Rock and Sole Place website.
- [Google](https://commons.wikimedia.org/wiki/File:Transparent_google_logo_2015.png) found on wikimedia commons.

### Code (book.html)

I used [this guide](https://webdesign.tutsplus.com/tutorials/building-responsive-forms-with-flexbox--cms-26767) when creating the booking form, in order to help with media break points and text alignment for the form list elements.  Although the majority of my code on this page doesn't come from the guide, it provided a good foundation for me to build around.

### Advice

Many thanks to my mentor Mitko Bachvarov for all the help and advice he has offered, including:

- advising on the proper syntax for git commits.
- suggesting CSS methods that might be appropriate for certain pages based on my wireframes.
- suggesting the elegent solution for form submission on a static site.
- advising on the footer look and feel.
- advising on the correct testing format.
- noticing the horizontal scroll issue (I thought it was a product of web developer tools!)
- answering all my questions no matter how stupid they were!

## Technical Information
([back to top](#smoking-buns))

Version Control: Git and Github\
Languages: HTML and CSS\
Libraries: Bootstrap 5.3.0\
Development Environment: VS Code on Windows and Linux\
Wireframes: Balsamiq\
Image Creation: Inkscape\
Image Editing: GIMP




