# City Cake

City Cake is a site that is developed to provide ease of access to users/ customers who love fresh and delicious homemade cakes. Customers can access and check the products and place orders with few clicks. It also benefits the owner of City Cake Shop to show his/her products and target more customers and meet their requests.

![Responsice Mockup](/assets/docs/mockup.png)

---
## User Stories

### First Time Visitor Goals:

* As a First Time Visitor, I want to easily understand the main purpose of the site, so I can learn more about the organization.
* As a First Time Visitor, I want to be able to easily navigate through the website, so I can find the content.
* As a First Time Visitor, I want to see the testimonials, so I can see whether the organization is trustworthy.

### Returning VisitorGoals:

* As a Returning Visitor, I want to see various cakes, so that I can pick from.
* As a Returning Visitor, I want to see information about different cakes, so that I can learn about each cake and make a prudent decision.
* As a Returning Visitor, I want to find a way to get in contact with the organization, so that I can ask additional questions or order a particular cake.
* As a Returning Visitor, I want to find community links, so that I can learn more about the organization.

### Frequent Visitor Goals:
* As a Frequent User, I want to check whether there are any changes with available cakes, so I can make a choice which cake to order.
* As a Frequent User, I want to have options for the reason to contact the organization, so I can get an explicit answer to my email. 

---
## Features

+ ### Navbar

+ ##### Navigation
    - Positioned at the top of the page.
    - Contains logo of the company on the left side.
    - Contains navigation links on the right side:
        * HOME - leads to the home page where users can learn about the City Cake Shop.
        * About - leads to about section where users can learn about the especiality of City Cake Shop.
        * Product - leads to the product section where users can see available cakes in the City Cake Shop.
        * Order - leads to the order page where users can place order with the City Cake Shop.
        * CONTACT - leads to the contact section where users can get in touch with the company through socail media links.
    - The links have animated hover effect.
    - The navigation is clear and easy to understand for the user.
    ![NavBar desktop](/assets/docs/navbar_desktop.png)

    - The navigation bar is responsive:
        * On tablet and mobile: navigation bar collapse like an hamburger on the right side and logo shifts to the center. 
        ![NavBar Tablet and Mobile](/assets/docs/navbar_tablet%26mobile_close.png)

        - When the hamburger menu is clicked, there is dropdown menu with the links in the same order.
            ![NavBar Table and Mobile Open](/assets/docs/navbar_tablet%26mobile_open.png)

---

+ ### Home Page

    - Represents: 

        * the main idea of the company.
        * Emphasizes the strong points of the company.
        * Shows product of the company.
        * Invites to place order with the company.
        * Provides social media links to contact with the company.

    ![Home Page](/assets/docs/home_page.png)

---
+ #### Hero Section

  - Hhe landing includes a photograph to allow the user to see exactly what kind of cakes the City Cake offers. 
  - This section introduces the user to City Cake with an eye catching animation to grab their attention.
    
    ![Hero Section](/assets/docs/hero_image.png)

---

- __About Us Section__

  - The About Us section will introduce the user the speciality of City Cake and allow to see different kinds of cakes it offers. 
  - The user will see the baking style used by City Cake and encourage them to taste the homemade fresh and delicious cakes. 

![About Us](/assets/images/City_cake_about.png)

- __Product section__

  - This section will allow the user to see exactly the types of cakes offered by City Cake for different variety of occasions. 
  - This section will be updated regularly to keep the user up to date and meet their demands. 
  - This section will provide the user with an easy link to place order besides having the possibility in the navigation bar as well.

![Product](/assets/images/City_cake_product.png)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for City Cake. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media.

![Footer](/assets/images/City_cake_footer.png)


- __The Order Page__

  - This page will allow the user to place order with City Cake. The user will provide the details of the request in a more simple and clear way by selecting the dropdown required options. Optionally, the user can also upload photos of the request and put any further remarks.
  - For data integrity each field is fitched with data types to check and control the correctness of data entered by the user.

![Order](/assets/images/City_cake_form.png)

This site is developed with the use of HTML and CSS with a minor coding of JavaScript for product page swiper. The site contains the full functionality front-end of a web with a better user experience by adopting different screen sizes.

- __The Order Response Page__

  - This page aknowledge and confirm the user request with a thank you message. 

![Order](/assets/images/City_cake_form_response.png)

### Features Left to Implement

- As this site is static, further enhancements and features are required to interact, get and process the user data.
- Further features to implement are:
  - Include the product ingredients and price
  - Filtering options
  - Add shopping cart
  - Add review page
  - Store the user data in a database
  - Secure credit card payment process

## Testing 

- This site is checked for any potential error in different browers and in different screen sizes. 
- Google chrome lighthouse is used to check and generate a comprehensive report regarding the site's performance, accessibility, best practices and SEO with taking both mobile and desktop view into consideration and and all rated above 90%. 

![Lighthouse report desktop view](/assets/images/Lighthouse_report_desktop_view.png)
![Lighthouse report mobile view](/assets/images/Lighthouse_report_mobile_view.png)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official ![W3C validator](/assets/images/W3C%20Validator.png)
- CSS
  - No errors were found when passing through the official ![(Jigsaw) validator](/assets/images/(Jigsaw)%20validator.png)

### Unfixed Bugs

- The background images were not displaying in Github live site view. The issue was fixed by using relative file paths.


## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://ahmad-hazrati.github.io/PP1/index.html


## Credits 

- Thanks to my Code Institute mentor Mr. Aleksei Konovalov for his guidance, insight and the constant confidence boost to help me in the right direction.

- Thanks to Slack community for general references, support and encouragement received. 

- The overall project idea and concept is taken from [Love Running Project](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode)
- - Instructions on coding of response navigation bar without JavaScript are taken from [Kevin Powell Youtube Tutorial](https://www.youtube.com/watch?v=8QKOaTYvYUA/)
- Instructions on JavaScript coding for swiper of product section are taken from [UIUX - Din Art's](https://www.youtube.com/watch?v=2vdjN8HILrc&t=56s)
- The form contents are taken from [Jotform](https://www.jotform.com/)
- W3C and Jigsaw Validators are used to check the HTML and CSS files for any errors.

### Content 

- Instructions on coding of response navigation bar without JavaScript are taken from [Kevin Powell Youtube Tutorial](https://www.youtube.com/watch?v=8QKOaTYvYUA/)
- Instructions on JavaScript coding for swiper of product section are taken from [UIUX - Din Art's](https://www.youtube.com/watch?v=2vdjN8HILrc&t=56s)
- The form contents are taken from [Jotform](https://www.jotform.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- The fonts used in the site are taken from [Google Fonts](https://fonts.google.com/)

### Media

- The background images used in home, order and order response pages are from [Freepik](https://www.freepik.com/)
- The images used for the about and product sections are taken from [Google Images ](https://www.google.com/)