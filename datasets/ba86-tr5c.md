# City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-university-of-new-york-cuny-university-retention-and-graduation-rates-beginning-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/ba86-tr5c) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ba86-tr5c/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ba86-tr5c/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ba86-tr5c |
| Name | City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990 |
| Attribution | City University of New York |
| Category | Education |
| Tags | higher education, enrollment |
| Created | 2014-01-17T17:03:53Z |
| Publication Date | 2015-12-23T17:44:26Z |

## Description

Data set contains one year retention rates and 150 time graduation rates (3yr rates for associate degree seekers and 6yr rates for baccalaureate seekers) for all CUNY colleges from 1990 through present where applicable for first-time, full-time freshmen.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | college                 | College                 | text      | text        |
| Yes      | series tag     | fall_term               | Fall Term               | text      | text        |
| Yes      | series tag     | record_type_code        | Record Type Code        | text      | number      |
| Yes      | series tag     | record_type_description | Record Type Description | text      | text        |
| Yes      | numeric metric | head_count              | Head Count              | number    | number      |
| Yes      | numeric metric | percentage              | Percentage              | percent   | percent     |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ba86-tr5c d:1990-01-01T00:00:00.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=81.8 m:head_count=1278

series e:ba86-tr5c d:1990-01-01T00:00:00.000Z t:record_type_code=2 t:record_type_description="150 Time Graduation" t:college="CUNY Baruch College" t:fall_term="Fall 1990" m:percentage=39.3 m:head_count=1278

series e:ba86-tr5c d:1990-01-01T00:00:00.000Z t:record_type_code=1 t:record_type_description="1 Year Retention" t:college="CUNY Baruch College" t:fall_term="Fall 1991" m:percentage=84.4 m:head_count=1170
```

## Meta Commands

```ls
metric m:head_count p:integer l:"Head Count" t:dataTypeName=number

metric m:percentage p:float l:Percentage t:dataTypeName=percent

entity e:ba86-tr5c l:"City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" t:attribution="City University of New York" t:url=https://data.ny.gov/api/views/ba86-tr5c

property e:ba86-tr5c t:meta.view v:id=ba86-tr5c v:category=Education v:averageRating=0 v:name="City University of New York (CUNY) University Retention and Graduation Rates: Beginning 1990" v:attribution="City University of New York"

property e:ba86-tr5c t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ba86-tr5c t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| college             | fall_term | record_type_code | record_type_description | head_count | percentage | 
| =================== | ========= | ================ | ======================= | ========== | ========== | 
| CUNY Baruch College | Fall 1990 | 1                | 1 Year Retention        | 1278       | 81.8       | 
| CUNY Baruch College | Fall 1990 | 2                | 150 Time Graduation     | 1278       | 39.3       | 
| CUNY Baruch College | Fall 1991 | 1                | 1 Year Retention        | 1170       | 84.4       | 
| CUNY Baruch College | Fall 1991 | 2                | 150 Time Graduation     | 1170       | 38.3       | 
| CUNY Baruch College | Fall 1992 | 1                | 1 Year Retention        | 1359       | 83.4       | 
| CUNY Baruch College | Fall 1992 | 2                | 150 Time Graduation     | 1359       | 34.8       | 
| CUNY Baruch College | Fall 1993 | 1                | 1 Year Retention        | 1300       | 82.5       | 
| CUNY Baruch College | Fall 1993 | 2                | 150 Time Graduation     | 1300       | 34.5       | 
| CUNY Baruch College | Fall 1994 | 1                | 1 Year Retention        | 1474       | 79.4       | 
| CUNY Baruch College | Fall 1994 | 2                | 150 Time Graduation     | 1474       | 33.5       | 
```