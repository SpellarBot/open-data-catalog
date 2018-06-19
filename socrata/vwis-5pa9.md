# ARTS ORGANIZATIONS

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/arts-organizations-29778) |
| Metadata | [Link](https://data.seattle.gov/api/views/vwis-5pa9) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/vwis-5pa9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/vwis-5pa9/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | vwis-5pa9 |
| Name | ARTS ORGANIZATIONS |
| Attribution | Department of Information Technology |
| Category | Community |
| Tags | arts, organizations, seattle, art, community |
| Created | 2011-04-20T21:20:25Z |
| Publication Date | 2014-07-01T16:36:23Z |

## Description

Arts organizations in Seattle To add an organization please use the form at http://data.seattle.gov/Community/Add-new-Arts-Organization/dhvi-6ck6

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | NAME       | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | url         | URL        | url       | url         |
| No       |             | latitude    | LATITUDE   | number    | number      |
| No       |             | longitude   | LONGITUDE  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,latitude,longitude
```

## Data Commands

```ls
series e:vwis-5pa9 d:2011-04-20T14:20:26.000Z t:name="911 MEDIA ARTS CENTER" t:url=http://www.911media.org/news m:row_number.vwis-5pa9=1

series e:vwis-5pa9 d:2011-04-20T14:20:26.000Z t:name="ARTIST TRUST" t:url=http://artisttrust.org/index.php m:row_number.vwis-5pa9=2

series e:vwis-5pa9 d:2011-04-20T14:20:26.000Z t:name="ARTS CORPS" t:url=http://www.artscorps.org/the-corps/ m:row_number.vwis-5pa9=3
```

## Meta Commands

```ls
metric m:row_number.vwis-5pa9 p:long l:"Row Number"

entity e:vwis-5pa9 l:"ARTS ORGANIZATIONS" t:attribution="Department of Information Technology" t:url=https://data.seattle.gov/api/views/vwis-5pa9

property e:vwis-5pa9 t:meta.view v:id=vwis-5pa9 v:category=Community v:averageRating=0 v:name="ARTS ORGANIZATIONS" v:attribution="Department of Information Technology"

property e:vwis-5pa9 t:meta.view.license v:name="Public Domain"

property e:vwis-5pa9 t:meta.view.owner v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:displayName="Seattle IT"

property e:vwis-5pa9 t:meta.view.tableauthor v:id=pfbu-yuv5 v:profileImageUrlMedium=/api/users/pfbu-yuv5/profile_images/THUMB v:profileImageUrlLarge=/api/users/pfbu-yuv5/profile_images/LARGE v:screenName="Seattle IT" v:profileImageUrlSmall=/api/users/pfbu-yuv5/profile_images/TINY v:roleName=administrator v:displayName="Seattle IT"
```

## Top Records

```ls
| :updated_at | name                        | address                | url                                         | latitude           | longitude           | 
| =========== | =========================== | ====================== | =========================================== | ================== | =================== | 
| 1303309226  | 911 MEDIA ARTS CENTER       | 909 NE 43rd Street     | [http://www.911media.org/news, null]        | 47.659518017700002 | -122.34715306       | 
| 1303309226  | ARTIST TRUST                | 1835 12th Ave          | [http://artisttrust.org/index.php, null]    | 47.618030687599997 | -122.316975141      | 
| 1303309226  | ARTS CORPS                  | 4408 Delridge Way SW   | [http://www.artscorps.org/the-corps/, null] | 47.564548707999997 | -122.36326593699999 | 
| 1303309226  | ARTSFUND                    | 10 Harrison Street     | [http://www.artsfund.org/, null]            | 47.622171645599998 | -122.35661100900001 | 
| 1303309226  | CORNISH COLLEGE OF THE ARTS | 1000 Lenora Street     | [http://www.cornish.edu/, null]             | 47.6178737738      | -122.336231911      | 
| 1303309226  | EARLY MUSIC GUILD           | 2366 Eastlake Ave E    | [http://www.earlymusicguild.org/, null]     | 47.640512635599997 | -122.325815338      | 
| 1303309226  | FREEHOLD THEATRE            | 2222 Second Avenue     | [http://www.freeholdtheatre.org/, null]     | 47.638963222299999 | -122.35315793300001 | 
| 1303309226  | FREMONT ABBEY ARTS CENTER   | 4272 Fremont Ave North | [http://www.fremontabbey.org/, null]        | 47.659026063900001 | -122.349952891      | 
| 1303309226  | NORTHWEST FINE WOODWORKING  | 101 South Jackson St   | [http://www.nwfinewoodworking.com/, null]   | 47.599153802499998 | -122.33411627       | 
| 1303309226  | PRATT FINE ARTS CENTER      | 1902 South Main St     | [http://www.pratt.org/, null]               | 47.6000274847      | -122.30765388099999 | 
```