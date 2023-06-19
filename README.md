# Parking Management System

## About
This is an attempt to reduce the inconvenience of parking in a zone where many automobiles enter and exit at once. Furthermore, it might be difficult to pinpoint whether there is open space that can be used. We use operations research towards optimizing parking zones by division into sub-zones and cells. In order to let visitors know where to go, we utilize cameras to continuously monitor the space. When the cell is empty, it might be indicated on the entrance using a basic LED implementation to direct a person there. Future improvements will aim to comprehend the parking spaces that are available in the surrounding area. People might even offer the space they own or have nearby in exchange for a small sum of crypto-currency. We, therefore, think that this would significantly enhance the user parking experience, especially when planning events where parking logistics are an issue.

## Algorithm
* The values of length and breadth of the parking area are taken as input
* Using length, maximum capacity of the row is determined
* Considering each row
* On the appearance of each vehicle, using the Dynamic Knapsack the parking space is allocated
* Constant values are associated with two wheelers and four-wheelers assuming elements of the same class are totally alike
* Once the row is completely filled the next row is considered, until the entire area is occupied.
