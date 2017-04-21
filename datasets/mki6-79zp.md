# ECY 2014 Rain Gage Stations Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ecy-2014-rain-gage-stations-location-518d4) |
| Metadata | [Link](https://data.wa.gov/api/views/mki6-79zp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/mki6-79zp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/mki6-79zp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | mki6-79zp |
| Name | ECY 2014 Rain Gage Stations Location |
| Attribution | WA Department of Ecology River and Stream Monitroing Program |
| Category | Natural Resources & Environment |
| Tags | ecy rain gage stations |
| Created | 2014-11-04T22:39:02Z |
| Publication Date | 2014-11-05T00:06:44Z |

## Columns

```ls
| Included | Schema Type | Field Name            | Name                  | Data Type | Render Type |
| ======== | =========== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag  | station_name          | Station Name          | text      | text        |
| Yes      | series tag  | station_id            | Station ID            | text      | text        |
| Yes      | series tag  | ecy_station_data_link | ECY Station Data Link | url       | url         |
```

## Time Field

```ls
Value = 2014
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mki6-79zp d:2014-01-01T00:00:00.000Z t:station_name="Crater Creek Trail Head" t:ecy_station_data_link="https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?wria=48" t:station_id=48W001 m:row_number.mki6-79zp=1

series e:mki6-79zp d:2014-01-01T00:00:00.000Z t:station_name="Pole Pick Mtn" t:ecy_station_data_link="https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W002" t:station_id=48W002 m:row_number.mki6-79zp=2

series e:mki6-79zp d:2014-01-01T00:00:00.000Z t:station_name="South Ridge" t:ecy_station_data_link="https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W003" t:station_id=48W003 m:row_number.mki6-79zp=3
```

## Meta Commands

```ls
metric m:row_number.mki6-79zp p:long l:"Row Number"

entity e:mki6-79zp l:"ECY 2014 Rain Gage Stations Location" t:attribution="WA Department of Ecology River and Stream Monitroing Program" t:url=https://data.wa.gov/api/views/mki6-79zp

property e:mki6-79zp t:meta.view v:id=mki6-79zp v:category="Natural Resources & Environment" v:averageRating=0 v:name="ECY 2014 Rain Gage Stations Location" v:attribution="WA Department of Ecology River and Stream Monitroing Program"

property e:mki6-79zp t:meta.view.owner v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:displayName="Markus.Von Prause@ecy.wa.gov"

property e:mki6-79zp t:meta.view.tableauthor v:id=q8y9-svx9 v:profileImageUrlMedium=/api/users/q8y9-svx9/profile_images/THUMB v:profileImageUrlLarge=/api/users/q8y9-svx9/profile_images/LARGE v:screenName="Markus.Von Prause@ecy.wa.gov" v:profileImageUrlSmall=/api/users/q8y9-svx9/profile_images/TINY v:roleName=publisher v:displayName="Markus.Von Prause@ecy.wa.gov"
```

## Top Records

```ls
| station_name            | station_id | ecy_station_data_link                                                                   | 
| ======================= | ========== | ======================================================================================= | 
| Crater Creek Trail Head | 48W001     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?wria=48, 48W001 Station Data]    | 
| Pole Pick Mtn           | 48W002     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W002, 48W002 Station Data] | 
| South Ridge             | 48W003     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W003, 48W003 Station Data] | 
| Cooper Mtn              | 48W004     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W004, 48W004 Station Data] | 
| Hungry Mtn              | 48W005     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W005, 48W005 Station Data] | 
| McClure Mtn             | 48W006     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W006, 48W006 Station Data] | 
| Blue Buck Mtn           | 48W007     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W007, 48W007 Station Data] | 
| Thrapp Mtn              | 48W008     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W008, 48W008 Station Data] | 
| Mount Leecher           | 48W009     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W009, 48W009 Station Data] | 
| Near Goat Mtn           | 48W010     | [https://fortress.wa.gov/ecy/wrx/wrx/flows/station.asp?sta=48W010, 48W010 Station Data] | 
```