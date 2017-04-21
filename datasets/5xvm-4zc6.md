# Chemical Dependence Treatment Program Admissions for 55 and Older: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/chemical-dependence-treatment-program-admissions-for-55-and-older-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/5xvm-4zc6) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5xvm-4zc6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5xvm-4zc6/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5xvm-4zc6 |
| Name | Chemical Dependence Treatment Program Admissions for 55 and Older: Beginning 2007 |
| Attribution | Office of Alcoholism and Substance Abuse Services |
| Category | Human Services |
| Tags | admissions, substance abuse, alcohol, heroin, opioids, over 55, senior, elderly, older |
| Created | 2016-11-29T22:26:05Z |
| Publication Date | 2016-12-29T15:15:12Z |

## Description

NYS Office of Alcoholism and Substance Abuse Services (OASAS) certified chemical dependence treatment programs report admissions of people served in programs throughout NYS.  The dataset displays the year of admission, client county of residence, gender, program categories, service type, and primary substance group of clients at admission for clients 55 years and older for nine years of data.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | time           | year                    | Year                    | number    | number      |
| Yes      | series tag     | county_of_residence     | County of Residence     | text      | text        |
| Yes      | series tag     | gender                  | Gender                  | text      | text        |
| Yes      | series tag     | program_category        | Program Category        | text      | text        |
| Yes      | series tag     | service_type            | Service Type            | text      | text        |
| Yes      | series tag     | primary_substance_group | Primary Substance Group | text      | text        |
| Yes      | numeric metric | admissions              | Admissions              | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5xvm-4zc6 d:2007-01-01T00:00:00.000Z t:county_of_residence=Albany t:primary_substance_group=Alcohol t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:gender=Male m:admissions=149

series e:5xvm-4zc6 d:2007-01-01T00:00:00.000Z t:county_of_residence=Albany t:primary_substance_group=Heroin t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:gender=Male m:admissions=18

series e:5xvm-4zc6 d:2007-01-01T00:00:00.000Z t:county_of_residence=Albany t:primary_substance_group="Rx Opioids" t:service_type="Medically Managed Detoxification" t:program_category=Crisis t:gender=Male m:admissions=7
```

## Meta Commands

```ls
metric m:admissions p:integer l:Admissions d:"The sum of the admissions to treatment by year, client county of residence, gender, program category, service type, and primary substance group." t:dataTypeName=number

entity e:5xvm-4zc6 l:"Chemical Dependence Treatment Program Admissions for 55 and Older: Beginning 2007" t:attribution="Office of Alcoholism and Substance Abuse Services" t:url=https://data.ny.gov/api/views/5xvm-4zc6

property e:5xvm-4zc6 t:meta.view v:id=5xvm-4zc6 v:category="Human Services" v:attributionLink=https://apps.oasas.ny.gov/portal/page/portal/OASAS_APPS v:averageRating=0 v:name="Chemical Dependence Treatment Program Admissions for 55 and Older: Beginning 2007" v:attribution="Office of Alcoholism and Substance Abuse Services"

property e:5xvm-4zc6 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5xvm-4zc6 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | county_of_residence | gender | program_category | service_type                     | primary_substance_group | admissions | 
| ==== | =================== | ====== | ================ | ================================ | ======================= | ========== | 
| 2007 | Albany              | Male   | Crisis           | Medically Managed Detoxification | Alcohol                 | 149        | 
| 2007 | Albany              | Male   | Crisis           | Medically Managed Detoxification | Heroin                  | 18         | 
| 2007 | Albany              | Male   | Crisis           | Medically Managed Detoxification | Rx Opioids              | 7          | 
| 2007 | Albany              | Male   | Crisis           | Medically Managed Detoxification | Other or Unknown        | 2          | 
| 2007 | Albany              | Male   | Crisis           | Med Sup Withdrawal - Inpatient   | Alcohol                 | 8          | 
| 2007 | Albany              | Male   | Crisis           | Med Sup Withdrawal - Inpatient   | Rx Opioids              | 1          | 
| 2007 | Albany              | Male   | Crisis           | Medically Monitored Withdrawal   | Alcohol                 | 147        | 
| 2007 | Albany              | Male   | Crisis           | Medically Monitored Withdrawal   | Marijuana incl Hashish  | 1          | 
| 2007 | Albany              | Male   | Crisis           | Medically Monitored Withdrawal   | Other or Unknown        | 5          | 
| 2007 | Albany              | Male   | Inpatient        | Inpatient - Rehabilitation       | Alcohol                 | 65         | 
```