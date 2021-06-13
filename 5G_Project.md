# Introduction / Business Problem

## Background
There is great interest in new applications of mobile technology, especially *fifth-generation technology (5G) and Internet of Things (IoT)*, also known as machine-to-machine communication (M2M), and the technological complements or accessories with which we equip ourselves.  The usage of high frequencies to transport the data, implies a reduction in the size of the cells and opening new challenges in the decision to provide the more adequate coverage. 

Over the next few years, the installation will increase of microcells. It is estimated that there will be around ten microcells for each macrocell in the large urban surfaces. Microcells are used to get more coverage and capacity. Like the microcells are closer to users of mobile phones will work more efficiently, the data speed will be improved and the user exposure. 

The mobile Operators look for maximizing the return of the investments, as for a long time have spent a lot of money in new wireless technologies and keeping the networks updated y supporting the continuous growth.
This has taken to them, to be very skeptical about how to the investments and use the resources in an effective way.  Deploying the new 5G networks requires smart decisions on resource allocation, and were to provide all the potential of this technology , in the best places customers can demand them and use them in a massive way and more efficiently.

Defining microcell coverage through key microcell site allocations is a fundamental factor to be successful in avoiding a high expend on resources, as well as giving the right service to customers where they usually live and meet each other. So our intention should solve the next question: How to identify the right places to deploy microcells , taking in consideration where the customer visit or stay more frequently? Could we link the most likely places based on the type of business categories that are concentrated in some particular areas?

The analisys that is proposed here is aimed to market teams mainly in Mobile Operators that are planning a strategy for deploying 5G microcells in urban areas. They are interested in solving the above question, in such a way that they can offer more suitable products and services to different types of users, favoring higher consumption. Marketers can share this results with technical teams in order to add this input as criteria for microcells allocation.

## Data Requirements

Our data sources for the research we expose here are base on:

* Previous/historical cell coverage data in the same urban areas (from https://opencellid.org), and statistic of most density areas of mobile users (taken as comparision of concentration/distribution of cells in a particular area).

  Over this link, it is attached the database fields present in the data that we require to identify cell sites including coverage in distance, ownership, latitude and longitude       worldwide, opoen source information.
  ![image](https://user-images.githubusercontent.com/65038782/121784127-bf8a7100-cb77-11eb-9e89-e477d9bed4a9.png)


* Operators Data Base - It helps to identify if operator-based analysis is required, in order to work with specific mobile operator data will be used. (Sample : Data for North America countries https://en.wikipedia.org/wiki/Mobile_Network_Codes_in_ITU_region_3xx_(North_America)#United_States_of_America_%E2%80%93_US) 

  See information from Mexico:

  ![image](https://user-images.githubusercontent.com/65038782/121816155-9c2af900-cc3f-11eb-9636-3b52f775420c.png)



* Database of businesses located in this area, clasified by category. Taken from Foursquare API. The purpose will be select the type of catagories that represent the most crowded places and create areas where massive coverage is required.

  Sample of a JSON response of a venue information (includes, name, category, location, ratings, etc
  ![image](https://user-images.githubusercontent.com/65038782/121815798-d0051f00-cc3d-11eb-8692-53c4350c8b11.png)

