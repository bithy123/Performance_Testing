# JMeter Performance Testing 
## 📌 Project Summary
This project focuses on **Performance Testing** of the **Restful-Booker API** using **Apache JMeter**.  
The testing covers **Login**, **Create Booking**, and **Search Booking** scenarios with both **Load Testing** and **Stress Testing**.  
## 🛠️ Technologies Used
- **Apache JMeter**  
- **Gaussian Random Timer** (Deviation 2000ms, Constant Delay 500ms)  
- **Excel (for report documentation)**  
- **GitHub (for submission)**
## ⚙️ Prerequisites
- JMeter installed and added to system path  
- Java 8 or Java 11 installed  
- Git installed (optional for cloning repo)  
## ▶️ How to Run This Project
1. Clone the repository  
2. Open `booking.jmx` in **JMeter**  
3. Run using **GUI** or from **CLI**
## 📑 How to Generate Report
1. Delete the previously generated **Reports** folder from the project  
2. Open **Command Prompt** in the **bin folder** of your JMeter installation location  
3. Run the following command (replace filename with the actual file name you are running):  
4. jmeter -n -t <file-name>.jmx -l <file-name>.jtl -e -o Reports

## Load Testing Reports
<img width="1047" height="600" alt="Load_Testing_report" src="https://github.com/user-attachments/assets/c183a0ae-a447-46a0-a3fc-0e8ca9564b15" />



<img width="1696" height="786" alt="Load_Test" src="https://github.com/user-attachments/assets/0e4bc7e5-9eef-49fa-a27f-31c6c06ee846" />




## Stress Testing Reports
<img width="1170" height="382" alt="Stress_testing_report" src="https://github.com/user-attachments/assets/0684338f-36db-4abf-b2c8-9b989f5e9c74" />


<img width="1692" height="793" alt="Stress_testing" src="https://github.com/user-attachments/assets/9f17a7f9-6317-4401-afa2-e44ea118c540" />








