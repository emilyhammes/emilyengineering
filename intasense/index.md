# Intasense Air Quality Monitor
Intasense was a European Commission funded project established to create a novel air quality monitor for use in energy efficient buildings [www.intasense.e](www.intasense.eu). It incorporated engineers and researchers from eight organizations in five countries within Europe. While at [CSEM](https://www.csem.ch/home), I lead the integration of the first prototype of this monitor, developed the microfluidics and preconditioning unit for the devices and developed computational models of gas transport though the system. These computational models were the focus of my doctoral thesis.

## Prototype of the Intasense Air Quality Monitor

My first task in the Intasense project was to lead the technical integration of the first prototype. This involved organizing meetings, leading discussions, communicating requirements for each component, determining adverse interactions between components and finding ways to avoid these interactions. To be successful I needed to orchestrate electrical engineers, software engineers, chemists, physicists and material scientists so that various components would be delivered at the right time and in the right sequence. Additionally, I designed and created the microfluidics and preconditioning unit for this platform.

## Final Design of the Intasense Air Quality Monitor

After the first prototype had been created, I handed off technical integration to a collaborator in England. I then  focused on designing, builing, and testing the microfluidics and preconditioning unit of the final version Intasense Air Quality Monitor. In order to create the microfluidic system, I mathematically modeled gas samples being transported through the system to find an optimized design. Additionally, I modeled gas flow to the sensors and heat transport from the gas sensors to the microfluidics. I then manufactured and assembled all components of the system using a 2.5D mill and a laser cutter, among other tools. After confirming that all systems were statistically similar, I sent these fluidic systems to collaborators in academia and industry throughout the European Union where it was used to optimize sensors and the electronics in the air quality control systems.  

## Computational Modeling of Gas Adsorption (Thesis Work on the Intasense} Project

The gas sensors used in the Intasense Air Quality Monitor are cross sensitive to humidity fluctuations, so I needed to stabilize the humidity of gas without removing toxins such as CO or NO2. To resolve this problem, I used a small quantity of silica gel which is a reversible adsorbent. This adsorbent adds water when the humidity is low and removes water when ambient humidity is high. This works very well for water, but the adsorbent also acts on the toxic gasses. To quantify toxic gas adsorption, I conducted experiments using the toxic gas laboratories at [CEIT](https://www.ceit.es/en/industrial-sectors/environmental/gas-and-odour-sensoring-and-treatment/air-a-gas-quality-monitoring) in San Sebastian and at [Siemens Building Technologies](https://www.siemens.com/global/en/home/products/buildings.html) in Zug. These experiments show that small quantities of the tested gasses are adsorbed and desorbed, causing a delay in toxic gas detection. This shows that there is a tradeoff between humidity buffering and toxic gas signal delay. In order to find the optimum for a given flow rate and humidity range, I developed a mathematical model of the system using Comsol and Matlab. This model is similar to the adsorption phase of a desiccant dryer system and accounts for both heat and mass transport. Using this optimal amount of adsorbent, I was also able to show that humidity stabilization leads to more accurate and repeatable toxic gas sensor readings.

## Publications
### Thesis
[My Thesis](https://infoscience.epfl.ch/record/219118?ln=en)

### Journal Articles

G. G. Mandayo, J. Gonzalez-Chavarri, E. Hammes, H. Newton, I. Castro-Hurtado, I. Ayerdi, H. Knapp, A. Sweetman, C. Hewitt and E. Castaño, “System to Control Indoor Air Quality in Energy Efficient Buildings,” Urban Climate, 2014.

Georgia Papavasiliou, Preedarat Songprawat, Victor Pérez-Luna, Emily Hammes, Megan Morris, Yu-Chieh Chiu, and Eric Brey, “Three-Dimensional Patterning of Poly(Ethylene Glycol) Hydrogels Through Surface-Initiated Photopolymerization,” Tissue Engineering Part C: Methods, 2008

### Invited Conference Presentations
G. G. Mandayo, J. Gonzalez-Chavarri, I. Castro-Hurtado,  E. Castaño,  T. Geiling, M. Hoffmann, E. Hammes, P. Ryser, H. Knapp, R. Heslop, J. Jones, P. Fitzpatrick  and R. Bell, “System to Control Indoor Air Quality in Energy Efficient Buildings,” EuNetAir, Copenhagen, 2013

E. Hammes and R. Findeisen, “Modeling Mesenchymal Stem Cell Differentiation,” The US-Turkey Advanced Study Institute on Global Healthcare Challenges, Adrasan, 2010

### Conference Proceedings
J. González-Chávarri, E. Hammes, L. Parellada, I. Castro-Hurtado, E. Castaño, I. Ayerdi, H. Knapp, G. G.
Mandayo, “Multisensor Platform for Indoor Air Quality Measurements,” Spanish Conference on
Electronic Devices, 2017

G. G. Mandayo, J. Gonzalez-Chavarri, I. Castro-Hurtado, I. Ayerdi, E. Castaño, E. Hammes, P. Ryser, H. Knapp, “The INTASENSE Project Approach for Toxic Gas Detection Indoors,” International Congress on Architectural Envelopes, San Sebastian, 2015.

E. Hammes, J. Gonzalez-Chavarri, L. Henwood-Moroney, G. G. Mandayo, P. Ryser and H. F. Knapp, “The Transport Phenomena within the  INTASENSE Indoor Air Quality Monitor Design,” American Institute of Chemical Engineers, Austin, 2015.

E. Hammes, J. Gonzalez-Chavarri, L. Henwood-Moroney, G. G. Mandayo, P. Ryser and H. F. Knapp, “A Smart Air Quality Monitor for Energy Efficient Buildings,” in Smart Systems Integration, Copenhagen, 2015.

### Conference Presentations
E. Hammes, J. Gonzalez de Chavarri, G. G. Mandayo, P. Ryser and H. F. Knapp, “Intasense—Fluidics Design,” Building Test Expo, Brussels, 2014.

### Technical Reports
E. Hammes, P. Ryser and H. F. Knapp, “Air Pretreatment Platform for Indoor Air Qualtiy Monitoring,” CSEM Scientific and Technical Report 2015, Neuchâtel, 2016.

E. Hammes, J. Gonzalez-Chavarri, L. Henwood-Moroney, G. G. Mandayo, P. Ryser and H. F. Knapp, “Air Pretreatment Platform for Indoor Air Quality Monitoring,” CSEM Scientific and Technical Report 2014, Neuchâtel, 2015.
