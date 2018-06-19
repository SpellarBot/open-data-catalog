# Libraries - Popular Fiction Titles at the Chicago Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-popular-fiction-titles-at-the-chicago-public-library-69299) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/nv46-bxa3) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/nv46-bxa3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/nv46-bxa3/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | nv46-bxa3 |
| Name | Libraries - Popular Fiction Titles at the Chicago Public Library |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, fiction |
| Created | 2011-09-23T20:11:50Z |
| Publication Date | 2014-02-28T19:08:01Z |

## Description

Popular fiction titles at the Chicago Public Library, January 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | rank           | RANK           | number    | number      |
| Yes      | series tag     | title          | TITLE          | text      | text        |
| Yes      | series tag     | author         | AUTHOR         | text      | text        |
| Yes      | time           | pub_year       | PUB YEAR       | number    | number      |
| Yes      | series tag     | catalog_record | CATALOG RECORD | url       | url         |
```

## Time Field

```ls
Value = pub_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nv46-bxa3 d:2013-01-01T00:00:00.000Z t:author="Tartt, Donna." t:title="The goldfinch" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316055437" m:rank=1

series e:nv46-bxa3 d:2012-01-01T00:00:00.000Z t:author="Flynn, Gillian, 1971-" t:title="Gone girl: a novel" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780307588364" m:rank=2

series e:nv46-bxa3 d:2013-01-01T00:00:00.000Z t:author="Grisham, John." t:title="Sycamore row" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780385537131" m:rank=3
```

## Meta Commands

```ls
metric m:rank p:integer l:RANK t:dataTypeName=number

entity e:nv46-bxa3 l:"Libraries - Popular Fiction Titles at the Chicago Public Library" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/nv46-bxa3

property e:nv46-bxa3 t:meta.view v:id=nv46-bxa3 v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - Popular Fiction Titles at the Chicago Public Library" v:attribution="Chicago Public Library"

property e:nv46-bxa3 t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:nv46-bxa3 t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| rank | title                      | author                   | pub_year | catalog_record                                                                                                             | 
| ==== | ========================== | ======================== | ======== | ========================================================================================================================== | 
| 1    | The goldfinch              | Tartt, Donna.            | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316055437, null] | 
| 2    | Gone girl: a novel         | Flynn, Gillian, 1971-    | 2012     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780307588364, null] | 
| 3    | Sycamore row               | Grisham, John.           | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780385537131, null] | 
| 4    | The gods of guilt: a novel | Connelly, Michael, 1956- | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316069519, null] | 
| 5    | The invention of wings     | Kidd, Sue Monk.          | 2014     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780670024780, null] | 
| 6    | Takedown twenty            | Evanovich, Janet.        | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=0345542886, null]    | 
| 7    | Cross my heart             | Patterson, James, 1947-  | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316210911, null] | 
| 8    | And the mountains echoed   | Hosseini, Khaled.        | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781594631764, null] | 
| 9    | The Interestings           | Wolitzer, Meg.           | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781594488399, null] | 
| 10   | Inferno: a novel           | Brown, Dan, 1964-        | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780385537858, null] | 
```