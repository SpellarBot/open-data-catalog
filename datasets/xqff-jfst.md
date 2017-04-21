# Iowa Veterans Home Current and Past Residents

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/iowa-veterans-home-current-and-past-residents) |
| Metadata | [Link](https://data.iowa.gov/api/views/xqff-jfst) |
| Data: JSON | [100 Rows](https://data.iowa.gov/api/views/xqff-jfst/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.iowa.gov/api/views/xqff-jfst/rows.csv?max_rows=100) |
| Host | data.iowa.gov |
| Id | xqff-jfst |
| Name | Iowa Veterans Home Current and Past Residents |
| Attribution | Iowa Veterans Home |
| Category | Health |
| Tags | veterans, quality of life |
| Created | 2014-11-24T14:15:07Z |
| Publication Date | 2016-09-02T17:54:06Z |

## Description

The Iowa Veterans Home provides a continuum of care to Iowa?s veterans and their spouses in an environment focusing on individualized services to enhance their quality of life. The Iowa Veterans Home opened its doors to Iowa veterans and their spouses in 1887. This dataset provides information on its residents.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | numeric metric | recno               | RecNo               | number    | text        |
| Yes      | series tag     | sex                 | Gender              | text      | text        |
| Yes      | series tag     | veteransstatus      | Veterans Status     | text      | text        |
| Yes      | series tag     | releasestatus       | Release Status      | text      | text        |
| Yes      | series tag     | countyofadmission   | County of Admission | text      | text        |
| Yes      | series tag     | currentage          | Current Age         | text      | text        |
| Yes      | series tag     | war                 | War                 | text      | text        |
| No       |                | primary_county_lat  | Primary County Lat  | number    | number      |
| No       |                | primary_county_long | Primary County Long | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = primary_county_lat,primary_county_long
```

## Data Commands

```ls
series e:xqff-jfst d:2016-09-02T17:53:19.000Z t:sex=Female t:countyofadmission=MARSHALL t:veteransstatus=Spouse t:releasestatus=Expired m:recno=1614

series e:xqff-jfst d:2016-09-02T17:53:19.000Z t:sex=Female t:veteransstatus=Spouse t:releasestatus=Expired m:recno=1771

series e:xqff-jfst d:2016-09-02T17:53:19.000Z t:sex=Female t:countyofadmission=GREENE t:veteransstatus=Spouse t:releasestatus=Expired m:recno=2083
```

## Meta Commands

```ls
metric m:recno p:integer l:RecNo d:"Unique ID" t:dataTypeName=number

entity e:xqff-jfst l:"Iowa Veterans Home Current and Past Residents" t:attribution="Iowa Veterans Home" t:url=https://data.iowa.gov/api/views/xqff-jfst

property e:xqff-jfst t:meta.view v:id=xqff-jfst v:category=Health v:attributionLink=http://ivh.iowa.gov/ v:averageRating=0 v:name="Iowa Veterans Home Current and Past Residents" v:attribution="Iowa Veterans Home"

property e:xqff-jfst t:meta.view.license v:name="Public Domain"

property e:xqff-jfst t:meta.view.owner v:id=7aqt-vm7i v:profileImageUrlMedium=/api/users/7aqt-vm7i/profile_images/THUMB v:profileImageUrlLarge=/api/users/7aqt-vm7i/profile_images/LARGE v:screenName="Iowa Veterans Home" v:profileImageUrlSmall=/api/users/7aqt-vm7i/profile_images/TINY v:displayName="Iowa Veterans Home"

property e:xqff-jfst t:meta.view.tableauthor v:id=7aqt-vm7i v:profileImageUrlMedium=/api/users/7aqt-vm7i/profile_images/THUMB v:profileImageUrlLarge=/api/users/7aqt-vm7i/profile_images/LARGE v:screenName="Iowa Veterans Home" v:profileImageUrlSmall=/api/users/7aqt-vm7i/profile_images/TINY v:roleName=editor v:displayName="Iowa Veterans Home"
```

## Top Records

```ls
| :updated_at | recno | sex    | veteransstatus | releasestatus | countyofadmission | currentage | war | primary_county_lat | primary_county_long | 
| =========== | ===== | ====== | ============== | ============= | ================= | ========== | === | ================== | =================== | 
| 1472838799  | 1614  | Female | Spouse         | Expired       | MARSHALL          |            |     | 42.0358499         | -92.9987706         | 
| 1472838799  | 1771  | Female | Spouse         | Expired       |                   |            |     |                    |                     | 
| 1472838799  | 2083  | Female | Spouse         | Expired       | GREENE            |            |     | 42.0362394         | -94.3968356         | 
| 1472838799  | 2253  | Female | Spouse         | Expired       | CHICKASAW         |            |     | 43.0600414         | -92.3176637         | 
| 1472838799  | 2254  | Female | Spouse         | Expired       | MARSHALL          |            |     | 42.0358499         | -92.9987706         | 
| 1472838799  | 2267  | Female | Spouse         | Expired       | LINN              |            |     | 42.0789478         | -91.5989646         | 
| 1472838799  | 2358  | Female | Spouse         | Expired       | BLACK HAWK        |            |     | 42.4700957         | -92.3088197         | 
| 1472838799  | 2390  | Female | Spouse         | Expired       | WAPELLO           |            |     | 41.0305845         | -92.4094499         | 
| 1472838799  | 2395  | Female | Spouse         | Discharge     | MONTGOMERY        |            |     | 41.03014           | -95.1563758         | 
| 1472838799  | 2438  | Female | Spouse         | Discharge     | POLK              |            |     | 41.6855048         | -93.5735335         | 
```