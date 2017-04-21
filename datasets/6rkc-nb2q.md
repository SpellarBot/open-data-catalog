# NCHS - Age-adjusted Death Rates for Selected Major Causes of Death: United States, 1900-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/age-adjusted-death-rates-for-selected-major-causes-of-death-united-states-1900-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/6rkc-nb2q) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/6rkc-nb2q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/6rkc-nb2q/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 6rkc-nb2q |
| Name | NCHS - Age-adjusted Death Rates for Selected Major Causes of Death: United States, 1900-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | age-adjusted death rate, cause of death, united states, nchs |
| Created | 2015-07-14T19:46:11Z |
| Publication Date | 2016-06-22T18:00:30Z |

## Description

Revisions to the International Classification of Diseases (ICD) over time may result in discontinuities in cause-of-death trends. http://blogs.cdc.gov/nchs-data-visualization/deaths-in-the-us/

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | leading_causes          | Leading Causes          | text      | text        |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | numeric metric | age_adjusted_death_rate | Age Adjusted Death Rate | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6rkc-nb2q d:1900-01-01T00:00:00.000Z t:leading_causes="Heart Disease" m:age_adjusted_death_rate=265.4

series e:6rkc-nb2q d:1901-01-01T00:00:00.000Z t:leading_causes="Heart Disease" m:age_adjusted_death_rate=272.6

series e:6rkc-nb2q d:1902-01-01T00:00:00.000Z t:leading_causes="Heart Disease" m:age_adjusted_death_rate=285.2
```

## Meta Commands

```ls
metric m:age_adjusted_death_rate p:float l:"Age Adjusted Death Rate" t:dataTypeName=number

entity e:6rkc-nb2q l:"NCHS - Age-adjusted Death Rates for Selected Major Causes of Death: United States, 1900-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/6rkc-nb2q

property e:6rkc-nb2q t:meta.view v:id=6rkc-nb2q v:category=NCHS v:averageRating=0 v:name="NCHS - Age-adjusted Death Rates for Selected Major Causes of Death: United States, 1900-2013" v:attribution="National Center for Health Statistics"

property e:6rkc-nb2q t:meta.view.license v:name="Public Domain"

property e:6rkc-nb2q t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:6rkc-nb2q t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:6rkc-nb2q t:meta.view.metadata.custom_fields.common_core v:Contact_Email=hku4@cdc.gov v:Publisher="National Center for Health Statistics" v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| leading_causes | year | age_adjusted_death_rate | 
| ============== | ==== | ======================= | 
| Heart Disease  | 1900 | 265.4                   | 
| Heart Disease  | 1901 | 272.6                   | 
| Heart Disease  | 1902 | 285.2                   | 
| Heart Disease  | 1903 | 304.5                   | 
| Heart Disease  | 1904 | 331.5                   | 
| Heart Disease  | 1905 | 327.8                   | 
| Heart Disease  | 1906 | 325.5                   | 
| Heart Disease  | 1907 | 356.5                   | 
| Heart Disease  | 1908 | 328.6                   | 
| Heart Disease  | 1909 | 329.2                   | 
```