# All for glass

All for glass is website with an intention of showing the works of a glazing workshop in Sweden that is aimed to attract customers in need of glazing and auto car services.

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
    - [Validation](#validation)
      - [Home page](#home-page-1)
      - [Our work page](#our-work-page-1)
      - [Ask us page](#ask-us-page-1)
      - [HTML and CSS Validation](#html-and-css-validation)
  - [Credits](#credits)
    - [Code used](#code-used)
    - [Content](#content-1)
    - [Media](#media)
    - [Acknowledgement](#acknowledgement)

## Purpose and target audience

The purpose of All For Glass website is to attract as many customers  as possible within Sweden to seek the services of the workshop whose experince in the glass industry is second to none.

The services offered by the workshop are are within glazing and auto glass. By glazing, the customers can have their windows renovated from old glass to new glass on the market, design parts of their homes with glass, like in the bathrooms or even build glass walls. All this can be offered with the advise and planning between the customer and the workshop. In regard to auto glass, the website is intented to showcase to the cutomer that they are able to change any auto glass broken from any car.

## Design

### Color palette

To get matching designs of the colours used to the website, [Coolors](http://coolors.co/) was used. Also note that in the css values these colours were used with rgba values instead of hex values. the intention was to give them an opacity value directly in the color value when required.

![image](/assets/images/color-pallete.png)

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

The idea on how to design this website was through the wireframes I created using Microsoft Paint.

![image](/assets/images/all-for-glass-design-plan.png)

### Imagery

The images of this website  were downloaded from [Pexels](https://www.pexels.com/), a free stock image site with high-quality photos. For quality perfomance of the page the images were reduced in size and their formats changed to WebP Image Format using an online free file/image converter [Convertio](https://convertio.co/)

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

- All For Glass logo, links back to the index page which is the home page.

- **Navigation bar** : Lies on the upper right corner for the screens that are 768px and above. For the smaller screens, a hamburger menu emerges.
  - *Home* takes you back to the index page with information on what services the workshop (All for glass) offers.
  - *Our work* links to a page in form of images, showcasing the work done as the workshop.
  - *Ask us* links to a page with the contact details that offer different options on how to contact the workshop.

- **Footer** : The eye-catching, *We Strive For Quality* phrase only shown on screens with 768px and above, while the social media icons are visible on all screens. The intention is to link to the social media pages of *All for Glass*. However, in this case they link to the homepages of the social media platforms.

### Pages

#### Home page

On the home page (index page), the visitor is offered with information on the glazing and auto glass services offered at the workshop.

### Our work page

Information on this page is presented through images. The intention is to show the visitor of the website the kind of work done at *All for glass*. For example the image of the bathroom, is to show that your bathroom can be customised to your needs well as the broken car windscreen is to send a message on the works of auto glass repair.

#### Ask us page

On this page the user is offered a variety of options to contact the workshop. Both telephone and email details are availed, as well as a pysical address to the workshop. Also on this page the person can choose to send in an inquiry/message using a form. The future intention for this form is to separate glazing and auto glass inquiries where by certain fields emerge or get hidden depending on the type of inquiry/message a person wants to send in.

The pages have been designed to respond to different screens (As seen in the image on top of this read me). The website was designed with the mobile screen size as the primary focus since it's through the mobile phones that most people seek their information. Css was used for the website to behave differently on other screen sizes like the tablet, laptop and desktop.

## Technologies

### HTML and CSS

- GitHub for storing repository
- Codeanywhere for code editing

### Imagery

- [Convertio](https://convertio.co/) was used to convert images to webP files, the Microsoft Photos app for desktop to resize the images and the Microsoft Paint app for desktop design the logo and wireframes.

### Content

- [Font Awesome](https://fontawesome.com/start): to generate icons used on the page.
- [Favicon generator](https://favicon.io/): to generate the fav icon on the tab next to the title.
- [Google Fonts](https://fonts.google.com/): to find the fonts used on the page and to the code to embed on the page using css.

## Accessibility

To ensure that the website is easily accessible, I have organised the content of the pages using sematic HTML elements, the *header*, *main*, *section* and *footer*.

For the pages to download faster, images have been resized while maintaining their quality. They have also been optimizsed from their original image formats to Webp image format which compresses images without changing their quality.

When it comes the images, I have give them a descriptive text under *alt* attribute to for example help people with visiual impairment using screen readers or just in case an image fails to load.

## Deployment

The *All for Glass* website was deployed to [GitHub](https://github.com) pages, following these steps:

1. Go to the [all-for-glass repository](https://github.com/Edgarkimbugwe/all-for-glass)
2. Go to the *Settings* tab (top left in the menu)
3. Go to the left-hand section, under *Code and automation* click **Pages**.
4. Go to *Source* under *Build and deployment* and choose **Deploy from a branch** from the dropdown menu.
5. Under *Branch*, select **main** and set the *folder* to **root**.

The live site can be viewed at: [https://edgarkimbugwe.github.io/all-for-glass/](https://edgarkimbugwe.github.io/all-for-glass/)

## Testing and Validation

### Testing

- Testing of the website functionalities was performed on:
  - Laptop: Lenovo Thinkpad, Windows 10, running Chrome and Edge (1920x1080 monitor)
  - Samsung Galaxy S21, Android (6.1" diagonal)
  - Alcatel Tablet, Android (10.2" diagonal)

### Validation

#### Home page

When images on the home page were reduced in size and changed from their original formats to Webp image format, the pages perfomance was improved tremendously.

![image](/assets/images/index-page-anaylsis.png)

#### Our work page

The same changes applied to the images on the home page were carried out on this page.

![image](/assets/images/our-work-page-analysis.png)

#### Ask us page

On this page, it was identified that two elements had been given the same id attiribute instead a class attribute. This was rectified and too, tremendously improved the page.

![image](/assets/images/ask-us-error2.png)

![image](/assets/images/ask-us-page-analysis.png)

#### HTML and CSS Validation

To validate both the HTML and CSS for the website, W3C's CSS and Markup Validation Services where used and after changes made on errors that had been identified. The page was no errors for both html and css.

![image](/assets/images/css%20validation.png)

![image](/assets/images/html%20validation.png)

## Credits

### Code used

- The Navbar on this website was inspired from the code for the Love Running project - CodeInstitute.
  
  ![image](/assets/images/navbar-loverunning-project.png)

### Content

The web site is meant for a fictional workshop, however the content is inspired by my work experience as a glazier.

### Media

- [flaticon](https://www.flaticon.com/free-icon/windscreen_5382703) was used to find a the icon to be used in the window tab as a favicon
- [Favicon generator](https://favicon.io/): to generate the fav icon on the tab next to the title.
- [Google fonts](https://fonts.google.com) was used to find matching fonts for the website.
- [Pexels](https://www.pexels.com/) was used for the images on the website, Microsoft Photo app to edit them and to covert the to a Webp image format, [Convertio](https://convertio.co/) was used.
- [Colormind](http://colormind.io/bootstrap>) was used to find colors matching for the design of the website.
- Knowledge gained from the *Love Running - Essentials Project* by [Code Institute](https://codeinstitute.net/se/) was so invaluable in designing this website.

### Acknowledgement

Lastly, I am thankful to my mentor at Code institute, *[Spencer Barriball](https://github.com/5pence)*, for the insightful guidance and feedback all through this project.
