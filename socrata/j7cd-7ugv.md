# Election Information

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/election-information) |
| Metadata | [Link](https://data.hartford.gov/api/views/j7cd-7ugv) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/j7cd-7ugv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/j7cd-7ugv/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | j7cd-7ugv |
| Name | Election Information |
| Attribution | City of Hartford |
| Category | Community |
| Tags | hartford, vote, election, registrar of voters |
| Created | 2014-07-29T12:34:43Z |
| Publication Date | 2015-11-18T02:12:39Z |

## Description

Election Information for years 2005 - 2015

## Columns

```ls
| Included | Schema Type    | Field Name  | Name        | Data Type | Render Type |
| ======== | ============== | =========== | =========== | ========= | =========== |
| Yes      | series tag     | description | Description | text      | text        |
| Yes      | series tag     | web_link    | Web_Link    | url       | url         |
| Yes      | time           | year        | Year        | number    | number      |
| Yes      | numeric metric | sortorder   | SortOrder   | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j7cd-7ugv d:2010-01-01T00:00:00.000Z t:description="Candidate Votes by District Democratic Town Committee Primary in Assembly Districts# 4,5, and 7 - March 2, 2010" t:web_link=http://gis1.hartford.gov/images/votingresults/city1.pdf m:sortorder=112

series e:j7cd-7ugv d:2010-01-01T00:00:00.000Z t:description="Federal State District Election November 2, 2010" t:web_link=http://gis1.hartford.gov/images/votingresults/FederalStateDistrictElection2010.pdf m:sortorder=113

series e:j7cd-7ugv d:2011-01-01T00:00:00.000Z t:description="Municipal Election November 8, 2011" t:web_link=http://gis1.hartford.gov/images/votingresults/FederalStateDistrictElection2011.pdf m:sortorder=115
```

## Meta Commands

```ls
metric m:sortorder p:integer l:SortOrder t:dataTypeName=number

entity e:j7cd-7ugv l:"Election Information" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/j7cd-7ugv

property e:j7cd-7ugv t:meta.view v:id=j7cd-7ugv v:category=Community v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Election Information" v:attribution="City of Hartford"

property e:j7cd-7ugv t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:j7cd-7ugv t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:displayName=Brett

property e:j7cd-7ugv t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```

## Top Records

```ls
| description                                                                                                     | web_link                                                                                   | year | sortorder | 
| =============================================================================================================== | ========================================================================================== | ==== | ========= | 
| Candidate Votes by District Democratic Town Committee Primary in Assembly Districts# 4,5, and 7 - March 2, 2010 | [http://gis1.hartford.gov/images/votingresults/city1.pdf, null]                            | 2010 | 112       | 
| Federal State District Election November 2, 2010                                                                | [http://gis1.hartford.gov/images/votingresults/FederalStateDistrictElection2010.pdf, null] | 2010 | 113       | 
| Municipal Election November 8, 2011                                                                             | [http://gis1.hartford.gov/images/votingresults/FederalStateDistrictElection2011.pdf, null] | 2011 | 115       | 
| Democratic State District and Municipal Primary August 4, 2012                                                  | [http://gis1.hartford.gov/images/votingresults/FederalStateDistrictElection2012.pdf, null] | 2012 | 116       | 
| Municipal Election November 8, 2005                                                                             | [http://gis1.hartford.gov/images/votingresults/Election11-05.pdf, null]                    | 2005 | 106       | 
| State Municipal Election November 3, 1998                                                                       | [http://gis1.hartford.gov/images/votingresults/Election1998.pdf, null]                     | 1998 | 103       | 
| Federal State Municipal Election November 7, 2000                                                               | [http://gis1.hartford.gov/images/votingresults/Election2000.pdf, null]                     | 2000 | 104       | 
| State Municipal Election November 5, 2002                                                                       | [http://gis1.hartford.gov/images/votingresults/Election2002.pdf, null]                     | 2002 | 105       | 
| State Election November 4,1994                                                                                  | [http://gis1.hartford.gov/images/votingresults/Election1994.pdf, null]                     | 1994 | 101       | 
| Federal State Election November 5, 1996                                                                         | [http://gis1.hartford.gov/images/votingresults/Election1996.pdf, null]                     | 1996 | 102       | 
```