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

property e:k7a5-emiw t:meta.view v:id=k7a5-emiw v:category="Public Safety" v:averageRating=0 v:name="Seattle Police Department In-Car Video Dropped Frame Report" v:attribution="Seattle Police"

property e:k7a5-emiw t:meta.view.owner v:id=avyg-ej9j v:screenName=spd2internetData v:displayName=spd2internetData

property e:k7a5-emiw t:meta.view.tableauthor v:id=avyg-ej9j v:screenName=spd2internetData v:roleName=publisher v:displayName=spd2internetData
```