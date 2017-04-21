# Listing of Senior Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/listing-of-senior-centers) |
| Metadata | [Link](https://data.ct.gov/api/views/kbx6-3an2) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/kbx6-3an2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/kbx6-3an2/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | kbx6-3an2 |
| Name | Listing of Senior Centers |
| Attribution | State Department of Aging |
| Category | Health and Human Services |
| Tags | senior centers, aging |
| Created | 2014-04-03T13:23:06Z |
| Publication Date | 2014-08-01T17:36:47Z |

## Description

Listing of Senior Centers and contacts in Connecticut

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | first       | First      | text      | text        |
| Yes      | series tag  | last        | Last       | text      | text        |
| Yes      | series tag  | agency      | Agency     | text      | text        |
| Yes      | series tag  | town_city   | Town/City  | text      | text        |
| No       |             | st          | ST         | text      | text        |
| Yes      | series tag  | tel         | Tel. #     | text      | text        |
| Yes      | series tag  | fax         | Fax #      | text      | text        |
| Yes      | series tag  | email       | Email      | text      | text        |
| Yes      | series tag  | notes       | Notes      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = st
```

## Data Commands

```ls
series e:kbx6-3an2 d:2014-07-28T06:05:06.000Z t:fax="(860) 464-0478" t:last=Rapp t:email="(860) 464-2124" t:tel=CT t:town_city="12 Van Tassell Dr" t:agency="Ledyard Senior Center" t:notes=senior.director@ledyardct.org t:first=Lauren m:row_number.kbx6-3an2=1

series e:kbx6-3an2 d:2014-07-28T06:05:39.000Z t:fax=First t:email=Last t:tel=CT t:notes=Agency m:row_number.kbx6-3an2=2

series e:kbx6-3an2 d:2014-07-28T06:05:39.000Z t:fax="(203) 323-2404" t:last=Oligerre t:tel=CT t:town_city="1 Saint Benedict Cr" t:agency="Our Lady of Montserrat Senior Center" t:first=Reverand m:row_number.kbx6-3an2=3
```

## Meta Commands

```ls
metric m:row_number.kbx6-3an2 p:long l:"Row Number"

entity e:kbx6-3an2 l:"Listing of Senior Centers" t:attribution="State Department of Aging" t:url=https://data.ct.gov/api/views/kbx6-3an2

property e:kbx6-3an2 t:meta.view v:id=kbx6-3an2 v:category="Health and Human Services" v:averageRating=0 v:name="Listing of Senior Centers" v:attribution="State Department of Aging"

property e:kbx6-3an2 t:meta.view.license v:name="Public Domain"

property e:kbx6-3an2 t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:kbx6-3an2 t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | first    | last         | agency                               | town_city           | st                    | tel | fax            | email          | notes                         | 
| =========== | ======== | ============ | ==================================== | =================== | ===================== | === | ============== | ============== | ============================= | 
| 1406527506  | Lauren   | Rapp         | Ledyard Senior Center                | 12 Van Tassell Dr   | Ledyard (Gales Ferry) | CT  | (860) 464-0478 | (860) 464-2124 | senior.director@ledyardct.org | 
| 1406527539  |          |              |                                      |                     | Windham               | CT  | First          | Last           | Agency                        | 
| 1406527539  | Reverand | Oligerre     | Our Lady of Montserrat Senior Center | 1 Saint Benedict Cr | Stamford              | CT  | (203) 323-2404 |                |                               | 
| 1406527539  | Judy     | Lukas        | Earl W. Smith Senior Center          | 25 Tremko Ln        | Ashford               | CT  | (860) 487-5122 | (860) 487-5122 | ew.smith.sr@snet.net          | 
| 1406527539  | Erin     | Graziani     | Ellington Senior Center              | PO Box 187          | Ellington             | CT  | (860) 870-3133 | (860) 875-0877 | egranziani@ellington-ct.gov   | 
| 1406527539  | Loryn    | Ray          | Woodbury Senior Center               | 7 Mountain Rd       | Woodbury              | CT  | (203) 263-6282 |                | Lray@woodbury.ct.org          | 
| 1406527539  | Magali   | Kupfer       | Casa Boricua de Meriden              | Colony St.          | Meriden               | CT  | (203) 235-1082 |                | Mkupfer857@aol.com            | 
| 1406527539  | Julie    | Sullivan     | Barkhamsted Senior Center            | PO Box 558          | Barkhamsted           | CT  | (860) 738-1264 | (860) 758-6262 | dstein@barkhamsted.us         | 
| 1406527539  | Michelle | Clary-Butler | East Shore Senior Center             | 411 Townsend Ave    | New Haven             | CT  | (203) 946-8544 | (203) 946-8459 | mclarybutler@newhavenct.net   | 
| 1406527539  | Valerie  | Buckley      | Easton Senior Center                 | 650 Morehouse Rd    | Easton                | CT  | (203) 268-1145 | (203) 268-9586 | eseniorc@optonline.net        | 
```