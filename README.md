# Automated-Gold-Price-Updates-and-Email-Reporting-using-RPA
Automated Gold Price Updates and Email Reporting using RPA
# Introduction
This project utilizes Robotic Process Automation (RPA) technology with UiPath Studio to automatically update gold prices by region (Hanoi, Ho Chi Minh City, etc.) and send email reports to customers. This solution helps minimize errors caused by manual operations, saves time, and enhances decision-making efficiency for both individual investors and businesses.

**Key Features**
- **Automated Data Extraction:** Utilizes UiPath to collect gold price data from the CafeF website for each region.

- **Data Processing and Storage:** Data is formatted and stored in Excel files, supporting historical tracking and trend analysis.

- Chart Screenshot Capture: Automatically captures screenshots of gold price trend charts, making it easier for customers to observe market trends.

- Email Reporting: Generates personalized email content with attached Excel reports and chart images, then sends them to a predefined list of customers.

- Automated Completion Notification: Displays a notification once the email sending process is complete, ensuring stable and reliable operation.

# System Requirements
- Software:

+ UiPath Studio (version 2024.10.6 or newer)

+ Microsoft Excel 2019 or later

- UiPath Libraries:
+ UiPath.Excel.Activities
+ UiPath.Mail.Activities
+ UiPath.System.Activities
+ UiPath.UIAutomation.Activities

- Operating System: Windows 10 or later
