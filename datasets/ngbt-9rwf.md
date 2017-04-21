# Chemical Dependence Treatment Program Admissions: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chemical-dependence-treatment-program-admissions-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/ngbt-9rwf) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ngbt-9rwf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ngbt-9rwf/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ngbt-9rwf |
| Name | Chemical Dependence Treatment Program Admissions: Beginning 2007 |
| Attribution | Office of Alcoholism and Substance Abuse Services |
| Category | Human Services |
| Tags | admissions, substance abuse, alcohol, heroin, opiates |
| Created | 2014-02-11T20:04:50Z |
| Publication Date | 2016-05-18T22:08:49Z |

## Description

NYS Office of Alcoholism and Substance Abuse Services (OASAS) certified chemical dependence treatment programs report admissions of people served in programs throughout NYS.  This dataset includes the number of admissions to NYS OASAS certified treatment programs aggregated by the program category, county of the program location, age group of client at admission, and the primary substance of abuse group.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | county_of_program_location | County of Program Location | text      | text        |
| Yes      | series tag     | program_category           | Program Category           | text      | text        |
| Yes      | series tag     | service_type               | Service Type               | text      | text        |
| Yes      | series tag     | age_group                  | Age Group                  | text      | text        |
| Yes      | series tag     | primary_substance_group    | Primary Substance Group    | text      | text        |
| Yes      | numeric metric | admissions                 | Admissions                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ngbt-9rwf d:2007-01-01T00:00:00.000Z t:primary_substance_group=Heroin t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:county_of_program_location=Albany t:age_group="Under 18" m:admissions=4

series e:ngbt-9rwf d:2007-01-01T00:00:00.000Z t:primary_substance_group=Alcohol t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:county_of_program_location=Albany t:age_group="18 thru 24" m:admissions=35

series e:ngbt-9rwf d:2007-01-01T00:00:00.000Z t:primary_substance_group=Heroin t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:county_of_program_location=Albany t:age_group="18 thru 24" m:admissions=132
```

## Meta Commands

```ls
metric m:admissions p:integer l:Admissions d:"The sum of the admissions to treatment by year, county of program location, program category, age group, and primary substance group." t:dataTypeName=number

entity e:ngbt-9rwf l:"Chemical Dependence Treatment Program Admissions: Beginning 2007" t:attribution="Office of Alcoholism and Substance Abuse Services" t:url=https://data.ny.gov/api/views/ngbt-9rwf

property e:ngbt-9rwf t:meta.view v:id=ngbt-9rwf v:category="Human Services" v:attributionLink=https://apps.oasas.ny.gov/portal/page/portal/OASAS_APPS v:averageRating=0 v:name="Chemical Dependence Treatment Program Admissions: Beginning 2007" v:attribution="Office of Alcoholism and Substance Abuse Services"

property e:ngbt-9rwf t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ngbt-9rwf t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ngbt-9rwf t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | county_of_program_location | program_category | service_type                     | age_group  | primary_substance_group | admissions | 
| ==== | ========================== | ================ | ================================ | ========== | ======================= | ========== | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | Under 18   | Heroin                  | 4          | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 18 thru 24 | Alcohol                 | 35         | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 18 thru 24 | Heroin                  | 132        | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 18 thru 24 | Rx Opioids              | 6          | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 18 thru 24 | Other or Unknown        | 2          | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 25 thru 34 | Alcohol                 | 135        | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 25 thru 34 | Heroin                  | 276        | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 25 thru 34 | Cocaine incl Crack      | 1          | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 25 thru 34 | Rx Opioids              | 11         | 
| 2007 | Albany                     | Crisis           | Medically Managed Detoxification | 25 thru 34 | Other or Unknown        | 8          | 
```