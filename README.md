Project Workflow

Step 1: Read Certificates from SFTP Folder
1.	Connect to the SFTP server.
2.	Access the folder containing the certificates.
3.	Read the list of certificates available in the folder.

   
Step 2: Extract Name and Date from Certificates using OCR
1.	Use OCR technology to extract the name and date of completion from each certificate.
2.	Store the extracted information in a structured format for further processing.

   
Step 3: Validate Name and Date against Accomplished Employees
1.	Read the list of accomplished employees from an Excel file.
2.	Compare the extracted name from the certificates with the names of accomplished employees.
3.	If a match is found, proceed to validate the date of completion.

   
Step 4: Validate Date of Completion
1.	Check if the date of completion extracted from the certificate is within the last 90 days.
2.	If the date is within the specified range, mark the employee as qualified.

   
Step 5: Grant Application Access
1.	Grant application access to employees who meet the qualification criteria.
2.	Log the details of qualified employees and their certifications.

   
Project Implementation Details

1.	Technology Stack: UiPath for automation, OCR technology for text extraction, Excel for storing employee data.
2.	Error Handling: Implement error handling mechanisms to manage exceptions during the validation process.


