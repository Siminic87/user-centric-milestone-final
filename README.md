# MarketingMan.ie – Digital Marketing Agency Homepage
MarketingMan.ie is a page where owners of small and medium sized businesses can quickly inform themselves about Online Marketing Services in the wider Dublin area as well as purchase them.

## UX
The purpose of MarketingMan.ie is to attract new customers via the “portfolio” and “services” page and then convert them via the contact page.

The page is for any individual or company who would like to avail of digital marketing services in the general Dublin area. 

MarketingMan.ie is the best way to book online marketing services in the Dublin area because of its local focus and efficient internal structure, potential customers can quickly inform themselves and then book the services they desire. 

- As a user type, I want to quickly inform myself about online marketing services on offer.
- As a user type, I want to be able to quickly book online marketing services I need.

Mockup:
[gomockingbird.com](https://gomockingbird.com/projects/yyire2b/4gXVnC)

## Features
MarketingMan.ie has various features that all intend to inform about Online Marketing and make booking Online Marketing services in the wider Dublin area as easy as possible. 

### Existing Features
- Top of Page Navigation - allows users to quickly navigate between pages in order to get to the information or feature that is desired. Special emphasis put on the contact page via CTA button on the right.
- Callout Section – Immediately introduces the main purpose of the page and allows users to quickly get to the contact page in order to book Online Marketing Services via the “Get in Touch!” Button. 
- Content Section – Displays written and visual content as relevant to each subpage.
- Portfolio Carousel – Allows users to quickly get an overview about past projects of MarketingMan in order to give an idea of what kind of quality one can expect. 
- Contact Form – Allows users to contact the website owner by inputting text into a form on the page and submitting it to his email address.
- Footer – Quick display of copyright information and contact page link.

All features fully responsive on mobile devices (incl. tablets and smartphones). 

### Features Left to Implement
- Direct booking system (vs. contact form only)
- SEO-optimized subpages with more detailed information on Online Marketing and the corresponding packages on offer.

## Technologies Used
- HTML
-- The project uses HTML code to allow structuring and display of the information presented via MarketingMan.ie.
- CSS
-- The project uses CSS code to visually design the data that is being transmitted via HTML.
- [Bootstrap](https://getbootstrap.com/docs/3.3/)
-- The project uses the Bootstrap framework (v. 3.3.7) to save time in development by relying on standardized HTML and CSS elements that can be found in the library.
- [jQuery](https://blog.jquery.com/2017/03/20/jquery-3-2-1-now-available/) & [Bootstrap javascript](https://getbootstrap.com/docs/3.3/getting-started/)
-- The project uses jQuery (v. 3.2.1) and Boostrap javascript (v. 3.2.1) for animation and inclusion of portfolio carousel element.
- [Google Fonts](https://fonts.google.com/)
-- The project uses Google Fonts to include font styles that visually represent the message of the page.
- [Embedded YouTube Video](https://www.youtube.com/watch?v=cP74xRrlSW4)
-- The project uses an embedded YouTube video in order to offer multimedia video content to users informing them about online marketing services.

## Testing
1.	Quick information about online marketing services on offer
    1. Go to the "MarketingMan.ie" homepage
    2. Try to scroll down to Content Section and click on “Learn More” to get to Portfolio Page. Verify that Portfolio Page is linked correctly and fully loads upon click. 
    3. Try to scroll down to Portfolio Section and verify that carousel moves slides correctly to left or right when clicking on corresponding arrow buttons.
    4. OR Try to click on “Services”, “Portfolio” or “Contact” /  “Get in Touch!” / “Get Quote” / ”Get your 1st free” in Main Navigation, Footer, Callout Section on homepage or at bottom of Services Page to get to relevant subpages. Verify that subpages are linked correctly and fully load upon click. 
    5. Try to click on video on Services Page and verify that it plays correctly.
    6. Try to scroll down to Portfolio carousel on Portfolio Page and verify that carousel moves slides correctly to left or right when clicking on corresponding arrow buttons.

Manual testing revealed that all content and pages are seamlessly accessible on all devices and all major browsers. The page looks virtually the same on different Browsers. 

2.	Quick booking of marketing services
    1. Go to Contact Page
    2. Try to scroll down to Callout Section and click on “Get in Touch!” CTA Button to get to Contact Page. Verify that Contact Page is linked correctly and fully loads upon click. 
    3. Try to enter information on Contact form and verify that email address format is corrected by form if wrong, that all options from category drop-down menu can be chosen and that form can be submitted.

Manual testing revealed that all content and pages are seamlessly accessible on all devices and all major browsers. The page looks virtually the same on different Browsers.
Only one minor bug was noticed when content on main page would not display correctly due to unclosed div tag. Bug fixed.

## Deployment
Uploaded project to github repository by using:

- git remote add origin https://github.com/Siminic87/user-centric-milestone-final.git

Followed by:

- git push -u origin master

Was then asked to enter username and password to confirm. Project now stored here: [https://github.com/Siminic87/user-centric-milestone-final](https://github.com/Siminic87/user-centric-milestone-final)

To run: download project to workspace in [Cloud9](https://c9.io/login), open index.html and click "Run" on top navigation.

## Credits
### Media
- The photos used in this site were obtained from [pixabay.com](http://pixabay.com)
- The video used in this site was embedded from [youtube.com](https://www.youtube.com/watch?v=cP74xRrlSW4m)

### Portfolio Carousel
- Advice for adapting Bootstrap carousel snippet for showing multiple slides at one found on https://stackoverflow.com/questions/20007610/bootstrap-carousel-multiple-frames-at-once