##### **Team members**:
Marcel Bernard
Kathleen Garland

##### Design assumptions:
* Current design only shows a snapshot of ferry fleet status at a given time
* Ferry schedules are able to change to accomodate load
* Real-time capacity and ferry location information is available

##### What?
The following information is displayed in real-time:
* Position of each ferry in the fleet (either berth location, or eta to a given berth)
* Departure and arrival times for each ferry
* Filled and empty berths

##### Why?
* Gives overview of entire fleet at a given time
* Allows user to see at a glance where there might be problem areas, and which berths might be available for rerouting

##### How?
We would probably implement a custom software solution, although some interesting applications do already exist for tracking ship traffic.

for example:
https://www.marinetraffic.com/en/ais/home/centerx:-15.9/centery:19.6/zoom:5

##### Design study methodologies
We will cover the pre-core phase of the nine-stage plan. 
###### Learn
Read through visualization literature to find different possible techniques to use and have a relevant background before starting design
###### Winnow
Question - has this  type of design already been implemented with other systems? ( Different ferry companies, even other bussing/transportation companies ) 
Question - can the problem be solved by designing an algorithm that spits out the best schedule with given assets? ( No the, client wants to be able to manually change things ) 
Question - does the  data exist for the system ( start times, end times, ship info, etc)


###### Cast 
Identify key players for the project
Front-line analyst - the person that will be using the software to see ferry info and use that info to modify the schedule ( domain expert )
Gatekeeper - Assuming the leader of the company, decides if they will allocate funds for the project

##### Potential pitfalls
* poor knowledge of visualization field - we are new to this, so this would probably be one of the largest potential pitfalls
* Real-time ferry data may not be available
* Problem could potentially be automated (algorithmic problem of schedule optimization)