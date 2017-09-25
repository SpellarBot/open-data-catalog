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
series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5045 - 1990" t:neighborhood="Behind the Rocks" t:year_by_census_track="1990 - 5045" m:population18_24=393 m:other=910 m:medianhouseholdincome=30969 m:rentervacancyrateper=77 m:whitealoneper=49 m:highschoolgraduateorequivalencyper25plus=29 m:femalepopulation=1814 m:femalehouseholderper=20 m:blackorafricanamericanper=23 m:population16yearsandoverinlaborforceper=72 m:homeownervacancyrateper=0 m:whitealone=1684 m:graduateorprofessionaldegreeper25plus=7 m:somecollegenodegreeper25plus=18 m:femalehouseholder=266 m:census_tract=5045 m:malepopulationper=47 m:blackorafricanamerican=786 m:population25andover=2144 m:unemployedper=4 m:vacanthousingunits=81 m:totalhouseholds=1308 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=13 m:highschoolgraduateorhigherper25plus=60 m:bachelorsdegreeper25plus=7 m:employedper=68 m:totalpopulation=3415 m:femalepopulationper=53 m:precentbachelorsdegreeorhigherper25plus=14 m:malepopulation=1601 m:otherper=27

series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5048 - 1990" t:neighborhood=Southwest t:year_by_census_track="1990 - 5048" m:population18_24=307 m:other=144 m:medianhouseholdincome=36662 m:rentervacancyrateper=75 m:whitealoneper=93 m:highschoolgraduateorequivalencyper25plus=37 m:femalepopulation=2254 m:femalehouseholderper=10 m:blackorafricanamericanper=3 m:population16yearsandoverinlaborforceper=61 m:homeownervacancyrateper=0 m:whitealone=3831 m:graduateorprofessionaldegreeper25plus=8 m:somecollegenodegreeper25plus=17 m:femalehouseholder=172 m:census_tract=5048 m:malepopulationper=45 m:blackorafricanamerican=109 m:population25andover=3200 m:unemployedper=3 m:vacanthousingunits=48 m:totalhouseholds=1656 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=3 m:highschoolgraduateorhigherper25plus=73 m:bachelorsdegreeper25plus=12 m:employedper=59 m:totalpopulation=4114 m:femalepopulationper=55 m:precentbachelorsdegreeorhigherper25plus=20 m:malepopulation=1860 m:otherper=4

series e:99t6-wshd d:1990-01-01T00:00:00.000Z t:census_tract_by_year="5049 - 1990" t:neighborhood="Behind the Rocks" t:year_by_census_track="1990 - 5049" m:population18_24=671 m:other=935 m:medianhouseholdincome=25009 m:rentervacancyrateper=60 m:whitealoneper=58 m:highschoolgraduateorequivalencyper25plus=29 m:femalepopulation=2892 m:femalehouseholderper=29 m:blackorafricanamericanper=23 m:population16yearsandoverinlaborforceper=68 m:homeownervacancyrateper=7 m:whitealone=3184 m:graduateorprofessionaldegreeper25plus=4 m:somecollegenodegreeper25plus=18 m:femalehouseholder=535 m:census_tract=5049 m:malepopulationper=47 m:blackorafricanamerican=1245 m:population25andover=3054 m:unemployedper=7 m:vacanthousingunits=109 m:totalhouseholds=1848 m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper=22 m:highschoolgraduateorhigherper25plus=58 m:bachelorsdegreeper25plus=7 m:employedper=61 m:totalpopulation=5482 m:femalepopulationper=53 m:precentbachelorsdegreeorhigherper25plus=11 m:malepopulation=2590 m:otherper=17
```

## Meta Commands

```ls
metric m:census_tract p:integer l:"Census Tract" t:dataTypeName=number

metric m:totalpopulation p:integer l:TotalPopulation t:dataTypeName=number

metric m:malepopulation p:integer l:MalePopulation t:dataTypeName=number

metric m:malepopulationper p:integer l:MalePopulationPer t:dataTypeName=percent

metric m:femalepopulation p:integer l:FemalePopulation t:dataTypeName=number

metric m:femalepopulationper p:integer l:FemalePopulationPer t:dataTypeName=percent

metric m:medianageyears p:integer l:MedianAgeYears t:dataTypeName=number

metric m:totalhouseholds p:integer l:TotalHouseholds t:dataTypeName=number

metric m:femalehouseholder p:integer l:FemaleHouseholder t:dataTypeName=number

metric m:femalehouseholderper p:integer l:FemaleHouseholderPer t:dataTypeName=percent

metric m:occupiedhousingunits p:integer l:OccupiedHousingUnits t:dataTypeName=number

