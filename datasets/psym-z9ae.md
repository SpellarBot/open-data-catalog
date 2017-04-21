# Police Officer Memorial Honor Roll: Beginning 1791

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/police-officer-memorial-honor-roll-beginning-1791) |
| Metadata | [Link](https://data.ny.gov/api/views/psym-z9ae) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/psym-z9ae/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/psym-z9ae/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | psym-z9ae |
| Name | Police Officer Memorial Honor Roll: Beginning 1791 |
| Attribution | New York State Division of Criminal Justice Services |
| Category | Public Safety |
| Tags | public safety, roll of honor, memorial |
| Created | 2014-04-03T17:55:43Z |
| Publication Date | 2016-05-02T22:08:44Z |

## Description

A listing of the police officers from around New York State who died while in the performance of their duties.  The Office of Public Safety (OPS) of the NYS Division of Criminal Justice Services (DCJS) facilitates and provides support services for all activities surrounding the New York State Police Officers Memorial.  A Remembrance Ceremony is held at the Memorial each year during the month of May.

## Columns

```ls
| Included | Schema Type    | Field Name | Name    | Data Type | Render Type |
| ======== | ============== | ========== | ======= | ========= | =========== |
| Yes      | series tag     | name       | Name    | text      | text        |
| Yes      | series tag     | rank       | Rank    | text      | text        |
| Yes      | series tag     | agency     | Agency  | text      | text        |
| No       |                | month      | Month   | number    | number      |
| Yes      | numeric metric | day        | Day     | number    | number      |
| No       |                | year       | Year    | number    | number      |
| Yes      | series tag     | panel      | Panel   | text      | text        |
| Yes      | series tag     | section    | Section | text      | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:psym-z9ae d:1981-12-01T00:00:00.000Z t:panel=D t:rank="Police Officer" t:name="Anthony  Abruzzo, Jr." t:agency="New York City Police Department" t:section=Bottom m:day=16

series e:psym-z9ae d:1956-10-01T00:00:00.000Z t:panel=C t:rank="Police Officer" t:name="Charles  Ackerly" t:agency="Scarsdale Police Department" t:section=Top m:day=4

series e:psym-z9ae d:1951-09-01T00:00:00.000Z t:panel=C t:rank=Sergeant t:name="Harry  Adams" t:agency="New York State Police" t:section=Bottom m:day=1
```

## Meta Commands

```ls
metric m:day p:integer l:Day d:"Day of officer?s death." t:dataTypeName=number

entity e:psym-z9ae l:"Police Officer Memorial Honor Roll:  Beginning 1791" t:attribution="New York State Division of Criminal Justice Services" t:url=https://data.ny.gov/api/views/psym-z9ae

property e:psym-z9ae t:meta.view v:id=psym-z9ae v:category="Public Safety" v:attributionLink=http://www.criminaljustice.ny.gov/ops/docs/pomc/honorroll.pdf v:averageRating=0 v:name="Police Officer Memorial Honor Roll:  Beginning 1791" v:attribution="New York State Division of Criminal Justice Services"

property e:psym-z9ae t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:psym-z9ae t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:psym-z9ae t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| name                 | rank           | agency                              | month | day | year | panel | section | 
| ==================== | ============== | =================================== | ===== | === | ==== | ===== | ======= | 
| Anthony Abruzzo, Jr. | Police Officer | New York City Police Department     | 12    | 16  | 1981 | D     | Bottom  | 
| Charles Ackerly      | Police Officer | Scarsdale Police Department         | 10    | 4   | 1956 | C     | Top     | 
| Harry Adams          | Sergeant       | New York State Police               | 9     | 1   | 1951 | C     | Bottom  | 
| Joseph F. Adamy      | Lieutenant     | Amherst Police Department           | 1     | 27  | 1990 | B     | Bottom  | 
| Sandra Y. Adrian     | Detective      | New York City Police Department     | 1     | 11  | 2006 | D     | Top     | 
| James J. Albanese    | Detective      | New York City Police Department     | 8     | 13  | 2014 | L     | Bottom  | 
| John Albanese        | Police Officer | New York City Police Department     | 11    | 8   | 1955 | D     | Top     | 
| Otto Albertson       | Police Officer | Poughkeepsie City Police Department | 12    | 25  | 1916 | C     | Top     | 
| Harry E. Albin       | Police Officer | Freeport Police Department          | 8     | 11  | 1929 | B     | Top     | 
| Joseph T. Alcamo     | Police Officer | New York City Police Department     | 3     | 26  | 1992 | J     | Bottom  | 
```