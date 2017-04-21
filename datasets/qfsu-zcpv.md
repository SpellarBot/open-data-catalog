# Fire Department Directory for New York State

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-department-directory-for-new-york-state) |
| Metadata | [Link](https://data.ny.gov/api/views/qfsu-zcpv) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/qfsu-zcpv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/qfsu-zcpv/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | qfsu-zcpv |
| Name | Fire Department Directory for New York State |
| Attribution | New York State Division of Homeland Security and Emergency Services (DHSES) |
| Category | Public Safety |
| Tags | fire house, fire district, fire company |
| Created | 2014-12-05T20:54:40Z |
| Publication Date | 2016-02-24T17:34:03Z |

## Description

This dataset lists the name, Division of Homeland Security and Emergency Services (DHSES) ID, location and phone number for all Fire Departments in New York State.  This data is collected and maintained by the Office of Fire Prevention & Control (OFPC) within DHSES and is updated annually.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type | Render Type |
| ======== | =========== | ==================== | ==================== | ========= | =========== |
| No       | time        | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag  | fire_department_name | Fire Department Name | text      | text        |
| Yes      | series tag  | fdid_code            | Fire Department Code | text      | text        |
| No       |             | address              | Address              | text      | text        |
| Yes      | series tag  | city                 | City                 | text      | text        |
| No       |             | st                   | State                | text      | text        |
| Yes      | series tag  | zip_code             | Zip Code             | text      | text        |
| Yes      | series tag  | county_code          | County Code          | text      | text        |
| Yes      | series tag  | countyname           | County Name          | text      | text        |
| Yes      | series tag  | phone_number         | Phone Number         | text      | number      |
| No       |             | lat                  | Latitude             | number    | number      |
| No       |             | long                 | Longitude            | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,st,lat,long
```

## Data Commands

```ls
series e:qfsu-zcpv d:2016-02-24T09:32:18.000Z t:countyname=Albany t:phone_number=5184477879 t:zip_code=12202-0000 t:fire_department_name="ALBANY FIRE DEPARTMENT" t:fdid_code=01001 t:county_code=01 t:city=ALBANY m:row_number.qfsu-zcpv=1

series e:qfsu-zcpv d:2016-02-24T09:32:18.000Z t:countyname=Albany t:phone_number=5188618171 t:zip_code=12009 t:fire_department_name="ALTAMONT FIRE DEPARTMENT" t:fdid_code=01002 t:county_code=01 t:city=ALTAMONT m:row_number.qfsu-zcpv=2

series e:qfsu-zcpv d:2016-02-24T09:32:18.000Z t:countyname=Albany t:phone_number=5188720470 t:zip_code=12023 t:fire_department_name="BERNE FIRE DEPARTMENT" t:fdid_code=01003 t:county_code=01 t:city=BERNE m:row_number.qfsu-zcpv=3
```

## Meta Commands

```ls
metric m:row_number.qfsu-zcpv p:long l:"Row Number"

entity e:qfsu-zcpv l:"Fire Department Directory for New York State" t:attribution="New York State Division of Homeland Security and Emergency Services  (DHSES)" t:url=https://data.ny.gov/api/views/qfsu-zcpv

property e:qfsu-zcpv t:meta.view v:id=qfsu-zcpv v:category="Public Safety" v:attributionLink=http://www.dhses.ny.gov/ofpc/ v:averageRating=0 v:name="Fire Department Directory for New York State" v:attribution="New York State Division of Homeland Security and Emergency Services  (DHSES)"

property e:qfsu-zcpv t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:qfsu-zcpv t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:qfsu-zcpv t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | fire_department_name            | fdid_code | address                    | city            | st | zip_code   | county_code | countyname | phone_number | lat       | long       | 
| =========== | =============================== | ========= | ========================== | =============== | == | ========== | =========== | ========== | ============ | ========= | ========== | 
| 1456306338  | ALBANY FIRE DEPARTMENT          | 01001     | 26 BROAD STREET            | ALBANY          | NY | 12202-0000 | 01          | Albany     | 5184477879   | 42.662577 | -73.759898 | 
| 1456306338  | ALTAMONT FIRE DEPARTMENT        | 01002     | 115 MAIN STREET PO BOX 642 | ALTAMONT        | NY | 12009      | 01          | Albany     | 5188618171   | 42.702865 | -74.02531  | 
| 1456306338  | BERNE FIRE DEPARTMENT           | 01003     | CANADAY ROAD               | BERNE           | NY | 12023      | 01          | Albany     | 5188720470   | 42.612842 | -74.070082 | 
| 1456306338  | BOGHT COMMUNITY FIRE DEPARTMENT | 01004     | 1095 LOUDON ROAD           | COHOES          | NY | 12047      | 01          | Albany     | 5187850339   | 42.783571 | -73.743969 | 
| 1456306338  | COEYMANS FIRE DEPARTMENT        | 01005     | 67 CHURCH STREET           | COEYMANS        | NY | 12045      | 01          | Albany     | 5187562027   | 42.474106 | -73.798832 | 
| 1456306338  | COEYMANS HOLLOW FIRE DEPARTMENT | 01006     | 1290 ROUTE 143             | COEYMANS HOLLOW | NY | 12046      | 01          | Albany     | 5187566310   | 42.48034  | -73.92286  | 
| 1456306338  | COHOES FIRE DEPARTMENT          | 01007     | 97 MOHAWK STREET           | COHOES          | NY | 12047      | 01          | Albany     | 5182372125   | 42.774511 | -73.700005 | 
| 1456306338  | COLONIE FIRE DEPARTMENT         | 01008     | 1631 CENTRAL AVENUE        | ALBANY          | NY | 12205      | 01          | Albany     | 5188699306   | 42.719292 | -73.834697 | 
| 1456306338  | DELMAR FIRE DEPARTMENT          | 01009     | 145 ADAMS STREET           | DELMAR          | NY | 12054      | 01          | Albany     | 5184757310   | 42.621806 | -73.83503  | 
| 1456306338  | ELSMERE FIRE DEPARTMENT         | 01010     | 15 WEST POPLAR DRIVE       | DELMAR          | NY | 12054      | 01          | Albany     | 5184399144   | 42.624501 | -73.819623 | 
```