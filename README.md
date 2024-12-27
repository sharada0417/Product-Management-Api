# Product Management API

A simple **Product Management** API built with **Express.js** and **SQLite**. This API allows users to manage products by adding, updating, deleting, and retrieving product details.

## Features

- 📦 **Add Products**: Create new products with details like name, description, category, brand, etc.
- 📋 **View All Products**: Retrieve a list of all products in the database.
- ✏️ **Update Products**: Edit product information using a PUT request.
- ❌ **Delete Products**: Remove products from the database by ID.
- 💻 **Easy Integration**: Integrate with any frontend application via RESTful API.

## Technologies Used
- Node.js
- Express.js
- SQLite3 (Database)

## Demo
1. **Add a Product**:
   - Send a `POST` request to `/api/products/` with product details.
   ![post](https://github.com/user-attachments/assets/6485ebb8-bd9c-4298-94f7-8a290204ff39)
   
2. **View All Products**:
   - Send a `GET` request to `/api/products` to get all the products.
   ![get](https://github.com/user-attachments/assets/7940801a-8f2d-4e96-a4db-217dc0275999)

3. **Update a Product**:
   - Send a `PUT` request to `/api/products/` with updated product details.
   ![put](https://github.com/user-attachments/assets/3a279d0d-3d38-416d-a14e-239daa34c5be)

4. **Delete a Product**:
   - Send a `DELETE` request to `/api/products/delete/:id` to delete a product by ID.
   ![delete](https://github.com/user-attachments/assets/99025fa5-e448-419f-842d-5db2155367ae)


## Project Structure

```
.
├── README.md
├── database.js
│── server.js
└── package.json


```

## How to Use

1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
3. Start the server:
    ```bash
    node server.js  

## Features

- Create: Add products with specific details like name, description, and price.
- Read: View all products stored in the database.
- Update: Edit product details.
- Delete: Remove products from the database by ID.

## License

This project is open-source and available under the [MIT License](LICENSE).
