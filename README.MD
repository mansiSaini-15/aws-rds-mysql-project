echo "# AWS RDS MySQL Project" > README.md
📂 Project Overview
This project includes:

Creating a MySQL database on AWS RDS

Configuring security groups for database access

Connecting the RDS instance with MySQL Workbench

Managing database operations (creating tables, inserting data, querying)

🚀 Technologies Used
AWS RDS (Relational Database Service)

MySQL Workbench

Git & GitHub

Command Line (Git Bash)

🔧 Setup Instructions
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/mansiSaini-15/aws-rds-mysql-project.git
cd aws-rds-mysql-project
2. MySQL Workbench Setup
Open MySQL Workbench

Create a new connection using:

Hostname: AWS RDS Endpoint

Port: 3306

Username: Provided AWS RDS username

Password: Provided AWS RDS password

3. AWS RDS Configuration
Ensure your AWS RDS instance is publicly accessible.

Add your IP address to the inbound rules of the security group.

💻 Usage
Perform SQL queries

Create, read, update, and delete tables in the database
