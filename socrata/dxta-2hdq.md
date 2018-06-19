# MCFFA (Medical Care Facilities Financing Agency) Bonds and Notes: Beginning 1995

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mcffa-medical-care-facilities-financing-agency-bonds-and-notes-beginning-1995) |
| Metadata | [Link](https://data.ny.gov/api/views/dxta-2hdq) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/dxta-2hdq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/dxta-2hdq/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | dxta-2hdq |
| Name | MCFFA (Medical Care Facilities Financing Agency) Bonds and Notes: Beginning 1995 |
| Attribution | Dormitory Authority State of New York |
| Category | Economic Development |
| Tags | finance, medical care facilities financing agency (mcffa), bond series, maturity status, defeased date, bond series par amount, bond series par amount outstanding, bonds |
| Created | 2014-01-27T16:25:08Z |
| Publication Date | 2016-07-20T22:03:56Z |

## Description

DASNY assumed all bonds and notes outstanding fromthe Medical Care Facilities Financing Agency (MCFFA)on September 1, 1995. DASNY maintains a cumulativerecord of this debt, which is updated quarterly. Thedataset includes details such as Bond Series Name,Maturity Status/Matured or Defeased Date, Bond SeriesPar Amount and Bond Series Par Amount Outstanding.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type | Render Type |
| ======== | ============== | ======================================== | ======================================== | ========= | =========== |
| Yes      | series tag     | bond_series_name                         | Bond Series Name                         | text      | text        |
| No       |                | maturity_status_matured_or_defeased_date | Maturity Status/Matured or Defeased Date | text      | text        |
| Yes      | numeric metric | bond_series_par_amount                   | Bond Series Par Amount                   | money     | money       |
| Yes      | numeric metric | bond_series_par_amount_outstanding       | Bond Series Par Amount Outstanding       | money     | money       |
```

## Time Field

```ls
Value = 1995
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = maturity_status_matured_or_defeased_date
```

## Data Commands

```ls
series e:dxta-2hdq d:1995-01-01T00:00:00.000Z t:bond_series_name="Hospital & Nursing Home FHA-Brooklyn Hospital 1998A" m:bond_series_par_amount_outstanding=0 m:bond_series_par_amount=58925000

series e:dxta-2hdq d:1995-01-01T00:00:00.000Z t:bond_series_name="Adult Day Care Project Revenue Bonds 1995 A" m:bond_series_par_amount_outstanding=1735000 m:bond_series_par_amount=39840000

series e:dxta-2hdq d:1995-01-01T00:00:00.000Z t:bond_series_name="Aurelia Osborn Fox Memorial Hospital Project Revenue Bonds, 1992 A" m:bond_series_par_amount_outstanding=0 m:bond_series_par_amount=14485000
```

## Meta Commands

```ls
metric m:bond_series_par_amount p:integer l:"Bond Series Par Amount" d:"Amount of the bonds issued for that particular series of bonds." t:dataTypeName=money

metric m:bond_series_par_amount_outstanding p:integer l:"Bond Series Par Amount Outstanding" d:"Amount outstanding for that particular bond series." t:dataTypeName=money

entity e:dxta-2hdq l:"MCFFA (Medical Care Facilities Financing Agency) Bonds and Notes: Beginning 1995" t:attribution="Dormitory Authority State of New York" t:url=https://data.ny.gov/api/views/dxta-2hdq

property e:dxta-2hdq t:meta.view v:id=dxta-2hdq v:category="Economic Development" v:averageRating=0 v:name="MCFFA (Medical Care Facilities Financing Agency) Bonds and Notes: Beginning 1995" v:attribution="Dormitory Authority State of New York"

property e:dxta-2hdq t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:dxta-2hdq t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:dxta-2hdq t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bond_series_name                                                       | maturity_status_matured_or_defeased_date | bond_series_par_amount | bond_series_par_amount_outstanding | 
| ====================================================================== | ======================================== | ====================== | ================================== | 
| Hospital & Nursing Home FHA-Brooklyn Hospital 1998A                    | 8/27/07                                  | 58925000               | 0                                  | 
| Adult Day Care Project Revenue Bonds 1995 A                            | OUTSTANDING                              | 39840000               | 1735000                            | 
| Aurelia Osborn Fox Memorial Hospital Project Revenue Bonds, 1992 A     | 11/18/98                                 | 14485000               | 0                                  | 
| Beth Israel Medical Center (Main Campus) Project Revenue Bonds, 1989 A | 12/31/03                                 | 66000000               | 0                                  | 
| Beth Israel Medical Center (Main Campus) Project Revenue Bonds, 1990 A | 11/20/97                                 | 54080000               | 0                                  | 
| Beth Israel Medical Center (Main Campus) Project Revenue Bonds, 1993 A | 9/2/04                                   | 64050000               | 0                                  | 
| Beth Israel Medical Center (Main Campus), 1994 A                       | 9/2/04                                   | 42125000               | 0                                  | 
| Beth Israel Medical Center Project Revenue Bonds, 1986 A Refunding     | 12/31/03                                 | 28875000               | 0                                  | 
| Brookdale Hospital Medical Center Secured Hospital Revenue Bonds 1995A | 2/26/98                                  | 130885000              | 0                                  | 
| Central Suffolk Hospital Mortgage Project Revenue Bonds, 1993 A        | 06/23/06                                 | 23765000               | 0                                  | 
```