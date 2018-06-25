Requirement:

•	An Apigee Account
•	Maven 3.0 installed on local machine
•	Right folder structure

We need to have both parent pom and child pom file in the folder structure. Check out the sample folder structure in the repository

Command to deploy the proxy in Apigee from local machine:

mvn install -Ptest -Dusername={apigee-edge-email} -Dpassword={apigee-edge-password} -Dorg={apigee-edge-org}
Above command will deploy the proxy on Apigee.

We can follow the same folder structure to deploy other API proxies on Apigee.

