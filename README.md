# NM-EX8h2

CREATE
POST http://localhost:8080/products
Body → raw → JSON:
{
    "name": "Keyboard",
    "price": 89.99,
    "category": "Electronics"
}
READ ALL
GET http://localhost:8080/products
READ ONE
GET http://localhost:8080/products/1
UPDATE
PUT http://localhost:8080/products/1
Body → raw → JSON:
{
    "name": "Gaming Laptop",
    "price": 1299.99,
    "category": "Electronics"
}
DELETE
DELETE http://localhost:8080/products/1
