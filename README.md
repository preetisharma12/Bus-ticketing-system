# Bus Ticketing System

A Web-based Bus Ticket Booking and Management Application designed for managing sales, bus operators, schedules, customers, and ticket reservations.

## Project Overview
The main objective of this Java Web Application is to streamline and automate bus ticket booking and sales administration. It provides administrative controls to handle customer records, manage bus schedules, track ticket bookings, and log sales transactions efficiently.

## Tech Stack
* **Language:** Java, JSP, HTML, CSS, JavaScript, AJAX, jQuery
* **Database:** MySQL (`database.sql`)
* **IDE:** Eclipse IDE for Enterprise Java and Web Developers (Eclipse JEE)
* **Web Server:** Apache Tomcat (v8.5 / v9.0 / v10+)

---

## How to Setup and Run the Project

### Prerequisites
1. [Eclipse IDE for Enterprise Java Developers](https://www.eclipse.org/downloads/packages/) installed.
2. [Apache Tomcat Server](https://tomcat.apache.org/) downloaded and configured.
3. [MySQL Workbench](https://www.mysql.com/products/workbench/) or MySQL Server installed.

---

### Step-by-step Setup

#### 1. Database Setup
1. Open MySQL Workbench or MySQL Command Line.
2. Create a new database (e.g., `bus_db`).
3. Import and execute the `database.sql` file included in this repository to create the required tables and sample data.
4. Update the database connection credentials (URL, username, password) inside your Java database connection utility file (usually found under `src/` as `DBConnection.java` or `db.java`).

#### 2. Import Project into Eclipse
1. Clone or download this repository to your local machine.
2. Open **Eclipse JEE**.
3. Go to **File** > **Import** > **General** > **Existing Projects into Workspace**.
4. Select the root folder of the downloaded project and click **Finish**.

#### 3. Configure Server & Run
1. Ensure Apache Tomcat is added to Eclipse under **Window** > **Preferences** > **Server** > **Runtime Environments**.
2. Right-click on the project in the Project Explorer.
3. Select **Run As** > **Run on Server**.
4. Choose your Apache Tomcat Server and click **Finish**.
5. Open your browser and navigate to `http://localhost:8080/Bus-ticketing-system/` (or the corresponding context root path).
