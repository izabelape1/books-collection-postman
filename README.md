# books-collection-postman
Welcome to the API collection for the "Book Store" online store. This collection contains endpoints for order management.This is the final project of my API testing course using the "Postman" tool. 
## Installation Instructions
 1. Download and install [Postman](https://www.postman.com/downloads/) or run in a web browser [Postman web version](https://www.postman.com/).
 2. Copy link to my collection: https://blue-star-656429.postman.co/workspace/My-Workspace~a8bb4542-626e-4d98-8d68-75d4bb818fef/collection/25449881-adb14ac2-d391-4e83-8b9b-90b3438e67e6?action=share&creator=25449881
 3. Open Postman and select "Import" from the sidebar.
 4. Wklej skopiowany link i zaimportuj kolekcję.
## Examples of Use
### Token generation and saving the received Token to environment variables
1. Select the "POST Token generation" endpoint from the collection (from the "Api-clients" folder).
2. Click the "Send" button to make a POST request.
3. View received Token.
4. In the "Tests" tab, the content of the response body has been assigned to the environment variable named "Token"
### Get an order list
1. Select the "GET Orders" endpoint from the collection (from the "Orders" folder).
2. Click the "Send" button to execute the GET request.
3. See the received list of orders in response (response body doesn't contain any orders because they haven't been added yet).
### Adding a new order
1. Select the "POST Orders" endpoint from the collection and go to the "Body" tab.
2. Enter the new book data in JSON format:
   {
    "bookId": {{bookId}},
    "customerName": "{{customerName}}"
   }
3. In the "Pre request script" tab:
- assigning a variable named "bookId" a random number from 1 to 6
- assigning a variable named "customerName" to a random name

   
  

