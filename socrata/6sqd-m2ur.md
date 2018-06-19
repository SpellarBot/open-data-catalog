# Heating Oil Regional Retail Prices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/heating-oil-regional-retail-prices) |
| Metadata | [Link](https://data.ct.gov/api/views/6sqd-m2ur) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/6sqd-m2ur/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/6sqd-m2ur/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | 6sqd-m2ur |
| Name | Heating Oil Regional Retail Prices |
| Created | 2014-03-13T19:16:42Z |
| Publication Date | 2017-01-05T18:13:12Z |

## Description

Connecticut Regional Retail Heating Oil Prices $/GALLON

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | ============== | ==================== | ==================== | ============= | ============= |
| Yes      | time           | date                 | Date                 | calendar_date | calendar_date |
| Yes      | numeric metric | fairfield_avg        | Fairfield-AVG        | number        | number        |
| Yes      | numeric metric | fairfield_high       | Fairfield- HIGH      | number        | number        |
| Yes      | numeric metric | fairfield_low        | Fairfield-LOW        | number        | number        |
| Yes      | numeric metric | hartford_avg         | Hartford- AVG        | number        | number        |
| Yes      | numeric metric | hartford_high        | Hartford-HIGH        | number        | number        |
| Yes      | numeric metric | hartford_low         | Hartford-LOW         | number        | number        |
| Yes      | numeric metric | litchfield_avg       | Litchfield-AVG       | number        | number        |
| Yes      | numeric metric | litchfield_high      | Litchfield-HIGH      | number        | number        |
| Yes      | numeric metric | litchfield_low       | Litchfield-LOW       | number        | number        |
| Yes      | numeric metric | middlesex_avg        | Middlesex-AVG        | number        | number        |
| Yes      | numeric metric | middlesex_high       | Middlesex-HIGH       | number        | number        |
| Yes      | numeric metric | middlesex_low        | Middlesex-LOW        | number        | number        |
| Yes      | numeric metric | new_haven_avg        | New Haven-AVG        | number        | number        |
| Yes      | numeric metric | new_haven_high       | New Haven-HIGH       | number        | number        |
| Yes      | numeric metric | new_haven_low        | New Haven-LOW        | number        | number        |
| Yes      | numeric metric | new_london_avg       | New London-AVG       | number        | number        |
| Yes      | numeric metric | new_london_high      | New London-HIGH      | number        | number        |
| Yes      | numeric metric | new_london_low       | New London-LOW       | number        | number        |
| Yes      | numeric metric | tolland_windham_avg  | Tolland/Windham-AVG  | number        | number        |
| Yes      | numeric metric | tolland_windham_high | Tolland/Windham-HIGH | number        | number        |
| Yes      | numeric metric | tolland_windham_low  | Tolland/Windham-LOW  | number        | number        |
| Yes      | numeric metric | statewide_high       | Statewide-AVG        | number        | number        |
| Yes      | numeric metric | statewide_avg        | Statewide-HIGH       | number        | number        |
| Yes      | numeric metric | statewide_low        | Statewide-LOW        | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:6sqd-m2ur d:2006-06-12T00:00:00.000Z m:new_london_low=2.519 m:new_haven_avg=2.509 m:statewide_low=2.28 m:fairfield_avg=2.708 m:litchfield_avg=2.557 m:middlesex_low=2.5 m:tolland_windham_low=2.479 m:tolland_windham_high=2.599 m:statewide_avg=2.899 m:hartford_avg=2.562 m:litchfield_low=2.38 m:new_london_avg=2.599 m:middlesex_avg=2.601 m:hartford_high=2.899 m:new_london_high=2.75 m:litchfield_high=2.659 m:new_haven_high=2.729 m:fairfield_high=2.899 m:middlesex_high=2.699 m:fairfield_low=2.499 m:new_haven_low=2.35 m:hartford_low=2.28 m:tolland_windham_avg=2.533 m:statewide_high=2.578

series e:6sqd-m2ur d:2006-07-10T00:00:00.000Z m:new_london_low=2.369 m:new_haven_avg=2.476 m:statewide_low=2.28 m:fairfield_avg=2.713 m:litchfield_avg=2.521 m:middlesex_low=2.43 m:tolland_windham_low=2.379 m:tolland_windham_high=2.549 m:statewide_avg=2.899 m:hartford_avg=2.521 m:litchfield_low=2.34 m:new_london_avg=2.535 m:middlesex_avg=2.585 m:hartford_high=2.799 m:new_london_high=2.65 m:litchfield_high=2.599 m:new_haven_high=2.689 m:fairfield_high=2.899 m:middlesex_high=2.699 m:fairfield_low=2.549 m:new_haven_low=2.299 m:hartford_low=2.28 m:tolland_windham_avg=2.475 m:statewide_high=2.547

series e:6sqd-m2ur d:2006-08-14T00:00:00.000Z m:new_london_low=2.529 m:new_haven_avg=2.561 m:statewide_low=2.37 m:fairfield_avg=2.764 m:litchfield_avg=2.577 m:middlesex_low=2.56 m:tolland_windham_low=2.509 m:tolland_windham_high=2.649 m:statewide_avg=3.09 m:hartford_avg=2.615 m:litchfield_low=2.37 m:new_london_avg=2.643 m:middlesex_avg=2.671 m:hartford_high=3.09 m:new_london_high=2.79 m:litchfield_high=2.699 m:new_haven_high=2.799 m:fairfield_high=2.899 m:middlesex_high=2.799 m:fairfield_low=2.649 m:new_haven_low=2.37 m:hartford_low=2.399 m:tolland_windham_avg=2.571 m:statewide_high=2.629
```

## Meta Commands

```ls
metric m:fairfield_avg p:float l:Fairfield-AVG t:dataTypeName=number

metric m:fairfield_high p:float l:"Fairfield- HIGH" t:dataTypeName=number

metric m:fairfield_low p:float l:Fairfield-LOW t:dataTypeName=number

metric m:hartford_avg p:float l:"Hartford- AVG" t:dataTypeName=number

metric m:hartford_high p:float l:Hartford-HIGH t:dataTypeName=number

metric m:hartford_low p:float l:Hartford-LOW t:dataTypeName=number

metric m:litchfield_avg p:float l:Litchfield-AVG t:dataTypeName=number

metric m:litchfield_high p:float l:Litchfield-HIGH t:dataTypeName=number

metric m:litchfield_low p:float l:Litchfield-LOW t:dataTypeName=number

metric m:middlesex_avg p:float l:Middlesex-AVG t:dataTypeName=number

metric m:middlesex_high p:float l:Middlesex-HIGH t:dataTypeName=number

metric m:middlesex_low p:float l:Middlesex-LOW t:dataTypeName=number

metric m:new_haven_avg p:float l:"New Haven-AVG" t:dataTypeName=number

metric m:new_haven_high p:float l:"New Haven-HIGH" t:dataTypeName=number

metric m:new_haven_low p:float l:"New Haven-LOW" t:dataTypeName=number

metric m:new_london_avg p:float l:"New London-AVG" t:dataTypeName=number

metric m:new_london_high p:float l:"New London-HIGH" t:dataTypeName=number

metric m:new_london_low p:float l:"New London-LOW" t:dataTypeName=number

metric m:tolland_windham_avg p:float l:Tolland/Windham-AVG t:dataTypeName=number

metric m:tolland_windham_high p:float l:Tolland/Windham-HIGH t:dataTypeName=number

metric m:tolland_windham_low p:float l:Tolland/Windham-LOW t:dataTypeName=number

metric m:statewide_high p:float l:Statewide-AVG t:dataTypeName=number

metric m:statewide_avg p:float l:Statewide-HIGH t:dataTypeName=number

metric m:statewide_low p:float l:Statewide-LOW t:dataTypeName=number

entity e:6sqd-m2ur l:"Heating Oil Regional Retail Prices" t:url=https://data.ct.gov/api/views/6sqd-m2ur

property e:6sqd-m2ur t:meta.view v:id=6sqd-m2ur v:averageRating=0 v:name="Heating Oil Regional Retail Prices"

property e:6sqd-m2ur t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:6sqd-m2ur t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| date                | fairfield_avg | fairfield_high | fairfield_low | hartford_avg | hartford_high | hartford_low | litchfield_avg | litchfield_high | litchfield_low | middlesex_avg | middlesex_high | middlesex_low | new_haven_avg | new_haven_high | new_haven_low | new_london_avg | new_london_high | new_london_low | tolland_windham_avg | tolland_windham_high | tolland_windham_low | statewide_high | statewide_avg | statewide_low | 
| =================== | ============= | ============== | ============= | ============ | ============= | ============ | ============== | =============== | ============== | ============= | ============== | ============= | ============= | ============== | ============= | ============== | =============== | ============== | =================== | ==================== | =================== | ============== | ============= | ============= | 
| 2006-06-12T00:00:00 | 2.708         | 2.899          | 2.499         | 2.562        | 2.899         | 2.280        | 2.557          | 2.659           | 2.380          | 2.601         | 2.699          | 2.500         | 2.509         | 2.729          | 2.350         | 2.599          | 2.750           | 2.519          | 2.533               | 2.599                | 2.479               | 2.578          | 2.899         | 2.280         | 
| 2006-07-10T00:00:00 | 2.713         | 2.899          | 2.549         | 2.521        | 2.799         | 2.280        | 2.521          | 2.599           | 2.340          | 2.585         | 2.699          | 2.430         | 2.476         | 2.689          | 2.299         | 2.535          | 2.650           | 2.369          | 2.475               | 2.549                | 2.379               | 2.547          | 2.899         | 2.280         | 
| 2006-08-14T00:00:00 | 2.764         | 2.899          | 2.649         | 2.615        | 3.090         | 2.399        | 2.577          | 2.699           | 2.370          | 2.671         | 2.799          | 2.560         | 2.561         | 2.799          | 2.370         | 2.643          | 2.790           | 2.529          | 2.571               | 2.649                | 2.509               | 2.629          | 3.090         | 2.370         | 
| 2006-09-05T00:00:00 | 2.721         | 2.849          | 2.599         | 2.557        | 2.890         | 2.260        | 2.535          | 2.699           | 2.380          | 2.603         | 2.699          | 2.420         | 2.507         | 2.749          | 2.269         | 2.617          | 2.730           | 2.459          | 2.507               | 2.599                | 2.389               | 2.576          | 2.890         | 2.260         | 
| 2006-09-11T00:00:00 | 2.683         | 2.799          | 2.499         | 2.492        | 2.790         | 2.250        | 2.455          | 2.599           | 2.330          | 2.559         | 2.699          | 2.400         | 2.443         | 2.699          | 2.179         | 2.551          | 2.699           | 2.309          | 2.453               | 2.549                | 2.329               | 2.517          | 2.799         | 2.179         | 
| 2006-09-18T00:00:00 | 2.617         | 2.799          | 2.499         | 2.407        | 2.790         | 1.990        | 2.389          | 2.599           | 2.180          | 2.493         | 2.649          | 2.399         | 2.384         | 2.689          | 2.029         | 2.407          | 2.599           | 2.059          | 2.321               | 2.449                | 2.250               | 2.437          | 2.799         | 1.990         | 
| 2006-09-25T00:00:00 | 2.562         | 2.799          | 2.399         | 2.331        | 2.690         | 1.990        | 2.303          | 2.459           | 2.160          | 2.433         | 2.649          | 2.199         | 2.355         | 2.689          | 2.020         | 2.361          | 2.499           | 2.119          | 2.255               | 2.399                | 2.179               | 2.380          | 2.799         | 1.990         | 
| 2006-10-02T00:00:00 | 2.522         | 2.599          | 2.399         | 2.315        | 2.699         | 1.990        | 2.281          | 2.459           | 2.090          | 2.410         | 2.599          | 2.250         | 2.340         | 2.599          | 2.049         | 2.355          | 2.499           | 2.199          | 2.265               | 2.399                | 2.179               | 2.362          | 2.699         | 1.990         | 
| 2006-10-10T00:00:00 | 2.507         | 2.699          | 2.349         | 2.315        | 2.690         | 2.050        | 2.261          | 2.459           | 2.090          | 2.362         | 2.549          | 2.200         | 2.329         | 2.599          | 2.029         | 2.317          | 2.499           | 2.199          | 2.227               | 2.349                | 2.089               | 2.345          | 2.699         | 2.029         | 
| 2006-10-16T00:00:00 | 2.508         | 2.699          | 2.349         | 2.327        | 2.699         | 1.990        | 2.273          | 2.459           | 2.150          | 2.370         | 2.549          | 2.200         | 2.323         | 2.599          | 1.999         | 2.343          | 2.499           | 2.199          | 2.247               | 2.349                | 2.189               | 2.352          | 2.699         | 1.990         | 
```