# leach_ns3
Modification to Traditional Leach Clustering Model in ns3 also known as Preprocessing Leach.


We(I and Wuxiucheng) have uploaded whole ns3 folder
In order to run code one need to download/clone leach_ns3 
And then complile as we do ns3 by using ./waf
Code is in scratch folder by name leach.cc which can be run using command: ./waf --run scratch/leach
We have plot.py file which reads ouput file generated by leach.cc and plots
leach.cc will produce three txt format files which holds average energy of overall network with every round.

Modified is only made for cluster head percent 0.05 and sink fixed at (500,500) with 50 nodes in network placed in (100,100) have 0.75 joule of energy

This work was part of Spring 2018 Wireless Sensor Network Project Course
Complete Report can be found here https://drive.google.com/open?id=1-Dnl9tNPO2X2ilbeEDVEUNpv51FUBJm9

