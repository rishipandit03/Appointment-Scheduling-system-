----------------------------------------------->>>>>>>> Appointment Scheduling System <<<<<<<<<<--------------------------------------------
The system is implemented using Java and includes the following main classes:

1.Appointment Class: Represents the details of an appointment (user, date, time, description).
2.User Class: Represents a user with basic login functionality.
3.AppointmentManager Class: Manages appointment scheduling, cancellation, and data persistence.
4.AppointmentScheduler Class: Main class to interact with the user and manage the scheduling process.

------------------------------------------------>>>>>>>> Requirements <<<<<<<<--------------------------------------------------------------
Before running the project, ensure you have the following:

Java: Version 8 or above.
IDE: Any Java IDE like IntelliJ IDEA, Eclipse, or NetBeans.
JDK: Java Development Kit 8+.
Operating System: Windows, macOS, or Linux (as long as Java is installed).

------------------------------------------------->>>>>>>> Project Setup <<<<<<<<-------------------------------------------------------------
1. Clone the Repository
To clone the project, open a terminal and run:
git clone https://github.com/your-username/appointment-scheduling-system.git
2. Navigate to the Project Directory
cd appointment-scheduling-system
3. Open the Project in Your IDE
Open the project folder in your preferred IDE (e.g., IntelliJ IDEA, Eclipse).
Ensure that your IDE is set up to use Java 8 or later.
4. Install Dependencies (if needed)
This project does not have any external dependencies (it uses core Java libraries), so you can skip this step.

------------------------------------------------>>>>>>>> Running the Project <<<<<<<------------------------------------------------------------
1. Compile and Run the Program
In your IDE, open the AppointmentScheduler.java class (located in the src folder).
Run the main method. This will start the program and prompt you to log in.
2. Login to the System
The default login credentials are:

Username: testUser
Password: password123
Once logged in, you will see a menu with the following options:

Schedule an appointment.
Cancel an appointment.
List all appointments.
Exit the system.
3. Using the System
Schedule an Appointment: Enter a date and time (in yyyy-MM-dd HH:mm format) for your appointment and provide a brief description.
Cancel an Appointment: Enter the date and time of the appointment you want to cancel.
List Appointments: View all currently scheduled appointments.
Exit: Exit the system when you're done.
Appointments are saved to a file (appointments.ser) in the project directory, ensuring that they persist between program runs.
