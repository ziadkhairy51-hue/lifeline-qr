# lifeline-qr
Emergency QR service system analysis and workflow design.
# 🚑 Lifeline QR - System for Emergency Medical Data Access

## 📖 Problem Statement
During emergencies or when a patient is unconscious, doctors often face difficulties in identifying the patient's medical history — such as chronic diseases, allergies, or previous test results. This lack of information can delay treatment or lead to inaccurate medical decisions

## 🎯 Objectives & Scope
* To develop a smart system that uses a QR code to store essential medical data for each patient
* To allow medical teams to instantly access these records by scanning the QR code, aiming to reduce medical errors and improve emergency response time
* The project focuses on developing a platform and a database system for hospitals within the Minya governorate, with the potential to expand to a national level

## ⚙️ Key Functional Requirements
* The system must generate a unique QR code for each patient and allow the creation of a patient file with a unique ID.
* The system must allow doctors to scan the QR code to instantly access and display the patient's medical history.
* The system must store medical records including diseases, allergies, and medications, and allow adding new test results.
* The system must restrict access to authorized doctors only and log every access made by a doctor to patient data.
* The system must ensure data privacy and maintain a secure digital record.

## 📐 System Design & Architecture
This repository contains comprehensive system analysis diagrams mapping out our emergency workflow:
* Context Diagram: Highlights the primary data flow between the Patient, Doctor, and the Lifeline-QR system (Context diagram.jpg).
* Data Flow Diagrams (DFD): Details the process workflows and data routing at Level 0 (DFD Level 0.jpg) and Level 1 (DFD Level 1.jpg).
* Entity-Relationship Diagram (ERD): Maps out the database entities, attributes, and relationships (ERD.jpg).
* Database Schema: Defines the structured tables, primary keys, and foreign keys for the system (Schema.jpg).

## 👥 Project Team
* Salah Mohy Mohamed
* Ziad Mohamed Khairy
* Shaher Gamal Mohamed
* Anas Mohamed Ismail
* Mohamed Ashraf Sayed Abdullah
