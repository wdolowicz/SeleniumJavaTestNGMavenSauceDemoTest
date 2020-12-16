# saucelabstest

This repo contains two java tests for www.saucedemo.com. Test suite consists of Logging in with correct credentials, and with incorrect credentials.

Whole development was made on a Linux running machine (Pop!_OS 20.10) and thus it works on Linux for sure, but it should work on any other OS as well (only if the must haves for target OS are met)

Must haves:

1. JDK
2. JAVA_HOME environment variable properly set
3. Maven (https://maven.apache.org/download.cgi)
4. chromedriver v87 & TestNG - libs are included but in case of trouble, there might be a need to install those separately

Usage:

1. Clone repo
2. Navigate to Test folder
3. Open terminal
4. Execute following:
      mvn clean test -DsuiteXmlFile=testng.xml
5. Tests should perform
