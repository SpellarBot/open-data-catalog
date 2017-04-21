# Libraries - Popular Kids Titles at the Chicago Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-popular-kids-titles-at-the-chicago-public-library-7199d) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/acyw-87uj) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/acyw-87uj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/acyw-87uj/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | acyw-87uj |
| Name | Libraries - Popular Kids Titles at the Chicago Public Library |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, kids |
| Created | 2014-02-28T19:16:47Z |
| Publication Date | 2014-07-16T21:26:46Z |

## Description

Popular kids titles at the Chicago Public Library, January 2014

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | numeric metric | rank           | RANK           | number    | number      |
| Yes      | series tag     | title          | TITLE          | text      | text        |
| Yes      | series tag     | author         | AUTHOR         | text      | text        |
| Yes      | time           | pub_year       | PUB YEAR       | number    | text        |
| Yes      | series tag     | catalog_record | CATALOG RECORD | text      | text        |
```

## Time Field

```ls
Value = pub_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:acyw-87uj d:2011-01-01T00:00:00.000Z t:author="Farshtey, Greg." t:title="Lego Ninjago, masters of spinjitzu.   #2, Mask of the Sensei" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781597073110" m:rank=1

series e:acyw-87uj d:2013-01-01T00:00:00.000Z t:author="Kinney, Jeff." t:title="Diary of a wimpy kid: hard luck" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781419711329" m:rank=2

series e:acyw-87uj d:2013-01-01T00:00:00.000Z t:author="Riordan, Rick." t:title="The house of Hades" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781423146728" m:rank=3
```

## Meta Commands

```ls
metric m:rank p:integer l:RANK t:dataTypeName=number

entity e:acyw-87uj l:"Libraries - Popular Kids Titles at the Chicago Public Library" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/acyw-87uj

property e:acyw-87uj t:meta.view v:id=acyw-87uj v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - Popular Kids Titles at the Chicago Public Library" v:attribution="Chicago Public Library"

property e:acyw-87uj t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:displayName=GPeck

property e:acyw-87uj t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```

## Top Records

```ls
| rank | title                                                      | author               | pub_year | catalog_record                                                                                                     | 
| ==== | ========================================================== | ==================== | ======== | ================================================================================================================== | 
| 1    | Lego Ninjago, masters of spinjitzu. #2, Mask of the Sensei | Farshtey, Greg.      | 2011     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781597073110 | 
| 2    | Diary of a wimpy kid: hard luck                            | Kinney, Jeff.        | 2013     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781419711329 | 
| 3    | The house of Hades                                         | Riordan, Rick.       | 2013     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781423146728 | 
| 4    | Wonder                                                     | Palacio, R. J.       | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780375869020 | 
| 5    | Batman: meet the super heroes                              | Teitelbaum, Michael. | 2010     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061878589 | 
| 6    | Batman. Reptile rampage                                    | Turner, Katharine.   | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061885211 | 
| 7    | Batman versus Man-Bat                                      | Bright, J. E.        | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061885235 | 
| 8    | Batman: going ape                                          | Sutton, Laurie.      | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061885228 | 
| 9    | Batman's friends and foes                                  | Hapka, Cathy.        | 2008     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061561900 | 
| 10   | Transformers. training day Hunt for the Decepticons:       | Teitelbaum, Michael. | 2011     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780061991776 | 
```