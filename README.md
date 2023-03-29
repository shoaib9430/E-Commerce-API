
# Ecommerce API
Its an Ecommerce API to manage product inventory






> ***Install project with npm***       

```bash
  cd EcommerceAPI_CN
  npm install
  npm install nodemon

```

***Start APP***

```bash 
npm start
```

## Routes and their responses


### method GET
API to list products
- http://localhost:8080/product

### method DELETE 
API to delete products
- http://localhost:8080/product/:id

### method POST
API to add products to the database
- http://localhost:8080/product/create

### method POST
API to update quantity of a product (can be incremented or decremented)
- http://localhost:8003/product/:id/update_quantity/?number=[number of qty]
## ***Tasks Performs***

- Show a list of all product. 
- Add Product
- Remove Product
- Update Product Quantity 





