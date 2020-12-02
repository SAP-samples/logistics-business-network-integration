# !!! THIS PAGE IS UNDER CONSTRUCTION !!! #


# How To Integrate with SAP LBN APIs - Step by Step Guide

![](Upload/slide4github.jpg)

## 0.) Get an overview of SAP LBN

![](Upload/0.png)

![](Upload/whatisLBN.png)
[Click here](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_kse4obrb) to view a video introduction session for the LBN Network - an introduction for carrier networks!

[Click here](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_o1pafhm5) to view a video introduction session for the LBN Network - for API enabled carriers!

Feel free to click through [these slides](Upload/SAP_LBN_FC_FOR_CARRIER_NETWORKS.pdf) to get further information on the carrier networks.

[These slides](Upload/SAP_LBN_FC_FOR_CARRIERS.pdf) will show you more information about API enabled carriers.

## 1.) Get to know SAP LBN and APIs

![](Upload/Picture1.png)

- All APIs are documented in SAP API hub. To view relevenat api's click on the [link](https://api.sap.com/package/LbnFreightCollaborationTenderingSubcontracting?section=Artifacts) and filter based on Type 'Rest'.

- This video will provide you an overview of the APIs used for various scenarios [Click here](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_56hc08n2).
Additionally to understand details of the individual scenario click on the listed description. You can view the slides used in presentation by clicking on this [link](Upload/APIOverviewSlides.pdf)
  - [Tendering API](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_arll0fdg)
  - [Subcontracting API](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_0nq8qf49)
  - [Visibility API](https://sapvideoa35699dc5.hana.ondemand.com/?entry_id=1_z9pmf751)


## 2.) Request Tenant and Technical User
![](Upload/2.png)

![](Upload/Screenshot3.png) 
### A. API Mapping & Testing ###

License 8007828 – Free of Charge *Test tenant to develop & test connectivity with standard LBN APIs* 




* For Partner Integration phase: Mapping to SAP LBN APIs & end-to-end testing for both Freight Collaboration & Global Track and Trace options 
* Also for Customer Testing / implementation project with testing of integration to the partner network

![](Upload/Screenshot.png)
### B. License Coverage Details
* SAP Logistics Business Network B2B Test Tenant for carriers and network partners
* License to set-up B2B connections for
  * Mapping to SAP Logistics Business Network standard APIs
  * Integration testing 
  * Set-up and testing of B2B connections with SAP Logistics Business Network shipper customer test tenants
* An unlimited number of connections 
* Related usage of SAP Cloud Identity and SAP Fiori
* Standard SAP cloud support for SAP Logistics Business Network and standard APIs

### C. Order the B2B Test Tenant 

* On completion of introduction of your company and solution for SAP Logistics Business Network integration and partnership team via email: LBNPartner@sap.com
* In the SAP Store via Hyperlink[ here](https://www.sapstore.com/solutions/46401/SAP-Logistics-Business-Network%2C-B2B-test-tenant)
* Or via URL: https://www.sapstore.com/solutions/46401/SAP-Logistics-Business-Network%2C-B2B-test-tenant

## 3.) Integrate with SAP LBN APIs

![](Upload/3.png)

You may use these [sample payload](Upload/SamplePayload/) to build your mappings and endpoints.

When the API s are ready, you can configure the endpoints to our test landscape. To configure them, you will have to login to SAP LBN and maintain your endpoints that SAP LBN needs to call. You may refere this [video](https://video.sap.com/media/t/1_igc0uy3u) to view how to setup outbound connections and inbound connections. 

For all the LBN provider APIs(inbound to LBN), when you call our endpoint, you would need to  procure an OAuth 2.0 client Id and secret. This can be procured by reporting an incident. Use the application component - SCM-LBN-INT in [sap support portal](https://support.sap.com/) Please mention the LBNID created for you account. To know the LBN ID, login to SAP LBN  and open the business profile tile.

The OAuth Id will be needed by you to call our endpoint for all the provider APIs.

The [LBN endpoint](https://l20398-iflmap.hcisbp.eu1.hana.ondemand.com/http/v1h) that you need to call.


During this step, SAP will invite your test tenant to a dummy shipper tenant for test puruposes.  You would have to accept the invitation by logging in to you LBN tenant and navigating to Manage Invitation tile.


Below [application link](https://help.sap.com/viewer/185742008f2c477ca789b93675b0ec6c/LBN/en-US/011fbcd85017450587389c4a10190077.html) help will guide you on how to configure your endpoint in our app.



## 4.) Testing 

![](Upload/4.png)

- To test , you can generate an test call from the system connection app. you may refer the document [here](https://help.sap.com/viewer/185742008f2c477ca789b93675b0ec6c/LBN/en-US/21f87b4b5d1547a5b7c185be5e764203.html) on how to generate a test payload

## 5.) Release for Productive Usage

![](Upload/5.png)

![](Upload/Screenshotproductive1.png)
### A. Customer Connectivity
License 8007133 – Free of charge
**Productive tenant for connectivity and transaction processing / data sharing with shippers*** 
* Covers both Freight Collaboration & Global Track and Trace options
* Enables business partner entry and discovery in the business partner directory 
* Enables listing and representation in SAP Logistics Business Network go-to-market materials


![](Upload/Schreenshotproductive2.png)
### B. License Coverage Details

* SAP Logistics Business Network membership as a carrier or network partner
* License to collaborate / transact with connected shipper customers via the SAP Logistics Business Network for:
  * Freight Requests for Quotation and freight order confirmation / rejectiion 
  * Order tracking 
  * Web-based access for documents exchange
* An unlimited number of connections 
* Related usage of SAP Cloud Identity and SAP Fiori
* Standard SAP cloud support for SAP Logistics Business Network and standard APIs


![](Upload/Screenshotproductive3.png)
### C.1  Request Productive Membership Invitation: 
* On completion of mapping and integration testing only
* Invitation request to be sent to network enablement validation via email: sap.dsc.network.enablement@sap.com 
### C.2   Order the Basic Membership License
* After successful completion of step C.1
* In the SAP Store via Hyperlink here
* Or via URL:https://www.sapstore.com/solutions/46399/SAP-Logistics-Business-Network%2C-Basic-Membership
* Using your purchase order number provided in the invitation email sent from network enablement 

Watch [this recording](https://www.kaltura.com/p/1921661/sp/192166100/embedIframeJs/uiconf_id/37285991/partner_id/1921661?iframeembed=true&playerId=kaltura_player&entry_id=1_87fynq6n)
to have the steps explained visually.

For all the LBN provider APIs, when you call our endpoint, you would need to request or procure an OAuth 2.0 client Id and secret. This can be procured by reporting an incident . Use the  application component - SCM-LBN-INT in [sap support portal](https://support.sap.com/). Please mention the LBNID created for you account. To know the LBN ID, login to SAP LBN and open the business profile tile.

The OAuth Id will be needed by you to call our endpoint for all the provider APIs.

The [LBN endpoint](https://l20398-iflmap.hcisbp.eu1.hana.ondemand.com/http/v1
) that you need to call.

The step above is same as the one you have request for test access. But the OAuth ID and secret will be separate for productive access.

Configure system connection in LBN for productive tenant.Repeat the activities carried out on System connection App in the test tenant ( [Click here](https://video.sap.com/media/t/1_igc0uy3u) ). This time maintain your productive URL

Follow activities as done in step 3 to your productive URLs.

Raise an incident in SCM-LBN-INT for a smoke test. We will facilitate an example order to your system . This activity will be done manually. 

## 6.) Become and SAP PartnerEdge Partner
![](Upload/Screenshot6.png)

As a network provider, with delivered connectivity to the SAP Logistics Business Network, your next step is to become an SAP PartnerEdge member. SAP PartnerEdge provides network solution and content providers an official SAP Partner status to allow joint go-to-market and marketing with SAP. You will profit from inclusion in the global go-to-market assets and enablement activities for the SAP Logistics Business Network. As a partner, you may issue SAP-supported press releases, participate in SAP events, and publish co-branded marketing materials for the joint solution and partnership. You will also have access to SAP partner management, for example to connect you with the relevant SAP stakeholders for opportunity and customer project alignment. Furthermore, with PartnerEdge membership, your solution will be included in the SAP APP Center for marketing and sales to SAP customers.   
 
 ![](SAPPartnerEdge.png)

To become a PartnerEdge member, you will need to complete the following:
1.	SAP PartnerEdge Build, Integrate application
2.	Application Readiness Check (ARC) for solution validation 
3.	Due Diligence check for compliance validation
4.	SAP App Center account and solution listing
 
Find out more here.
https://www.sap.com/partner/become/partneredge-build.html





## How to obtain support

If you have further questions, please post them here [this repository](https://github.wdf.sap.corp/D055590/logistics-business-network-integration/issues)

## License
Copyright (c) 2020 SAP SE or an SAP affiliate company. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file.
