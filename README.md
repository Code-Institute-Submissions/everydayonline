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

[Deployment](#deployment) || [Local Deployment](#local-deployment) | [Deploying To Heroku](#heroku) 

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
    - [Temp-mail:](https://temp-mail.org/)
        - Temp-mail was used to test the automated emails, account sign-up/verification and reset password
        emails amongst others.
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
- ### Local Deployment
The following instructions are based on the user running GitPod on Windows 10. If your IDE / OS is different, your commands may differ slightly, 
but the process remains the same.

You will need the [Code-Institute-Org/gitpod-full-template](https://github.com/Code-Institute-Org/gitpod-full-template) and the 
[GitPod browser extension](https://www.gitpod.io/docs/browser-extension/) installed on your machine. You will also need the newest version of Python and
pip3 which should come pre-built into the gitpod full template. Having your own GitHub account is also highly recommended.

The following steps will allow you to deploy locally:

- Head over to the project repo at [https://github.com/joenapper/everydayonline](https://github.com/joenapper/everydayonline) and click the 'GitPod' button in 
the top right corner. This should automatically download all the files and open them in your own workspace.
- Install any required modules with pip3 install -r requirements.txt
- Head over to the 'settings.py' file in the project root and set up the required local environment variables, like below(make sure 'os' is imported).

    - (import os)
    - os.environ.setdefault("SECRET_KEY", "<Enter Your Django Secret Key here")
    - os.environ.setdefault("HOST_NAME", "127.0.0.1")
    - os.environ.setdefault("DEBUG", "1")

    - email
    - os.environ.setdefault("EMAIL_ADDRESS", "<Email Address App Will Use To Send Emails")
    - os.environ.setdefault("EMAIL_HOST_PASS", "<Password For Above Email Address>")
    - os.environ.setdefault("EMAIL_HOST_USER",  "<Your outgoing mail server")
    - os.environ.setdefault("EMAIL_PORT",  "<Your smtp port>")

    - stripe keys
    - os.environ.setdefault("STRIPE_PUBLIC_KEY", "<Enter Your STRIPE_PUBLIC_KEY value here>")
    - os.environ.setdefault("STRIPE_SECRET_KEY", "<Enter Your STRIPE_SECRET_KEY value here>")
    - os.environ.setdefault("STRIPE_WH_KEY", "<Enter Your STRIPE_WH_KEY value here>")

- **Note:** When deploying locally, there is no need to set up AWS S3 buckets as all media files are served locally.

- Run python3 manage.py runserver in the terminal. This will create a local sqlite3.db file for us to use.
- Once this has run, close the server using 'CTRL + C' inside the terminal.
- Then run python3 manage.py migrate to set up the database. There is no need to make migrations as the migration files are already present.
- Create a superuser using python3 manage.py createsuperuser - you will need to enter a username, email address and password (twice).
- Start the server up again with python3 manage.py runserver
- Open the app in a browser window by 'CTRL + click' on the link in the terminal or by navigating to 'http://127.0.0.1:8000/accounts/login/' or 
'https://8000-aabfcfe3-5bf8-4bf3-8622-7695e7dadaab.ws-eu01.gitpod.io/accounts/login' and login with your newly created superuser.
- Once logged in, navigate to the admin panel at http://127.0.0.1:8000/admin' / 'https://8000-aabfcfe3-5bf8-4bf3-8622-7695e7dadaab.ws-eu01.gitpod.io/admin' 
and click on 'Email addresses'.
- Click on your email from the list, tick the 'Verified' and 'Primary' boxes and click 'Save'.

- ### Deploying To Heroku
These instructions make the following assumptions:

- The app has been deployed locally, following the above steps, and then pushed to your own GitHub account.
- Private files should be added to your '.gitignore'(i.e. *.sqlite3, *.pyc...).
- You have created and configured an AWS S3 Bucket for serving the media files.
- You have a Stripe account.
- There should be no reason to create a Procfile or requirements.txt file(these should already be present in the cloned repository).

Once all the above is in place, the instructions below will enable you to deploy to Heroku.

- Go to [heroku.com](https://www.heroku.com/) and log in or create an account.
- Add a new app, give it a name, choose a region closest to you and click Create app.
- On the dashboard, click the resources tab. From within the addons input field search for 'Heroku Postgres' and select it.
- In the plan box that pops up, select 'Hobby Dev - Free', then click 'Provision'.
- Once set up, click the 'Postgres' database, select the 'settings' tab and 'Database Credentials' heading. Make a note of the URI value, you will 
need it later(It will start with 'postgres://'...).
- Go back to the Dashboard, and from the 'Setttings' tab, click the 'Reveal Config Vars' button and add the following key / value pairs: 
    - AWS_ACCESS_KEY_ID - Your AWS Access Key ID.
    - AWS_SECRET_ACCESS_KEY - Your AWS Secret Access Key.
    - DATABASE_URL - This should already be here after you created the Postgres db, but if not, it is the Postgres URI you made a note of earlier.
    - EMAIL_HOST_USER - The email address you want the app to send emails from.
    - EMAIL_HOST_PASS - The password for above email address.
    - SECRET_KEY - Django secret key(use a Django secret key generator).
    - STRIPE_PUBLIC_KEY - Your Stripe public key.
    - STRIPE_SECRET_KEY - Your Stripe Secret key.
    - STRIPE_WH_KEY - Your Stripe webhook key.
    - USE_AWS - Set to 'True'.

- Prepare the new Postgres db, by following these steps:
    - From your local IDE, go to your'settings.py' file and under 'DATABASE_URL' add your postgress value(this can be copied from the Heroku config vars) and 
    restart your IDE to allow the new environment variable for the database to take effect.
- Your local deployment should now be connected to the remote Postgres db so you can run:
    - python3 manage.py migrate to set up the database
    - python3 manage.py createsuperuser to set up your admin account.
    - Delete / comment out the 'DATABASE_URL' entry in your 'settings.py file.

- Back in the Heroku Dashboard, click the Deploy tab and scroll down to Deployment Method. Select GitHub and link your account and repository.
- Scroll down further to Manual Deploy, choose the branch you wish to deploy and click Deploy Branch
- Wait for the app to build, and once complete, click view to launch your app in the browser.
- Log in with the superuser details you created and navigate to the admin panel at 'your-deployment-url/admin'.
- Repeat the instructions from 'Local Deployment' to 'Verify' and make 'Primary' email to give access to your superuser(remember to press save).

## Credits
- ### Content
    - All HTML, CSS, JavaScript and Python code is of my own with the use of [Bootstraps](https://getbootstrap.com/) built in classes and functions.
    - The products details and assets were sourced from [Kaggle](https://www.kaggle.com/).
    - All other words and text are my own.

- ### Media
    - The product images have been sourced from their respective products at [Kaggle](https://www.kaggle.com/).
    - All other media was sourced from [Google Images](https://www.google.co.uk/imghp?hl=en&tab=wi&ogbl).

- ### Acknowledgements
    - My Mentor Mark Railton for continuous helpful feedback and ideas to improve both myself as a developer and my project.