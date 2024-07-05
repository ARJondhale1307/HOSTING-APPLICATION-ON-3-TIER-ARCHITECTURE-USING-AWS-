# HOSTING-APPLICATION-ON-3-TIER-ARCHITECTURE-USING-AWS-
## Introduction:

In this project, I create a 3-tier architecture for host application and database.  Three-tier architecture is a well-established software application architecture that organizes applications into three logical and physical computing tiers: the jump-server tier, or user interface; the application tier, where data is processed; and the database tier, where application data is stored and managed.
## Prerequisite:
1. Basic understanding of AWS and Mysql 
2. SHH key
3. Knowledge about linux commands

**Step 1: Create Architecture using VP**
**Step 2: Create 3 instance using EC2 service** 
**Step 3: Create database using RDS (Relational Database Service)**
**Step 4: Configure Jump server**
**Step 5: Configure Application Server**
**Step 6 : Configure DB-server**
**Step 7: Heat Public IP address of Jump Server**

## Summury:

In this 3-tier application project, I have hosted an application using **nginx** for reverse proxy in jump server and use **tomcat** java-based web server to host the application. RDS is used to create database used engine is **mariadb** for store application database and also use AWS services like **EC2**, **VPC** etc.