metric m:occupiedhousingunitsper p:integer l:OccupiedHousingUnitsPer t:dataTypeName=percent

metric m:vacanthousingunits p:integer l:VacantHousingUnits t:dataTypeName=number

metric m:vacanthousingunitsper p:integer l:VacantHousingUnitsPer t:dataTypeName=percent

metric m:owneroccupiedunits p:integer l:OwnerOccupiedUnits t:dataTypeName=number

metric m:owneroccupiedunitsper p:integer l:OwnerOccupiedUnitsPer t:dataTypeName=percent

metric m:renteroccupiedunits p:integer l:RenterOccupiedUnits t:dataTypeName=number

metric m:renteroccupiedunitsper p:integer l:RenterOccupiedUnitsPer t:dataTypeName=percent

metric m:homeownervacancyrateper p:double l:HomeownerVacancyRatePer t:dataTypeName=percent

metric m:rentervacancyrateper p:integer l:RenterVacancyRatePer t:dataTypeName=percent

metric m:hispaniclatinopopulation p:integer l:HispanicLatinoPopulation t:dataTypeName=number

metric m:hispaniclatinopopulationper p:integer l:HispanicLatinoPopulationPer t:dataTypeName=percent

metric m:nothispanicorlatino p:integer l:NotHispanicorLatino t:dataTypeName=number

metric m:nothispanicorlatinoper p:integer l:NotHispanicorLatinoPer t:dataTypeName=percent

metric m:whitealone p:integer l:Whitealone t:dataTypeName=number

metric m:whitealoneper p:integer l:WhitealonePer t:dataTypeName=percent

metric m:blackorafricanamerican p:integer l:BlackorAfricanAmerican t:dataTypeName=number

metric m:blackorafricanamericanper p:integer l:BlackorAfricanAmericanPer t:dataTypeName=percent

metric m:puertorican p:integer l:PuertoRican t:dataTypeName=number

metric m:puertoricanper p:double l:PuertoRicanPer t:dataTypeName=percent

metric m:mexican p:integer l:Mexican t:dataTypeName=number

metric m:mexicanper p:double l:MexicanPer t:dataTypeName=percent

metric m:otherhispanicorlatino p:integer l:OtherHispanicorLatino t:dataTypeName=number

metric m:otherhispanicorlatinoper p:integer l:OtherHispanicorLatinoPer t:dataTypeName=percent

metric m:other p:integer l:Other t:dataTypeName=number

metric m:otherper p:integer l:OtherPer t:dataTypeName=percent

metric m:nothispanicorlatinoother p:integer l:NotHispanicorLatinoOther t:dataTypeName=number

metric m:nothispanicorlatinootherper p:integer l:NotHispanicorLatinoOtherPer t:dataTypeName=percent

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

metric m:highschoolgraduateorhigherper25plus p:double l:HighSchoolGraduateorHigherPer25Plus t:dataTypeName=number

metric m:precentbachelorsdegreeorhigherper25plus p:integer l:PrecentBachelorsDegreeorHigherPer25Plus t:dataTypeName=number

metric m:population16yearsandoverinlaborforceper p:integer l:Population16yearsandoverinLaborForcePer t:dataTypeName=percent

metric m:employedper p:integer l:EmployedPer t:dataTypeName=percent

metric m:unemployedper p:integer l:UnemployedPer t:dataTypeName=percent

metric m:privatewageandsalaryworkersper p:integer l:PrivatewageandsalaryworkersPer t:dataTypeName=percent

metric m:governmentworkersper p:integer l:GovernmentworkersPer t:dataTypeName=percent

metric m:selfemployedworkersinownnotincorporatedbusiness p:integer l:Selfemployedworkersinownnotincorporatedbusiness t:dataTypeName=number

metric m:medianhouseholdincome p:integer l:MedianHouseholdIncome t:dataTypeName=money

metric m:percapitaincome p:integer l:Percapitaincome t:dataTypeName=number

metric m:householdswithearningsper p:integer l:HouseholdswithearningsPer t:dataTypeName=percent

metric m:householdswithsocialsecurityincomeper p:integer l:HouseholdswithsocialsecurityincomePer t:dataTypeName=percent

metric m:withfoodstampsnapbenefitsinpast12monthsperofhouseholds p:integer l:WithFoodStampSNAPbenefitsinpast12monthsPerofhouseholds t:dataTypeName=number

metric m:householdswithpublicassistanceincomeper p:integer l:HouseholdswithpublicassistanceincomePer t:dataTypeName=percent

