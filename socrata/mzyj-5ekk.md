# Inspector General - Public Statements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/inspector-general-public-statements) |
| Metadata | [Link](https://datacatalog.cookcountyil.gov/api/views/mzyj-5ekk) |
| Data: JSON | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mzyj-5ekk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://datacatalog.cookcountyil.gov/api/views/mzyj-5ekk/rows.csv?max_rows=100) |
| Host | datacatalog.cookcountyil.gov |
| Id | mzyj-5ekk |
| Name | Inspector General - Public Statements |
| Attribution | Cook County Office of the Independent Inspector General |
| Category | Finance & Administration |
| Tags | oiig |
| Created | 2016-05-18T20:46:09Z |
| Publication Date | 2016-12-28T18:53:19Z |

## Description

The Independent Inspector General is authorized to issue public statements in two circumstances: When an investigation that exonerates an individual who is publicly known to have been under investigation, where the subject requests such a statement; and when an investigation concerns inefficient or wasteful management, as opposed to individual misconduct or illegality.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | series tag  | link        | Link        | url           | url           |
| Yes      | time        | date_issued | Date Issued | calendar_date | calendar_date |
| Yes      | series tag  | case_number | Case Number | text          | text          |
```

## Time Field

```ls
Value = date_issued
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:mzyj-5ekk d:2016-03-24T00:00:00.000Z t:case_number=IIG15-0364 t:link=http://opendocs.cookcountyil.gov/inspector-general/public-statements/Open-Meetings-Act-Compliance-Management-March-24-2016-IIG15-0364.pdf m:row_number.mzyj-5ekk=1

series e:mzyj-5ekk d:2015-12-15T00:00:00.000Z t:case_number=IIG14-0438 t:link=http://opendocs.cookcountyil.gov/inspector-general/public-statements/Campaign-Contributions-Bond-Vendors-December-15-2015-IIG14-0438.pdf m:row_number.mzyj-5ekk=2

series e:mzyj-5ekk d:2015-12-09T00:00:00.000Z t:case_number=N/A t:link=http://opendocs.cookcountyil.gov/inspector-general/public-statements/Media-Advisory-December-9-2015.pdf m:row_number.mzyj-5ekk=3
```

## Meta Commands

```ls
metric m:row_number.mzyj-5ekk p:long l:"Row Number"

entity e:mzyj-5ekk l:"Inspector General - Public Statements" t:attribution="Cook County Office of the Independent Inspector General" t:url=https://datacatalog.cookcountyil.gov/api/views/mzyj-5ekk

property e:mzyj-5ekk t:meta.view v:id=mzyj-5ekk v:category="Finance & Administration" v:averageRating=0 v:name="Inspector General - Public Statements" v:attribution="Cook County Office of the Independent Inspector General"

property e:mzyj-5ekk t:meta.view.license v:name="Public Domain"

property e:mzyj-5ekk t:meta.view.owner v:id=u38g-hbsa v:screenName="Cook County Open Data" v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"

property e:mzyj-5ekk t:meta.view.tableauthor v:id=u38g-hbsa v:screenName="Cook County Open Data" v:roleName=administrator v:lastNotificationSeenAt=1492536815 v:displayName="Cook County Open Data"
```

## Top Records

```ls
| link                                                                                                                                                                                     | date_issued         | case_number | 
| ======================================================================================================================================================================================== | =================== | =========== | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Open-Meetings-Act-Compliance-Management-March-24-2016-IIG15-0364.pdf, Open Meetings Act Compliance Management]     | 2016-03-24T00:00:00 | IIG15-0364  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Campaign-Contributions-Bond-Vendors-December-15-2015-IIG14-0438.pdf, Campaign Contributions - Bond Vendors]        | 2015-12-15T00:00:00 | IIG14-0438  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Media-Advisory-December-9-2015.pdf, Media Advisory]                                                                | 2015-12-09T00:00:00 | N/A         | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/IIG15-0027-Operational-Review-of-Animal-Control.pdf, Operational Review of Animal Control]                         | 2015-08-21T00:00:00 | IIG15-0027  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Board-of-Review-Ethics-Compliance-Review-March-24-2015-IIG13-0053.pdf, Board of Review - Ethics Compliance Review] | 2015-03-24T00:00:00 | IIG13-0053  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/FLSA-and-Supplemental-Policy-Survey-February-2-2015-IIG14-0266.pdf, FLSA and Supplemental Policy Survey]           | 2015-02-02T00:00:00 | IIG14-0266  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Employee-Appeals-Board-December-18-2014-IIG14-0461.pdf, Employee Appeals Board]                                    | 2014-12-18T00:00:00 | IIG14-0461  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Media-Advisory-August-25-20141.pdf, Media Advisory]                                                                | 2014-08-25T00:00:00 | N/A         | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/Lobbyist-Compliance-Review-May-19-2014-IIG13-0404.pdf, Lobbyist Compliance Review]                                 | 2014-05-19T00:00:00 | IIG13-0404  | 
| [http://opendocs.cookcountyil.gov/inspector-general/public-statements/FPD-Site-Inspections-February-14-2014-IIG13-0061.pdf, Forest Preserve District Site Inspections]                   | 2014-02-14T00:00:00 | IIG13-0061  | 
```