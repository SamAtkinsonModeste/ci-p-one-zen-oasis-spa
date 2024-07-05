<div align="center">
  <img src="assets/images/spa-logo-text-readme.webp" style="border-radius: 10px; width: 250px" alt="Zen Spa Logo">
</div>
<div align="center">
  <img src="assets/images/all-devices.webp" alt="Home page of Zen Spa">
</div>

# Zen Oasis Spa

[Zen Oasis Spa](https://samatkinsonmodeste.github.io/ci-p-one-zen-oasis-spa/index.html) website was created as a digital gateway to the serene experience that awaits within its walls. It serves as an invitation for visitors to explore the array of rejuvenating treatments and facilities Zen Oasis offer. The website reflects its commitment to relaxation, wellness, and rejuvenation. It’s designed to provide a glimpse into the tranquil atmosphere and holistic approach that define it's spa, encouraging guests to book their next escape to rejuvenation. 🌸💆‍♀️

## User Story:

- #### Persona: Jenny, a 28-year-old marketing executive.
- #### Goal: To find a spa that offers a tranquil environment and specialized facial treatments that cater to her stressed skin

### Acceptance Criteria:

- The spa website must provide clear information on various facial treatments, including mud and mask therapies.

- The booking process should be straightforward, allowing Jenny to schedule an appointment with ease.

- High-quality images of the spa’s serene setting and treatment rooms should be displayed to set the mood for relaxation.

## Table of Contents

## UX

- [Goals](#goals)
  - [Visitors Goals](#visitors-goals)
- [Visual Design](#visual-design)
  - [High Fidelity Mockup](#high-fidelity-mockup)
  - [Fonts](#fonts)
  - [Colour](#colour-palette)
  - [Styling](#styling)
- [Features](#features)
  - [Navigation Bars](#naviagation-bars)
    - [Mobile Navigation](#mobile-navigation)
    - [Tablet Desktop Navigation](#tablet-desktop-navigation)
  - [Home Page](#home-page)
    - [Home Welcome Section](#home-welcome-section)
    - [Unwind Tranquillity](#unwind-tranquillity)
    - [Explore Escape](#explore-escape)
    - [Treatments Experts](#treatments-experts)
  - [Treatment Page](#treatment-page)
    - [Treatment Introduction](#treatment-introduction)
    - [Body Massages](#body-massages)
    - [Facial Massages](#body-massages)
  - [Booking Page](#booking-page)
    - [Booked Page](#booked-page)
    - [Booked Page Links](#booked-page-links)
    - [Booked Page More](#booked-page-more)
  - [Footer](#footer)
  - [Technologies Used](#technologies-used)
    - [Languages](#languages)
    - [Other Tools](#other-tools)
  - [Testing](#testing)
    - [Methods](#methods)
      - [Validation](#validation)
      - [Accessibility](#accessibility)
      - [Mobile Testing](#mobile-testing)
      - [Desktop Testing](#desktop-testing)
  - [Bugs](#bugs)
    - [Known Bugs](#known-bugs)
    - [Fixed Bugs](#fixed-bugs)
- [Deployment](#deployment)
  - [Github Deployment](#github-deployment)
- [Credits](#credits)
- [Author](#author)

## Goals

### Visitors Goals

User goals are:

- Get a sense of the spa's ambience
- View all treatment massages available
- Book a time and date for their treatment

### Visual Design

#### High Fidelity Mockup

With a clear idea of the site's look, I went straight to a high-fidelity mockup using Adobe XD.

> Note: The standard process is to create a Wireframe first.

<div align="center">
  <img src="assets/images/high-f-mockups.webp" style="background-color:black" alt="Home, Treatment and Booking mobile pages mockups">
</div>

### Fonts

<div align="center">
  <img src="assets/images/amandine-font.webp" alt="Font Amandine">
</div>

- Adobe's [Amandine](https://fonts.adobe.com/fonts/amandine) font has clean lines and graceful curves that evoke a sense of elegance and tranquillity.
  It complements the serene atmosphere of Zen Oasis, conveying relaxation and sophistication.
  Amandine’s legibility ensures that headings are easy to read, even at larger sizes. The balanced letterforms enhance clarity, making it ideal for titles and headers. Amandine works well across various devices and screen resolutions. Whether on a desktop or mobile, it maintains its visual appeal.

<div align="center">
  <img src="assets/images/aptly-font.webp" alt="Font Aptly">
</div>

- Adobe's [Aptly](https://fonts.adobe.com/fonts/aptly) font was used for body text. It is also a sans-serif font, and the combination of **Amandine** (for headings) and **Aptly** (for body text) creates a pleasing contrast. **Amandine’s** sophistication draws attention, while **Aptly** maintains legibility, striking a harmonious balance.
  **Aptly’s** contemporary aesthetics align with the site's modern and serene vibe. Its simplicity conveys professionalism and a sense of calm. Aptly adapts well to various screen sizes, ensuring a consistent experience on desktops, tablets, and mobiles.

### Colour Palette

<div align="center">
  <img src="assets/images/color-palette.webp" alt="Colour palette of 6six different colours">
</div>

- The primary colour evokes relaxation, tranquillity, and sandy beaches, setting the overall tone and mood of the website.
- The accent colour adds visual interest and draws attention to specific elements.
- My white shade represents purity, cleanliness, and spaciousness. As the background colour for content areas, it ensures readability and a sense of openness.
- My black, which hints at the accent colour, makes a great contrast.
- My greys provide subtle contrast and depth.

### Styling

<div align="center">
Over the years, my CSS journey has been fun.<br>
I love how you can use CSS not only for the layout of your pages <br> but also to add artistic touches to your site using properties such as:
 </div>

- [Text-Shadow](https://www.w3schools.com/cssref/css3_pr_text-shadow.php) By giving the horizontal value zero, the vertival setting a positive value and a small blur value text can seem as if they are popping or leaping off the page.
- [Border-Radius](https://www.w3schools.com/cssref/css3_pr_border-radius.php) which can be used to make interestng shapes of a block element.
- [RGBA Function](https://css-tricks.com/the-power-of-rgba/) used with background images can change the look and feel of your image by taking advantage of the Aplha value.
- I used [Normalize.css](https://necolas.github.io/normalize.css/) to reset all elements across all browsers.
- [Media Queries](https://www.w3schools.com/cssref/css3_pr_mediaquery.php) - I used several to ensure my layout stayed intact for most devices.

## Features

### Navigation Bars

#### Mobile Navigation

<div align="center">
  <img src="assets/images/mobile-nav.webp"  alt="Mobile Hamburger Nav">
  <img src="assets/images/mobile-nav-open.webp" alt=" Mobile Hamburger Nav Open">
</div>

- The logo returns a user to the home page.
- I created the hamburger with span tags.
- With the use of a checkbox along with it's corresponding label animation of the span elements can be toggled to display the nav menu.
- The accent color was used for the text links to indicate what page the user is currently on.

#### Tablet Desktop Navigation

<div align="center">
  <img style=" width: 600px"src="assets/images/nav.webp"  alt="Desktop Nav">
</div>

- The full nav functions the same as the mobile.
- The logo takes you back to the home page.
- The accent colour is used on the links to indicate the current page a user is on.

## Home Page

### Home Welcome Section

<div align="center">
  <img src="assets/images/home-welcome.webp"  alt="Home top section with reception image and welcome text">
</div>

- A luxurious reception picture establishes the ambience for a high-class spa escape.
- A heartfelt welcome message embodies the spa's principles and atmosphere.

### Unwind Tranquillity

<div align="center">
  <img src="assets/images/home-relax.webp"  alt="Home unwind section candles and massage tools image with text">
</div>

- An image of all the tools used for massages and candles representing the relaxing, quiet, calm, and romantic ambiance of a spa.
- Embracing simplicity, the text emphasizes the essential activities of mind and body.

### Explore Escape

<div align="center">
  <img src="assets/images/home-explore.webp"  alt="Home section pool image and text">
</div>

- Text encouraging users to explore the spa's services.
- The image of the pool, towel, and orchard flowers will evoke thoughts of escape, vacation, and relaxation.

### Treatments Experts

<div align="center">
  <img src="assets/images/home-treatments.webp"  alt="Home treatment section image of massge beds and text">
</div>

- An enchanting scene is set with a background image of massage beds and rose petals, creating the perfect ambiance for the magic of massages to unfold.
- The accompanying text outlines the high standard of massages provided by the expert therapist.

## Treatment Page

### Treatment Introduction

<div align="center">
  <img src="assets/images/treatment-intro.webp"  alt="Treatment top section intro to massages with text and image of massage beds">
</div>

- The image of the waiting area in the massage therapy rooms and the inviting beds ignites a sense of anticipation for what lies ahead in the massage room.
- The text beautifully highlights the three main aspects of well-being that a massage therapist can nurture: the mind, body, and spirit.

### Body Massages

<div align="center">
  <img src="assets/images/treatment-body-massages.webp"  alt="images of Swedish, Hot-Stone and Couples massages with text explaining each one.">
</div>

- Each Massage article has an image of the specific massage.
  Which gives a visual demostration of that specific massage.
- Every body article massage is color-coded, representing the uniqueness of each massage.
- A comprehensive description of the massage and its benefits for the body, mind, and spirit will help users determine if it's the perfect fit for them.

### Facial Massages

<div align="center">
  <img src="assets/images/treatment-face-massages.webp"  alt="images of Facial, Mud Facial and Mask Facials with text explaining each one.">
</div>

- Facial massages are categorized separately from body massages.
- Images are a powerful tool to distinguish between the various types of facial massages and to illustrate their unique characteristics.
- Each paragraph unlocks the potential of each facial massage as it reveals different purposes, guiding the user to choose the one that's right for them.

## Booking Page

<div align="center">
  <img src="assets/images/booking-form.webp"  alt="booking form.">
</div>

- A form provides the method for a user to book their massage.
- In the first part of the form, a user can enter their contact details.
- The second part of the form presents an opportunity for users to select the massage that best suits their needs and preferences.
- The user has the power to select the perfect date for their rejuvenating massage.

### Booked Page Links

<div align="center">
  <img src="assets/images/booking-thank-you-links.webp"  alt="Image of indoor pools and text">
</div>

- Once a user submits the booking form through the action attribute of the form, they are taken to the _Thank you for booking_ page.
- With a Book link, a user is empowered to return to the booking page and indulge in booking another rejuvenating massage experience.
- The alternative is for the user to utilize the "Home page" link.

### Booked Page More

<div align="center">
  <img src="assets/images/booking-enjoy.webp"  alt="A couple in a spa pool.">
</div>

- An invitation to fully embrace the additional amenities at the spa is warmly extended.

## Footer

<div align="center">
  <img style="width: 800px;" src="assets/images/footer-social-media.webp"  alt="A footer with social media image links">
</div>

- The footer is not just a small detail, it is one of the consistent elements present on every page.
- It is crucial to maintain a strong presence on social media in today's digital landscape. The footer showcases each social media platform where Zen Oasis is active.

- The inclusion of social media links opens the doors for users to discover glowing reviews about Zen Oasis, stay in the loop with the latest offers, and reminisce about their stay, inspiring them to plan a return visit.

## Technologies Used

### Languages

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
  - Page Structure
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

  - Page Styling

  ### Other Tools

  - [Adobe XD](https://adobe-xd.en.softonic.com/)
    - To create the High Fidelity mock-ups.
  - [Favicon](https://www.favicon-generator.org/)
    - Creates multiple favicons from a single image to cater to diverse browsers and devices.
  - [Colormind](http://colormind.io/bootstrap/)
    - Designs colour palettes.

  # Testing

  ## Methods

  ### Validation

  - All HTML files validated with [W3C Markup Validation Service](https://validator.w3.org/)

    - <div align="center">
        <img src="assets/images/all-html-checked.webp"  alt="Images of four HTML pages validation results">
      </div>

- Stylesheet validated with [W3C CSS Validation Service](https://validator.w3.org/)

  - <div align="center">
      <img src="assets/images/css-validation.webp"  alt="Image of CSS validation results of a style sheet">
    </div>

    ## Accessibility

- I used [Chrome's Lighthouse](https://developer.chrome.com/docs/lighthouse/overview) for mainly accessibility as well as:
  - Performance
  - Best Practices
  - SEO
- <div align="center">
     <img src="assets/images/all-lighthouse.webp"  alt="A footer with social media image links">
   </div>

  ## Mobile Testing

  Mobile testing was done on:

  - iPhone 14 Pro Max
  - iPhone XR
  - Samsung S23

  Tablet

  - iPad Pro Portrait and Landscape

## Desktop Testing

Desktop testing was done on:

- Dell Inspiron Desktop
- Macbook Pro Laptop
- Huawei Laptop

## Bugs

### Known Bugs

- When the form is submitted user wasn't redirected to **thank-you.html**.

### Fixed Bugs

1. Submit button directing user to **thank-you.html** page - fixed by removing the _method_ attribute from my form element.
2. Added attribute _target_ with value _underscore blank_ to the _form_ opening tag.

# Deployment

## Github Deployment

### Github Instructions

Steps for creating a repository and deploying it:

1. I went to my GitHub account and clicked on the **Repositories** page, then I clicked on the **New** button.
2. On the **Create a new repository** page, I entered the name of my repository in the input element labelled _Repository name_.
3. In the input labelled _Description_, I wrote a brief description.
4. I made sure to select the radio button labelled **Public**.
5. I checked the checkbox labelled _Add a README file_ .
6. For the select element labelled _Add .gitignore_ I chose _VisualStudio_
7. Once done, I clicked the **Create Repository** button.
8. I cloned my new repository in my VSCode, where I added all my files.
9. Back on the GitHub site on the page of my new repository, I clicked on the **Settings** link.
10. On the **Settings** in the side nav I clicked on **Github Pages**.
11. In the **Github Pages** section I ensure the _Master Branch_ was the source and clicked **Confirm**.
12. After a few minutes, my repository was live.

This is my repository's [live link: Zen Oasis Spa](https://samatkinsonmodeste.github.io/ci-p-one-zen-oasis-spa/index.html)

> Note: I dabbled in creating branches and merging them into my main branch. While it's typical to delete these branches after merging, I chose to keep them as a testament to the power of branching in this project.

## Credits

#### Ideas for Spa Websites

I drew inspiration for my spa from various sources:

- The [Gloss Genius Blog about Spa Names](https://glossgenius.com/blog/spa-names) guided me in choosing the perfect name for my spa.

- I found ideas for designing my spa website from the [21 Best Spa Websites Examples 2024](https://colorlib.com/wp/spa-websites/) webpage.

- To understand various massage therapies, I explored the [10 Types of Spa Treatments to Rejuvenate Your Mind, Body, and Soul](https://www.bellacollina.com/blog/10-types-of-spa-treatments-to-rejuvenate-your-mind-body-and-soul).

- [Microsoft 365 Copilot](https://blogs.microsoft.com/blog/2023/03/16/introducing-microsoft-365-copilot-your-copilot-for-work/) provided much of the uplifting text content for my spa website.

- As someone who struggles with dyslexia, I relied on [Grammarly](https://app.grammarly.com/) for grammar and spelling support. Their AI also helped me enhance the overall wording of my text.

## Author

- Twitter - [@sammodeste1](https://www.twitter.com/@sammodeste1)
- LinkedIn - [Sam-Atkinson-Modeste](https://www.linkedin.com/<<sam-atkinson-modeste>>)
- GitHub - [SamAtkinsonModeste](https://www.github.com/SamAtkinsonModeste)
