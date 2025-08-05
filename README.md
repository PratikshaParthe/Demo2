# Medical Appointment No-Shows: Data Cleaning & Analysis

This project focuses on cleaning and preparing a real-world healthcare dataset that records patient appointment details and whether or not they showed up. The data is sourced from Kaggle's **"Medical Appointment No Shows"** dataset and includes patient demographics, health conditions, and scheduling information.

## Dataset Overview

**Source**: [Kaggle - Medical Appointment No Shows](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

The dataset includes **110,000+ rows** with the following key columns:
- `PatientId`: Unique identifier for each patient
- `Gender`, `Age`, `Neighbourhood`
- `Scholarship`, `Hypertension`, `Diabetes`, `Alcoholism`, `Handicap`
- `SMS_received`: Whether the patient received a reminder
- `ScheduledDay`, `AppointmentDay`
- `No-show`: Whether the patient showed up or not

---

## Task 1: Data Cleaning & Preparation

### Cleaning Goals:
- Rename columns with typos and inconsistent casing (e.g., `Hipertension` → `Hypertension`)
- Convert date/time fields to datetime format
- Handle invalid age values (e.g., negative numbers)
- Standardize categorical formats (e.g., `No-show` → `0/1`)
- Remove duplicates and nulls
- Feature Engineering:
  - Waiting time (`WaitDays`) between scheduling and appointment
  - Appointment day of the week

