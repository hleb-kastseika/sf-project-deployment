How to deploy an existing Salesforce project to a new sandbox

[![License](https://img.shields.io/badge/License-WTFPL-brightgreen.svg)](https://raw.githubusercontent.com/gleb-kosteiko/sf-project-deployment/master/copying.txt)

Since separate parts of the SF project depend on each other, deploying it to a new sandbox could be trick. However, there is a straightforward deployment flow you can follow to prevent any potential issues. Salesforce is a growing platform (hence new features are coming), so this list might be incomplete.

To avoid the possible dependency errors, deploy the project components in the following order:

1. static resources
2. labels
3. groups
4. roles
5. letterhead
6. documents
7. custom settings
8. objects (standard & custom)
9. tabs
10. apps
11. roles
12. queues
13. groups
14. remote site settings
15. emails
16. classes
17. components
18. pages
19. weblinks
20. layouts
21. triggers
22. workflows
23. approval processes 
24. assignment rules
25. report types
26. reports
27. dashbords
28. homepage layouts
29. homepage components
30. flows
31. profiles
32. permission sets

### Salesforce Continuous Integration 
The [sf-ci](https://github.com/gleb-kosteiko/sf-project-deployment/tree/master/sf-ci) folder contains different aproaches for organization of continious integration process on your Salesforce project.


---

**Copyright © 2018 Gleb Kosteiko <gleb.kosteiko@gmail.com>**

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the [COPYING](https://raw.githubusercontent.com/gleb-kosteiko/sf-project-deployment/master/copying.txt) file for more details.
