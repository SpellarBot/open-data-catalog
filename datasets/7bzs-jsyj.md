# House Share Prohibited Buildings List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/house-share-prohibited-buildings-list) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/7bzs-jsyj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/7bzs-jsyj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/7bzs-jsyj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 7bzs-jsyj |
| Name | House Share Prohibited Buildings List |
| Attribution | City of Chicago |
| Category | Buildings |
| Tags | house share, regulation, restrictions |
| Created | 2016-11-18T21:57:47Z |
| Publication Date | 2016-12-07T21:19:18Z |

## Description

A list of buildings excluded from short-term rental activity under the Shared Housing Ordinance.  See https://www.cityofchicago.org/city/en/depts/bacp/provdrs/bus/alerts/2016/july/Prohibited_Buildings_List_Affidavit.html for more information on the exclusion process.

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                               | Data Type     | Render Type   |
| ======== | ============== | ================================ | ================================== | ============= | ============= |
| Yes      | series tag     | application_id                   | Application ID                     | text          | number        |
| Yes      | series tag     | submission_id                    | Submission ID                      | text          | text          |
| Yes      | series tag     | applicant_role                   | Applicant Role                     | text          | text          |
| Yes      | series tag     | association_cooperative_or_owner | Association, Cooperative, or Owner | text          | text          |
| No       |                | address_number                   | Address Number                     | text          | text          |
| Yes      | series tag     | street_direction                 | Street Direction                   | text          | text          |
| Yes      | series tag     | street_name                      | Street Name                        | text          | text          |
| Yes      | series tag     | street_type                      | Street Type                        | text          | text          |
| Yes      | numeric metric | number_of_units                  | Number of Units                    | number        | number        |
| Yes      | series tag     | pin                              | PIN                                | text          | text          |
| No       |                | vote_date                        | Vote Date                          | calendar_date | calendar_date |
| No       |                | recorded_date                    | Recorded Date                      | calendar_date | calendar_date |
| Yes      | time           | signed_date                      | Signed Date                        | calendar_date | calendar_date |
| No       |                | latitude                         | Latitude                           | number        | number        |
| No       |                | longitude                        | Longitude                          | number        | number        |
```

## Time Field

```ls
Value = signed_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address_number,vote_date,recorded_date,latitude,longitude
```

## Data Commands

```ls
series e:7bzs-jsyj d:2016-09-22T00:00:00.000Z t:submission_id=PB2016A00597 t:pin=17-17-210-095-0000 t:applicant_role="Authorized Agent" t:street_name=Monroe t:street_direction=W t:application_id=597 t:association_cooperative_or_owner="Chelsea Townhomes" t:street_type=ST m:number_of_units=1

series e:7bzs-jsyj d:2016-10-06T00:00:00.000Z t:submission_id=PB2016A00703 t:pin=14-33-207-026-0000 t:applicant_role="Registered Agent" t:street_name=Orleans t:street_direction=N t:application_id=703 t:association_cooperative_or_owner="Orleans I LLC" t:street_type=ST m:number_of_units=70

series e:7bzs-jsyj d:2016-09-22T00:00:00.000Z t:submission_id=PB2016A00620 t:pin=17-17-210-072-0000 t:applicant_role="Authorized Agent" t:street_name=Monroe t:street_direction=W t:application_id=620 t:association_cooperative_or_owner="Chelsea Townhomes" t:street_type=ST m:number_of_units=1
```

## Meta Commands

```ls
metric m:number_of_units p:integer l:"Number of Units" t:dataTypeName=number

entity e:7bzs-jsyj l:"House Share Prohibited Buildings List" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/7bzs-jsyj

property e:7bzs-jsyj t:meta.view v:id=7bzs-jsyj v:category=Buildings v:attributionLink=https://www.cityofchicago.org v:averageRating=0 v:name="House Share Prohibited Buildings List" v:attribution="City of Chicago"

property e:7bzs-jsyj t:meta.view.owner v:id=vewm-vupz v:screenName="Jonathan Levy" v:displayName="Jonathan Levy"

