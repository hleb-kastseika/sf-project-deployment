This Ant script check-out the head revision from Subversion to a local folder and deploy to a Salesforce org with unit tests running.
It can be used in a continuous integration scenario. Hence this script would be automated by a Hudson or Jenkins job that would be monitoring the Subversion repository for commit operations.

Prerequisites:
- Java
- [Force.com Migration Tool](https://developer.salesforce.com/docs/atlas.en-us.daas.meta/daas/meta_development.htm), in particular *salesforce.jar*
- Apache Ant 
- SvnAnt task
