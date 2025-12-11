# Postman API Automation Integration with Github Actions #

This repository is a demonstration for POC for integrating postman tests with github actions. The tests are written in postman and they are executed on the VM with the help of newman and newman-reporter-htmlextra.
Github Actions will trigger the project execution on every push to the main branch. You can also execute the project manually using workflow_dispatch. The project runs on a scheduled time with the help of the cron job.

The HTML report is archived and kept in the artifact section for the team to download it. Along with that they can view the report directly from the github page : https://saravanan-ramaraj.github.io/Phoenix-Inwarranty-Flow/
The latest report is mailed to the stakeholders using gmail SMTP.


 ## Tech Stack ##
 1. Postman
 2. Node js 24v
 3. Newman
 4. Newman-Reporter-Htmlextra
 5. Github Actions
 6. Gmail SMTP
 7. Github Pages
 8. CSV for Data Driven Testing
 9. AWS-EC2 instance for Self hosted github runner
