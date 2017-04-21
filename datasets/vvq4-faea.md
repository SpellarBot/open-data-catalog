# ISP - Firearm Owners' Identification (FOID) Applications

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/isp-firearm-owners-identification-foid-applications-879e5) |
| Metadata | [Link](https://data.illinois.gov/api/views/vvq4-faea) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/vvq4-faea/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/vvq4-faea/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | vvq4-faea |
| Name | ISP - Firearm Owners' Identification (FOID) Applications |
| Attribution | Illinois State Police |
| Category | Public Safety |
| Tags | police, state police, firearms, guns |
| Created | 2012-01-31T23:03:48Z |
| Publication Date | 2012-01-31T23:10:19Z |

## Description

FOID Card Applications -- 10 Year History -- 2002 through 2011

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | time           | year                               | YEAR                               | number    | text        |
| Yes      | numeric metric | foid_applications_received_by_year | FOID APPLICATIONS RECEIVED BY YEAR | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vvq4-faea d:2002-01-01T00:00:00.000Z m:foid_applications_received_by_year=225067

series e:vvq4-faea d:2003-01-01T00:00:00.000Z m:foid_applications_received_by_year=234667

series e:vvq4-faea d:2004-01-01T00:00:00.000Z m:foid_applications_received_by_year=279511
```

## Meta Commands

```ls
metric m:foid_applications_received_by_year p:integer l:"FOID APPLICATIONS RECEIVED BY YEAR" t:dataTypeName=number

entity e:vvq4-faea l:"ISP - Firearm Owners' Identification (FOID) Applications" t:attribution="Illinois State Police" t:url=https://data.illinois.gov/api/views/vvq4-faea

property e:vvq4-faea t:meta.view v:id=vvq4-faea v:category="Public Safety" v:attributionLink=http://www.isp.state.il.us/ v:averageRating=0 v:name="ISP - Firearm Owners' Identification (FOID) Applications" v:attribution="Illinois State Police"

property e:vvq4-faea t:meta.view.owner v:id=sdcr-8kwc v:screenName="Alan Burgard" v:displayName="Alan Burgard"

property e:vvq4-faea t:meta.view.tableauthor v:id=sdcr-8kwc v:screenName="Alan Burgard" v:displayName="Alan Burgard"
```

## Top Records

```ls
| year | foid_applications_received_by_year | 
| ==== | ================================== | 
| 2002 | 225067                             | 
| 2003 | 234667                             | 
| 2004 | 279511                             | 
| 2005 | 231693                             | 
| 2006 | 225594                             | 
| 2007 | 238805                             | 
| 2008 | 278374                             | 
| 2009 | 326008                             | 
| 2010 | 287552                             | 
| 2011 | 321467                             | 
```