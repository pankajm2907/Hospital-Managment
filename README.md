# Health Management System

A Health Management System built using microservices architecture to manage hospital operations such as patient management, doctor schedules, disease records, medicines, and more.

## Microservices

The system is divided into several microservices, each responsible for a specific function. Here's a brief description of each:

### 1. **Patient Service**
   - Manages patient information, including personal details, medical history, and visit history.
   - Exposes REST APIs to add, update, retrieve, and delete patient records.
   - Responsible for handling patient registrations and managing their appointments.

### 2. **Doctor Service**
   - Manages doctor information, including specialization, availability, and consultation history.
   - Provides APIs to view doctor details, check available schedules, and assign doctors to patients.
   - Responsible for managing doctor profiles and working shifts.

### 3. **Disease Service**
   - Manages disease-related data, including symptoms, treatments, and patient records related to specific diseases.
   - Provides APIs to add, update, and retrieve disease records, which can be linked to patient diagnoses.

### 4. **Medicine Service**
   - Handles information about medicines, including name, dosage, and associated diseases.
   - Provides APIs for managing inventory and medicine prescription details.
   - Helps in tracking stock levels of medicines in the hospital and facilitates medicine administration.

### 5. **Contact Us Service**
   - Manages queries from patients or potential patients regarding hospital services, information, and inquiries.
   - Provides APIs to submit queries or feedback via a contact form.
   - Sends notifications to the admin for inquiries that require follow-up or response.

## API Gateway

An API Gateway is used to route requests from the client to the appropriate microservices. It serves as the central entry point for all client requests, ensuring better load balancing, security, and integration.

## Technologies Used
- HTML and CSS (Frontend)
- Java (Spring Boot)
- Microservices Architecture
- REST APIs
- API Gateway
- MySQL (For database)

###By Shubh Joshi(B067) and Pankaj Mirchandani(B070)
