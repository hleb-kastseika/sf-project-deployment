How to deploy an existing Salesforce project to a new sandbox
=========
Since separate parts of the SF project depend on each other, deploying it to a new sandbox could be trick. However, there is a straightforward deployment flow you can follow to prevent any potential issues. Salesforce is a growing platform (hence new features are coming), so this list might be incomplete.

To avoid the possible dependency errors, deploy the project components in the following order:

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

### Salesforce Continuous Integration 
The *sf-ci* folder contains Ant build file for an automated Subversion code check-outing and deployment to SF Org. See more details in *sf-ci/README.txt*

**Copyright © 2015 Last Khajiit <last.khajiit@gmail.com>**

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the COPYING file for more details.
