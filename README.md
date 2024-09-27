# Refugees-Status-Application-Systsem

This Application Management System allows users to manage applications, particularly for processing refugee status. The system implements a simple menu-driven interface that supports Create, Read, Update, Delete (CRUD) operations, as well as integrity audits on applications

##Features

-Create Application: Add new applications with unique IDs and applicant details. -Read Application: Retrieve application details by ID. -Update Application: Modify existing application data. -Delete Application: Remove applications from the system. -Process Refugee Status: Update application status to processed. -Audit Application Integrity: Perform integrity checks on applications and log results.

Data Structures
applications: A dictionary to store application details, where each application is indexed by its unique ID. Each application includes:

applicant_data: Information about the applicant (name and country).
status: Current status of the application (e.g., pending, processed).
integrity_checked: Boolean indicating if the integrity of the application has been checked.
integrity_audit_log: A dictionary to log the results of integrity audits for each application, indexed by a unique integrity ID.

Usage
To run the program, ensure you have Python installed. You can execute the script directly. The program will present a menu for interaction.

Start the program: Run the script.
Choose an option: Enter a number (1-7) to select an action.
Follow prompts: Provide necessary inputs based on the selected action.
Menu Options
Create Application: Input application ID, applicant name, and country.
Read Application: Input application ID to view details.
Update Application: Input application ID and new details for modification.
Delete Application: Input application ID to remove it.
Process Refugee Status Application: Input application ID to process.
Audit Application Integrity: Input integrity audit ID and application ID to perform an audit.
Exit: Exit the program.
Example
Menu:
1. Create Application
2. Read Application
3. Update Application
4. Delete Application
5. Process Refugee Status Application
6. Audit Application Integrity
7. Exit

## Requirements
- Python 3.x

## Contributing
- Feel free to contribute by modifying the code, improving functionality, or adding new features. Submit your changes via pull requests.

## License
- This project is open-source and available under the MIT License.
