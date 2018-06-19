# Production office space

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/production-office-space-83dc3) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/bvna-6j7v) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/bvna-6j7v/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/bvna-6j7v/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | bvna-6j7v |
| Name | Production office space |
| Attribution | Office of Film, Theatre, and Broadcasting (FILM) |
| Category | Recreation |
| Tags | property, business, media, production, record, recording, sound, studio, commercial, space, production office space, moftb |
| Created | 2011-10-08T20:43:42Z |
| Publication Date | 2013-06-21T20:27:27Z |

## Description

List of Commercial space for recording and sound production in New York City. This is a list of studios which have requested to be included, rather than a comprehensive list of NYC facilities.

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type | Render Type |
| ======== | =========== | =========== | =========== | ========= | =========== |
| No       | time        | :updated_at | updated_at  | meta_data | meta_data   |
| Yes      | series tag  | studio_name | Studio Name | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code    | text      | number      |
| Yes      | series tag  | phone       | Phone       | text      | text        |
| Yes      | series tag  | fax         | Fax         | text      | text        |
| Yes      | series tag  | website     | Website     | text      | text        |
| Yes      | series tag  | email       | Email       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:bvna-6j7v d:2011-10-08T13:44:17.000Z t:phone=212-203-2325 t:fax=212-222-1113 t:zip_code=10031 t:email=ny411@strongboystudios.com t:website=www.strongboystudios.com t:studio_name="Strongboy Studios" m:row_number.bvna-6j7v=1

series e:bvna-6j7v d:2011-10-08T13:44:17.000Z t:phone=212-967-6532 t:fax=646-607-2767 t:zip_code=10018 t:email=info@hoboaudio.com t:website=www.hoboaudio.com t:studio_name="Hobo Audio Company" m:row_number.bvna-6j7v=2

series e:bvna-6j7v d:2011-10-08T13:44:17.000Z t:phone=212-473-2700 t:fax=212-473-2772 t:zip_code=10003 t:email=jenniferh@audioengine.net t:website=www.audioengine.net t:studio_name=audioEngine m:row_number.bvna-6j7v=3
```

## Meta Commands

```ls
metric m:row_number.bvna-6j7v p:long l:"Row Number"

entity e:bvna-6j7v l:"Production office space" t:attribution="Office of Film, Theatre, and Broadcasting (FILM)" t:url=https://data.cityofnewyork.us/api/views/bvna-6j7v

property e:bvna-6j7v t:meta.view v:id=bvna-6j7v v:category=Recreation v:averageRating=0 v:name="Production office space" v:attribution="Office of Film, Theatre, and Broadcasting (FILM)"

property e:bvna-6j7v t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:bvna-6j7v t:meta.view.tableauthor v:id=txun-eb7e v:screenName="Albert Webber" v:roleName=administrator v:displayName="Albert Webber"
```

## Top Records

```ls
| :updated_at | studio_name              | zip_code | phone        | fax          | website                  | email                       | 
| =========== | ======================== | ======== | ============ | ============ | ======================== | =========================== | 
| 1318081457  | Strongboy Studios        | 10031    | 212-203-2325 | 212-222-1113 | www.strongboystudios.com | ny411@strongboystudios.com  | 
| 1318081457  | Hobo Audio Company       | 10018    | 212-967-6532 | 646-607-2767 | www.hoboaudio.com        | info@hoboaudio.com          | 
| 1318081457  | audioEngine              | 10003    | 212-473-2700 | 212-473-2772 | www.audioengine.net      | jenniferh@audioengine.net   | 
| 1318081457  | Silver Sound Inc.        | 10001    | 212-757-5147 | 212-757-6245 | www.silversound.us       | cory@silversound.us         | 
| 1318081457  | Bond                     | 10012    | 212-533-9400 |              | www.bondedit.com         | jeff_beckerman@bondedit.com | 
| 1318081457  | Full House Productions   | 10011    | 212-645-2228 | 212-627-2838 | www.fullhouseny.com      |                             | 
| 1318081457  | Mixopolis, Inc.          | 10017    | 212-980-5009 | 212-223-4524 | www.mixopolis.com        | lydia@mixopolis.com         | 
| 1318081457  | Avatar Studios           | 10019    | 212-765-7500 |              | www.avatarstudios.net    | tino@avatarstudios.net      | 
| 1318081457  | Manhattan Center Studios | 10001    | 877-627-8834 | 212-564-1092 | www.mcstudios.com        | obie@mcpstudios.com         | 
| 1318081457  | Pomann Sound, Inc.       | 10036    | 212-869-4161 | 212-869-4541 | www.pomannsound.com      | info@pomannsound.com        | 
```