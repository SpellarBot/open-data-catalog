# Public Art Inventory

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/public-art-inventory-d9c20) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/5xsg-uc29) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/5xsg-uc29/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/5xsg-uc29/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 5xsg-uc29 |
| Name | Public Art Inventory |
| Attribution | Baltimore Office of Promotion & The Arts |
| Category | Culture & Arts |
| Tags | art, history |
| Created | 2012-05-02T19:38:37Z |
| Publication Date | 2014-04-03T23:42:34Z |

## Description

Public Art Installations in the City of Baltimore

## Columns

```ls
| Included | Schema Type | Field Name              | Name                    | Data Type | Render Type |
| ======== | =========== | ======================= | ======================= | ========= | =========== |
| No       | time        | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag  | artistlastname          | artistLastName          | text      | text        |
| Yes      | series tag  | artistfirstname         | artistFirstName         | text      | text        |
| Yes      | series tag  | image                   | image                   | document  | document    |
| Yes      | series tag  | titleofartwork          | titleOfArtwork          | text      | text        |
| Yes      | series tag  | dateofartwork           | dateOfArtwork           | text      | text        |
| Yes      | series tag  | medium                  | medium                  | text      | text        |
| Yes      | series tag  | zipcodes                | zipcodes                | text      | text        |
| Yes      | series tag  | locationofartwork       | locationOfArtwork       | text      | text        |
| No       |             | addressofartwork        | addressOfArtwork        | text      | text        |
| Yes      | series tag  | publicschoolnumber      | publicSchoolNumber      | text      | text        |
| Yes      | series tag  | siteofartwork           | siteOfArtwork           | text      | text        |
| Yes      | series tag  | descriptionofartwork    | descriptionOfArtwork    | text      | text        |
| Yes      | series tag  | visibility              | visibility              | text      | text        |
| Yes      | series tag  | indooroutdooraccessible | indoorOutdoorAccessible | text      | text        |
| Yes      | series tag  | monument                | monument                | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = addressofartwork
```

## Data Commands

```ls
series e:5xsg-uc29 d:2012-05-02T12:38:38.000Z t:artistfirstname=Henry t:locationofartwork="Lafayette Courts" t:dateofartwork=1953 t:titleofartwork="Family Group" t:medium=concrete t:artistlastname=Berge m:row_number.5xsg-uc29=1

series e:5xsg-uc29 d:2012-05-02T12:38:38.000Z t:siteofartwork="Reliefs on front of building" t:artistfirstname=Antonio t:locationofartwork="St. Paul's Episcopal Church" t:dateofartwork=c.1817 t:titleofartwork="Moses and Christ Reliefs" t:medium=marble t:artistlastname=Capellano m:row_number.5xsg-uc29=2

series e:5xsg-uc29 d:2012-05-02T12:38:38.000Z t:artistfirstname=Rodney t:dateofartwork=2009 t:titleofartwork="William Donald Schaefer" t:artistlastname=Carroll m:row_number.5xsg-uc29=3
```

## Meta Commands

```ls
metric m:row_number.5xsg-uc29 p:long l:"Row Number"

entity e:5xsg-uc29 l:"Public Art Inventory" t:attribution="Baltimore Office of Promotion & The Arts" t:url=https://data.baltimorecity.gov/api/views/5xsg-uc29

property e:5xsg-uc29 t:meta.view v:id=5xsg-uc29 v:category="Culture & Arts" v:attributionLink="http://www.bop.org/index.cfm?page=artscouncil&id=21" v:averageRating=0 v:name="Public Art Inventory" v:attribution="Baltimore Office of Promotion & The Arts"

property e:5xsg-uc29 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:5xsg-uc29 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:5xsg-uc29 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | artistlastname | artistfirstname | image                    | titleofartwork                                    | dateofartwork | medium                  | zipcodes | locationofartwork                                  | addressofartwork                           | publicschoolnumber | siteofartwork                 | descriptionofartwork                                          | visibility   | indooroutdooraccessible | monument | 
| =========== | ============== | =============== | ======================== | ================================================= | ============= | ======================= | ======== | ================================================== | ========================================== | ================== | ============================= | ============================================================= | ============ | ======================= | ======== | 
| 1335962318  | Berge          | Henry           | [null, null, null, null] | Family Group                                      | 1953          | concrete                |          | Lafayette Courts                                   | Lafayette Courts                           |                    |                               |                                                               |              |                         |          | 
| 1335962318  | Capellano      | Antonio         | [null, null, null, null] | Moses and Christ Reliefs                          | c.1817        | marble                  |          | St. Paul's Episcopal Church                        | St. Paul's Episcopal Church                |                    | Reliefs on front of building  |                                                               |              |                         |          | 
| 1335962318  | Carroll        | Rodney          | [null, null, null, null] | William Donald Schaefer                           | 2009          |                         |          |                                                    |                                            |                    |                               |                                                               |              |                         |          | 
| 1335962318  | Cea            | Dominic         | [null, null, null, null] | Atlantic Blue Roller Column or Interlocking Piece | 1977          | painted steel           |          | Russell St. Median strip                           | Russell St.                                |                    | Median strip near Oriole Park |                                                               |              |                         |          | 
| 1335962318  | Christie       | Alden           | [null, null, null, null] | Baltimore Pylon                                   |               |                         |          | Baltimore Washington Expressway                    | Baltimore Washington Expressway            |                    | At city line                  |                                                               |              |                         |          | 
| 1335962318  | Hepworth       | Barbara         | [null, null, null, null] | Single Form                                       |               |                         |          | Blaustein Building Lobby                           | Blaustein Building Lobby                   |                    |                               |                                                               |              |                         |          | 
| 1335962318  | Hosler         | Danamarie       | [null, null, null, null] |                                                   | 2007          | mural                   |          | Health Department                                  |                                            |                    |                               |                                                               |              |                         |          | 
| 1335962318  | Kirby          | Michael         | [null, null, null, null] | Three Baltimores                                  | 2005          | mural (non-city funded) |          | Key Highway under I95                              | Key Highway under I95                      |                    | Key Highway under I95         | Three aspects of Baltimore: ships, railroad, workers (steel?) | Very visible |                         |          | 
| 1335962318  | Lipschitz      | Jacques         | [null, null, null, null] | Mother and Child                                  | 1930          | bronze                  |          | Auctioned in 1993/ private Jewish Community Center | Auctioned in 1993/ Jewish Community Center |                    | Auctioned in 1993 Private?    |                                                               |              |                         |          | 
| 1335962318  | Moring         | Greg            | [null, null, null, null] | Series of Points on a Line                        |               |                         |          | City Hospitals                                     | City Hospitals                             |                    |                               |                                                               |              |                         |          | 
```