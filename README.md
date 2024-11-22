# E-Commerce Order System
This repository is a training to hone my skills on microservices and hexagonal architecture patterns
## Microservices Overview
This project is composed by three services
1. [Order Service](https://github.com/cristeven94/e-commerce-order-service)
2. Inventory Service
3. Notification Service
### Order Service
This service is responsible for handling incoming orders and manage their live cycle (creating, updating or canceling orders), this communicates sychronously with the **Inventory service** to check product availability and reserve the stock
### Inventory Service
This service manage the inventory, stock levels and reserves products for orders
### Notification Service
This server listen to events and sends notifications to users about their order status
