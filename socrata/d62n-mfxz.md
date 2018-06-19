# Occupational Projections 2008-2018

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/occupational-projections-2008-2018-a55e6) |
| Metadata | [Link](https://data.mo.gov/api/views/d62n-mfxz) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/d62n-mfxz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/d62n-mfxz/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | d62n-mfxz |
| Name | Occupational Projections 2008-2018 |
| Category | Revenue |
| Tags | occupational, projections, occupational projections |
| Created | 2012-04-24T14:17:15Z |
| Publication Date | 2012-04-24T15:23:14Z |

## Description

Occupational Projections 2008-2018

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                        | Data Type | Render Type |
| ======== | ============== | ========================== | =========================== | ========= | =========== |
| Yes      | series tag     | occupationalgrade          | OccupationalGrade           | text      | text        |
| Yes      | series tag     | occupationalcode           | OccupationalCode            | text      | text        |
| Yes      | series tag     | occupationaltitle          | OccupationalTitle           | text      | text        |
| Yes      | numeric metric | estimatedemployment2008    | EstimatedEmployment2008     | number    | number      |
| Yes      | numeric metric | projectedemployment2018    | ProjectedEmployment2018     | number    | number      |
| Yes      | numeric metric | netchange20082018          | NetChange20082018           | number    | number      |
| Yes      | numeric metric | percentchange20082018      | PercentChange20082018       | percent   | percent     |
| Yes      | numeric metric | meanannualwages2008        | MeanAnnualWages2008         | money     | money       |
| Yes      | numeric metric | entryannualwages2008       | EntryAnnualWages2008        | money     | money       |
| Yes      | numeric metric | experiencedannualwages2008 | ExperiencedAnnualWages2008  | money     | money       |
| Yes      | numeric metric | openingsgrowth             | 20082018OpeningsGrowth      | number    | number      |
| Yes      | numeric metric | openingsreplacement        | 20082018OpeningsReplacement | number    | number      |
| Yes      | numeric metric | openingstotal              | 20082018OpeningsTotal       | number    | number      |
| Yes      | numeric metric | annualopeningsgrowth       | AnnualOpeningsGrowth        | number    | number      |
| Yes      | numeric metric | annualopeningsreplacement  | AnnualOpeningsReplacement   | number    | number      |
| Yes      | numeric metric | annualopeningstotal        | AnnualOpeningsTotal         | number    | number      |
| Yes      | series tag     | educationtrainingrequired  | EducationTrainingRequired   | text      | text        |
| Yes      | series tag     | wiaregion                  | WIARegion                   | text      | text        |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:d62n-mfxz d:2008-01-01T00:00:00.000Z t:educationtrainingrequired="Bachelor's or higher degree, plus work experience" t:wiaregion=Central t:occupationalcode=11-1011 t:occupationaltitle="Chief Executives" t:occupationalgrade=C+ m:openingstotal=207 m:experiencedannualwages2008=185830 m:openingsgrowth=0 m:percentchange20082018=-5.56 m:entryannualwages2008=75580 m:estimatedemployment2008=740 m:annualopeningsgrowth=0 m:annualopeningstotal=21 m:meanannualwages2008=149080 m:netchange20082018=-41 m:openingsreplacement=207 m:projectedemployment2018=700 m:annualopeningsreplacement=21

series e:d62n-mfxz d:2008-01-01T00:00:00.000Z t:educationtrainingrequired="Bachelor's or higher degree, plus work experience" t:wiaregion=Central t:occupationalcode=11-1021 t:occupationaltitle="General and Operations Managers" t:occupationalgrade=C+ m:openingstotal=857 m:experiencedannualwages2008=120600 m:openingsgrowth=0 m:percentchange20082018=-3.35 m:entryannualwages2008=46890 m:estimatedemployment2008=2960 m:annualopeningsgrowth=0 m:annualopeningstotal=86 m:meanannualwages2008=96030 m:netchange20082018=-99 m:openingsreplacement=857 m:projectedemployment2018=2860 m:annualopeningsreplacement=86

series e:d62n-mfxz d:2008-01-01T00:00:00.000Z t:educationtrainingrequired="Bachelor's or higher degree, plus work experience" t:wiaregion=Central t:occupationalcode=11-1031 t:occupationaltitle=Legislators t:occupationalgrade=F+ m:openingstotal=30 m:experiencedannualwages2008=41850 m:openingsgrowth=1 m:percentchange20082018=0.97 m:entryannualwages2008=19970 m:estimatedemployment2008=100 m:annualopeningsgrowth=0 m:annualopeningstotal=3 m:meanannualwages2008=34560 m:netchange20082018=1 m:openingsreplacement=29 m:projectedemployment2018=100 m:annualopeningsreplacement=3
```

## Meta Commands

```ls
metric m:estimatedemployment2008 p:integer l:EstimatedEmployment2008 d:"Estimated Employment 2008" t:dataTypeName=number

metric m:projectedemployment2018 p:integer l:ProjectedEmployment2018 d:"Projected Employment 2018" t:dataTypeName=number

metric m:netchange20082018 p:integer l:NetChange20082018 d:"Net Change 2008-2018" t:dataTypeName=number

metric m:percentchange20082018 p:float l:PercentChange20082018 d:"Percent Change 2008-2018" t:dataTypeName=percent

metric m:meanannualwages2008 p:integer l:MeanAnnualWages2008 d:"Mean Annual Wages 2008" t:dataTypeName=money

metric m:entryannualwages2008 p:integer l:EntryAnnualWages2008 d:"Entry Annual Wages 2008" t:dataTypeName=money

metric m:experiencedannualwages2008 p:integer l:ExperiencedAnnualWages2008 d:"Experienced Annual Wages 2008" t:dataTypeName=money

metric m:openingsgrowth p:integer l:20082018OpeningsGrowth d:"2008-2018 Openings Growth" t:dataTypeName=number

metric m:openingsreplacement p:integer l:20082018OpeningsReplacement d:"2008-2018 Openings Replacement" t:dataTypeName=number

metric m:openingstotal p:integer l:20082018OpeningsTotal d:"2008-2018 Openings Total" t:dataTypeName=number

metric m:annualopeningsgrowth p:integer l:AnnualOpeningsGrowth d:"Annual Openings Growth" t:dataTypeName=number

metric m:annualopeningsreplacement p:integer l:AnnualOpeningsReplacement d:"Annual Openings Replacement" t:dataTypeName=number

metric m:annualopeningstotal p:integer l:AnnualOpeningsTotal d:"Annual Openings Total" t:dataTypeName=number

entity e:d62n-mfxz l:"Occupational Projections 2008-2018" t:url=https://data.mo.gov/api/views/d62n-mfxz

property e:d62n-mfxz t:meta.view v:id=d62n-mfxz v:category=Revenue v:averageRating=0 v:name="Occupational Projections 2008-2018"

property e:d62n-mfxz t:meta.view.owner v:id=gp37-vwsj v:profileImageUrlMedium=/api/users/gp37-vwsj/profile_images/THUMB v:profileImageUrlLarge=/api/users/gp37-vwsj/profile_images/LARGE v:screenName="Stuart Knight" v:profileImageUrlSmall=/api/users/gp37-vwsj/profile_images/TINY v:displayName="Stuart Knight"

property e:d62n-mfxz t:meta.view.tableauthor v:id=gp37-vwsj v:profileImageUrlMedium=/api/users/gp37-vwsj/profile_images/THUMB v:profileImageUrlLarge=/api/users/gp37-vwsj/profile_images/LARGE v:screenName="Stuart Knight" v:profileImageUrlSmall=/api/users/gp37-vwsj/profile_images/TINY v:displayName="Stuart Knight"
```

## Top Records

```ls
| occupationalgrade | occupationalcode | occupationaltitle                         | estimatedemployment2008 | projectedemployment2018 | netchange20082018 | percentchange20082018 | meanannualwages2008 | entryannualwages2008 | experiencedannualwages2008 | openingsgrowth | openingsreplacement | openingstotal | annualopeningsgrowth | annualopeningsreplacement | annualopeningstotal | educationtrainingrequired                         | wiaregion | 
| ================= | ================ | ========================================= | ======================= | ======================= | ================= | ===================== | =================== | ==================== | ========================== | ============== | =================== | ============= | ==================== | ========================= | =================== | ================================================= | ========= | 
| C+                | 11-1011          | Chief Executives                          | 740                     | 700                     | -41               | -5.56                 | 149080              | 75580                | 185830                     | 0              | 207                 | 207           | 0                    | 21                        | 21                  | Bachelor's or higher degree, plus work experience | Central   | 
| C+                | 11-1021          | General and Operations Managers           | 2960                    | 2860                    | -99               | -3.35                 | 96030               | 46890                | 120600                     | 0              | 857                 | 857           | 0                    | 86                        | 86                  | Bachelor's or higher degree, plus work experience | Central   | 
| F+                | 11-1031          | Legislators                               | 100                     | 100                     | 1                 | 0.97                  | 34560               | 19970                | 41850                      | 1              | 29                  | 30            | 0                    | 3                         | 3                   | Bachelor's or higher degree, plus work experience | Central   | 
| D                 | 11-2011          | Advertising and Promotions Managers       | 50                      | 50                      | -4                | -7.41                 | 78080               | 39840                | 97200                      | 0              | 13                  | 13            | 0                    | 1                         | 1                   | Bachelor's or higher degree, plus work experience | Central   | 
| B+                | 11-2021          | Marketing Managers                        | 190                     | 210                     | 15                | 7.77                  | 111260              | 61590                | 136100                     | 15             | 42                  | 57            | 2                    | 4                         | 6                   | Bachelor's or higher degree, plus work experience | Central   | 
| A-                | 11-2022          | Sales Managers                            | 340                     | 390                     | 42                | 12.24                 | 110580              | 57840                | 136960                     | 42             | 74                  | 116           | 4                    | 7                         | 11                  | Bachelor's or higher degree, plus work experience | Central   | 
| B-                | 11-2031          | Public Relations Managers                 | 120                     | 120                     | 8                 | 6.90                  | 91340               | 57340                | 108340                     | 8              | 27                  | 35            | 1                    | 3                         | 4                   | Bachelor's or higher degree, plus work experience | Central   | 
| B+                | 11-3011          | Administrative Services Managers          | 390                     | 410                     | 23                | 5.94                  | 76600               | 43470                | 93160                      | 23             | 81                  | 104           | 2                    | 8                         | 10                  | Bachelor's or higher degree, plus work experience | Central   | 
| A-                | 11-3021          | Computer and Information Systems Managers | 430                     | 480                     | 50                | 11.60                 | 102260              | 71420                | 117680                     | 50             | 70                  | 120           | 5                    | 7                         | 12                  | Bachelor's or higher degree, plus work experience | Central   | 
| B+                | 11-3031          | Financial Managers                        | 550                     | 570                     | 22                | 4.03                  | 110280              | 64670                | 133080                     | 22             | 98                  | 120           | 2                    | 10                        | 12                  | Bachelor's or higher degree, plus work experience | Central   | 
```