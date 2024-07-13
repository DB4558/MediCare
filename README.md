###Medicare

Description

MediCare is a comprehensive, doctor-friendly tablet-based application designed to streamline healthcare workflows and enhance the efficiency of healthcare delivery. Developed using Spring Boot, Spring Scheduler, React Native with Expo, MySQL, JWT, AES Encryption, QR code, and Twilio, MediCare offers secure management of patient consent for electronic health records and facilitates seamless collaboration across various modules.
Key Features

    Patient Management: View registered patients (indoor/outdoor) with QR codes for quick access.
    Medical Records: Review past medical records, including vitals, symptoms, and past medical images.
    Digital Prescriptions: Write and manage prescriptions digitally.
    Appointment Scheduling: Schedule and manage patient appointments.
    Medication Management: Integrate with pharmacies for efficient medication management.
    Consent Management: Securely manage patient consent for data usage, with options for revocation and automatic expiration.
    Security: Implement JWT-based security with role-based access control.
    Notifications: Use Twilio for sending login time notifications and OTPs.

Modules

    Doctors:
        View patient list.
        Check patient details like vitals, temperature, past history.
        Write prescriptions on a digital canvas.
        Diagnose diseases and recommend medications.

    Nurses:
        Record vitals, symptoms, and past medical history.
        Upload past medical images and records for doctor review.

    Receptionists:
        Book appointments for patients.
        Allocate outdoor doctors and recommend indoor doctors.
        Manage bed allocation based on availability.
        Obtain patient consent for data usage.

    Pharmacy:
        Serve medications based on doctor prescriptions.
        Manage medication inventory and orders.

    Admin:
        Oversee all modules and manage system settings.
        Ensure data security and compliance with healthcare regulations.

Security

    JWT Security: Ensures secure access to the system with role-based access control.
    AES Encryption: Protects sensitive data throughout the application.

Notifications

    Twilio Integration: Sends login time notifications and OTPs for secure authentication.

Data Management

    Consent Management: Patient consent can be revoked when necessary, and consent automatically expires after one week. Patient data is deleted entirely three years after the last visit.

Project Details

This project is a group effort. I specifically implemented the following features:

    JWT security.
    The entire nurse and pharmacy modules (both frontend and backend).
    Backend validation.
    Twilio notification management.
    Backend schedulers.

Getting Started
Prerequisites

    Node.js
    Expo CLI
    Java Development Kit (JDK)
    MySQL
