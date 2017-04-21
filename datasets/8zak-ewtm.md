# BRFSS Prevalence and Trends Data: Tobacco Use - Four Level Smoking Data for 1995-2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/brfss-prevalence-and-trends-data-tobacco-use-four-level-smoking-data-for-1995-2010) |
| Metadata | [Link](https://data.cdc.gov/api/views/8zak-ewtm) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/8zak-ewtm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/8zak-ewtm/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | 8zak-ewtm |
| Name | BRFSS Prevalence and Trends Data: Tobacco Use - Four Level Smoking Data for 1995-2010 |
| Attribution | Behavioral Risk Factor Surveillance System (BRFSS) |
| Category | Smoking & Tobacco Use |
| Tags | brfss, current smokers, former smoker, non-smoker |
| Created | 2013-06-11T12:40:31Z |
| Publication Date | 2013-08-02T15:35:52Z |

## Description

Percentages are weighted to population characteristics. Data are not available if it did not meet BRFSS stability requirements.For more information on these requirements, as well as risk factors and calculated variables, see the Technical Documents and Survey Data for a specific year - http://www.cdc.gov/brfss/annual_data/annual_data.htm.Recommended citation: Centers for Disease Control and Prevention (CDC). Behavioral Risk Factor Surveillance System. Atlanta, Georgia: U.S. Department of Health and Human Services, Centers for Disease Control and Prevention, [appropriate year].

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | time           | year            | Year            | number    | number      |
| Yes      | series tag     | state           | State           | text      | text        |
| Yes      | numeric metric | smoke_everyday  | Smoke everyday  | percent   | percent     |
| Yes      | numeric metric | smoke_some_days | Smoke some days | percent   | percent     |
| Yes      | numeric metric | former_smoker   | Former smoker   | percent   | percent     |
| Yes      | numeric metric | never_smoked    | Never smoked    | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8zak-ewtm d:1996-01-01T00:00:00.000Z t:state="Puerto Rico" m:former_smoker=16 m:never_smoked=69.5 m:smoke_some_days=5.1 m:smoke_everyday=9.4

series e:8zak-ewtm d:1997-01-01T00:00:00.000Z t:state="Puerto Rico" m:former_smoker=15.7 m:never_smoked=69.9 m:smoke_some_days=5 m:smoke_everyday=9.4

series e:8zak-ewtm d:1998-01-01T00:00:00.000Z t:state="Puerto Rico" m:former_smoker=16.8 m:never_smoked=67.9 m:smoke_some_days=5.2 m:smoke_everyday=10.1
```

## Meta Commands

```ls
metric m:smoke_everyday p:float l:"Smoke everyday" t:dataTypeName=percent

metric m:smoke_some_days p:float l:"Smoke some days" t:dataTypeName=percent

metric m:former_smoker p:float l:"Former smoker" t:dataTypeName=percent

metric m:never_smoked p:float l:"Never smoked" t:dataTypeName=percent

entity e:8zak-ewtm l:"BRFSS Prevalence and Trends Data: Tobacco Use - Four Level Smoking Data for 1995-2010" t:attribution="Behavioral Risk Factor Surveillance System (BRFSS)" t:url=https://data.cdc.gov/api/views/8zak-ewtm

property e:8zak-ewtm t:meta.view v:id=8zak-ewtm v:category="Smoking & Tobacco Use" v:attributionLink=http://www.cdc.gov/brfss v:averageRating=0 v:name="BRFSS Prevalence and Trends Data: Tobacco Use - Four Level Smoking Data for 1995-2010" v:attribution="Behavioral Risk Factor Surveillance System (BRFSS)"

property e:8zak-ewtm t:meta.view.owner v:id=7vdi-f8f4 v:screenName=Mark@CDC v:displayName=Mark@CDC

property e:8zak-ewtm t:meta.view.tableauthor v:id=7vdi-f8f4 v:screenName=Mark@CDC v:roleName=editor v:displayName=Mark@CDC

property e:8zak-ewtm t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| year | state          | smoke_everyday | smoke_some_days | former_smoker | never_smoked | 
| ==== | ============== | ============== | =============== | ============= | ============ | 
| 1996 | Puerto Rico    | 9.4            | 5.1             | 16            | 69.5         | 
| 1997 | Puerto Rico    | 9.4            | 5               | 15.7          | 69.9         | 
| 1998 | Puerto Rico    | 10.1           | 5.2             | 16.8          | 67.9         | 
| 1999 | Puerto Rico    | 9.7            | 4               | 15.3          | 71           | 
| 2000 | Puerto Rico    | 9.2            | 3.9             | 15.2          | 71.6         | 
| 2001 | Puerto Rico    | 8              | 4.5             | 17            | 70.5         | 
| 2001 | Virgin Islands | 6.9            | 2.7             | 12.6          | 77.8         | 
| 2002 | Puerto Rico    | 8.8            | 4.4             | 16.9          | 69.8         | 
| 2002 | Virgin Islands | 7              | 2.4             | 12.1          | 78.5         | 
| 2003 | Puerto Rico    | 8.9            | 4.6             | 17.7          | 68.8         | 
```