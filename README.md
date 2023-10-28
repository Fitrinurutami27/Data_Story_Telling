# Data_Story_Telling_and_Responsible_Analytics_Practices
## Dataset Description
### Monitoring Social Assistance Distribution
This dataset contains information about the COVID-19 Social Assistance program in DKI Jakarta. This data includes the number of aid recipients from two entities, namely the Ministry of Social Affairs of the Republic of Indonesia (Kemensos RI) and the Provincial Government of DKI Jakarta. There are two groups of recipients, namely those with DKI ID cards and those with non-DKI ID cards who live in Jakarta. The total recipients of assistance from these two entities are 2.4 million families vulnerable to COVID-19. This dataset can be used to monitor the distribution and effectiveness of social assistance programs during the PSBB period in DKI Jakarta.

Data Source: Monitoring Social Assistance Distribution https://data.jakarta.go.id/visualization/detail/188
The dataset has 9 columns and 2693 rows.
Data dictionary:
- No: contains the sequential number in a table.
- City Area: contains recipients (KK) based on city areas in Jakarta who receive social assistance.
- Subdistrict: contains recipients (KK) based on subdistricts in Jakarta who receive social assistance.
- Village: contains Social Assistance Recipients (KK) according to sub-districts in Jakarta who receive social assistance.
- RW: contains recipients (KK) according to RW in Jakarta who receive social assistance.
- Recipients (KK): contains the number of recipients (KK) in the Jakarta area who receive social assistance.
- Distribution Schedule: contains the schedule for the distribution of social assistance that will be distributed to each region.
- Distribution Date: contains the distribution date of social assistance that has been distributed to each region.
- Sembako: contains basic necessities for social assistance such as rice, oil, biscuits and soap.

### Preparation for processing data:
- Prepare the Code to Use
- Python Version 3.11.4
- Pandas, Numpy, Matplotlib, Seaborn packages
- 
### Data cleaning
- Purging data because there are two columns that do not match the data type, namely the distribution schedule and distribution date columns
- Replace missing values ​​with the average value

### Exploratory Data Analysis
- Visualization of the number of Top 5 Aid Recipients (KK) by Regency
- Visualization of the highest and lowest number of recipients (KK) based on city area
- Visualization of the lowest number of aid recipients (KK) based on RW
- Visualization of the lowest percentage of five recipients (KK) based on sub-district
- Visualization of percentage distribution of food types

## Responsible Analytics Practices
### Data Privacy and Best Practices
Data Privacy Laws Data privacy laws, also known as data protection laws, are legal regulations governing the collection, use, processing, storage and sharing of personal data. This law is designed to protect the privacy and rights of individuals by imposing certain obligations on organizations, businesses and other entities that handle personal data.
The Data Privacy Law is divided into:
- General Data Protection Regulation (GDPR): Applicable in the European Union, GDPR is one of the most comprehensive data privacy regulations, setting high standards for data protection.
EXAMPLE OF ITS IMPLEMENTATION:
Have organizations collect, process and store personal data with explicit permission from individuals, and report data breaches within 72 hours.
- FERPA (Family Educational Rights and Privacy Act): federal law in the United States that regulates privacy and access to educational data. FERPA gives parents and students the right to access and control their education data.
EXAMPLE :
maintain the confidentiality of student academic data, including grades, academic records and other personal information. Only this agency provides access and must not provide this information to other parties without permission.
- HIPAA (Health Insurance Portability and Accountability Act): federal law in the United States that regulates the privacy and security of health information. HIPAA applies to healthcare entities and sets privacy and security standards for medical data.
EXAMPLE :
A hospital or medical practice must encrypt their patients' medical data and limit access to personal medical information to authorized staff. They must also give patients the right to access their medical history and decide with whom they want to share their medical information.
- IRB (Institutional Review Board): ethics committee tasked with assessing, monitoring, and protecting the rights and welfare of human research subjects in scientific research. The IRB ensures that research involving human subjects is conducted ethically and adheres to privacy and security standards.
EXAMPLE :
A researcher who wishes to conduct clinical studies on patients to collect medical data must submit a research proposal to the IRB which acts as an ethics body. The IRB will assess the proposal to ensure that the research is safe, ethical, and protects the privacy and rights of research subjects.
- PCI (Payment Card Industry): data security standard that applies to organizations that manage credit card payment data. It regulates payment data security and requires organizations to protect customer credit card information.
EXAMPLE :
An e-commerce store that accepts credit card payments must ensure that customer credit card data is encrypted during the payment process. They must also comply with security standards such as regular security testing and limiting access to credit card data to only staff who need access to process transactions.
