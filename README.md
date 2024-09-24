# Vehicle Rental System

A project developed using Object-Oriented Programming (OOP) and TypeScript.

## Team Members
- Samir Laguardia
- Alan Vasconi
- Daniella Maria
- Lucas Rocha

## Professors
- Dannyel Kayke
- Rafael Costa

---

## Vehicle Rental System Development

This project focuses on developing a system for a vehicle rental service, adhering to business rules provided by the client.

### Context and Requirements

### Business Rules Established by the Client

#### Vehicle Registration:
1. It is not allowed to register vehicles with the same license plate as another already registered in the system.
2. Vehicle registration must include the hourly rental rate.

#### Vehicle Rental:
1. To rent a vehicle, the customer must provide their name, CPF (Brazilian Taxpayer ID), and license type.
2. If the customer's license type is "A", they can only rent a motorcycle; if it's "B", they can only rent a car.
3. Each customer can only rent one vehicle at a time and must not be renting another vehicle when initiating a new rental.
4. Upon renting a vehicle, the system must calculate the rental cost based on the daily rate, the number of days to be rented, and an additional fee according to the vehicle type. Cars have a 10% fee, while motorcycles have a 5% fee.

#### Vehicle Return:
1. Returning a vehicle requires the customer's CPF and the vehicle's license plate.
2. It is not allowed to remove a vehicle from the system if it is currently rented.

#### Billing:
1. The system must generate an invoice upon request, detailing the rental costs for each vehicle.

### System Features:
1. Register vehicle
2. Rent vehicle
3. Return vehicle
4. List available vehicles
5. List rented vehicles
6. Show customer invoice
7. Exit system