metric m:familieswhoseincomeinpast12monthsisbelowpovertylineper p:integer l:FamilieswhoseIncomeinpast12monthsisbelowpovertylinePer t:dataTypeName=percent

metric m:femaleheadedfamilieswhoseincomeinpast12monthsisbelowpovertylineper p:integer l:FemaleHeadedFamilieswhoseIncomeinpast12monthsisbelowpovertylinePer t:dataTypeName=percent

metric m:allpeoplewhoseincomeinpast12monthsisbelowpovertylineper p:integer l:AllpeoplewhoseIncomeinpast12monthsisbelowpovertylinePer t:dataTypeName=percent

metric m:peopleunder18belowthepovertylevelper p:integer l:Peopleunder18belowthepovertylevelPer t:dataTypeName=percent

entity e:99t6-wshd l:"Behind the Rocks Southwest NRZ Census Data" t:attribution="City of Hartford" t:url=https://data.hartford.gov/api/views/99t6-wshd

property e:99t6-wshd t:meta.view d:2017-09-25T07:29:14.290Z v:averageRating=0 v:name="Behind the Rocks Southwest NRZ Census Data" v:attribution="City of Hartford" v:attributionLink=http://www.hartford.gov v:id=99t6-wshd v:category=Community

property e:99t6-wshd t:meta.view.license d:2017-09-25T07:29:14.290Z v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:99t6-wshd t:meta.view.owner d:2017-09-25T07:29:14.290Z v:displayName=Brett v:id=cdqe-xcn5 v:screenName=Brett

