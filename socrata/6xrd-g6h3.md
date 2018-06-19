# Maryland PRAMS 2006-2010 Surveillance and Selected Healthy People 2020 Objectives

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/maryland-prams-2006-2010-surveillance-and-selected-healthy-people-2020-objectives-320d9) |
| Metadata | [Link](https://data.maryland.gov/api/views/6xrd-g6h3) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6xrd-g6h3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6xrd-g6h3/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6xrd-g6h3 |
| Name | Maryland PRAMS 2006-2010 Surveillance and Selected Healthy People 2020 Objectives |
| Attribution | Maryland Pregnancy Risk Assessment Monitoring System (PRAMS), U.S. Department of Health and Human Services. |
| Category | Health and Human Services |
| Tags | healthy people 2020, preconception, prenatal, postpartum, risk factors, maternal and child health |
| Created | 2013-01-04T21:31:56Z |
| Publication Date | 2013-01-04T21:36:42Z |

## Description

Results from the Maryland Pregnancy Risk Assessment Monitoring System (PRAMS) survey of new mothers who delivered live births in the years 2006 through 2010 for selected Healthy People 2020 objectives. The two missing values for "Increase abstinence from binge drinking*** among pregnant women." are <100%. [*PRAMS data includes only information on pregnancies that end in live birth. **First trimester defined by PRAMS as <13 weeks. ***Binge drinking = 4 or more drinks in a two hour sitting, starting 2009 births.  Prior to 2009, binge drinking = 5 or more drinks in one episode.]

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                           | Data Type | Render Type |
| ======== | ============== | ============================= | ============================== | ========= | =========== |
| Yes      | series tag     | healthy_people_2020_objective | Healthy People 2020 Objective  | text      | text        |
| Yes      | numeric metric | maryland_prams_2006_births    | Maryland PRAMS 2006 Births (%) | number    | number      |
| Yes      | numeric metric | maryland_prams_2007_births    | Maryland PRAMS 2007 Births (%) | number    | number      |
| Yes      | numeric metric | maryland_prams_2008_births    | Maryland PRAMS 2008 Births (%) | number    | number      |
| Yes      | numeric metric | maryland_prams_2009_births    | Maryland PRAMS 2009 Births (%) | number    | number      |
| Yes      | numeric metric | maryland_prams_2010_births    | Maryland PRAMS 2010 Births (%) | number    | number      |
| Yes      | numeric metric | healthy_people_2020_target    | Healthy People 2020 Target (%) | number    | number      |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6xrd-g6h3 d:2006-01-01T00:00:00.000Z t:healthy_people_2020_objective="Increase the proportion of pregnancies that are intended.*" m:maryland_prams_2010_births=56 m:healthy_people_2020_target=56 m:maryland_prams_2007_births=57 m:maryland_prams_2009_births=55 m:maryland_prams_2008_births=58 m:maryland_prams_2006_births=60

series e:6xrd-g6h3 d:2006-01-01T00:00:00.000Z t:healthy_people_2020_objective="Increase the proportion of women who took multivitamins/folic acid prior to pregnancy." m:maryland_prams_2010_births=33 m:healthy_people_2020_target=33 m:maryland_prams_2007_births=30 m:maryland_prams_2009_births=32 m:maryland_prams_2008_births=30 m:maryland_prams_2006_births=32

series e:6xrd-g6h3 d:2006-01-01T00:00:00.000Z t:healthy_people_2020_objective="Increase the proportion of women who did not smoke during the three months prior to pregnancy." m:maryland_prams_2010_births=81 m:healthy_people_2020_target=85.4 m:maryland_prams_2007_births=83 m:maryland_prams_2009_births=83 m:maryland_prams_2008_births=81 m:maryland_prams_2006_births=85
```

## Meta Commands

```ls
metric m:maryland_prams_2006_births p:integer l:"Maryland PRAMS 2006 Births (%)" t:dataTypeName=number

metric m:maryland_prams_2007_births p:integer l:"Maryland PRAMS 2007 Births (%)" t:dataTypeName=number

metric m:maryland_prams_2008_births p:integer l:"Maryland PRAMS 2008 Births (%)" t:dataTypeName=number

metric m:maryland_prams_2009_births p:integer l:"Maryland PRAMS 2009 Births (%)" t:dataTypeName=number

metric m:maryland_prams_2010_births p:integer l:"Maryland PRAMS 2010 Births (%)" t:dataTypeName=number

metric m:healthy_people_2020_target p:float l:"Healthy People 2020 Target (%)" t:dataTypeName=number

entity e:6xrd-g6h3 l:"Maryland PRAMS 2006-2010 Surveillance and Selected Healthy People 2020 Objectives" t:attribution="Maryland Pregnancy Risk Assessment Monitoring System (PRAMS), U.S. Department of Health and Human Services." t:url=https://data.maryland.gov/api/views/6xrd-g6h3

property e:6xrd-g6h3 t:meta.view v:id=6xrd-g6h3 v:category="Health and Human Services" v:attributionLink=http://fha.dhmh.maryland.gov/mch/SitePages/prams.aspx v:averageRating=0 v:name="Maryland PRAMS 2006-2010 Surveillance and Selected Healthy People 2020 Objectives" v:attribution="Maryland Pregnancy Risk Assessment Monitoring System (PRAMS), U.S. Department of Health and Human Services."

property e:6xrd-g6h3 t:meta.view.owner v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:displayName="Andrea Bankoski"

property e:6xrd-g6h3 t:meta.view.tableauthor v:id=e5tx-wz6d v:screenName="Andrea Bankoski" v:roleName=editor v:displayName="Andrea Bankoski"
```

## Top Records

```ls
| healthy_people_2020_objective                                                                                        | maryland_prams_2006_births | maryland_prams_2007_births | maryland_prams_2008_births | maryland_prams_2009_births | maryland_prams_2010_births | healthy_people_2020_target | 
| ==================================================================================================================== | ========================== | ========================== | ========================== | ========================== | ========================== | ========================== | 
| Increase the proportion of pregnancies that are intended.*                                                           | 60                         | 57                         | 58                         | 55                         | 56                         | 56.0                       | 
| Increase the proportion of women who took multivitamins/folic acid prior to pregnancy.                               | 32                         | 30                         | 30                         | 32                         | 33                         | 33.0                       | 
| Increase the proportion of women who did not smoke during the three months prior to pregnancy.                       | 85                         | 83                         | 81                         | 83                         | 81                         | 85.4                       | 
| Increase the proportion of women who did not drink alcohol during the three months prior to pregnancy.               | 51                         | 49                         | 47                         | 45                         | 46                         | 56.6                       | 
| Increase the proportion of women who had a healthy weight (BMI 18.5-24.9) prior to pregnancy.                        | 51                         | 56                         | 52                         | 53                         | 51                         | 53.6                       | 
| Increase the proportion of pregnant women who receive prenatal care beginning in the first trimester of pregnancy.** | 74                         | 76                         | 78                         | 79                         | 78                         | 77.9                       | 
| Increase abstinence from cigarette smoking among pregnant women.                                                     | 92                         | 91                         | 89                         | 91                         | 91                         | 98.6                       | 
| Increase abstinence from alcohol among pregnant women.                                                               | 93                         | 93                         | 91                         | 90                         | 91                         | 98.3                       | 
| Increase abstinence from binge drinking*** among pregnant women.                                                     |                            |                            | 99                         | 98                         | 99                         | 100.0                      | 
| Increase the proportion of infants who are put to sleep on their backs.                                              | 69                         | 71                         | 69                         | 74                         | 72                         | 75.9                       | 
```