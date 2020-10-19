# Title

**do not publish this please. It is still a draft**

## Description (mandatory)

# How To Integrate with SAP LBN APIs - Step by Step Guide



**You can also opt in for SAP Professional Services to help guid you through the process,
please contact us via ICC@SAP.COM**

![](Upload/selfvsenterprisAPI.png)

![](Upload/slide4github.jpg)

**You can also opt in for SAP Professional Services to help guid you through the process,
please contact us via ICC@SAP.COM**

**In case of questions please raise an Issue here in [this repository](https://github.wdf.sap.corp/D055590/logistics-business-network-integration/issues)**


## 0.) get yourself familiar with SAP LBN

![](Upload/0.png)

Type	Name	Latest commit message	Commit time

* (Sabine) general overview <link>
* (Ravish) api overview <link>
* partner edge <link>

## 1.) Get yourself familiar with SAP LBN and APIs

![](Upload/Picture1.png)

- API Links
  
  [Consumer API for Dock Appointment Scheduling](https://api.sap.com/api/GenericAppointment_Out/overview)

## 2.) Request Tenant and Technical User

![](Upload/2.png)

(Joy/Baoning, Leon)
NEW PROCESS FROM LEON, central e-mail for tenant request - NEED TO BE REFLECTED IN HERE
ADD ALSO SLIDES FROM NATALIE FOR TENANT TYPE EXPLANATION.

To be able to communicate to LBN carriers or network partners have to request for a free test B2B account. Click on the below link and follow the steps in the [link](https://www.sapstore.com/solutions/46401/) to request for a new B2B test account in LBN.

(Ravish System Connection App)
After completion of your request, you will be provided with a login URL to SAP LBN and also credentials. Please use these URL and credentials to access LBN UIs and for maintaining configurations

(Ravish -> Benito)
For all the LBN provider APIs(inbound to LBN), when you call our endpoint, you would need to  procure an OAuth 2.0 client Id and secret. This can be procured by reporting an incident. Use the application component - SCM-LBN-INT in [sap support portal](support.sap.com) Please mention the LBNID created for you account. To know the LBN ID, login to SAP LBN  and open the business profile tile.

The OAuth Id will be needed by you to call our endpoint for all the provider APIs.

The [LBN endpoint](ttps://l20398-iflmap.hcisbp.eu1.hana.ondemand.com/http/v1h) that you need to call:


During this step, SAP Will invite your test tenant to a dummy shipper tenant for test puruposes.  You would have to accept the invitation by logging in to you LBN tenant and Navigating to Manage Invitation tile.


## 3.) Integrate against SAP LBN APIs

![](Upload/3.png)

- Postman Example (Ravish)

https://github.wdf.sap.corp/D055590/logistics-business-network-integration/blob/master/P44%20Visibility%20Tracking%20FTL%20End2End%20TestCase.postman_collection.json

https://github.wdf.sap.corp/D055590/logistics-business-network-integration/blob/master/P44%20Visibility%20Tracking%20FTL%20End2End%20Testing.postman_environment.json

When the API s are ready, you can configure the endpoints to our test landscape. To configure them, you will have to login to SAP LBN and maintain your endpoints that SAP LBN needs to call. 

Below [application link](https://help.sap.com/viewer/185742008f2c477ca789b93675b0ec6c/LBN/en-US/011fbcd85017450587389c4a10190077.html) help will guide you on how to configure you endpoint in our app.

## 4.) Testing 

![](Upload/4.png)

- Ravish (Hardcoded Test Payload & Endpoint)

## 5.) Release for Productive Usage

![](Upload/5.png)

(Joy/Baoning/Leon)
* Get onboarded to LBN productive tenant

To be able to communicate to LBN carriers or network partners have to request for a free productive account. Click on the [link](https://www.sapstore.com/solutions/46399/) and follow the steps in the link to request for a new productive account in LBN.

(Ravish)
* Request access to LBN endpoint for productive tenant

For all the LBN provider APIs, when you call our endpoint, you would need to request or procure an OAuth 2.0 client Id and secret. This can be procured by reporting an incident . Use the  application component - SCM-LBN-INT in sap support portal(support.sap.com) Please mention the LBNID created for you account. To know the LBN ID, login to SAP LBN and open the business profile tile.

The OAuth Id will be needed by you to call our endpoint for all the provider APIs.

The [LBN endpoint](https://l20398-iflmap.hcisbp.eu1.hana.ondemand.com/http/v1
) that you need to call:

The step above is same as the one you have request for test access. But the OAuth ID and secret will be separate for productive access.

(Ravish)
* Configure system connection in LBN for productive tenant

Follow activities as done in step 6 to your productive URLs

(Ravish)
* Quality Gate - Smoke test in productive
Raise an incident in SCM-LBN-INT for a smoke test. We will facilitate an example order to your system . This activity will be done manually. 

## Requirements

## Download and Installation

## Known Issues

## How to obtain support (mandatory(

## Contributing

## License (mandatory)
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
