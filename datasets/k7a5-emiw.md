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
| Rows Updated | 2017-01-10T21:15:02Z |

## Columns

```ls
| Included | Schema Type    | Field Name       | Name                | Data Type | Render Type |
| ======== | ============== | ================ | =================== | ========= | =========== |
| No       | time           | :updated_at      | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | officer_id       | Officer ID          | text      | text        |
| Yes      | series tag     | file_date_time   | File Date Time      | text      | text        |
| Yes      | series tag     | time_range       | Player Time Range   | text      | text        |
| Yes      | series tag     | frame_range      | Frame Range         | text      | text        |
| Yes      | series tag     | time_stamp_start | Dropped Frame Start | text      | text        |
| Yes      | series tag     | time_stamp_end   | Dropped Frame End   | text      | text        |
| Yes      | numeric metric | duration         | Duration            | number    | number      |
| Yes      | numeric metric | fps              | FPS                 | number    | number      |
| Yes      | numeric metric | dropped_frames   | Dropped Frames      | number    | number      |
| Yes      | series tag     | resolution       | Resolution          | text      | text        |
| Yes      | series tag     | file_size        | File Size           | text      | text        |
| Yes      | series tag     | file_name        | File Name           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:k7a5-emiw d:2014-10-03T16:00:51.000Z t:file_date_time=@2014022412390 t:time_stamp_start="2014-02-24 12:39:27.200" t:officer_id=7693 t:time_stamp_end="2014-02-24 12:39:38.017" t:file_size="47.783 MB" t:frame_range=598-897 t:resolution=720x480 t:file_name=76936@20140224123907.mpg t:time_range=00:00:19-00:00:29 m:duration=10.82 m:dropped_frames=24 m:fps=27.64

series e:k7a5-emiw d:2014-10-03T16:00:51.000Z t:file_date_time=@2014031019215 t:time_stamp_start="2014-03-10 19:22:17.596" t:officer_id=7693 t:time_stamp_end="2014-03-10 19:22:29.509" t:file_size="28.075 MB" t:frame_range=598-897 t:resolution=720x480 t:file_name=76936@20140310192154.mpg t:time_range=00:00:19-00:00:29 m:duration=11.91 m:dropped_frames=57 m:fps=25.1

series e:k7a5-emiw d:2014-10-03T16:00:51.000Z t:file_date_time=@2014031019215 t:time_stamp_start="2014-03-10 19:22:39.487" t:officer_id=7693 t:time_stamp_end="2014-03-10 19:22:53.166" t:file_size="28.075 MB" t:frame_range=1196-1495 t:resolution=720x480 t:file_name=76936@20140310192154.mpg t:time_range=00:00:39-00:00:49 m:duration=13.68 m:dropped_frames=110 m:fps=21.86
```

## Meta Commands

```ls
metric m:duration l:Duration t:dataTypeName=number

metric m:fps l:FPS d:"Frames Per Second" t:dataTypeName=number

metric m:dropped_frames p:integer l:"Dropped Frames" d:"Count of dropped frames in 10 second sample period" t:dataTypeName=number

entity e:k7a5-emiw l:"Seattle Police Department In-Car Video Dropped Frame Report" t:attribution="Seattle Police" t:url=https://data.seattle.gov/api/views/k7a5-emiw

property e:k7a5-emiw t:meta.view v:id=k7a5-emiw v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department In-Car Video Dropped Frame Report" v:attribution="Seattle Police"

property e:k7a5-emiw t:meta.view.owner v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData

property e:k7a5-emiw t:meta.view.tableauthor v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData
```