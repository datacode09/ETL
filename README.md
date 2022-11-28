# Souce
- A csv file with the same name as table (Department.csv)
# Target
A sql server table named "Department"
# Files
- DDL- Includes create table command for the table "Department"
- test.csv - test data
# Table
Department
Columns:
- ID: unique identifier of the department
- name: name of department (constraint)
- description: description of the department
- pid: NULL if there is no parent department
- Status: 0= Normal, 1= Deleted
- Managetype: 0= All access, 1= Acces list
# ETL Requirement
Eveyday the full table is going to be available. Insert or Update based on table constraints (column: name)
