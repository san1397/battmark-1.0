# Project - BattMark 1.0

## Summary - Battmark is a ticket booking and event hosting platform designed to help small artists seamlessly organize events, workshops, and seminars without relying on manual processes.

## Problem Statement -  Small artists often face challenges in hosting events on popular platforms like BookMyShow or Paytm Insider, leading them to promote their events manually through social media (Instagram, Facebook, WhatsApp, etc.). Participants register by contacting the host directly and making payments via UPI or cash, requiring the host to manually track payments, registrations, and attendance using spreadsheets. On the event day, hosts must appoint someone to verify payments and mark attendance, causing inefficiencies and last-minute issues.

## Solution: - 
Battmark provides a centralized platform for artists to:

Host events and share links for promotion.

Allow participants to book tickets and make payments online.

Enable hosts to track registrations and payment status via a dashboard.

Generate QR codes for participants upon successful registration.

Facilitate QR code scanning for attendance marking on the event day.

Provide a transparent view of total participation and revenue for the host.

This end-to-end solution eliminates manual tracking, ensures hassle-free event management, and enhances the overall experience for both hosts and participants.


## My role -
As a Data Engineer, I worked on building an ETL pipeline to process event workshop data and create a Power BI dashboard for business decision-making.

We collected workshop details in CSV format from various sources and uploaded them to AWS S3 (source folder). Using AWS Glue, 
I performed the following transformations:

Loaded data into the staging layer and joined multiple files using SQL-based logic.
Removed unnecessary rows, duplicates, and null values to clean the dataset.
Excluded unnecessary columns
Stored the transformed data in the AWS S3 target folder.
After processing, I used Power BI to create interactive dashboards for stakeholders, helping them analyze workshop trends and make informed decisions.

Tools used - 
AWS S#, AWS Glue, AWS Lambda, PowerBI, QuickSight, Amazon Athena
