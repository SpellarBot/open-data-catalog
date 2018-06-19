# 2011 Primary - Races

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/201108-list-of-races-dd021) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/tqg4-seid) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/tqg4-seid/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/tqg4-seid/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | tqg4-seid |
| Name | 2011 Primary - Races |
| Attribution | King County |
| Category | Election operations |
| Tags | elections, vote, voting, 2011 |
| Created | 2011-08-16T00:21:34Z |
| Publication Date | 2011-08-16T00:21:34Z |

## Description

Primary election 2011 list of races

## Columns

```ls
| Included | Schema Type | Field Name | Name    | Data Type | Render Type |
| ======== | =========== | ========== | ======= | ========= | =========== |
| Yes      | series tag  | results    | Results | url       | url         |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Data Commands

```ls
series e:tqg4-seid d:2011-01-01T00:00:00.000Z t:results=http://your.kingcounty.gov/elections/elections/201108/resPage3.aspx m:row_number.tqg4-seid=1

series e:tqg4-seid d:2011-01-01T00:00:00.000Z t:results=http://your.kingcounty.gov/elections/elections/201108/resPage5.aspx m:row_number.tqg4-seid=2

series e:tqg4-seid d:2011-01-01T00:00:00.000Z t:results=http://your.kingcounty.gov/elections/elections/201108/resPage7.aspx m:row_number.tqg4-seid=3
```

## Meta Commands

```ls
metric m:row_number.tqg4-seid p:long l:"Row Number"

entity e:tqg4-seid l:"2011 Primary - Races" t:attribution="King County" t:url=https://data.kingcounty.gov/api/views/tqg4-seid

property e:tqg4-seid t:meta.view v:id=tqg4-seid v:category="Election operations" v:attributionLink=http://www.kingcounty.gov/elections v:averageRating=0 v:name="2011 Primary - Races" v:attribution="King County"

property e:tqg4-seid t:meta.view.license v:name="Public Domain"

property e:tqg4-seid t:meta.view.owner v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:displayName="King County Webteam"

property e:tqg4-seid t:meta.view.tableauthor v:id=2gzv-6b6z v:profileImageUrlMedium=/api/users/2gzv-6b6z/profile_images/THUMB v:profileImageUrlLarge=/api/users/2gzv-6b6z/profile_images/LARGE v:screenName="King County Webteam" v:profileImageUrlSmall=/api/users/2gzv-6b6z/profile_images/TINY v:roleName=administrator v:displayName="King County Webteam"
```

## Top Records

```ls
| results                                                                                                                                                                   | 
| ========================================================================================================================================================================= | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage3.aspx, Court of Appeals, Division No. 1, District No. 1]                                                   | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage5.aspx, City of Kirkland Council Position No. 6 nonpartisan office]                                         | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage7.aspx, City of Seattle Council Position No. 9]                                                             | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage7.aspx, City of Seattle Council Position No. 1]                                                             | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage6.aspx, City of Sammamish Council Position No. 4]                                                           | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage6.aspx, City of Renton Council Position No. 5]                                                              | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage6.aspx, City of Newcastle Council Position No. 4]                                                           | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage5.aspx, City of Kent Council Position No. 5]                                                                | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage8.aspx, City of Tukwila Proposition No. 1 Formation and Funding of Tukwila Pool Metropolitan Park District] | 
| [http://your.kingcounty.gov/elections/elections/201108/resPage12.aspx, King County Fire Protection District No. 43 Commissioner Position No. 4]                           | 
```