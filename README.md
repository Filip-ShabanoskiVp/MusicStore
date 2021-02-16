# Music Store

For these mobile application I chose to use mobile operating system Android.
Today Android it is the most famous operating system for development of mobile web application, and so I decide to develop mobile application, which will be of great benefit to a music store and which will help consumers to buy music products from their smartphones.
The programming language that I chose to use in this application is Java.
The data in this application persist in Room Database.
In the main page of the mobile application is displayed some of the products of the page in the form of a card matrix. On the top of the page there is an menu where the use can navigate where he want’s to. There are links that lead to Login page, User profile, Home page and Register page.
Also in the home page there is an link that leads to page where the user can see the location of the store.
The non logged user can see the music products, but he/she cannot manipulate with these products if he is not logged in.
If the user is not registered he choose the link that leads to the Register page. He must filled all the required fields, in order to register the user. When hi filled all the entries the user is registered, and the user is redirected to login page.
When the user filled the username and password fields he clicked to sign in button and then the user is redirected to UserProfile activity and the user is logged in,
In the userProfile activity it is displayed the all information about the logged user.
Also there is an button named Shopping cart, which once clicked will take us to ShoppingCart Activity.    In the product activity there is a list of all products that are added in the system.
In each product in the list there is an button named Add to Cart, and when the logged user clicked that button, the product is removed from the list of products, and is added in the shopping cart.
When the user go to ShoppingCart activity he can see all the product that he has added in his shopping cart.
In the ShoppingCart activity there is an button named Cancel. When the user clicked that button the product is removed from shopping cart and moved back to product list in Product activity.
If the user clicked the Pay button, a dialog is displayed to the user and the user must filled all the required fields. When the user filled all the fields, he\she clicked the Bu Products button, and then the products are successfully bought. The list of products in shopping cart are removed from the shopping cart.
In the Product Activity there is an Action button. When the button is clicked, a dialog is displayed to the user named Add Product. When all the fields are filled the use clicked Add button and the product is added in the product list. In the Product activity there is an link called api_data_link. When the user clicked the link, he\she is redirected to ApiData activity.
In the navigation menu is displayed and search bar. The user enter an key word and given that word, the user finds the artist or music group, which he wrote in the search bar.
