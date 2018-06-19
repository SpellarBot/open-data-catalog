# Mindfulness tuesday practice session schedule

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mindfulness-tuesday-practice-session-schedule) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/a4yq-kp3q) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/a4yq-kp3q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/a4yq-kp3q/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | a4yq-kp3q |
| Name | Mindfulness tuesday practice session schedule |
| Tags | mbsr, mindfulness, mindful practice |
| Created | 2016-01-30T19:31:16Z |
| Publication Date | 2016-02-01T17:32:58Z |

## Description

Drop in sessions open to all

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| Yes      | time        | start_time    | Start Time    | date      | date        |
| No       |             | end_time      | End Time      | date      | date        |
| Yes      | series tag  | event_name    | Event Name    | text      | text        |
| Yes      | series tag  | location_name | Building/Room | text      | text        |
| Yes      | series tag  | url           | URL           | url       | url         |
```

## Time Field

```ls
Value = start_time
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = end_time
```

## Data Commands

```ls
series e:a4yq-kp3q d:2016-04-05T23:00:00.000Z t:location_name="KSC 8th floor room J" t:event_name="Mindfulness Practice" t:url=http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx m:row_number.a4yq-kp3q=1

series e:a4yq-kp3q d:2016-02-24T00:00:00.000Z t:location_name="KSC 8th floor room J" t:event_name="Mindfulness Practice" t:url=http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx m:row_number.a4yq-kp3q=2

series e:a4yq-kp3q d:2016-04-26T23:00:00.000Z t:location_name="Chinook room 121" t:event_name="Mindfulness Practice" t:url=http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx m:row_number.a4yq-kp3q=3
```

## Meta Commands

```ls
metric m:row_number.a4yq-kp3q p:long l:"Row Number"

entity e:a4yq-kp3q l:"Mindfulness tuesday practice session schedule" t:url=https://data.kingcounty.gov/api/views/a4yq-kp3q

property e:a4yq-kp3q t:meta.view v:id=a4yq-kp3q v:averageRating=0 v:name="Mindfulness tuesday practice session schedule"

property e:a4yq-kp3q t:meta.view.owner v:id=niwt-u6t9 v:screenName=christimasi v:displayName=christimasi

property e:a4yq-kp3q t:meta.view.tableauthor v:id=niwt-u6t9 v:screenName=christimasi v:roleName=designer v:displayName=christimasi
```

## Top Records

```ls
| start_time | end_time   | event_name           | location_name                           | url                                                                                                                        | 
| ========== | ========== | ==================== | ======================================= | ========================================================================================================================== | 
| 1459897200 | 1459899000 | Mindfulness Practice | KSC 8th floor room J                    | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1456272000 | 1456273800 | Mindfulness Practice | KSC 8th floor room J                    | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1461711600 | 1461713400 | Mindfulness Practice | Chinook room 121                        | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1464735600 | 1464737400 | Mindfulness Practice | KSC 8th floor room J                    | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1460502000 | 1460503800 | Mindfulness Practice | Chinook 223 Rhodendron room (2nd floor) | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1455667200 | 1455669000 | Mindfulness Practice | Chinook room 121                        | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at Kingcounty]  | 
| 1458687600 | 1458689400 | Mindfulness Practice | KSC 8th floor room J                    | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1459292400 | 1458689400 | Mindfulness Practice | Chinook room 121                        | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1458082800 | 1426462200 | Mindfulness Practice | Chinook room 121                        | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
| 1462316400 | 1462318200 | Mindfulness Practice | KSC 8th floor room J                    | [http://www.kingcounty.gov/audience/employees/healthy-incentives/get-started/mindfulness.aspx, Mindfulness at King County] | 
```