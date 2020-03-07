# hlf-medicChain

The designed concept of the pharmaceutical supplychain system based on the blockchain technology
Hyperledger Fabric.

##### Background

Medicines move through a supply chain in which several participants participate. These usually include the manufacturer, wholesaler and retailer and finally consumer. They are engaged in the production, transportation and sale of these products. Also in these systems, there is a key participant - the regulating authority responsible for each stage of the movement of batches of products throughout the chain. In particular, at the state level, this participant may be some authorized body of the state apparatus, for example, a special Agency for the control of turnover of medicinal products. 

Pharmaceutical companies that manufacture, ship and supply products face difficulties in tracking their products, allowing counterfeiters to inject counterfeit drugs into the system.This situation is observed in many countries around the world. In a recent report by the world health Organization, drug counterfeiting has been identified as a global problem. 

The ability of blockchain systems to pinpoint the origin of data makes them particularly suitable for pharmaceutical supply chain applications. The data stored in the blockchain distributed register on the identification of drugs produced by the plant, as well as records of their movements throughout the supply chain, can accurately determine the authenticity of pharmaceutical products lying on the shelves of pharmacies. A properly designed system based on blockchain technology can significantly simplify the process of drug turnover control for authorized state bodies. At the same time, a decentralized approach has a number of advantages that increase the information security of such systems compared to centralized counterparts.


##### Participants
 
 1. Regulator(Health Administration) : A government entity has an authority to regulate medical products and also has ability to register other participants on the system, giving licenses for production & selling of medicines.
 2. Manufacturer:  Produces goods and takes orders from the Pharmacy and authorization by Regulator.
 3. Distributor or Wholesaler: A person or entity that distribute large quantity of medical products from manufacturers to the retaier.
 4. Retailer(Pharmacy Stores): Sells medical products to consumers based on Doctor prescription.
 5. Doctor: No special intro. Writes prescription of medicine to heal their patients.
 6. Consumer: Patient

##### Work-flow:

“Healthcare is not based on supply and demand. It can’t be ‘stocked’ like it’s a traditional product” says Mike Rip, Director of the Master of Science in Healthcare Management at Michigan State University. “So a hospital’s supply chain is very different from a business or company’s supply chain.”
> As Mike Rip said --drug supplychain system is still under development, so it is not possible to provide a final list of of work flow. However, we can distinguish the main ones, giving an approximate picture of the functioning of the working prototype. 

The main transactions of the system at this stage for prposed model are,

1. Participants registration and approval of licenses to different Participants by Regulator 
2. Adding manufactured medicine data to the ledger by Manufacturer.
3. Retailer orders certain units of medicine
4. Transfer of medicine units to the distributor by Manufacturer.
5. Transfer of medicine units to the Retailer by distributor.
6. Doctor Prescription to the patient.
6. Sale of medicine to the Consumer based on doctor prescription.

<img align="center" src="https://github.com/Salmandabbakuti/hlf-medicChain/blob/master/medicChain_flow.png" width="90%">

##### Data Structure:
###### Order:
<img align="center" src="https://github.com/Salmandabbakuti/hlf-medicChain/blob/master/orderer.png" width="90%">

###### Drug UUID:
<img align="center" src="https://github.com/Salmandabbakuti/hlf-medicChain/blob/master/uuid.png" width="90%">

###### History Chain:
<img align="center" src="https://github.com/Salmandabbakuti/hlf-medicChain/blob/master/uuid2.png" width="90%">


##### Terminologies Used in Chaincode:
 >In Progress..
##### User Interface:

 >Not yet implemented.

##### References:

 1. https://www.researchgate.net/publication/326286259_Blockchain_Technology_for_Detecting_Falsified_and_Substandard_Drugs_in_the_Pharmaceuticals_Distribution_System_Preprint
 2. https://www.michiganstateuniversityonline.com/resources/healthcare-management/changes-and-challenges-in-the-healthcare-supply-chain/
 3. https://www.biopharmadive.com/news/top-challenges-facing-drug-supply-chains/521876/


##### Author   

##### :wave: [Salman Dabbakuti](https://salmandabbakuti.github.io)

<a href="https://www.buymeacoffee.com/Salmandabbakuti" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

©Salman Dabbakuti

 
