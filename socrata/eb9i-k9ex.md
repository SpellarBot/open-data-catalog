# Youtube IDs for body worn videos from phase 1 of the pilot

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/youtube-ids-for-body-worn-videos-from-phase-1-of-the-pilot) |
| Metadata | [Link](https://data.seattle.gov/api/views/eb9i-k9ex) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/eb9i-k9ex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/eb9i-k9ex/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | eb9i-k9ex |
| Name | Youtube IDs for body worn videos from phase 1 of the pilot |
| Category | Public Safety |
| Created | 2015-06-08T05:00:46Z |
| Publication Date | 2015-06-08T05:02:14Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | filename    | Filename   | text      | text        |
| Yes      | series tag  | youtube_id  | Youtube ID | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:eb9i-k9ex d:2015-06-07T22:06:38.000Z t:filename=FDFE480648AA4F888530AE7562436CF0.mp4 t:youtube_id=pQYNLRqEVHU m:row_number.eb9i-k9ex=1

series e:eb9i-k9ex d:2015-06-07T22:06:38.000Z t:filename=FEDC4682AE564209AC664040FC29777B.mp4 t:youtube_id=2bcSV-zu9V0 m:row_number.eb9i-k9ex=2

series e:eb9i-k9ex d:2015-06-07T22:06:40.000Z t:filename=FEEDB291E6E54A7DA65D875F7795A785.mp4 t:youtube_id=AymhZ47SDsk m:row_number.eb9i-k9ex=3
```

## Meta Commands

```ls
metric m:row_number.eb9i-k9ex p:long l:"Row Number"

entity e:eb9i-k9ex l:"Youtube IDs for body worn videos from phase 1 of the pilot" t:url=https://data.seattle.gov/api/views/eb9i-k9ex

property e:eb9i-k9ex t:meta.view v:id=eb9i-k9ex v:category="Public Safety" v:averageRating=0 v:name="Youtube IDs for body worn videos from phase 1 of the pilot"

property e:eb9i-k9ex t:meta.view.license v:name="Public Domain"

property e:eb9i-k9ex t:meta.view.owner v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans

property e:eb9i-k9ex t:meta.view.tableauthor v:id=v35j-cik3 v:screenName=timothyclemans v:displayName=timothyclemans
```

## Top Records

```ls
| :updated_at | filename                             | youtube_id  | 
| =========== | ==================================== | =========== | 
| 1433714798  | FDFE480648AA4F888530AE7562436CF0.mp4 | pQYNLRqEVHU | 
| 1433714798  | FEDC4682AE564209AC664040FC29777B.mp4 | 2bcSV-zu9V0 | 
| 1433714800  | FEEDB291E6E54A7DA65D875F7795A785.mp4 | AymhZ47SDsk | 
| 1433714800  | FFFB367133A74118B2D7123B9717941F.mp4 | kmFlDlZAsLM | 
| 1433714802  | FE8986CEE44D4E248B34BF252F817D70.mp4 | PFlASI6bu48 | 
| 1433714802  | FE451FF3E27F4EC7A8F5C1EC220A7052.mp4 | NVI_0nxzl1k | 
| 1433714802  | FFECD16F02E1472780EAB04CE4D69A9C.mp4 | IygZdTFBUrg | 
| 1433714802  | FF7B2ACBE65D404ABCAC27084E127747.mp4 | kxCqvoe1hok | 
| 1433714807  | FDDD90B5D446404CB692D0E44D81034D.mp4 | 8F4G6aTQZ5I | 
| 1433714811  | FDCACC47F38F42E88264590458FF3CAA.mp4 | 52H-zUmgPi4 | 
```