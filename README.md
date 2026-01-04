SQL to PostgreSQL Migration Tool (Selected Column)

📌 Overview

This project provides a Windows-based data migration tool that allows controlled data transfer from MS SQL Server to PostgreSQL with support for selected column migration. It is designed for users who want precise control over what data is migrated instead of moving entire tables.

✨ Key Features

Migrate data from MS SQL Server → PostgreSQL

Selected column migration support

GUI-based tool (no scripting required)

Network connectivity validation

SQL Server & PostgreSQL connection checks

Real-time migration progress and error reporting

⚠️ Trial Version Notice

This is a trial (initial) release

Supports up to 20,000 records per table

Suitable for testing, evaluation, and small datasets

🖥️ System Requirements

Windows 10 / 11

MS SQL Server (source database)

PostgreSQL (destination database)

Network connectivity between both systems

Required open ports:

SQL Server: 1433 (or custom)

PostgreSQL: 5432

🚀 How to Use (Step-by-Step)

1️⃣ Check Network Connectivity

From your system, verify connectivity to the SQL Server:

ping <SQL_Server_IP> -t

2️⃣ Verify SQL Server Port

Enable Telnet Client on Windows and run:

telnet <SQL_Server_IP> <SQL_Port>


A blank screen indicates successful access.

3️⃣ Configure PostgreSQL Access

Locate pg_hba.conf in the PostgreSQL data directory

Add your system IP address

Save the file

Restart PostgreSQL service

4️⃣ Verify PostgreSQL Port
telnet <PostgreSQL_IP> 5432

5️⃣ Prepare Destination Database

Create an empty PostgreSQL database to receive the migrated data.

6️⃣ Run the Migration Tool

Launch the .exe file

Enter MS SQL Server credentials

Click MSSQL DB to verify connection

Select required tables and columns

Enter PostgreSQL credentials

Click PGSQL DB

Click Migrate to start data transfer

📦 Download (GitHub Releases)

The executable file is distributed via GitHub Releases due to size limits.

🔽 Steps to Download

Go to the Releases section of this repository

Open the latest release

Download the .exe file from Assets

👉 Quick link:

[../../releases/latest](https://github.com/Meenargb/Data_migration_full_table_selected-column/releases/tag/v2.0.0)

🏷️ Release Information

Version: v2.0.0

Release Title: Initial Release – SQL to PostgreSQL Migration Tool (Selected Column)

📄 Notes

This release focuses on selected column migration

Designed for controlled, precise data transfer

Future versions may include performance and scalability enhancements
