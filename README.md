# everydayonline

everydayonline is a e-commerce store built using Pythons Django framework, and hosted using Heroku.
The main function of the app is to allow users to browse the range of products and buy which they 
see fit. Users can also add, edit and delete their own products but wont be-able to affect products
posted by other users.

## Table Of Contents
[UX](#user-experience-(ux)) || [User Stories](#user-stories) | [Design](#design)

[Features](https://github.com/joenapper/everydayonline/blob/master/FEATURES.md) || Features table of contents can be found in separate [FEATURES.md](https://github.com/joenapper/everydayonline/blob/master/FEATURES.md) file.

[Technologies Used](#technologies-used) || [Languages](#languages-used) | [Libraries](#libraries-used) | [Tools](#tools-used) | [Databases](#databases) | [Hosting](#hosting)

[Testing](#testing) || [Code Validation](#code-validation) | [Testing User Stories](#testing-user-stories-from-user-experience-(ux)-section) | [CRUD Testing](#crud-testing) | [Further Testing](#further-testing)

[Deployment](#deployment) 

[Credits](#credits) || [Content](#content) | [Media](#media) | [Acknowledgements](#acknowledgements)

## User Experience (UX)
- ### User Stories
    - #### First Time Visitor Goals
        1. As a First Time Visitor, I want to understand the purpose of the site.
        2. Also, I want to easily find products to buy.
        3. Also, I want to easily navigate through the site.
        
    - #### Returning Visitor Goals
        1. As a Returning Visitor, I want to see my previous orders.
        2. Also, I want a way to save details to checkout faster.
        3. Also, I want to create my own account.
        4. Also, I want to add my own products.

    - #### Frequent User Goals
        1. As a Frequent User, I want to see newly added products.
        2. Also, I want to be made aware of new deals and special offers.
        3. Also, I want to edit and delete my own products.

- ### Design
    - #### Bootstrap 4
        - Bootstrap is a CSS framework that was used to build this app. 

    - #### Layout
        - The everydayonline app uses the Bootstrap 4 framework which I used throughout the site to keep the
        design / layour the same by utilising Bootstraps built-in classes. By using the row and column classes,
        I was easily able to quickly put together a simplistic yet professional looking layout without having 
        too add much(if any) custom CSS.

    - #### Icon Set
        - Font Awesome has been used throughout the project, across all sections, ranging from icons in the 
        nav bar through to the checkout page and everything in between. These icons are built into the Bootstrap
        framework and really help illustrate the page.

    - #### Database
        - Django uses SQL databases. During development, the Django default sqlite3 database was used. When deployed 
        to Heroku, a PostgreSQL database was used.

## Features
**Note:** All Features Information can be located in the separate [FEATURES.md](https://github.com/joenapper/everydayonline/blob/master/FEATURES.md) due to the length of content.

## Technologies Used
- ### Languages Used
    - [HTML5](https://en.wikipedia.org/wiki/HTML5)
    - [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
    - [JavaScript](https://en.wikipedia.org/wiki/JavaScript)
    - [Python](https://en.wikipedia.org/wiki/Python_(programming_language))

- ### Libraries Used
    - [Bootstrap:](https://getbootstrap.com/)
        - Bootstrap provided the CSS framework which made it easy to keep the site looking consistent throughout.
    - [Font Awesome:](https://fontawesome.com/)
        - Font Awesome was used to help illustrate various sections of the site by adding icons.
    - [jQuery:](https://jquery.com/)
        - jQuery was used for many things but mainly worked with Bootstrap to enhance some of it features.
    - [Django:](https://www.djangoproject.com/)
        - Django is the Python framework used to power the app itself.

- ### Tools Used
    - [Figma:](https://www.figma.com/)
        - Figma was used to create the wireframes during the design process.
    - [Kaggle:](https://www.kaggle.com/)
        - Kaggle was used to prune the dataset and easily aquire assets.
    - [Stripe:](https://stripe.com/gb)
        - Stripe was used to accept payments when users checkout.
    - [Photoshop:](https://www.adobe.com/ie/products/photoshop.html)
        - Photoshop was used to create 'README-assets' images. 
    - [Web Formatter:](https://webformatter.com/)
        - Web Formatter was used to beautify code to keep everything neat and improve readability. 
        - This can also be done by utilizing Beautify Cmd (Shift + Alt + F) in GitPod.
    - [Grammarly:](https://app.grammarly.com/)
        - Grammarly was used at the end to correct any spelling/grammar mistakes. 
    - [Jasmine:](https://jasmine.github.io/)
        - Jasmine was used to test the JavaScript before Implementing It into the website.
    - [Git:](https://git-scm.com/)
        - Git was used for version control by utilizing the Gitpod terminal to commit to Git and push to GitHub.
    - [Gitpod:](https://www.gitpod.io/)
        - Gitpod was the IDE used throughout the entirety of the project. 
    - [GitHub:](https://github.com/)
        - GitHub is used to store the project's code after being pushed from Git.

- ### Databases
    - [SQLite3:](https://www.sqlite.org/index.html)
        - SQLite3 is the default Django database, used during development.
    - [PostgreSQL:](https://www.postgresql.org/)
        - PostgreSQL is the production database, provided by, and deployed to Heroku.

- ### Hosting
    - [Heroku:](https://www.heroku.com/)
        - Heroku was used to deploy the final version of the site.

## Testing
- ### Code Validation
    - #### HTML
        - [W3C HTML Validator](https://validator.w3.org/)
            - All HTML was passed through the HTML validator. Outside of errors thrown due to using the Django templating 
            language, which are unavoidable given the nature of the project, everything came back fine.

    - #### CSS
        - [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
            - The W3C CSS Validator was used to validate the CSS page to ensure there were no syntax errors in the document.

    - #### JavaScript
        - [JSHint](https://jshint.com/)
            - The JavaScript files were run through JSHINT and apart from a few missed semicolons (which were rectified), 
            no errors displayed.

    - #### Python
        - [Python](http://pep8online.com/)
            - The Python script was checked using pep8online and is fully PEP8 compliant with zero errors or warnings.

- ### Testing User Stories from User Experience (UX) Section
- #### First Time Visitor Goals
    As a First Time Visitor...
    - I want to understand the purpose of the site.
        - On entry of the site the user can clear see the background image of a women shopping with the caption "THE NEW COLLECTIONS 
        ARE HERE!" and a "SHOP NOW" button... clearly showing its a online store.
    - I want to easily find products to buy.
        - On the home page theirs a search bar which can be used to search anything the user wants to fine. Not only that but the 
        nav-bar contains links to all the different categories available on the site.
    - I want to easily navigate through the site.
        - The site uses a sticky header which always keeps the navbar at the top of the users screen. This means the user can never get
        trapped on the page. Also, there is an arrow at the bottom of the screen which acts as a 'back to top' button so the user can
        return to the page of the page whenever they want without having to scroll.

- #### Returning Visitor Goals
    As a Returning Visitor...
    - I want to see my previous orders.
        - Everytime an order is made, the user will be asked to provide an email address. After the items have ben purchased, a comfirmation 
        email is sent to that address where the user can alwyas go back to and see what they bought. Not only that but, as a member of the 
        site, the users previous orders are saved my default in the 'My Profile' section as an easy way to see previous orders.
    - I want a way to save details to checkout faster.
        - The user can save there details to make check out faster by creating there own account on the site and adding there details to the
        'My Profile' section. This will save there details and use the information to populate the checkout page for the next purchase.
    - I want to create my own account.
        - We make it easy for users to create an account on our website. On the navbar, theirs a 'My Account' button (and icon) that the user can 
        click which then gives options to sign in or create an account. From here the user can easily create an account, verify it and enjoy as
        a member.
    - I want to add my own products.
        - As a member of the site, users have access to the 'Product Management' button which will redirect them to a page where they can add
        there own product, along with a description, price and image amongst other things.

- #### Frequent User Goals
    As a Frequent User...
    - I want to see newly added products.
        - All product pages on the site are set to display newest added first. Even if the user uses filters, for example 'By Price', and two
        different products have a price of '$9.99', the newest added product will display first. Therfor, the user will always see the most
        recent products first.
    - I want to be made aware of new deals and special offers.
        - We help promote any deals and/or special offers by making it clear on the site of what sales are currently on. At the moment, we have
        a tab of the navbar that links to 'Special Offers' so the user can see whats on offer. 
    - I want to edit and delete my own products.
        - As a member we allow users to add and sell there own products on the site using the 'Product Management' section. We also allow Users
        to edit these products and even remove them if necessary. This can be done by searching for your added product and selecting the edit or
        delete buttons. Note this can only be done for products that the user added - not any product.

- ### CRUD Testing
    - Create
        - I tested the create functionality of the website by using the 'Product Management'(My Account > Product Management) form. This form allows
        users to add there own product. Using this form, I copied the information from a product already inside the database and clicked the 'Add Product'
        button. I then went to the site admin page and checked the information i just added was displaying the same way as the copied product.
    - Read
        - The read functionality was testing using for loops to display all the products in the database and then from there, all the information linked
        to that specific product. This was made more aesthetically pleasing using CSS and displayed in a more professional manner. On the main page, I only 
        displayed the product image, name, price, rating and category so I could display more products on the page and keep everything looking good. If the user 
        was interested in the product and wanted more information, they can click the anywhere on the products 'card', and all the information will be displayed. 
    - Update
        - The update functionality was tested by adding an 'Edit' button to each product. I would deliberately add a new product with a spelling mistake and then 
        use the edit button to correct the mistake. I would then go back to the product page and make sure the changes were successful and double check inside the
        database.
    - Delete
        - The delete functionality was tested by adding clones of a product to the database and then using the 'Delete' button on that specific product to make sure 
        they were being removed. I used duplicate products to make sure I wasn't deleting any valuable information from the database. There is also a validation 
        step to the delete process where the user has to click that they are sure they want to delete. I did this just to make sure the user didn't click the button 
        by accident and end up deleting something that they didn't want to.

- ### Further Testing
    - The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge, Firefox and Safari browsers. 
    - The website was viewed on a variety of devices such as Desktop, Laptop, Samsung Galaxy S7, Samsung Galaxy S10, iPhone 5, iPhone 6s & iPhone X.
    - A large amount of testing was done to ensure that everything rendered and linked correctly on all browsers and a wide variety of devices.
    - All JavaScript and jQuery code was tested in a separate workspace using Jasmine and the Jasmine-JQuery plugin before importing it into the project. 
    - Friends and Family members were asked to review the site and report feedback on any bugs and/or user experience issues/negative experiences.

## Deployment
- ### Heroku
    - The site was deployed to [Heroku](https://www.heroku.com/) using the following steps...