property e:99t6-wshd t:meta.view.tableauthor d:2017-09-25T07:29:14.290Z v:displayName=Brett v:roleName=administrator v:id=cdqe-xcn5 v:screenName=Brett
```

## Top Records

```ls
| census_tract | year | census_tract_by_year | year_by_census_track | neighborhood                | totalpopulation | malepopulation | malepopulationper | femalepopulation | femalepopulationper | medianageyears | totalhouseholds | femalehouseholder | femalehouseholderper | occupiedhousingunits | occupiedhousingunitsper | vacanthousingunits | vacanthousingunitsper | owneroccupiedunits | owneroccupiedunitsper | renteroccupiedunits | renteroccupiedunitsper | homeownervacancyrateper | rentervacancyrateper | hispaniclatinopopulation | hispaniclatinopopulationper | nothispanicorlatino | nothispanicorlatinoper | whitealone | whitealoneper | blackorafricanamerican | blackorafricanamericanper | puertorican | puertoricanper | mexican | mexicanper | otherhispanicorlatino | otherhispanicorlatinoper | other | otherper | nothispanicorlatinoother | nothispanicorlatinootherper | population18_24 | lessthanhighschoolgraduateper18_24 | highschoolgraduateorequivalencyper18_24 | somecollegeorassociatesdegreeper18_24 | bachelorsdegreeorhigherper18_24 | population25andover | lessthan9thgradeper25plus | 9th_12thgradenodiplomaper25plus | highschoolgraduateorequivalencyper25plus | somecollegenodegreeper25plus | associatesdegreeper25plus | bachelorsdegreeper25plus | graduateorprofessionaldegreeper25plus | highschoolgraduateorhigherper25plus | precentbachelorsdegreeorhigherper25plus | population16yearsandoverinlaborforceper | employedper | unemployedper | privatewageandsalaryworkersper | governmentworkersper | selfemployedworkersinownnotincorporatedbusiness | medianhouseholdincome | percapitaincome | householdswithearningsper | householdswithsocialsecurityincomeper | withfoodstampsnapbenefitsinpast12monthsperofhouseholds | householdswithpublicassistanceincomeper | familieswhoseincomeinpast12monthsisbelowpovertylineper | femaleheadedfamilieswhoseincomeinpast12monthsisbelowpovertylineper | allpeoplewhoseincomeinpast12monthsisbelowpovertylineper | peopleunder18belowthepovertylevelper | 
| ============ | ==== | ==================== | ==================== | =========================== | =============== | ============== | ================= | ================ | =================== | ============== | =============== | ================= | ==================== | ==================== | ======================= | ================== | ===================== | ================== | ===================== | =================== | ====================== | ======================= | ==================== | ======================== | =========================== | =================== | ====================== | ========== | ============= | ====================== | ========================= | =========== | ============== | ======= | ========== | ===================== | ======================== | ===== | ======== | ======================== | =========================== | =============== | ================================== | ======================================= | ===================================== | =============================== | =================== | ========================= | =============================== | ======================================== | ============================ | ========================= | ======================== | ===================================== | =================================== | ======================================= | ======================================= | =========== | ============= | ============================== | ==================== | =============================================== | ===================== | =============== | ========================= | ===================================== | ====================================================== | ======================================= | ====================================================== | ================================================================== | ======================================================= | ==================================== | 
| 5045         | 1990 | 5045 - 1990          | 1990 - 5045          | Behind the Rocks            | 3415            | 1601           | 47                | 1814             | 53                  |                | 1308            | 266               | 20                   |                      |                         | 81                 |                       |                    |                       |                     |                        | 0                       | 77                   |                          |                             |                     |                        | 1684       | 49            | 786                    | 23                        |             |                |         |            |                       |                          | 910   | 27       |                          |                             | 393             |                                    |                                         |                                       |                                 | 2144                |                           |                                 | 29                                       | 18                           |                           | 7                        | 7                                     | 60                                  | 14                                      | 72                                      | 68          | 4             |                                |                      |                                                 | 30969                 |                 |                           |                                       |                                                        |                                         |                                                        |                                                                    | 13                                                      |                                      | 
| 5048         | 1990 | 5048 - 1990          | 1990 - 5048          | Southwest                   | 4114            | 1860           | 45                | 2254             | 55                  |                | 1656            | 172               | 10                   |                      |                         | 48                 |                       |                    |                       |                     |                        | 0                       | 75                   |                          |                             |                     |                        | 3831       | 93            | 109                    | 3                         |             |                |         |            |                       |                          | 144   | 4        |                          |                             | 307             |                                    |                                         |                                       |                                 | 3200                |                           |                                 | 37                                       | 17                           |                           | 12                       | 8                                     | 73                                  | 20                                      | 61                                      | 59          | 3             |                                |                      |                                                 | 36662                 |                 |                           |                                       |                                                        |                                         |                                                        |                                                                    | 3                                                       |                                      | 
| 5049         | 1990 | 5049 - 1990          | 1990 - 5049          | Behind the Rocks            | 5482            | 2590           | 47                | 2892             | 53                  |                | 1848            | 535               | 29                   |                      |                         | 109                |                       |                    |                       |                     |                        | 7                       | 60                   |                          |                             |                     |                        | 3184       | 58            | 1245                   | 23                        |             |                |         |            |                       |                          | 935   | 17       |                          |                             | 671             |                                    |                                         |                                       |                                 | 3054                |                           |                                 | 29                                       | 18                           |                           | 7                        | 4                                     | 58                                  | 11                                      | 68                                      | 61          | 7             |                                |                      |                                                 | 25009                 |                 |                           |                                       |                                                        |                                         |                                                        |                                                                    | 22                                                      |                                      | 
| 5247         | 1990 | 5247 - 1990          | 1990 - 5247          | Behind the Rocks /Southwest | 6327            | 2899           | 46                | 3428             | 54                  |                | 1888            | 887               | 47                   |                      |                         | 54                 |                       |                    |                       |                     |                        | 30                      | 59                   |                          |                             |                     |                        | 2796       | 44            | 1506                   | 24                        |             |                |         |            |                       |                          | 1920  | 30       |                          |                             | 735             |                                    |                                         |                                       |                                 | 3025                |                           |                                 | 28                                       | 11                           |                           | 7                        | 2                                     | 47                                  | 9                                       | 53                                      | 46          | 7             |                                |                      |                                                 |                       |                 |                           |                                       |                                                        |                                         |                                                        |                                                                    | 38                                                      |                                      | 
| 5045         | 2000 | 5045 - 2000          | 2000 - 5045          | Behind the Rocks            | 3597            | 1723           | 48                | 1874             | 52                  | 29             | 1222            | 387               | 31                   | 1222                 | 91                      | 117                | 9                     | 396                | 32                    | 826                 | 68                     | 2                       | 9                    | 2275                     | 63                          | 1322                | 37                     | 476        | 13            | 705                    | 20                        | 1896        | 52.7           | 28      | 1          | 340                   | 10                       | 1640  | 46       |                          |                             | 372             | 49                                 | 49                                      | 49                                    | 49                              | 2057                | 18                        | 19                              | 31                                       | 19                           | 2                         | 7                        | 4                                     | 63                                  | 11                                      | 63                                      | 58          | 5             | 80                             | 18                   | 1                                               | 31953                 | 13852           | 79                        | 18                                    |                                                        | 14                                      | 20                                                     | 30                                                                 | 21                                                      | 29                                   | 
| 5048         | 2000 | 5048 - 2000          | 2000 - 5048          | Southwest                   | 4750            | 2134           | 45                | 2616             | 55                  | 40             | 1694            | 288               | 17                   | 1694                 | 97                      | 57                 | 3                     | 1106               | 65                    | 588                 | 35                     | 0.4                     | 5                    | 1731                     | 36                          | 3019                | 64                     | 2118       | 45            | 702                    | 15                        | 1315        | 28             | 10      | 0.2        | 370                   | 8                        | 1115  | 24       |                          |                             | 321             | 33                                 | 37                                      | 26                                    | 4                               | 3324                | 13                        | 18                              | 34                                       | 18                           | 2                         | 11                       | 5                                     | 69                                  | 15                                      | 54                                      | 51          | 3             | 79                             | 17                   | 4                                               | 37855                 | 16797           | 74                        | 32                                    |                                                        | 8                                       | 6                                                      | 9                                                                  | 6                                                       | 6                                    | 
| 5049         | 2000 | 5049 - 2000          | 2000 - 5049          | Behind the Rocks            | 4415            | 2133           | 48                | 2282             | 52                  | 30             | 1411            | 454               | 32                   | 1411                 | 94                      | 96                 | 6                     | 528                | 37                    | 883                 | 63                     | 1                       | 7                    | 2901                     | 66                          | 1514                | 34                     | 619        | 14            | 713                    | 16                        | 2534        | 57             | 28      | 1          | 321                   | 7                        | 1971  | 45       |                          |                             | 465             | 39                                 | 47                                      | 11                                    | 3                               | 2491                | 37                        | 21                              | 33                                       | 13                           | 3                         | 2                        | 2                                     | 53                                  | 4                                       | 54                                      | 51          | 3             | 79                             | 17                   | 4                                               | 29758                 | 16797           | 74                        | 32                                    |                                                        | 8                                       | 24                                                     | 30                                                                 | 26                                                      | 33                                   | 
| 5247         | 2000 | 5247 - 2000          | 2000 - 5247          | Behind the Rocks /Southwest | 3168            | 1455           | 46                | 1713             | 54                  | 34             | 1106            | 313               | 28                   | 1106                 | 93                      | 84                 | 7                     | 602                | 54                    | 504                 | 46                     | 2                       | 9                    | 1506                     | 48                          | 1635                | 52                     | 886        | 28            | 667                    | 21                        | 1210        | 38             | 5       | 0.1        | 268                   | 8                        | 705   | 22       |                          |                             | 278             | 38                                 | 37                                      | 21                                    | 4                               | 1961                | 16                        | 25                              | 24                                       | 18                           | 5                         | 8                        | 5                                     | 0.1                                 | 0                                       | 59                                      | 54          | 5             | 81                             | 13                   | 6                                               |                       | 14833           | 72                        | 33                                    |                                                        | 12                                      | 20                                                     | 37                                                                 | 19                                                      | 31                                   | 
| 5045         | 2010 | 5045 - 2010          | 2010 - 5045          | Behind the Rocks            | 3701            | 1745           | 47                | 1956             | 53                  | 31             | 1299            | 458               | 35                   | 1299                 | 93                      | 99                 | 7                     | 412                | 32                    | 887                 | 68                     | 1                       | 6                    | 2649                     | 72                          | 1052                | 28                     | 964        | 26            | 774                    | 21                        | 2088        | 56             | 47      | 1          | 492                   | 13                       | 1380  | 37       | 31                       | 1                           | 232             | 26                                 | 44                                      | 31                                    | 0                               | 2364                | 16                        | 17                              | 40                                       | 17                           | 3                         | 6                        | 1                                     | 67                                  | 7                                       | 76                                      | 56          | 20            | 85                             | 9                    | 7                                               | 34494                 | 19876           | 77                        | 23                                    | 26                                                     | 6                                       | 16                                                     | 30                                                                 | 19                                                      | 22                                   | 
| 5048         | 2010 | 5048 - 2010          | 2010 - 5048          | Southwest                   | 4560            | 2180           | 48                | 2380             | 52                  | 37             | 1597            | 385               | 24                   | 1597                 | 94                      | 97                 | 6                     | 1068               | 67                    | 529                 | 33                     | 1                       | 7                    | 2582                     | 57                          | 1978                | 43                     | 1150       | 25            | 957                    | 21                        | 1947        | 43             | 37      | 1          | 567                   | 12                       | 1182  | 26       | 49                       | 1                           | 447             | 26                                 | 46                                      | 22                                    | 6                               | 3503                | 12                        | 9                               | 38                                       | 20                           | 6                         | 10                       | 6                                     | 79                                  | 16                                      | 67                                      | 64          | 3             | 81                             | 17                   | 2                                               | 57207                 | 25721           | 79                        | 29                                    | 10                                                     | 5                                       | 6                                                      | 4                                                                  | 9                                                       | 14                                   | 
```