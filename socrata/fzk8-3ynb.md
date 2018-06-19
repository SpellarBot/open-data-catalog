# Medical Assistance Program Medicaid Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medical-assistance-program-medicaid-offices-01145) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/fzk8-3ynb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/fzk8-3ynb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/fzk8-3ynb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | fzk8-3ynb |
| Name | Medical Assistance Program Medicaid Offices |
| Attribution | Human Resources Administration (HRA) |
| Category | City Government |
| Tags | jobs and economic mobility, human resources administration, hra, medicaid, assistance |
| Created | 2013-03-19T20:24:29Z |
| Publication Date | 2016-03-02T20:27:43Z |

## Description

This table represents the list of different types of organizations where individuals and families can get help determining their eligibility for public health insurance as well as assistance with completing the application process.

## Columns

```ls
| Included | Schema Type | Field Name               | Name                     | Data Type | Render Type |
| ======== | =========== | ======================== | ======================== | ========= | =========== |
| No       | time        | :updated_at              | updated_at               | meta_data | meta_data   |
| Yes      | series tag  | borough                  | Borough                  | text      | text        |
| Yes      | series tag  | name_of_medicaid_offices | Name of Medicaid Offices | text      | text        |
| No       |             | address                  | Address                  | text      | text        |
| Yes      | series tag  | telephone_number         | Telephone Number         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:fzk8-3ynb d:2016-03-02T12:27:03.000Z t:name_of_medicaid_offices="Bronx Lebanon Hospital" t:telephone_number="(718) 860-4634/4635" t:borough=BRONX m:row_number.fzk8-3ynb=1

series e:fzk8-3ynb d:2016-03-02T12:27:03.000Z t:name_of_medicaid_offices="Lincoln Medical and Mental Health Center" t:telephone_number="(718) 585-7872/7920" t:borough=BRONX m:row_number.fzk8-3ynb=2

series e:fzk8-3ynb d:2016-03-02T12:27:03.000Z t:name_of_medicaid_offices="North Central Bronx Hospital" t:telephone_number="(718) 920-1070" t:borough=BRONX m:row_number.fzk8-3ynb=3
```

## Meta Commands

```ls
metric m:row_number.fzk8-3ynb p:long l:"Row Number"

entity e:fzk8-3ynb l:"Medical Assistance Program Medicaid Offices" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/fzk8-3ynb

property e:fzk8-3ynb t:meta.view v:id=fzk8-3ynb v:category="City Government" v:attributionLink=http://www.nyc.gov/html/hia/html/public_insurance/enroll.shtml v:averageRating=0 v:name="Medical Assistance Program Medicaid Offices" v:attribution="Human Resources Administration (HRA)"

property e:fzk8-3ynb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:fzk8-3ynb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | borough   | name_of_medicaid_offices                                                      | address                                                                                | telephone_number        | 
| =========== | ========= | ============================================================================= | ====================================================================================== | ======================= | 
| 1456921623  | BRONX     | Bronx Lebanon Hospital                                                        | 1316 Fulton Avenue, 1st Floor Bronx, New York 10456                                    | (718) 860-4634/4635     | 
| 1456921623  | BRONX     | Lincoln Medical and Mental Health Center                                      | 234 East 149th Street, Basement, Room B-75, Bronx, New York 10451                      | (718) 585-7872/7920     | 
| 1456921623  | BRONX     | North Central Bronx Hospital                                                  | 3424 Kossuth Avenue, 1st Floor, Room 1A 05, Bronx, New York 10467                      | (718) 920-1070          | 
| 1456921623  | BRONX     | Morrisania                                                                    | 1225 Gerard Avenue, Basement Bronx, New York 10452                                     | (718) 960-2799/2752     | 
| 1456921623  | BROOKLYN  | Boerum Hill                                                                   | 35 Fourth Avenue Brooklyn, New York 11217                                              | (718) 623-7427/7428     | 
| 1456921623  | BROOKLYN  | Brooklyn South                                                                | 785 Atlantic Avenue                                                                    | (929) 221-3502          | 
| 1456921623  | BROOKLYN  | Kings County Hospital Medicaid Office                                         | 441 Clarkson Avenue "T" Building Nurses' Residence, 1st Floor Brooklyn, New York 11203 | (718) 718-221-2300/2301 | 
| 1456921623  | BROOKLYN  | Coney Island                                                                  | 30-50 West 21st Street Brooklyn, New York 11224                                        | (929) 221-3776/3790     | 
| 1456921623  | BROOKLYN  | East New York                                                                 | 2094 Pitkin Avenue, Basement Brooklyn, New York 11207                                  | (718) 922-8292/8293     | 
| 1456921623  | MANHATTAN | Bellevue Hospital Medicaid Office (Temporarily closed due to Hurricane Sandy) | 462 First Avenue, ?G? Link, Ground Floor New York, New York 10016                      | (212) 679-7424          | 
```