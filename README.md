# BookMyShow_Online_Ticket_Booking_Stream_Data_Processing

Project Title:
BookMyShow Online Ticket Booking Stream Data Processing

Tech Stack:
Programming Language: Python
Azure Services: Event Hub, Azure Stream Analytics Job, Synapse Data Warehouse
Database: SQL
Pipeline Workflow:
Data Ingestion:

Booking Event Hub: Streams mock booking data.
Payments Event Hub: Streams mock payment data.
Stream Processing:

Azure Stream Analytics Job:
Joins Booking and Payment streams using window-based joins.
Transforms the data for downstream analytics.
Data Storage:

Writes the processed, structured data to a Synapse Data Warehouse table.
![diagram-export-05-12-2024-17_50_36](https://github.com/user-attachments/assets/2aa232b2-bc6e-4350-b558-fb7b8d332be6)
