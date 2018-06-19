# DOHMH New York City Restaurant Inspection Results

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dohmh-new-york-city-restaurant-inspection-results) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/43nn-pn8j) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/43nn-pn8j/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/43nn-pn8j/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 43nn-pn8j |
| Name | DOHMH New York City Restaurant Inspection Results |
| Attribution | Department of Health and Mental Hygiene (DOHMH) |
| Category | Health |
| Tags | restaurant, inspection, violation, grade, adjudication, fines |
| Created | 2014-08-01T19:10:59Z |
| Publication Date | 2016-03-22T19:25:10Z |

## Description

This dataset provides restaurant inspections, violations, grades and adjudication information

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | numeric metric | camis                 | CAMIS                 | number        | text          |
| Yes      | series tag     | dba                   | DBA                   | text          | text          |
| Yes      | series tag     | boro                  | BORO                  | text          | text          |
| Yes      | series tag     | building              | BUILDING              | text          | text          |
| Yes      | series tag     | street                | STREET                | text          | text          |
| Yes      | series tag     | zipcode               | ZIPCODE               | text          | text          |
| Yes      | series tag     | phone                 | PHONE                 | text          | text          |
| Yes      | series tag     | cuisine_description   | CUISINE DESCRIPTION   | text          | text          |
| Yes      | time           | inspection_date       | INSPECTION DATE       | calendar_date | calendar_date |
| Yes      | series tag     | action                | ACTION                | text          | text          |
| Yes      | series tag     | violation_code        | VIOLATION CODE        | text          | text          |
| Yes      | series tag     | violation_description | VIOLATION DESCRIPTION | text          | text          |
| Yes      | series tag     | critical_flag         | CRITICAL FLAG         | text          | text          |
| Yes      | numeric metric | score                 | SCORE                 | number        | number        |
| Yes      | series tag     | grade                 | GRADE                 | text          | text          |
| No       |                | grade_date            | GRADE DATE            | calendar_date | calendar_date |
| No       |                | record_date           | RECORD DATE           | calendar_date | calendar_date |
| Yes      | series tag     | inspection_type       | INSPECTION TYPE       | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = grade_date,record_date
```

## Data Commands

```ls
series e:43nn-pn8j d:2016-10-06T00:00:00.000Z t:boro=MANHATTAN t:building=246 t:phone=3472425762 t:critical_flag="Not Critical" t:violation_code=10B t:dba="MILK BAR NOLITA" t:street="MOTT ST" t:zipcode=10012 t:action="Violations were cited in the following area(s)." t:inspection_type="Pre-permit (Non-operational) / Initial Inspection" t:cuisine_description=Caf??/Coffee/Tea t:violation_description="Plumbing not properly installed or maintained; anti-siphonage or backflow prevention device not provided where required; equipment or floor not properly drained; sewage disposal system in disrepair or not functioning properly." m:camis=50056178 m:score=9

series e:43nn-pn8j d:2015-08-14T00:00:00.000Z t:boro=MANHATTAN t:building=591 t:phone=2128380404 t:critical_flag=Critical t:violation_code=04N t:dba="PARIS BAGUETTE" t:street="LEXINGTON AVE" t:zipcode=10022 t:action="Violations were cited in the following area(s)." t:inspection_type="Cycle Inspection / Initial Inspection" t:cuisine_description=Bakery t:violation_description="Filth flies or food/refuse/sewage-associated (FRSA) flies present in facilitys food and/or non-food areas. Filth flies include house flies, little house flies, blow flies, bottle flies and flesh flies. Food/refuse/sewage-associated flies include fruit flies, drain flies and Phorid flies." m:camis=50003253 m:score=26

series e:43nn-pn8j d:2015-01-05T00:00:00.000Z t:boro=BRONX t:building=1761 t:phone=7187166430 t:critical_flag=Critical t:violation_code=04L t:dba="U.S KENNEDY FRIED CHICKEN" t:street="UNIVERSITY AVENUE" t:zipcode=10453 t:action="Violations were cited in the following area(s)." t:inspection_type="Cycle Inspection / Initial Inspection" t:cuisine_description=Chicken t:violation_description="Evidence of mice or live mice present in facility's food and/or non-food areas." m:camis=41716001 m:score=17
```

## Meta Commands

```ls
metric m:camis p:integer l:CAMIS d:"This is an unique identifier for the entity (restaurant)" t:dataTypeName=number

metric m:score p:integer l:SCORE d:"Total Score for a particular inspection. If there was adjudication a judge may reduce the total points for the inspection and this field will have the update amount." t:dataTypeName=number

entity e:43nn-pn8j l:"DOHMH New York City Restaurant Inspection Results" t:attribution="Department of Health and Mental Hygiene (DOHMH)" t:url=https://data.cityofnewyork.us/api/views/43nn-pn8j

property e:43nn-pn8j t:meta.view v:id=43nn-pn8j v:category=Health v:averageRating=0 v:name="DOHMH New York City Restaurant Inspection Results" v:attribution="Department of Health and Mental Hygiene (DOHMH)"

