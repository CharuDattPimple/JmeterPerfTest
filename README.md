# CX Performance Test Scripts #

### The repo for JMeter Scripts for the CX App ###

## How to Run this script ##

You will need Apache Jmeter Binary to installed on your system

[Download Link ](https://archive.apache.org/dist/jmeter/binaries/)

There are two ways to run the script CX-App.jmx 

## 1. GUI (Not the recommended way) ##

After you unzip the JMeter zip file, go to the bin directory and open jmeter.sh file (mac or linux) or jmeter.bat (windows).

This should be used only for script development. Open the CX-App.jmx file in jmeter. Click on the Green Arrow button at the top.

## 2. Non-GUI mode ##

You should use the below command in actual  perf test run:

./jmeter.sh -n -t weatherMapAndBlazeDemo.jmx  -l htmlReports.csv -e -o /htmlReports -f


## 3. Running with Maven

If you have maven installed , running is pretty easy. You will need to run the below command:


## 4. Azure Pipelines

https://mpcoderepo.visualstudio.com/wealth/_release?view=mine&definitionId=144

