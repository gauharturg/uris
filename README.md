# Road Planning 

The data collected from OpenStreetMap + NetworkX (OSMnx) was used for machine learning algorithms to build effective algorithms for dealing with route planning issues on already existing road networks. We made a simulation of cars' behavior on actual city roads. The data is stored in the format of a graph alongside with some related information, such as the nature of the area (commercial, residential, and industrial areas), traffic lights location, speed limit information, etc. 

## Description
The program was tested on the area in Hong Kong called Happy Valley.
<img width="567" alt="Screenshot 2022-09-08 at 9 03 39 PM" src="https://user-images.githubusercontent.com/53049009/189129054-2b16eef2-bbe6-4f3f-ac4f-ff5bc9d3841b.png">
*Happy Valley. Map and Graph of the area*

The roadmap is saved as a graph where the edges are the streets and the nodes are the intersections. Traffic lights' presence and types of roads (one- or two-way) are the variables in our simulation. The simulation shows the direction of roads and the traffic lights placement for the most efficient route planning. The calculations are made based on Dijkstra algorithm with additional consideration of the building and traffic at different time of the day.

## Demonstration

The 
![unnamed](https://user-images.githubusercontent.com/53049009/187439274-ed1820ef-305d-4ff5-9790-e0eb3e1b799f.png)



![unnamed](https://user-images.githubusercontent.com/53049009/187441229-a33d463c-1465-420f-a856-7e8a27475810.gif)
