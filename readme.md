# Web Mapping Solutions currently available within the BC Government

## Problem Statement
People internal to government are not familiar with web mapping tools/services that are available/suitable to them -  IIT, GeoBC, and DataBC want to provide a consistent message about these tools and services.

## Summary of existing code or frameworks for Web Mapping currently in use within the Government of British Columbia

| ﻿    Web Mapping Solution                  | Detailed Descriptions                          |    Lifecyle  |
|--------------------------------------------|-------------------------------------|---------------|
| IMF2 - DataBC's Internet Mapping Framework |[description](/docs/0003-DataBC-IMF2.md)|Platform Maturity|
| SMK - DataBC's Simple Map Kit                |[description](/docs/0002-DataBC-SMK.md) |  Growth  |
| AGO - BC's Map Hub (ArcGIS Online)         |[description](/docs/0004-AGO-BCMapHub.md)| SaaS   |
| CWM - IIT's Common Web Mapping Framework |[description](/docs/0001-IIT-CWM.md)    | Platform Maturity  |
| DMF - DataBC's Mash-up Framework  |    | Deprecated |

see [Detailed Capbilities Comparison](DetailedComparison.md) for more information 

|                                                                                                                                                       | Internet Mapping Framework 2                                                                                                                                                                                                                      | BC Map Hub                                                                                                                                                                                                                                                                                                                             | Simple Map Kit                                                                                                                                            | Common Web Mapping                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                         | IMF2                                                                                                                                                                                                                                              | AGO                                                                                                                                                                                                                                                                                                                             | SMK                                                                                                                                                       | CWM                                                                                                                                                                                                                                                                                                                                              |
|                                                                                                                                                         |                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                  |
| Overview                                                                                                                                                |  [description](/docs/0003-DataBC-IMF2.md)                                                                                                                                                                             |  [description](/docs/0004-AGO-BCMapHub.md)                                                                     |  [description](/docs/0002-DataBC-SMK.md)                                         |  [description](/docs/0001-IIT-CWM.md)                                                                                                                                                                                            |
| Future Direction                                                                                                                                        | Platform Maturity - Minor UI Updates                                                                                                                                                                                   | Continued vigilance on data governance and content publication                                                                                                                                                                                                                                                    | Positioned as light weight points on a map replacement for DMF (An older government framework which uses the Google API). Community involvement, source code on GitHub. Optional support and hosting model from DataBC | Platform Maturity - Minor UI Updates                                                                                                                                                                                                                                                                                                                |
| Contact                                                                                                                            | DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                                                                                                                                |  DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                                                                                                                                                                                                                      |  DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                               | Common Services Manager IITD                                                                                                                                                                                                                                                                                                                     |
| Architecture                                                                                                                                            | Custom BC Gov't Web services and tools on top of Geocortex Essentials/ArcGIS Server/BCGW                                                                                                                                                          | Licensed cloud based service running on elastic Amazon cloud                                                                                                                                                                                                                                                |  javascript libraries - deploy anywhere                                                                                                                            | Custom BC Gov't Framework on top of Geoserver and Open Layers 2                                                                                                                                                                                                                                                                        |
| Examples                                                                                                                                                | [iMapBC](https://maps.gov.bc.ca/ess/hm/imap4m) Consultative Area Database, Major Projects, ACDF, Traditional Use Studies,                                                                                                                                                                         | EMBC COP ,  PICES, Mount Polly, Wildfire apps, Drought portal app                                                                                                                                                                      | Assisted living and residential care                                                                                                                      | MTO, ILRR, EYOR, NRS Explore                                                                                                                                                                                                                                                                                                                     |
| **Build Requirements**   