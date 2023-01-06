# Merchant-Service
Merchant service app is a service that handles the catalog of products owned by merchants. The user of this service is merchant. In this app a merchant could register itself/create an account and remove its data/delete its account in the merchant service. A merchant could add, delete, and update products in the merchant service. Also can get the list of products in the merchant service.


## Entity Relationship Diagram
This is how entity relationship work shown by diagram.

![ERD Merchant Service](/assets/erd.jpg)


## Architecture Diagram Merchant Service
This is a architecture diagram of merchant service.

![Architecture Diagram Merchant Service](/assets/adiagram.jpg)


## List of API

These are the list of API /merchant
```
[GET] /merchant -> to get all merchant on merchant service

[GET] /merchant/{id} -> to get one merchant on merchant service

[PUT] /merchant/{id} -> to update merchant on merchant service

[POST] /merchant -> to create account on merchant service

[DEL] /merchant/{id} -> to delete account on merchant service
```

These are the list of API /product
```
[GET] /product -> to get all products on merchant service

[GET] /product/{id} -> to get one product on merchant service

[POST] /product -> to add product on merchant service

[DEL] /product/{id} -> to delete product on merchant service

[PUT] /product/{id} -> to update product on merchant service
```

This is the API /login
```
[POST] /login -> to login on merchant service
```
