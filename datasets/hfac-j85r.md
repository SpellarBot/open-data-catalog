# Directory of Senior News Services in NYCHA Journal

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/directory-of-senior-news-services-in-nycha-journal-a941b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hfac-j85r) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hfac-j85r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hfac-j85r/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hfac-j85r |
| Name | Directory of Senior News Services in NYCHA Journal |
| Attribution | Department of City Planning (DCP) |
| Category | Social Services |
| Tags | dcp, city, planning, senior, norc, nycha, journal, news, article |
| Created | 2013-02-13T19:55:47Z |
| Publication Date | 2013-02-13T19:57:48Z |

## Description

Details of News Articles targeted for Seniors that were published in NYCHA Journal

## Columns

```ls
| Included | Schema Type | Field Name        | Name              | Data Type | Render Type |
| ======== | =========== | ================= | ================= | ========= | =========== |
| No       |             | year              | Year              | number    | text        |
| No       |             | month             | Month             | text      | text        |
| Yes      | series tag  | senior_news_topic | Senior News Topic | text      | text        |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:hfac-j85r d:2010-01-01T00:00:00.000Z t:senior_news_topic="Free Tax assistance/EITC" m:row_number.hfac-j85r=1

series e:hfac-j85r d:2010-02-01T00:00:00.000Z t:senior_news_topic="Identity Theft Prevention" m:row_number.hfac-j85r=2

series e:hfac-j85r d:2010-02-01T00:00:00.000Z t:senior_news_topic="Do Not Call Registry" m:row_number.hfac-j85r=3
```

## Meta Commands

```ls
metric m:row_number.hfac-j85r p:long l:"Row Number"

entity e:hfac-j85r l:"Directory of Senior News Services in NYCHA Journal" t:attribution="Department of City Planning (DCP)" t:url=https://data.cityofnewyork.us/api/views/hfac-j85r

property e:hfac-j85r t:meta.view v:id=hfac-j85r v:category="Social Services" v:attributionLink=http://www.nyc.gov/html/dcp/pdf/pub/conplan12_amended_vol2.pdf v:averageRating=0 v:name="Directory of Senior News Services in NYCHA Journal" v:attribution="Department of City Planning (DCP)"

property e:hfac-j85r t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hfac-j85r t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| year | month    | senior_news_topic                                                                                                                        | 
| ==== | ======== | ======================================================================================================================================== | 
| 2010 | January  | Free Tax assistance/EITC                                                                                                                 | 
| 2010 | February | Identity Theft Prevention                                                                                                                | 
| 2010 | February | Do Not Call Registry                                                                                                                     | 
| 2010 | March    | Medicare Advantage Open Enrollment Period, in which all people with Medicare can again switch their Medicare plan choice ? ends in March | 
| 2010 | April    | Food Card                                                                                                                                | 
| 2010 | May      | Free Summer Events/Concerts                                                                                                              | 
| 2010 | June     | SSA/SSI Stimulus Checks                                                                                                                  | 
| 2010 | July     | Emergency Cooling Centers                                                                                                                | 
| 2010 | July     | West Nile Virus Prevention                                                                                                               | 
| 2010 | August   | Transportation Benefits                                                                                                                  | 
```