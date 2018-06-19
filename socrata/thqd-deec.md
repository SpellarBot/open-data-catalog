# Cash Assistance Recipients Since 1955

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/odra-total-pann-bbf5b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/thqd-deec) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/thqd-deec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/thqd-deec/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | thqd-deec |
| Name | Cash Assistance Recipients Since 1955 |
| Attribution | Human Resources Administration (HRA) |
| Category | Social Services |
| Tags | odra total pann, hra, human resources, pann, 1955 |
| Created | 2013-05-21T12:35:54Z |
| Publication Date | 2016-11-04T14:13:26Z |

## Description

Office of Data Reporting and Analysis (ODRA) data dating back to 1955.

## Columns

```ls
| Included | Schema Type    | Field Name                    | Name                          | Data Type | Render Type |
| ======== | ============== | ============================= | ============================= | ========= | =========== |
| Yes      | time           | month                         | MONTH                         | text      | text        |
| Yes      | numeric metric | adc_persons                   | ADC PERSONS                   | number    | number      |
| Yes      | numeric metric | adcu_persons                  | ADCU PERSONS                  | number    | number      |
| Yes      | numeric metric | afdc_persons                  | AFDC PERSONS                  | number    | number      |
| Yes      | numeric metric | tanf_recipients               | TANF Recipients               | number    | number      |
| Yes      | numeric metric | hrpg_persons                  | HRPG PERSONS                  | number    | text        |
| Yes      | numeric metric | hr_exclud_pg_adc_persons      | HR Exclud PG-ADC PERSONS      | number    | number      |
| Yes      | numeric metric | hr_persons                    | HR PERSONS                    | number    | number      |
| Yes      | numeric metric | afdc                          | afdc                          | number    | number      |
| Yes      | numeric metric | sn_recipients                 | SN Recipients                 | number    | number      |
| Yes      | numeric metric | duplicated_count_ca_persons   | DUPLICATED COUNT CA PERSONS   | number    | number      |
| Yes      | numeric metric | unduplicated_count_ca_persons | UNDUPLICATED COUNT CA PERSONS | number    | number      |
```

## Time Field

```ls
Value = month
Format & Zone = MMM-yy
```

## Data Commands

```ls
series e:thqd-deec d:1955-02-01T00:00:00.000Z m:afdc_persons=142403 m:adcu_persons=0 m:afdc=142403 m:hr_persons=58535 m:duplicated_count_ca_persons=200938 m:unduplicated_count_ca_persons=200938 m:tanf_recipients=142403 m:sn_recipients=58535

series e:thqd-deec d:1955-03-01T00:00:00.000Z m:afdc_persons=144262 m:adcu_persons=0 m:afdc=144262 m:hr_persons=60224 m:duplicated_count_ca_persons=204486 m:unduplicated_count_ca_persons=204486 m:tanf_recipients=144262 m:sn_recipients=60224

series e:thqd-deec d:1955-04-01T00:00:00.000Z m:afdc_persons=145085 m:adcu_persons=0 m:afdc=145085 m:hr_persons=57898 m:duplicated_count_ca_persons=202983 m:unduplicated_count_ca_persons=202983 m:tanf_recipients=145085 m:sn_recipients=57898
```

## Meta Commands

```ls
metric m:adc_persons p:integer l:"ADC PERSONS" t:dataTypeName=number

metric m:adcu_persons p:integer l:"ADCU PERSONS" t:dataTypeName=number

metric m:afdc_persons p:integer l:"AFDC PERSONS" t:dataTypeName=number

metric m:tanf_recipients p:integer l:"TANF Recipients" t:dataTypeName=number

metric m:hrpg_persons p:long l:"HRPG PERSONS" t:dataTypeName=number

metric m:hr_exclud_pg_adc_persons p:long l:"HR Exclud PG-ADC PERSONS" t:dataTypeName=number

metric m:hr_persons p:integer l:"HR PERSONS" t:dataTypeName=number

metric m:afdc p:integer l:afdc t:dataTypeName=number

metric m:sn_recipients p:integer l:"SN Recipients" t:dataTypeName=number

metric m:duplicated_count_ca_persons p:integer l:"DUPLICATED COUNT CA PERSONS" t:dataTypeName=number

metric m:unduplicated_count_ca_persons p:integer l:"UNDUPLICATED COUNT CA PERSONS" t:dataTypeName=number

entity e:thqd-deec l:"Cash Assistance Recipients Since 1955" t:attribution="Human Resources Administration (HRA)" t:url=https://data.cityofnewyork.us/api/views/thqd-deec

property e:thqd-deec t:meta.view v:id=thqd-deec v:category="Social Services" v:averageRating=0 v:name="Cash Assistance Recipients Since 1955" v:attribution="Human Resources Administration (HRA)"

property e:thqd-deec t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:thqd-deec t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| month  | adc_persons | adcu_persons | afdc_persons | tanf_recipients | hrpg_persons | hr_exclud_pg_adc_persons | hr_persons | afdc   | sn_recipients | duplicated_count_ca_persons | unduplicated_count_ca_persons | 
| ====== | =========== | ============ | ============ | =============== | ============ | ======================== | ========== | ====== | ============= | =========================== | ============================= | 
| Feb-55 |             | 0            | 142403       | 142403          |              |                          | 58535      | 142403 | 58535         | 200938                      | 200938                        | 
| Mar-55 |             | 0            | 144262       | 144262          |              |                          | 60224      | 144262 | 60224         | 204486                      | 204486                        | 
| Apr-55 |             | 0            | 145085       | 145085          |              |                          | 57898      | 145085 | 57898         | 202983                      | 202983                        | 
| May-55 |             | 0            | 145962       | 145962          |              |                          | 56326      | 145962 | 56326         | 202288                      | 202288                        | 
| Jun-55 |             | 0            | 147075       | 147075          |              |                          | 55534      | 147075 | 55534         | 202609                      | 202609                        | 
| Jul-55 |             | 0            | 146405       | 146405          |              |                          | 54132      | 146405 | 54132         | 200537                      | 200537                        | 
| Aug-55 |             | 0            | 146674       | 146674          |              |                          | 53302      | 146674 | 53302         | 199976                      | 199976                        | 
| Sep-55 |             | 0            | 147297       | 147297          |              |                          | 51984      | 147297 | 51984         | 199281                      | 199281                        | 
| Oct-55 |             | 0            | 146446       | 146446          |              |                          | 50332      | 146446 | 50332         | 196778                      | 196778                        | 
| Nov-55 |             | 0            | 145744       | 145744          |              |                          | 49217      | 145744 | 49217         | 194961                      | 194961                        | 
```