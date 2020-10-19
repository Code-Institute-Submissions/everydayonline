<h1 align="center">everydayonline</h1>

<h2 align="center"><a href="https://github.com/joenapper/everydayonline/blob/master/README.md">Back to full README file</a></h2>

##### Note: FEATURES.MD is in a separate file to the [README.md](https://github.com/joenapper/everydayonline/blob/master/README.md) to keep the file a reasonable length and to maintain cleanliness.

## Features

### Site-Wide 
- The base of the website is made up of the landing page, which shows the purpose of the site, the products pages, which show all 
the added products, the product detail page which gives the user more information about the product and a way to 'Add To Bag',
the product management page to add, edit and delete the users products, a checkout page to purchase itens in the 'bag' and a 
'My Profile' page. The use of Djangos built in functions allowed me to easily create a way for users to create there own accounts
and save there information (this can be seen on the 'My Profile' page). Another built in feature of django was templating which allowed 
me to implement a consistent layout throughout the site using a 'base.html' file and 'Block content'. I was able to build a 
complex, responsive navbar, suitable for all screen sizes, and simple use the 'blocks' to display the navbar on every page without
having to copy all the code over. This saved me lots of time and minimised the amount coding necessary.  

- ##### The Navigation Bar
    - The navigation bar is fully responsive and is aesthetically pleasing on all platforms and devices. This was achieved by creating
    a 'main-nav.html' and 'mobile-top-header.html'and using content blocks to 'include' one of the files depending on the scren size.

    - On desktop view (screen width size of 992px and above) the brand name is located at the far left-hand side of the navigation bar 
    followed the search bar and then all the links to other pages, including customer login.

    - On tablet view (screen width sizes between 992px to 767px), I replaced the brand name with a 'hamburger' icon which, when toggled,
    displays a drop down menu containing all the links to other pages. I then replaced the search bar with a search icon which, when clicked,
    displays the search bar. I did this to save space on the smaller screen sizes but without having to get rid of the feature. We then have
    account login icon and the shopping bag icon which fit nicely and are interactive.

    - On mobile view & smaller screen sized devices (screen width sizes under 767px) the navbar acts the same as described in the 'tablet' view
    however i decided to add the shopping bag icon on its own line in the navbar because it was slighly too cluttered having everything on the
    same line. This still looks good and keeps all the functionality in working order.

