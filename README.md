# API_Performance_Test


<h2>Project Summary:</h2> 
I conducted Load Testing and Stress Testing on the Booking APIs to evaluate their performance and identify system limits. Additionally, I implemented API Chaining (JMeter Collection) for the DMoney website’s Transaction APIs. For the Transaction APIs, data was retrieved from CSV files, and multiple API requests were executed concurrently using four threads in JMeter.

<h2>Test Case Scenarios for Load and Stress Testing:</h2>
Created a collection of APIs (JMeter Collection) consisting of Login API, Create Booking API, and Search API HTTP requests.
Executed Load Testing and Stress Testing to measure system performance and determine the bottleneck and capacity thresholds.<br>
<br>
Website for APIs - https://restful-booker.herokuapp.com

<h2>Testcase scenarios for API Chaining in Jmeter Test -</h2>
1. 5 agents perform deposits for 10 customers.<br>
2. 5 customers send money to another 10 customers.<br>
3. 5 customers make payments to 2 merchants.<br>
4. Set the ramp-up time to 120 seconds in all the above thread configuration.<br>
<br>
Website for APIs - http://dmoney.roadtocareer.net



<h2> Execute the following steps using JMeter: </h2> 
   
  - ``` git clone https://github.com/Yasir-Hossain-Katib/DMoney-API-Testing-POSTMAN.git ```<br>
  - ``` Open ApacheJMeter ``` <br>
  - ``` From apacheJMeter open the JMX File ```<br> 
  - ``` Finally Run ```


