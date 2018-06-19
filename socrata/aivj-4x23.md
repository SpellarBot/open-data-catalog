# Gun Offenders

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gun-offenders) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/aivj-4x23) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/aivj-4x23/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/aivj-4x23/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | aivj-4x23 |
| Name | Gun Offenders |
| Attribution | Baltimore Police Department |
| Category | Public Safety |
| Tags | crime, police, gun |
| Created | 2011-07-18T17:36:12Z |
| Publication Date | 2015-12-10T20:09:01Z |

## Description

Source:  BPD Gun Offender Registry databaseOpen Baltimore view updated 12/10/2015Persons convicted of at least one gun-related offense that are required to register their name and address with police; also required to checkin with police every 6 months for three years.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name             | Data Type     | Render Type   |
| ======== | ============== | ================= | ================ | ============= | ============= |
| Yes      | series tag     | case_number       | caseNumber       | text          | text          |
| Yes      | series tag     | sentence          | sentence         | text          | text          |
| No       |                | registration_date | registrationDate | calendar_date | calendar_date |
| Yes      | time           | expiration_date   | Expiration_Date  | calendar_date | calendar_date |
| Yes      | series tag     | category          | category         | text          | text          |
| Yes      | series tag     | first_name        | firstName        | text          | text          |
| Yes      | series tag     | middle_name       | middleName       | text          | text          |
| Yes      | series tag     | last_name         | lastName         | text          | text          |
| No       |                | date_of_birth     | Date_Of_Birth    | calendar_date | calendar_date |
| Yes      | numeric metric | age               | age              | number        | number        |
| Yes      | series tag     | sex               | sex              | text          | text          |
| Yes      | series tag     | race              | race             | text          | text          |
| Yes      | series tag     | sid_number        | SID_Number       | text          | text          |
| Yes      | series tag     | district          | district         | text          | text          |
| Yes      | numeric metric | post              | post             | number        | number        |
| Yes      | series tag     | neighborhood      | neighborhood     | text          | text          |
```

## Time Field

```ls
Value = expiration_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = registration_date,date_of_birth
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:age p:long l:age t:dataTypeName=number

metric m:post p:long l:post t:dataTypeName=number

entity e:aivj-4x23 l:"Gun Offenders" t:attribution="Baltimore Police Department" t:url=https://data.baltimorecity.gov/api/views/aivj-4x23

property e:aivj-4x23 t:meta.view v:id=aivj-4x23 v:category="Public Safety" v:attributionLink=http://www.baltimorepolice.org/ v:averageRating=0 v:name="Gun Offenders" v:attribution="Baltimore Police Department"

property e:aivj-4x23 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:aivj-4x23 t:meta.view.owner v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:displayName="Jeffrey Cooper"

property e:aivj-4x23 t:meta.view.tableauthor v:id=ye7n-cr57 v:screenName="Jeffrey Cooper" v:roleName=publisher v:displayName="Jeffrey Cooper"
```

## Top Records

```ls
| case_number | sentence | registration_date | expiration_date     | category | first_name | middle_name | last_name   | date_of_birth       | age | sex    | race  | sid_number | district | post | neighborhood | 
| =========== | ======== | ================= | =================== | ======== | ========== | =========== | =========== | =================== | === | ====== | ===== | ========== | ======== | ==== | ============ | 
| 13-0385     |          |                   | 2016-08-20T00:00:00 |          | Umar       | Salie       | Abdul-Basir | 1979-10-02T00:00:00 |     | Male   | Black | 1659417    |          |      |              | 
| 15-0305     |          |                   | 2018-06-18T00:00:00 |          | Bilal      | Yusuf       | Abdullah    | 1988-07-12T00:00:00 |     | Male   | Black | 2946280    |          |      |              | 
| 13-0454     |          |                   | 2016-10-03T00:00:00 |          | Eric       |             | Acree       | 1989-06-19T00:00:00 |     | Male   | Black | 3237568    |          |      |              | 
| 14-0118     |          |                   | 2017-03-18T00:00:00 |          | Clyde      | Andre       | Adams       | 1974-03-13T00:00:00 |     | Male   | Black | 1363460    |          |      |              | 
| 12-0234     |          |                   | 2017-08-27T00:00:00 |          | Leroy      | Antonio     | Adams       | 1988-03-28T00:00:00 |     | Male   | Black | 2456879    |          |      |              | 
| 14-0058     |          |                   | 2017-02-25T00:00:00 |          | Khrystina  | Shade       | Adams       | 1989-03-22T00:00:00 |     | Female | Black | 3205649    |          |      |              | 
| 11-0066     |          |                   | 2017-05-20T00:00:00 |          | Bryant     | Lamont      | Adams       | 1990-08-02T00:00:00 |     | Male   | Black | 3227068    |          |      |              | 
| 12-0531     |          |                   | 2016-07-31T00:00:00 |          | Michael    | Marcus      | Adams       | 1981-06-07T00:00:00 |     | Male   | Black | 2052642    |          |      |              | 
| 15-0474     |          |                   | 2018-10-09T00:00:00 |          | Tahja      |             | Agent       | 1984-02-03T00:00:00 |     | Male   | Black | 2455854    |          |      |              | 
| 13-0071     |          |                   | 2016-11-04T00:00:00 |          | Rilwonn    | Olurunkummi | Akinola     | 1982-09-23T00:00:00 |     | Male   | Black | 2838828    |          |      |              | 
```