# Food Inspection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/food-inspection-475fc) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/5pue-gfbe) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/5pue-gfbe/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/5pue-gfbe/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 5pue-gfbe |
| Name | Food Inspection |
| Category | Health and Human Services |
| Tags | food, inspection, violations, closures, restaurant |
| Created | 2012-08-29T17:44:20Z |
| Publication Date | 2015-10-21T14:43:30Z |

## Description

The Licensure & Regulatory Services Program inspects all licensed retail food establishments in Montgomery County for a variety of reasons (e.g. obtaining a permit, regular check-ups, or in response to complaints.) Included in this overall surveillance are two types of inspections that are conducted on a routine basis. The first type, a comprehensive inspection, is a thorough inspection that evaluates the sanitation, maintenance, and food service operations for the facility. This inspection includes many of the items found in the monitoring inspection, such as critical temperatures and food handling procedures. The second type, a monitoring inspection, involves checking the food service operation for critical food temperatures, equipment temperatures, and general food handling / cleanliness practices. While monitoring inspections are not as detailed as environmental inspections, they help ensure that the facility is operating safely throughout the year.

The frequency of inspections is based on the food-borne illness risks associated with the food being processed at a facility. Based on the risk each facility is designated as high, medium, or low priority. High priority risk facilities prepare food products a day or more in advance or utilize any combination of two or more processes such as a cooking, cooling, reheating and hot holding food over four hours. Moderate priority risk facilities prepare and cook food products which are served immediately or within four hours. A low priority risk facility serve prepackage foods that are not potentially hazardous.

For high risk facilities, a monitoring inspection is conducted at least twice a year, and moderate risk facilities are inspected at least once a year. High and moderate risk facilities also receive at least one comprehensive inspection every year. Low risk priority facilities typically receive one comprehensive inspection every two years.

(C) Denotes a Critical Violation. A Critical Violation means a food safety requirement that requires immediate correction. Failure for immediate correction results in cessation of some or all food operations or closure of the facility until violation is able to be corrected.

Update Frequency:  Daily

## Columns

```ls
| Included | Schema Type    | Field Name        | Name                                    | Data Type     | Render Type   |
| ======== | ============== | ================= | ======================================= | ============= | ============= |
| Yes      | series tag     | establishment_id  | Establishment ID                        | text          | text          |
| Yes      | series tag     | name              | Name                                    | text          | text          |
| No       |                | address1          | Address 1                               | text          | text          |
| No       |                | address2          | Address 2                               | text          | text          |
| Yes      | series tag     | city              | City                                    | text          | text          |
| Yes      | series tag     | zip               | Zip                                     | text          | text          |
| Yes      | time           | inspectiondate    | Inspection Date                         | calendar_date | calendar_date |
| Yes      | series tag     | inspectionresults | Inspection Results                      | text          | text          |
| Yes      | series tag     | violation1        | Food from Approved Source (C)           | text          | text          |
| Yes      | series tag     | violation2        | Food Protected from Contamination (C)   | text          | text          |
| Yes      | series tag     | violation3        | Ill Workers Restricted (C)              | text          | text          |
| Yes      | series tag     | violation4        | Proper Hand Washing (C)                 | text          | text          |
| Yes      | series tag     | violation5        | Cooling Time and Temperature (C)        | text          | text          |
| Yes      | series tag     | violation6a       | Cold Holding Temperature (C)            | text          | text          |
| Yes      | series tag     | violation6b       | Hot Holding Temperature (C)             | text          | text          |
| Yes      | series tag     | violation7a       | Cooking Time and Temperature (C)        | text          | text          |
| Yes      | series tag     | violation7b       | Reheating Time and Temperature (C)      | text          | text          |
| Yes      | series tag     | violation8        | Hot and Cold Running Water Provided (C) | text          | text          |
| Yes      | series tag     | violation9        | Proper Sewage Disposal (C)              | text          | text          |
| Yes      | series tag     | violation20       | Toxic Substances & Pesticides           | text          | text          |
| Yes      | series tag     | violation22       | Rodent and Insects                      | text          | text          |
| Yes      | series tag     | violationmenu     | Nutritional Labeling                    | text          | text          |
| Yes      | series tag     | violationtransfat | Trans Fat Ban                           | text          | text          |
| Yes      | series tag     | violationsmoking  | No-Smoking Sign Posted                  | text          | text          |
| Yes      | series tag     | inspectiontype    | Inspection Type                         | text          | text          |
| Yes      | series tag     | organization      | Owner                                   | text          | text          |
| Yes      | series tag     | category          | Category                                | text          | text          |
| Yes      | series tag     | type              | Type                                    | text          | text          |
| No       |                | latitude          | Latitude                                | number        | number        |
| Yes      | numeric metric | longitude         | Longitude                               | number        | number        |
```

