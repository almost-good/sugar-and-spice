# Sugar and Spice
**Sugar and Spice** is a company that makes custom made-candles, includes its customers in the entire development process and offers a deeply personalized experience. The website is targeted toward people that are interested in the purchase of custom-shaped candles containing specific or random scent mixtures.

Sugar and Spice, or *SaS*, features a "recipe" on how to order a candle, as it is not a modern webshop but takes more traditional approach where, depending on the needs, the customer is presented with the **price quote**.
Users can also view all essential oils available for candle mixtures, a bit of information about them, and the most popular scents which are updated monthly.
Lastly, the site includes a gallery of previous works done, which can be used as inspiration for coming up with new interesting candle shapes.

View live site here - [Sugar and Spice](https://almost-good.github.io/sugar-and-spice/index.html)
<br><br>
![Responsive Site](assets/docs/images/am-i-responsive.jpg)
<br><br>


## **Table of Contents**

- [Developer's Note](#developers-note)
- [UX - User Experience Design](#ux-user-experience-design)
  - [Business Objectives](#business-objectives)
  - [User Stories](#user-stories)
- [Visual Design](#visual-design)
  - [Initial Concept](#initial-concept)
  - [Wireframes](#wireframes)
  - [Colour Scheme](#colour-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
- [Features](#features)
  - [Existing Features](#existing-features)
  - [Features Left to Implement](#features-left-to-implement)
- [Testing](#testing)
  - [Devices and Browsers](#devices-and-browsers)
  - [Validators](#validators)
  - [Feature Testing](#feature-testing)
  - [User Story Testing](#user-story-testing)
- [Bugs](#bugs)
- [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Tools](#tools)
  - [For Testing](#for-testing)
- [Deployment](#deployment)
- [Credits](#credits)
  - [Content](#content)
  - [Images](#images)


## **Developer's Note**
Sugar and Spice project is created as a **Portfolio Project** for Code Institute Full Stack Software Developer program.
The project showcases my skills in HTML and CSS, which I acquired as a Code Institute student.

Please **note:** This website is purely fictional, and the company in question does not exist. Although I enjoy candles myself, I am in no way an expert, *so I would advise against using this site as a primary reference for candle-related information*.

Back to [Table of Contents](#table-of-contents)


## **UX, User Experience Design**


### **Business Objectives**
As the business:
1. We want to attract customers with our modern design.
2. We want an accessible website for any of our potential customers.
3. We want to clarify what the customer can expect from us.
4. We want to help the customer find the perfect scent for them by providing them with information about the different scents we offer.
5. We want to show the customer portfolio of our previous work.
6. We want to make the ordering process simple for the customer.
7. We want to get an order from the customer.

### **User Stories**
As a user:
1. I want to have a clear sense of what the site is about.
2. I want to be able to easily navigate the site and in an intuitive way.
3. I want to interact with a page in a way that I am already accustomed to.
4. I want to be able to view the site on a device of my choosing.
5. I want to know what I should do to do to order a candle.
6. I want to know what kind of product I can expect.
7. I want to check out what kind of candle scents they are currently offering.
8. I want to check out which scents are most popular.
9. I want to educate myself in regard to different scents and see what they are about.
10. I want to see what kind of candles they have already done.
11. I want to be able to contact site owners so I can get more information or make an order.

Back to [Table of Contents](#table-of-contents)


## **Visual Design**


### **Initial Concept**

### **Wireframes**
Wireframes are created using **Balsamiq** for organizational purposes. They were used for the initial concept only. The final product contains some design differences but still remain heavily influenced by the initial concept.
<br><br>
  
![Home-Desktop View Wireframe](assets/docs/wireframes/home-desktop.png)
<br><br>

You can find all wireframes here:
- **Desktop View**
  - [Home](assets/docs/wireframes/home-desktop.png)
  - [Scents Page](assets/docs/wireframes/scents-desktop.png)
  - [Gallery Page](assets/docs/wireframes/gallery-desktop.png)
  - [Contact Page](assets/docs/wireframes/contact-desktop.png)
- **Tablet View**
  - [Home](assets/docs/wireframes/home-tablet.png)
  - [Scents Page](assets/docs/wireframes/scents-tablet.png)
  - [Gallery Page](assets/docs/wireframes/gallery-tablet.png)
  - [Contact Page](assets/docs/wireframes/contact-tablet.png)
- **Mobile View**
  - [Home](assets/docs/wireframes/home-mobile.png)
  - [Scents Page](assets/docs/wireframes/scents-mobile.png)
  - [Gallery Page](assets/docs/wireframes/gallery-mobile.png)
  - [Contact Page](assets/docs/wireframes/contact-mobile.png)
  - [Navigation](assets/docs/wireframes/navigation-mobile.png)
 
### **Colour Scheme**
The design for the site is modern, with a deep, dark background and occasional pop of color used to brighten the overall experience.
<br><br>
![Color-Wheel](assets/docs/images/color-wheel.png)
<br><br>

### **Typography**
There are three different font styles used on the page. **Open Sans** was selected for most of the page due to its readability, **League Gothic** for significant headings and **Pacifico** for notable little highlights. I also included websafe fallback fonts, followed by the generic fonts.

Back to [Table of Contents](#table-of-contents)


## **Features**


### **Existing Features**
- **Features shared between all pages:**
  - **Navigation**
    - Fully responsive navigation bar placed horizontally for desktop and tablet devices. For a mobile view, the navigation links are accessed through a hamburger menu in the vertical direction.
    - The navigation bar is in a fixed position, always visible to the user, ensuring easy access to different parts of a site.
    - The navigation bar features Sugar and Spice logo and navigational links.
    - Navigational links direct customers to:
      - Home page
      - Scents page
      - Gallery page
      - Contact page
    - ![Navigation](assets/docs/images/features-navigation.jpg)
  - **Footer**
    - SaS dedicated footer to their developer, aka me.
    - Footer is placed at the bottom of the site and includes Copyrights and the developer's social media links, GitHub and LinkedIn.
    - ![Footer](assets/docs/images/features-footer.jpg)
- **Home Page**
  - **Header**
    - Header contains the title of the page together with two different calls to action.
    - 1st CTA is targeted towards the site's main function which is the sale of the product. The user is able to get in touch with SaS experts and order a candle.
    - 2nd CTA links to the different Aroma types, just below, so the user can check out the different essential oils we are using in our blends.
    - Header is designed so the user can immediately order products or continue exploring the site.
    - ![Header](assets/docs/images/features-header.jpg)
  - **Aroma List Section**
    - The Aroma List Section includes three stunning images of the different aroma types available on website.
    - This section shows users what types of fragrance we have available and it invites them to read more about each one.
    - ![Aroma List](assets/docs/images/features-aroma-list.jpg)
  - **Order Recipe Section**
    - Order Recipe Section contains step-by-step instructions on how to order a product. Each step opens the door to more exploration, with the last inviting the user to purchase the product.
    - This section is very important because it prompts the user to investigate what would be best for them so that we can make an outstanding product for them.
    - ![Order Recipe](assets/docs/images/features-recipe.jpg)
  - **Expectation Section**
    - This section lists product and delivery information, service expectation etc.
    - This is valuable information for the user and will help them to decide if the SaS products fit their needs.
    - The end of this section features the final call-to-action, redirecting the user to the contact page to purchase the product.
    - ![Expectation](assets/docs/images/features-expectation.jpg)
- **Scents Page**
  - **Top Picks Section**
    - Top Picks Section showcases the most popular scents from each group of fragrances. This section is updated every month.
    - It's constructed as a grid of images with a different layout for mobile, tablet and desktop devices. Each grid item has its name displayed, enabling the user to differentiatebetween different aromas.
    - Grid items have two different states.
      - During the first state, they display the image of aroma type.
      - Second state, the focused one, displays the name of the aroma type.
    - ![Top Picks](assets/docs/images/features-top-picks.jpg)
  - **Something More Section**
    - The Something More Section is an introductionary section with the purpose of prompting the user to read the list containing all the available fragrances.
    - ![Something More](assets/docs/images/features-something-more.jpg)
  - **Aroma Types Section**
    - The Aroma Types Section contains four different aroma types, with their general descriptions and traits, together with an extensive list of every fragrance available to choose from. 
    - All aroma types are interlinked, allowing for easy navigation between them.
    - ![Aroma Type](assets/docs/images/features-aroma-type.jpg)
- **Gallery Page**
  - Gallery Page is used for showcasing the previous work done by the Sugar and Spice company.
  - Images follow a specific layout, so the final look is coherent.
  - Mobile layout has been adjusted so the images can remain visible on smaller devices.
  - ![Gallery](assets/docs/images/features-gallery.jpg)
- **Contact Page**
  - Contact Page is the final page of the site. It enables users to get in touch with our experts, whether they seek more information regarding the products or wish to buy them.
  - Contact Page features a standard contact form, including the name, email and content fields.
  - ![Contact Page](assets/docs/images/features-contact.jpg)

### **Features Left to Implement**
- Enable effect when user closes hamburger menu for the removal of the navigation links. The effect should be the same sliding animation as the one that shows up when the user opens the hamburger menu.

Back to [Table of Contents](#table-of-contents)


## **Testing**


### **Devices and Browsers**

### **Validators**
- [W3C Markup](https://validator.w3.org/nu/)
  - Completed with no errors for each page.
  - ![Marukup Validation Result](assets/docs/images/w3c-markup.jpg)
- [W3C CSS](https://jigsaw.w3.org/css-validator)
  - Completed with no errors.
  - There are 6 warnings present due to the use of css variables, and 4 more due to scrollbar styling.
  - ![Css Validation Result](assets/docs/images/w3c-css.jpg)


### **Feature Testing**

### **User Story Testing**
Back to [Table of Contents](#table-of-contents)


## **Bugs**
Back to [Table of Contents](#table-of-contents)


## **Technologies Used**


### **Languages**
- HTML5 - Used for markup.
- CSS3 - Used to provide styling.
- [JS](https://www.javascript.com) - Used for navigation.

### **Tools**
- [VScode](https://code.visualstudio.com) - Used as the IDE.
- [Git](https://git-scm.com/) - Used for version control.
- [GitHub](https://github.com) - Used for code hosting.
- [Balsamiq](https://balsamiq.com) - Used to create wireframes.
- [Google Fonts](https://fonts.google.com) - Used for fonts.
- [Font Awesome](https://fontawesome.com) - Used for icons.
- [Photoresizer](https://www.photoresizer.com) - Used to resize the imgages and to compress them.
- [Adobe Express](https://www.adobe.com/express/create/logo) - Used to create logo.
- [Colormind](http://colormind.io) - Used to create color palette.
- [Am I Responsive](https://ui.dev/amiresponsive) - Used to create website showcase photo on top of the README.

### **For Testing**
- [W3C Markup](https://validator.w3.org/nu/) - Used for markup validation.
- [W3C CSS](https://jigsaw.w3.org/css-validator) - Used for CSS validation.

Back to [Table of Contents](#table-of-contents)


## **Deployment**


The steps to deploy using GitHub pages are:

- Go to the repository on [GitHub](https://github.com).
- Select 'Settings' close to the top of the page.
- Select 'Pages' from the left menu bar.
- Under 'Source' select the 'Branch' dropdown menu and select the **main branch**.
- Once selected, click the 'Save'.
- Deployment will be confirmed by a message saying "Your site is live at" followed by the web address.


Back to [Table of Contents](#table-of-contents)


## **Credits**


### **Content**
All Essential Oil content was sourced from [Sea Cliff Hemp NY](https://seacliffhempny.com) & [New Directions Aromatics](https://www.newdirectionsaromatics.com).

### **Images**
All images used were sourced from following sites:
- [PXfuel](https://www.pxfuel.com/en/photos)
  - **Home page**
    - [Orange basket](https://www.pxfuel.com/en/free-photo-emaus)
- [Unsplash](https://unsplash.com)
  - **Home page**
    - [Red roses](https://unsplash.com/photos/dt8Q85QOxJM)
    - [Foggy pine forest](https://unsplash.com/photos/OYFHT4X5isg)
  - **Scents page**
    - [Jasmine flower](https://unsplash.com/photos/vkybvOiDqr0)
  - **Gallery page**
    - [Miniature candle](https://unsplash.com/photos/lV_1--cFJWo)
- [Pexels](https://www.pexels.com)
  - **Scents page**
    - [Juniper berries](https://www.pexels.com/photo/unripe-berries-and-green-leaves-11429854)
    - [Chamomile field](https://www.pexels.com/photo/cluster-of-daisies-699964)
    - [Lavender flower](https://www.pexels.com/photo/selective-focus-photo-of-purple-petaled-plant-1381683)
    - [Lemon branch](https://www.pexels.com/photo/shallow-focus-photography-of-yellow-lime-with-green-leaves-129574)
    - [Geranium flower](https://www.pexels.com/photo/close-up-of-flowers-on-green-plant-5625901)
    - [Lemongrass](https://www.pexels.com/photo/close-up-photo-of-lemongrass-6021461)
    - [Pine branches](https://www.pexels.com/photo/green-pine-tree-12822973)
    - [Orange branches](https://www.pexels.com/photo/orange-fruit-on-tree-3804878)
    - [Roses](https://www.pexels.com/photo/red-roses-1187079)
    - [Tangerine branch](https://www.pexels.com/photo/close-up-of-an-orange-on-a-tree-14766943)
    - [Lime branch](https://www.pexels.com/photo/key-lime-growing-in-garden-8236016)
  - **Gallery page**
    - [Bubble candle](https://www.flickr.com/photos/67865224@N06/45700299704)
    - [Body candle](https://www.flickr.com/photos/67865224@N06/45700299704)
- [Flickr](https://www.flickr.com)
  - **Scents page**
    - [Cedarwood branch](https://www.flickr.com/photos/bambolia/5303050738)
    - [Citronella flower](https://www.flickr.com/photos/susanchaffin/5596428956)
    - [Cypress bud](https://www.flickr.com/photos/149505955@N06/46215502804)
    - [Neroli flower](https://www.flickr.com/photos/easygiving/4025469058)
    - [Sandalwood branches](https://www.flickr.com/photos/saltys_place/5989777724)
  - **Gallery page**
    - [Tree candle](https://www.flickr.com/photos/67865224@N06/45700299704)
    - [Charmander candle](https://www.flickr.com/photos/pokemon4u/8391221832)
- [PXhere](https://pxhere.com)
  - **Gallery page**
    - [Dripping red candle stick](https://pxhere.com/en/photo/817721)
    - [Angel candle](https://pxhere.com/en/photo/374487)
    - [Winged heart candle](https://pxhere.com/en/photo/1024272)
- [Wikimedia Commons](https://commons.wikimedia.org/wiki/Main_Page)
  - **Gallery page**
    - [Egg candle](https://commons.wikimedia.org/wiki/File:Egg_candles_%287099864271%29.jpg)

Back to [Table of Contents](#table-of-contents)