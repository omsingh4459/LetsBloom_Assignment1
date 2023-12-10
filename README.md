# LetsBloom_Assignment1 (Om_Kumar_Singh 20JE0650 IIT(ISM))
Step 1: Necessary Packages( express, mongoose, body-parser) are installed, after starting server 
        Database connection request will be there in mongo db compass. collection will be named as Sample

Step 2: I have implemented all CRUD operations using Postman 

Step 3: For Creating a book, POST method is used http://localhost:3000/api/v1/product/new
        Using Schema defined in my code for product , new product will be created and inserted in database.

Step 4: For Get all books, GET method is used, I used http://localhost:3000/api/v1/products 
        My code will find all products and will return all prodcuts, and that can be seen on postman .

Step 5: For update a book, PUT method is used I used http://localhost:3000/api/v1/product/:id 
        Similarly for Updating book , url should contain id, and then we can pass fields that we want to update
        For example, if price of book changed.

Step 6: For deleting book, I used http://localhost:3000//api/v1/product/:id 
        For example ,
        http://localhost:3000/api/v1/product/6575b7e4221f0c151b7b0197 This will find a book with given id, if 
        not , it will throw error, and if exist, it will delete that book from database and will return successful message.

Postman workspace
https://www.postman.com/telecoms-specialist-94559196/workspace/letsbloom-assignment/collection/21774865-5dfdc338-2ff8-462a-b63e-998ef35429b7?action=share&creator=21774865

