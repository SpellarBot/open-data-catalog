# Table 1.06 RESIDENT POPULATION, BY COUNTY 2000 TO 2014 (as of July 1)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-1-06-resident-population-by-county-2000-to-2013-as-of-july-1) |
| Metadata | [Link](https://data.hawaii.gov/api/views/hnpb-2rfi) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/hnpb-2rfi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/hnpb-2rfi/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | hnpb-2rfi |
| Name | Table 1.06 RESIDENT POPULATION, BY COUNTY 2000 TO 2014 (as of July 1) |
| Attribution | Department of Economic Development and Tourism |
| Category | Government-Wide Support |
| Tags | population |
| Created | 2012-08-27T19:49:56Z |
| Publication Date | 2015-10-27T00:48:37Z |

## Description

* Based on place of usual residence, regardless of physical location on the estimate or census date.  									
* Includes military personnel stationed or homeported in Hawaii and residents temporarily absent; excludes visitors present									
* Maui County includes Kalawao County (Kalaupapa Settlement).  Kalawao had 147 in 2000, 90 in 2010 and 89 in 2014. 									
* Population estimates for 2000 through 2009 were revised based upon the April 1, 2010  figures which were released September 28, 2011.  									
* Population estimates after April 1, 2010 were based on revisions released in March 2015 and may differ somewhat from earlier figures cited in other tables. 									
     Source:  U.S. Bureau of the Census

## Columns

```ls
| Included | Schema Type    | Field Name                  | Name                        | Data Type | Render Type |
| ======== | ============== | =========================== | =========================== | ========= | =========== |
| Yes      | time           | year                        | Year                        | number    | text        |
| Yes      | numeric metric | state_total                 | State total                 | number    | number      |
| Yes      | numeric metric | city_and_county_of_honolulu | City and County of Honolulu | number    | number      |
| Yes      | numeric metric | hawaii_county               | Hawaii County               | number    | number      |
| Yes      | numeric metric | kauai_county                | Kauai County                | number    | number      |
| Yes      | numeric metric | maui_county                 | Maui County                 | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hnpb-2rfi d:2000-01-01T00:00:00.000Z m:state_total=1213519 m:hawaii_county=149244 m:city_and_county_of_honolulu=876629 m:maui_county=129078 m:kauai_county=58568

series e:hnpb-2rfi d:2001-01-01T00:00:00.000Z m:state_total=1225948 m:hawaii_county=151690 m:city_and_county_of_honolulu=882755 m:maui_county=132428 m:kauai_county=59075

series e:hnpb-2rfi d:2002-01-01T00:00:00.000Z m:state_total=1239613 m:hawaii_county=154576 m:city_and_county_of_honolulu=890473 m:maui_county=134583 m:kauai_county=59981
```

## Meta Commands

```ls
metric m:state_total p:integer l:"State total" t:dataTypeName=number

metric m:city_and_county_of_honolulu p:integer l:"City and County of Honolulu" t:dataTypeName=number

metric m:hawaii_county p:integer l:"Hawaii County" t:dataTypeName=number

metric m:kauai_county p:integer l:"Kauai County" t:dataTypeName=number

metric m:maui_county p:integer l:"Maui County" t:dataTypeName=number

entity e:hnpb-2rfi l:"Table 1.06 RESIDENT POPULATION, BY COUNTY 2000 TO 2014 (as of July 1)" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/hnpb-2rfi

property e:hnpb-2rfi t:meta.view v:id=hnpb-2rfi v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/dbedt/databook v:averageRating=0 v:name="Table 1.06 RESIDENT POPULATION, BY COUNTY 2000 TO 2014 (as of July 1)" v:attribution="Department of Economic Development and Tourism"

property e:hnpb-2rfi t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:hnpb-2rfi t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:hnpb-2rfi t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | state_total | city_and_county_of_honolulu | hawaii_county | kauai_county | maui_county | 
| ==== | =========== | =========================== | ============= | ============ | =========== | 
| 2000 | 1213519     | 876629                      | 149244        | 58568        | 129078      | 
| 2001 | 1225948     | 882755                      | 151690        | 59075        | 132428      | 
| 2002 | 1239613     | 890473                      | 154576        | 59981        | 134583      | 
| 2003 | 1251154     | 894311                      | 158442        | 60805        | 137596      | 
| 2004 | 1273569     | 907997                      | 162852        | 62095        | 140625      | 
| 2005 | 1292729     | 918181                      | 168237        | 62863        | 143448      | 
| 2006 | 1309731     | 926954                      | 173536        | 63465        | 145776      | 
| 2007 | 1315675     | 925335                      | 177733        | 64490        | 148117      | 
| 2008 | 1332213     | 933680                      | 181506        | 65603        | 151424      | 
| 2009 | 1346717     | 943177                      | 183629        | 66518        | 153393      | 
```