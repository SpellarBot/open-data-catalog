# 2010 Local Film Festivals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-local-film-festivals-39efe) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yggg-xf4b) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yggg-xf4b/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yggg-xf4b/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yggg-xf4b |
| Name | 2010 Local Film Festivals |
| Attribution | Office of Film, Theatre, and Broadcasting (FILM) |
| Category | Recreation |
| Tags | film, movie, festival, event, theater, theatre, media, moftb, 2010 local film festivals |
| Created | 2011-08-30T19:19:22Z |
| Publication Date | 2013-06-26T17:19:12Z |

## Description

List of local film festivals

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| Yes      | series tag  | local_festivals | Local Festivals | text      | text        |
| No       |             | date            | Date            | text      | text        |
| Yes      | series tag  | website         | Website         | text      | text        |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = date
```

## Data Commands

```ls
series e:yggg-xf4b d:2010-01-01T00:00:00.000Z t:local_festivals="Local Festivals" m:row_number.yggg-xf4b=1

series e:yggg-xf4b d:2010-01-01T00:00:00.000Z t:local_festivals="Dance on Camera Festival" t:website=http://www.dancefilmsassn.org/ m:row_number.yggg-xf4b=2

series e:yggg-xf4b d:2010-01-01T00:00:00.000Z t:local_festivals="The New York Jewish Film Festival" t:website=http://www.thejewishmuseum.org/nyjff2010schedule m:row_number.yggg-xf4b=3
```

## Meta Commands

```ls
metric m:row_number.yggg-xf4b p:long l:"Row Number"

entity e:yggg-xf4b l:"2010 Local Film Festivals" t:attribution="Office of Film, Theatre, and Broadcasting (FILM)" t:url=https://data.cityofnewyork.us/api/views/yggg-xf4b

property e:yggg-xf4b t:meta.view v:id=yggg-xf4b v:category=Recreation v:averageRating=0 v:name="2010 Local Film Festivals" v:attribution="Office of Film, Theatre, and Broadcasting (FILM)"

property e:yggg-xf4b t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yggg-xf4b t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| local_festivals                                 | date              | website                                                       | 
| =============================================== | ================= | ============================================================= | 
| Local Festivals                                 |                   |                                                               | 
| Dance on Camera Festival                        | 1.25.10 ? 2.2.10  | http://www.dancefilmsassn.org/                                | 
| The New York Jewish Film Festival               | 1.13.10 ? 1.28.10 | http://www.thejewishmuseum.org/nyjff2010schedule              | 
| The New York Sephardic Jewish Film Festival     | 2.4.10 ? 2.11.10  | http://www.americansephardifederation.org/sub/events/film.asp | 
| New York International Children?s Film Festival | 2.26.10 ? 3.1.10  | http://www.gkids.com/                                         | 
| New York International Film & Video Festival    | 7.22.10 ? 7.29.10 | http://www.nyfilmvideo.com/                                   | 
| New Directors/New Films Festival                | 3.24.10 ? 4.4.10  | http://www.filmlinc.com/ndnf/ndnf.html                        | 
| GenArt Film Festival                            | 4.7.10 ? 4.13.10  | http://www.genart.org/                                        | 
| New York African Film Festival                  | 4.7.19 ? 4.13.10  | http://www.africanfilmny.org/                                 | 
| Tribeca Film Festival                           | 4.21.10 ? 5.2.10  | http://www.tribecafilm.com/festival/                          | 
```