## Purpose of this repo
The purpose of this repo is to test, allow the implementation of, further develop and document the Energy Performance Monitoring API developed by Stroomversnelling, Enermatics, Lens, Fifthplay, Swycs and Enervalis. 

This API is developed as part of the monitoring norm (https://monitoringnorm.nl/) for net-zero energy housing (nul-op-de-meter), initially for The Netherlands, but also for other parts of Europe and North America. Monitoring energy performance is an essential requirement for being able to guarantee said energy performance and therefore the financing of the investment necessary to achieve net-zero energy.

## What is in this repo
There are several components of this repo:

1. The API specifications. These specifications are synced FROM SwaggerHub (https://app.swaggerhub.com/apis/energiesprong/performance/0.4.4) as unresolved yaml. It is NOT syncing bidirectionally, so any proposed changes will be reviewed in Github, and then changed in SwaggerHub through the admin (currently Marten). Documentation for Github Sync from Swagger can be found here: https://app.swaggerhub.com/help/integrations/github-sync
2. Issues. This is to report bugs and request features while working with the API.
3. Wiki. This is to document the working of the API.  

## What is NOT in this repo  
Some things that might be very useful for you that are not here, are:

- CI integration
- Swagger Editor integration

These were deemed overkill or overly complex for the situation.  

## How to work with this repo 
Standard Github workflow applies. On top of that, the following is proposed:

1. Every company working on implementation does so using their own branch. On the 24th of January 2019, we discuss all proposed changes and the admin will update those in the master branch and on SwaggerHub.  
2. If you encounter bugs or want to request additional features, please use the "Issues" section.  
3. If there are important discussions between now and the 24th of January, please use the "Wiki" section to propose changes and discuss the merits of these changes.  
4. If you learn something about the API and its implementation, please use the "Wiki" section to add to the documentation.  
5. If the functionality of Swagger is required (e.g. stub generation) and your branch is not yet in SwaggerHub, every company is expected to use their own Swagger Editor or SwaggerHub environment to import their branch of the API specifications.  

If you need anything in the meantime, please contact the admin, mwitkamp@stroomversnelling.nl.  
