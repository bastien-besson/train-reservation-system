# TRAS : Train Reservation Awesome System
Contributors : [Bastien BESSON](https://github.com/bastien-besson)

## Legacy Code Sandbox for TDD

This project aims to simulate a legacy code project where to apply TDD transformations. It will simulate a real life project and gives us a how to guide on how to implement TDD in our team.

This project is part of the "Legacy Code Sandbox project" from [Optivem Journal](https://journal.optivem.com/) created by [Valentina (Cupać) Jemuović](https://www.linkedin.com/in/valentinajemuovic/) 
<br />
<br />
<br />
### - Use Cases :

#### Book a Train Ticket
- System : Train Reservation System
- Primary Actor : Customers who want to book a train ticket

TRAS offer a simple booking page, completed with free train cancel abilities. It also allows account holders to pay with paypal. The different use cases are :

- A customer can browse train schedules and prices
- A customer can select a train date and time
- A customer can pay with paypal
- A customer can cancel a train ticket

### - External Systems : 
- External REST API : We will use the french train company api : https://api.sncf.com/v1
(Documentation link [here](https://doc.navitia.io/#getting-started))<br />

- External Non Determinism System : System Clock


### - System Architecture Style :
- TRAS.Frontend 
- TRAS.Booking.Train 
- TRAS.Payment

### - Architecture Diagram : 
Diagram (TODO)

### - Teck Stack
- Language : C#
- Framework : .NET 8.0
- Databases :
  - Booking.Train : PostgreSQL
  - Booking.Hotel : Sql Server
  - Payment : PostgreSQL
- Message Broker : 
  - RabbitMQ

### - Repository Strategy :
- Multiple Repository approach

### - Branching Strategy :
- Trunk Based Development
- 
### - Deployment Model :
- Local only (maybe Google Cloud Platform)