property e:43nn-pn8j t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:43nn-pn8j t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| camis    | dba                                   | boro      | building | street            | zipcode | phone      | cuisine_description | inspection_date     | action                                          | violation_code | violation_description                                                                                                                                                                                                                                                                             | critical_flag | score | grade | grade_date          | record_date         | inspection_type                                   | 
| ======== | ===================================== | ========= | ======== | ================= | ======= | ========== | =================== | =================== | =============================================== | ============== | ================================================================================================================================================================================================================================================================================================= | ============= | ===== | ===== | =================== | =================== | ================================================= | 
| 50056178 | MILK BAR NOLITA                       | MANHATTAN | 246      | MOTT ST           | 10012   | 3472425762 | Caf??/Coffee/Tea    | 2016-10-06T00:00:00 | Violations were cited in the following area(s). | 10B            | Plumbing not properly installed or maintained; anti-siphonage or backflow prevention device not provided where required; equipment or floor not properly drained; sewage disposal system in disrepair or not functioning properly.                                                                | Not Critical  | 9     |       |                     | 2017-04-20T06:01:12 | Pre-permit (Non-operational) / Initial Inspection | 
| 50003253 | PARIS BAGUETTE                        | MANHATTAN | 591      | LEXINGTON AVE     | 10022   | 2128380404 | Bakery              | 2015-08-14T00:00:00 | Violations were cited in the following area(s). | 04N            | Filth flies or food/refuse/sewage-associated (FRSA) flies present in facilitys food and/or non-food areas. Filth flies include house flies, little house flies, blow flies, bottle flies and flesh flies. Food/refuse/sewage-associated flies include fruit flies, drain flies and Phorid flies. | Critical      | 26    |       |                     | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 41716001 | U.S KENNEDY FRIED CHICKEN             | BRONX     | 1761     | UNIVERSITY AVENUE | 10453   | 7187166430 | Chicken             | 2015-01-05T00:00:00 | Violations were cited in the following area(s). | 04L            | Evidence of mice or live mice present in facility's food and/or non-food areas.                                                                                                                                                                                                                   | Critical      | 17    |       |                     | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 41239724 | LAGUARDIA PLAZA HOTEL/PAVILLION GRILL | QUEENS    | 10404    | DITMARS BOULEVARD | 11369   | 7184576300 | American            | 2014-02-12T00:00:00 | Violations were cited in the following area(s). | 10I            | Single service item reused, improperly stored, dispensed; not used when required.                                                                                                                                                                                                                 | Not Critical  | 11    | A     | 2014-02-12T00:00:00 | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 50006295 | AFRICAN LAST STOP                     | BRONX     | 1300     | E 222ND ST        | 10469   | 7183251200 | African             | 2016-05-12T00:00:00 | Violations were cited in the following area(s). | 04L            | Evidence of mice or live mice present in facility's food and/or non-food areas.                                                                                                                                                                                                                   | Critical      | 6     |       |                     | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 41303170 | JC MAR RESTAURANT                     | BROOKLYN  | 736      | NOSTRAND AVENUE   | 11216   | 7187735238 | Spanish             | 2014-12-31T00:00:00 | Violations were cited in the following area(s). | 02B            | Hot food item not held at or above 140?? F.                                                                                                                                                                                                                                                       | Critical      | 28    | C     | 2014-12-31T00:00:00 | 2017-04-20T06:01:12 | Cycle Inspection / Re-inspection                  | 
| 41377149 | BARCLAYS CLIENT DINING ROOM           | MANHATTAN | 745      | 7 AVENUE          | 10019   | 2125262159 | American            | 2014-07-21T00:00:00 | Violations were cited in the following area(s). | 10F            | Non-food contact surface improperly constructed. Unacceptable material used. Non-food contact surface or equipment improperly maintained and/or not properly sealed, raised, spaced or movable to allow accessibility for cleaning on all sides, above and underneath the unit.                   | Not Critical  | 3     | A     | 2014-07-21T00:00:00 | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 50045841 | IPPUDO NY                             | MANHATTAN | 321      | W 51ST ST         | 10019   | 2129742500 | Japanese            | 2016-04-15T00:00:00 | Violations were cited in the following area(s). | 06B            | Tobacco use, eating, or drinking from open container in food preparation, food storage or dishwashing area observed.                                                                                                                                                                              | Critical      | 11    | A     | 2016-04-15T00:00:00 | 2017-04-20T06:01:12 | Pre-permit (Operational) / Re-inspection          | 
| 41525379 | BAR ITALIA                            | MANHATTAN | 768      | MADISON AVENUE    | 10065   | 9175466676 | Italian             | 2016-12-12T00:00:00 | Violations were cited in the following area(s). | 10F            | Non-food contact surface improperly constructed. Unacceptable material used. Non-food contact surface or equipment improperly maintained and/or not properly sealed, raised, spaced or movable to allow accessibility for cleaning on all sides, above and underneath the unit.                   | Not Critical  | 3     | A     | 2016-12-12T00:00:00 | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
| 50052178 | GRACE DELICIOUS KITCHEN INC           | BROOKLYN  | 2687     | PITKIN AVE        | 11208   | 7188275722 | Caribbean           | 2016-11-22T00:00:00 | Violations were cited in the following area(s). | 10F            | Non-food contact surface improperly constructed. Unacceptable material used. Non-food contact surface or equipment improperly maintained and/or not properly sealed, raised, spaced or movable to allow accessibility for cleaning on all sides, above and underneath the unit.                   | Not Critical  | 16    |       |                     | 2017-04-20T06:01:12 | Cycle Inspection / Initial Inspection             | 
```