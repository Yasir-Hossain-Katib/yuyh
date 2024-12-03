# Project Summary:
I conducted Load Testing and Stress Testing on the Booking APIs to evaluate their performance and identify system limits. Additionally, I implemented API Chaining (JMeter Collection) for the DMoney website’s Transaction APIs. For the Transaction APIs, data was retrieved from CSV files, and multiple API requests were executed concurrently using four threads in JMeter.

Test Case Scenarios for Load and Stress Testing:
Created a collection of APIs (JMeter Collection) consisting of Login API, Create Booking API, and Search API HTTP requests.
Executed Load Testing and Stress Testing to measure system performance and determine the bottleneck and capacity thresholds.
Website for APIs - https://restful-booker.herokuapp.com

Testcase scenarios for API Chaining in Jmeter Test -
5 agents perform deposits for 10 customers.
5 customers send money to another 10 customers.
5 customers make payments to 2 merchants.

Set the ramp-up time to 120 seconds in all the above thread configuration.
Website for APIs - http://dmoney.roadtocareer.net

Execute the following steps using JMeter:
git clone <repo_url>
Open ApacheJMeter
From ApacheJMeter open the JMX File
Finally Run
