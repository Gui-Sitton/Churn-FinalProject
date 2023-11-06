# Churn-FinalProject

Communications operator Interconnect would like to be able to predict its customers' churn. If it is discovered that a user is planning to switch operator, the company will offer them promotional codes and special plan options. Interconnect's marketing team has collected some personal data from its clientele, including information about their plans and contracts.

### Interconnect Services

Interconnect mainly provides two types of services:

1. fixed telephony. The telephone can be connected to several lines at the same time.
2. Internet. The network can be established via a telephone line (DSL, *digital subscriber line*) or via a fiber optic cable.

Some other services provided by the company include:

- Internet security: antivirus software (*DeviceProtection*) and a malicious website blocker (*OnlineSecurity*).
- A dedicated technical support line (*TechSupport*).
- Cloud file storage and data backup (*OnlineBackup*).
- TV streaming (*StreamingTV*) and a movie directory (*StreamingMovies*).

Customers can choose between making a monthly payment and signing a 1 or 2 year contract. They can use various payment methods and receive an electronic invoice after the transaction.

### Data Description

The data consists of files obtained from different sources:

- `contract.csv` - contractual information;
- `personal.csv` - personal customer data;
- `internet.csv` - information about Internet services;
- `phone.csv` - information about telephone services.

In each file, the `customerID` column contains a unique code assigned to each customer. The contractual information is valid from February 1, 2020.
