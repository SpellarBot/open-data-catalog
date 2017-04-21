# Legislative data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/legislative-data) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7hrs-ce5x) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7hrs-ce5x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7hrs-ce5x/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7hrs-ce5x |
| Name | Legislative data |
| Created | 2016-08-26T01:24:58Z |
| Publication Date | 2016-08-26T01:26:10Z |

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | series tag  | bill_number      | bill number      | text          | text          |
| Yes      | series tag  | url              | url              | url           | url           |
| Yes      | time        | last_action_date | last_action_date | calendar_date | calendar_date |
| Yes      | series tag  | last_action      | last_action      | text          | text          |
| Yes      | series tag  | title            | title            | text          | text          |
| Yes      | series tag  | description      | description      | text          | text          |
```

## Time Field

```ls
Value = last_action_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:7hrs-ce5x d:2015-12-17T00:00:00.000Z t:title="PUC; Grid-Connected Energy Storage System; Independent Distribution System Operators" t:last_action="Carried over to 2016 Regular Session." t:bill_number=HB1 t:description="Requires the PUC to open proceedings for grid-connected energy storage systems and independent distribution system operators, submit reports, and convene a working group." t:url=https://legiscan.com/HI/bill/HB1/2016 m:row_number.7hrs-ce5x=1

series e:7hrs-ce5x d:2015-12-17T00:00:00.000Z t:title="Renewable Energy; Non-export System; Net Energy Metering; Electric Utilities" t:last_action="Carried over to 2016 Regular Session." t:bill_number=HB2 t:description="Requires that all applications for solar, wind, or similar electrical generation devices that do not feed electricity to the electric grid be automatically approved by an electric utility within 30 days." t:url=https://legiscan.com/HI/bill/HB2/2016 m:row_number.7hrs-ce5x=2

series e:7hrs-ce5x d:2015-12-17T00:00:00.000Z t:title="Public Electric Utilities; UH; DBEDT; Study; Appropriations ($)" t:last_action="Carried over to 2016 Regular Session." t:bill_number=HB3 t:description="Requires UH, in consultation with DBEDT, to study the benefits of establishing public electric utilities in the State that are publicly owned. Appropriates moneys for the study." t:url=https://legiscan.com/HI/bill/HB3/2016 m:row_number.7hrs-ce5x=3
```

## Meta Commands

```ls
metric m:row_number.7hrs-ce5x p:long l:"Row Number"

entity e:7hrs-ce5x l:"Legislative data" t:url=https://data.hawaii.gov/api/views/7hrs-ce5x

property e:7hrs-ce5x t:meta.view v:id=7hrs-ce5x v:averageRating=0 v:name="Legislative data"

property e:7hrs-ce5x t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:7hrs-ce5x t:meta.view.tableauthor v:id=wktp-67q4 v:screenName=karen v:roleName=administrator v:displayName=karen
```

## Top Records

```ls
| bill_number | url                                            | last_action_date    | last_action                           | title                                                                                                | description                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| =========== | ============================================== | =================== | ===================================== | ==================================================================================================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================ | 
| HB1         | [https://legiscan.com/HI/bill/HB1/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | PUC; Grid-Connected Energy Storage System; Independent Distribution System Operators                 | Requires the PUC to open proceedings for grid-connected energy storage systems and independent distribution system operators, submit reports, and convene a working group.                                                                                                                                                                                                                                                                   | 
| HB2         | [https://legiscan.com/HI/bill/HB2/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Renewable Energy; Non-export System; Net Energy Metering; Electric Utilities                         | Requires that all applications for solar, wind, or similar electrical generation devices that do not feed electricity to the electric grid be automatically approved by an electric utility within 30 days.                                                                                                                                                                                                                                  | 
| HB3         | [https://legiscan.com/HI/bill/HB3/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Public Electric Utilities; UH; DBEDT; Study; Appropriations ($)                                      | Requires UH, in consultation with DBEDT, to study the benefits of establishing public electric utilities in the State that are publicly owned. Appropriates moneys for the study.                                                                                                                                                                                                                                                            | 
| HB4         | [https://legiscan.com/HI/bill/HB4/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Beach Erosion Study; Appropriation; 50th House District CIP ($)                                      | Appropriates moneys to subsidize a beach erosion study for the island of Oahu that specifically includes the shoreline areas within the 50th representative district.                                                                                                                                                                                                                                                                        | 
| HB5         | [https://legiscan.com/HI/bill/HB5/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Environmental Impact Statement; Environmental Assessment; Climate Change Analysis                    | Requires the environmental council to adopt rules that require all environmental impact statements and environmental assessments include climate change analysis.                                                                                                                                                                                                                                                                            | 
| HB6         | [https://legiscan.com/HI/bill/HB6/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Bail; Repeat Offenders; Denial for Certain Offenses                                                  | Expands conditions under which bail may be denied to repeat offenders.                                                                                                                                                                                                                                                                                                                                                                       | 
| HB7         | [https://legiscan.com/HI/bill/HB7/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Historic Preservation; DLNR; Historic Property                                                       | Exempts private residences not on or nominated by the owner onto the Hawaii register of historic places from designation as a historic property in order to exempt those properties from DLNR historic preservation review in connection with project permit or land use applications.                                                                                                                                                       | 
| HB8         | [https://legiscan.com/HI/bill/HB8/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Liquefied Natural Gas; Utilities                                                                     | Prohibits utilities from engaging in large-scale import of liquefied natural gas.                                                                                                                                                                                                                                                                                                                                                            | 
| HB9         | [https://legiscan.com/HI/bill/HB9/2016, null]  | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Paid Sick Leave                                                                                      | Requires employers to provide a minimum amount of paid sick leave to employees to be used to care for themselves or a family member who is ill or needs medical care.                                                                                                                                                                                                                                                                        | 
| HB12        | [https://legiscan.com/HI/bill/HB12/2016, null] | 2015-12-17T00:00:00 | Carried over to 2016 Regular Session. | Department of Education; Fundraising; Charitable Activity; Nonprofit Organizations; Student Learning | Bars prohibition of student or class participation in a fundraiser or charitable activity in conjunction with a nonprofit organization as part of a school project when participation benefits student learning. Requires the department to take all steps necessary to prevent the preferential treatment of specific charities and undue pressure on school children or their families to participate in charitable activities. (HB12 HD1) | 
```