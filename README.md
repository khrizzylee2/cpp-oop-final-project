# cpp-oop-final-project

A C++ object-oriented programming project developed as a final semester project, applying classes, inheritance, vectors, file organization, and data management.

## Project Concept

This project is a simple backend system for a delivery service platform.

The system connects businesses, customers, and delivery workers. Businesses can register their companies and request deliveries after receiving customer orders. Regular users can also register to send items to other people. Delivery workers, called motor boys, can register in the system and be assigned to delivery requests.

The goal of the system is to manage the full delivery flow: registration, order creation, pickup information, delivery information, delivery assignment, and delivery status tracking.

## Registration Types

The system supports three main types of registration:

1. **Business Registration**
   - For companies that want to use the platform to request deliveries.
   - A business has information such as name, CNPJ, address, phone number, and business category.

2. **Motor Boy Registration**
   - For delivery workers who will collect and deliver orders.
   - A motor boy has information such as name, CPF, phone number, vehicle plate, availability status, and completed deliveries.

3. **Person Registration**
   - For regular users who want to send goods to another person.
   - A person has information such as name, CPF, phone number, address, and delivery history.
