# 2014 Election - Early Voting Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2014-election-early-voting-centers-5bd8e) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/2bng-h6xm) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/2bng-h6xm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/2bng-h6xm/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 2bng-h6xm |
| Name | 2014 Election - Early Voting Centers |
| Attribution | Montgomery County, MD |
| Category | Elections |
| Tags | election, polling place, vote |
| Created | 2013-10-22T13:48:14Z |
| Publication Date | 2013-12-03T18:40:46Z |

## Description

2014 early voting locations in Montgomery County as selected October 21, 2013, subject to approval by the Maryland State Board of Elections. For more information, see www.777vote.org.

## Columns

```ls
| Included | Schema Type | Field Name    | Name              | Data Type | Render Type |
| ======== | =========== | ============= | ================= | ========= | =========== |
| Yes      | series tag  | site_number   | District-Precinct | text      | text        |
| Yes      | series tag  | building_name | Building Name     | text      | text        |
| No       |             | address       | Address           | text      | text        |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:2bng-h6xm d:2014-01-01T00:00:00.000Z t:building_name="Mid-County Community Recreation Center" t:site_number=EV-1 m:row_number.2bng-h6xm=1

series e:2bng-h6xm d:2014-01-01T00:00:00.000Z t:building_name="Executive Office Building" t:site_number=EV-2 m:row_number.2bng-h6xm=2

series e:2bng-h6xm d:2014-01-01T00:00:00.000Z t:building_name="Germantown Community Recreation Center" t:site_number=EV-3 m:row_number.2bng-h6xm=3
```

## Meta Commands

```ls
metric m:row_number.2bng-h6xm p:long l:"Row Number"

entity e:2bng-h6xm l:"2014 Election - Early Voting Centers" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/2bng-h6xm

property e:2bng-h6xm t:meta.view v:id=2bng-h6xm v:category=Elections v:averageRating=0 v:name="2014 Election - Early Voting Centers" v:attribution="Montgomery County, MD"

property e:2bng-h6xm t:meta.view.license v:name="Public Domain"

property e:2bng-h6xm t:meta.view.owner v:id=fnci-gphj v:screenName="MC Open Data" v:displayName="MC Open Data"

property e:2bng-h6xm t:meta.view.tableauthor v:id=fnci-gphj v:screenName="MC Open Data" v:roleName=administrator v:displayName="MC Open Data"
```

## Top Records

```ls
| site_number | building_name                                   | address                                          | 
| =========== | =============================================== | ================================================ | 
| EV-1        | Mid-County Community Recreation Center          | 2004 Queensguard Road Silver Spring MD 20906     | 
| EV-2        | Executive Office Building                       | 101 Monroe Street Rockville MD 20850             | 
| EV-3        | Germantown Community Recreation Center          | 18905 Kingsview Road Germantown MD 20874         | 
| EV-4        | Marilyn J. Praisner Community Recreation Center | 14906 Old Columbia Pike Burtonsville MD 20866    | 
| EV-5        | Silver Spring Civic Building                    | 1 Veterans Place Silver Spring MD 20910          | 
| EV-7        | Damascus Community Recreation Center            | 25520 Oak Drive Damascus MD 20872                | 
| EV-8        | Jane Lawton Community Recreation Center         | 4301 Willow Lane Chevy Chase MD 20815            | 
| EV-6        | Activity Center at Bohrer Park                  | 506 South Frederick Avenue Gaithersburg MD 20877 | 
| EV-9        | Wheaton Community Recreation Center             | 11711 Georgia Avenue Wheaton MD 20902            | 
```