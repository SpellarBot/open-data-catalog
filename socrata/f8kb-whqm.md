# Surface Water Quality Assessments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/surface-water-quality-assessments-4153e) |
| Metadata | [Link](https://data.maryland.gov/api/views/f8kb-whqm) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/f8kb-whqm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/f8kb-whqm/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | f8kb-whqm |
| Name | Surface Water Quality Assessments |
| Category | Energy and Environment |
| Tags | water quality, water, impairments, mde |
| Created | 2012-10-05T20:46:25Z |
| Publication Date | 2016-03-25T19:10:34Z |

## Description

This is the 2014 Integrated Report.  EPA approved this submission in accordance with Sections 303(d), 305(b), and 314(l) of the Clean Water Act, on October 16, 2015.  The Integrated Report (IR) combines two water quality reports required under sections 305(b) and 303(d) of the federal Clean Water Act.  Section 305(b) requires states, territories and authorized tribes to perform annual water quality assessments to determine the status of jurisdictional waters.  Section 303(d) requires states, territories and authorized tribes to identify waters assessed as not meeting water quality standards(see Code of Maryland Regulations 26.08.02).  Waters that do not meet standards may require a Total Maximum Daily Load to determine the maximum amount of an impairing substance or pollutant that a particular water body can assimilate and still meet water quality criteria.  Historically, the 303(d) List and the 305(b) report were submitted to the Environmental Protection Agency (EPA) as separate documents but more recent guidance has called for combining these two reports into a single biennial publication.

More information is available at http://www.mde.state.md.us/PROGRAMS/WATER/TMDL/INTEGRATED303DREPORTS/Pages/Programs/WaterPrograms/TMDL/Maryland%20303%20dlist/index.aspx

A searchable version of this data is available at http://www.mde.state.md.us/programs/Water/TMDL/Integrated303dReports/Pages/303d.aspx

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | numeric metric | cycle_first_listed               | Cycle_First_Listed               | number    | number      |
| Yes      | series tag     | assessment_unit_id               | Assessment Unit ID               | text      | text        |
| Yes      | series tag     | waterbody_name                   | Waterbody_Name                   | text      | text        |
| Yes      | series tag     | basin_name                       | Basin_Name                       | text      | text        |
| Yes      | series tag     | huc                              | HUC                              | text      | text        |
| Yes      | series tag     | basin_code                       | Basin_Code                       | text      | text        |
| Yes      | series tag     | subbasin_code                    | Subbasin_Code                    | text      | text        |
| Yes      | series tag     | county                           | County                           | text      | text        |
| Yes      | series tag     | water_type                       | Water_Type                       | text      | text        |
| Yes      | series tag     | water_type_detail                | Water_Type_Detail                | text      | text        |
| Yes      | numeric metric | assessment_unit_size             | Assessment Unit Size             | number    | number      |
| Yes      | series tag     | assessment_unit_size_units       | Assessment Unit Size Units       | text      | text        |
| Yes      | series tag     | use_class                        | Use_Class                        | text      | text        |
| Yes      | series tag     | designated_use                   | Designated_Use                   | text      | text        |
| Yes      | series tag     | listing_category                 | Listing_Category                 | text      | text        |
| Yes      | series tag     | cause                            | Cause                            | text      | text        |
| Yes      | series tag     | priority                         | Priority                         | text      | text        |
| No       |                | impairment_addressed_within_2_yr | Impairment_Addressed_Within_2_Yr | text      | text        |
| Yes      | series tag     | action                           | Action                           | text      | text        |
| Yes      | time           | action_year                      | Action_Year                      | text      | number      |
| Yes      | series tag     | tmdl_id                          | TMDL_ID                          | text      | text        |
| Yes      | series tag     | notes                            | Notes                            | text      | text        |
| Yes      | series tag     | link_to_tmdl                     | Link to TMDL                     | text      | text        |
```

## Time Field

```ls
Value = action_year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = impairment_addressed_within_2_yr
```

## Data Commands

```ls
series e:f8kb-whqm d:2016-01-01T00:00:00.000Z t:assessment_unit_id=MD-02050301 t:cause="Cause Unknown" t:county=CR t:water_type_detail="1st thru 4th order streams" t:listing_category=3 t:use_class=I t:water_type=RIVER t:huc=02050306 t:assessment_unit_size_units=Miles t:designated_use="Aquatic Life and Wildlife" t:basin_code=02050301 t:basin_name="Conewago Creek" m:assessment_unit_size=9.94

series e:f8kb-whqm d:2016-01-01T00:00:00.000Z t:waterbody_name="Rock Run" t:assessment_unit_id=MD-021202010319-Rock_Run1 t:cause="Temperature, water" t:water_type_detail="Non-tidal Segment(s)" t:listing_category=5 t:huc=02050306 t:subbasin_code=021202010319 t:county=CE t:priority=Low t:water_type=RIVER t:use_class=III-P t:assessment_unit_size_units=Miles t:notes="Temperature measurements exceed criteria and no coldwater obligate taxa were found." t:designated_use="Aquatic Life and Wildlife" t:basin_code=02120201 t:basin_name="Lower Susquehanna River" m:assessment_unit_size=0.48 m:cycle_first_listed=2014

series e:f8kb-whqm d:2016-01-01T00:00:00.000Z t:waterbody_name="Rock Run" t:assessment_unit_id=MD-021202010319-Rock_Run2 t:cause="Temperature, water" t:water_type_detail="Non-tidal Segment(s)" t:listing_category=5 t:huc=02050306 t:subbasin_code=021202010319 t:county=CE t:priority=Low t:water_type=RIVER t:use_class=III-P t:assessment_unit_size_units=Miles t:notes="Temperature measurements exceed criteria and no coldwater obligate taxa were found." t:designated_use="Aquatic Life and Wildlife" t:basin_code=02120201 t:basin_name="Lower Susquehanna River" m:assessment_unit_size=0.9 m:cycle_first_listed=2014
```

## Meta Commands

```ls
metric m:cycle_first_listed p:integer l:Cycle_First_Listed d:"Report cycle year when the waterbody was first listed" t:dataTypeName=number

metric m:assessment_unit_size p:double l:"Assessment Unit Size" t:dataTypeName=number

entity e:f8kb-whqm l:"Surface Water Quality Assessments" t:url=https://data.maryland.gov/api/views/f8kb-whqm

property e:f8kb-whqm t:meta.view v:id=f8kb-whqm v:category="Energy and Environment" v:averageRating=0 v:name="Surface Water Quality Assessments"

property e:f8kb-whqm t:meta.view.license v:name="Public Domain"

property e:f8kb-whqm t:meta.view.owner v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"

property e:f8kb-whqm t:meta.view.tableauthor v:id=6wh5-kegk v:profileImageUrlMedium=/api/users/6wh5-kegk/profile_images/THUMB v:profileImageUrlLarge=/api/users/6wh5-kegk/profile_images/LARGE v:screenName="Andrew Gosden" v:profileImageUrlSmall=/api/users/6wh5-kegk/profile_images/TINY v:roleName=editor v:lastNotificationSeenAt=1491588421 v:displayName="Andrew Gosden"
```

## Top Records

```ls
| cycle_first_listed | assessment_unit_id                | waterbody_name      | basin_name              | huc      | basin_code | subbasin_code | county | water_type | water_type_detail          | assessment_unit_size | assessment_unit_size_units | use_class | designated_use            | listing_category | cause              | priority | impairment_addressed_within_2_yr | action                                            | action_year | tmdl_id | notes                                                                                | link_to_tmdl | 
| ================== | ================================= | =================== | ======================= | ======== | ========== | ============= | ====== | ========== | ========================== | ==================== | ========================== | ========= | ========================= | ================ | ================== | ======== | ================================ | ================================================= | =========== | ======= | ==================================================================================== | ============ | 
|                    | MD-02050301                       |                     | Conewago Creek          | 02050306 | 02050301   |               | CR     | RIVER      | 1st thru 4th order streams | 9.94                 | Miles                      | I         | Aquatic Life and Wildlife | 3                | Cause Unknown      |          | FALSE                            |                                                   |             |         |                                                                                      |              | 
| 2014               | MD-021202010319-Rock_Run1         | Rock Run            | Lower Susquehanna River | 02050306 | 02120201   | 021202010319  | CE     | RIVER      | Non-tidal Segment(s)       | 0.48                 | Miles                      | III-P     | Aquatic Life and Wildlife | 5                | Temperature, water | Low      | FALSE                            |                                                   |             |         | Temperature measurements exceed criteria and no coldwater obligate taxa were found.  |              | 
| 2014               | MD-021202010319-Rock_Run2         | Rock Run            | Lower Susquehanna River | 02050306 | 02120201   | 021202010319  | CE     | RIVER      | Non-tidal Segment(s)       | 0.9                  | Miles                      | III-P     | Aquatic Life and Wildlife | 5                | Temperature, water | Low      | FALSE                            |                                                   |             |         | Temperature measurements exceed criteria and no coldwater obligate taxa were found.  |              | 
|                    | MD-02120201-Mainstem              |                     | Lower Susquehanna River | 02050306 | 02120201   |               | CE, HA | RIVER      | River Mainstem             | 4.33                 | Miles                      | I         | Aquatic Life and Wildlife | 3                |                    |          | FALSE                            |                                                   |             |         | Mainstem of Lower Susquehanna River, below Conowingo Dam has not yet been assessed.  |              | 
| 2002               | MD-02120201-Non-mainstem          |                     | Lower Susquehanna River | 02050306 | 02120201   |               | CE, HA | RIVER      | 1st thru 4th order streams | 32.1                 | Miles                      | I         | Aquatic Life and Wildlife | 5                | Cause Unknown      | Low      | FALSE                            | 12-digit listings now subsumed by 8-digit listing | 2008        |         |                                                                                      |              | 
|                    | MD-02120202                       |                     | Deer Creek              | 02050306 | 02120202   |               | HA     | RIVER      | 1st thru 4th order streams | 270.42               | Miles                      | I         | Aquatic Life and Wildlife | 2                | Cause Unknown      |          | FALSE                            | 12-digit listings now subsumed by 8-digit listing | 2008        |         |                                                                                      |              | 
|                    | MD-021202020327-RockHollow_Branch | Rock Hollow Branch  | Deer Creek              | 02050306 | 02120202   | 021202020327  | HA     | RIVER      | Non-tidal Segment(s)       | 2.47                 | Miles                      | III-P     | Aquatic Life and Wildlife | 2                | Temperature, water |          | FALSE                            |                                                   |             |         | Logger data demonstrates attainment of temperature criteria (68 degrees Fahrenheit). |              | 
| 2014               | MD-021202020330-Deer_Creek1       | Deer Creek mainstem | Deer Creek              | 02050306 | 02120202   | 021202020330  | HA     | RIVER      | Non-tidal Segment(s)       | 0.92                 | Miles                      | III-P     | Aquatic Life and Wildlife | 5                | Temperature, water | Low      | FALSE                            |                                                   |             |         | Temperature measurements exceed criteria and no coldwater obligate taxa were found.  |              | 
| 2014               | MD-021202020330-Deer_Creek2       | Deer Creek mainstem | Deer Creek              | 02050306 | 02120202   | 021202020330  | HA     | RIVER      | Non-tidal Segment(s)       | 0.38                 | Miles                      | III-P     | Aquatic Life and Wildlife | 5                | Temperature, water | Low      | FALSE                            |                                                   |             |         | Temperature measurements exceed criteria and no coldwater obligate taxa were found.  |              | 
| 2014               | MD-021202020330-Deer_Creek3       | Deer Creek          | Deer Creek              | 02050306 | 02120202   | 021202020330  | HA     | RIVER      | Non-tidal Segment(s)       | 0.99                 | Miles                      | III-P     | Aquatic Life and Wildlife | 5                | Temperature, water | Low      | FALSE                            |                                                   |             |         | Temperature measurements exceed criteria and few coldwater obligate taxa were found. |              | 
```