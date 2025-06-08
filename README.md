# AUTOMATED-REPORT-GENERATION-TASK2-
COMPANY: CODTECH IT SOLUTIONS

NAME: KOPPOLU NISHMITHA

INTERN ID: CT06DL1266

DOMAIN: PYTHON PROGRAMMING

DURATION: 6 WEEKS

MENTOR: NEELA SANTOSH

TASK DESCRIPTION:

The objective of this task is to automate the creation of a structured and visually organized PDF report from a CSV data source using Python. This process is particularly useful in real-world applications where transforming raw data into readable reports is essential for analysis, record keeping, and professional presentation.

Task Overview: In this task, we developed a Python script that reads employee-related data from a CSV file and generates a comprehensive PDF report using the reportlab library. The report displays the data in a structured tabular format, making it easy to read and analyze. The goal is to ensure that data collected in raw form can be presented in a formal document suitable for meetings, HR evaluations, or managerial overviews.

Steps Performed:

CSV File Creation: A sample data file named employee_data.csv was created containing information such as employee names, their respective departments, designations, and salaries.

Reading the Data: The csv module in Python was used to read data from the file. The script reads each row and stores it in a list for further processing.

PDF Setup Using ReportLab: The core functionality for PDF creation was implemented using the reportlab library. Necessary modules like SimpleDocTemplate, Table, and TableStyle were imported to design the document layout and apply styling such as font size, alignment, background color, and border formatting.

Tabular Data Formatting: The list of employee data retrieved from the CSV file was passed into a table object, which was then added to a list of elements for the PDF document.

Report Building: A new PDF file named employee_report.pdf was created in the same directory using SimpleDocTemplate. The script compiled all elements into a single structured document and generated the final output. A confirmation message was printed in the terminal upon successful completion.

Technologies and Libraries Used:

Python 3.13: Main programming language used for writing the script.

CSV Module: For reading structured tabular data from a .csv file.

ReportLab: A robust library for generating PDF files programmatically, enabling customization of layouts and formatting.

OUTPUT:
![Image](https://github.com/user-attachments/assets/94bb8147-accf-4645-87f9-7247e35c376e)
