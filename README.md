# Salon Appointment Scheduler - Bash Script

![Salon Appointment Scheduler](screenshot.png)

## Introduction

The Salon Appointment Scheduler Bash Script is a command-line application designed to simplify the process of managing appointments at a salon. It allows salon staff to handle appointment bookings, services, and customer records efficiently.

## Features

- **Service Selection**: Users can choose from a list of available services offered by the salon.
- **Appointment Booking**: Users can book appointments by selecting a service, providing their phone number, and specifying the appointment time.
- **Customer Management**: The script manages customer information, such as names and phone numbers, and maintains records of their appointments.
- **Integration with PostgreSQL**: The script interacts with a PostgreSQL database to store and retrieve service details, customer information, and appointment records.

## Prerequisites

Before using the Salon Appointment Scheduler Bash Script, ensure you have the following set up:

- A PostgreSQL database with the necessary tables: `services`, `customers`, and `appointments`.
- Required database credentials and connection details properly configured in the script (`PSQL` variable).
- Bash shell environment to execute the script.

## Usage

1. **Clone the Repository**: Start by cloning this repository to your local machine.

   ```bash
   git clone https://github.com/your-username/salon-appointment-scheduler-bash.git
    ```
2. **Database Setup**: Ensure your PostgreSQL database is set up with the required tables (services, customers, and appointments). You can find the table structure in the database.sql file.

3. **Configuration**: Open the script (salon_appointment_scheduler.sh) in a text editor and configure the PSQL variable with your database connection details.

4. **Run the Script**: In the terminal, navigate to the project directory and execute the script.

```bash
    cd salon-appointment-scheduler-bash
    ./salon_appointment_scheduler.sh
```
5. **Follow the Prompts**: The script will guide you through selecting services, providing customer information, and booking appointments.

## Important Notes
- This script assumes a specific database structure and does not include extensive error handling. Ensure your database matches the expected structure.
- You should customize and enhance the script according to your specific requirements and error-handling needs.
- This script is provided as a basic example and should be extended for production use.

## Author
- Alish Bista