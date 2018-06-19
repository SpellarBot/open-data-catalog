# Libraries - Popular Nonfiction Titles at the Chicago Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-popular-nonfiction-titles-at-the-chicago-public-library-6d242) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/y4km-wdbp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/y4km-wdbp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/y4km-wdbp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | y4km-wdbp |
| Name | Libraries - Popular Nonfiction Titles at the Chicago Public Library |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, nonfiction |
| Created | 2011-09-26T14:25:49Z |
| Publication Date | 2014-02-28T19:15:13Z |

## Description

Popular nonfiction titles at the Chicago Public Library, January 2014.

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | rank           | Rank           | number    | number      |
| Yes      | series tag     | title          | TITLE          | html      | html        |
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
series e:y4km-wdbp d:2014-01-01T00:00:00.000Z t:author="Smith, Ian, 1969-" t:title="Super shred: the big results diet: 4 weeks, 20 pounds, lose it faster!" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781250044532" m:rank=1

series e:y4km-wdbp d:2011-01-01T00:00:00.000Z t:author="Wilkerson, Isabel." t:title="The warmth of other suns: the epic story of America's great migration" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780679763888" m:rank=2

series e:y4km-wdbp d:2013-01-01T00:00:00.000Z t:author="Gladwell, Malcolm, 1963-" t:title="David and Goliath: underdogs, misfits, and the art of battling giants" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316204361" m:rank=3
```

## Meta Commands

```ls
metric m:rank p:integer l:Rank t:dataTypeName=number

entity e:y4km-wdbp l:"Libraries - Popular Nonfiction Titles at the Chicago Public Library" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/y4km-wdbp

property e:y4km-wdbp t:meta.view v:id=y4km-wdbp v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - Popular Nonfiction Titles at the Chicago Public Library" v:attribution="Chicago Public Library"

property e:y4km-wdbp t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:y4km-wdbp t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| rank | title                                                                                       | author                       | pub_year | catalog_record                                                                                                             | 
| ==== | =========================================================================================== | ============================ | ======== | ========================================================================================================================== | 
| 1    | Super shred: the big results diet: 4 weeks, 20 pounds, lose it faster!                      | Smith, Ian, 1969-            | 2014     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781250044532, null] | 
| 2    | The warmth of other suns: the epic story of America's great migration                       | Wilkerson, Isabel.           | 2011     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780679763888, null] | 
| 3    | David and Goliath: underdogs, misfits, and the art of battling giants                       | Gladwell, Malcolm, 1963-     | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780316204361, null] | 
| 4    | The monuments men: allied heroes, Nazi thieves and the greatest treasure hunt in history    | Edsel, Robert M.             | 2010     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781599951508, null] | 
| 5    | The devil in the white city: murder, magic, and madness at the fair that changed America    | Larson, Erik.                | 2004     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=0375725601, null]    | 
| 6    | Zealot: the life and times of Jesus of Nazareth                                             | Aslan, Reza.                 | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781400069224, null] | 
| 7    | Duty: memoirs of a Secretary at war                                                         | Gates, Robert Michael, 1943- | 2014     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780307959478, null] | 
| 8    | Lean in: women, work, and the will to lead                                                  | Sandberg, Sheryl.            | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780385349949, null] | 
| 9    | Orange is the new black: my year in a women's prison                                        | Kerman, Piper.               | 2011     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780385523394, null] | 
| 10   | The bully pulpit: Theodore Roosevelt, William Howard Taft, and the golden age of journalism | Goodwin, Doris Kearns.       | 2013     | [http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781416547860, null] | 
```