## Time Field

```ls
Value = inspectiondate
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address1,address2,latitude
```

## Data Commands

```ls
series e:5pue-gfbe d:2017-02-03T00:00:00.000Z t:inspectionresults="No Critical Violations Noted" t:establishment_id=18475 t:violation8="In Compliance" t:violation20="In Compliance" t:violation7a="In Compliance" t:violation5="In Compliance" t:type=Food t:violation22="In Compliance" t:violationsmoking="In Compliance" t:city=ROCKVILLE t:violation9="In Compliance" t:violationmenu="Not applicable" t:inspectiontype=Comprehensive t:organization="GANAPATI FOODS, LLP." t:violation3="In Compliance" t:violation4="In Compliance" t:violation1="In Compliance" t:violation7b="In Compliance" t:name="GANAPATA FOODS" t:violation2="In Compliance" t:zip=20851 t:violationtransfat="In Compliance" t:category=Restaurant t:violation6b="In Compliance" t:violation6a="In Compliance" m:longitude=-77.1357

series e:5pue-gfbe d:2017-02-06T00:00:00.000Z t:inspectionresults="No Critical Violations Noted" t:establishment_id=28610 t:violation8="In Compliance" t:violation20="In Compliance" t:violation7a="In Compliance" t:violation5="In Compliance" t:type=Food t:violation22="In Compliance" t:violationsmoking="In Compliance" t:city="MONTGOMERY VILLAGE" t:violation9="In Compliance" t:violationmenu="Not applicable" t:inspectiontype=Monitoring t:organization="YALT LLC" t:violation3="In Compliance" t:violation4="In Compliance" t:violation1="In Compliance" t:violation7b="In Compliance" t:name="SUBWAY #26930" t:violation2="In Compliance" t:zip=20886 t:violationtransfat="In Compliance" t:category=Restaurant t:violation6b="In Compliance" t:violation6a="In Compliance" m:longitude=-77.1892

series e:5pue-gfbe d:2017-02-06T00:00:00.000Z t:inspectionresults="Critical Violations Corrected" t:establishment_id=18969 t:violation8="In Compliance" t:violation20="In Compliance" t:violation7a="In Compliance" t:violation5="In Compliance" t:type=Food t:violation22="Out of Compliance" t:violationsmoking="In Compliance" t:city="TAKOMA PARK" t:violation9="In Compliance" t:violationmenu="Not applicable" t:inspectiontype=Comprehensive t:organization="CARLOS WALTER VILLATORO, MOGOTILLO LLC" t:violation3="In Compliance" t:violation4="In Compliance" t:violation1="In Compliance" t:violation7b="In Compliance" t:name="MOGOTILLO RESTAURANT" t:violation2="In Compliance" t:zip=20912 t:violationtransfat="In Compliance" t:category=Restaurant t:violation6b="In Compliance" t:violation6a="Out of Compliance" m:longitude=-76.9874
```

## Meta Commands

```ls
metric m:longitude p:float l:Longitude t:dataTypeName=number

entity e:5pue-gfbe l:"Food Inspection" t:url=https://data.montgomerycountymd.gov/api/views/5pue-gfbe

property e:5pue-gfbe t:meta.view v:id=5pue-gfbe v:category="Health and Human Services" v:averageRating=0 v:name="Food Inspection"

property e:5pue-gfbe t:meta.view.owner v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"

property e:5pue-gfbe t:meta.view.tableauthor v:id=ajn4-zy65 v:screenName="MCG ESB Service" v:roleName=administrator v:lastNotificationSeenAt=1491401045 v:displayName="MCG ESB Service"
```

