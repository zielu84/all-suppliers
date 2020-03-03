# AllSuppliers

1. [PoC](#poc) 

   1.1. [Areas to check](#areas)

2. [Functional requirements](#functional)
3. [Non-Functional requirements](#nonfunctional)
   
   
<a name="poc"></a>
## 1. Proof of Concept

<a name="areas"></a>
### 1.1. Areas to check
1. GPS
2. Camera
3. Media
4. Contacts
5. UX
6. Compatibility

#### 1.1.1. GPS
1. Read GPS location from device (phone/tablet)
2. Display GPS location (check against native application)

#### 1.1.2. Camera
1. Default camera app is launched
2. [optional] After making photo photo is automatically passed to app

#### 1.1.3. Media
1. Photo gallery is launched for image selection

#### 1.1.4. Contacts 
1. Default contact app is launched
2. Contact details can be passed to app 
   - name
   - email
   - phone

#### 1.1.5. UX 
1. Application prompts for installing on desktop (home screen)
2. App is launched from icon

#### 1.1.6. Compatibility
1. All previous points must run on Android and iOS

<a name="functional"></a>
## Functional requirements
Can be skipped in PoC

1. Client can log in
2. Client can search for products/supplies
3. Client can see products/supplies as an list
4. List of products is sortable by
   1. Distance (default)
   2. Price
5. Client can select one or more products/supplies 
6. Client can adjust quantity of products/supplies (items/kilograms/liters)
7. Client can order selected products/supplies
8. Client can find his order on order list

<a name="nonfunctional"></a>
## Non-functional requirements

1. Use of some universal styles, for example [Materialize CSS](https://materializecss.com/)
2. Application will inform that is working in offline mode and cannot  proceed
