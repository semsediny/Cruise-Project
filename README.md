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

  - Standard / Custom Objects (A-3):
 
  - Master Detail and Lookup relations (A-4):
 
  - Record Types for Different Processes (A-5):
  
  - Custom Record Layouts for the Object Record Type Pages (A-6): 
  
  - Formula fields (A-7):
  
  - Custom picklists (A-8):
  
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

  <img width="1262" alt="image" src="https://user-images.githubusercontent.com/33948183/186581314-99a8087f-c24a-4543-914e-3d3d48995230.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186581457-7281c98d-ceb8-4322-8566-5549c0327867.png">
  
  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186582051-dd9c0768-3e2f-4c3b-99d8-fee2b6d5d8ef.png">
  
  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186582423-aea68cd3-38d8-42f3-83f0-831b79819800.png">

  <img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186582515-229364c8-139a-4eee-8847-e0dfcfa09b3f.png">
  
####  Ship Map
  
    <apex:page showHeader="false">
      <apex:iframe src="https://www.cruisemapper.com/"/>
    </apex:page>

#### Hospital Map

    <apex:page >
      <apex:iframe src="https://maps.google.com/maps?q=Florida%20hospitals&t=&z=7&ie=UTF8&iwloc=&output=embed" frameborder="0" scrolling="true" id="theIframe"/>
    </apex:page>
    
#### Weather Map

##### HTML

    <template>
      <lightning-card title={getCityName}>
          <lightning-layout>
              <lightning-layout-item size="6" medium-device-size="4" padding="around-small">
                  <lightning-combobox name="cities"
                      label="Cities"
                      value={value}
                      placeholder="--Select--"
                      options={options}
                      onchange={handleChange} >
                  </lightning-combobox>
              </lightning-layout-item>
          </lightning-layout>
          <lightning-layout>
                  <lightning-layout-item size="3" medium-device-size="4" padding="around-small">
                      <lightning-card icon-name="standard:topic" title="Current Temperature">
                          <div class="slds-align_absolute-center color-blue">
                              <template if:true={result}>
                                  {getConvertedTemp}
                              </template>
                          </div>
                      </lightning-card>
                  </lightning-layout-item>
                  <lightning-layout-item size="3" medium-device-size="4" padding="around-small">
                      <lightning-card icon-name="utility:flow" title="Current Wind Speed">
                          <div class="slds-align_absolute-center color-grey">
                              <template if:true={result}>
                                  {getCurrentWindSpeed}
                              </template>
                          </div>
                      </lightning-card>
                  </lightning-layout-item>
                  <lightning-layout-item size="3" medium-device-size="4" padding="around-small">
                      <lightning-card icon-name="standard:calibration" title="Precipitation">
                          <div class="slds-align_absolute-center color-green">
                              <template if:true={result}>
                                  {getCurrentPrecip}
                              </template>
                          </div>
                      </lightning-card>
                  </lightning-layout-item>
              </lightning-layout>
          <lightning-map
              map-markers={mapMarkers}
              zoom-level={zoomLevel}>
          </lightning-map>
      </lightning-card>
    </template>

##### CSS

    .color-blue {
      background-color: #08a7da;
      height: 100px;
      color: white;
      font-family: Tahoma;
      font-size: 30px;
      font-weight: 500;
      border-radius: 25px;
    }
 
    .color-grey {
      background-color: rgb(11, 236, 74);
      height: 100px;
      color: white;
      font-family: Tahoma;
      font-size: 30px;
      font-weight: 500;
      border-radius: 25px;
    }
 
    .color-green {
      background-color:red;
      height: 100px;
      color: white;
      font-family: Tahoma;
      font-size: 30px;
      font-weight: 500;
      border-radius: 25px;
    }
    