property e:7bzs-jsyj t:meta.view.tableauthor v:id=vewm-vupz v:screenName="Jonathan Levy" v:roleName=administrator v:displayName="Jonathan Levy"
```

## Top Records

```ls
| application_id | submission_id | applicant_role   | association_cooperative_or_owner | address_number | street_direction | street_name | street_type | number_of_units | pin                                                                                                                                                                                            | vote_date           | recorded_date       | signed_date         | latitude     | longitude     | 
| ============== | ============= | ================ | ================================ | ============== | ================ | =========== | =========== | =============== | ============================================================================================================================================================================================== | =================== | =================== | =================== | ============ | ============= | 
| 597            | PB2016A00597  | Authorized Agent | Chelsea Townhomes                | 1117 #2        | W                | Monroe      | ST          | 1               | 17-17-210-095-0000                                                                                                                                                                             |                     |                     | 2016-09-22T00:00:00 | 41.880247094 | -87.655383997 | 
| 703            | PB2016A00703  | Registered Agent | Orleans I LLC                    | 2046           | N                | Orleans     | ST          | 70              | 14-33-207-026-0000                                                                                                                                                                             | 2016-10-05T00:00:00 |                     | 2016-10-06T00:00:00 | 41.919727308 | -87.63789348  | 
| 620            | PB2016A00620  | Authorized Agent | Chelsea Townhomes                | 1127           | W                | Monroe      | ST          | 1               | 17-17-210-072-0000                                                                                                                                                                             |                     |                     | 2016-09-22T00:00:00 | 41.880241194 | -87.65576272  | 
| 70             | PB2016A00070  | Authorized Agent | Stonegate Harbor Condos          | 436            | W                | Belmont     | AVE         | 16              | 14-21-314-059-1001-1040                                                                                                                                                                        |                     | 1998-05-15T00:00:00 | 2016-07-22T00:00:00 | 41.940202781 | -87.641190217 | 
| 519            | PB2016A00519  | Authorized Agent | 560 W Fulton Condominium Assoc   | 560            | W                | Fulton      | ST          | 40              | 17-09-303-087-1001-1080                                                                                                                                                                        |                     |                     | 2016-09-13T00:00:00 | 41.88692284  | -87.642293415 | 
| 537            | PB2016A00537  | President        | 2614 N Racine Condominium Assoc  | 2614           | N                | Racine      | AVE         | 7               | 14-29-310-054-1007                                                                                                                                                                             |                     | 2016-09-16T00:00:00 | 2016-09-16T00:00:00 | 41.929374456 | -87.658741107 | 
| 464            | PB2016A00464  | Authorized Agent | 1744 Henderson Condominium Assoc | 1744-1746      | W                | Henderson   | ST          | 7               | 14-19-422-047-1001-1012                                                                                                                                                                        |                     |                     | 2016-08-17T00:00:00 | 41.94248442  | -87.672903992 | 
| 179            | PB2016A00179  | Property Manager | Lake Meadow Townhomes I          | 506-556        | E                | 32nd        | ST          | 38              | 17-34-224-005-0000 thru 17-34-224-018-0000 17-34-224-020-0000 thru 17-34-224-033-0000 17-34-224-035-0000 17-34-224-040-0000 thru 17-34-224-045-0000 17-34-224-048-0000 thru 17-34-224-050-0000 |                     |                     | 2016-08-09T00:00:00 | 41.836176251 | -87.61320482  | 
| 194            | PB2016A00194  | Authorized Agent | Lunt Ave Condo & Health Club     | 1327-1339      | W                | Lunt        | AVE         | 38              | 11-32-114-034-1001                                                                                                                                                                             |                     |                     | 2016-08-01T00:00:00 | 42.009033941 | -87.664768281 | 
| 115            | PB2016A00115  | Authorized Agent | PAC Lofts Condominium Assoc      | 1735           | N                | Paulina     | ST          | 95              | 14-31-422-042-1001-1188                                                                                                                                                                        |                     |                     | 2016-07-28T00:00:00 | 41.91342543  | -87.67006247  | 
```