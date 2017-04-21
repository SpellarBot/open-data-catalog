# Department of Motor Vehicles Office Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/department-of-motor-vehicles-office-listing) |
| Metadata | [Link](https://data.ct.gov/api/views/scnc-rath) |
| Data: JSON | [100 Rows](https://data.ct.gov/api/views/scnc-rath/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ct.gov/api/views/scnc-rath/rows.csv?max_rows=100) |
| Host | data.ct.gov |
| Id | scnc-rath |
| Name | Department of Motor Vehicles Office Listing |
| Attribution | Department of Motor Vehicles |
| Category | Transportation |
| Tags | dmv, offices, service |
| Created | 2014-04-04T17:11:32Z |
| Publication Date | 2014-04-04T17:51:26Z |

## Description

Listing of all Department of Motor Vehicles office with links to services, hours, and wait times.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | office      | Office     | text      | text        |
| Yes      | series tag  | location    | Location   | text      | text        |
| Yes      | series tag  | zip_code    | Zip Code   | text      | text        |
| Yes      | series tag  | type        | Type       | text      | text        |
| Yes      | series tag  | url         | Url        | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:scnc-rath d:2014-04-04T10:17:09.000Z t:office="Danbury Office" t:zip_code=06810 t:location="2 Lee Mack Avenue" t:type=Hub t:url="http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244582" m:row_number.scnc-rath=1

series e:scnc-rath d:2014-04-04T10:17:17.000Z t:office="Hamden Office" t:zip_code=06517 t:location="1985 State Street" t:type=Hub t:url="http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244590" m:row_number.scnc-rath=2

series e:scnc-rath d:2014-04-04T10:17:26.000Z t:office="Norwalk Office" t:zip_code=06851 t:location="540 Main Avenue" t:type=Hub t:url="http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244600" m:row_number.scnc-rath=3
```

## Meta Commands

```ls
metric m:row_number.scnc-rath p:long l:"Row Number"

entity e:scnc-rath l:"Department of Motor Vehicles Office Listing" t:attribution="Department of Motor Vehicles" t:url=https://data.ct.gov/api/views/scnc-rath

property e:scnc-rath t:meta.view v:id=scnc-rath v:category=Transportation v:attributionLink="http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244586" v:averageRating=0 v:name="Department of Motor Vehicles Office Listing" v:attribution="Department of Motor Vehicles"

property e:scnc-rath t:meta.view.license v:name="Public Domain"

property e:scnc-rath t:meta.view.owner v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"

property e:scnc-rath t:meta.view.tableauthor v:id=cvy9-n6sb v:screenName="Tyler Kleykamp" v:roleName=administrator v:lastNotificationSeenAt=1492608796 v:displayName="Tyler Kleykamp"
```

## Top Records

```ls
| :updated_at | office            | location              | zip_code | type       | url                                                       | 
| =========== | ================= | ===================== | ======== | ========== | ========================================================= | 
| 1396606629  | Danbury Office    | 2 Lee Mack Avenue     | 06810    | Hub        | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244582, null] | 
| 1396606637  | Hamden Office     | 1985 State Street     | 06517    | Hub        | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244590, null] | 
| 1396606646  | Norwalk Office    | 540 Main Avenue       | 06851    | Hub        | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244600, null] | 
| 1396606655  | Waterbury Office  | 2210 Thomaston Avenue | 06704    | Hub        | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244612, null] | 
| 1396606664  | Westport AAA      | 419 Post Road East    | 06880    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
| 1396606669  | Waterbury AAA     | 835 Wolcott Street    | 06705    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
| 1396606677  | Milford AAA       | 827 Bridgeport Avenue | 06460    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
| 1396606695  | Branford AAA      | 143 Cedar Street      | 06405    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
| 1396606701  | West Hartford AAA | 815 Farmington Avenue | 06119    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
| 1396606707  | Plainville AAA    | 17 Farmington Avenue  | 06062    | AAA Office | [http://www.ct.gov/dmv/cwp/view.asp?a=808&q=244578, null] | 
```