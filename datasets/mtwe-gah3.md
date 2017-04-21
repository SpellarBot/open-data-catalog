# Life Insurance In Force in the State of New York: Beginning 1996

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/life-insurance-in-force-in-the-state-of-new-york-beginning-1996) |
| Metadata | [Link](https://data.ny.gov/api/views/mtwe-gah3) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/mtwe-gah3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/mtwe-gah3/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | mtwe-gah3 |
| Name | Life Insurance In Force in the State of New York: Beginning 1996 |
| Attribution | New York State Department of Financial Services |
| Category | Economic Development |
| Tags | life insurance, policy, in force |
| Created | 2013-02-27T18:39:11Z |
| Publication Date | 2016-02-22T23:01:00Z |

## Description

Life insurance in force is the total value of life insurance policies that a company has issued.  It is normally the sum of face amounts plus dividends outstanding that a company would have to pay out at the death of an individual.  The amounts given here are for policyholders who reside in New York.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                                           | Data Type | Render Type |
| ======== | ============== | ================== | ============================================== | ========= | =========== |
| Yes      | time           | year               | Year                                           | number    | number      |
| Yes      | numeric metric | insurance_in_force | Insurance In Force (dollar amount in billions) | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mtwe-gah3 d:2013-01-01T00:00:00.000Z m:insurance_in_force=2012.7

series e:mtwe-gah3 d:2012-01-01T00:00:00.000Z m:insurance_in_force=1923

series e:mtwe-gah3 d:2011-01-01T00:00:00.000Z m:insurance_in_force=1934.7
```

## Meta Commands

```ls
metric m:insurance_in_force p:double l:"Insurance In Force (dollar amount in billions)" t:dataTypeName=money

entity e:mtwe-gah3 l:"Life Insurance In Force in the State of New York: Beginning 1996" t:attribution="New York State Department of Financial Services" t:url=https://data.ny.gov/api/views/mtwe-gah3

property e:mtwe-gah3 t:meta.view v:id=mtwe-gah3 v:category="Economic Development" v:attributionLink=http://www.dfs.ny.gov/reportpub/dfs_reportpub.htm v:averageRating=0 v:name="Life Insurance In Force in the State of New York: Beginning 1996" v:attribution="New York State Department of Financial Services"

property e:mtwe-gah3 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:mtwe-gah3 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:mtwe-gah3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | insurance_in_force | 
| ==== | ================== | 
| 2013 | 2012.7             | 
| 2012 | 1923.0             | 
| 2011 | 1934.7             | 
| 2010 | 1828.8             | 
| 2009 | 1813.1             | 
| 2008 | 1727.5             | 
| 2007 | 1690.7             | 
| 2006 | 1767.8             | 
| 2005 | 1662.9             | 
| 2004 | 1514.3             | 
```