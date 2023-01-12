[![Test-Vagrant.jpg](https://i.postimg.cc/435bBWV6/Test-Vagrant.jpg)](https://postimg.cc/KK1MYr9j)   [![testvagrant-square-Logo.png](https://i.postimg.cc/rFxh5CnJ/testvagrant-square-Logo.png)](https://postimg.cc/KRcr2Lyk)

:seedling: This is just a basic framework under development for automating REST APIs .  `Maven` `Java` `TestNG` `RestAssured` `ExtentReports`.    

Designed specifically for `TestVagrant` project.

**Pre-requisites**: `Maven` and `Java` should be installed in the machine if you are running tests locally.

 

**How to run test locally**  :desktop_computer:   

1. Go to the project root folder where `pom.xml` file is present.
2. Open terminal/CMD in this folder.
3. Run command **mvn clean install**

the test suite execution will start and you can see the execution report under **test-result** folder that will be generated after run (refresh project folder if you don't see it).


**How to run test using github actions**    :rocket:   

I have created a github workflow for this project to run the tests    

On this repository   
1. Go to Actions tab in this repository
2. Click on workflow `TestVagrant API Automation`
3. Click on `Run workflow` dropdown 
4. Click on green `Run workflow` button   

Refresh the browser and you can see that run has been started. Check logs of the tests by going inside this running workflow.   
You can also download the `test-result` folder present inside `Artifacts` block in last github workflow run summary and see the extent HTML report.   

It looks like this:

[![wrappedsuite.png](https://i.postimg.cc/SQcfJQt2/wrappedsuite.png)](https://postimg.cc/kDXbHCCq)   
[![openedsuite.png](https://i.postimg.cc/0yYTnqQb/openedsuite.png)](https://postimg.cc/ZWqsY26S)   


Cheers :shipit: :tada:   
