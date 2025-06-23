# Task 1: Data Cleaning – Medical Appointment No Shows

## 📁 Dataset Used
Medical Appointment No Shows  
Source: Kaggle – https://www.kaggle.com/datasets/joniarroba/noshowappointments

## 🧹 Changes Made / Cleaning Steps
- Removed duplicate rows  
- Removed rows with invalid age values (e.g., negative ages)  
- Filled missing values in `country` and `director` with placeholders (if applicable)  
- Standardized text values in `gender` and `no-show` columns  
- Converted `no-show` column to a binary flag: `0` = showed up, `1` = missed  
- Renamed all column headers to lowercase with underscores  
- Converted `scheduledday` and `appointmentday` to datetime format  
- Added a new column: `waiting_days` (days between scheduled and appointment date)  
- Removed rows with negative waiting days  
- Saved cleaned data as `medical_appointments_cleaned.csv`

## 🙋‍♀ Submitted By
Yeshashwini G
