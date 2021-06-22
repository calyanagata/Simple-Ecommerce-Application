# $okopedia
 A simple e-commerce for buy and sell product. I made this web application with my friend <b>Merisa Syafrina</b>, please check her work by clicking this link: https://merisasyafrina.github.io/
 
 <h2>Introduction</h2>
 $okopedia is a famous Indonesian technology company specializing in e-commerce, to expand its business, $okopedia wants to create a website for their shop. In that website, people can find information about the $okopedia’s products and order it. This website enables the customers to know what is inside $okopedia.
 
 <br><h2>Class Diagram</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122917522-54674880-d388-11eb-9d42-0c7527afcc4d.png">
</p>

<br><h2>Navigation Bar</h2>
<h3>1. Member</h3>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122918104-f8e98a80-d388-11eb-9fd1-dfb8813d7a4a.png">
</p>

The navigation bar as above will appear when the user has a role as a member. The NavBar for members will display the $okopedia logo, search bar, cart button along with the number of items in the cart, history button, and the name of the user who is currently logged in.

The following are the functions of the navigation bar components for members:
- Logo button: when clicked it will go to the Home Page.
- Search bar: useful for typing a search for an item.
- Search button: useful for doing a search.
- Cart button: go to Cart page.
- History button: go to the History page.
- Username: dropdown list for Logout.

<h3>2. Admin</h3>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122918393-48c85180-d389-11eb-863b-c0d21032fb94.png">
</p>

The navigation bar as above will appear when the user has a role as admin. On the NavBar for admins, admin posts, product buttons, category buttons, and the $okopedia logo will be displayed.

Here are the functions of the navigation bar components for admins:
- Admin posts: when clicked it will go to the admin-panel.
- Product button: dropdown list for Add Product and Show All Product.
- Category button: dropdown list for Add Category and Show All Category.
- Logo button: dropdown list for Logout

<h3>3. Guest</h3>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122918872-c9874d80-d389-11eb-9f33-90a03f9567a9.png">
</p>

Here are the functions of the navigation bar components for guests:
- Logo button: when clicked it will go to the Home Page.
- Search bar: useful for typing a search for an item.
- Search button: useful for doing a search.
- Login: go to Login page.
- Register: go to the Register page.

<br><h2>Search</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919008-f176b100-d389-11eb-8248-7f324f8d3205.png">
</p>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919019-f3407480-d389-11eb-9f19-59e927eec317.png">
</p>

By typing keywords in the search bar, users can search for the desired item. The display will consistently display per 3 items and with the page features below (the data shown is duplicate because it is only an example to show page features).

<br><h2>Login</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919162-1f5bf580-d38a-11eb-9666-29199fdb7aa4.png">
</p>

This page is a login page where users can enter their email address and password based on the account they already have. Users can also check Remember Me to save cookies so they can continue to be authenticated.

<br><h2>Forgot Password</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919288-4286a500-d38a-11eb-8a20-a096595c4141.png"></p>

Users can take advantage of this feature if they forget their password at any time.

<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919322-4dd9d080-d38a-11eb-8f4e-42d38f6871a4.png"></p>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919329-50d4c100-d38a-11eb-92a2-c3ac9ad80f68.png"></p>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919338-529e8480-d38a-11eb-84ca-b5e96443728c.png"></p>

Email will be sent by the system using mailtrap.io as a test only. After the user clicks the Reset Password button in their email, the user will be redirected to a new password creation page.

<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919377-5d591980-d38a-11eb-9093-927ee7390365.png"></p>

After completing the Reset Password form, the user can enter his account and go directly to the Home Page.

<br><h2>Register</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919643-a90bc300-d38a-11eb-9f21-c4094c84e6ea.png"></p>
    
This page is intended for guests who want to register as members. Each component has the following validations:
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919820-dfe1d900-d38a-11eb-901e-3e24c4fe95d9.png"></p>

After clicking Register the user can automatically login and go to the Home Page.

<br><h2>Number of Cart Calculations</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919894-f6883000-d38a-11eb-99f6-d06159d6219f.png"></p>

This number indicates several types of items in the Cart. Clicking this button will take you to the Cart page.

<br><h2>Drop Down List Layout</h2>
<p align="center">
<img src="https://user-images.githubusercontent.com/72309158/122919962-09026980-d38b-11eb-91ac-439bf2b696f6.png"></p>

When the user name is clicked, a list will appear for Logout.

<br><h2>Logout</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920103-364f1780-d38b-11eb-9a25-b4acbe755c5c.png"></p>

After clicking the Logout button, the session will be deleted and the user will exit his account and return to the Home Page as a guest.

