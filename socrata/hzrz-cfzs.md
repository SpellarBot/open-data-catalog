# Charm City Circulator Headways

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/charm-city-circulator-headways-88a37) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/hzrz-cfzs) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/hzrz-cfzs/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/hzrz-cfzs/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | hzrz-cfzs |
| Name | Charm City Circulator Headways |
| Attribution | Department of Transportation |
| Category | Transportation |
| Tags | transportation, bus, circulator, eco-friendly |
| Created | 2012-05-11T14:22:29Z |
| Publication Date | 2014-04-03T23:40:22Z |

## Description

The City of Baltimore is constantly seeking innovative and creative ways to alleviate traffic congestion and green house gases in our great city. A new fleet of eco-friendly buses will provide everyone with a faster, more convenient, greener way to move about Baltimore's busy downtown neighborhoods. A headway is the amount of time that passes between two buses.  The goal for the Charm City Circulator headways is a bus every ten minutes. Morning and evening peak times for each route are(7 am ??_??_??_ 9 am and 4 pm ??_??_??_ 6 pm.

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type     | Render Type   |
| ======== | =========== | ================= | ================= | ============= | ============= |
| Yes      | series tag  | day               | day               | text          | text          |
| Yes      | time        | date              | date              | calendar_date | calendar_date |
| Yes      | series tag  | orangeheadway     | orangeHeadway     | text          | text          |
| Yes      | series tag  | orangemorningpeak | orangeMorningPeak | text          | text          |
| Yes      | series tag  | orangeeveningpeak | orangeEveningPeak | text          | text          |
| Yes      | series tag  | purpleheadway     | purpleHeadway     | text          | text          |
| Yes      | series tag  | purplemorningpeak | purpleMorningPeak | text          | text          |
| Yes      | series tag  | purpleeveningpeak | purpleEveningPeak | text          | text          |
| Yes      | series tag  | greenheadway      | greenHeadway      | text          | text          |
| Yes      | series tag  | greenmorningpeak  | greenMorningPeak  | text          | text          |
| Yes      | series tag  | greeneveningpeak  | greenEveningPeak  | text          | text          |
| Yes      | series tag  | bannerheadway     | bannerHeadway     | text          | text          |
| Yes      | series tag  | bannermorningpeak | bannerMorningPeak | text          | text          |
| Yes      | series tag  | bannereveningpeak | bannerEveningPeak | text          | text          |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hzrz-cfzs d:2010-01-11T00:00:00.000Z t:day=Monday t:orangeeveningpeak=10:10 t:orangeheadway=10:11 m:row_number.hzrz-cfzs=1

series e:hzrz-cfzs d:2010-01-12T00:00:00.000Z t:orangemorningpeak=11:58 t:day=Tuesday t:orangeeveningpeak=15:13 t:orangeheadway=12:42 m:row_number.hzrz-cfzs=2

series e:hzrz-cfzs d:2010-01-13T00:00:00.000Z t:orangemorningpeak=9:27 t:day=Wednesday t:orangeeveningpeak=12:36 t:orangeheadway=10:56 m:row_number.hzrz-cfzs=3
```

## Meta Commands

```ls
metric m:row_number.hzrz-cfzs p:long l:"Row Number"

entity e:hzrz-cfzs l:"Charm City Circulator Headways" t:attribution="Department of Transportation" t:url=https://data.baltimorecity.gov/api/views/hzrz-cfzs

property e:hzrz-cfzs t:meta.view v:id=hzrz-cfzs v:category=Transportation v:attributionLink=http://www.charmcitycirculator.com/ v:averageRating=0 v:name="Charm City Circulator Headways" v:attribution="Department of Transportation"

property e:hzrz-cfzs t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:hzrz-cfzs t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:hzrz-cfzs t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| day       | date                | orangeheadway | orangemorningpeak | orangeeveningpeak | purpleheadway | purplemorningpeak | purpleeveningpeak | greenheadway | greenmorningpeak | greeneveningpeak | bannerheadway | bannermorningpeak | bannereveningpeak | 
| ========= | =================== | ============= | ================= | ================= | ============= | ================= | ================= | ============ | ================ | ================ | ============= | ================= | ================= | 
| Monday    | 2010-01-11T00:00:00 | 10:11         |                   | 10:10             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Tuesday   | 2010-01-12T00:00:00 | 12:42         | 11:58             | 15:13             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Wednesday | 2010-01-13T00:00:00 | 10:56         | 9:27              | 12:36             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Thursday  | 2010-01-14T00:00:00 | 10:31         | 9:44              | 11:41             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Friday    | 2010-01-15T00:00:00 | 10:24         | 9:17              | 11:42             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Saturday  | 2010-01-16T00:00:00 | 10:04         |                   |                   |               |                   |                   |              |                  |                  |               |                   |                   | 
| Sunday    | 2010-01-17T00:00:00 | 10:06         |                   |                   |               |                   |                   |              |                  |                  |               |                   |                   | 
| Monday    | 2010-01-18T00:00:00 | 8:15          |                   |                   |               |                   |                   |              |                  |                  |               |                   |                   | 
| Tuesday   | 2010-01-19T00:00:00 | 10:27         | 10:18             | 10:58             |               |                   |                   |              |                  |                  |               |                   |                   | 
| Wednesday | 2010-01-20T00:00:00 | 10:37         | 11:17             | 10:41             |               |                   |                   |              |                  |                  |               |                   |                   | 
```