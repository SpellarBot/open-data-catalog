# Baltimore Arts Organizations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/baltimore-arts-organizations-e25f6) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/r4ur-u5nm) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/r4ur-u5nm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/r4ur-u5nm/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | r4ur-u5nm |
| Name | Baltimore Arts Organizations |
| Attribution | The Baltimore Office of Promotion & The Arts |
| Category | Culture & Arts |
| Tags | theater, art, music, dance, literature, photography |
| Created | 2012-03-30T16:20:59Z |
| Publication Date | 2014-04-03T23:46:56Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | organization | organization | text      | text        |
| Yes      | series tag  | adress       | adress       | text      | text        |
| Yes      | series tag  | citystate    | cityState    | text      | text        |
| Yes      | series tag  | zipcode      | zipCode      | text      | text        |
| Yes      | series tag  | url          | URL          | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:r4ur-u5nm d:2012-03-30T09:21:08.000Z t:adress="140 West Mount Royal" t:organization="Modell Performing Arts Center at the Lyric" t:zipcode=21201 t:citystate="Baltimore, MD" t:url=http://www.lyricoperahouse.com/ m:row_number.r4ur-u5nm=1

series e:r4ur-u5nm d:2012-03-30T09:21:08.000Z t:adress="3618 Greenmount Avenue" t:organization="National James Baldwin Literary Society, Inc./BMI" t:zipcode=21218 t:citystate="Baltimore, MD" t:url=http://jamesbaldwin.org/Home_Page.html m:row_number.r4ur-u5nm=2

series e:r4ur-u5nm d:2012-03-30T09:23:13.000Z t:adress="806 S. Broadway" t:organization="Vagabond Players, Inc." t:zipcode=21231 t:citystate="Baltimore, MD" t:url=http://www.vagabondplayers.org/ m:row_number.r4ur-u5nm=3
```

## Meta Commands

```ls
metric m:row_number.r4ur-u5nm p:long l:"Row Number"

entity e:r4ur-u5nm l:"Baltimore Arts Organizations" t:attribution="The Baltimore Office of Promotion & The Arts" t:url=https://data.baltimorecity.gov/api/views/r4ur-u5nm

property e:r4ur-u5nm t:meta.view v:id=r4ur-u5nm v:category="Culture & Arts" v:attributionLink=http://www.bop.org v:averageRating=0 v:name="Baltimore Arts Organizations" v:attribution="The Baltimore Office of Promotion & The Arts"

property e:r4ur-u5nm t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:r4ur-u5nm t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:r4ur-u5nm t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | organization                                      | adress                 | citystate     | zipcode | url                                               | 
| =========== | ================================================= | ====================== | ============= | ======= | ================================================= | 
| 1333099268  | Modell Performing Arts Center at the Lyric        | 140 West Mount Royal   | Baltimore, MD | 21201   | [http://www.lyricoperahouse.com/, null]           | 
| 1333099268  | National James Baldwin Literary Society, Inc./BMI | 3618 Greenmount Avenue | Baltimore, MD | 21218   | [http://jamesbaldwin.org/Home_Page.html, null]    | 
| 1333099393  | Vagabond Players, Inc.                            | 806 S. Broadway        | Baltimore, MD | 21231   | [http://www.vagabondplayers.org/, null]           | 
| 1333099268  | Baltimore Jazz Alliance                           | 847 N. Howard Street   | Baltimore, MD | 21201   | [http://www.baltimorejazz.com/, null]             | 
| 1333099268  | CityLit Project                                   | 120 S. Curley Street   | Baltimore, MD | 21224   | [http://www.citylitproject.org/, null]            | 
| 1333099268  | Studiokafi Photography                            | 3101 Gibbons Avenue    | Baltimore, MD | 21214   | [http://studiokafi.wordpress.com/, null]          | 
| 1333099268  | New Mercury Readings                              | 3312 Beech Avenue      | Baltimore, MD | 21201   | [http://thenewmercuryreadings.com/, null]         | 
| 1333099268  | Reginald Lewis Museum                             | 830 East Pratt Strett  | Baltimore, MD | 21202   | [http://www.africanamericanculture.org/, null]    | 
| 1333099268  | Baltimore Dance Collective                        | 7430 Brookwood Avenue  | Baltimore, MD | 21236   | [http://www.collective-dance.com/home.html, null] | 
| 1333099268  | Baltimore Theatre Project                         | 45 W. Preston Street   | Baltimore, MD | 21201   | [http://www.theatreproject.org/, null]            | 
```