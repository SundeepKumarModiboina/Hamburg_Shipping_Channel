# Hamburg_Shipping_Channel
Predicting the Shipping Routes in Hamburg
From Hamburg port, there are two channels out of which each ship will take one channel to travel from Hamburg.
The data set contains the shipping data that are going to different destinations along with their current Co-ordinates.
We have to filter the ships that are in Hamburg and predict which channel will each ship take.

The data set contains two csv files.
1. South Shipping Data - Ships that take the South channel for travelling
2. North Shipping Data - Ships that take the North channel for travelling

Here are the data features
1. mssi - Ship Id
2. shiptype - There are different types of ships based on the size.
3. length - Length of the ship in metres
4. breadth - Breadth of the ship in metres
5. draught - Height of the ship in metres
6. longtitude - Current Longitude position of the ship
7. latitude - Current Latitude position of the ship
8. sog - Current Carrier Weight
9. cog - Maximum Carrier Weight
10. th - threshold Carrier Weight
11. destination - Destination of the ship
12. name - Name of the Ship
13. callsign - Call Sign of the ship
14. utc - Time recorded
15. tss - Shipping Channel route

In these data features, tss is the dependent variable which has to be predicted.
