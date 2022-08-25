# TRIFORCIA CRUISE TRAVEL AGENCY APP PROJECT

## 1.  General:

Triforcia is a Cruise Travel Agency company. Triforcia agency currently maintaining business processes in classical way and mostly by running business by assigning manual tasks to employees. Company has a website for customers to interact and check deals. The website is also used for advertisement purpose. All customer communications and processes handled by emails, phone calls and excel sheets.

Company can’t keep up with increased customer volume and agile response requirements. Old manual business processes are not enough to keep growth rate in a maximum level.

Triforcia leadership decided to use a CRM system to improve separate current business process efficiency and offer better service to current or potential customers.

Salesforce is a well-known CRM system and leadership wants to see a proof-of-concept Salesforce application that can cover all the emerging requirements.

## 2.  Company Information:

Triforcia Cruise Agency is providing staying and entertaining services on Cruise Ships. Customers can book a room on a ship and select pre-defined entertainment packages during sail duration. 

They can attend standard events on the ship. Also, they can attend specific events as well with extra costs. Based on the route of the ships, some specific events can be sold to customers in addition to ship room or cabin allocation.

Triforcia Cruise Agency is not the owner of the ships. Cruise ship rooms are being sold by Triforcia according to mutual contracts and booked to customers with some added commissions. In addition to ship owners, customers also need to sign contract in every purchase. 

## 3.	Requirements:

  - A Salesforce App needs to be created on Salesforce platform so that all stakeholders can reach any provided services from any device (desktop, laptop, mobile) or any place.

  - App theme needs to align with company’s current branding. Branding logo and color palette should be same as website logo and branding style.

  - Basic sale process should start with a Campaign (Advertisement, Email, Phone etc). Then potential customers need to be put into lead category. Once Leads shows interest about buying offered products or services, they need to be converted to Guests, Members and Deals records.

  - Dynamic data like ship, cabin, product and contract needs to be stored separately to make data more manageable in case of future updates. Also, relation between these objects needs to be defined correctly so that for example if a ship has been deleted related cabins also needs to be deleted from the database.

  - For strategic planning, also expanse and income records need to be created from every completed sale. 

  - An internal approval process needs to be set for contract sign off. For initial phase, contracts that have commission rate less than %20 will be allowed to be signed off by deal owner. If it is more than %20, direct manager of deal owner needs to approve signing off of the related contract. The approval process needs to be created in optimum way so that future approval steps or conditions can be added or removed easily and quickly.

  - In addition to business process, an additional emergency process needs to be defined for urgent health evacuation or broken ship evacuation. In this process, nearby hospitals and helicopter agencies will be our additional stakeholders. Since the process requires special attention and mostly human interactions, this process will be handled on a separate page as tasks and responsible users will handle tasks urgently under supervision of their managers. The process should include necessary assignments, notifications, emails, dashboards for available nearby hospitals, helicopter agencies, instant real-time weather conditions, ship, hospital, helicopter details etc.

  - As best practices, use standard objects and business processes as much as possible. Instead of creating new custom objects try to use record types to keep integrity of the data.

  - Every object data including standard objects and custom objects needs to be reportable. Leadership and ends users should have necessary dashboards and reports available for all app data based on their permission allowance.

  - Triforcia Cruise Travel Agency have some historic data available from previous processes or applications that can be incorporated to this Salesforce app. These data also need to be imported to Salesforce environment. 

  - In addition to above historic data there are also some historic data on a separate Salesforce org that needs to be shown as separate tab on current Salesforce org. In order to fulfill this requirement, a cross org connection needs to be established and related data needs to be present on a separate custom tab in same app.

  - Previously used systems like gmail, outlook, telephony etc. needs to be integrated applications so that end users can use them during marketing and sale process.

  - Validations or filters needs to be placed for any kind of required fields or any kind of processes like avoiding double booking same room to different customers or not being able to close a deal without a contract selection etc. 

## 4. Solutions:

  - Lightning App (A-1):
  
    - Theme Customization
    - Branding
    - Tab Order
    
  - Lightning App Page (Emergency page) (A-2):
 
    - Visualforce pages
    - Embeded iFrames
    - LWC Weather Component

  - Standard / Custom Objects
 
  - Master Detail and Lookup relations
 
  - Record Types for Different Processes
  
  - Custom record layouts for the object record pages
  
  - Formula fields
  
  - Custom picklists
  
  - Dashboards:
  
    - Charts
    - Reports
  
  - Reports:
  
    - Standard
    - Custom
    - Joined Reports

  - Approval process (Contract object)
  
  - Users and permissions
  
  - Flow for Expense and Income calculations
  
  - Telephony integration
  
  - Gmail Integration
  
  - Outlook Integration
  
  - Creating API connection
  
  - Creating Apex class and helper classes
  
  - Using Apex Trigger for Emergency Task logic
  
  - Apex trigger for cabin occupied
  
  - Data import to import sample data
  
  - Cross Org integration for Historic data
  
  - Custom Notifications
  
  - Lookup Filters

## 5.	Attachments:

### A-1:

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580347-86fac0b9-3f7c-457d-9f86-76c244816488.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580451-ffe88c82-666d-4838-9bed-3ab85a44bb88.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580517-20b86fe9-b7f4-4329-b5e8-7765322b724c.png">
  
  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580594-674de759-e2bf-4ee3-8a7e-78ec8ca89794.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580651-14f7fb12-08cb-4bb0-8d2c-5363e9a1594a.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186580713-20ff4d37-1674-4be8-8bc2-de18dc022b08.png">
  
  <img width="1268" alt="image" src="https://user-images.githubusercontent.com/33948183/186579474-a8bf2a1a-6a0e-4720-8c43-b53a287a31fe.png">
  
  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186579936-a6581452-f23b-4982-a84c-b59d8d83867b.png">


### A-2:

  
