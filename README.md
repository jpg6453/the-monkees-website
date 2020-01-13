# The Monkees Website

I have been asked by the band’s representatives to build a static (front-end only) website because they feel that the band’s current site is tired and out of date.  The site has a homepage with image carousel, music section which announces the latest release with sample tracks, a video section showing the band in their heyday and a tour section detailing up and coming tour dates and a link to purchase tickets.

The about page contains a short bio of each band member and the photos page shows a gallery with photos of the band spanning a 50 year career.

The book us page contains a simple form for fans to fill in and book the band for an event. This is a key business goal of the site.




## UX

The 2 user groups the site is targeting are fans and potential fans and the main goals they are trying to achieve when visiting the site are:

-	listen and watch clips from the band's back catalogue
-	discover new material when it's released

Business goals of the site are as follows:

- showcase back catalogue 
- announce new material
- link to Spotify Platform
- announce tour details and facilitate ticket purchase
- take event bookings 
- grow social media following

The website is the best solution for users to achieve their goals because:

-   Guides them to complete goals - consume content and fill in the contact form
-	the UX of the existing site is poor with users having to hunt for information and read lots of text
-	Follows conventions from other music industry sites
-	Easy to navigate
-	Well laid out and easy to read
-	Content is exciting and well presented
	

The overall colour theme for the site is dark grey contrasting with light grey to demark sections. This simple colour scheme was selected to create a yester-year feel (the 1960’s) and also because it allows the content to take centre stage.


### HOME PAGE

#### Navbar 

A fixed navbar was implemented so that when user scrolls down navigation elements remain on view. Logo conventially located top left which brands the site. Dark navbar was selected with nav elements subtly becoming lighter on hover. The “Book Us” link is highlighted using the bootstrap secondary class so that it stands out from the other elements. This is a key goal of the site to guide users to navigate to the contact form and fill out the form to make an enquiry.

#### Footer

This is free of clutter and contains 3 social media icons which link users to the relevant sites. There is a subtle hover effect which feeds back to the user which social site they are about to select should they wish to confirm with a click.

#### Carousel

The band image was selected as it shows them performing in their heyday, sparking nostalgia in long standing fans and attracting interest from newer/potential fans. The secondary slide image of Peter Tork is in colour by way of a contrast. This serves as a fitting tribute to Peter who sadly passed away recently. The carousel cycles automatically on loading. Manual directional arrows have not been included. It dominates the viewport to immerse the user and leave them in no doubt they are at the home of all things Monkees.

#### Listen

This section uses an iTunes style execution, with the large album artwork image and 4 sample audio tracks that the user can play natively in the browser. There is also a clickable link to the Monkees entire back catalogue on spotify. Key goal of site is to be able to discover and play audio content.

#### Watch

This section is very clean and the embedded video features one of the bands biggest hits. It is very easy for users to achieve the goal of seeing a clip of the band.

#### Tour Section

This section is clearly laid out and has a prominent clickable “Get Tickets” button which takes users to an external site in a new tab to browse for and purchase tickets.

### ABOUT PAGE

Speaker background image selected as a nod to music industry. Page title and card backgrounds have a dark effect applied so that the white text pops off the background. Not content heavy. Combination of images and very short bios so as to not overload users.

#### Photos Page

Subtle background image selected inspired by mac screen saver to allow the content to take centre stage. The photos are presented as a gallery grid which follows convention. The page title has dark effect applied so the title pops off the background.

#### Book Us

Background image selected to convey live performance/party vibe. Contact form centrally located with a contrasting send call to action “send” button to help users achieve their goal easily. Each field of the form has a label and placeholder text to guide users to make accurate inputs and the application of validation ensures correct inputs.

#### User Stories

1. As a fan, I would like to browse for songs, so that I can play my favourites.

2. As a fan, I would like to watch videos, so that I can see the band perform.

3. As a potential fan, I would like to browse for songs, so that I can listen to their back catalogue.
4. As a potential fan, I would like to learn more about the band, so that I can find out about them as people.

5. As a potential customer, I would like to send in an event request, so that i can book them for a birthday party.

6. As a live music lover, I would like to find a list of tour dates, so that I can see them in concert.

7. As a visitor to the site, I would like to navigate easily, so that I can move around the site and find what I need.

8. As a fan, I would like to browse photos of the band


## Features


### Navigation

There is a fixed navbar at the top of every page which has the band logo conventionally located in the top left hand corner. This serves as brand recognition for users to confirm that they have landed on the band's website and also takes users back to the home page when clicked. On the right hand side there are links to other pages/sections of the site. The "Book Us" link to the far right is highlighted to draw users' attention to it. It takes the user to a contact form to fill out in order to book the band for an event. This is one of the main goals of the site.

### Footer

There is a footer on every page which contains social media links to the band’s Facebook, Twitter and Youtube pages and allows users to access additional content. All these links open in a new tab.

### Homepage

#### Carousel

