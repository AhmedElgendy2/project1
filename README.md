# Northwind Products Fiori Application  

## Description  
This is an SAP Fiori List Report application built using SAP Business Application Studio.  
It displays product data from the Northwind OData service and allows users to explore product details.  

---

## Architecture Overview  
The application is developed in SAP Business Application Studio (BAS).  
A destination in SAP BTP is used to connect securely to the Northwind OData service.  
The app is deployed to Cloud Foundry, where it runs and can be accessed عبر public URL.  

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
I faced a Git push rejection error بسبب اختلاف بين local و GitHub.  
I solved it using:  
git pull origin master --rebase  
then pushed successfully.  

---

## Bonus Tasks Completed  
- Deployed the application to Cloud Foundry    

---

## Deployed Application URL  
(https://9a58d515trial-dev-northwind-app.cfapps.us10-001.hana.ondemand.com)  

---

## Screenshots  