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

### Home Page (Landing Page)
- When the site is first opened, the user can instantly see what the site is and what its purpose is for. The use of the large, full-screen cover 
photo helps illustrate the site and the use of bright colours promotes a better user experience. The main text on this page reads 'THE NEW COLLECTIONS 
ARE HERE!' followed by a 'SHOP NOW' button further enticing the user to see whats on offer.

- For tablet and mobile users, the image is re-positioned to best keep the 'shopping' aspect noticable. This was done by using the top/bottom and 
left/right properties in CSS to get the best possible postion without affecting the image quality.

### All Products
- ##### Search bar
    - The search bar is located at the top of every page inside the navbar. The placeholder text "Search our site" makes it easy for users to understand 
    that if they're looking for products, for example, jeans, they type in jeans and it will search and return all items related to jeans. This search engine 
    is smart and doesn't need the user to be case sensitive or even spell the word correctly. The most relevant data linked to the search will be displayed. 
    The actual search button is standoff-ish on its own and clearly indicates its purpose (search for the queried product). Alternatively, the user can also 
    just press the enter key, which is more commonly used on desktop devices, which will give them the same result.  

    - The search bar will always appear in the navbar but on smaller screens (tablet and mobile) the search bar is hidden untill the user clicks the search
    icon. This makes better use of the available space and only displays the actual bar if the user needs it.

- ##### Specific product page (i.e: Arizona Original Bootcut Jeans)
    - Clicking on any of the product 'cards' will take the user to that specific product page which will show the full details of that product including a 
    description, quantity the user wants to buy and select size (if applicable). Not only that but from here the user has access to the manage buttons where
    the product can be edited, if theirs a spelling error for example, or deleted, if the item is no longer for sale. However, it is worth noting that products 
    can only be edited or deleted by the person who added them.

    - Each piece of information is displayed on its own line and can be easily read. On desktop and tablet devices, the photo of the products appears to the left 
    of the details and further improves the look and readability. The use of icons for the category and rating also helped as it split up some of the text and 
    makes the area more appealing to look at. The same can be said for the size select and quantity box which add another layour to the page and help break up the
    information better.

    - For mobile users, all the information remains in the same layout but instead of displaying the image and text next to each other, the image displays above 
    the text. This was done to maintain the quality of the image, but also keep the content easy to read and visually impacting.

- ##### Manage buttons
    - Edit: Clicking the edit button will redirect the user to a page very similar to the page used to add the product. The same form from the 'Product 
    Management' page will be displayed, however, all the information will be pre-populated in correspondence to the specific product the user has chosen to 
    edit. From here the user can easily pinpoint the mistake that needs to be edited and then simply click the 'Update Product' button. This will then redirect 
    the user to the page where they can see their changes have been made successfully.
    
    - Delete: 

<h3 align="center"><a href="https://github.com/joenapper/everydayonline/blob/master/README.md">Return to README.md</a></h3>