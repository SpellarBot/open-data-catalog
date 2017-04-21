# Open Data Commitments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/open-data-commitments) |
| Metadata | [Link](https://data.wa.gov/api/views/btuj-66g2) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/btuj-66g2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/btuj-66g2/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | btuj-66g2 |
| Name | Open Data Commitments |
| Tags | open data, performance |
| Created | 2016-11-27T22:02:39Z |
| Publication Date | 2016-11-28T01:29:54Z |

## Description

Agency open data commitments from published Open Data plans. We are still assessing the plans and entering data, so this is a BETA dataset.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type      | Render Type    |
| ======== | ============== | ============== | ============== | ============== | ============== |
| Yes      | series tag     | entity         | Entity         | text           | text           |
| Yes      | series tag     | commitmentname | CommitmentName | text           | text           |
| Yes      | series tag     | desscription   | Description    | html           | html           |
| Yes      | series tag     | similar_to     | Similar to     | drop_down_list | drop_down_list |
| Yes      | time           | publisheddate  | PublishedDate  | calendar_date  | calendar_date  |
| Yes      | series tag     | current_status | Current Status | text           | drop_down_list |
| Yes      | numeric metric | progress       | Progress       | number         | number         |
| No       |                | statusdate     | StatusDate     | calendar_date  | calendar_date  |
| Yes      | series tag     | t_shirt        | T-Shirt        | drop_down_list | drop_down_list |
| Yes      | series tag     | reference      | Reference      | url            | url            |
```

## Time Field

```ls
Value = publisheddate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = statusdate
```

## Data Commands

```ls
series e:btuj-66g2 d:2016-10-01T00:00:00.000Z t:commitmentname=Feedback t:t_shirt=aufq-nxr9 t:similar_to=tvt3-25sb t:desscription="&bull; Ecology will collect feedback on our Databases web page and on data.wa.gov, to inform us on which datasets are most needed by our partners. 
Measureable: Count how many suggestions we receive and how many are implemented." t:entity=ECY t:current_status=xuxz-c5x9 m:progress=4

series e:btuj-66g2 d:2016-10-01T00:00:00.000Z t:commitmentname=Showcase t:t_shirt=aufq-nxr9 t:similar_to=ttv6-897z t:desscription="&bull; Ecology will dedicate space on our website to showcase significant open data projects, including but not limited to: 
&#61607; Significant open data releases 
&#61607; Ecology&rsquo;s mapping efforts 
&#61607; Special purpose web-pages that use data to tell Ecology&rsquo;s story &#61607; Mobile applications 
&#61607; Data visualizations 
&#61607; Data analysis performed by Ecology staff" t:entity=ECY t:current_status=xuxz-c5x9 m:progress=4

series e:btuj-66g2 d:2016-10-04T00:00:00.000Z t:commitmentname="Application Owners as Stewards" t:t_shirt=gtet-qsqn t:similar_to=cc7m-22kg t:desscription="&bull; Data stewards are generally business staff with staff positions in the
agency&rsquo;s key business units that have knowledge of where data is
located, how it is structured, provide insight into the use and
classification of the data, and are responsible for the availability,
accuracy and integrity of one or more data assets will be identified as
data stewards in their position descriptions, following guidance from
OCIO or models in use in other state agencies.
Application Owners" t:entity=RCO t:current_status=3tvh-82ur m:progress=2
```

## Meta Commands

```ls
metric m:progress p:integer l:Progress d:"Percent complete. 0-1: Discussing 1-2: Planning 3-5: Doing / Executing 6-7: Checking / Feedback 8-9: Adjusting / Updating" t:dataTypeName=number

entity e:btuj-66g2 l:"Open Data Commitments" t:url=https://data.wa.gov/api/views/btuj-66g2

property e:btuj-66g2 t:meta.view v:id=btuj-66g2 v:averageRating=0 v:name="Open Data Commitments"

property e:btuj-66g2 t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:btuj-66g2 t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| entity | commitmentname                 | desscription                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | similar_to | publisheddate       | current_status | progress | statusdate          | t_shirt   | reference    | 
| ====== | ============================== | ========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ========== | =================== | ============== | ======== | =================== | ========= | ============ | 
| ECY    | Feedback                       | ? Ecology will collect feedback on our Databases web page and on data.wa.gov, to inform us on which datasets are most needed by our partners. Measureable: Count how many suggestions we receive and how many are implemented.                                                                                                                                                                                                                                                                                                                                                            | tvt3-25sb  | 2016-10-01T00:00:00 | xuxz-c5x9      | 4        | 2016-11-27T00:00:00 | aufq-nxr9 | [null, null] | 
| ECY    | Showcase                       | ? Ecology will dedicate space on our website to showcase significant open data projects, including but not limited to: ? Significant open data releases ? Ecology?s mapping efforts ? Special purpose web-pages that use data to tell Ecology?s story ? Mobile applications ? Data visualizations ? Data analysis performed by Ecology staff                                                                                                                                                                                                                                              | ttv6-897z  | 2016-10-01T00:00:00 | xuxz-c5x9      | 4        | 2016-11-27T00:00:00 | aufq-nxr9 | [null, null] | 
| RCO    | Application Owners as Stewards | ? Data stewards are generally business staff with staff positions in the agency?s key business units that have knowledge of where data is located, how it is structured, provide insight into the use and classification of the data, and are responsible for the availability, accuracy and integrity of one or more data assets will be identified as data stewards in their position descriptions, following guidance from OCIO or models in use in other state agencies. Application Owners                                                                                           | cc7m-22kg  | 2016-10-04T00:00:00 | 3tvh-82ur      | 2        | 2016-11-27T00:00:00 | gtet-qsqn | [null, null] | 
| RCO    | Database Inventory             | ? The agency will maintain an inventory of its principal databases, and produce a published (though perhaps not detailed) table of information systems acquired, redesigned or rebuilt since 1996 that incorporate provision for electronic public access. ApplicationDatabaseInventory                                                                                                                                                                                                                                                                                                   | 7suy-ayks  | 2016-10-04T00:00:00 | xuxz-c5x9      | 4        |                     | hz6m-kkwt | [null, null] | 
| RCO    | Data Catalog                   | The agency has and will maintain a data catalog that identifies the category of data held in agency databases ? aiding agency staff in determining the appropriate level of public access. [Example, The Department of Transportation?s DOTS project catalogs and links the majority of databases in use by the agency, including the topical and security categorization of tables and records within the databases.]                                                                                                                                                                    | mjtr-sxrp  | 2016-10-04T00:00:00 | xuxz-c5x9      | 3        |                     | gtet-qsqn | [null, null] | 
| RCO    | Check with Stakeholders        | The agency staff will engage strategic partners for suggestions on which datasets to prioritize. - Habitat and Recreation Lands Coordinating Group - Recreation and Conservation Funding Board - Agencies Boating Committee - Northwest Marine Trade Association - Washington Trails Association - Salmon Recovery Funding Board - Salmon Recovery Regions and Lead Entities - Washington Invasive Species Council                                                                                                                                                                        | tvt3-25sb  | 2016-10-04T00:00:00 | 3tvh-82ur      | 2        |                     | aufq-nxr9 | [null, null] | 
| RCO    | Designate One Portal           | The agency will identify the location where it will be posting its datasets and IT tools necessary for extracting, transforming and loading this dataset to these sites. http://www.rco.wa.gov/data with links to other open data repositories or portals.                                                                                                                                                                                                                                                                                                                                | ec2y-j4q3  | 2016-10-04T00:00:00 | 3tvh-82ur      | 2        |                     | aufq-nxr9 | [null, null] | 
| RCO    | Data Appendix                  | The agency will publish a data appendix for each of its legislative reports that cites statistics or maps in support of the narrative, and will make each data appendix available to the State Library?s Depository program (See RCW 40.06.030) in searchable, downloadable and machine-readable form. [Example, a legislatively mandated report on the availability of broadband across the state could include a link to (or a copy of) a federal, state or private dataset where a citizen can search, download or study the aggregate numbers used to generate charts in the report.] | rcct-quib  | 2016-10-04T00:00:00 | 3tvh-82ur      | 2        |                     | aufq-nxr9 | [null, null] | 
| RCO    | Stewardship as a skill         | ? The agency will adopt policies and procedures describing specific staff roles and responsibilities for the management of data, including open data or specific data sets. RCO POL Managing Information and Records RCO POL Publishing and Using Authoritative Data Habitat and Recreation Lands Coordinating Group Coordinator PRISM Application Owner Compliance Program Manager Cultural Resources Program Manager HWS Application Owner WISC Coordinator Boating Program Manager Trails Program Manager Recreation and ADA Program Manager                                           | cc7m-22kg  | 2016-10-04T00:00:00 | xuxz-c5x9      | 4        |                     | hz6m-kkwt | [null, null] | 
| RCO    | M&O support for Open Data      | ? The agency will dedicate budget and staff time to the maintenance and operation of select technology services that interconnect, federate or provide documented application programming interfaces (API) for agency data on agency-specific or shared servers. ArcGIS Online Open Data Portal                                                                                                                                                                                                                                                                                           | 6ayv-6hqy  | 2016-10-04T00:00:00 | xuxz-c5x9      | 5        |                     | aufq-nxr9 | [null, null] | 
```