##### JS

    import { LightningElement } from 'lwc';
    import performCallout from '@salesforce/apex/WebServiceLWC.performCallout';

    export default class WeatherLWC extends LightningElement {

    lat;
    long;

    mapMarkers = [];
    zoomLevel = 10;
    result;
    value;

    connectedCallback() {
        performCallout({location: 'Norfolk,VA'}).then(data => {
            this.mapMarkers = [{
                location: {
                    Latitude: data['cityLat'],
                    Longitude: data['cityLong']
                },
                title: data['cityName'] + ', ' + data['state'],
            }];
            this.result = data;
        }).catch(err => console.log(err));

    }

    get getCityName() {
        if (this.result) {
            return this.result.cityName + ' Information';
        } else {
            return '---'
        }
    }

    get getConvertedTemp() {
        if (this.result) {
            return Math.round((this.result.cityTemp * (9/5)) + 32) + ' deg';
        } else {
            return '--'
        }
    }

    get getCurrentWindSpeed() {
        if (this.result) {
            return this.result.cityWindSpeed + ' mph';
        } else {
            return '--'
        }
    }

    get getCurrentPrecip() {
        if (this.result) {
            return this.result.cityPrecip + " in"
        } else {
            return '--'
        }
    }

    get options() {
        return [
            { label: 'Arvada, CO', value: 'Arvada,CO' },
            { label: 'Austin, TX', value: 'Austin,TX' },
            { label: 'Sacramento, CA', value: 'Sacramento,CA' },
            { label: 'Raleigh, NC', value: 'Raleigh,NC' },
            { label: 'Chesapeake, VA', value: 'Chesapeake,VA' }
        ];
    }

    handleChange(event) {
        this.value = event.detail.value;
        performCallout({location: this.value}).then(data => {
            this.mapMarkers = [{
                location: {
                    Latitude: data['cityLat'],
                    Longitude: data['cityLong']
                },
                title: data['cityName'] + ', ' + data['state'],
            }];
            this.result = data;
        }).catch(err => console.log(err));
    }
  }

##### META XML

    <?xml version="1.0" encoding="UTF-8"?>
    <LightningComponentBundle xmlns="http://soap.sforce.com/2006/04/metadata">
        <apiVersion>55.0</apiVersion>
        <isExposed>true</isExposed>
        <targets>
            <target>lightning__AppPage</target>
            <target>lightning__HomePage</target>
            <target>lightning__RecordPage</target>
        </targets>
    </LightningComponentBundle>

### A-3:

<img width="654" alt="image" src="https://user-images.githubusercontent.com/33948183/186584523-e6e95d34-0b7f-46bc-a86b-5e45a26a738b.png">

### A-4:

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186584644-7b332a31-1f68-4677-b470-02c196260026.png">

### A-5:

#### Family and Company Record Types for Guest (Account) Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186585680-1fce9089-6582-458d-9f8c-5e22e51d1d18.png">

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186585943-fe4e360c-1ea4-42e1-9f58-f1b79769f281.png">

#### Family and Company Record Types for Lead Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186586139-d48d314b-47b5-4c5d-8c7c-e9654e84d53f.png">

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186586330-a797ae35-0c59-41ea-8234-5db4e683dfe9.png">

#### Ship Owner and Passenger Record Types for Contract Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186586399-d1156963-2921-41a7-9621-ea12264e3985.png">

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186586627-3bea56b7-6bae-424d-b38c-8ac4e0e1283b.png">

#### Cruise, Gulet and Yacth Record Types for Ship Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186586767-d3152631-9fac-40f0-a772-d8ae4d783361.png">

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186587020-167d20b9-3c4e-451c-8787-11ad3f1a130e.png">

### A-6:

#### Family and Company Custom Layouts for Guest (Account) Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186587727-37c9dd21-7575-4b8f-a5e8-b95d6616fff4.png">

#### Family and Company Custom Layouts for Lead Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186587893-3f068f43-1e67-4e10-a0c6-389a0bd2936e.png">

#### Ship Owner and Passenger Custom Layouts for Contract Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186588122-d9748286-1a7f-4af9-8d4f-5f41b1e0d3d5.png">

#### Cruise, Gulet and Yacth Custom Layouts for Ship Object

<img width="1284" alt="image" src="https://user-images.githubusercontent.com/33948183/186588248-72f31f61-f863-4d9c-a523-fdc8ac813edd.png">

### A-7:

#### Commision Formula Field on Deal Object

<img width="1280" alt="image" src="https://user-images.githubusercontent.com/33948183/186589362-31dfb6ce-f06d-4119-a3fd-e4a7abef8907.png">

### A-8:




