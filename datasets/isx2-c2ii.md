# NCHS - Percent Distribution of Births, by Maternal Age: United States, 1933-2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/percent-distribution-of-births-by-maternal-age-united-states-1933-2013) |
| Metadata | [Link](https://data.cdc.gov/api/views/isx2-c2ii) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/isx2-c2ii/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/isx2-c2ii/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | isx2-c2ii |
| Name | NCHS - Percent Distribution of Births, by Maternal Age: United States, 1933-2013 |
| Attribution | National Center for Health Statistics |
| Category | NCHS |
| Tags | maternal age, births, united states, nchs |
| Created | 2015-12-02T19:09:26Z |
| Publication Date | 2015-12-02T19:12:25Z |

## Description

http://blogs.cdc.gov/nchs-data-visualization/us-natality-trends/

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | year                | Year                | number    | number      |
| Yes      | series tag     | age_group           | Age Group           | text      | text        |
| Yes      | numeric metric | percentage_of_birth | Percentage of Birth | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:isx2-c2ii d:1933-01-01T00:00:00.000Z t:age_group=15-19 m:percentage_of_birth=12.1

series e:isx2-c2ii d:1933-01-01T00:00:00.000Z t:age_group=20-24 m:percentage_of_birth=30

series e:isx2-c2ii d:1933-01-01T00:00:00.000Z t:age_group=25-29 m:percentage_of_birth=26.1
```

## Meta Commands

```ls
metric m:percentage_of_birth p:float l:"Percentage of Birth" t:dataTypeName=percent

entity e:isx2-c2ii l:"NCHS - Percent Distribution of Births, by Maternal Age: United States, 1933-2013" t:attribution="National Center for Health Statistics" t:url=https://data.cdc.gov/api/views/isx2-c2ii

property e:isx2-c2ii t:meta.view v:id=isx2-c2ii v:category=NCHS v:averageRating=0 v:name="NCHS - Percent Distribution of Births, by Maternal Age: United States, 1933-2013" v:attribution="National Center for Health Statistics"

property e:isx2-c2ii t:meta.view.license v:name="Public Domain"

property e:isx2-c2ii t:meta.view.owner v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:displayName=hku4@cdc.gov

property e:isx2-c2ii t:meta.view.tableauthor v:id=ki96-txhe v:profileImageUrlMedium=/api/users/ki96-txhe/profile_images/THUMB v:profileImageUrlLarge=/api/users/ki96-txhe/profile_images/LARGE v:screenName=hku4@cdc.gov v:profileImageUrlSmall=/api/users/ki96-txhe/profile_images/TINY v:roleName=administrator v:displayName=hku4@cdc.gov

property e:isx2-c2ii t:meta.view.metadata.custom_fields.common_core v:Publisher="National Center for Health Statistics" v:Contact_Email=hku4@cdc.gov v:Contact_Name="National Center for Health Statistics" v:Bureau_Code=009:020 v:Program_Code=009:000
```

## Top Records

```ls
| year | age_group       | percentage_of_birth | 
| ==== | =============== | =================== | 
| 1933 | 15-19           | 12.10               | 
| 1933 | 20-24           | 30.00               | 
| 1933 | 25-29           | 26.10               | 
| 1933 | 30-34           | 17.10               | 
| 1933 | 35-39           | 10.60               | 
| 1933 | 40-44           | 3.70                | 
| 1933 | 45 years & over | 0.40                | 
| 1933 | Under 15 years  | 0.10                | 
| 1934 | 15-19           | 12.30               | 
| 1934 | 20-24           | 30.40               | 
```