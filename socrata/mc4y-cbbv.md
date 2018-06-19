# NCHS - Top Five Leading Causes of Death: United States, 1990, 1950, 2000

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-five-leading-causes-of-death-united-states-1990-1950-2000) |
| Metadata | [Link](https://data.cdc.gov/api/views/mc4y-cbbv) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/mc4y-cbbv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/mc4y-cbbv/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | mc4y-cbbv |
| Name | NCHS - Top Five Leading Causes of Death: United States, 1990, 1950, 2000 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | cause of death, united states, nchs |
| Created | 2015-07-14T19:50:12Z |
| Publication Date | 2016-06-22T18:02:08Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | leading_causes   | Leading Causes   | text      | text        |
| Yes      | time           | year             | Year             | number    | number      |
| Yes      | numeric metric | number_of_deaths | Number of Deaths | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mc4y-cbbv d:1900-01-01T00:00:00.000Z t:leading_causes=Influenza/Pneumonia m:number_of_deaths=40362

series e:mc4y-cbbv d:1900-01-01T00:00:00.000Z t:leading_causes=Tuberculosis m:number_of_deaths=38820

series e:mc4y-cbbv d:1900-01-01T00:00:00.000Z t:leading_causes="Diarrhea/Enteritis/Ulcerative Colitis" m:number_of_deaths=28491
```

## Meta Commands

```ls
metric m:number_of_deaths p:integer l:"Number of Deaths" t:dataTypeName=number

entity e:mc4y-cbbv l:"NCHS - Top Five Leading Causes of Death: United States, 1990, 1950, 2000" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/mc4y-cbbv

property e:mc4y-cbbv t:meta.view v:id=mc4y-cbbv v:category=NCHS v:averageRating=0 v:name="NCHS - Top Five Leading Causes of Death: United States, 1990, 1950, 2000" v:attribution="National Center for Health Statistics"

property e:mc4y-cbbv t:meta.view.license v:name="Public Domain"

property e:mc4y-cbbv t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:mc4y-cbbv t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:mc4y-cbbv t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| leading_causes                        | year | number_of_deaths | 
| ===================================== | ==== | ================ | 
| Influenza/Pneumonia                   | 1900 | 40362            | 
| Tuberculosis                          | 1900 | 38820            | 
| Diarrhea/Enteritis/Ulcerative Colitis | 1900 | 28491            | 
| Heart Disease                         | 1900 | 27427            | 
| Stroke                                | 1900 | 21353            | 
| Heart Disease                         | 1950 | 535705           | 
| Cancer                                | 1950 | 210733           | 
| Vascular Lesions                      | 1950 | 156751           | 
| Accidents                             | 1950 | 91249            | 
| Certain Diseases of Infancy           | 1950 | 60989            | 
```