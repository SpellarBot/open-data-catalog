# Historic Zoning Districts - March 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historical-zoning-districts-march-2005-54e8b) |
| Metadata | [Link](https://data.sfgov.org/api/views/d7vm-pqzv) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/d7vm-pqzv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/d7vm-pqzv/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | d7vm-pqzv |
| Name | Historic Zoning Districts - March 2005 |
| Category | Geographic Locations and Boundaries |
| Tags | planning, zoning, shapefile, gis |
| Created | 2016-07-28T17:41:18Z |
| Publication Date | 2016-08-19T21:40:55Z |

## Description

Historic Zoning Districts - March 2005.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | blklot     | blklot     | text      | text        |
| Yes      | series tag     | block_num  | block_num  | text      | text        |
| Yes      | series tag     | from_st    | from_st    | text      | text        |
| Yes      | series tag     | heightlimi | heightlimi | text      | text        |
| Yes      | series tag     | lot_num    | lot_num    | text      | text        |
| Yes      | series tag     | mapblklot  | mapblklot  | text      | text        |
| Yes      | series tag     | objectid   | objectid   | text      | number      |
| Yes      | series tag     | odd_even   | odd_even   | text      | text        |
| Yes      | numeric metric | planningdi | planningdi | number    | number      |
| Yes      | series tag     | quadrant   | quadrant   | text      | text        |
| Yes      | series tag     | ssd        | ssd        | text      | text        |
| Yes      | series tag     | street     | street     | text      | text        |
| Yes      | series tag     | st_type    | st_type    | text      | text        |
| Yes      | series tag     | sud        | sud        | text      | text        |
| Yes      | series tag     | to_st      | to_st      | text      | text        |
| Yes      | series tag     | zoning     | zoning     | text      | text        |
| No       |                | geometry   | geometry   | polygon   | polygon     |
| Yes      | series tag     | multigeom  | multigeom  | checkbox  | checkbox    |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = geometry
```

## Data Commands

```ls
series e:d7vm-pqzv d:2005-01-01T00:00:00.000Z t:sud=NOWAT-2 t:blklot=0013009 t:ssd=ILLUMIN t:lot_num=009 t:street=MASON t:quadrant=NORTHEAST t:odd_even=O t:to_st=2601 t:block_num=0013 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=2601 t:objectid=25 t:zoning=C-2 t:mapblklot=0013009 m:planningdi=3

series e:d7vm-pqzv d:2005-01-01T00:00:00.000Z t:sud=NOWAT-2 t:blklot=0013010 t:ssd=ILLUMIN t:lot_num=010 t:street=BEACH t:quadrant=NORTHEAST t:odd_even=E t:to_st=330 t:block_num=0013 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=330 t:objectid=26 t:zoning=C-2 t:mapblklot=0013010 m:planningdi=3

series e:d7vm-pqzv d:2005-01-01T00:00:00.000Z t:sud=NOWAT-2 t:blklot=0014001 t:ssd=ILLUMIN t:lot_num=001 t:street=JEFFERSON t:quadrant=NORTHEAST t:odd_even=O t:to_st=91 t:block_num=0014 t:heightlimi=40-X t:multigeom=false t:st_type=ST t:from_st=1 t:objectid=28 t:zoning=C-2 t:mapblklot=0014001 m:planningdi=3
```

## Meta Commands

```ls
metric m:planningdi p:long l:planningdi t:dataTypeName=number

entity e:d7vm-pqzv l:"Historic Zoning Districts - March 2005" t:url=https://data.sfgov.org/api/views/d7vm-pqzv

property e:d7vm-pqzv t:meta.view v:id=d7vm-pqzv v:category="Geographic Locations and Boundaries" v:averageRating=0 v:name="Historic Zoning Districts - March 2005"

property e:d7vm-pqzv t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:d7vm-pqzv t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:d7vm-pqzv t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| blklot  | block_num | from_st | heightlimi | lot_num | mapblklot | objectid | odd_even | planningdi | quadrant  | ssd     | street             | st_type | sud          | to_st | zoning | geometry                                                                                                                                                                                                                                                                                 | multigeom | 
| ======= | ========= | ======= | ========== | ======= | ========= | ======== | ======== | ========== | ========= | ======= | ================== | ======= | ============ | ===== | ====== | ======================================================================================================================================================================================================================================================================================== | ========= | 
| 0013009 | 0013      | 2601    | 40-X       | 009     | 0013009   | 25       | O        | 3.0        | NORTHEAST | ILLUMIN | MASON              | ST      | NOWAT-2      | 2601  | C-2    | POLYGON ((-122.41440714513173 37.80752258376409, -122.41444804468331 37.80772598556728, -122.41461900036224 37.8077045661382, -122.4146530844683 37.8078740686171, -122.41418506383822 37.80793270664871, -122.41410887505653 37.80755995329709, -122.41440714513173 37.80752258376409)) | false     | 
| 0013010 | 0013      | 330     | 40-X       | 010     | 0013010   | 26       | E        | 3.0        | NORTHEAST | ILLUMIN | BEACH              | ST      | NOWAT-2      | 330   | C-2    | POLYGON ((-122.41461900036224 37.8077045661382, -122.41444804468331 37.80772598556728, -122.41440714513173 37.80752258376409, -122.41457809921867 37.8075011644119, -122.41461900036224 37.8077045661382))                                                                               | false     | 
| 0014001 | 0014      | 1       | 40-X       | 001     | 0014001   | 28       | O        | 3.0        | NORTHEAST | ILLUMIN | JEFFERSON          | ST      | NOWAT-2      | 91    | C-2    | POLYGON ((-122.41387534685282 37.80759194475995, -122.41402801451368 37.808338893395835, -122.41262882367502 37.80851405648082, -122.41246723410697 37.80777175250363, -122.41387534685282 37.80759194475995))                                                                           | false     | 
| 0015001 | 0015      | 1789    | 40-X       | 001     | 0015001   | 29       | O        | 3.0        | NORTHEAST |         | EMBARCADERO CENTER |         | WATERFRONT-3 | 1789  | C-2    | POLYGON ((-122.41223210048018 37.80779760424541, -122.41238029281914 37.808478380209515, -122.41088274965435 37.80825540708036, -122.41082187297532 37.80797572321348, -122.41223210048018 37.80779760424541))                                                                           | false     | 
| 0016001 | 0016      | 50      | 40-X       | 001     | 0016001   | 30       | E        | 3.0        | NORTHEAST |         | BEACH              | ST      | WATERFRONT-3 | 50    | C-2    | POLYGON ((-122.41059241348093 37.8079987634875, -122.41064085033346 37.80822130048096, -122.40983206407077 37.808096148276185, -122.41059241348093 37.8079987634875))                                                                                                                    | false     | 
| 0017002 | 0017      | 2       | 40-X       | 002     | 0017002   | 31       | E        | 3.0        | NORTHEAST |         | NORTH POINT        | ST      | WATERFRONT-3 | 2     | C-2    | POLYGON ((-122.40884064163777 37.80726578858193, -122.408971265666 37.807922351525654, -122.4077424077014 37.80740414938926, -122.40884064163777 37.80726578858193))                                                                                                                     | false     | 
| 0018001 | 0018      | 1       | 40-X       | 001     | 0018001   | 32       | O        | 3.0        | NORTHEAST |         | BEACH              | ST      | NOWAT-2      | 1     | C-2    | POLYGON ((-122.41007937624877 37.80787321945866, -122.40913962814184 37.80799357685251, -122.40906535653328 37.80762027142686, -122.41000547959769 37.807501819936014, -122.41007937624877 37.80787321945866))                                                                           | false     | 
| 0018004 | 0018      | 2340    | 40-X       | 004     | 0018004   | 33       | E        | 3.0        | NORTHEAST |         | STOCKTON           | ST      | NOWAT-2      | 2340  | C-2    | POLYGON ((-122.41007937624877 37.80787321945866, -122.41000547959769 37.807501819936014, -122.40993126534833 37.80712881954002, -122.4104013246121 37.8070695921578, -122.41054924971586 37.80781303749352, -122.41007937624877 37.80787321945866))                                      | false     | 
| 0018005 | 0018      | 100     | 40-X       | 005     | 0018005   | 34       | E        | 3.0        | NORTHEAST |         | NORTH POINT        | ST      | NOWAT-2      | 100   | C-2    | POLYGON ((-122.41000547959769 37.807501819936014, -122.40906535653328 37.80762027142686, -122.40899114691148 37.80724727134852, -122.40993126534833 37.80712881954002, -122.41000547959769 37.807501819936014))                                                                          | false     | 
| 0020001 | 0020      | 211     | 40-X       | 001     | 0020001   | 36       | O        | 3.0        | NORTHEAST |         | BEACH              | ST      | NOWAT-2      | 211   | C-2    | POLYGON ((-122.41368912671325 37.80666302436419, -122.4138411394907 37.80740507323876, -122.41242749279496 37.80758558770158, -122.4122778951539 37.80683772133315, -122.41368912671325 37.80666302436419))                                                                              | false     | 
```