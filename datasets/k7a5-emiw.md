# Seattle Police Department In-Car Video Dropped Frame Report

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-police-department-in-car-video-dropped-frame-report-0b127) |
| Metadata | [Link](https://data.seattle.gov/api/views/k7a5-emiw) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/k7a5-emiw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/k7a5-emiw/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | k7a5-emiw |
| Name | Seattle Police Department In-Car Video Dropped Frame Report |
| Attribution | Seattle Police |
| Category | Public Safety |
| Created | 2014-08-21T17:08:55Z |
| Publication Date | 2014-10-02T05:46:17Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                | Data Type | Render Type |
| ======== | ============== | ================ | =================== | ========= | =========== |
| Yes      | series tag     | officer_id       | Officer ID          | text      | text        |
| Yes      | time           | file_date_time   | File Date Time      | text      | text        |
| Yes      | series tag     | time_range       | Player Time Range   | text      | text        |
| Yes      | series tag     | frame_range      | Frame Range         | text      | text        |
| No       |                | time_stamp_start | Dropped Frame Start | text      | text        |
| No       |                | time_stamp_end   | Dropped Frame End   | text      | text        |
| Yes      | numeric metric | duration         | Duration            | number    | number      |
| Yes      | numeric metric | fps              | FPS                 | number    | number      |
| Yes      | numeric metric | dropped_frames   | Dropped Frames      | number    | number      |
| Yes      | series tag     | resolution       | Resolution          | text      | text        |
| Yes      | series tag     | file_size        | File Size           | text      | text        |
| Yes      | series tag     | file_name        | File Name           | text      | text        |
```

## Time Field

```ls
Value = file_date_time
Format & Zone = yyyyMMddHHmmss
```

## Series Fields

```ls
Excluded Fields = time_stamp_start,time_stamp_end
```

## Data Commands

```ls
series e:k7a5-emiw d:2014-02-24T12:39:00.000Z t:officer_id=7693 t:file_size="47.783 MB" t:resolution=720x480 t:frame_range=598-897 t:file_name=76936@20140224123907.mpg t:time_range=00:00:19-00:00:29 m:duration=10.82 m:dropped_frames=24 m:fps=27.64

series e:k7a5-emiw d:2014-03-10T19:21:05.000Z t:officer_id=7693 t:file_size="28.075 MB" t:resolution=720x480 t:frame_range=598-897 t:file_name=76936@20140310192154.mpg t:time_range=00:00:19-00:00:29 m:duration=11.91 m:dropped_frames=57 m:fps=25.1

series e:k7a5-emiw d:2014-03-10T19:21:05.000Z t:officer_id=7693 t:file_size="28.075 MB" t:resolution=720x480 t:frame_range=1196-1495 t:file_name=76936@20140310192154.mpg t:time_range=00:00:39-00:00:49 m:duration=13.68 m:dropped_frames=110 m:fps=21.86
```

## Meta Commands

```ls
metric m:duration p:float l:Duration t:dataTypeName=number

metric m:fps p:float l:FPS d:"Frames Per Second" t:dataTypeName=number

metric m:dropped_frames p:integer l:"Dropped Frames" d:"Count of dropped frames in 10 second sample period" t:dataTypeName=number

entity e:k7a5-emiw l:"Seattle Police Department In-Car Video Dropped Frame Report" t:attribution="Seattle Police" t:url=https://data.seattle.gov/api/views/k7a5-emiw

property e:k7a5-emiw t:meta.view d:2017-06-09T13:57:04.621Z v:id=k7a5-emiw v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department In-Car Video Dropped Frame Report" v:attribution="Seattle Police"

property e:k7a5-emiw t:meta.view.owner d:2017-06-09T13:57:04.621Z v:id=avyg-ej9j v:screenName=spd2internetData v:displayName=spd2internetData

property e:k7a5-emiw t:meta.view.tableauthor d:2017-06-09T13:57:04.621Z v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData
```

## Top Records

```ls
| officer_id | file_date_time | time_range        | frame_range | time_stamp_start        | time_stamp_end          | duration | fps   | dropped_frames | resolution | file_size   | file_name                | 
| ========== | ============== | ================= | =========== | ======================= | ======================= | ======== | ===== | ============== | ========== | =========== | ======================== | 
| 7693       | @2014022412390 | 00:00:19-00:00:29 | 598-897     | 2014-02-24 12:39:27.200 | 2014-02-24 12:39:38.017 | 10.82    | 27.64 | 24             | 720x480    | 47.783 MB   | 76936@20140224123907.mpg | 
| 7693       | @2014031019215 | 00:00:19-00:00:29 | 598-897     | 2014-03-10 19:22:17.596 | 2014-03-10 19:22:29.509 | 11.91    | 25.10 | 57             | 720x480    | 28.075 MB   | 76936@20140310192154.mpg | 
| 7693       | @2014031019215 | 00:00:39-00:00:49 | 1196-1495   | 2014-03-10 19:22:39.487 | 2014-03-10 19:22:53.166 | 13.68    | 21.86 | 110            | 720x480    | 28.075 MB   | 76936@20140310192154.mpg | 
| 7693       | @2014031019215 | 00:00:19-00:00:29 | 598-897     | 2014-03-10 19:22:18.742 | 2014-03-10 19:22:30.651 | 11.91    | 25.11 | 57             | 352x240    | 12.946 MB   | 76936@20140310192156.mpg | 
| 7693       | @2014031019215 | 00:00:39-00:00:49 | 1196-1495   | 2014-03-10 19:22:40.617 | 2014-03-10 19:22:54.128 | 13.51    | 22.13 | 105            | 352x240    | 12.946 MB   | 76936@20140310192156.mpg | 
| 7693       | @2014031019363 | 00:00:59-00:01:09 | 1794-2092   | 2014-03-10 19:37:32.950 | 2014-03-10 19:37:44.831 | 11.88    | 25.08 | 56             | 720x480    | 30.032 MB   | 76936@20140310193633.mpg | 
| 7693       | @2014031019363 | 00:00:59-00:01:09 | 1794-2093   | 2014-03-10 19:37:34.216 | 2014-03-10 19:37:46.106 | 11.89    | 25.15 | 56             | 352x240    | 13.252 MB   | 76936@20140310193634.mpg | 
| 7693       | @2014031021225 | 00:00:59-00:01:09 | 1794-2093   | 2014-03-10 21:23:50.170 | 2014-03-10 21:24:02.116 | 11.95    | 25.03 | 58             | 720x480    | 252.535 MB  | 76936@20140310212250.mpg | 
| 7693       | @2014031021225 | 00:00:59-00:01:09 | 1794-2093   | 2014-03-10 21:23:50.896 | 2014-03-10 21:24:02.841 | 11.94    | 25.03 | 58             | 352x240    | 109.154 MB  | 76936@20140310212251.mpg | 
| 7693       | @2014031221023 | 00:00:59-00:01:09 | 1794-2093   | 2014-03-12 21:03:37.124 | 2014-03-12 21:03:49.070 | 11.95    | 25.03 | 58             | 720x480    | 1054.040 MB | 76936@20140312210237.mpg | 
```