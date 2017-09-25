# Austin Water Authorized Irrigation Inspector List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/austin-water-authorized-irrigation-inspector-list) |
| Metadata | [Link](https://data.austintexas.gov/api/views/dhvz-stgx) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/dhvz-stgx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/dhvz-stgx/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | dhvz-stgx |
| Name | Austin Water Authorized Irrigation Inspector List |
| Attribution | Austin Water |
| Category | Utilities and City Services |
| Tags | austin water, irrigation, inspector, water, code, property owner |
| Created | 2016-10-06T21:01:26Z |
| Publication Date | 2017-09-21T19:42:08Z |

## Description

Austin Water’s authorized irrigation inspectors are approved to perform the irrigation evaluation required by City Code 6-4-10(A) Facilities Regulated. Each property owner/manager is responsible for selecting an inspector. Individuals on this list are provided as a resource without endorsement by the City of Austin.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| No       | time        | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag  | inspector_number | Inspector Number | text      | text        |
| Yes      | series tag  | first_name       | First Name       | text      | text        |
| Yes      | series tag  | last_name        | Last Name        | text      | text        |
| Yes      | series tag  | company          | Company          | text      | text        |
| Yes      | series tag  | telephone        | Telephone        | text      | text        |
| Yes      | series tag  | email            | Email            | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:dhvz-stgx d:2016-10-06T21:01:29.000Z t:inspector_number="AWII 87" t:last_name=Proctor t:company="Absolute Commercial & Environmental Services" t:telephone=512-560-1099 t:first_name=Matt t:email=matt@absoluteenvironmental.net m:row_number.dhvz-stgx=1

series e:dhvz-stgx d:2016-10-06T21:01:29.000Z t:inspector_number="AWII 103" t:last_name=Warnke t:company="All-Star Inspections" t:telephone=512-803-8711 t:first_name=Eric t:email=Eric@All-StarTexas.com m:row_number.dhvz-stgx=2

series e:dhvz-stgx d:2016-10-06T21:01:29.000Z t:inspector_number="AWII 104" t:last_name=Scoby t:company="Living Water Irrigation Inspections" t:telephone=512-845-6403 t:first_name=David t:email=irrinspection@outlook.com m:row_number.dhvz-stgx=3
```

## Meta Commands

```ls
metric m:row_number.dhvz-stgx p:long l:"Row Number"

entity e:dhvz-stgx l:"Austin Water Authorized Irrigation Inspector List" t:attribution="Austin Water" t:url=https://data.austintexas.gov/api/views/dhvz-stgx

property e:dhvz-stgx t:meta.view d:2017-09-25T07:27:08.444Z v:averageRating=0 v:name="Austin Water Authorized Irrigation Inspector List" v:attribution="Austin Water" v:attributionLink=http://waterwiseaustin.org v:id=dhvz-stgx v:category="Utilities and City Services"

property e:dhvz-stgx t:meta.view.owner d:2017-09-25T07:27:08.444Z v:displayName="Erik Luna" v:lastNotificationSeenAt=1493912017 v:id=579b-znrx v:screenName="Erik Luna"

property e:dhvz-stgx t:meta.view.tableauthor d:2017-09-25T07:27:08.444Z v:displayName="Erik Luna" v:lastNotificationSeenAt=1493912017 v:roleName=editor v:id=579b-znrx v:screenName="Erik Luna"
```

## Top Records

```ls
| :updated_at | inspector_number | first_name | last_name | company                                      | telephone    | email                               | 
| =========== | ================ | ========== | ========= | ============================================ | ============ | =================================== | 
| 1475787689  | AWII 87          | Matt       | Proctor   | Absolute Commercial & Environmental Services | 512-560-1099 | matt@absoluteenvironmental.net      | 
| 1475787689  | AWII 103         | Eric       | Warnke    | All-Star Inspections                         | 512-803-8711 | Eric@All-StarTexas.com              | 
| 1475787689  | AWII 104         | David      | Scoby     | Living Water Irrigation Inspections          | 512-845-6403 | irrinspection@outlook.com           | 
| 1475787689  | AWII 109         | Brandon    | Cardwell  | Cardwell Irrigation Inspections              | 512-420-6551 | cardwellinspections@gmail.com       | 
| 1475787689  | AWII 113         | Brian      | Dunn      | All Pro Irrigation Inspections               | 512-876-0344 | allproirrigationtx@gmail.com        | 
| 1475787689  | AWII 114         | Alec       | Rose      | Lone Star Landscaping & Irrigation, LLC      | 512-228-9819 | alec.rose1@gmail.com                | 
| 1475787689  | AWII 119         | Michael    | Williams  |                                              | 512-517-0758 | austinirrigationsolutions@gmail.com | 
| 1475787689  | AWII 127         | Robert     | Biafore   | Accuracy Inspection Services                 | 512-293-8583 | accuracyinspections@gmail.com       | 
| 1475787689  | AWII 131         | Mac        | Newton    | Absolute Commercial & Environmental Services | 512-560-1099 | mac@absoluteenvironmental.com       | 
| 1475787689  | AWII 133         | Michael    | Olson     | Xerismart Water Solutions                    | 512-937-5262 | michael@xerismartwatersolutions.com | 
```