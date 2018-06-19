# DASNY (Dormitory Authority of the State of New York) Bonds and Notes: Beginning 1957

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dasny-dormitory-authority-of-the-state-of-new-york-bonds-and-notes-beginning-1957) |
| Metadata | [Link](https://data.ny.gov/api/views/iyue-ijfp) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/iyue-ijfp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/iyue-ijfp/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | iyue-ijfp |
| Name | DASNY (Dormitory Authority of the State of New York) Bonds and Notes: Beginning 1957 |
| Attribution | Dormitory Authority State of New York |
| Category | Economic Development |
| Tags | bonds, bond series name, dated date, maturity |
| Created | 2014-01-24T22:11:08Z |
| Publication Date | 2016-07-22T22:07:37Z |

## Description

DASNY maintains a cumulative record of all bonds andnotes issued by DASNY. This dataset is updatedquarterly. The dataset includes details such as: BondSeries name, Dated Date, Maturity Status/AnticipatedMaturity Date, Maturity Status/Matured or Defeased Date,Bond Series Par Amount and Bond Series Par AmountOutstanding.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | bond_series_name                          | Bond Series Name                          | text          | text          |
| Yes      | time           | dated_date                                | Dated Date                                | calendar_date | calendar_date |
| No       |                | maturity_status_anticipated_maturity_date | Maturity Status/Anticipated Maturity Date | text          | text          |
| No       |                | maturity_status_matured_or_defeased_date  | Maturity Status/Matured or Defeased Date  | text          | text          |
| Yes      | numeric metric | bond_series_par_amount                    | Bond Series Par Amount                    | money         | money         |
| Yes      | numeric metric | bond_series_par_amount_outstanding        | Bond Series Par Amount Outstanding        | money         | money         |
```

## Time Field

```ls
Value = dated_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = maturity_status_anticipated_maturity_date,maturity_status_matured_or_defeased_date
```

## Data Commands

```ls
series e:iyue-ijfp d:1987-12-02T00:00:00.000Z t:bond_series_name="1987 Pooled Short-Term Revenue Obligations" m:bond_series_par_amount_outstanding=0 m:bond_series_par_amount=100000000

series e:iyue-ijfp d:1990-02-01T00:00:00.000Z t:bond_series_name="1989 Pooled Equipment Commercial Paper" m:bond_series_par_amount_outstanding=0 m:bond_series_par_amount=40000000

series e:iyue-ijfp d:1998-12-01T00:00:00.000Z t:bond_series_name="4201 Schools Program Series 1998 (Lexington School for the Deaf, Series 1998)" m:bond_series_par_amount_outstanding=0 m:bond_series_par_amount=9525000
```

## Meta Commands

```ls
metric m:bond_series_par_amount p:integer l:"Bond Series Par Amount" d:"Amount of the bonds issued for that particular series of bonds." t:dataTypeName=money

metric m:bond_series_par_amount_outstanding p:integer l:"Bond Series Par Amount Outstanding" d:"Amount outstanding for that particular bond series." t:dataTypeName=money

entity e:iyue-ijfp l:"DASNY (Dormitory Authority of the State of New York) Bonds and Notes: Beginning 1957" t:attribution="Dormitory Authority State of New York" t:url=https://data.ny.gov/api/views/iyue-ijfp

property e:iyue-ijfp t:meta.view v:id=iyue-ijfp v:category="Economic Development" v:attributionLink=http://www.dasny.org/finance/outstand/index.php v:averageRating=0 v:name="DASNY (Dormitory Authority of the State of New York) Bonds and Notes: Beginning 1957" v:attribution="Dormitory Authority State of New York"

property e:iyue-ijfp t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:iyue-ijfp t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:iyue-ijfp t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| bond_series_name                                                                             | dated_date          | maturity_status_anticipated_maturity_date | maturity_status_matured_or_defeased_date | bond_series_par_amount | bond_series_par_amount_outstanding | 
| ============================================================================================ | =================== | ========================================= | ======================================== | ====================== | ================================== | 
| 1987 Pooled Short-Term Revenue Obligations                                                   | 1987-12-02T00:00:00 | MATURED                                   | 3/31/1999                                | 100000000              | 0                                  | 
| 1989 Pooled Equipment Commercial Paper                                                       | 1990-02-01T00:00:00 | MATURED                                   | 6/30/2000                                | 40000000               | 0                                  | 
| 4201 Schools Program Series 1998 (Lexington School for the Deaf, Series 1998)                | 1998-12-01T00:00:00 | MATURED                                   | 8/29/2012                                | 9525000                | 0                                  | 
| 4201 Schools Program Series 1998 (Mill Neck Manor School for Special Education, Series 1998) | 1998-12-01T00:00:00 | MATURED                                   | 8/29/2012                                | 8875000                | 0                                  | 
| 4201 Schools Program Series 1998 (New York Institute for Special Education, Series 1998)     | 1998-12-01T00:00:00 | MATURED                                   | 8/29/2012                                | 14240000               | 0                                  | 
| 4201 Schools Program Series 1998 (New York School for the Deaf, Series 1998)                 | 1998-12-01T00:00:00 | 7/1/2018                                  | OUTSTANDING                              | 14225000               | 3205000                            | 
| 4201 Schools Program Series 1998 (Rochester School for the Deaf Revenue Bonds, Series 2000)  | 2000-11-01T00:00:00 | 7/1/2020                                  | OUTSTANDING                              | 13745000               | 5130000                            | 
| 4201 Schools Program Series 1998 (St. Francis deSales School for the Deaf, Series 1998)      | 1998-12-01T00:00:00 | MATURED                                   | 8/29/2012                                | 2525000                | 0                                  | 
| 4201 Schools Program Series 1998 (St. Joseph's School for the Deaf, Series 1998)             | 1998-12-01T00:00:00 | MATURED                                   | 8/29/2012                                | 2250000                | 0                                  | 
| 853 Schools Program (Ketchum-Grande Memorial School Revenue Bonds, Series 2014)              | 2014-12-10T00:00:00 | 7/1/1934                                  | OUTSTANDING                              | 4740000                | 4740000                            | 
```