# Libraries - Popular Teen Titles at the Chicago Public Library

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-popular-teen-titles-at-the-chicago-public-library-28a24) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/izv6-vdkm) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/izv6-vdkm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/izv6-vdkm/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | izv6-vdkm |
| Name | Libraries - Popular Teen Titles at the Chicago Public Library |
| Attribution | Chicago Public Library |
| Category | Education |
| Tags | libraries, teens |
| Created | 2014-02-28T19:20:00Z |
| Publication Date | 2014-07-16T21:25:28Z |

## Description

Popular teen titles at the Chicago Public Library, January 2014

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
series e:izv6-vdkm d:2011-01-01T00:00:00.000Z t:author="Roth, Veronica." t:title=Divergent t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780062024022" m:rank=1

series e:izv6-vdkm d:2012-01-01T00:00:00.000Z t:author="Green, John, 1977-" t:title="The fault in our stars" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780525478812" m:rank=2

series e:izv6-vdkm d:2007-01-01T00:00:00.000Z t:author="Zusak, Markus." t:title="The book thief" t:catalog_record="http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780375842207" m:rank=3
```

## Meta Commands

```ls
metric m:rank p:integer l:RANK t:dataTypeName=number

entity e:izv6-vdkm l:"Libraries - Popular Teen Titles at the Chicago Public Library" t:attribution="Chicago Public Library" t:url=https://data.cityofchicago.org/api/views/izv6-vdkm

property e:izv6-vdkm t:meta.view v:id=izv6-vdkm v:category=Education v:attributionLink=http://chipublib.org v:averageRating=0 v:name="Libraries - Popular Teen Titles at the Chicago Public Library" v:attribution="Chicago Public Library"

property e:izv6-vdkm t:meta.view.owner v:id=jitu-w2pw v:screenName=GPeck v:displayName=GPeck

property e:izv6-vdkm t:meta.view.tableauthor v:id=jitu-w2pw v:screenName=GPeck v:roleName=editor v:displayName=GPeck
```

## Top Records

```ls
| rank | title                  | author             | pub_year | catalog_record                                                                                                     | 
| ==== | ====================== | ================== | ======== | ================================================================================================================== | 
| 1    | Divergent              | Roth, Veronica.    | 2011     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780062024022 | 
| 2    | The fault in our stars | Green, John, 1977- | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780525478812 | 
| 3    | The book thief         | Zusak, Markus.     | 2007     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780375842207 | 
| 4    | Mockingjay             | Collins, Suzanne.  | 2010     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780439023511 | 
| 5    | Allegiant              | Roth, Veronica.    | 2013     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780062024060 | 
| 6    | Insurgent              | Roth, Veronica.    | 2012     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780062024046 | 
| 7    | Catching fire          | Collins, Suzanne.  | 2009     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780439023498 | 
| 8    | The Hunger Games       | Collins, Suzanne.  | 2008     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9780545310581 | 
| 9    | Eleanor & Park         | Rowell, Rainbow.   | 2013     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781250012579 | 
| 10   | Fangirl                | Rowell, Rainbow.   | 2013     | http://chipublib.bibliocommons.com/search?suppress=true&custom_edit=false&custom_query=identifier%3A=9781250030955 | 
```