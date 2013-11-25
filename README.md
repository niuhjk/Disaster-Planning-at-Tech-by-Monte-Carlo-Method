Disaster-Planning-at-Tech-by-Monte-Carlo-Method
===============================================

Solve the problem of Disaster Planning at Tech by Monte-Carlo Method


This is a case solution for 'Introduction to management science - simulation chapter' - case study 3.


# Case Detail

Concerned about recent weather-related disasters, fires, and other calamities at universities around the country, university administrators at Tech have initiated several planning projects to determine how effectively local emergency facilities can handle such situations. 

One of these projects has focused on the transport of disaster victims from campus to the five major hospitals in the area: 

Montgomery Regional, 
Raeford Memorial, 
County General, 
Lewis Galt,
HGA Healthcare. 

The project team would like to determine how many victims each hospital might expect in a disaster and how long it would take to transport victims to the hospitals.

However, one of the problems the project team faces is the lack of data on disasters, since they occur so infrequently.

The project team has looked at disasters at other schools and has estimated that the minimum number of victims that would qualify an event as a disaster for the purpose of initiating a disaster plan is 10. The team has further estimated that the largest number of victims in any disaster would be 200, and based on limited data from other schools, they believe the most likely number of disaster victims is approximately 50. Because of the lack of data, it is assumed that these parameters best define a triangular distribution.


Capabilities
The emergency facilities and capabilities at the five area hospitals vary. It has been estimated that in the event of a disaster situation, the victims should be dispersed to the hospitals on a percentage basis based on the hospitals’
relative emergency capabilities, as follows: 25% should be sent to Montgomery Regional, 30% to Raeford Memorial, 15% to County General, 10% to Lewis Galt, and 20% to HGA Healthcare. 


Transport times
The proximity of the hospitals to Tech also varies. It is estimated that transport times to each of the hospitals is exponentially distributed with an average time of 5 minutes to Montgomery Regional, 10 minutes to
Raeford Memorial, 20 minutes to County General, 20 minutes to Lewis Galt, and 15 minutes to HGA Healthcare. (It is assumed that each hospital has two emergency vehicles, so that one leaves Tech when the other leaves the hospital, and consequently, one arrives at Tech when the other arrives at the hospital. Thus, the total transport time will be the sum of transporting each victim to a specific hospital.)

a. Perform a simulation analysis using Crystal Ball to determine the average number o
f victims that can be expected at each hospital and the average total time required to transport victims to each hospital.

b. Suppose that the project team believes they cannot confidently assume that the number of victims will follow a triangular distribution using the parameters they have estimated. Instead, they believe that the number of victims is best estimated using a normal distribution with the following parameters for each hospital:
•	a mean of 6 minutes and a standard deviation of 4 minutes for Montgomery Regional; 
•	a mean of 11 minutes and a standard deviation of 4 minutes for Raeford Memorial;
•	a mean of 22 minutes and a standard deviation of 8 minutes for County General; 
•	a mean of 22 minutes and a standard deviation of 9 minutes for Lewis Galt;
•	a mean of 15 minutes and a standard deviation of 5 minutes for HGA Healthcare. 
•	
Perform a simulation analysis using this revised information.

c. Discuss how this information might be used for planning purposes. How might the simulation be altered or changed to provide additional useful information?
