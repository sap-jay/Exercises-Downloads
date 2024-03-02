# Exercises for RAP ABAP Training

## 1. Set Up a Cloud Environment on SAP BTP
a.   Enable ABAP Environamet 

b.   Install Eclipse [Eclipse](https://www.eclipse.org/downloads/download.php?file=/oomph/epp/2023-12/R/eclipse-inst-jre-win64.exe)

c.   Install ADT in Eclipse [ADT](https://tools.hana.ondemand.com/latest)

d.   Install abapGIT in Eclipse [ABAP Git](https://eclipse.abapgit.org/updatesite/)


## 2. Migrate ABAP Program to the Cloud

Migrating an existing ABAP program to the cloud may present challenges. Document the process, challenges faced, and solutions:

## 3. Version Control with abap-Git and Open-Source Integration

Utilize abap-Git for version control and push you respective packages to the repositories available in this account

## 4. Build SAP Fiori Apps with ABAP RAP Managed - Beginners

Build an application using the ABAP RESTful Application Programming (RAP) Managed approach. 
In this context, we focus on the practical use case of [Manage Purchase Orders](https://github.com/sap-jay/Exercises-Downloads/blob/main/Use%20Case%20%3A%20Manage%20Purchase%20Order.md) or any oter realisting use case of your choise.

**Bigenner leval (Optional)** You can use an existing set of objects 
1. **Create a Package for Your Exercises**
   - Organize your exercises within a dedicated package.

2. **Creating the Database Tables**
   - Define the necessary database tables to store purchase order data.

3. **Creating the Core Data Services (CDS) Data Model**
   - Establish the core data services (CDS) data model to structure and manage data.

4. **Defining the CDS Data Model Projection**
   - Define projections within the CDS data model to tailor data for specific use cases.

5. **Enriching the Projected Data Model with UI Metadata**
   - Enhance the projected data model by adding UI metadata for improved user experience.

6. **Creating and Previewing the OData UI Service**
   - Generate and preview the OData UI service to facilitate interaction with the application.

7. **Implementing Basic Authorizations**
   - Set up basic authorizations ( DCL, Instence & Global )

**Intermediate Level** - Mandetory for all

8. **Enhance the BO Behavior – Early Numbering**  
9. **Enhance the BO Behavior – Determinations**                         
10. **Enhance the BO Behavior – Validations**  
11. **Enhance the BO Behavior – Actions** 
12. **Enhance the BO Behavior – Dynamic Feature Control** 

## 5. Build SAP Fiori Apps with ABAP RAP - Unmanaged Scenario

Explore the unmanaged scenario of building SAP Fiori apps with ABAP RAP. Use the same set of database tables created for managed scenario. 

 1.   Enhance the Data Model of the Base and Projected BO
 2.   Enhance the BO Behavior Definition and Projection
 3.   Implement the Base BO Behavior - Late Numbering
 4.   Adjust the UI Semantics in the Metadata Extensions
 5.   Implement the Base BO Behavior - Validations
 6.   Implement the Base BO Behavior - Actions
 7.   Implement the Base BO Behavior - Determinations
 8.   Enhance the BO Behavior with Side Effects
 9.   Implement the Base BO Behavior - Functions
 10.  Enhance the BO Behavior with Business Events
 11.  Implement the Base BO Behavior - Dynamic Feature Control


## 6. Side-by-Side Extensibility with SAP BTP ABAP Environment

Explore side-by-side extensibility with SAP BTP ABAP Environment, Base on the Odata Consumption Model and Custom Entity Implimentation in the sessions. 

1.   Consume an OData service - use an odata service form an available server or use a service from ES5 [SAP Gateway server (ES5)](https://developers.sap.com/tutorials/gateway-demo-signup.html)
2.   Consume a SOAP Web service - use a SOAP service from an available server or use an open SOAP service from [POSTMAN](https://documenter.getpostman.com/view/8854915/Szf26WHn)
3.   Consume a RFC via service consumption model - [Generate RFC Proxy Classes](https://developers.sap.com/tutorials/abap-environment-generation-rfc-proxy.html)

## 7. Use ABAP Cloud for Developer Extensibility (on-stack extensions)

Extend SAP applications using ABAP Cloud for developer extensibility. 

1.   Consume a released RAP BO - **Can use the objects created during our sessions or create your own objects Enable Extensibility & Release as per C0**
2.   Extend a RAP Business object
      -   Extend the behavior (determinations, validations, side-effects)
      -   Extend the data model (add additional fields)
      -   Extend the behavior (add an action)

