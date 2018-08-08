
Please find the details for project assessment as below:


PreRequisite:

Performance testing done using Apache Jmeter Version 4



Task_1 details:

Recorded the following scenario and named as Task1_BookFlight


Scenario:

1)Navigated to http://www.newtours.demoaut.com/
  and logged in with username and password as yahya/yahya.
2)Selected current date in flight departing and returning date and Click Continue of Flight finder screen.

3)Select random flights and clicked continue.
  
4)Filled in firstname, lastname and number 
5)Clicked secure purchase.
Click logout.

Above test cases named as LoginPage,Reservation,Filldetails,Purchase,Signoff

 

Task_2
 details:
Recorded task2 scenario and named as Task2_BookFlight_SingleUser

Scenario:
1)Booked Flight for single user(Single Thread) for 15 min.For this Created HTTPRequest for Single user  and Ramp Up period as 900 sec(15 Minutes)
2)Analysis report and summary results are mentioned in the form of Summary Report,Tree,Graph and Table
3)Summary results exported to Task2-Results.csv

Note:Best practices followed like Created Single User and tracked results in the form of graph,tree,reports

Task_3 details:
Recorded task3 scenario and named as Task3_BookFlight_FiveUsers_SLA

scenario:

       
1)Incorporated five different virtual users for login in CSV File
2)Randomly selected a flight for all the executions.

3)Executed the test case for 5 virtual users for 20 minutes with the ramp-up time of 1 user / 10 sec. 

Note:
1)Best practices followed like Created Single User and tracked results in the form of graph,tree,reports
2)Inserted Duration assertion of 1300 ms/page

Note: SLA of 1000 ms/page is not possible due to heavy traffic,Page performance issue and network speed.Hence SLA of >1000 ms/page is reachable




