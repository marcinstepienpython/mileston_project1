# The Monkees

Project idea was to build a website for a rock band. The webpage contains info about the group, band members and upcoming events. The visitors have an opportunity to book the band for a private show, book tickets for live preformances and buy all currently available albums.

The website is available here: https://marcinstepienpython.github.io/mileston_project1/

## UX

The Monkees website is a simple design consising of three sections.

THE LAYOUT:

- MAIN NAVIGATION:

  - User will have a possibiliy to navigate to:
    - The Monkees => index.html
    - The Band => band.html (info about the band and samples od music/video)
    - News => news.html (info about current chenages and news about the band)
    - Concerts => concerts.html (info about coming live shows and links to buying tickets)
    - Book a Show => book.html (form to book the band for a private show)
    - Shop => shop.html (links to amazon.com where users may acquire band's albums)

- DISPLAY SECTION:

  - Displaying main content of given sub-page => eg. news, book form, concerts dates and tickets links.

- SOCIAL LINKS:

  - Displaying links to all social platforms related to the band (facebook, instagram, twitter).

USER SCENARIOS:

1. Buy tickets: visitors can see 'buy tickets' link right on the main page. Apart from 'news' buying tickets will be the most frequent action on the page. Users have also special section dedicated to buying tickets for upcomming events.

2. Book the band for wedding/party: visitors have dedicatted section (book.html) for booking the band for private events. In future the section will be upgraded with calendar for viewing possible private shows dates.

3. Buy album(s): visitors will find dedicated section (albums.html) where they can listen to sample music and buy band's albums on amazon.com.

4. Learn about the band: visitors will find a dedicated section (band.html) with band's history and info about current band members. Sample music and recent band's videos are available to listen/watch.

5. Check the news: dedicated section (news.html) for updates and press coverage.

## Features

The website makes it easy for visitors to purchase tickets, albums and book the band for private shows. The info about the band and news are also accessible.

### Existing Features

The website sections and subpages:

- Showcase photos, audio and video clips from the band's catalog.
- Publicise the band's upcoming shows and/or availability to perform at events such as weddings and corporate parties.
- Provide links to external resources, such as the band's social media profiles (can point anywhere at all).

### Features Left to Implement

Shop:

- It would be a good idea to implement own shop, where vistors might purchase band's related products (t-shirts, posters, dvds).

Calendar:

- Implementation of a booking system where visitors might find open time spots for possible private shows.

## Technologies Used

HolidayPal uses following frameworks:

- [Bootstrap](https://getbootstrap.com/)

  - The project uses **Bootstrap** to simplify managing layout and CSS elements.

- [Google Fonts](https://fonts.google.com/)

  - The project uses **Google Fonts** to display beautiful and free fonts.

- [JQuery](https://jquery.com)

  - The project uses **JQuery** to simplify DOM manipulation.

The site has been created using:

- HTML
- CSS
- JavaScript

## Testing

Basic set-up:

1. Added boostrap framework and tested by creating simple container and jumbotron classes.
2. Added google fonts and tested Fixed the '|' issues in rel link.

Layout:

1. Testing site responsiveness:

   - google developer tools:
     - site has been tested on all available devices (Galaxy, iPhone, iPad)
   - mobile phones (Huawei P8, iPhone 8, iPhone 6)
   - tablets (Samsung Galaxy Tab)

2. Validators
   The page has been validated using the following tools:

- (html) https://validator.w3.org/ => resulted in: Document checking completed. No errors or warnings to show.
- (html) https://html5.validator.nu/ => resulted in: The document is valid HTML5 + ARIA + SVG 1.1 + MathML 2.0 (subject to the utter previewness of this service).
- (css) https://jigsaw.w3.org/css-validator/ => resulted in: W3C CSS Validator results for https://marcinstepienpython.github.io/mileston_project1/css/main.css (CSS level 3 + SVG) => Congratulations! No Error Found.

## Deployment

The Application has been deployed to GitHub Pages. There is no difference between development and production version of the system. No environemnt variables have been used.

Deployment log:

- c98ad8d was deployed by GitHub Pages

The application is available here: https://marcinstepienpython.github.io/mileston_project1/

Deployment issues:

- relative links in the main navigation fixed through "./[pagename.html]" path.

### Content

The page uses information found on Wikipedia. It applies to the section about band history. All the info has been copied from Wikipedia.

### Media

The page usues images related to google search about The Monkees. Some of the images have been provided by Code Institute. Video files and MP3 files have been provided by Code Institute.
