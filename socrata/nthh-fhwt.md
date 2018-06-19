# Cargo Tonnage by Airport, Port Authority of NY NJ: Beginning 1977

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/cargo-tonnage-by-airport-port-authority-of-ny-nj-beginning-1977) |
| Metadata | [Link](https://data.ny.gov/api/views/nthh-fhwt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/nthh-fhwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/nthh-fhwt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | nthh-fhwt |
| Name | Cargo Tonnage by Airport, Port Authority of NY NJ: Beginning 1977 |
| Attribution | The Port Authority of New York and New Jersey |
| Category | Transportation |
| Tags | domestic cargo, international cargo, airport cargo |
| Created | 2013-05-08T17:20:45Z |
| Publication Date | 2016-06-30T19:33:06Z |

## Description

The dataset presented in this forum is monthly data. The Port Authority collects monthly data for domestic and international cargo, flight, passengers and aircraft equipment type from each carrier at PANYNJ-operated airports. The data is aggregated and forms the basis for estimating flight fees, parking, concession, and PFC revenues at the Port Authority Airports.

## Columns

```ls
| Included | Schema Type    | Field Name    | Name                  | Data Type | Render Type |
| ======== | ============== | ============= | ===================== | ========= | =========== |
| Yes      | series tag     | airport       | Airport               | text      | text        |
| No       |                | year          | Year                  | number    | number      |
| No       |                | month         | Month                 | text      | text        |
| Yes      | numeric metric | domestic      | Domestic Tonnage      | number    | number      |
| Yes      | numeric metric | international | International Tonnage | number    | number      |
| Yes      | numeric metric | total         | Total Tonnage         | number    | number      |
```

## Time Field

```ls
Value = year-month
Format & Zone = yyyy-MMM
```

## Series Fields

```ls
Excluded Fields = year,month
```

## Data Commands

```ls
series e:nthh-fhwt d:2015-01-01T00:00:00.000Z t:airport=EWR m:total=55658 m:international=20201 m:domestic=35457

series e:nthh-fhwt d:2015-02-01T00:00:00.000Z t:airport=EWR m:total=55182 m:international=21497 m:domestic=33685

series e:nthh-fhwt d:2015-03-01T00:00:00.000Z t:airport=EWR m:total=59641 m:international=24542 m:domestic=35099
```

## Meta Commands

```ls
metric m:domestic p:integer l:"Domestic Tonnage" d:"Number of arriving plus departing short tons of cargo between Port Authority airports and other United States Airports." t:dataTypeName=number

metric m:international p:integer l:"International Tonnage" d:"Number of arriving plus departing short tons of cargo between Port Authority airports and other international Airports." t:dataTypeName=number

metric m:total p:integer l:"Total Tonnage" d:"Number of domestic plus international short tons of cargo. It includes cargo carried by Cargo only Airlines such as UPS and FEDEX and cargo carried in the belly of passenger aircrafts" t:dataTypeName=number

entity e:nthh-fhwt l:"Cargo Tonnage by Airport, Port Authority of NY NJ: Beginning 1977" t:attribution="The Port Authority of New York and New Jersey" t:url=https://data.ny.gov/api/views/nthh-fhwt

property e:nthh-fhwt t:meta.view v:id=nthh-fhwt v:category=Transportation v:averageRating=0 v:name="Cargo Tonnage by Airport, Port Authority of NY NJ: Beginning 1977" v:attribution="The Port Authority of New York and New Jersey"

property e:nthh-fhwt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:nthh-fhwt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:nthh-fhwt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| airport | year | month | domestic | international | total | 
| ======= | ==== | ===== | ======== | ============= | ===== | 
| EWR     | 2015 | Jan   | 35457    | 20201         | 55658 | 
| EWR     | 2015 | Feb   | 33685    | 21497         | 55182 | 
| EWR     | 2015 | Mar   | 35099    | 24542         | 59641 | 
| EWR     | 2015 | Apr   | 36625    | 21022         | 57647 | 
| EWR     | 2015 | May   | 36029    | 20666         | 56695 | 
| EWR     | 2015 | Jun   | 34441    | 21285         | 55726 | 
| EWR     | 2015 | Jul   | 36978    | 21214         | 58191 | 
| EWR     | 2015 | Aug   | 34449    | 19635         | 54084 | 
| EWR     | 2015 | Sep   | 38436    | 19262         | 57699 | 
| EWR     | 2015 | Oct   | 40430    | 21204         | 61634 | 
```