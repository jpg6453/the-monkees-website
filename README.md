# The Monkees Website

I have been asked by the band’s representatives to build a static (front-end only) website because they feel that the band’s current site is tired and out of date.  The site has a homepage with image carousel, music section which announces the latest release with sample tracks, a video section showing the band in their heyday and a tour section detailing up and coming tour dates and a link to purchase tickets.

The about page contains a short bio of each band member and the photos page shows a gallery with photos of the band spanning a 50 year career.

The book us page contains a simple form for fans to fill in and book the band for an event. This is a key business goal of the site.

The website can be viewed on **GitHub Pages** [here](https://jpg6453.github.io/the-monkees-website/)


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

## Testing

Testing user stories outlined in the UX section above.

**1. As a fan, I would like to browse for songs, so that I can play my favourites.**

i. Visit the home page and scroll down to the “Listen” section where there are details of the band’s latest release with 4 clickable sample tracks that are prominently displayed. Songs will be played natively. Verify that each track plays.

ii. Try to navigate to this “Listen” section by clicking the Music link in the nav menu on any page. Confirm that the link works on all pages.

iii. There is clickable Spotify icon which takes users to the Monkees section of the Spotify website in a separate tab. Verify the link works and opens in a separate tab.

**2. As a fan, I would like to watch videos, so that I can see the band perform.**

i. Visit the home page and scroll down to the “Watch” section to the embedded music video. Try to play the video and verify that the controls work.

ii. Try to navigate to this “Watch” section by clicking the Video link in the nav menu on any page. Confirm that the link works on all pages.


**3. As a potential fan, I would like to browse for songs, so that I can listen to their back catalogue.**

i. Follow the same test contained in user story 1. above.

**4. As a potential fan, I would like to learn more about the band, so that I can find out about them as people.**

i. Navigate to the about page where 4 cards are displayed which feature a photo and short bio of each band member.

ii. Try to navigate to the about page by clicking the about link in the nav menu on any page. Confirm that the link works on all pages.

**5. As a potential customer, I would like to send in an event request, so that I can book them for a birthday party.**

i. Navigate to the book us page using the highlighted book us link in the nav menu from any page. Confirm the link works on all pages.

ii. Try to fill out the form and click the send call to action button.

iii. Verify there are no error messages.

**6. As a live music lover, I would like to find a list of tour dates, so that I can see them in concert.**

i. Visit the home page and scroll down to the “Tour” section where there are details of the band’s current tour dates. 

ii. Click the Get tickets call to action button and confirm the ticketmaster website launches in a separate tab.

iii. Try to navigate to the “Tour” section by clicking the Tour link in the nav menu on any page. Confirm that the link works on all pages.

**7. As a visitor to the site, I would like to navigate easily, so that I can move around the site and find what I need.**

i. Users can easily find the navbar which is fixed at the top of each page.

ii. The logo in the top left of the navbar takes users back the home page.

**8. As a fan, I would like to browse photos of the band.**

i. Navigate to the photos page using the Photos link in the nav menu from any page. Confirm the link works on all pages.

ii. Click on any image to enter fancy box “lightbox” mode. Use the arrow controls to cycle through the photos.

### Manual Functionality testing of all pages

#### Home Page

**1. Navigation Bar**

i. On desktop, go to the Home page.

ii. Reduce the browser size down to tablet to verify that the navbar is responsive and switches from the expanded, inline menu to burger menu at this screen size.

iii. Verify that the logo alt text (brand logo) appears on hover.

ix. Click on the logo in the top left of the navbar and confirm that it links to the home page.

v. Click on each navigation menu element and confirm that it links to the correct page/section.

vi. Confirm that there is a subtle colour change when hovering over the highlighted book us link in the Nav bar.

vii. Reduce the screen down to small and confirm the burger menu drops down when clicked.

viii. All above functionality and checks carried out on tablet and mobile.

**2. Carousel**

i. On desktop, navigate to home page.

ii. Verify that the carousel is visible, cycles between the 2 images automatically on loading and occupies the full screen width. Check also that the indicators are visible.

iii. Reduce the screen size down to small to confirm that the caption on slider 2 does not appear.

**3. Listen Section**

i. Scroll down to the Listen section and confirm that the text and image layout looks good on all screen sizes.

ii. Reduce the screen size to small to confirm that the right hand column containing the sample  audio tracks wraps under the album artwork.

iii. Play each audio track in turn to verify they play natively.

iv. Click “Listen on Spotify” logo link and confirm it opens in a separate tab.

**4. Watch Section**

i. Scroll down to the Watch section and confirm that the video is visible and occupies the right hand half of the screen, does not autoplay and the poster image is displayed with the controls overlaid.

ii. Play the video and verify that all the controls work.

iii. Reduce the browser size and check that the video position is responsive and looks balanced within the section.

**5. Tour Section**

i. Scroll down to the Tour section and confirm that the tour dates poster is centred and the layout looks good.

ii. Hover over the “Get Tickets” call to action button to check there is a subtle change to the button background colour. 

iii. Click the Get Tickets button to verify that it links to the ticketmaster website and launches in a separate tab.

iv. Verify that the 2 blockquotes appear one underneath the other on smaller screen sizes.

**6. Footer**

i. Check each social media icon in turn and verify that the icon and background colours reverse out on hover.

ii. Click each icon and verify it links to the correct social media site in a separate tab.

iii. Check the responsiveness of the footer across all screen sizes and check that the layout looks good.

**7. Repeat the above on tablet and mobile to ensure responsiveness on all available devices.**

#### About

**1. Navigation**

i. Repeat procedure carried out to test navbar on Home page.

ii. Verify that code in navbar section of each html page is the same.

**2. Cards**

i. Confirm that the cards containing images and bios of the band are laid out in a single row of 4 and the layout looks good.

ii. Reduce the screensize to tablet and confirm that the layout switches to 2 rows of 2 cards.

iii. Change the screensize to small and verify that the layout changes again to a single scrolling column of 4 cards.

**3. Footer**

i. Repeat test procedure carried out to the footer on Home page.

ii. Check that the code in the footer section on the About, Photos & Book Us html pages is the same.

**4. Repeat the above on tablet and mobile to ensure responsiveness on all available devices.**

#### Photos

**1. Navigation**

i. Testing complete, the navbar is the same on all pages.

**2. Gallery**

i. Review html code to check that each image has an alt attribute assigned to facilitate the use of screen readers for visually impaired users. Title attributes were not assigned as it would compromise the look of the photo gallery.

ii. Click on each photo to check that the fancy box “lightbox” mode starts.

iii. With the fancy box modal on screen, cycle through the photos with the forward and back arrows and verify all other controls work properly.

iv. Reduce the browser size to check that the grid of photos is responsive and is well laid out across all devices.

**3. Footer**

i. Testing complete, the footer is the same as the about page.

**4. Repeat the above on tablet and mobile to ensure responsiveness on all available devices.**

#### Book Us

**1. Navigation**

i. Testing complete, the navbar is the same on all pages.

**2. Contact Form**

i. Try to submit the form with all fields empty and confirm that an error message is displayed.

ii. Try to enter text into the phone field and verify that no text or special characters are accepted.

iii. Try to submit the form with an invalid email address and confirm that the relevant error message is displayed that prompts the user to enter the correct format.

iv. Try to submit the form with valid inputs in all fields and verify there is no error message. There will be no success message as this is a front end only project.

v. Resize the browser by increasing and decreasing the width to check that the form is responsive and looks good across all devices.

vi. Verify that there is a subtle colour change to the “send” call to action button on hover.

**3. Footer**

i. Testing complete, the footer is the same as the about page.

**4. Repeat the above on tablet and mobile to ensure responsiveness on all available devices.**

#### Further Testing

i. I tested the website on all devices that I have at my disposal (iMac, Windows laptop, iPad, iPhone 5/6/7/XR) across multiple browsers.

ii. A link to the website was sent to family and friends, particularly those with Android devices, and comments/observations were invited.

## Deployment

**Hosting On GitHub Pages**

This website was committed to git and pushed to GitHub via the terminal built into the Cloud 9 IDE.
The project was deployed to GitHub Pages from this GitHub repository by doing the following:
1.	Log into GitHub.
2.	From the list of repositories on the left side of the screen, select **jpg6453/the-monkees-website**
3.	From the toolbar at the top of the page, select Settings.
4.	Scroll down to GitHub Pages.
5.	Under Source change the drop down menu from None to Master Branch
6.	On selecting Master Branch the website is now deployed and the page refreshes.
7. Scroll back down to the GitHub Pages section to find the link to the deployed site,   Your site is published at https://jpg6453.github.io/the-monkees-website/

At the time of submission there is no difference between the master branch and the deployed version of the project.

**To run locally**

The website can be cloned from GitHub as follows:
1.	Follow this link to the repo https://github.com/jpg6453/the-monkees-website 
2.	Click "Clone or download".
3.	A Clone with HTTPs modal appears on screen, copy the clone URL for the repository https://github.com/jpg6453/the-monkees-website
4.	Within your chosen IDE launch a terminal session
5.	Ensure the current working directory is the location where you want the cloned directory to be made. Change this if necessary.
6.	Type git clone, and then paste the URL copied in Step 3.
	git clone https://github.com/jpg6453/the-monkees-website
7.	Press Enter and a clone will be created locally. This could take a few minutes.


## Credits

### Content
	
**About Page**

Text for each band member bio taken from Wikipedia.

[Davy](https://en.wikipedia.org/wiki/Davy_Jones_(musician))

[Micky](https://en.wikipedia.org/wiki/Micky_Dolenz)

[Peter](https://en.wikipedia.org/wiki/Peter_Tork)

[Michael](https://en.wikipedia.org/wiki/Michael_Nesmith)

### Tour Dates

Dates  taken from [facebook](https://www.facebook.com/TheMonkees/)

Quotes by Micky Dolenz and Mike Nesmith taken from [Eventfinda NZ](https://www.eventfinda.co.nz/news/2018/12/the-monkees-present-the-mike-micky-show-tour-hits-nz-roads-in-june-2019)

### Code 

CSS code to push down the footer when content is shorter than the viewport taken from [CSS Tricks](https://css-tricks.com/couple-takes-sticky-footer/)


### Media

#### Images

**Homepage** 

Logo in Navbar - [Fanart](https://fanart.tv/artist/b8549efe-f4fd-4dc0-8ef1-226e9c400233/monkees-the/?loggedout=true)

**Carousel**

Slide 1 - Band image supplied by **Code Institute.**

Slide2 - Peter Tork tribute. Obtained from [Rolling Stone](https://www.rollingstone.com/music/music-news/peter-tork-monkees-dead-at-77-obituary-797269/)

**Listen Section**

Album Artwork - The Very Best of the Monkees - **Supplied by Code Institute.**

Spotify Logo - [here](https://itslivb.com/podcast/spotify-logo-png-file-spotify-badge-large-png-1280/)

**Watch Section**

Video Poster Image - [Pass the Paisley](https://passthepaisley.com/the-monkees-daydream-believer/)

**Tour Dates Section**

Tour Poster image obtained from [Eventfinda NZ](https://www.eventfinda.co.nz/news/2018/12/the-monkees-present-the-mike-micky-show-tour-hits-nz-roads-in-june-2019)

**About Page** 

Images supplied by **Code Institute**

**Photos Page**

**Row 1 L-R**

1.[RTE](https://www.rte.ie/entertainment/2016/0209/766577-the-monkees-to-reform-with-new-album-and-tour)

2.[Rolling Stone](https://www.rollingstone.com/music/music-features/the-monkees-michael-nesmith-micky-dolenz-on-their-upcoming-duo-tour-630457/)

3.[BGM](https://beardedgentlemenmusic.com/2016/06/24/monkees-good-times-review/)

**Row 2 L-R**

1.Code Institute

2.[CSINDY](https://www.csindy.com/coloradosprings/the-monkees-present-the-mike-and-micky-show-at-paramount-theatre-show-preview/Content?oid=12798435)

3.[USAtoday](https://www.google.com/search?client=safari&rls=en&biw=1920&bih=996&tbm=isch&sa=1&ei=jy3-XMesEvuV1fAP7JS9wAs&q=peter+tork+usa+today&oq=peter+tork+usa+today&gs_l=img.3..35i39.41895.44130..44637...0.0..0.69.621.10......0....1..gws-wiz-img.......0j0i24.OgH5cM3tkuU#imgrc=3yNVctMzkMPIoM:)

**Row 3 L-R**

1. [Grunge](https://www.grunge.com/146172/the-untold-truth-of-the-monkees/)
2. [WGN](https://www.google.com/search?q=monkees+wgn&client=safari&rls=en&source=lnms&tbm=isch&sa=X&ved=0ahUKEwju6NW92t7iAhU4SxUIHc7cCdQQ_AUIECgB&biw=1324&bih=969#imgrc=1PawYSLJTOELvM:)
3. [Xmas](http://www.947wls.com/2018/09/21/the-monkees-to-unwrap-christmas-party-next-month/)

**Background Images**

About Page - [Speaker](https://pixabay.com/photos/audio-speaker-astronomy-exploration-1839221/)

Photos Page  - [Space](https://pixabay.com/illustrations/background-space-universe-galaxy-3883181/)

Book Us Page - [Concert](https://pixabay.com/photos/music-silhouette-concert-people-3084876/)

### Audio

**Listen Section**

4 Native Play mp3 audio files (Last Train to Clarksville, I'm A Believer, 'Steppin Stone, Daydream Believer - **supplied by Code Institute**.

**Link to Monkees Content on** [Spotify](https://open.spotify.com/artist/320EPCSEezHt1rtbfwH6Ck)

### Video

**Watch Section**

Daydream Believer MP4 Video - supplied by Code Institute.

## Acknowledgements

I received inspiration for this project by browsing band websites from other genres/generations (U2.com, www.thekillersmusic.com, thebeatles.com, coldplay.com) and received support and encouragement from my mentor Marantha Ilesanmi.

## Disclaimer

This site was built for educational purposes only.


