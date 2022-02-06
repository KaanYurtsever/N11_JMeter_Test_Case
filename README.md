# N11 JMeter Test Case
This project was created by using Jmeter to measure the performance of the n11 page under load. In this project, 15 products are added to the basket, but only products under 100 TL should be added. Some steps in the project are as follows:

- Using assortions between steps,
- Failure to continue next step after Assertion error,
- Using different timeouts for different pages in the test. 
- Using preprocessing and processing methods.
- Note: Before run the test, you should add your product urls csv file to the CSV Data Set Config in the Loop Controller.
