This Ant script check-out the head revision from Subversion to a local folder and deploy to a Salesforce org with unit tests running.
It can be used in a continuous integration scenario. Hence this script would be automated by a Hudson or Jenkins job that would be monitoring the Subversion repository for commit operations.

Prerequisites:
- Force.com Migration Tool
- Apache Ant 
- SvnAnt task