## Top Records

```ls
| establishment_id | name                                | address1                      | address2 | city               | zip   | inspectiondate      | inspectionresults             | violation1    | violation2    | violation3    | violation4    | violation5    | violation6a       | violation6b       | violation7a   | violation7b   | violation8    | violation9        | violation20   | violation22       | violationmenu  | violationtransfat | violationsmoking | inspectiontype                       | organization                           | category        | type | latitude | longitude | 
| ================ | =================================== | ============================= | ======== | ================== | ===== | =================== | ============================= | ============= | ============= | ============= | ============= | ============= | ================= | ================= | ============= | ============= | ============= | ================= | ============= | ================= | ============== | ================= | ================ | ==================================== | ====================================== | =============== | ==== | ======== | ========= | 
| 18475            | GANAPATA FOODS                      | 705 FIRST ST.                 |          | ROCKVILLE          | 20851 | 2017-02-03T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | GANAPATI FOODS, LLP.                   | Restaurant      | Food | 39.085   | -77.1357  | 
| 28610            | SUBWAY #26930                       | 9136 ROTHBURY DR              |          | MONTGOMERY VILLAGE | 20886 | 2017-02-06T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Monitoring                           | YALT LLC                               | Restaurant      | Food | 39.1845  | -77.1892  | 
| 18969            | MOGOTILLO RESTAURANT                | 7637 NEW HAMPSHIRE AVE        |          | TAKOMA PARK        | 20912 | 2017-02-06T00:00:00 | Critical Violations Corrected | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | Out of Compliance | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | Out of Compliance | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | CARLOS WALTER VILLATORO, MOGOTILLO LLC | Restaurant      | Food | 38.9869  | -76.9874  | 
| 20579            | BAJA FRESH                          | 2800 W. UNIVERSITY BLVD. S116 |          | SILVER SPRING      | 20902 | 2017-02-06T00:00:00 | Critical Violations Corrected | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | Out of Compliance | Out of Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Monitoring                           | AASHNIN FOUR INC.                      | Market          | Food | 39.0383  | -77.0569  | 
| 27626            | CHICK-FIL-A                         | 12001 ROCKVILLE PIKE          |          | ROCKVILLE          | 20852 | 2017-02-06T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | BRIX LLC                               | Market          | Food | 39.0538  | -77.1164  | 
| 19393            | NATRAJ RESTAURANT CATERER           | 403 E. DIAMOND AVE            |          | GAITHERSBURG       | 20877 | 2017-02-06T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | Out of Compliance | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | JANAKARORA ASHWANIRORA                 | Caterer         | Food | 39.1419  | -77.1904  | 
| 19490            | LE PAIN QUOTIDIEN                   | 7140 BETHESDA LANE            | F,G,H    | BETHESDA           | 20814 | 2016-09-19T00:00:00 | Critical Violations Corrected | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | In Compliance  | In Compliance     | In Compliance    | Comprehensive                        | PQ BETHESDA, INC                       | Restaurant      | Food | 38.9828  | -77.0983  | 
| 28939            | BETHESDA CARES @ CHURCH IN BETHESDA | 5033 WILSON LANE              |          | BETHESDA           | 20814 | 2017-02-03T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | BETHESDA CARES INC                     | Non-Profit      | Food | 38.9875  | -77.1002  | 
| 20892            | DUNKIN DONUTS                       | 865-A ROCKVILLE PIKE          |          | ROCKVILLE          | 20852 | 2016-07-21T00:00:00 | Critical Violations Corrected | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | Out of Compliance | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Monitoring w/Complaint Investigation | W DONUT OPERATING, LLC.                |                 | Food | 39.0752  | -77.1378  | 
| 11472            | MARIAN ASSISTED LIVING-DOM          | 19109 GEORGIA AVE             |          | BROOKEVILLE        | 20833 | 2017-02-06T00:00:00 | No Critical Violations Noted  | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance     | In Compliance | In Compliance | In Compliance | In Compliance     | In Compliance | In Compliance     | Not applicable | In Compliance     | In Compliance    | Comprehensive                        | MARIAN ASSISTED LIVING, INC.           | Assisted Living | Food | 39.1703  | -77.0566  | 
```