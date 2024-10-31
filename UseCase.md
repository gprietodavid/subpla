# Problem

Business has requested a new project named **Submission Platform**. This new system will be in charge of submitting tax returns (e-files) to the different government's APIs, for instances: 

- Belgian TAs exposes SOAP services requiring XML files as reports
- French TAs exposes REST APIs with oAuth protection requiring encrypted JSON files
- ...

Features required for MVP:

- Submission of e-filing according to their e-file requirements
- Ability to use this component in multiple projects (client and Deloitte applications)
- Should be easy to onboard new Country/TAs
- Security implementation and registration of new clients and users
- Ability to notify the calling application on progress/status
- Validate and transform incoming files before submission to ensure reception on the TAs side

Expected usage:

- 1.000 to 2.000 submissions per hour in peak season (at least once a month)
- Roughly 10 to 20 applications submitting e-files
- Audit and track incoming and outgoing information and user activity
- Possiblity to sell to other clients or Deloitte member firms