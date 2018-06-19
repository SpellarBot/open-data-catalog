# FOIA Request Log - Independent Police Review Authority

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-independent-police-review-authority-f6bb3) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/gzxp-vdqf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/gzxp-vdqf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/gzxp-vdqf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | gzxp-vdqf |
| Name | FOIA Request Log - Independent Police Review Authority |
| Attribution | City of Chicago |
| Category | FOIA |
| Created | 2010-04-16T18:53:39Z |
| Publication Date | 2016-01-14T17:57:50Z |

## Description

FOIA requests received by the Independent Police Review Authority as of May 1, 2010

## Columns

```ls
| Included | Schema Type | Field Name     | Name           | Data Type     | Render Type   |
| ======== | =========== | ============== | ============== | ============= | ============= |
| Yes      | series tag  | requestor_name | REQUESTOR NAME | text          | text          |
| Yes      | series tag  | organization   | ORGANIZATION   | text          | text          |
| Yes      | series tag  | description    | DESCRIPTION    | text          | text          |
| No       |             | date_received  | DATE RECEIVED  | calendar_date | calendar_date |
| Yes      | time        | due_date       | DUE DATE       | calendar_date | calendar_date |
```

## Time Field

```ls
Value = due_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_received
```

## Data Commands

```ls
series e:gzxp-vdqf d:2010-05-10T00:00:00.000Z t:organization=Unknown t:requestor_name="Devonne Reed" t:description="Photos and statements contained in Log# 1008171" m:row_number.gzxp-vdqf=1

series e:gzxp-vdqf d:2010-05-10T00:00:00.000Z t:organization=Unknown t:requestor_name="Lee McCorker" t:description="Arrest report for Donald Pickett" m:row_number.gzxp-vdqf=2

series e:gzxp-vdqf d:2010-05-18T00:00:00.000Z t:organization=Unknown t:requestor_name="Don Vance" t:description="1)  Names and badge numbers of all active duty CPD with ""allegations of domestic violence, excessive force, coercion through a threat of violence, and bias-based verbal against them.""  2)  Names and badge numbers of all law enforcement officers in Illinois and Chicago with ""allegations of domestic violence, excessive force, coercion through a threat of violence, and bias-based verbal against them.""  3)  Names and badge numbers of all active personnel employed by the city of Chicago to ""perform law enforcement functions."" 4) Names and badge numbers of ""all current active duty personnel who are sworn to act as law enforcement officers and are given the authority to Arrest/Detention under the color of Illinois Law.""" m:row_number.gzxp-vdqf=3
```

## Meta Commands

```ls
metric m:row_number.gzxp-vdqf p:long l:"Row Number"

entity e:gzxp-vdqf l:"FOIA Request Log - Independent Police Review Authority" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/gzxp-vdqf

property e:gzxp-vdqf t:meta.view v:id=gzxp-vdqf v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Independent Police Review Authority" v:attribution="City of Chicago"

property e:gzxp-vdqf t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:gzxp-vdqf t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name  | organization             | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | date_received       | due_date            | 
| =============== | ======================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | =================== | =================== | 
| Devonne Reed    | Unknown                  | Photos and statements contained in Log# 1008171                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Lee McCorker    | Unknown                  | Arrest report for Donald Pickett                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Don Vance       | Unknown                  | 1) Names and badge numbers of all active duty CPD with "allegations of domestic violence, excessive force, coercion through a threat of violence, and bias-based verbal against them." 2) Names and badge numbers of all law enforcement officers in Illinois and Chicago with "allegations of domestic violence, excessive force, coercion through a threat of violence, and bias-based verbal against them." 3) Names and badge numbers of all active personnel employed by the city of Chicago to "perform law enforcement functions." 4) Names and badge numbers of "all current active duty personnel who are sworn to act as law enforcement officers and are given the authority to Arrest/Detention under the color of Illinois Law." | 2010-05-11T00:00:00 | 2010-05-18T00:00:00 | 
| Ruben Zarate    | Unknown                  | 1) Identification of rules governing CPD use of force during arrest; and 2) identification of "Who is responsible for doing an investigation to find out, how many shots were fired by each officer, and where those shots were found."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | 2010-05-25T00:00:00 | 2010-06-02T00:00:00 | 
| Kelvin Stokes   | Unknown                  | "copies of two verbal complaints made over the phone to the Independent Police Review Authority on 27-Mar-2010, Reference: Log No. 1034954 , and Reference: Log No. 1034936."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2010-05-25T00:00:00 | 2010-06-02T00:00:00 | 
| Karen Szpajer   | Public Defender's Office | Any and all IPRA (former OPS) investigations of misconduct involving P.O. Mike Collins (Star# 16346) and P.O Miguel Renteria (Star# 19762)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 | 
| Yi Tang         | Unknown                  | "complete Investigative Report" related to a specific investigation.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 2010-06-05T00:00:00 | 2010-06-14T00:00:00 | 
| Lowell London   | Unknown                  | Copies of all correspondence IPRA sent to him                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 2010-06-04T00:00:00 | 2010-06-11T00:00:00 | 
| Allison Weaver  | Unknown                  | Copy of Log# 1036850                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 2010-06-09T00:00:00 | 2010-06-16T00:00:00 | 
| Erin K. Farrell | Public Defender's Office | Any and all IPRA (former OPS) investigations of misconduct involving P.O. A. Vivanco (Star# 17296)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | 2010-06-15T00:00:00 | 2010-06-22T00:00:00 | 
```