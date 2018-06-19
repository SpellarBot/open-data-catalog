# Doing Business Search - People

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/doing-business-search-people) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2sps-j9st) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2sps-j9st/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2sps-j9st/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2sps-j9st |
| Name | Doing Business Search - People |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Created | 2015-12-23T17:34:14Z |
| Publication Date | 2016-04-14T17:32:01Z |

## Description

The Doing Business Search provides access to information on entities and individuals that do business with the City of New York. http://www.nyc.gov/portal/site/DBusinessSite

## Columns

```ls
| Included | Schema Type | Field Name                | Name                      | Data Type     | Render Type   |
| ======== | =========== | ========================= | ========================= | ============= | ============= |
| Yes      | series tag  | mocs_peopleid             | MOCS PEOPLE ID            | text          | text          |
| Yes      | series tag  | organization_name         | ORGANIZATION NAME         | text          | text          |
| Yes      | series tag  | person_name_first         | PERSON FIRST NAME         | text          | text          |
| Yes      | series tag  | person_name_middle        | PERSON MIDDLE NAME        | text          | text          |
| Yes      | series tag  | person_name_last          | PERSON LAST NAME          | text          | text          |
| Yes      | series tag  | person_name_suffix        | PERSON_NAME_SUFFIX        | text          | text          |
| Yes      | series tag  | relationship_type_code    | RELATIONSHIP TYPE CODE    | text          | text          |
| Yes      | time        | doing_business_start_date | DOING BUSINESS START DATE | calendar_date | calendar_date |
| No       |             | doing_business_end_date   | DOING BUSINESS END DATE   | calendar_date | calendar_date |
```

## Time Field

```ls
Value = doing_business_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = doing_business_end_date
```

## Data Commands

```ls
series e:2sps-j9st d:2015-10-01T00:00:00.000Z t:relationship_type_code=OWN t:person_name_first=JORDAN t:person_name_last=CRAM t:organization_name="ENSTOA INC" t:mocs_peopleid=102921 m:row_number.2sps-j9st=1

series e:2sps-j9st d:2008-02-02T00:00:00.000Z t:relationship_type_code=OWN t:person_name_first=ALEXANDER t:person_name_last=MARCHUK t:organization_name="PERFECT SCORE TUTORING INC" t:mocs_peopleid=50424 m:row_number.2sps-j9st=2

series e:2sps-j9st d:2008-02-02T00:00:00.000Z t:relationship_type_code=OWN t:person_name_first=STEPHEN t:person_name_last=DISTLER t:organization_name="TEACHERS SUPPORT NETWORK" t:mocs_peopleid=52312 m:row_number.2sps-j9st=3
```

## Meta Commands

```ls
metric m:row_number.2sps-j9st p:long l:"Row Number"

entity e:2sps-j9st l:"Doing Business Search - People" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/2sps-j9st

property e:2sps-j9st t:meta.view v:id=2sps-j9st v:category="City Government" v:averageRating=0 v:name="Doing Business Search - People" v:attribution="Office of the Mayor (OTM)"

property e:2sps-j9st t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2sps-j9st t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| mocs_peopleid | organization_name             | person_name_first | person_name_middle | person_name_last | person_name_suffix | relationship_type_code | doing_business_start_date | doing_business_end_date | 
| ============= | ============================= | ================= | ================== | ================ | ================== | ====================== | ========================= | ======================= | 
| 102921        | ENSTOA INC                    | JORDAN            |                    | CRAM             |                    | OWN                    | 2015-10-01T00:00:00       |                         | 
| 50424         | PERFECT SCORE TUTORING INC    | ALEXANDER         |                    | MARCHUK          |                    | OWN                    | 2008-02-02T00:00:00       |                         | 
| 52312         | TEACHERS SUPPORT NETWORK      | STEPHEN           |                    | DISTLER          |                    | OWN                    | 2008-02-02T00:00:00       |                         | 
| 121811        | DEMOCRACY AT WORK INSTITUTE   | MELISSA           | M                  | HOOVER           |                    | CEO                    | 2015-08-01T00:00:00       |                         | 
| 51695         | EVBO INC.                     | EVELYN            |                    | BELLO            |                    | MCT                    | 2008-07-31T00:00:00       |                         | 
| 2600          | SENIOR HELPING SENIORS INC    | ROBERTA           | C                  | TOURNOUR         |                    | MCT                    | 2015-08-01T00:00:00       |                         | 
| 67258         | OLYMPUS AMERICA INC           | RICHARD           |                    | BAUCOM           |                    | MCT                    | 2016-01-01T00:00:00       |                         | 
| 123378        | CROKER FIRE DRILL CORPORATION | BRIAN             | L                  | WEINSTEIN        |                    | COO                    | 2015-05-01T00:00:00       |                         | 
| 69682         | JCMS INC                      | FRANCO            |                    | GEORGE           |                    | OWN                    | 2015-08-06T00:00:00       |                         | 
| 31937         | AMSEC ENGINEERING OF NY. P.C. | JOHN              | C                  | DAIDOLA          |                    | MCT                    | 2015-08-31T00:00:00       |                         | 
```