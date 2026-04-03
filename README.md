<img width="1919" height="1032" alt="Post" src="https://github.com/user-attachments/assets/0d14c90e-d668-444c-a095-df043d6cb6db" />
<img width="1919" height="1032" alt="Get-top" src="https://github.com/user-attachments/assets/0f001ec7-0a9d-4998-9180-3adffa5cafcf" />
<img width="1913" height="1035" alt="Get-select" src="https://github.com/user-attachments/assets/598a08ec-9b64-440d-87d8-c150ada8aece" />
<img width="1914" height="1029" alt="Get-orderby" src="https://github.com/user-attachments/assets/d491cbc7-802b-410c-9624-ef76a168ffca" />
<img width="1918" height="1034" alt="Get-Filter" src="https://github.com/user-attachments/assets/ba4e1fe8-8de7-4cf2-8d94-77557c0f011a" />
<img width="1887" height="946" alt="Depoy2" src="https://github.com/user-attachments/assets/f9cc90ec-b805-4a20-9693-fe8fc87c1fc6" />
<img width="1080" height="144" alt="Deploy" src="https://github.com/user-attachments/assets/81f7bdb4-c466-46d9-b979-1d27bebc9695" />
# Northwind Products Fiori Application  

## Description  
This is an SAP Fiori List Report application built using SAP Business Application Studio.  
It displays product data from the Northwind OData service and allows users to explore product details.  

---

## Architecture Overview  
The application is developed in SAP Business Application Studio (BAS).  
A destination in SAP BTP is used to connect securely to the Northwind OData service.  
The app is deployed to Cloud Foundry, where it runs and can be accessed through public URL.  

---

## Setup Instructions  

1. Clone the repository  
2. Install dependencies:  
   npm install  

3. Run the app:  
   npm start  

4. Login to Cloud Foundry:  
   cf login  

5. Build the project:  
   mbt build  

6. Deploy:  
   cf deploy mta_archives/project1.mtar  

---

## OData Entity Used  
The selected entity is **Products**.  
It was chosen because it contains useful business data like product name, price, and category.  

---

## Challenges Faced  
I faced an issue during deployment where the application status showed 0/1. After investigating, I found that the problem was related to limitations in the trial account.
I also encountered an issue with the Build Work Zone. After downloading it, there was no need to create it, and when I navigated to the authorization settings, no configuration options were available.

---

## Bonus Tasks Completed  
- B1   
- B2 
- B5 
---


## Deployed Application URL  
(https://9a58d515trial-dev-northwind-app.cfapps.us10-001.hana.ondemand.com)  

---
<<<<<<< HEAD

## Screenshots  
=======
>>>>>>> ae0de18 (update README as required)
