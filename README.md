Usual steps for deploying existing Salesforce project to new sandbox
=========
If you need to deploy existing Salesforce project to new sandbox, you probably can face with some issues, because different parts of SF project are dependent on each other. So, I provide here simple flow for deployment. Actualy, my list can contains not all types of Salesforce project entities, because this platform is growing and some new features are coming.

So, for avoiding dependency errors, I suggest to deploy project entities in such order:

1. static resources
2. labels
3. groups
4. roles
5. letterhead
6. documents
7. OBJECTS
8. tabs
9. apps
10. emails
11. classes
12. pages
13. components
14. layouts
15. triggers
16. workflows
17. reports
18. dashbords
19. homepage layouts 
20. homepage components
21. profiles
22. permission sets
