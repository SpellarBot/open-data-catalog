# Capital District Transportation Authority (CDTA) Annual Reports: Beginning 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-district-transportation-authority-cdta-annual-reports-beginning-2007) |
| Metadata | [Link](https://data.ny.gov/api/views/vqr5-qxvt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/vqr5-qxvt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/vqr5-qxvt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | vqr5-qxvt |
| Name | Capital District Transportation Authority (CDTA) Annual Reports: Beginning 2007 |
| Attribution | Capital District Transportation Authority |
| Category | Transportation |
| Tags | transportation, annual report, financial |
| Created | 2013-03-03T18:18:41Z |
| Publication Date | 2016-02-22T15:55:50Z |

## Description

CDTA is a public transportation authority in the Capital Region.  This dataset presents information that external stakeholders find valuable for understanding the governance, financial, and strategic positions of the organization.  The dataset being reported contains organization number of employees, number of vehicles, and operating budget.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | fiscal_year         | Fiscal Year         | text      | text        |
| Yes      | numeric metric | number_of_employees | Number of Employees | number    | number      |
| Yes      | numeric metric | number_of_vehicles  | Number of Vehicles  | number    | number      |
| Yes      | numeric metric | annual_budget       | Annual Budget       | money     | money       |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vqr5-qxvt d:2007-01-01T00:00:00.000Z t:fiscal_year=FY2007 m:number_of_employees=650 m:number_of_vehicles=322 m:annual_budget=64000000

series e:vqr5-qxvt d:2007-01-01T00:00:00.000Z t:fiscal_year=FY2008 m:number_of_employees=650 m:number_of_vehicles=275 m:annual_budget=64500000

series e:vqr5-qxvt d:2007-01-01T00:00:00.000Z t:fiscal_year=FY2009 m:number_of_employees=650 m:number_of_vehicles=299 m:annual_budget=71000000
```

## Meta Commands

```ls
metric m:number_of_employees p:integer l:"Number of Employees" d:"Quantity of active full and part-time staff." t:dataTypeName=number

metric m:number_of_vehicles p:integer l:"Number of Vehicles" d:"Quantity of active revenue vehicles in fleet." t:dataTypeName=number

metric m:annual_budget p:integer l:"Annual Budget" d:"Value used to reflect annual incomes and expenditures." t:dataTypeName=money

entity e:vqr5-qxvt l:"Capital District Transportation Authority (CDTA) Annual Reports: Beginning 2007" t:attribution="Capital District Transportation Authority" t:url=https://data.ny.gov/api/views/vqr5-qxvt

property e:vqr5-qxvt t:meta.view v:id=vqr5-qxvt v:category=Transportation v:attributionLink=http://www.cdta.org/about_annual_report.php v:averageRating=0 v:name="Capital District Transportation Authority (CDTA) Annual Reports: Beginning 2007" v:attribution="Capital District Transportation Authority"

property e:vqr5-qxvt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:vqr5-qxvt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:vqr5-qxvt t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| fiscal_year | number_of_employees | number_of_vehicles | annual_budget | 
| =========== | =================== | ================== | ============= | 
| FY2007      | 650                 | 322                | 64000000      | 
| FY2008      | 650                 | 275                | 64500000      | 
| FY2009      | 650                 | 299                | 71000000      | 
| FY2010      | 700                 | 306                | 73500000      | 
| FY2011      | 704                 | 306                | 73500000      | 
| FY2012      | 642                 | 306                | 74300000      | 
| FY2013      | 650                 | 277                | 74392000      | 
| FY2014      | 638                 | 306                | 76100000      | 
| FY2015      | 650                 | 306                | 79000000      | 
```