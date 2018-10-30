Java service monitoring class ( Multi-threaded )
=================================================

To build using maven : Please follow bellow instrction.

1.) Import as a Eclipse maven project

2.) At the Run profile select project working place and then add maven gols as : clean install -U

3.) Above maven command will Sucessfully Compile & Run & pass all the Junit5 Test cases & eventually build a diployable jar with depecdancies.

4.) When you run "ServiceMonitor.java" individually you must go to browser and then type - localhost:9000 to see how services are working , you can periodically refresh browsor to see how many services are working.

5. Maven SureFire plugin TestCases report will be created under "/service-monitor/target/surefire-reports/"

It's look like.

http://localhost:9000/

ServiceBroker: Service-A - Thread Pooled Server - 1540891753506