<br><h2>Product Detail</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920151-4666f700-d38b-11eb-897e-f3696e31f049.png"></p>

Each product card displays a product image, product name, product price, and a button to go to product details. When the button is clicked, the user will go to the Product Detail page:
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920170-4cf56e80-d38b-11eb-8084-177e9a090d96.png"></p>

If the user clicks Add to Cart, a text box will appear to input the desired amount to be purchased:
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920195-5252b900-d38b-11eb-8fe8-5c2fddff56ec.png"></p>

After the quantity is inputted and the button is clicked again, the user will be redirected back to the Home Page and the number of carts has increased:
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920228-5aaaf400-d38b-11eb-8281-fd37c8ff986c.png"></p>

If guests who have not logged in want to access Product Details, they will be redirected to the Login page to login first.

<br><h2>Cart</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920262-65fe1f80-d38b-11eb-90f0-69b81e6d8d06.png"></p>

When the Cart button is clicked, the user will go to the Cart page. On the Cart page, users can edit or delete items that have been previously added to the Cart.
When the Edit button is clicked, the user will go to the edit item page as follows:
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920302-71514b00-d38b-11eb-8b2f-1a4a406ce687.png"></p>

User can input a new quantity then click the Edit button.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920320-757d6880-d38b-11eb-9468-0de6f5fb97dc.png"></p>

Then after that, the item quantity was successfully edited:
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920365-85954800-d38b-11eb-8a16-6de93ea52c8f.png"></p>

When the Delete button is clicked it will look like this (items are removed from the Cart):
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122920384-8cbc5600-d38b-11eb-8905-0ed7bc03f98c.png"></p>

When the Checkout button is clicked, the item will be moved to History.

<br><h2>History</h2>
If the user clicks the history button, the user will go to the History page which will provide information on the date and time each user checks out the goods. In addition there is also a Details button to redirect the user to the Transaction Details page.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921236-74990680-d38c-11eb-898f-38e19cd368be.png"></p>

<br><h2>Detail Transaction Page</h2>
On this page the user can see what products have been checked out on a certain date and time.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921312-87134000-d38c-11eb-9f38-a593a6b885da.png"></p>

<br><h2>Admin Panel</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921339-8f6b7b00-d38c-11eb-8579-d6acbb4aedee.png"></p>

If the logged in user has the admin role, the page above will appear.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921362-972b1f80-d38c-11eb-9e08-42e2595617df.png"></p>

If the admin presses the Product button, the Add Product and Show All Product dropdown lists will appear.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921391-9e522d80-d38c-11eb-9415-8de5c02e4ab3.png"></p>

If the admin presses the Category button, the Add Category and Show All Category dropdown lists will appear.
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921422-a9a55900-d38c-11eb-8dc5-ac44a70a6353.png"></p>

If the admin presses the logo button, a dropdown list will appear for Logout.

<br><h2>Add Product</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122921487-bfb31980-d38c-11eb-8df1-86e0084aa79e.png"></p>

If the admin clicks the Add Product button, the admin will go to the Add Product page as above where the admin can add the product to the database by filling out the available form and submit it by clicking the Add Product button.

<br><h2>List Product Page</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122922935-57653780-d38e-11eb-8346-8cca593757f4.png"></p>

If the admin clicks the Show All Product button, the admin will go to the Product List page to see all the products in the database. There is also a Delete button, if the admin wants to delete the desired product.

<br><h2>Add Category</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122922996-6815ad80-d38e-11eb-9cfe-dffe735a483b.png"></p>
If the admin clicks the Add Category button, the admin will go to the Add Category page as above where the admin can add a category to the database by filling out the available form and submit it by clicking the Add Category button.

<br><h2>List Category Page</h2>
<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122923060-782d8d00-d38e-11eb-9517-c693ceb7a10d.png"></p>

If the admin clicks the Show All Category button, the admin will go to the List Category page to see all the categories in the database. The Category list is displayed in the form of a button that can be clicked to view the product according to the desired category as follows.

<p align="center"><img src="https://user-images.githubusercontent.com/72309158/122923097-7fed3180-d38e-11eb-9023-a37c30add649.png"></p>

The picture above is when the admin clicks on the TV category and the TV category product will appear under the category buttons.

<br><h2>Reference</h2>
- https://bit.ly/36a3NUN / \laravel\public\assets\iphone.jpg
- https://bit.ly/39im8kD / \laravel\public\assets\s20.jpg
- https://bit.ly/3l8xZDW / \laravel\public\assets\macbook.jpg
- https://bit.ly/3nZBApW / \laravel\public\assets\xiaomitv.jpg
