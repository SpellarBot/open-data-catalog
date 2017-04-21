# FOIA Request Log - Environment - Historical

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foia-request-log-environment-ac773) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/s7ek-ru5b) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/s7ek-ru5b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/s7ek-ru5b/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | s7ek-ru5b |
| Name | FOIA Request Log - Environment - Historical |
| Attribution | City of Chicago |
| Category | FOIA |
| Tags | historical |
| Created | 2010-04-16T16:29:01Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

FOIA requests received by Environment as of May 1, 2010. In 2011, the Department of Environment was merged into the Department of Public Health.  See https://data.cityofchicago.org/FOIA/FOIA-Request-Log-Health/4h87-zdcp for records since that time.

## Columns

```ls
| Included | Schema Type | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | =========== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag  | requestor_name         | REQUESTOR NAME         | text          | text          |
| Yes      | series tag  | organization           | ORGANIZATION           | text          | text          |
| Yes      | series tag  | description_of_request | DESCRIPTION OF REQUEST | text          | text          |
| Yes      | time        | date_received          | DATE RECEIVED          | calendar_date | calendar_date |
| No       |             | due_date               | DUE DATE               | calendar_date | calendar_date |
```

## Time Field

```ls
Value = date_received
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = due_date
```

## Data Commands

```ls
series e:s7ek-ru5b d:2010-05-03T00:00:00.000Z t:description_of_request="Asbestos, UST/AST, ermegency response, hazmat etc. re: 545 N. Central Park" t:organization=Atwell t:requestor_name="Jason Roth" m:row_number.s7ek-ru5b=1

series e:s7ek-ru5b d:2010-05-03T00:00:00.000Z t:description_of_request="Underground Tank and Hazardous Wastes re: 3657 W. Lawrence" t:organization=Hydrodynamics t:requestor_name="Mike Wan" m:row_number.s7ek-ru5b=2

series e:s7ek-ru5b d:2010-05-03T00:00:00.000Z t:description_of_request="Underground Tank and Hazardous Wastes re: 2240 S. Wentworth" t:organization=Hydrodynamics t:requestor_name="Mike Wan" m:row_number.s7ek-ru5b=3
```

## Meta Commands

```ls
metric m:row_number.s7ek-ru5b p:long l:"Row Number"

entity e:s7ek-ru5b l:"FOIA Request Log - Environment - Historical" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/s7ek-ru5b

property e:s7ek-ru5b t:meta.view v:id=s7ek-ru5b v:category=FOIA v:attributionLink=http://www.cityofchicago.org v:averageRating=0 v:name="FOIA Request Log - Environment - Historical" v:attribution="City of Chicago"

property e:s7ek-ru5b t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:s7ek-ru5b t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| requestor_name    | organization                  | description_of_request                                                                                                                                                                                                                    | date_received       | due_date            | 
| ================= | ============================= | ========================================================================================================================================================================================================================================= | =================== | =================== | 
| Jason Roth        | Atwell                        | Asbestos, UST/AST, ermegency response, hazmat etc. re: 545 N. Central Park                                                                                                                                                                | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Mike Wan          | Hydrodynamics                 | Underground Tank and Hazardous Wastes re: 3657 W. Lawrence                                                                                                                                                                                | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Mike Wan          | Hydrodynamics                 | Underground Tank and Hazardous Wastes re: 2240 S. Wentworth                                                                                                                                                                               | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Beth Ayn Spatz    | EBI Consulting                | UST Records re: 321 E. Erie & 710 N. Lake Shore Dr.                                                                                                                                                                                       | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Lara Hoffman      | EPS Environmental             | Any and all info re: 9924-10015 S. Western, 9939-10007 S. Artesian, 2350-2449 W. 100TH ST.                                                                                                                                                | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Marissa Ambrosius | Gabriel Envrionmental         | Any and all info re: 1102-1140 S. Kedzie, 1101-1139 S. Kedzie, 1102-1140 S. Troy, 1101-1139 S. Troy, 1102-1140 S. Homan, 1101-1139 S. Homan, 3125-3365 W. Roosevelt, 3124-3364 W. Roosevelt, 3125-3365 W. Fillmore, 3124-3364 W. Fillmore | 2010-05-03T00:00:00 | 2010-05-10T00:00:00 | 
| Judie Wilson      | Environment Inc               | Any and all info re: 393 E. Illinois                                                                                                                                                                                                      | 2010-05-04T00:00:00 | 2010-05-11T00:00:00 | 
| Jeff Goeden       | PSI                           | Leaking UST, hazardous waste, spills and environmental conerns re: 5110 S. King Drive                                                                                                                                                     | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Jeff Goeden       | PSI                           | Leaking UST, hazardous waste, spills and environmental conerns re: 4554 S. Drexel                                                                                                                                                         | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
| Matt McDonnell    | Hanrahan Investigations Group | Any and all asbestos related records regarding: 2055 W. Pershing, 2101 W. Pershing, 2101-2109 W. Pershing, 4551 S. Racine, 4504 S. Racine, 3901 S. Morgan.                                                                                | 2010-05-05T00:00:00 | 2010-05-12T00:00:00 | 
```