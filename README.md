# E-Shop

In this website, I used the MVC structure. You will find below the description of the important files.


Models:


user.js: extracts information from the 'users' collection which contains id, name, email and the cart of the users (I used a unique user for now). Through this file, you can add items to the cart, get them and delete them. 
You can also confirm your order by putting the cart items in a collection called 'orders'. 


product.js: extracts information from the 'products' collection which contains id, name, imageUrl, price, description and the userid that added it. 


Controllers:


admin.js: an admin can add an item to the platform, edit it and delete it. 


shop.js: a client can choose an item, add it to cart, delete it from the cart and make an order after confirmation. 


Views: contains ejs files


Routers: connects you to controllers


public: contains css files


util: contains path.js and database.js (database connection)






