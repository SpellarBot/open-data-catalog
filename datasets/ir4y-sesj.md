# Motor Vehicle Crashes - Individual Information: Three Year Window

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/motor-vehicle-crashes-individual-information-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/ir4y-sesj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/ir4y-sesj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/ir4y-sesj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | ir4y-sesj |
| Name | Motor Vehicle Crashes - Individual Information: Three Year Window |
| Attribution | NYS Department of Motor Vehicles |
| Category | Transportation |
| Tags | crash, accident, fatalities, driver passenger |
| Created | 2013-05-28T19:14:17Z |
| Publication Date | 2015-08-10T20:01:39Z |

## Description

Attributes about each individual involved in a crash as reported to NYS DMV

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | year               | Year               | number    | number      |
| Yes      | series tag     | case_individual_id | Case Individual ID | text      | number      |
| Yes      | series tag     | case_vehicle_id    | Case Vehicle ID    | text      | number      |
| Yes      | series tag     | victim_status      | Victim Status      | text      | text        |
| Yes      | series tag     | role_type          | Role Type          | text      | text        |
| Yes      | series tag     | seating_position   | Seating Position   | text      | text        |
| Yes      | series tag     | ejection           | Ejection           | text      | text        |
| Yes      | series tag     | license_state_code | License State Code | text      | text        |
| Yes      | series tag     | gender             | Sex                | text      | text        |
| Yes      | series tag     | transported_by     | Transported By     | text      | text        |
| Yes      | series tag     | safety_equipment   | Safety Equipment   | text      | text        |
| Yes      | series tag     | injury_descriptor  | Injury Descriptor  | text      | text        |
| Yes      | series tag     | injury_location    | Injury Location    | text      | text        |
| Yes      | series tag     | injury_severity    | Injury Severity    | text      | text        |
| Yes      | numeric metric | age                | Age                | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ir4y-sesj d:2012-01-01T00:00:00.000Z t:injury_severity=Uninjured t:license_state_code=NY t:ejection="Not Applicable" t:victim_status="Not Applicable" t:seating_position=Driver t:case_vehicle_id=9971704 t:case_individual_id=12964171 t:safety_equipment="Not Applicable" t:gender=F t:injury_location="Not Applicable" t:injury_descriptor="Not Applicable" t:role_type=Registrant t:transported_by="Not Entered" m:age=21

series e:ir4y-sesj d:2012-01-01T00:00:00.000Z t:injury_severity=Uninjured t:license_state_code=NY t:ejection="Not Ejected" t:victim_status="Not Applicable" t:seating_position=Driver t:case_vehicle_id=9971703 t:case_individual_id=12964170 t:safety_equipment="Lap Belt/Harness" t:gender=M t:injury_location="Not Applicable" t:injury_descriptor="Not Applicable" t:role_type="Driver of a Motor Vehicle in Transport" t:transported_by="Not Entered" m:age=46

series e:ir4y-sesj d:2012-01-01T00:00:00.000Z t:injury_severity=Moderate t:license_state_code=NY t:ejection="Not Ejected" t:victim_status=Conscious t:seating_position=Driver t:case_vehicle_id=9971710 t:case_individual_id=12964182 t:safety_equipment="Lap Belt/Harness" t:gender=F t:injury_location="Elbow-Lower Arm-Hand" t:injury_descriptor="Minor Bleeding" t:role_type="Driver of a Motor Vehicle in Transport" t:transported_by="Ambulance (Unknown plate number)" m:age=36
```

## Meta Commands

```ls
metric m:age p:integer l:Age d:"Reported age of the individual in the crash." t:dataTypeName=number

entity e:ir4y-sesj l:"Motor Vehicle Crashes - Individual Information: Three Year Window" t:attribution="NYS Department of Motor Vehicles" t:url=https://data.ny.gov/api/views/ir4y-sesj

property e:ir4y-sesj t:meta.view v:id=ir4y-sesj v:category=Transportation v:attributionLink=http://www.dmv.ny.gov/stats.htm v:averageRating=0 v:name="Motor Vehicle Crashes - Individual Information: Three Year Window" v:attribution="NYS Department of Motor Vehicles"

property e:ir4y-sesj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:ir4y-sesj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:ir4y-sesj t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| year | case_individual_id | case_vehicle_id | victim_status  | role_type                              | seating_position | ejection       | license_state_code | gender | transported_by                   | safety_equipment                  | injury_descriptor | injury_location      | injury_severity | age | 
| ==== | ================== | =============== | ============== | ====================================== | ================ | ============== | ================== | ====== | ================================ | ================================= | ================= | ==================== | =============== | === | 
| 2012 | 12964171           | 9971704         | Not Applicable | Registrant                             | Driver           | Not Applicable | NY                 | F      | Not Entered                      | Not Applicable                    | Not Applicable    | Not Applicable       | Uninjured       | 21  | 
| 2012 | 12964170           | 9971703         | Not Applicable | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | M      | Not Entered                      | Lap Belt/Harness                  | Not Applicable    | Not Applicable       | Uninjured       | 46  | 
| 2012 | 12964182           | 9971710         | Conscious      | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | F      | Ambulance (Unknown plate number) | Lap Belt/Harness                  | Minor Bleeding    | Elbow-Lower Arm-Hand | Moderate        | 36  | 
| 2012 | 12964187           | 9971713         | Conscious      | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | F      | Unknown Ambulance                | Air Bag Deployed/Lap Belt/Harness | Complaint of Pain | Neck                 | Minor           | 51  | 
| 2012 | 12964186           | 9971712         | Conscious      | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | M      | Unknown Ambulance                | Air Bag Deployed/Lap Belt/Harness | Complaint of Pain | Abdomen-Pelvis       | Minor           | 68  | 
| 2012 | 12964189           | 9971715         | Not Applicable | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | F      | Not Entered                      | Lap Belt/Harness                  | Not Applicable    | Not Applicable       | Uninjured       | 22  | 
| 2012 | 12964199           | 9971724         | Not Applicable | Registrant                             | Driver           | Not Ejected    | NY                 | F      | Not Entered                      | Lap Belt/Harness                  | Not Applicable    | Not Applicable       | Uninjured       | 62  | 
| 2012 | 12964198           | 9971723         | Not Applicable | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | M      | Not Entered                      | Lap Belt/Harness                  | Not Applicable    | Not Applicable       | Uninjured       | 23  | 
| 2012 | 12964204           | 9971728         | Not Applicable | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | FL                 | M      | Not Entered                      | None                              | Not Applicable    | Not Applicable       | Uninjured       | 56  | 
| 2012 | 12964226           | 9971747         | Not Applicable | Driver of a Motor Vehicle in Transport | Driver           | Not Ejected    | NY                 | M      | Not Entered                      | Lap Belt/Harness                  | Not Applicable    | Not Applicable       | Uninjured       | 49  | 
```