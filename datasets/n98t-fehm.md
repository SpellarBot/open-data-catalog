# Board of Agriculture Meetings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/board-of-agriculture-meetings-9b440) |
| Metadata | [Link](https://data.oregon.gov/api/views/n98t-fehm) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/n98t-fehm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/n98t-fehm/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | n98t-fehm |
| Name | Board of Agriculture Meetings |
| Attribution | Oregon Department of Agriculture |
| Category | Natural Resources |
| Tags | agriculture, oda, board, meetings, minutes, agenda |
| Created | 2014-08-09T00:19:07Z |
| Publication Date | 2014-09-11T22:22:26Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| Yes      | time        | start       | Start       | calendar_date | calendar_date |
| No       |             | end         | End         | calendar_date | calendar_date |
| Yes      | series tag  | agenda      | Agenda      | url           | url           |
| Yes      | series tag  | minutes     | Minutes     | url           | url           |
| Yes      | series tag  | resolutions | Resolutions | text          | text          |
```

## Time Field

```ls
Value = start
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = end
```

## Data Commands

```ls
series e:n98t-fehm d:2014-06-02T00:00:00.000Z t:agenda="https://data.oregon.gov/views/peu4-h785/files/mrB-_Ts3-DU5C3lbI9okKQ5bkrbUlTgOPnKwVkraAKE?filename=Agenda%2006-2014.pdf&content_type=application/pdf%3B%20charset%3Dbinary" m:row_number.n98t-fehm=1

series e:n98t-fehm d:2013-06-04T00:00:00.000Z t:agenda="https://data.oregon.gov/views/peu4-h785/files/Ost9WcvrqxveeSn9GUmGzly03izLJvG63r_ZhalhnYo?filename=Agenda%2006-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary" t:minutes="https://data.oregon.gov/views/peu4-h785/files/4CkjJQN2wG9upAcHUGnLDG54Ds8Dj6QhKPxMRKZnOmU?filename=Minutes%2006-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary" m:row_number.n98t-fehm=2

series e:n98t-fehm d:2013-12-03T00:00:00.000Z t:agenda="https://data.oregon.gov/views/peu4-h785/files/rd5kLCBTBOSRQOTQ7LyDADqQ6K3XOs3hQBm0RvjO0Hw?filename=Agenda%2012-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary" t:minutes="https://data.oregon.gov/views/peu4-h785/files/oTToLR5A-mPCd06NPerjys0WWBRFVYO-EyaW8-C9DmQ?filename=Minutes%2012-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary" m:row_number.n98t-fehm=3
```

## Meta Commands

```ls
metric m:row_number.n98t-fehm p:long l:"Row Number"

entity e:n98t-fehm l:"Board of Agriculture Meetings" t:attribution="Oregon Department of Agriculture" t:url=https://data.oregon.gov/api/views/n98t-fehm

property e:n98t-fehm t:meta.view v:id=n98t-fehm v:category="Natural Resources" v:attributionLink=http://oregon.gov/ODA v:averageRating=0 v:name="Board of Agriculture Meetings" v:attribution="Oregon Department of Agriculture"

property e:n98t-fehm t:meta.view.owner v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"

property e:n98t-fehm t:meta.view.tableauthor v:id=hfyt-zc65 v:screenName="Katherine Leamaster" v:displayName="Katherine Leamaster"
```

## Top Records

```ls
| start               | end                 | agenda                                                                                                                                                                                           | minutes                                                                                                                                                                                            | resolutions                                                            | 
| =================== | =================== | ================================================================================================================================================================================================ | ================================================================================================================================================================================================== | ====================================================================== | 
| 2014-06-02T00:00:00 | 2014-06-05T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/mrB-_Ts3-DU5C3lbI9okKQ5bkrbUlTgOPnKwVkraAKE?filename=Agenda%2006-2014.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 06-2014.pdf] | [null, null]                                                                                                                                                                                       |                                                                        | 
| 2013-06-04T00:00:00 | 2013-06-06T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/Ost9WcvrqxveeSn9GUmGzly03izLJvG63r_ZhalhnYo?filename=Agenda%2006-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 06-2013.pdf] | [https://data.oregon.gov/views/peu4-h785/files/4CkjJQN2wG9upAcHUGnLDG54Ds8Dj6QhKPxMRKZnOmU?filename=Minutes%2006-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Minutes 06-2013.pdf] |                                                                        | 
| 2013-12-03T00:00:00 | 2013-12-05T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/rd5kLCBTBOSRQOTQ7LyDADqQ6K3XOs3hQBm0RvjO0Hw?filename=Agenda%2012-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 12-2013.pdf] | [https://data.oregon.gov/views/peu4-h785/files/oTToLR5A-mPCd06NPerjys0WWBRFVYO-EyaW8-C9DmQ?filename=Minutes%2012-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Minutes 12-2013.pdf] |                                                                        | 
| 2014-02-18T00:00:00 | 2014-02-20T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/rs2JwLPl_vfgcKjrEAJr8Fs7qQAViYweulu85xWJsSU?filename=Agenda%2002-2014.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 02-2014.pdf] | [https://data.oregon.gov/views/peu4-h785/files/INhof2VGlN9QFN9RbAc22vq1WNvHkfCzH9vlbmGhgrE?filename=Minutes%2002-2014.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Minutes 02-2014.pdf] |                                                                        | 
| 2013-03-05T00:00:00 | 2013-03-07T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/TsDtFwqTMLXo1xcIKwQusHMc3uxq11E3NMowgNggaZk?filename=Agenda%2003-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 03-2013.pdf] | [https://data.oregon.gov/views/peu4-h785/files/28k3OdaPoQUulHUnHM1Nxv39ItGF8ABoahMkJEKWMvU?filename=Minutes%2003-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Minutes 03-2013.pdf] | Agricultural Water Quality Management Program Strategic Implementation | 
| 2013-09-17T00:00:00 | 2013-09-19T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/kSSsNBSJ5G17Rb9UNzDIuT-0XnsR7N7uNB7eb_YLBxs?filename=Agenda%2009-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 09-2013.pdf] | [https://data.oregon.gov/views/peu4-h785/files/3zrDYzpTFETnptEkBIRrvzp4C77vCM7nyTxxO9gINAs?filename=Minutes%2009-2013.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Minutes 09-2013.pdf] |                                                                        | 
| 2014-09-23T00:00:00 | 2014-09-25T00:00:00 | [https://data.oregon.gov/views/peu4-h785/files/K7qGSn7bRwe8j3miimomfXm9uH1xSNUu4HqJ_gwzH_8?filename=Agenda%2009-2014.pdf&content_type=application/pdf%3B%20charset%3Dbinary, Agenda 09-2014.pdf] | [null, null]                                                                                                                                                                                       |                                                                        | 
```