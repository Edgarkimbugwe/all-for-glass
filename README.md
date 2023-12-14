# All for glass

All for glass is website with an intention of showing the works of a glazing workshop in sweden that is aimed to attract customers in need of glazing and auto car services.

![image](/assets/images/responsiveness.png)

## Table of contents

- [All for glass](#all-for-glass)
  - [Table of contents](#table-of-contents)
  - [Purpose and target audience](#purpose-and-target-audience)
  - [Design](#design)
    - [Color palette](#color-palette)
    - [Typography](#typography)
    - [Wireframes](#wireframes)
    - [Imagery](#imagery)
    - [Icons](#icons)
  - [Pages and Features](#pages-and-features)
    - [General Features](#general-features)
    - [Pages](#pages)
      - [Home page](#home-page)
    - [Our work page](#our-work-page)
      - [Ask us page](#ask-us-page)
  - [Technologies](#technologies)
    - [HTML and CSS](#html-and-css)
    - [Imagery](#imagery-1)
    - [Content](#content)
  - [Accessibility](#accessibility)
  - [Deployment](#deployment)
  - [Testing and Validation](#testing-and-validation)
    - [Testing](#testing)

## Purpose and target audience

The purpose of All For Glass website is to attract as many customers  as possible within Sweden to seek the services of the workshop whose experince in the glazing industry is second to none.

The services offered by the workshop are are within glazing and auto glass. By glazing, the customers can have their windows renovated from old glass to new glass on the market, design parts of their homes with glass, like in the bathrooms or even build glass walls. All this can be offered with the advise and planning between the customer and the workshop. In regard to auto glass, the website is intented to showcase to the cutomer that they are able to change any auto glass broken from any car.

## Design

### Color palette

To get matching designs of the colours used to the website, [Coolors](http://coolors.co/) was used. Also note that in the css values these colours were used with rgba values instead of hex values. the intention was to give them an opacity value directly in the color value when required.

![image](/assets/images/color%20palette.png)

- Header and Footer color : #58A4B0 - Note that in the header, the color is applied to the Logo, as seen in the image below.
  ![image](/assets/images/all-for-glass-logo.png)
- Background colors : #F3FBEF and #E0F7DE

### Typography

In regard to fonts, the google fonts below where used. However for the logo as seen in the image above, Microsoft 'Snap ITC' fonts were used since the logo was designed using the Microsoft Paint App.

- Abhaya Libre (Regular 400, Medium 500, SemiBold 600, Bold 700, ExtraBold 800) and Barlow Condensed of which only Light 300 was imported.

![image](/assets/images/fonts-windows-screen.png)

- Below, image showing CSS imports of the google fonts.

![image](/assets/images/fonts-in-css.png)

### Wireframes

The idea on how to design this website was through the wireframes I created using Microsoft Paint. As seen in the design plan, there has been adjustments in the number of images on the 'our work' page, the design of the footer and on the 'ask us' page, the form placement was replaced at the part which had been intended to hold the map. The idea of having the map in the page was entirely dropped.

![image](/assets/images/all-for-glass-design-plan.webp)

### Imagery

The images of this  were downloaded from [Pexels](https://www.pexels.com/) a free stock image site with high-quality photos. For quality perfomance of the page the images were reduced in size and their formats changed to WebP Image Format using an online free file/image converter [Convertio](https://convertio.co/)

![image](/assets/images/images%20used%20on%20the%20page.png)

### Icons

The icons used are from Font Awesome

- Facebook
- Youtube
- Instagram
- Whatsapp

For the tab window, the fav icon used is a windscreen image from [flaticon](https://www.flaticon.com/free-icon/windscreen_5382703) then generated using [Favicon](https://favicon.io/) to get the versions for different browsers.

## Pages and Features

### General Features

- All For Glass logolinks back to the index page, the home page.

- **Navigation bar** : Lies on the upper right corner for the screens that are 768px and above. For th  smaller screens, a hamburger menu emerges.
  - *Home* takes you back to the index page with which informs of what services the workshop (All for glass) offers.
  - *Our work* links to a page in form of images, showcasing the work done as the workshop.
  - *Ask us* links to a page with the contact details that offer different options on how to contact the workshop.

- **Footer** : The eye-catching, *We Strive For Quality* phrase only shown on screens with 768px and above, while the social media icons are visible on all screens. The intention is to link to the social media pages of *All for Glass*. However, in this case they link to the homepages of the social media platforms.

### Pages

#### Home page

On the home page (index page), the visitor is offered with information on the glazing and auto glass services offered at the workshop.

### Our work page

Information on this page is presented through images. The intention is to show the visitor of the website the kind of work done at *All for glass*. For example the image of the bathroom, is to show that at the workshop, you bathroom can be customised to your needs well as the broken car windscreen is to send a message on the works of auto glass repair.

#### Ask us page

On this page the user is offered a variety of options to contact the workshop. Both telephone and email details are availed, as well as a pysical address to the workshop. Also on this page the person can choose to send in an inquiry/message using a form. The future intention for this form is to separate glazing and auto glass inquiries where by certain fields emerge or get hidden depending on the type of inquiry/message a person wants to send in.

The pages have been designed to respond to different screens (As seen in the image on top of this read me). The website was designed with the mobile screen size as the primary focus since it's through the mobile phones that most people seek their information. Css was used for the website to behave difeetently on other screen sizes like the tablet, laptop and desktop.

## Technologies

### HTML and CSS

- GitHub for storing repository
- Codeanywhere for code editing

### Imagery

- [Convertio](https://convertio.co/) was used to convert images to webP files, the Microsoft Photos app for desktop to resize the images and the Microsoft Paint app for desktop design the logo and wireframes.

### Content

- [Font Awesome](https://fontawesome.com/start): to generate icons used on the page.
- [Favicon generator](https://favicon.io/): to generate the fav icon on the tab next to the title.
- [Google Fonts](https://fonts.google.com/): to find the fonts used on the page and to get the code to embed on the page.

## Accessibility

To ensure that the website is easily accessible, I have organised the content of the pages using sematic HTML elements, the *header*, *main*, *section* and *footer*.

For the pages to doenload faster, images have been resized while maintaining their quality. They have also been optimizsed from their original image formats to Webp image format which compresses images without changing their quality.

When is comes the images, I have give them a descriptive text under *alt* attribute to forexample help people with visiual impairment using screen readers or just in case an image fails to load.

## Deployment

The *All for Glass* website was deployed to [GitHub](https://github.com) pages, following these steps:

1. Go to the [all-for-glass repository](https://github.com/Edgarkimbugwe/all-for-glass)
2. Go to the *Settings* tab (top left in the menu)
3. Go to the left-hand section,under *Code and automation* click **Pages**.
4. Go to *Source* under *Build and deployment* and use the dropdown menu to choose **Deploy from a branch**
5. Under *Branch* use the dropdown menu to select **main** and set the *folder* to **root**.

The live site can be viewed at: [https://edgarkimbugwe.github.io/all-for-glass/](https://edgarkimbugwe.github.io/all-for-glass/)

## Testing and Validation

### Testing

- Testing of the website functionalities was performed on:
  - Laptop: Lenovo Thinkpad, Windows 10, running Chrome and Edge (1920x1080 monitor)
  - Samsung Galaxy S21, Android (6.1" diagonal)
  - Alcatel Tablet, Android (10.2" diagonal)