# UiPath_ADV_Udemy_Sales_Price Project README (Completed)

## Project Overview

The UiPath_ADV_Udemy_sales_price project is a successfully completed automation solution designed to streamline the process of retrieving course information from Udemy based on specific criteria received via email. This project is fully functional and has successfully met the following objectives:

1. **Trigger**: The project is triggered by an email with an attached file named "Course Criteria.txt" and the subject "Courses Descriptions."

2. **Course Criteria Retrieval**: The robot effectively extracts the criteria for course selection from incoming emails.

3. **Web Scraping**: The robot reliably navigates to the Udemy website (www.Udemy.com), logs in, searches for courses matching the criteria, and scrapes the table results.

4. **Data Filtering**: Courses are filtered based on cost criteria provided in the email. Courses that fall within the specified range are retained, while those outside the range are deleted from the data table.

5. **Business Exception Handling**: The robot identifies and handles cases where course costs exceed the amount described in the input criteria, marking them as business exceptions.

6. **Report Generation**: The project successfully generates detailed reports, including course Name, Description, Instructor Info, Rate, Cost, and Status. The report is sorted in ascending order based on course cost.

## Additional Notes

- The project incorporates robust error-handling mechanisms to deal with system failures and ensure reliable performance.

- In the event of three consecutive system failures, the robot suspends the process for safety -using checkpoints- and sends an email to the IT team containing the latest screenshot.

- System failures trigger the saving of a screenshot for subsequent review by the IT team.

- The project adheres to best practices.

- Utilizing a currency converter API can further enhance the project's capabilities.


## Supervision
This project has been done under the supervision of **ADVANSYS-ESC**, providing guidance and support throughout the development process.
