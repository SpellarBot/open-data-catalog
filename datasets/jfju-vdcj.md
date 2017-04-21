# Boundary Review Board 2010 meeting agendas and minutes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/boundary-review-board-2010-meeting-agendas-and-minutes-41a6f) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/jfju-vdcj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/jfju-vdcj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/jfju-vdcj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | jfju-vdcj |
| Name | Boundary Review Board 2010 meeting agendas and minutes |
| Attribution | King County Boundary Review Board |
| Category | Operations |
| Tags | boundary review, annex, annexation |
| Created | 2011-05-18T00:33:08Z |
| Publication Date | 2011-05-18T00:33:08Z |

## Description

King County Boundary Review Board meeting agendas and minutes

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type     | Render Type   |
| ======== | =========== | ================ | ================ | ============= | ============= |
| Yes      | time        | meeting          | Meeting          | calendar_date | calendar_date |
| Yes      | series tag  | download_agenda  | Download agenda  | url           | url           |
| Yes      | series tag  | download_minutes | Download Minutes | url           | url           |
| Yes      | series tag  | meeting_type     | Meeting type     | text          | text          |
```

## Time Field

```ls
Value = meeting
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:jfju-vdcj d:2010-11-15T00:00:00.000Z t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20101115regular.ashx t:meeting_type="Regular meeting" t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20101115regular.ashx m:row_number.jfju-vdcj=1

series e:jfju-vdcj d:2010-10-14T00:00:00.000Z t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20101014regular.ashx t:meeting_type="Regular meeting" t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20101014regular.ashx m:row_number.jfju-vdcj=2

series e:jfju-vdcj d:2010-02-11T00:00:00.000Z t:download_agenda=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100211regular.ashx t:meeting_type="Regular meeting" t:download_minutes=http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/Minutes20100211regular.ashx m:row_number.jfju-vdcj=3
```

## Meta Commands

```ls
metric m:row_number.jfju-vdcj p:long l:"Row Number"

entity e:jfju-vdcj l:"Boundary Review Board 2010 meeting agendas and minutes" t:attribution="King County Boundary Review Board" t:url=https://data.kingcounty.gov/api/views/jfju-vdcj

property e:jfju-vdcj t:meta.view v:id=jfju-vdcj v:category=Operations v:attributionLink=http://www.kingcounty.gov/property/annexations/ v:averageRating=0 v:name="Boundary Review Board 2010 meeting agendas and minutes" v:attribution="King County Boundary Review Board"

property e:jfju-vdcj t:meta.view.license v:name="Public Domain"

property e:jfju-vdcj t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:jfju-vdcj t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| meeting             | download_agenda                                                                                                                              | download_minutes                                                                                                                               | meeting_type    | 
| =================== | ============================================================================================================================================ | ============================================================================================================================================== | =============== | 
| 2010-11-15T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20101115regular.ashx, Agenda (106KB PDF)]  | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20101115regular.ashx, Minutes (25KB PDF)]   | Regular meeting | 
| 2010-10-14T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20101014regular.ashx, Agenda (115KB PDF)]  | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20101014regular.ashx, Minutes (82KB PDF)]   | Regular meeting | 
| 2010-02-11T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100211regular.ashx, Agenda (98KB PDF)]   | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/Minutes20100211regular.ashx, Minutes (3.15MB PDF)] | Regular meeting | 
| 2010-06-07T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100607special.ashx, Agenda (2.25MB PDF)] | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20100607special.ashx, Minutes (7MB PDF)]    | Special meeting | 
| 2010-05-18T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100518special.ashx, Agenda (2.6MB PDF)]  | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20100518special.ashx, Minutes (6.46MB PDF)] | Special meeting | 
| 2010-03-22T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/Agenda20100322special.ashx, Agenda (2.2MB PDF)]  | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20100322special.ashx, Minutes (7.70MB PDF)] | Special meeting | 
| 2010-12-09T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20101209regular.ashx, Agenda (12KB PDF)]   | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20101209regular.ashx, Minutes (20KB PDF)]   | Regular meeting | 
| 2010-09-09T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100909regular.ashx, Agenda (106KB PDF)]  | [null, Minutes not yet available]                                                                                                              | Regular meeting | 
| 2010-08-12T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100812regular.ashx, Agenda (135KB PDF)]  | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20100812regular.ashx, Minutes (2.4MB PDF)]  | Regular meeting | 
| 2010-07-08T00:00:00 | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/agenda20100708regular.ashx, Agenda (98KB PDF)]   | [http://www.kingcounty.gov/property/annexations/News/~/media/property/annexations/News/2010/minutes20100708regular.ashx, Minutes (7699KB PDF)] | Regular meeting | 
```