# Restaurant Scores - LIVES Standard

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-inspections-lives-standard) |
| Metadata | [Link](https://data.sfgov.org/api/views/pyih-qa8i) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/pyih-qa8i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/pyih-qa8i/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | pyih-qa8i |
| Name | Restaurant Scores - LIVES Standard |
| Attribution | Department of Public Health |
| Category | Health and Social Services |
| Tags | lives, san francisco, environmental health, department of public health, dph, sfdph, restaurant scores, sanitary scores, inspections |
| Created | 2015-10-28T15:57:36Z |
| Publication Date | 2015-10-28T16:03:26Z |

## Description

The Health Department has developed an inspection report and scoring system. After conducting an inspection of the facility, the Health Inspector calculates a score based on the violations observed. Violations can fall into:high risk category: records specific violations that directly relate to the transmission of food borne illnesses, the adulteration of food products and the contamination of food-contact surfaces.moderate risk category: records specific violations that are of a moderate risk to the public health and safety.low risk category: records violations that are low risk or have no immediate risk to the public health and safety.The score card that will be issued by the inspector is maintained at the food establishment and is available to the public in this dataset.
San Francisco's LIVES restaurant inspection data leverages the LIVES Flattened Schema (https://goo.gl/c3nNvr), which is based on LIVES version 2.0, cited on Yelp's website (http://www.yelp.com/healthscores).

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | business_id           | business_id           | text          | text          |
| Yes      | series tag     | business_name         | business_name         | text          | text          |
| No       |                | business_address      | business_address      | text          | text          |
| Yes      | series tag     | business_city         | business_city         | text          | text          |
| Yes      | series tag     | business_state        | business_state        | text          | text          |
| Yes      | series tag     | business_postal_code  | business_postal_code  | text          | text          |
| No       |                | business_latitude     | business_latitude     | number        | number        |
| No       |                | business_longitude    | business_longitude    | number        | number        |
| Yes      | series tag     | business_phone_number | business_phone_number | text          | text          |
| Yes      | series tag     | inspection_id         | inspection_id         | text          | text          |
| Yes      | time           | inspection_date       | inspection_date       | calendar_date | calendar_date |
| Yes      | numeric metric | inspection_score      | inspection_score      | number        | number        |
| Yes      | series tag     | inspection_type       | inspection_type       | text          | text          |
| Yes      | series tag     | violation_id          | violation_id          | text          | text          |
| Yes      | series tag     | violation_description | violation_description | text          | text          |
| Yes      | series tag     | risk_category         | risk_category         | text          | text          |
```

## Time Field

```ls
Value = inspection_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = business_address,business_latitude,business_longitude
```

## Data Commands

```ls
series e:pyih-qa8i d:2014-01-14T00:00:00.000Z t:business_name="Tiramisu Kitchen" t:business_postal_code=94104 t:violation_id=10_20140114_103119 t:risk_category="Moderate Risk" t:inspection_id=10_20140114 t:business_id=10 t:inspection_type="Routine - Unscheduled" t:violation_description="Inadequate and inaccessible handwashing facilities" t:business_city="San Francisco" t:business_state=CA m:inspection_score=92

series e:pyih-qa8i d:2014-01-14T00:00:00.000Z t:business_name="Tiramisu Kitchen" t:business_postal_code=94104 t:violation_id=10_20140114_103145 t:risk_category="Low Risk" t:inspection_id=10_20140114 t:business_id=10 t:inspection_type="Routine - Unscheduled" t:violation_description="Improper storage of equipment utensils or linens" t:business_city="San Francisco" t:business_state=CA m:inspection_score=92

series e:pyih-qa8i d:2014-01-14T00:00:00.000Z t:business_name="Tiramisu Kitchen" t:business_postal_code=94104 t:violation_id=10_20140114_103154 t:risk_category="Low Risk" t:inspection_id=10_20140114 t:business_id=10 t:inspection_type="Routine - Unscheduled" t:violation_description="Unclean or degraded floors walls or ceilings" t:business_city="San Francisco" t:business_state=CA m:inspection_score=92
```

## Meta Commands

```ls
metric m:inspection_score p:integer l:inspection_score t:dataTypeName=number

entity e:pyih-qa8i l:"Restaurant Scores - LIVES Standard" t:attribution="Department of Public Health" t:url=https://data.sfgov.org/api/views/pyih-qa8i

property e:pyih-qa8i t:meta.view v:id=pyih-qa8i v:category="Health and Social Services" v:attributionLink=http://www.sfdph.org/dph/EH/Food/score/default.asp v:averageRating=0 v:name="Restaurant Scores - LIVES Standard" v:attribution="Department of Public Health"

property e:pyih-qa8i t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:pyih-qa8i t:meta.view.owner v:id=grh2-fx3e v:screenName="FME Internal" v:displayName="FME Internal"

property e:pyih-qa8i t:meta.view.tableauthor v:id=grh2-fx3e v:screenName="FME Internal" v:displayName="FME Internal"
```

## Top Records

```ls
| business_id | business_name             | business_address      | business_city | business_state | business_postal_code | business_latitude | business_longitude | business_phone_number | inspection_id  | inspection_date     | inspection_score | inspection_type       | violation_id          | violation_description                                      | risk_category | 
| =========== | ========================= | ===================== | ============= | ============== | ==================== | ================= | ================== | ===================== | ============== | =================== | ================ | ===================== | ===================== | ========================================================== | ============= | 
| 10          | Tiramisu Kitchen          | 033 Belden Pl         | San Francisco | CA             | 94104                | 37.791116         | -122.403816        |                       | 10_20140114    | 2014-01-14T00:00:00 | 92               | Routine - Unscheduled | 10_20140114_103119    | Inadequate and inaccessible handwashing facilities         | Moderate Risk | 
| 10          | Tiramisu Kitchen          | 033 Belden Pl         | San Francisco | CA             | 94104                | 37.791116         | -122.403816        |                       | 10_20140114    | 2014-01-14T00:00:00 | 92               | Routine - Unscheduled | 10_20140114_103145    | Improper storage of equipment utensils or linens           | Low Risk      | 
| 10          | Tiramisu Kitchen          | 033 Belden Pl         | San Francisco | CA             | 94104                | 37.791116         | -122.403816        |                       | 10_20140114    | 2014-01-14T00:00:00 | 92               | Routine - Unscheduled | 10_20140114_103154    | Unclean or degraded floors walls or ceilings               | Low Risk      | 
| 10          | Tiramisu Kitchen          | 033 Belden Pl         | San Francisco | CA             | 94104                | 37.791116         | -122.403816        |                       | 10_20140729    | 2014-07-29T00:00:00 | 94               | Routine - Unscheduled | 10_20140729_103144    | Unapproved or unmaintained equipment or utensils           | Low Risk      | 
| 10          | Tiramisu Kitchen          | 033 Belden Pl         | San Francisco | CA             | 94104                | 37.791116         | -122.403816        |                       | 10_20140729    | 2014-07-29T00:00:00 | 94               | Routine - Unscheduled | 10_20140729_103129    | Insufficient hot water or running water                    | Moderate Risk | 
| 4864        | DRAGON CITY BAKERY & CAFE | 2367 MISSION St       | San Francisco | CA             | 94110                | 37.759174         | -122.419066        | +14155829718          | 4864_20161206  | 2016-12-06T00:00:00 | 84               | Routine - Unscheduled | 4864_20161206_103157  | Food safety certificate or food handler card not available | Low Risk      | 
| 79782       | Deli 23                   | 2449 23rd St          | San Francisco | CA             | 94110                |                   |                    |                       | 79782_20160503 | 2016-05-03T00:00:00 | 92               | Routine - Unscheduled | 79782_20160503_103120 | Moderate risk food holding temperature                     | Moderate Risk | 
| 63757       | Ajisen Ramen              | 865 Market St #STC-12 | San Francisco | CA             | 94103                | 37.784317         | -122.407563        |                       | 63757_20141113 | 2014-11-13T00:00:00 | 79               | Routine - Unscheduled | 63757_20141113_103142 | Unclean nonfood contact surfaces                           | Low Risk      | 
| 76437       | Sweetheart Cafe           | 909 Grant Ave         | San Francisco | CA             | 94108                |                   |                    |                       | 76437_20160329 | 2016-03-29T00:00:00 | 76               | Routine - Unscheduled | 76437_20160329_103113 | Sewage or wastewater contamination                         | High Risk     | 
| 5813        | LICK MIDDLE SCHOOL        | 1220 Noe St           | San Francisco | CA             | 94114                | 37.74949          | -122.43175         | +14155816139          | 5813_20140908  | 2014-09-08T00:00:00 | 100              | Routine - Unscheduled |                       |                                                            |               | 
```