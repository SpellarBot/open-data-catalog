# Boundary Review Board meeting information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boundary-review-board-meeting-information-07593) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/n3km-dyia) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/n3km-dyia/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/n3km-dyia/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | n3km-dyia |
| Name | Boundary Review Board meeting information |
| Attribution | King County Boundary Review Board |
| Category | Operations |
| Tags | boundary review, annex, annexation, calendar, meetings, agendas, minutes |
| Created | 2011-05-18T00:37:10Z |
| Publication Date | 2017-04-10T23:30:20Z |

## Description

King County Boundary Review Board calendar, meeting agendas and minutes

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | time        | meeting          | Meeting          | date      | date        |
| Yes      | series tag  | download_agenda  | Download agenda  | url       | url         |
| Yes      | series tag  | download_minutes | Download Minutes | url       | url         |
| Yes      | series tag  | meeting_type     | Meeting type     | text      | text        |
| Yes      | series tag  | meeting_facility | Meeting facility | text      | text        |
| No       |             | address          | Address          | text      | text        |
| Yes      | series tag  | city             | City             | text      | text        |
| Yes      | series tag  | state            | State            | text      | text        |
| Yes      | series tag  | zip              | Zip              | text      | text        |
```

## Time Field

```ls
Value = meeting
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:n3km-dyia d:2014-05-09T02:00:00.000Z t:meeting_facility="Bellevue Fire Station #9" t:zip=98006 t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140508regular.ashx t:state=WA t:meeting_type="Regular meeting" t:city=Bellevue t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140508regular.ashx m:row_number.n3km-dyia=1

series e:n3km-dyia d:2014-04-11T02:00:00.000Z t:meeting_facility="Bellevue Fire Station #9" t:zip=98006 t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140410regular.ashx t:state=WA t:meeting_type="Regular meeting" t:city=Bellevue t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140410regular.ashx m:row_number.n3km-dyia=2

series e:n3km-dyia d:2014-03-14T02:00:00.000Z t:meeting_facility="Bellevue Fire Station #9" t:zip=98006 t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140313regular.ashx t:state=WA t:meeting_type="Regular meeting" t:city=Bellevue t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140313regular.ashx m:row_number.n3km-dyia=3
```

## Meta Commands

```ls
metric m:row_number.n3km-dyia p:long l:"Row Number"

entity e:n3km-dyia l:"Boundary Review Board meeting information" t:attribution="King County Boundary Review Board" t:url=https://data.kingcounty.gov/api/views/n3km-dyia

property e:n3km-dyia t:meta.view v:id=n3km-dyia v:category=Operations v:attributionLink=http://www.kingcounty.gov/property/annexations/ v:averageRating=0 v:name="Boundary Review Board meeting information" v:attribution="King County Boundary Review Board"

property e:n3km-dyia t:meta.view.license v:name="Public Domain"

property e:n3km-dyia t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:n3km-dyia t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| meeting    | download_agenda                                                                                                                             | download_minutes                                                                                                                              | meeting_type    | meeting_facility         | address                | city     | state | zip   | 
| ========== | =========================================================================================================================================== | ============================================================================================================================================= | =============== | ======================== | ====================== | ======== | ===== | ===== | 
| 1399600800 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140508regular.ashx, Agenda (133KB PDF)] | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140508regular.ashx, Minutes (255KB PDF)] | Regular meeting | Bellevue Fire Station #9 | 12412 SE Newcastle Way | Bellevue | WA    | 98006 | 
| 1397181600 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140410regular.ashx, Agenda (173KB PDF)] | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140410regular.ashx, Minutes (122KB PDF)] | Regular meeting | Bellevue Fire Station #9 | 12412 SE Newcastle Way | Bellevue | WA    | 98006 | 
| 1394762400 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140313regular.ashx, Agenda (179KB PDF)] | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140313regular.ashx, Minutes (143KB PDF)] | Regular meeting | Bellevue Fire Station #9 | 12412 SE Newcastle Way | Bellevue | WA    | 98006 | 
| 1392346800 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/agenda20140213regular.ashx, Agenda (180KB PDF)] | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140213regular.ashx, Minutes (201KB PDF)] | Regular meeting | Bellevue Fire Station #9 | 12412 SE Newcastle Way | Bellevue | WA    | 98006 | 
| 1389322800 | [http://www.kingcounty.gov/~/media/property/annexations/News/2014/agenda20140109regular.ashx, Agenda (106KB PDF)]                           | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2014/minutes20140109regular.ashx, Minutes (301KB PDF)] | Regular meeting | Bellevue Fire Station #9 | 12412 SE Newcastle Way | Bellevue | WA    | 98006 | 
| 1386903600 | [http://www.kingcounty.gov/property/annexations/News/AgendasMinutes.aspx, Agenda not yet available]                                         | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/minutes20131212regular.ashx, Minutes (115KB PDF)]                           | Regular meeting | TBA                      |                        | Kirkland | WA    |       | 
| 1384484400 | [null, null]                                                                                                                                | [null, null]                                                                                                                                  | Regular meeting | Bellevue Fire Station #9 | 12412 SE 69th Way      | Bellevue | WA    | 98006 | 
| 1381456800 | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/agenda20131010regular.ashx, Agenda (112KB PDF)]                           | [null, null]                                                                                                                                  | Regular meeting | Bellevue Fire Station #9 | 12412 SE 69th Way      | Bellevue | WA    | 98006 | 
| 1379642400 | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/agenda20130918special.ashx, Agenda (663KB PDF)]                           | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/minutes20130919special.ashx, Minutes (148KB PDF)]                           | Special meeting | Issaquah Holiday Inn     | 1801 12th Ave NW       | Issaquah | WA    | 98027 | 
| 1379556000 | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/agenda20130918special.ashx, Agenda (663KB PDF)]                           | [http://www.kingcounty.gov/~/media/property/annexations/News/2013/minutes20130918special.ashx, Minutes (224KB PDF)]                           | Special meeting | Issaquah Holiday Inn     | 1801 12th Ave NW       | Issaquah | WA    | 98027 | 
```