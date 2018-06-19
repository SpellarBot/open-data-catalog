# Council District 11: City-Owned Properties Zoned Residential

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/council-district-11-city-owned-properties-zoned-residential) |
| Metadata | [Link](https://data.lacity.org/api/views/hcw6-f2zh) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/hcw6-f2zh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/hcw6-f2zh/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | hcw6-f2zh |
| Name | Council District 11: City-Owned Properties Zoned Residential |
| Attribution | Juan Vasquez |
| Created | 2017-02-01T23:26:04Z |
| Publication Date | 2017-02-02T17:57:49Z |

## Description

Council District 11: City-Owned Properties Zoned Residential

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | council_district | Council District | text      | number      |
| No       |                | address          | Address          | text      | text        |
| Yes      | series tag     | jurisdiction     | Jurisdiction     | text      | text        |
| Yes      | numeric metric | square_footage   | Square Footage   | number    | number      |
| Yes      | series tag     | parcel_number    | Parcel Number    | text      | number      |
| Yes      | series tag     | property_class   | Property Class   | text      | text        |
| Yes      | series tag     | property_status  | Property Status  | text      | text        |
| Yes      | series tag     | zoning           | Zoning           | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:hcw6-f2zh d:2017-02-01T23:26:05.000Z t:property_status=Owned t:property_class="Vacant Land" t:council_district=11 t:jurisdiction=Airports t:parcel_number=4128005910 t:zoning=* m:square_footage=4984.464626

series e:hcw6-f2zh d:2017-02-01T23:26:05.000Z t:property_status=Owned t:property_class="Vacant Land" t:council_district=11 t:jurisdiction=Airports t:parcel_number=4128005901 t:zoning=* m:square_footage=5006.466392

series e:hcw6-f2zh d:2017-02-01T23:26:05.000Z t:property_status=Owned t:property_class="Residential Improved" t:council_district=11 t:jurisdiction="General Services" t:parcel_number=4239024900 t:zoning=RD1.5-1 m:square_footage=5200.7814
```

## Meta Commands

```ls
metric m:square_footage p:double l:"Square Footage" t:dataTypeName=number

entity e:hcw6-f2zh l:"Council District 11: City-Owned Properties Zoned Residential" t:attribution="Juan Vasquez" t:url=https://data.lacity.org/api/views/hcw6-f2zh

property e:hcw6-f2zh t:meta.view v:id=hcw6-f2zh v:averageRating=0 v:name="Council District 11: City-Owned Properties Zoned Residential" v:attribution="Juan Vasquez"

property e:hcw6-f2zh t:meta.view.owner v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:displayName=JuanSVas

property e:hcw6-f2zh t:meta.view.tableauthor v:id=yv94-nsgm v:profileImageUrlMedium=/api/users/yv94-nsgm/profile_images/THUMB v:profileImageUrlLarge=/api/users/yv94-nsgm/profile_images/LARGE v:screenName=JuanSVas v:profileImageUrlSmall=/api/users/yv94-nsgm/profile_images/TINY v:roleName=publisher v:displayName=JuanSVas
```

## Top Records

```ls
| :updated_at | council_district | address               | jurisdiction     | square_footage | parcel_number | property_class       | property_status | zoning  | 
| =========== | ================ | ===================== | ================ | ============== | ============= | ==================== | =============== | ======= | 
| 1485991565  | 11               | 5211 PARDEE ST        | Airports         | 4984.464626    | 4128005910    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 5207 PARDEE ST        | Airports         | 5006.466392    | 4128005901    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 650 E WESTMINSTER AVE | General Services | 5200.7814      | 4239024900    | Residential Improved | Owned           | RD1.5-1 | 
| 1485991565  | 11               | 5201 PARDEE ST        | Airports         | 5203.859372    | 4128005923    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 5217 W 98TH ST        | General Services | 5271.975052    | 4128017909    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 9407 HINDRY PL        | Airports         | 5735.8798      | 4128008933    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 9619 HINDRY PL        | General Services | 5772.892944    | 4128014925    | Residential Improved | Owned           | *       | 
| 1485991565  | 11               | 9507 HINDRY PL        | Airports         | 5830.814901    | 4128007914    | Vacant Land          | Owned           | *       | 
| 1485991565  | 11               | 5428 W 96TH ST        | Airports         | 6095.2647      | 4128012925    | Residential Improved | Owned           | *       | 
| 1485991565  | 11               | 5220 W 98TH ST        | Airports         | 6113.884274    | 4128017902    | Vacant Land          | Owned           | *       | 
```