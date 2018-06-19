# San Francisco Flood Health Vulnerability

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/san-francisco-flood-health-vulnerability-0ca93) |
| Metadata | [Link](https://data.sfgov.org/api/views/cne3-h93g) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/cne3-h93g/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/cne3-h93g/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | cne3-h93g |
| Name | San Francisco Flood Health Vulnerability |
| Attribution | SFDPH |
| Category | Health and Social Services |
| Tags | climate change, flood, sea level rise, health impacts, health assessment, san francisco climate and health program, sfclimatehealth.org, community resiliency, public health, @sfclimatehealth.org, ... |
| Created | 2016-03-10T01:55:38Z |
| Publication Date | 2016-03-25T00:38:12Z |

## Description

The San Francisco Department of Public Health Flood Health Vulnerability Index is a composite index that measures the spatial distribution and relative vulnerability of San Francisco communities to the health impacts of flood inundation and extreme storms. The index is constructed using socioeconomic and demographic, exposure, health, and housing indicators and is intended to serve as a planning tool for health and climate adaptation. Steps for calculating the index can be found in in the "An Assessment of San Francisco?s Vulnerability to Flooding & Extreme Storms" located at https://extxfer.sfdph.org/gis/Flooding/SFDPH_FloodHealthVulnerability2016.pdf.

Data dictionary can be found in the attachments section of the metadata.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| No       | time           | :updated_at                | updated_at                 | meta_data | meta_data   |
| Yes      | series tag     | census_blockgroup          | Census Blockgroup          | text      | text        |
| Yes      | numeric metric | children                   | Children                   | number    | number      |
| Yes      | numeric metric | children_wnullvalues       | Children_wNULLvalues       | number    | number      |
| Yes      | numeric metric | elderly                    | Elderly                    | number    | number      |
| Yes      | numeric metric | elderly_wnullvalues        | Elderly_wNULLvalues        | number    | number      |
| Yes      | numeric metric | nonwhite                   | NonWhite                   | number    | number      |
| Yes      | numeric metric | nonwhite_wnullvalues       | NonWhite_wNullvalues       | number    | number      |
| Yes      | numeric metric | poverty                    | Poverty                    | number    | number      |
| Yes      | numeric metric | poverty_wnullvalues        | Poverty_wNULLvalues        | number    | number      |
| Yes      | numeric metric | education                  | Education                  | number    | number      |
| Yes      | numeric metric | education_wnullvalues      | Education_wNULLvalues      | number    | number      |
| Yes      | numeric metric | english                    | English                    | number    | number      |
| Yes      | numeric metric | english_wnullvalues        | English_wNULLvalues        | number    | number      |
| Yes      | numeric metric | elevation                  | Elevation                  | number    | number      |
| Yes      | numeric metric | sealevelrise               | SeaLevelRise               | number    | number      |
| Yes      | numeric metric | precipitation              | Precipitation              | number    | number      |
| Yes      | numeric metric | diabetes                   | Diabetes                   | number    | number      |
| Yes      | numeric metric | mentalhealth               | MentalHealth               | number    | number      |
| Yes      | numeric metric | asthma                     | Asthma                     | number    | number      |
| Yes      | numeric metric | disability                 | Disability                 | number    | number      |
| Yes      | numeric metric | disability_wnullvalues     | Disability_wNULLvalues     | number    | number      |
| Yes      | numeric metric | housingquality             | HousingQuality             | number    | number      |
| Yes      | numeric metric | homeless                   | Homeless                   | number    | number      |
| Yes      | numeric metric | livalone                   | LivAlone                   | number    | number      |
| Yes      | numeric metric | livalone_wnullvalues       | LivAlone_wNULLvalues       | number    | number      |
| Yes      | numeric metric | floodhealthindex           | FloodHealthIndex           | number    | number      |
| Yes      | numeric metric | floodhealthindex_quintiles | FloodHealthIndex_Quintiles | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:cne3-h93g d:2016-03-10T13:51:28.000Z t:census_blockgroup=060759809001 m:education_wnullvalues=0.996079927094 m:floodhealthindex=84.81899999999999 m:elevation=-6 m:diabetes=22.0584 m:children=0.0729571224289 m:nonwhite=0.599175 m:education=0.996079927094 m:nonwhite_wnullvalues=0.599175 m:livalone_wnullvalues=0.48059111555 m:housingquality=14.1093 m:poverty=0.356678376001 m:homeless=17.5025 m:mentalhealth=36.52 m:precipitation=0.035771 m:floodhealthindex_quintiles=5 m:asthma=15.1339 m:disability=0.133608318612 m:elderly=0.00000000080378513 m:english=0.15055862845100002 m:livalone=0.48059111555 m:sealevelrise=0.182261

series e:cne3-h93g d:2016-03-10T13:51:28.000Z t:census_blockgroup=060750201001 m:education_wnullvalues=0.724000035838 m:floodhealthindex=83.48599999999999 m:elevation=7.83292 m:diabetes=16.0115 m:children=0.0798930015311 m:nonwhite=0.6509999999999999 m:education=0.724000035838 m:nonwhite_wnullvalues=0.6509999999999999 m:poverty_wnullvalues=0.509706010019 m:livalone_wnullvalues=0.5220000221059999 m:elderly_wnullvalues=0.124000003135 m:housingquality=10.2406 m:poverty=0.509706010019 m:homeless=15.8921 m:mentalhealth=62.0535 m:precipitation=0.0205164 m:floodhealthindex_quintiles=5 m:asthma=10.5741 m:disability=0.23800000496100002 m:elderly=0.124000003135 m:english=0.23200000158800002 m:livalone=0.5220000221059999 m:disability_wnullvalues=0.23800000496100002 m:sealevelrise=0

series e:cne3-h93g d:2016-03-10T13:51:28.000Z t:census_blockgroup=060750117001 m:education_wnullvalues=0.862000015261 m:floodhealthindex=83.4791 m:elevation=-1.99906 m:diabetes=1.4068 m:children=0.0271490014679 m:nonwhite=0.6970000000000001 m:education=0.862000015261 m:nonwhite_wnullvalues=0.6970000000000001 m:poverty_wnullvalues=0.378595002719 m:livalone_wnullvalues=0.6350000074959999 m:housingquality=39.5622 m:poverty=0.378595002719 m:homeless=4.9374 m:mentalhealth=98.5924 m:precipitation=0.00532113 m:floodhealthindex_quintiles=5 m:asthma=0.8008 m:disability=0.18700000128100003 m:elderly=0.10300000090099999 m:english=0.17100000128099999 m:livalone=0.6350000074959999 m:sealevelrise=0.106609
```

## Meta Commands

```ls
metric m:children p:double l:Children t:dataTypeName=number

metric m:children_wnullvalues p:double l:Children_wNULLvalues t:dataTypeName=number

metric m:elderly p:float l:Elderly t:dataTypeName=number

metric m:elderly_wnullvalues p:float l:Elderly_wNULLvalues t:dataTypeName=number

metric m:nonwhite p:float l:NonWhite t:dataTypeName=number

metric m:nonwhite_wnullvalues p:float l:NonWhite_wNullvalues t:dataTypeName=number

metric m:poverty p:double l:Poverty t:dataTypeName=number

metric m:poverty_wnullvalues p:double l:Poverty_wNULLvalues t:dataTypeName=number

metric m:education p:decimal l:Education t:dataTypeName=number

metric m:education_wnullvalues p:decimal l:Education_wNULLvalues t:dataTypeName=number

metric m:english p:decimal l:English t:dataTypeName=number

metric m:english_wnullvalues p:decimal l:English_wNULLvalues t:dataTypeName=number

metric m:elevation p:float l:Elevation t:dataTypeName=number

metric m:sealevelrise p:float l:SeaLevelRise t:dataTypeName=number

metric m:precipitation p:float l:Precipitation t:dataTypeName=number

metric m:diabetes p:float l:Diabetes t:dataTypeName=number

metric m:mentalhealth p:float l:MentalHealth t:dataTypeName=number

metric m:asthma p:float l:Asthma t:dataTypeName=number

metric m:disability p:float l:Disability t:dataTypeName=number

metric m:disability_wnullvalues p:float l:Disability_wNULLvalues t:dataTypeName=number

metric m:housingquality p:float l:HousingQuality t:dataTypeName=number

metric m:homeless p:float l:Homeless t:dataTypeName=number

metric m:livalone p:double l:LivAlone t:dataTypeName=number

metric m:livalone_wnullvalues p:double l:LivAlone_wNULLvalues t:dataTypeName=number

metric m:floodhealthindex p:decimal l:FloodHealthIndex t:dataTypeName=number

metric m:floodhealthindex_quintiles p:integer l:FloodHealthIndex_Quintiles t:dataTypeName=number

entity e:cne3-h93g l:"San Francisco Flood Health Vulnerability" t:attribution=SFDPH t:url=https://data.sfgov.org/api/views/cne3-h93g

property e:cne3-h93g t:meta.view v:id=cne3-h93g v:category="Health and Social Services" v:averageRating=0 v:name="San Francisco Flood Health Vulnerability" v:attribution=SFDPH

property e:cne3-h93g t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:cne3-h93g t:meta.view.owner v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:displayName="SFDPH Open Data"

property e:cne3-h93g t:meta.view.tableauthor v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:roleName=editor v:displayName="SFDPH Open Data"
```

## Top Records

```ls
| :updated_at | census_blockgroup | children             | children_wnullvalues | elderly                      | elderly_wnullvalues  | nonwhite            | nonwhite_wnullvalues | poverty             | poverty_wnullvalues | education           | education_wnullvalues | english              | english_wnullvalues | elevation           | sealevelrise         | precipitation         | diabetes           | mentalhealth       | asthma              | disability          | disability_wnullvalues | housingquality     | homeless           | livalone            | livalone_wnullvalues | floodhealthindex   | floodhealthindex_quintiles | 
| =========== | ================= | ==================== | ==================== | ============================ | ==================== | =================== | ==================== | =================== | =================== | =================== | ===================== | ==================== | =================== | =================== | ==================== | ===================== | ================== | ================== | =================== | =================== | ====================== | ================== | ================== | =================== | ==================== | ================== | ========================== | 
| 1457617888  | 060759809001      | 0.072957122428899998 |                      | 0.00000000080378512999999999 |                      | 0.59917500000000001 | 0.59917500000000001  | 0.356678376001      |                     | 0.99607992709399995 | 0.99607992709399995   | 0.15055862845100002  |                     | -6                  | 0.18226100000000001  | 0.035770999999999997  | 22.058399999999999 | 36.520000000000003 | 15.133900000000001  | 0.13360831861200001 |                        | 14.109299999999999 | 17.502500000000001 | 0.48059111555       | 0.48059111555        | 84.818999999999988 | 5                          | 
| 1457617888  | 060750201001      | 0.079893001531100002 |                      | 0.12400000313499999          | 0.12400000313499999  | 0.65099999999999991 | 0.65099999999999991  | 0.50970601001899996 | 0.50970601001899996 | 0.72400003583799999 | 0.72400003583799999   | 0.23200000158800002  |                     | 7.8329199999999997  | 0                    | 0.020516400000000001  | 16.011500000000002 | 62.0535            | 10.5741             | 0.23800000496100002 | 0.23800000496100002    | 10.240600000000001 | 15.892099999999999 | 0.52200002210599994 | 0.52200002210599994  | 83.48599999999999  | 5                          | 
| 1457617888  | 060750117001      | 0.027149001467899999 |                      | 0.10300000090099999          |                      | 0.69700000000000006 | 0.69700000000000006  | 0.37859500271899998 | 0.37859500271899998 | 0.86200001526100001 | 0.86200001526100001   | 0.17100000128099999  |                     | -1.9990600000000001 | 0.106609             | 0.0053211300000000003 | 1.4068000000000001 | 98.592399999999998 | 0.80079999999999996 | 0.18700000128100003 |                        | 39.562199999999997 | 4.9374000000000002 | 0.63500000749599994 | 0.63500000749599994  | 83.479100000000003 | 5                          | 
| 1457617888  | 060750178021      | 0.084214999999999998 | 0.084214999999999998 | 0.088000000000000009         | 0.088000000000000009 | 0.58399999999999996 | 0.58399999999999996  | 0.32736199999999999 | 0.32736199999999999 | 0.84299999999999997 | 0.84299999999999997   | 0.11900000000000001  | 0.11900000000000001 | -5.9662899999999999 | 0.064579399999999995 | 0.024166400000000001  | 14.9856            | 54.069899999999997 | 9.5801999999999996  | 0.22899999999999998 | 0.22899999999999998    | 7.04366            | 19.2683            | 0.42700000000000005 | 0.42700000000000005  | 82.492500000000007 | 5                          | 
| 1457617888  | 060750125012      | 0.095331509775999995 |                      | 0.22199906769300001          | 0.22199906769300001  | 0.72600100000000001 | 0.72600100000000001  | 0.79475029013200005 | 0.79475029013200005 | 0.69499738992900006 | 0.69499738992900006   | 0.202999257948       | 0.202999257948      | 7.1327800000000003  | 0                    | 0.0041050100000000001 | 15.5               | 63.749899999999997 | 12.9672             | 0.424997971365      | 0.424997971365         | 13.7255            | 14.618399999999999 | 0.73199689018699998 | 0.73199689018699998  | 81.806100000000001 | 5                          | 
| 1457617888  | 060750176011      | 0.109834             | 0.109834             | 0.14099999999999999          | 0.14099999999999999  | 0.73299999999999998 | 0.73299999999999998  | 0.55086199999999996 | 0.55086199999999996 | 0.80599999999999994 | 0.80599999999999994   | 0.11699999999999999  | 0.11699999999999999 | 10.696899999999999  | 0                    | 0.0086246099999999996 | 16.009399999999999 | 62.059399999999997 | 10.5831             | 0.22700000000000001 | 0.22700000000000001    | 170.94             | 19.2683            | 0.60899999999999999 | 0.60899999999999999  | 81.799400000000006 | 5                          | 
| 1457617888  | 060750201003      | 0.079893000000000006 | 0.079893000000000006 | 0.12400000000000001          | 0.12400000000000001  | 0.65099999999999991 | 0.65099999999999991  | 0.50970599999999999 | 0.50970599999999999 | 0.72400000000000009 | 0.72400000000000009   | 0.23199999999999998  | 0.23199999999999998 | 5.81684             | 0                    | 0.028468              | 15.9985            | 61.883600000000001 | 10.543799999999999  | 0.23800000000000002 | 0.23800000000000002    | 9.6873799999999992 | 3.2195             | 0.52200000000000002 | 0.52200000000000002  | 81.506             | 5                          | 
| 1457617888  | 060750101001      | 0.05751665777        | 0.05751665777        | 0.19751667000000001          | 0.19751667000000001  | 0.55779900000000004 | 0.55779900000000004  | 0.32755633910999998 | 0.32755633910999998 | 0.87850697999999994 | 0.87850697999999994   | 0.18474195999999998  | 0.18474195999999998 | -7.5257699999999996 | 0.22820299999999999  | 0.00314665            | 5.1173000000000002 | 22.3352            | 4.0437000000000003  | 0.12971244000000001 | 0.12971244000000001    | 4.5454499999999998 | 4.8487999999999998 | 0.51688442000000001 | 0.51688442000000001  | 81.1858            | 5                          | 
| 1457617888  | 060750232002      | 0.25512766087099997  |                      | 0.100990574381               | 0.100990574381       | 0.94300499999999998 |                      | 0.42760483777899999 | 0.42760483777899999 | 0.70993307123299998 | 0.70993307123299998   | 0.091991232884100008 |                     | -6                  | 0.102409             | 0.0151036             | 23.190300000000001 | 38.563800000000001 | 16.108799999999999  | 0.10798980443799999 |                        | 6.2182000000000004 | 17.613             | 0.26597487641000001 |                      | 80.865700000000004 | 5                          | 
| 1457617888  | 060750201002      | 0.079893084955900001 | 0.079893084955900001 | 0.124000120942               | 0.124000120942       | 0.65099899999999988 | 0.65099899999999988  | 0.50970633930499998 | 0.50970633930499998 | 0.72400092825399998 | 0.72400092825399998   | 0.23200008166200001  | 0.23200008166200001 | 13.917899999999999  | 0                    | 0.0137591             | 16.012499999999999 | 62.05              | 10.5693             | 0.23800018399700001 | 0.23800018399700001    | 11.5778            | 3.2195             | 0.52200053131700008 | 0.52200053131700008  | 80.832699999999988 | 5                          | 
```