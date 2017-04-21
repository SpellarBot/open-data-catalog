# IDOA - Area Agencies on Aging

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idoa-area-agencies-on-aging-7c9a4) |
| Metadata | [Link](https://data.illinois.gov/api/views/6bgh-ttez) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/6bgh-ttez/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/6bgh-ttez/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 6bgh-ttez |
| Name | IDOA - Area Agencies on Aging |
| Category | Social/Healthcare |
| Tags | aging, service area |
| Created | 2011-10-19T12:19:55Z |
| Publication Date | 2011-10-19T12:40:02Z |

## Description

Listing of Illinois Area Agencies on Aging.     
In accordance with Federal Older American's Act regulations, the Illinois Department on Aging has divided Illinois into 13 Planning and Service Areas (PSAs).

The 13 Planning and Service Areas in Illinois are each managed and served by an Area Agency on Aging. The Department works in partnership with these agencies: 12 not-for-profit corporations and one unit of local government, the City of Chicago.

Area Agencies have the primary task of planning and coordinating services and programs for older people in their respective areas. The Area Agencies receive funding from the Department based on a formula which takes into consideration the number of older citizens and minorities in that area, as well as the number living in poverty, in rural areas, and alone. 

Like the Department on Aging, Area Agencies are not, as a rule, direct service providers. Area Agencies contract with local agencies which provide services to the older people who live in the same community.

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| No       | time           | :updated_at               | updated_at                | meta_data | meta_data   |
| Yes      | numeric metric | planning_and_service_area | Planning and Service Area | number    | number      |
| Yes      | series tag     | area_agency_name          | Area Agency Name          | text      | text        |
| Yes      | series tag     | zip_code                  | Zip Code                  | text      | text        |
| Yes      | series tag     | phone_1                   | Phone 1                   | text      | text        |
| Yes      | series tag     | phone_2                   | Phone 2                   | text      | text        |
| Yes      | series tag     | fax                       | Fax                       | text      | text        |
| Yes      | series tag     | executive_director        | Executive Director        | text      | text        |
| Yes      | series tag     | website                   | Website                   | text      | text        |
| Yes      | series tag     | e_mail                    | E-mail                    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:6bgh-ttez d:2011-10-19T05:20:04.000Z t:area_agency_name="Southeastern Illinois Area Agency on Aging, Inc." t:fax="(618) 262-4967" t:phone_2=1-800-635-8544 t:zip_code=62863 t:website=www.seiaoa.com t:phone_1="(618) 262-2306" t:executive_director="Yvonne DeKnikker" t:e_mail=seiaoa@frontier.com m:planning_and_service_area=10

series e:6bgh-ttez d:2011-10-19T05:20:05.000Z t:area_agency_name="AgeOptions, Inc." t:fax="(708) 524-0870" t:phone_2=1-800-699-9043 t:zip_code=60301 t:website=www.ageoptions.org t:phone_1="(708) 383-0258" t:executive_director="Jonathan Lavin" t:e_mail=information@ageoptions.org m:planning_and_service_area=13

series e:6bgh-ttez d:2011-10-19T05:20:05.000Z t:area_agency_name="Western Illinois Area Agency on Aging" t:fax="(309) 793-6807" t:phone_2=1-800-322-1051 t:zip_code=61201 t:website=www.wiaaa.org t:phone_1="(309) 793-6800" t:executive_director="Barbara Eskildsen" t:e_mail=FirstStopForSeniors@wiaaa.org m:planning_and_service_area=3
```

## Meta Commands

```ls
metric m:planning_and_service_area p:integer l:"Planning and Service Area" t:dataTypeName=number

entity e:6bgh-ttez l:"IDOA - Area Agencies on Aging" t:url=https://data.illinois.gov/api/views/6bgh-ttez

property e:6bgh-ttez t:meta.view v:id=6bgh-ttez v:category=Social/Healthcare v:averageRating=0 v:name="IDOA - Area Agencies on Aging"

property e:6bgh-ttez t:meta.view.owner v:id=kcsp-4rdt v:screenName="Bernie Clancy IDoA" v:displayName="Bernie Clancy IDoA"

property e:6bgh-ttez t:meta.view.tableauthor v:id=kcsp-4rdt v:screenName="Bernie Clancy IDoA" v:displayName="Bernie Clancy IDoA"
```

## Top Records

```ls
| :updated_at | planning_and_service_area | area_agency_name                                                                         | zip_code | phone_1        | phone_2        | fax            | executive_director   | website                     | e_mail                        | 
| =========== | ========================= | ======================================================================================== | ======== | ============== | ============== | ============== | ==================== | =========================== | ============================= | 
| 1319001604  | 10                        | Southeastern Illinois Area Agency on Aging, Inc.                                         | 62863    | (618) 262-2306 | 1-800-635-8544 | (618) 262-4967 | Yvonne DeKnikker     | www.seiaoa.com              | seiaoa@frontier.com           | 
| 1319001605  | 13                        | AgeOptions, Inc.                                                                         | 60301    | (708) 383-0258 | 1-800-699-9043 | (708) 524-0870 | Jonathan Lavin       | www.ageoptions.org          | information@ageoptions.org    | 
| 1319001605  | 3                         | Western Illinois Area Agency on Aging                                                    | 61201    | (309) 793-6800 | 1-800-322-1051 | (309) 793-6807 | Barbara Eskildsen    | www.wiaaa.org               | FirstStopForSeniors@wiaaa.org | 
| 1319001605  | 5                         | East Central Illinois Area Agency on Aging, Inc.                                         | 61704    | (309) 829-2065 | 1-800-888-4456 | (309) 829-6021 | Michael J. O?Donnell | www.eciaaa.org              | aginginfo@eciaaa.org          | 
| 1319001605  | 8                         | Area Agency on Aging of Southwestern Illinois                                            | 62221    | (618) 222-2561 | 1-800-326-3221 | (618) 222-2567 | Joy Paeth            | www.answersonaging.com      | ask@answersonaging.com        | 
| 1319001605  | 9                         | Midland Area Agency on Aging                                                             | 62801    | (618) 532-1853 | 1-877-532-1853 | (618) 532-5259 | Tracy Barczewski     | www.midlandaaa.org          | office@midlandaaa.org         | 
| 1319001605  | 11                        | Egyptian Area Agency on Aging, Inc.                                                      | 62918    | (618) 985-8311 | 1-888-895-3306 | (618) 985-8315 | John M. Smith        | www.egyptianaaa.org         | egyptianaaa@mediacombb.net    | 
| 1319001605  | 7                         | Area Agency on Aging for Lincolnland, Inc.                                               | 62704    | (217) 787-9234 | 1-800-252-2918 | (217) 787-6290 | Julie Hubbard        | www.aginglinc.org           | info@aginglinc.org            | 
| 1319001605  | 6                         | West Central Illinois Area Agency on Aging                                               | 62306    | (217) 223-7904 | 1-800-252-9027 | (217) 222-1220 | Lynn Niewohner       | www.wciagingnetwork.org     | lynn@wciagingnetwork.org      | 
| 1319001605  | 12                        | Chicago Department of Family and Support Services - Senior Services Area Agency on Aging | 60622    | (312) 744-4016 |                | (312) 744-0680 | Joyce Gallagher      | www.cityofchicago.org/aging | aging@cityofchicago.org       | 
```