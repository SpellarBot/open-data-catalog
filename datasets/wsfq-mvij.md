# BPD Part 1 Victim Based Crime Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/bpd-part-1-victim-based-crime-data-66843) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/wsfq-mvij) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/wsfq-mvij/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/wsfq-mvij/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | wsfq-mvij |
| Name | BPD Part 1 Victim Based Crime Data |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | crime, police, victim |
| Created | 2011-12-15T15:48:42Z |
| Publication Date | 2017-04-20T16:55:31Z |

## Description

All BPD data on Open Baltimore is preliminary data and subject to change.  The information presented through Open Baltimore represents Part I victim based crime data. The data do not represent statistics submitted to the FBI's Uniform Crime Report (UCR); therefore any comparisons are strictly prohibited. For further clarification of UCR data, please visit http://www.fbi.gov/about-us/cjis/ucr/ucr. Please note that this data is preliminary and subject to change. Prior month data is likely to show changes when it is refreshed on a monthly basis.  All data is geocoded to the approximate latitude/longitude location of the incident and excludes those records for which an address could not be geocoded. Any attempt to match the approximate location of the incident to an exact address is strictly prohibited.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | time           | crimedate       | CrimeDate       | calendar_date | calendar_date |
| Yes      | series tag     | crimetime       | CrimeTime       | text          | text          |
| Yes      | series tag     | crimecode       | CrimeCode       | text          | text          |
| Yes      | series tag     | location        | Location        | text          | text          |
| Yes      | series tag     | description     | Description     | text          | text          |
| Yes      | series tag     | inside_outside  | Inside/Outside  | text          | text          |
| Yes      | series tag     | weapon          | Weapon          | text          | text          |
| Yes      | numeric metric | post            | Post            | number        | number        |
| Yes      | series tag     | district        | District        | text          | text          |
| Yes      | series tag     | neighborhood    | Neighborhood    | text          | text          |
| Yes      | series tag     | premise         | Premise         | text          | text          |
| Yes      | numeric metric | total_incidents | Total Incidents | number        | number        |
```

## Time Field

```ls
Value = crimedate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:wsfq-mvij d:2017-04-15T00:00:00.000Z t:premise=STREET t:location="3500 FAIRVIEW AVE" t:description="AGG. ASSAULT" t:weapon=OTHER t:neighborhood="Forest Park" t:inside_outside=O t:crimetime=23:19:00 t:district=NORTHWESTERN t:crimecode=4C m:total_incidents=1 m:post=642

series e:wsfq-mvij d:2017-04-15T00:00:00.000Z t:premise=OTHER/RESI t:location="3600 BROOKLYN AVE" t:description=BURGLARY t:neighborhood=Brooklyn t:inside_outside=I t:crimetime=23:05:00 t:district=SOUTHERN t:crimecode=5A m:total_incidents=1 m:post=913

series e:wsfq-mvij d:2017-04-15T00:00:00.000Z t:premise=STREET t:location="1600 W LANVALE ST" t:description="COMMON ASSAULT" t:weapon=HANDS t:neighborhood="Harlem Park" t:inside_outside=O t:crimetime=23:02:00 t:district=WESTERN t:crimecode=4E m:total_incidents=1 m:post=713
```

## Meta Commands

```ls
metric m:post p:long l:Post t:dataTypeName=number

metric m:total_incidents p:long l:"Total Incidents" t:dataTypeName=number

entity e:wsfq-mvij l:"BPD Part 1 Victim Based Crime Data" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/wsfq-mvij

property e:wsfq-mvij t:meta.view v:id=wsfq-mvij v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="BPD Part 1 Victim Based Crime Data" v:attribution="Baltimore Police Department"

property e:wsfq-mvij t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wsfq-mvij t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:wsfq-mvij t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| crimedate           | crimetime | crimecode | location             | description      | inside_outside | weapon  | post | district     | neighborhood              | premise    | total_incidents | 
| =================== | ========= | ========= | ==================== | ================ | ============== | ======= | ==== | ============ | ========================= | ========== | =============== | 
| 2017-04-15T00:00:00 | 23:19:00  | 4C        | 3500 FAIRVIEW AVE    | AGG. ASSAULT     | O              | OTHER   | 642  | NORTHWESTERN | Forest Park               | STREET     | 1               | 
| 2017-04-15T00:00:00 | 23:05:00  | 5A        | 3600 BROOKLYN AVE    | BURGLARY         | I              |         | 913  | SOUTHERN     | Brooklyn                  | OTHER/RESI | 1               | 
| 2017-04-15T00:00:00 | 23:02:00  | 4E        | 1600 W LANVALE ST    | COMMON ASSAULT   | O              | HANDS   | 713  | WESTERN      | Harlem Park               | STREET     | 1               | 
| 2017-04-15T00:00:00 | 23:02:00  | 4E        | 1600 W LANVALE ST    | COMMON ASSAULT   | O              | HANDS   | 713  | WESTERN      | Harlem Park               | STREET     | 1               | 
| 2017-04-15T00:00:00 | 21:30:00  | 4E        | 1000 SCOTT ST        | COMMON ASSAULT   | I              | HANDS   | 932  | SOUTHERN     | Washington Village/Pigtow | ROW/TOWNHO | 1               | 
| 2017-04-15T00:00:00 | 21:23:00  | 3AF       | 3400 PULASKI HWY     | ROBBERY - STREET | O              | FIREARM | 223  | SOUTHEASTERN | Baltimore Highlands       | STREET     | 1               | 
| 2017-04-15T00:00:00 | 21:10:00  | 4E        | 1200 COOKS LN        | COMMON ASSAULT   |                | HANDS   | 823  | SOUTHWESTERN |                           |            | 1               | 
| 2017-04-15T00:00:00 | 20:30:00  | 4E        | 3600 BUENA VISTA AVE | COMMON ASSAULT   | O              | HANDS   | 531  | NORTHERN     | Hampden                   | ALLEY      | 1               | 
| 2017-04-15T00:00:00 | 20:26:00  | 7A        | 900 S HANOVER ST     | AUTO THEFT       | O              |         | 942  | SOUTHERN     | Federal Hill              | STREET     | 1               | 
| 2017-04-15T00:00:00 | 20:00:00  | 3B        | 100 WASHBURN AVE     | ROBBERY - STREET | O              |         | 913  | SOUTHERN     | Brooklyn                  | STREET     | 1               | 
```