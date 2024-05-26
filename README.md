# Hospital Management System - SQL Database Resources

This repository contains all SQL scripts necessary for setting up and managing the database of a hospital management system. Below is a detailed description of each component included in this repository.

## ER Diagrams
- **ER_Diagram.PNG**: Visual representation of the Entity-Relationship model of the database. This diagram shows how tables like `Patient`, `Doctor`, `Visit`, and `Clinic` are interconnected.
- **Hospital.EER_Diagram.mwb**: MySQL Workbench file for the ER diagram, editable format for further modifications.
- **Hospital.EER_Diagram.mwb.beforefix**: Backup of the original ER diagram before any modifications.

## Database Creation Scripts
- **Hospital_CREATE.sql**: SQL script to create all the necessary tables and relationships for the hospital management database.
- **Hospital_CREATE_med_Trigger_Views_Procedures_INSERTs.sql**: Comprehensive SQL file that includes commands for creating tables, triggers, views, stored procedures, and initial data insertions.

## Data Insertion Scripts
- **Hospital_INSERT.sql**: SQL script to populate the database with initial data for testing and development purposes.

## Stored Procedures
- **Procedure_add_visit.sql**: Stored procedure to add a new visit record to the database.
- **Procedure_AddNewPatient.sql**: Stored procedure to add a new patient to the system.
- **Procedure_get_patient_visits.sql**: Stored procedure to retrieve all visits associated with a particular patient.
- **Procedure_UpdatePatientInfo.sql**: Stored procedure to update existing patient information.

## Triggers
- **Trigger_UpdateLatestVisitInfo.sql**: SQL trigger to update the latest visit information whenever a new visit is recorded.

## Views
- **View_latestvisitinfo.sql**: SQL view to easily access the most recent visit details for any patient.
- **View_patient_count_per_doctor.sql**: SQL view that provides a count of patients per doctor, useful for load balancing and operational insights.
