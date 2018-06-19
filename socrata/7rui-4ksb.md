# Broadband Speed Test

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/broadband-speed-test-55d72) |
| Metadata | [Link](https://data.seattle.gov/api/views/7rui-4ksb) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/7rui-4ksb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/7rui-4ksb/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | 7rui-4ksb |
| Name | Broadband Speed Test |
| Attribution | City of Seattle |
| Category | City Business |
| Tags | broadband speed test |
| Created | 2016-10-13T21:41:52Z |
| Publication Date | 2016-10-17T15:36:08Z |

## Description

Broadband Speed Test

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| No       |                | id                  | id                  | text      | number      |
| Yes      | numeric metric | actual_download     | actual_download     | number    | number      |
| Yes      | numeric metric | actual_upload       | actual_upload       | number    | number      |
| Yes      | numeric metric | advertised_download | advertised_download | number    | text        |
| Yes      | numeric metric | advertised_upload   | advertised_upload   | number    | text        |
| Yes      | series tag     | connection_type     | connection_type     | text      | text        |
| Yes      | series tag     | cost_of_service     | cost_of_service     | text      | text        |
| No       |                | date_pretty         | date_pretty         | text      | text        |
| Yes      | series tag     | isp                 | isp                 | text      | text        |
| Yes      | series tag     | isp_user            | isp_user            | text      | text        |
| Yes      | numeric metric | min_rtt             | min_rtt             | number    | number      |
| Yes      | numeric metric | timestamp           | timestamp           | number    | number      |
| Yes      | numeric metric | seattle_blkgrpce10  | seattle_blkgrpce10  | number    | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = id,date_pretty
```

## Data Commands

```ls
series e:7rui-4ksb d:2017-03-30T18:21:11.000Z t:cost_of_service=75_100 t:isp_user=comcast t:isp=comcast t:connection_type=wired m:actual_download=0.88 m:timestamp=1455314109 m:actual_upload=11.07 m:min_rtt=52

series e:7rui-4ksb d:2017-03-30T18:21:11.000Z t:cost_of_service=75_100 t:isp_user=centurylink t:isp=centurylink t:connection_type=wireless-multiple m:advertised_upload=100 m:actual_download=0.22 m:timestamp=1479412352 m:actual_upload=43.6 m:advertised_download=50 m:min_rtt=3

series e:7rui-4ksb d:2017-03-30T18:21:11.000Z t:cost_of_service=50_75 t:isp_user=centurylink t:isp=centurylink t:connection_type=wireless-multiple m:actual_download=2.87 m:timestamp=1467551860 m:seattle_blkgrpce10=530330095001 m:actual_upload=5.07 m:min_rtt=5
```

## Meta Commands

```ls
metric m:actual_download p:float l:actual_download t:dataTypeName=number

metric m:actual_upload p:float l:actual_upload t:dataTypeName=number

metric m:advertised_download p:integer l:advertised_download t:dataTypeName=number

metric m:advertised_upload p:integer l:advertised_upload t:dataTypeName=number

metric m:min_rtt p:integer l:min_rtt t:dataTypeName=number

metric m:timestamp p:integer l:timestamp t:dataTypeName=number

metric m:seattle_blkgrpce10 p:long l:seattle_blkgrpce10 t:dataTypeName=number

entity e:7rui-4ksb l:"Broadband Speed Test" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/7rui-4ksb

property e:7rui-4ksb t:meta.view v:id=7rui-4ksb v:category="City Business" v:attributionLink=http://www.seattle.gov v:averageRating=0 v:name="Broadband Speed Test" v:attribution="City of Seattle"

property e:7rui-4ksb t:meta.view.license v:name="Public Domain"

property e:7rui-4ksb t:meta.view.owner v:id=58et-jnvx v:screenName="Butler, Mark" v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"

property e:7rui-4ksb t:meta.view.tableauthor v:id=58et-jnvx v:screenName="Butler, Mark" v:roleName=administrator v:lastNotificationSeenAt=1491575928 v:displayName="Butler, Mark"
```

## Top Records

```ls
| :updated_at | id   | actual_download | actual_upload | advertised_download | advertised_upload | connection_type   | cost_of_service | date_pretty                   | isp                          | isp_user        | min_rtt | timestamp  | seattle_blkgrpce10 | 
| =========== | ==== | =============== | ============= | =================== | ================= | ================= | =============== | ============================= | ============================ | =============== | ======= | ========== | ================== | 
| 1490898071  | 428  | 0.88            | 11.07         |                     |                   | wired             | 75_100          | Fri, 12 Feb 2016 21:55:09 GMT | comcast                      | comcast         | 52      | 1455314109 |                    | 
| 1490898071  | 2771 | 0.22            | 43.6          | 50                  | 100               | wireless-multiple | 75_100          | Thu, 17 Nov 2016 19:52:32 GMT | centurylink                  | centurylink     | 3       | 1479412352 |                    | 
| 1490898071  | 2297 | 2.87            | 5.07          |                     |                   | wireless-multiple | 50_75           | Sun, 03 Jul 2016 13:17:40 GMT | centurylink                  | centurylink     | 5       | 1467551860 | 530330095001       | 
| 1490898071  | 2196 | 23.81           | 5.91          |                     |                   | wireless-multiple | 50_75           | Sat, 28 May 2016 18:04:51 GMT | comcast                      | comcast         | 13      | 1464458691 |                    | 
| 1490898071  | 569  | 1.29            | 0.1           | 4                   | 1                 | wired             | 25_50           | Sat, 13 Feb 2016 07:35:51 GMT | AS18566 MegaPath Corporation | Global Capacity | 39      | 1455348951 |                    | 
| 1490898071  | 1964 | 12.98           | 10.9          |                     |                   | wireless-multiple | 100_or_above    | Thu, 07 Apr 2016 23:16:21 GMT | comcast                      | comcast         | 12      | 1460070981 | 530330075003       | 
| 1490898071  | 1255 | 67.13           | 72.83         | 1000                | 1000              | wired             | 100_or_above    | Tue, 16 Feb 2016 19:45:38 GMT | centurylink                  | centurylink     | 52      | 1455651938 |                    | 
| 1490898071  | 2511 | 13.99           | 3.5           |                     |                   | wireless-multiple | dont_know       | Tue, 23 Aug 2016 07:49:58 GMT | comcast                      | comcast         | 42      | 1471938598 |                    | 
| 1490898071  | 854  | 52.92           | 23.48         |                     |                   | wireless-multiple | 100_or_above    | Sun, 14 Feb 2016 08:52:17 GMT | comcast                      | comcast         | 6       | 1455439937 | 530330079004       | 
| 1490898071  | 2172 | 30.39           | 165.67        | 1000                | 1000              | wired             | 75_100          | Mon, 23 May 2016 09:18:36 GMT | AS4474 TCT West, Inc.        | tct             | 9       | 1463995116 |                    | 
```