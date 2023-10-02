# GP Aviation
![Full Screenshot](readme_screenshots/scrot_full.png)
GP Aviation is a website for a hypothetical helicopter company based in Sweden focused on selling different experience trips, such as sightseeing tours around Stockholm, short learning sessions with instructors or luxurious transfer trips.

## Features

### Navigation Bar
![Navigation Bar](readme_screenshots/scrot_navbar.png)
The Navigation bar is fixed to the top of the page, on the left side is the company logo, wich is clickable and leads back to the main page.
To the right are links to the different pages, the current page is underlined to make it easier for the user to know where they are.
The navigation bar is responsive so when viewed on smaller devices the links collapses into a bar icon, when pressed a menu appears with the links.

### Hero image.
Each page starts with a large beatiful hero image that covers the entire width of the page. The image is different for each
page making navigation easier.

### Main Page
![Main Page](readme_screenshots/scrot_main.png)
Beneath the hero image are three sections, each for the different services 'GP Aviation' has to offer.
Each section starts with a header and a location pin to show where the service is available. A short paragraph explains the experience followed by an unordered list that explains how many passengers each service can carry, the estimated length of the ride, as well as where the estimated starting price is currently at. 
Each section ends with a button that leads to the Booking page.

### Booking
![Booking](readme_screenshots/scrot_booking.png)
Starts with a short paragraph explaining that the company's sales team will contact the client after the form beneath is submitted.
The form contains:
- Radio button selector for which experience the client is interested in.
- Preferred date.
- Contact information.

### Our Fleet
![Fleet](readme_screenshots/scrot_fleet.png)
This page showcases the different aircrafts GP Aviation owns. With a picture and a short paragraph.

### About us
![About](readme_screenshots/scrot_about.png)
Here we find a backstory of the company, founded by a former Swedish helicopter pilot.

### Footer
![Footer](readme_screenshots/scrot_footer.png)
The footer contains social media links and copyright information.

## Testing
I've tested the website on:
- Safari
- Firefox
- Chrome
- IOS

### Bugs
- Warning: Section lacks heading.
When validating, I got a warning that the hero-image section lacked a header.
Since I didn't want any text in this section, I fixed it by adding a hidden header:
```html
<section id="hero-image" class="hero-index">
<h2 class="hidden">GP Aviation</h2>
</section>
```

```css
h2.hidden {
visibility: hidden;
}
```

- Duplicate ID information.
I had multiple `<div>` with the `id=information` tag. This is not valid HTML.
    * Changed `id=information` to `class=information`.
    * in style.css I changed `#information` to `.information`

### Known bugs
No known bugs remaining.

### Validator Results
* HTML
* No errors were found by [W3C validator](https://validator.w3.org)
* CSS
* No errors were found by [jigsaw validator](https://jigsaw.w3.org/css-validator/)

## Technologies used
- HTML5
- CSS

## Deployment
The page is hosted on GitHub Pages
[Link](https://dvudd.github.io/CI_PP1/)
## Credits
### Contents
- The Code for the toggleable navigation bar and social media links was taken from CI Love Running project.
- Fonts used are:
    * Font awesome
    * Noto Sans and Mulish from Google Fonts.
### Media
- Photos [www.pexels.com](https://www.pexels.com/)
- Favicon: [favicon.io](https://favicon.io)
- The "founder" of the company is generated by:[thispersondoesnotexist.com](https://thispersondoesnotexist.com)
- https://dvudd.github.io/CI_PP1/

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)
This is my Portfolio Project 1 as part of the Full Stack Software Developer program at [Code Institute](https://codeinstitute.net/).
David Eriksson 2023