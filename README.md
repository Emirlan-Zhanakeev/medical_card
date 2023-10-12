# medical_card
Diploma project
## Doctor Appointment Management System
# Table of Contents:
Introduction
Features
Prerequisites
Configuration
Usage
Database Schema


## Introduction
The Doctor Appointment Management System is a web-based application designed to streamline the process of scheduling and managing doctor-patient appointments. It is developed using Java, Spring MVC, and utilizes PostgreSQL as its database. This documentation provides an overview of the system, its features, and guidance on installation, configuration, and usage.

## Features
User Roles: The system supports multiple user roles, including administrators, doctors, and patients, each with specific permissions.

Appointment Scheduling: Patients can request appointments with doctors, and doctors can approve or reschedule appointments.

Patient Records: Doctors can access patient records, including medical history and treatment plans.

Admin Panel: Administrators have access to manage users, doctors, and appointments.

Security: The system prioritizes data security, including user authentication and access controls.

## Prerequisites
Before you begin, ensure you have met the following requirements:

Java Development Kit (JDK) 8 or later
Apache Maven
PostgreSQL Database
Integrated Development Environment (IDE), e.g., IntelliJ IDEA or Eclipse

## Configuration
Database configuration can be found in src/main/resources/application.properties. Update the PostgreSQL database connection settings according to your environment.

User roles and permissions can be configured in the database after the system is up and running.

## Usage
Access the application in your web browser at http://localhost:8080.

Sign in as an administrator, doctor, or patient with the respective credentials.

Use the application to schedule, manage, or approve appointments, access patient records, and perform administrative tasks.

## Database Schema
The database schema can be found in the Database Schema file.
