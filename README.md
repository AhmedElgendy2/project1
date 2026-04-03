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
I faced a Git push rejection error Becuase different between local and GitHub.  
I solved it using:  
git pull origin master --rebase  
then pushed successfully.  

---

## Bonus Tasks Completed  
- Deployed the application to Cloud Foundry    
- Tested the OData service using Postman with the following query options: $top, $filter, $select, $orderby  
- Performed a POST request on a mock OData service and documented request + response  

---

## Postman Testing  
The deployed OData service was tested using Postman. The following query options were successfully executed:  
- $top: Retrieved a limited number of records (e.g., top 5 products)  
- $filter: Filtered data based on conditions (e.g., price greater than 20)  
- $select: Retrieved specific fields such as ProductName and Price  
- $orderby: Sorted the results based on price in descending order  

The Postman collection and screenshots are available in the docs folder.  

---

## OData POST Operation  
A POST request was performed using a mock OData service.  

Request Body:  
{
    "ID": 103,
    "Name": "Wireless Mouse",
    "Description": "Wireless Mouse",
    "ReleaseDate": "2022-11-22T00:00:00",
    "DiscontinuedDate": null,
    "Rating": 5,
    "Price": "50"
}

The request was successfully executed, and the response confirmed that the data was created.  
Screenshots of the POST request and response are available in the docs folder.  

---


## Deployed Application URL  
(https://9a58d515trial-dev-northwind-app.cfapps.us10-001.hana.ondemand.com)  

---

## Screenshots  