# Public Health Services - Licensed Substance Abuse Treatment Providers in Chicago, 2011

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-health-services-licensed-substance-abuse-treatment-providers-in-chicago-2011-a261e) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/9zqv-3uhs) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/9zqv-3uhs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/9zqv-3uhs/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 9zqv-3uhs |
| Name | Public Health Services - Licensed Substance Abuse Treatment Providers in Chicago, 2011 |
| Attribution | Chicago Department of Public Health Office of Substance Abuse |
| Category | Health & Human Services |
| Tags | alcohol, drugs, substance abuse |
| Created | 2011-12-27T17:23:16Z |
| Publication Date | 2012-01-24T21:00:27Z |

## Description

Detailed listing of licensed substance abuse treatment providers, treatment modalities, and populations served in Chicago as of April 2011.  See the full dataset description for more information: http://bit.ly/z4SLQ3

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| Yes      | series tag  | treatment_center   | Treatment Center   | text      | text        |
| Yes      | series tag  | suite_floor_number | Suite/Floor Number | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | text        |
| Yes      | series tag  | service_modalities | Service Modalities | text      | text        |
| Yes      | series tag  | population_served  | Population Served  | text      | text        |
| Yes      | series tag  | payment_method     | Payment Method     | text      | text        |
| No       |             | address            | Address            | text      | text        |
| Yes      | series tag  | city               | City               | text      | text        |
| Yes      | series tag  | state              | State              | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:9zqv-3uhs d:2011-01-01T00:00:00.000Z t:phone_number=773-435-8300 t:zip_code=60636 t:service_modalities="RH Level 1, 2, & 3.5" t:treatment_center="A Safe Haven & Main Intake Number" t:state=Illinois t:population_served="Adults & Adolescents" t:payment_method="Sliding Scale" t:city=Chicago m:row_number.9zqv-3uhs=1

series e:9zqv-3uhs d:2011-01-01T00:00:00.000Z t:phone_number="773-262-1974 x107" t:zip_code=60645 t:service_modalities=RH t:treatment_center="A Safe Haven Damen" t:state=Illinois t:population_served=Adults t:payment_method="Sliding Scale" t:city=Chicago m:row_number.9zqv-3uhs=2

series e:9zqv-3uhs d:2011-01-01T00:00:00.000Z t:phone_number="773-722-7900 x4052" t:zip_code=60612 t:service_modalities="Level 1 & 2" t:treatment_center="Bobby E. Wright CBHC Additions Program" t:state=Illinois t:population_served="Adults & Adolescents" t:payment_method="Sliding Scale, Medicaid, Client Fee" t:city=Chicago m:row_number.9zqv-3uhs=3
```

## Meta Commands

```ls
metric m:row_number.9zqv-3uhs p:long l:"Row Number"

entity e:9zqv-3uhs l:"Public Health Services - Licensed Substance Abuse Treatment Providers in Chicago, 2011" t:attribution="Chicago Department of Public Health Office of Substance Abuse" t:url=https://data.cityofchicago.org/api/views/9zqv-3uhs

property e:9zqv-3uhs t:meta.view v:id=9zqv-3uhs v:category="Health & Human Services" v:averageRating=0 v:name="Public Health Services - Licensed Substance Abuse Treatment Providers in Chicago, 2011" v:attribution="Chicago Department of Public Health Office of Substance Abuse"

property e:9zqv-3uhs t:meta.view.owner v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia

property e:9zqv-3uhs t:meta.view.tableauthor v:id=is6y-5c5n v:screenName=Jamyia v:displayName=Jamyia
```

## Top Records

```ls
| treatment_center                            | suite_floor_number | phone_number       | service_modalities                   | population_served                    | payment_method                      | address               | city    | state    | zip_code | 
| =========================================== | ================== | ================== | ==================================== | ==================================== | =================================== | ===================== | ======= | ======== | ======== | 
| A Safe Haven & Main Intake Number           |                    | 773-435-8300       | RH Level 1, 2, & 3.5                 | Adults & Adolescents                 | Sliding Scale                       | 2750 W Roosevelt Rd   | Chicago | Illinois | 60636    | 
| A Safe Haven Damen                          |                    | 773-262-1974 x107  | RH                                   | Adults                               | Sliding Scale                       | 7349 N Damen Ave      | Chicago | Illinois | 60645    | 
| Bobby E. Wright CBHC Additions Program      |                    | 773-722-7900 x4052 | Level 1 & 2                          | Adults & Adolescents                 | Sliding Scale, Medicaid, Client Fee | 9 S Kedzie Ave        | Chicago | Illinois | 60612    | 
| Alexian Brothers Bonaventure House          |                    | 773-327-9921 x123  | RH                                   | Adult Women, HIV/AIDS, Gay & Lesbian | Self Payment, Sliding Scale         | 825 W Wellington St   | Chicago | Illinois | 60657    | 
| American Indian Health Services             |                    | 773-883-9100       | Level 1                              | Adults & Adolescents                 | Sliding Scale                       | 4081 N BRdway St      | Chicago | Illinois | 60613    | 
| Annie B Jones Community Services Inc.       |                    | 773-667-2100       | Level 1 & 2                          | Adults & Adolescents                 | Medicaid                            | 1818 E 71st St        | Chicago | Illinois | 60649    | 
| Anixter Center/Schwab Rehabilitation Center |                    | 773-522-2010       | Level 1 & 2                          | Adults                               | Medicaid                            | 1401 S California Ave | Chicago | Illinois | 60608    | 
| Advance Counseling Services Inc.            |                    | 773-503-6345       | Level 1                              | Adults                               | Self Payment                        | 4125 S Archer Ave     | Chicago | Illinois | 60632    | 
| Access Behavioral Services, Inc.            | Suite 114          | 312-659-3570       | Level 1 & 2, DUI Services            | Adults                               | Contact Agency                      | 3948 W 26th St        | Chicago | Illinois | 60623    | 
| Cermak Health Services of Cook County       |                    | 773-869-5641       | Ambulatory Detox, Methadone Services | Adults                               | Contact Agency                      | 2800 S California Ave | Chicago | Illinois | 60608    | 
```