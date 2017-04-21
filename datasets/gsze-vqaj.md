# Urban Environment & Transit 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/urban-environment-transit-2010-c93c2) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/gsze-vqaj) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/gsze-vqaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/gsze-vqaj/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | gsze-vqaj |
| Name | Urban Environment & Transit 2010 |
| Attribution | Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore |
| Category | Neighborhoods |
| Tags | transit, environment, census |
| Created | 2013-02-26T13:45:23Z |
| Publication Date | 2014-04-04T00:02:28Z |

## Description

Baltimore City is home to many green spaces, parks, and waterways. Some of the more widely recognized locations include the Inner Harbor, Middle Branch, Druid Hill , Gwynns Falls and Herring Run Parks. City residents in particular value access to green spaces as a place to recreate, exercise and congregate, but the City??_??s green spaces serve a vital role in ensuring clean air and water for long term urbansustainability. Baltimore neighborhoods actively participate in increasing access to green spaces through tree planting and other watershed protection activities such as stream clean-ups. Urban living also enables residents the option to choose alternative means of transportation to reduce vehicle miles traveled by car. The City is already served by numerous modes of mass transit including MARC, metro, light rail, the Charm City Circulator, and bus lines. BNIA-JFI tracks eight indicators to measure the City??_??s urban environment and transit. These indicators are categorized into the following categories: air quality and hazardous waste; tree canopy, alternative transportation mode use; and travel time to work.

## Columns

```ls
| Included | Schema Type    | Field Name | Name      | Data Type | Render Type |
| ======== | ============== | ========== | ========= | ========= | =========== |
| Yes      | series tag     | csa2010    | CSA2010   | text      | text        |
| Yes      | numeric metric | trav14m10  | trav14m10 | number    | number      |
| Yes      | numeric metric | trav29m10  | trav29m10 | number    | number      |
| Yes      | numeric metric | trav44m10  | trav44m10 | number    | number      |
| Yes      | numeric metric | trav45m10  | trav45m10 | number    | number      |
| Yes      | numeric metric | nocar10    | nocar10   | number    | number      |
| Yes      | numeric metric | transit10  | transit10 | number    | number      |
| Yes      | numeric metric | otherm10   | otherm10  | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gsze-vqaj d:2010-01-01T00:00:00.000Z t:csa2010="Allendale/Irvington/S. Hilton" m:transit10=17.15 m:trav14m10=12.91 m:trav29m10=40.23 m:trav45m10=19.47 m:nocar10=24.17 m:otherm10=7.02 m:trav44m10=27.39

series e:gsze-vqaj d:2010-01-01T00:00:00.000Z t:csa2010="Beechfield/Ten Hills/West Hills" m:transit10=14.03 m:trav14m10=13.54 m:trav29m10=43.52 m:trav45m10=15.75 m:nocar10=18.97 m:otherm10=4.93 m:trav44m10=27.19

series e:gsze-vqaj d:2010-01-01T00:00:00.000Z t:csa2010=Belair-Edison m:transit10=20.58 m:trav14m10=9.14 m:trav29m10=41.08 m:trav45m10=21.21 m:nocar10=27.6 m:otherm10=7.02 m:trav44m10=28.58
```

## Meta Commands

```ls
metric m:trav14m10 p:float l:trav14m10 t:dataTypeName=number

metric m:trav29m10 p:float l:trav29m10 t:dataTypeName=number

metric m:trav44m10 p:float l:trav44m10 t:dataTypeName=number

metric m:trav45m10 p:float l:trav45m10 t:dataTypeName=number

metric m:nocar10 p:float l:nocar10 t:dataTypeName=number

metric m:transit10 p:float l:transit10 t:dataTypeName=number

metric m:otherm10 p:float l:otherm10 t:dataTypeName=number

entity e:gsze-vqaj l:"Urban Environment & Transit 2010" t:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore" t:url=https://data.baltimorecity.gov/api/views/gsze-vqaj

property e:gsze-vqaj t:meta.view v:id=gsze-vqaj v:category=Neighborhoods v:attributionLink=http://www.bniajfi.org/ v:averageRating=0 v:name="Urban Environment & Transit 2010" v:attribution="Baltimore Neighborhood Indicators Alliance-Jacob France Institute at the University of Baltimore"

property e:gsze-vqaj t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:gsze-vqaj t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:gsze-vqaj t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| csa2010                           | trav14m10 | trav29m10          | trav44m10 | trav45m10 | nocar10            | transit10          | otherm10           | 
| ================================= | ========= | ================== | ========= | ========= | ================== | ================== | ================== | 
| Allendale/Irvington/S. Hilton     | 12.91     | 40.229999999999997 | 27.39     | 19.47     | 24.17              | 17.149999999999999 | 7.02               | 
| Beechfield/Ten Hills/West Hills   | 13.54     | 43.52              | 27.19     | 15.75     | 18.97              | 14.03              | 4.93               | 
| Belair-Edison                     | 9.14      | 41.08              | 28.58     | 21.21     | 27.6               | 20.58              | 7.02               | 
| Brooklyn/Curtis Bay/Hawkins Point | 22.81     | 31.94              | 24.69     | 20.56     | 19.829999999999998 | 13.57              | 6.27               | 
| Canton                            | 22.18     | 45.07              | 22.62     | 10.14     | 18.399999999999999 | 7.5                | 10.9               | 
| Cedonia/Frankford                 | 12.04     | 39.159999999999997 | 28.24     | 20.57     | 21.74              | 16.98              | 4.76               | 
| Cherry Hill                       | 23.21     | 30.58              | 27.16     | 19.04     | 37.229999999999997 | 32.5               | 4.7300000000000004 | 
| Chinquapin Park/Belvedere         | 17.97     | 40.69              | 25.5      | 15.84     | 18.3               | 8.3000000000000007 | 10                 | 
| Claremont/Armistead               | 13.35     | 32.49              | 31.09     | 23.07     | 23.98              | 17.05              | 6.92               | 
| Clifton-Berea                     | 15.56     | 32.82              | 25.09     | 26.53     | 43.5               | 35.24              | 8.26               | 
```