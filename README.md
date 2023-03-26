# Python-project
Calculating the distance between two locations helps companies like Swiggy and Zomato calculate the delivery time for an order. 
How to Calculate Distance Between two Locations?
We can use the haversine formula to calculate the distance between two locations. The haversine formula calculates the distance between two latitude and longitude points. This formula is defined as:

haversine(d/R) = haversine(latitude2- latitude1 + cos(latitude1 * cos(latitude2 * haversine(longitude2 – longitude1)

In this formula:

d is the distance between the two points
r is the radius of the earth
and haversine is the haversine function defined as:
haversine(theta) = sin^2(theta/2)
To calculate the final distance in kilometres, you need to multiply the distance between the two points by the radius of the earth.