At the top of the homepage there is an image carousel which cycles through two image slides. On landing on the website, a black and white image of the band from their heyday is displayed. The alternate image is in colour, to contrast with the band image, and features an image of one of the founding members, Peter Tork as a tribute following his recent death. The carousel is full width and covers the full viewport height on desktop, but only occupies the top half of the screen on tablets and mobile devices.

#### Music Section

This section is in two columns. On the left there is a large image of the artwork from the band's latest release with explanatory notes. On the right side there are 4 sample tracks which can be played natively using the browser's default media player and a link to the band's back catalogue on Spotify. On mobile the right hand column wraps under the left column, placing the album artwork at the top of this section.

#### Video Section

The video section is also in 2 columns. To the left is a section heading and sub-heading and on the right side there is an embedded video with controls. This has auto-play turned off. Again, on mobile the right hand column wraps underneath the left so the video will be placed at the bottom of this section in this view.

#### Tour Section

This section is a single column sized for different devices. It has a heading/sub-heading at the top with a tour poster image displaying the tour dates and locations. There is a "Get Tickets" button underneath using bootstraps primary class to make it stand out from the background. When clicked the user is taken to the Ticketmaster website in a new tab where they can purchase tickets.

#### About Page

This page utilises bootstrap's "cards" class and presents 4 cards in a single row, each occupying a quarter of the screen width on desktop. There is a card for each band member with a headshot image at the top, name and short bio. The cards are arranged 2x2 on tablets and appear as a single scrolling column on mobile devices.

#### Photos Page

The images in the photos gallery are presented as a 3 x 3 grid on larger screens, which moves to 2 columns on tablets and a single column on mobile. When an image is clicked the fancybox modal is activated which allows the user to cycle through the images using forward and back controls in a lightbox slide show which is very similar to Apples cover flow view for browsing content.

#### Book Us Page

This page presents a simple contact form which enables users to fill it out and submit a request for the band to play at an event they are planning. It is a single central column which is simply re-sized to fit different screen sizes. Each field of the form has a label and placeholder text to guide the user. All fields are required and validation has been added to the phone number and email fields. The send button uses bootstrap's primary class so it stands out and allows the user to achieve their goal of submitting the form.

## Existing Features

- **Navigation bar** – features on every page and enables users to navigate easily to all pages/sections of the site. Fixed at the top so is visible when scrolling down.

- **Brand logo** – present to the left side of the navbar on all pages. Provides branding for the site and takes users to the home page when clicked.

- **Book Us** call to action button – located to the right within in navbar on all pages. This is highlighted to make it stand out from other navbar elements and takes users to the contact form.
- **Footer social icons** – located on every page and allows users to access the 3 social media platforms maintained by the band.

- **Carousel** – Showcases the band performing in their’ heyday, with a second image providing a tribute to one of the band members who passed away recently.

- **Listen Section** – contains sample audio tracks and enables users to play them natively and a link to Spotify to access the band’s back catalogue.

- **Watch Section** – The embedded video enables users to watch the band perform one of their greatest hits.

- **Tour Section** – Allows fans to look up tour dates and provides a link to ticketmaster where they can buy tickets.

- **About Page** – Enables all visitors to the site to learn a little bit about each band member.

- **Photos Page** – Enables all visitors to view large thumbnails of key moments in the band’s history.

- **Fancybox “lightbox”** – Enables visitors to the photos page to click on the image thumbnails and view an enlarged image and then move through them with forward/back controls. There is also a control to play as a slideshow and an option to return to the gallery.

- **Book Us Page** – Enables users who wish to make an enquiry to book the band for an event to fill in a contact form and submit their details.


## Features for the future

- iTunes Store style media player – A cleaner execution that doesn’t rely on the default media player within the browser. A progress bar would appear when a track listing is clicked. JS required.

- Expanded video section – Youtube feed

- Social media feeds  

- Members area – sign up to enable users to leave comments

- Add a Captcha to contact form to eliminate spam

- Investigate and implement how to push down content from behind fixed navbar when navigating homepage sections using navbar links. Section headings are currently hidden by navbar.

## Technologies Used

**Chosen IDE**  - [Cloud9](https://aws.amazon.com/cloud9/)

**Programming languages** – HTML & CSS

### Libraries

[BootstrapCDN](https://www.bootstrapcdn.com)

The website was built following mobile first principles and utilises Bootstrap4 to make all elements responsive across different screen sizes. 

Icons obtained from [Fontawesome](https://www.bootstrapcdn.com/fontawesome/). 

[jQuery](https://jquery.com)

This was used to pull in the necessary Javascript for the responsive navbar and Fancybox image “lightbox” modal. 

[Popper.js](https://popper.js.org)

This library is required for the responsive navbar to function correctly. 

[Fancybox](https://fancyapps.com/fancybox/3/)

This was used on the photos page to enable users to view images as a Mac-style "lightbox", a modal that floats above the webpage. 

[Google Fonts](https://fonts.google.com)

Fonts for headings, sub-headings and body text were styled using Google fonts. Those selected were researched and are deemed to work well together in combination. 
