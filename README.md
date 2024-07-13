# Medicare:A tablet based app for busy doctors

## Description

MediCare is a comprehensive, doctor-friendly tablet-based application designed to streamline healthcare workflows and enhance the efficiency of healthcare delivery. Developed using Spring Boot, Spring Scheduler, React Native with Expo, MySQL, JWT, AES Encryption, QR code, and Twilio, MediCare offers secure management of patient consent for electronic health records and facilitates seamless collaboration across various modules.

## Key Features

    Patient Management: View registered patients (indoor/outdoor) with QR codes for quick access.
    Medical Records: Review past medical records, including vitals, symptoms, and past medical images.
    Digital Prescriptions: Write and manage prescriptions digitally.
    Appointment Scheduling: Schedule and manage patient appointments.
    Medication Management: Integrate with pharmacies for efficient medication management.
    Consent Management: Securely manage patient consent for data usage, with options for revocation and automatic expiration.
    Security: Implement JWT-based security with role-based access control.
    Notifications: Use Twilio for sending login time notifications and OTPs.

## Modules
 **Doctors:**
           1. View patient list.
           2. Check patient details like vitals, temperature, past history,symptom images,test results.
           3. Write prescriptions on a digital canvas.
           4. Diagnose diseases and recommend medications.
           5. Recommend test
           6. Outdoor doctors can recommend to indoor
       

**Nurses:**
       1. Record and update vitals, symptoms, and past medical history,symptom images,test results.
       2.  Upload past medical images and records for doctor review.
       3.Can login only during scheduled duty hours

**Receptionists:**
       1. Book appointments for patients.
        2. Allocate outdoor doctors and recommend indoor doctors.
       3. Manage bed allocation based on availability.
       4. Obtain patient consent for data usage.
       5. Revoke patient consent when asked by patient

**Pharmacy:**
        1.Serve medications based on doctor prescriptions.
       2. Manage medication inventory and orders.

**Admin:**
       1. Oversee all modules and manage system settings.
       2. Ensure data security and compliance with healthcare regulations.

## Security

    1. JWT Security: Ensures secure access to the system with role-based access control.
    2. AES Encryption: Protects sensitive data throughout the application.
    3. Email-password encryption: Email and password are sent in encrypted form through api fromt frontend to avoid security breaches
    4. Ensures automatic logout if user inactive for more than 15 mins

## Notifications

    Twilio Integration: Sends login time notifications and OTPs for secure authentication.

## Data Management

    Consent Management: Patient consent can be revoked when necessary, and consent automatically expires after one week. Patient data is deleted entirely three years after the last visit.

## Project Details

This project is a group effort. I specifically implemented the following features:

    1. JWT security(with refresh and access token) with role based access control
    2. The entire nurse and pharmacy modules (both frontend and backend).
    3. Backend validation(both service and database level)
    4. Frontend validation
    5. Twilio notification management.
    6. Backend Spring schedulers.
    7. AES encryption of database(confidential data)
    8. Other secutity features like automatic logout,email-password encryption,sesssion management,ip address matching to ensure secutiy etc

## Getting Started
**Prerequisites**

    Expo CLI
    Java Development Kit (JDK)
    MySQL
