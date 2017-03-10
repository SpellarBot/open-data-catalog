# Behind the Rocks Southwest NRZ Census Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/behind-the-rocks-southwest-nrz-census-data) |
| Metadata | [Link](https://data.hartford.gov/api/views/99t6-wshd) |
| Data: JSON | [100 Rows](https://data.hartford.gov/api/views/99t6-wshd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hartford.gov/api/views/99t6-wshd/rows.csv?max_rows=100) |
| Host | data.hartford.gov |
| Id | 99t6-wshd |
| Name | Behind the Rocks Southwest NRZ Census Data |
| Attribution | City of Hartford |
| Category | Community |
| Tags | behind the rocks, southwest, census, neighborhood, nrz, hartford |
| Created | 2015-01-09T18:17:38Z |
| Publication Date | 2015-01-13T03:35:22Z |
| Rows Updated | 2015-01-13T03:34:28Z |

## Description

This data contains information for the Southwest and Behind The Rocks NRZ Strategic Plan. It is Census Data for the years 1990, 2000, and 2010. The percentages shown are based on the  specific census tract.

## Columns

```ls
| Included | Schema Type    | Field Name                                                         | Name                                                               | Data Type | Render Type |
| ======== | ============== | ================================================================== | ================================================================== | ========= | =========== |
| Yes      | numeric metric | census_tract                                                       | Census Tract                                                       | number    | number      |
| Yes      | time           | year                                                               | Year                                                               | number    | number      |
| Yes      | series tag     | census_tract_by_year                                               | Census Tract by Year                                               | text      | text        |
| Yes      | series tag     | year_by_census_track                                               | Year by Census Track                                               | text      | text        |
| Yes      | series tag     | neighborhood                                                       | Neighborhood                                                       | text      | text        |
| Yes      | numeric metric | totalpopulation                                                    | TotalPopulation                                                    | number    | number      |
| Yes      | numeric metric | malepopulation                                                     | MalePopulation                                                     | number    | number      |
| Yes      | numeric metric | malepopulationper                                                  | MalePopulationPer                                                  | percent   | percent     |
| Yes      | numeric metric | femalepopulation                                                   | FemalePopulation                                                   | number    | number      |
| Yes      | numeric metric | femalepopulationper                                                | FemalePopulationPer                                                | percent   | percent     |
| Yes      | numeric metric | medianageyears                                                     | MedianAgeYears                                                     | number    | number      |
| Yes      | numeric metric | totalhouseholds                                                    | TotalHouseholds                                                    | number    | number      |
| Yes      | numeric metric | femalehouseholder                                                  | FemaleHouseholder                                                  | number    | number      |
| Yes      | numeric metric | femalehouseholderper                                               | FemaleHouseholderPer                                               | percent   | percent     |
| Yes      | numeric metric | occupiedhousingunits                                               | OccupiedHousingUnits                                               | number    | number      |
| Yes      | numeric metric | occupiedhousingunitsper                                            | OccupiedHousingUnitsPer                                            | percent   | percent     |
| Yes      | numeric metric | vacanthousingunits                                                 | VacantHousingUnits                                                 | number    | number      |
| Yes      | numeric metric | vacanthousingunitsper                                              | VacantHousingUnitsPer                                              | percent   | percent     |
| Yes      | numeric metric | owneroccupiedunits                                                 | OwnerOccupiedUnits                                                 | number    | number      |
| Yes      | numeric metric | owneroccupiedunitsper                                              | OwnerOccupiedUnitsPer                                              | percent   | percent     |
| Yes      | numeric metric | renteroccupiedunits                                                | RenterOccupiedUnits                                                | number    | number      |
| Yes      | numeric metric | renteroccupiedunitsper                                             | RenterOccupiedUnitsPer                                             | percent   | percent     |
| Yes      | numeric metric | homeownervacancyrateper                                            | HomeownerVacancyRatePer                                            | percent   | percent     |
| Yes      | numeric metric | rentervacancyrateper                                               | RenterVacancyRatePer                                               | percent   | percent     |
| Yes      | numeric metric | hispaniclatinopopulation                                           | HispanicLatinoPopulation                                           | number    | number      |
| Yes      | numeric metric | hispaniclatinopopulationper                                        | HispanicLatinoPopulationPer                                        | percent   | percent     |
| Yes      | numeric metric | nothispanicorlatino                                                | NotHispanicorLatino                                                | number    | number      |
| Yes      | numeric metric | nothispanicorlatinoper                                             | NotHispanicorLatinoPer                                             | percent   | percent     |
| Yes      | numeric metric | whitealone                                                         | Whitealone                                                         | number    | number      |
| Yes      | numeric metric | whitealoneper                                                      | WhitealonePer                                                      | percent   | percent     |
| Yes      | numeric metric | blackorafricanamerican                                             | BlackorAfricanAmerican                                             | number    | number      |
| Yes      | numeric metric | blackorafricanamericanper                                          | BlackorAfricanAmericanPer                                          | percent   | percent     |
| Yes      | numeric metric | puertorican                                                        | PuertoRican                                                        | number    | number      |
| Yes      | numeric metric | puertoricanper                                                     | PuertoRicanPer                                                     | percent   | percent     |
| Yes      | numeric metric | mexican                                                            | Mexican                                                            | number    | number      |
| Yes      | numeric metric | mexicanper                                                         | MexicanPer                                                         | percent   | percent     |
| Yes      | numeric metric | otherhispanicorlatino                                              | OtherHispanicorLatino                                              | number    | number      |
| Yes      | numeric metric | otherhispanicorlatinoper                                           | OtherHispanicorLatinoPer                                           | percent   | percent     |
| Yes      | numeric metric | other                                                              | Other                                                              | number    | number      |
| Yes      | numeric metric | otherper                                                           | OtherPer                                                           | percent   | percent     |
| Yes      | numeric metric | nothispanicorlatinoother                                           | NotHispanicorLatinoOther                                           | number    | number      |
| Yes      | numeric metric | nothispanicorlatinootherper                                        | NotHispanicorLatinoOtherPer                                        | percent   | percent     |
| Yes      | numeric metric | population18_24                                                    | Population18_24                                                    | number    | number      |
| Yes      | numeric metric | lessthanhighschoolgraduateper18_24                                 | LessthanHighSchoolGraduatePer18_24                                 | number    | number      |
| Yes      | numeric metric | highschoolgraduateorequivalencyper18_24                            | HighSchoolGraduateorequivalencyPer18_24                            | number    | number      |
| Yes      | numeric metric | somecollegeorassociatesdegreeper18_24                              | SomeCollegeorAssociatesDegreePer18_24                              | number    | number      |
| Yes      | numeric metric | bachelorsdegreeorhigherper18_24                                    | BachelorsDegreeorHigherPer18_24                                    | number    | number      |
| Yes      | numeric metric | population25andover                                                | Population25andover                                                | number    | number      |
| Yes      | numeric metric | lessthan9thgradeper25plus                                          | Lessthan9thGradePer25Plus                                          | number    | number      |
| Yes      | numeric metric | 9th_12thgradenodiplomaper25plus                                    | 9th_12thGradeNoDiplomaPer25Plus                                    | number    | number      |
| Yes      | numeric metric | highschoolgraduateorequivalencyper25plus                           | HighSchoolGraduateorequivalencyPer25Plus                           | number    | number      |
| Yes      | numeric metric | somecollegenodegreeper25plus                                       | SomeCollegeNoDegreePer25Plus                                       | number    | number      |
| Yes      | numeric metric | associatesdegreeper25plus                                          | AssociatesDegreePer25Plus                                          | number    | number      |
| Yes      | numeric metric | bachelorsdegreeper25plus                                           | BachelorsDegreePer25Plus                                           | number    | number      |
| Yes      | numeric metric | graduateorprofessionaldegreeper25plus                              | GraduateorProfessionalDegreePer25Plus                              | number    | number      |
| Yes      | numeric metric | highschoolgraduateorhigherper25plus                                | HighSchoolGraduateorHigherPer25Plus                                | number    | number      |
| Yes      | numeric metric | precentbachelorsdegreeorhigherper25plus                            | PrecentBachelorsDegreeorHigherPer25Plus                            | number    | number      |
| Yes      | numeric metric | population16yearsandoverinlaborforceper                            | Population16yearsandoverinLaborForcePer                            | percent   | percent     |
| Yes      | numeric metric | employedper                                                        | EmployedPer                                                        | percent   | percent     |
| Yes      | numeric metric | unemployedper                                                      | UnemployedPer                                                      | percent   | percent     |
| Yes      | numeric metric | privatewageandsalaryworkersper                                     | PrivatewageandsalaryworkersPer                                     | percent   | percent     |
| Yes      | numeric metric | governmentworkersper                                               | GovernmentworkersPer                                               | percent   | percent     |
| Yes      | numeric metric | selfemployedworkersinownnotincorporatedbusiness                    | Selfemployedworkersinownnotincorporatedbusiness                    | number    | number      |
| Yes      | numeric metric | medianhouseholdincome                                              | MedianHouseholdIncome                                              | money     | money       |
| Yes      | numeric metric | percapitaincome                                                    | Percapitaincome                                                    | number    | number      |
| Yes      | numeric metric | householdswithearningsper                                          | HouseholdswithearningsPer                                          | percent   | percent     |
| Yes      | numeric metric | householdswithsocialsecurityincomeper                              | HouseholdswithsocialsecurityincomePer                              | percent   | percent     |
| Yes      | numeric metric | withfoodstampsnapbenefitsinpast12monthsperofhouseholds             | WithFoodStampSNAPbenefitsinpast12monthsPerofhouseholds             | number    | number      |
| Yes      | numeric metric | householdswithpublicassistanceincomeper                            | HouseholdswithpublicassistanceincomePer                            | percent   | percent     |
| Yes      | numeric metric | familieswhoseincomeinpast12monthsisbelowpovertylineper             | FamilieswhoseIncomeinpast12monthsisbelowpovertylinePer             | percent   | percent     |
| Yes      | numeric metric | femaleheadedfamilieswhoseincomeinpast12monthsisbelowpovertylineper | FemaleHeadedFamilieswhoseIncomeinpast12monthsisbelowpovertylinePer | percent   | percent     |
| Yes      | numeric metric | allpeoplewhoseincomeinpast12monthsisbelowpovertylineper            | AllpeoplewhoseIncomeinpast12monthsisbelowpovertylinePer            | percent   | percent     |
| Yes      | numeric metric | peopleunder18belowthepovertylevelper                               | Peopleunder18belowthepovertylevelPer                               | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5045 - 1990" t:neighborhood="Behind the Rocks" t:year_by_census_track="1990 - 5045" m:medianhouseholdincome=30969 m:other=910 m:blackorafricanamerican=786 m:somecollegenodegreeper25plus=18 m:malepopulation=1601 m:whitealoneper=49 m:bachelorsdegreeper25plus=7 m:vacanthousingunits=81 m:femalepopulationper=53 m:totalhouseholds=1308 m:femalepopulation=1814 m:population18_24=393 m:census_tract=5045 m:blackorafricanamericanper=23 m:rentervacancyrateper=77 m:highschoolgraduateorequivalencyper25plus=29 m:population25andover=2144 m:malepopulationper=47 m:employedper=68 m:totalpopulation=3415 m:otherper=27 m:femalehouseholderper=20 m:highschoolgraduateorhigherper25plus=60 m:precentbachelorsdegreeorhigherper25plus=14 m:whitealone=1684 m:homeownervacancyrateper=0 m:femalehouseholder=266 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=13 m:graduateorprofessionaldegreeper25plus=7 m:unemployedper=4 m:population16yearsandoverinlaborforceper=72

series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5048 - 1990" t:neighborhood=Southwest t:year_by_census_track="1990 - 5048" m:medianhouseholdincome=36662 m:other=144 m:blackorafricanamerican=109 m:somecollegenodegreeper25plus=17 m:malepopulation=1860 m:whitealoneper=93 m:bachelorsdegreeper25plus=12 m:vacanthousingunits=48 m:femalepopulationper=55 m:totalhouseholds=1656 m:femalepopulation=2254 m:population18_24=307 m:census_tract=5048 m:blackorafricanamericanper=3 m:rentervacancyrateper=75 m:highschoolgraduateorequivalencyper25plus=37 m:population25andover=3200 m:malepopulationper=45 m:employedper=59 m:totalpopulation=4114 m:otherper=4 m:femalehouseholderper=10 m:highschoolgraduateorhigherper25plus=73 m:precentbachelorsdegreeorhigherper25plus=20 m:whitealone=3831 m:homeownervacancyrateper=0 m:femalehouseholder=172 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=3 m:graduateorprofessionaldegreeper25plus=8 m:unemployedper=3 m:population16yearsandoverinlaborforceper=61

series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5049 - 1990" t:neighborhood="Behind the Rocks" t:year_by_census_track="1990 - 5049" m:medianhouseholdincome=25009 m:other=935 m:blackorafricanamerican=1245 m:somecollegenodegreeper25plus=18 m:malepopulation=2590 m:whitealoneper=58 m:bachelorsdegreeper25plus=7 m:vacanthousingunits=109 m:femalepopulationper=53 m:totalhouseholds=1848 m:femalepopulation=2892 m:population18_24=671 m:census_tract=5049 m:blackorafricanamericanper=23 m:rentervacancyrateper=60 m:highschoolgraduateorequivalencyper25plus=29 m:population25andover=3054 m:malepopulationper=47 m:employedper=61 m:totalpopulation=5482 m:otherper=17 m:femalehouseholderper=29 m:highschoolgraduateorhigherper25plus=58 m:precentbachelorsdegreeorhigherper25plus=11 m:whitealone=3184 m:homeownervacancyrateper=7 m:femalehouseholder=535 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=22 m:graduateorprofessionaldegreeper25plus=4 m:unemployedper=7 m:population16yearsandoverinlaborforceper=68
```

## Meta Commands

```ls
metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:totalpopulation p:integer l:TotalPopulation t:dataTypeName=number

metric m:malepopulation p:integer l:MalePopulation t:dataTypeName=number

metric m:femalepopulation p:integer l:FemalePopulation t:dataTypeName=number

metric m:medianageyears p:integer l:MedianAgeYears t:dataTypeName=number

metric m:totalhouseholds p:integer l:TotalHouseholds t:dataTypeName=number

metric m:femalehouseholder p:integer l:FemaleHouseholder t:dataTypeName=number

metric m:occupiedhousingunits p:integer l:OccupiedHousingUnits t:dataTypeName=number

metric m:vacanthousingunits p:integer l:VacantHousingUnits t:dataTypeName=number

metric m:owneroccupiedunits p:integer l:OwnerOccupiedUnits t:dataTypeName=number

metric m:renteroccupiedunits p:integer l:RenterOccupiedUnits t:dataTypeName=number

metric m:hispaniclatinopopulation p:integer l:HispanicLatinoPopulation t:dataTypeName=number

metric m:nothispanicorlatino p:integer l:NotHispanicorLatino t:dataTypeName=number

metric m:whitealone p:integer l:Whitealone t:dataTypeName=number

metric m:blackorafricanamerican p:integer l:BlackorAfricanAmerican t:dataTypeName=number

metric m:puertorican p:integer l:PuertoRican t:dataTypeName=number

metric m:mexican p:integer l:Mexican t:dataTypeName=number

metric m:otherhispanicorlatino p:integer l:OtherHispanicorLatino t:dataTypeName=number

metric m:other p:integer l:Other t:dataTypeName=number

metric m:nothispanicorlatinoother p:integer l:NotHispanicorLatinoOther t:dataTypeName=number

metric m:population18_24 p:integer l:Population18_24 t:dataTypeName=number

metric m:lessthanhighschoolgraduateper18_24 p:integer l:LessthanHighSchoolGraduatePer18_24 t:dataTypeName=number

metric m:highschoolgraduateorequivalencyper18_24 p:integer l:HighSchoolGraduateorequivalencyPer18_24 t:dataTypeName=number

metric m:somecollegeorassociatesdegreeper18_24 p:integer l:SomeCollegeorAssociatesDegreePer18_24 t:dataTypeName=number

metric m:bachelorsdegreeorhigherper18_24 p:integer l:BachelorsDegreeorHigherPer18_24 t:dataTypeName=number

metric m:population25andover p:integer l:Population25andover t:dataTypeName=number

metric m:lessthan9thgradeper25plus p:integer l:Lessthan9thGradePer25Plus t:dataTypeName=number

metric m:9th_12thgradenodiplomaper25plus p:integer l:9th_12thGradeNoDiplomaPer25Plus t:dataTypeName=number

metric m:highschoolgraduateorequivalencyper25plus p:integer l:HighSchoolGraduateorequivalencyPer25Plus t:dataTypeName=number

metric m:somecollegenodegreeper25plus p:integer l:SomeCollegeNoDegreePer25Plus t:dataTypeName=number

metric m:associatesdegreeper25plus p:integer l:AssociatesDegreePer25Plus t:dataTypeName=number

metric m:bachelorsdegreeper25plus p:integer l:BachelorsDegreePer25Plus t:dataTypeName=number

metric m:graduateorprofessionaldegreeper25plus p:integer l:GraduateorProfessionalDegreePer25Plus t:dataTypeName=number

metric m:highschoolgraduateorhigherper25plus l:HighSchoolGraduateorHigherPer25Plus t:dataTypeName=number

metric m:precentbachelorsdegreeorhigherper25plus p:integer l:PrecentBachelorsDegreeorHigherPer25Plus t:dataTypeName=number

metric m:selfemployedworkersinownnotincorporatedbusiness p:integer l:Selfemployedworkersinownnotincorporatedbusiness t:dataTypeName=number

metric m:percapitaincome p:integer l:Percapitaincome t:dataTypeName=number

metric m:withfoodstampsnapbenefitsinpast12monthsperofhouseholds p:integer l:WithFoodStampSNAPbenefitsinpast12monthsPerofhouseholds t:dataTypeName=number

entity e:99t6-wshd l:"Behind the Rocks Southwest NRZ Census Data" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/99t6-wshd

property e:99t6-wshd t:meta.view v:id=99t6-wshd v:category=Community v:attributionLink=http://www.hartford.gov v:averageRating=0 v:name="Behind the Rocks Southwest NRZ Census Data" v:attribution="City of Hartford"

property e:99t6-wshd t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:99t6-wshd t:meta.view.owner v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett

property e:99t6-wshd t:meta.view.tableauthor v:id=cdqe-xcn5 v:screenName=Brett v:roleName=administrator v:displayName=Brett
```