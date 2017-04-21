# Community Resiliency Indicator System

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/community-resiliency-indicator-system-72819) |
| Metadata | [Link](https://data.sfgov.org/api/views/banc-xdvr) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/banc-xdvr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/banc-xdvr/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | banc-xdvr |
| Name | Community Resiliency Indicator System |
| Attribution | SFDPH |
| Category | Health and Social Services |
| Tags | san francisco's climate & health program, sfclimatehealth.org, community resiliency, san francisco indicator project, community resiliency system, san francisco, environmental health, department o... |
| Created | 2015-01-23T01:28:34Z |
| Publication Date | 2015-01-23T01:47:32Z |

## Description

The Community Resiliency Indicator System was developed by  San Francisco's Climate and Health Program and is part of San Francisco's Climate and Health Profile. The system includes 40 indicators and an additive index which is a compilation of all of the indicators. See attached methods and project description documents for more details, you can also visit San Francisco's Climate and Health Profile website - www.sfclimatehealth.org (available Feb-2015)

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | neighborhood  | Neighborhood  | text      | text        |
| Yes      | numeric metric | flood_per     | Flood_Per     | number    | number      |
| Yes      | numeric metric | heat_per      | Heat_Per      | number    | number      |
| Yes      | numeric metric | liq_per       | Liq_Per       | number    | number      |
| Yes      | numeric metric | haz_score     | Haz_Score     | number    | number      |
| Yes      | numeric metric | imp_per       | Imp_Per       | number    | number      |
| Yes      | numeric metric | tree_per      | Tree_Per      | number    | number      |
| Yes      | numeric metric | pm_conc       | PM_Conc       | number    | number      |
| Yes      | numeric metric | tox_per       | Tox_Per       | number    | number      |
| Yes      | numeric metric | env_score     | Env_Score     | number    | number      |
| Yes      | numeric metric | at_min        | AT_Min        | number    | number      |
| Yes      | numeric metric | ptrans_sco    | PTrans_Sco    | number    | number      |
| Yes      | numeric metric | trans_sco     | Trans_Sco     | number    | number      |
| Yes      | numeric metric | vcrim_rate    | VCrim_Rate    | number    | number      |
| Yes      | numeric metric | vot_rate      | Vot_Rate      | number    | number      |
| Yes      | numeric metric | newsf_per     | NewSF_Per     | number    | number      |
| Yes      | numeric metric | citz_per      | Citz_Per      | number    | number      |
| Yes      | numeric metric | eng_per       | Eng_Per       | number    | number      |
| Yes      | numeric metric | com_score     | Com_Score     | number    | number      |
| Yes      | numeric metric | food_score    | Food_Score    | number    | number      |
| Yes      | numeric metric | hs_per        | HS_Per        | number    | number      |
| Yes      | numeric metric | pharm_per     | Pharm_Per     | number    | number      |
| Yes      | numeric metric | pr_score      | PR_Score      | number    | number      |
| Yes      | numeric metric | lival_per     | LivAl_Per     | number    | number      |
| Yes      | numeric metric | eldlival_per  | EldLivAl_Per  | number    | number      |
| Yes      | numeric metric | oc_per        | OC_Per        | number    | number      |
| Yes      | numeric metric | viol_rate     | Viol_Rate     | number    | number      |
| Yes      | numeric metric | ac_per        | AC_Per        | number    | number      |
| Yes      | numeric metric | rent_per      | Rent_Per      | number    | number      |
| Yes      | numeric metric | house_score   | House_Score   | number    | number      |
| Yes      | numeric metric | emp_per       | Emp_per       | number    | number      |
| Yes      | numeric metric | ec_score      | Ec_Score      | number    | number      |
| Yes      | numeric metric | shelt_rate    | Shelt_Rate    | number    | number      |
| Yes      | numeric metric | sheltday_rate | SheltDay_Rate | number    | number      |
| Yes      | numeric metric | dis_per       | Dis_Per       | number    | number      |
| Yes      | numeric metric | prevhos       | PrevHos       | number    | number      |
| Yes      | numeric metric | health_score  | Health_Score  | number    | number      |
| Yes      | numeric metric | over85_per    | Over85_Per    | number    | number      |
| Yes      | numeric metric | over65_per    | Over65_Per    | number    | number      |
| Yes      | numeric metric | under18_per   | Under18_Per   | number    | number      |
| Yes      | numeric metric | under5_per    | Under5_Per    | number    | number      |
| Yes      | numeric metric | nonwhi_per    | NonWhi_Per    | number    | number      |
| No       |                | lat_per       | Lat_Per       | number    | number      |
| Yes      | series tag     | black_per     | Black_Per     | text      | text        |
| Yes      | numeric metric | asian_per     | Asian_Per     | number    | number      |
| Yes      | numeric metric | pov_per       | Pov_Per       | number    | number      |
| Yes      | numeric metric | popdens       | PopDens       | number    | number      |
| Yes      | numeric metric | daypopdens    | DayPopDens    | number    | number      |
| Yes      | numeric metric | dem_score     | Dem_Score     | number    | number      |
| Yes      | numeric metric | res_score     | Res_Score     | number    | number      |
| Yes      | numeric metric | res_rank      | Res_Rank      | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = lat_per
```

## Data Commands

```ls
series e:banc-xdvr d:2015-01-22T17:28:43.000Z t:black_per=0.341864261 t:neighborhood=Bayview m:newsf_per=0.04721006 m:ac_per=0.0096 m:asian_per=0.293998838 m:over65_per=0.098967988 m:pharm_per=0.0954962 m:res_score=1 m:popdens=6944.77 m:emp_per=0.838264518 m:hs_per=0.725054753 m:dis_per=0.112580583 m:citz_per=0.236618484 m:rent_per=0.150953984 m:res_rank=35 m:pov_per=0.413468721 m:lival_per=0.224653947 m:under18_per=0.260022688 m:at_min=15.342 m:viol_rate=7.78 m:com_score=2 m:ptrans_sco=13.758 m:pr_score=1 m:dem_score=1 m:nonwhi_per=0.797305149 m:ec_score=1 m:food_score=33.0789 m:under5_per=0.08839886 m:tree_per=0.0674749 m:flood_per=0.0683688 m:daypopdens=9850.25 m:tox_per=0.269811 m:oc_per=0.115881033 m:haz_score=1 m:pm_conc=8.71243 m:sheltday_rate=0.186687 m:prevhos=1893.17 m:heat_per=0.586532 m:env_score=1 m:eldlival_per=0.073887018 m:over85_per=0.011177821 m:vot_rate=0.631774 m:trans_sco=1 m:shelt_rate=0.264792 m:liq_per=0.557273 m:vcrim_rate=105.799 m:health_score=1 m:imp_per=0.693209 m:house_score=2 m:eng_per=0.281838048

series e:banc-xdvr d:2015-01-22T17:28:43.000Z t:black_per=0.051902712 t:neighborhood="Bernal Heights" m:newsf_per=0.040006325 m:ac_per=0.0511 m:asian_per=0.179913883 m:over65_per=0.086000233 m:pharm_per=0.212705 m:res_score=3 m:popdens=22066.8 m:emp_per=0.927948127 m:hs_per=0.878191214 m:dis_per=0.074091315 m:citz_per=0.204186047 m:rent_per=0.077073595 m:res_rank=16 m:pov_per=0.242755731 m:lival_per=0.243069899 m:under18_per=0.172970247 m:at_min=22.505 m:viol_rate=6.9 m:com_score=4 m:ptrans_sco=28.6832 m:pr_score=3 m:dem_score=3 m:nonwhi_per=0.374684821 m:ec_score=3 m:food_score=82.4083 m:under5_per=0.05399744 m:tree_per=0.121011 m:flood_per=0 m:daypopdens=16503.8 m:tox_per=0.115277 m:oc_per=0.055658224 m:haz_score=3 m:pm_conc=8.75023 m:sheltday_rate=0.466926 m:prevhos=1081.97 m:heat_per=0.104888 m:env_score=2 m:eldlival_per=0.050114143 m:over85_per=0.006633306 m:vot_rate=0.774304 m:trans_sco=3 m:shelt_rate=0.349216 m:liq_per=0.12912 m:vcrim_rate=43.7684 m:health_score=3 m:imp_per=0.656492 m:house_score=5 m:eng_per=0.198548407

series e:banc-xdvr d:2015-01-22T17:28:43.000Z t:black_per=0.029873443 t:neighborhood="Castro/Upper Market" m:newsf_per=0.05932371 m:ac_per=0.03 m:asian_per=0.093054057 m:over65_per=0.094476602 m:pharm_per=0.565764 m:res_score=5 m:popdens=23023 m:emp_per=0.930182529 m:hs_per=0.972638866 m:dis_per=0.077749436 m:citz_per=0.084665678 m:rent_per=0.087670727 m:res_rank=2 m:pov_per=0.161875797 m:lival_per=0.428755999 m:under18_per=0.07196115 m:at_min=39.1284 m:viol_rate=9.34 m:com_score=5 m:ptrans_sco=36.8504 m:pr_score=5 m:dem_score=5 m:nonwhi_per=0.189934269 m:ec_score=4 m:food_score=87.8162 m:under5_per=0.027764152 m:tree_per=0.145122 m:flood_per=0 m:daypopdens=18531 m:tox_per=0.000597061 m:oc_per=0.007105943 m:haz_score=5 m:pm_conc=8.446 m:sheltday_rate=0.378167 m:prevhos=625.231 m:heat_per=0.00268633 m:env_score=4 m:eldlival_per=0.077242525 m:over85_per=0.013980182 m:vot_rate=0.822557 m:trans_sco=4 m:shelt_rate=0.304383 m:liq_per=0.119483 m:vcrim_rate=64.1234 m:health_score=4 m:imp_per=0.655799 m:house_score=3 m:eng_per=0.032946519
```

## Meta Commands

```ls
metric m:flood_per p:float l:Flood_Per t:dataTypeName=number

metric m:heat_per p:float l:Heat_Per t:dataTypeName=number

metric m:liq_per p:float l:Liq_Per t:dataTypeName=number

metric m:haz_score p:integer l:Haz_Score t:dataTypeName=number

metric m:imp_per p:float l:Imp_Per t:dataTypeName=number

metric m:tree_per p:float l:Tree_Per t:dataTypeName=number

metric m:pm_conc p:float l:PM_Conc t:dataTypeName=number

metric m:tox_per p:float l:Tox_Per t:dataTypeName=number

metric m:env_score p:integer l:Env_Score t:dataTypeName=number

metric m:at_min p:float l:AT_Min t:dataTypeName=number

metric m:ptrans_sco p:float l:PTrans_Sco t:dataTypeName=number

metric m:trans_sco p:integer l:Trans_Sco t:dataTypeName=number

metric m:vcrim_rate p:float l:VCrim_Rate t:dataTypeName=number

metric m:vot_rate p:float l:Vot_Rate t:dataTypeName=number

metric m:newsf_per p:double l:NewSF_Per t:dataTypeName=number

metric m:citz_per p:double l:Citz_Per t:dataTypeName=number

metric m:eng_per p:float l:Eng_Per t:dataTypeName=number

metric m:com_score p:integer l:Com_Score t:dataTypeName=number

metric m:food_score p:float l:Food_Score t:dataTypeName=number

metric m:hs_per p:double l:HS_Per t:dataTypeName=number

metric m:pharm_per p:float l:Pharm_Per t:dataTypeName=number

metric m:pr_score p:integer l:PR_Score t:dataTypeName=number

metric m:lival_per p:double l:LivAl_Per t:dataTypeName=number

metric m:eldlival_per p:double l:EldLivAl_Per t:dataTypeName=number

metric m:oc_per p:double l:OC_Per t:dataTypeName=number

metric m:viol_rate p:float l:Viol_Rate t:dataTypeName=number

metric m:ac_per p:float l:AC_Per t:dataTypeName=number

metric m:rent_per p:double l:Rent_Per t:dataTypeName=number

metric m:house_score p:integer l:House_Score t:dataTypeName=number

metric m:emp_per p:double l:Emp_per t:dataTypeName=number

metric m:ec_score p:integer l:Ec_Score t:dataTypeName=number

metric m:shelt_rate p:float l:Shelt_Rate t:dataTypeName=number

metric m:sheltday_rate p:float l:SheltDay_Rate t:dataTypeName=number

metric m:dis_per p:double l:Dis_Per t:dataTypeName=number

metric m:prevhos p:float l:PrevHos t:dataTypeName=number

metric m:health_score p:integer l:Health_Score t:dataTypeName=number

metric m:over85_per p:double l:Over85_Per t:dataTypeName=number

metric m:over65_per p:double l:Over65_Per t:dataTypeName=number

metric m:under18_per p:double l:Under18_Per t:dataTypeName=number

metric m:under5_per p:double l:Under5_Per t:dataTypeName=number

metric m:nonwhi_per p:float l:NonWhi_Per t:dataTypeName=number

metric m:asian_per p:double l:Asian_Per t:dataTypeName=number

metric m:pov_per p:double l:Pov_Per t:dataTypeName=number

metric m:popdens p:float l:PopDens t:dataTypeName=number

metric m:daypopdens p:double l:DayPopDens t:dataTypeName=number

metric m:dem_score p:integer l:Dem_Score t:dataTypeName=number

metric m:res_score p:integer l:Res_Score t:dataTypeName=number

metric m:res_rank p:integer l:Res_Rank t:dataTypeName=number

entity e:banc-xdvr l:"Community Resiliency Indicator System" t:attribution=SFDPH t:url=https://data.sfgov.org/api/views/banc-xdvr

property e:banc-xdvr t:meta.view v:id=banc-xdvr v:category="Health and Social Services" v:attributionLink=http://www.sfclimatehealth.org v:averageRating=0 v:name="Community Resiliency Indicator System" v:attribution=SFDPH

property e:banc-xdvr t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:banc-xdvr t:meta.view.owner v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:displayName="SFDPH Open Data"

property e:banc-xdvr t:meta.view.tableauthor v:id=5w65-feqy v:profileImageUrlMedium=/api/users/5w65-feqy/profile_images/THUMB v:profileImageUrlLarge=/api/users/5w65-feqy/profile_images/LARGE v:screenName="SFDPH Open Data" v:profileImageUrlSmall=/api/users/5w65-feqy/profile_images/TINY v:roleName=editor v:displayName="SFDPH Open Data"
```

## Top Records

```ls
| :updated_at | neighborhood              | flood_per | heat_per    | liq_per   | haz_score | imp_per  | tree_per  | pm_conc | tox_per     | env_score | at_min  | ptrans_sco | trans_sco | vcrim_rate | vot_rate | newsf_per   | citz_per    | eng_per     | com_score | food_score | hs_per      | pharm_per | pr_score | lival_per   | eldlival_per | oc_per      | viol_rate | ac_per | rent_per    | house_score | emp_per     | ec_score | shelt_rate | sheltday_rate | dis_per     | prevhos | health_score | over85_per  | over65_per  | under18_per | under5_per  | nonwhi_per  | lat_per     | black_per   | asian_per   | pov_per     | popdens | daypopdens | dem_score | res_score | res_rank | 
| =========== | ========================= | ========= | =========== | ========= | ========= | ======== | ========= | ======= | =========== | ========= | ======= | ========== | ========= | ========== | ======== | =========== | =========== | =========== | ========= | ========== | =========== | ========= | ======== | =========== | ============ | =========== | ========= | ====== | =========== | =========== | =========== | ======== | ========== | ============= | =========== | ======= | ============ | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | =========== | ======= | ========== | ========= | ========= | ======== | 
| 1421947723  | Bayview                   | 0.0683688 | 0.586532    | 0.557273  | 1         | 0.693209 | 0.0674749 | 8.71243 | 0.269811    | 1         | 15.342  | 13.758     | 1         | 105.799    | 0.631774 | 0.04721006  | 0.236618484 | 0.281838048 | 2         | 33.0789    | 0.725054753 | 0.0954962 | 1        | 0.224653947 | 0.073887018  | 0.115881033 | 7.78      | 0.0096 | 0.150953984 | 2           | 0.838264518 | 1        | 0.264792   | 0.186687      | 0.112580583 | 1893.17 | 1            | 0.011177821 | 0.098967988 | 0.260022688 | 0.08839886  | 0.797305149 | 0.237667045 | 0.341864261 | 0.293998838 | 0.413468721 | 6944.77 | 9850.25    | 1         | 1         | 35       | 
| 1421947723  | Bernal Heights            | 0         | 0.104888    | 0.12912   | 3         | 0.656492 | 0.121011  | 8.75023 | 0.115277    | 2         | 22.505  | 28.6832    | 3         | 43.7684    | 0.774304 | 0.040006325 | 0.204186047 | 0.198548407 | 4         | 82.4083    | 0.878191214 | 0.212705  | 3        | 0.243069899 | 0.050114143  | 0.055658224 | 6.9       | 0.0511 | 0.077073595 | 5           | 0.927948127 | 3        | 0.349216   | 0.466926      | 0.074091315 | 1081.97 | 3            | 0.006633306 | 0.086000233 | 0.172970247 | 0.05399744  | 0.374684821 | 0.3068389   | 0.051902712 | 0.179913883 | 0.242755731 | 22066.8 | 16503.8    | 3         | 3         | 16       | 
| 1421947723  | Castro/Upper Market       | 0         | 0.00268633  | 0.119483  | 5         | 0.655799 | 0.145122  | 8.446   | 0.000597061 | 4         | 39.1284 | 36.8504    | 4         | 64.1234    | 0.822557 | 0.05932371  | 0.084665678 | 0.032946519 | 5         | 87.8162    | 0.972638866 | 0.565764  | 5        | 0.428755999 | 0.077242525  | 0.007105943 | 9.34      | 0.03   | 0.087670727 | 3           | 0.930182529 | 4        | 0.304383   | 0.378167      | 0.077749436 | 625.231 | 4            | 0.013980182 | 0.094476602 | 0.07196115  | 0.027764152 | 0.189934269 | 0.091582459 | 0.029873443 | 0.093054057 | 0.161875797 | 23023   | 18531      | 5         | 5         | 2        | 
| 1421947723  | Chinatown                 | 0         | 0.999761    | 0.312332  | 1         | 0.875325 | 0.0500452 | 8.81237 | 0.00116048  | 1         | 41.4272 | 89.9066    | 5         | 50.8277    | 0.579499 | 0.075387286 | 0.379653428 | 0.67985904  | 1         | 90.8436    | 0.447475334 | 1.00001   | 3        | 0.473995772 | 0.247639183  | 0.250458069 | 10.59     | 0.0016 | 0.226497533 | 1           | 0.842658261 | 1        | 0.424448   | 0.107328      | 0.195933333 | 739.095 | 1            | 0.048866667 | 0.281066667 | 0.0996      | 0.016266667 | 0.8786      |             | NULL        | 0.830266667 | 0.657466667 | 70416.6 | 278476     | 1         | 1         | 36       | 
| 1421947723  | Crocker Amazon            | 0         | 0.218043    | 0.0192769 | 3         | 0.705708 | 0.0521826 | 8.25316 | 0.00133914  | 3         | 14.1353 | 18.5395    | 1         | 20.6687    | 0.652737 | 0.030931316 | 0.213926095 | 0.431434599 | 2         | 50.2971    | 0.734397264 | 0.137773  | 1        | 0.174093264 | 0.064248705  | 0.15        | 3.83      | 0.0106 | 0.088341969 | 4           | 0.884297521 | 1        | 0.227964   | 0.239158      | 0.10588631  | 920.674 | 1            | 0.019038009 | 0.15452405  | 0.195694585 | 0.043390515 | 0.779414733 | 0.229330642 | 0.038748739 | 0.582374706 | 0.287790111 | 28187.1 | 26867.7    | 1         | 1         | 30       | 
| 1421947723  | Diamond Heights/Glen Park | 0         | 0.000279492 | 0.19802   | 4         | 0.433316 | 0.240678  | 8.31805 | 0.00608127  | 5         | 19.0645 | 24.6857    | 2         | 20.3355    | 0.840038 | 0.072178142 | 0.114825808 | 0.053663852 | 5         | 64.5804    | 0.958131542 | 0.241605  | 3        | 0.376536611 | 0.10181721   | 0.006948156 | 5.47      | 0.0002 | 0.076696954 | 4           | 0.937884379 | 4        | 0.344669   | 0.430663      | 0.074031891 | 483.676 | 4            | 0.014679828 | 0.132118451 | 0.146545178 | 0.070868135 | 0.321564161 | 0.120096178 | 0.033156163 | 0.16312326  | 0.184510251 | 12163.5 | 9734.72    | 4         | 5         | 5        | 
| 1421947723  | Downtown/Civic Center     | 0         | 0.999767    | 0.153798  | 1         | 0.867658 | 0.0407454 | 9.18731 | 0.00221848  | 1         | 41.887  | 83.2956    | 5         | 177.47     | 0.634302 | 0.109729412 | 0.280030604 | 0.278696127 | 1         | 93.2561    | 0.790392868 | 0.997356  | 5        | 0.676120176 | 0.144176811  | 0.137788138 | 9.06      | 0.008  | 0.295778296 | 1           | 0.893339055 | 1        | 0.284711   | 0.184318      | 0.210701274 | 1549.06 | 1            | 0.019918624 | 0.14724889  | 0.073504774 | 0.025077786 | 0.543600245 | 0.155040821 | 0.079328777 | 0.313485626 | 0.561497753 | 65411.7 | 101040     | 2         | 1         | 34       | 
| 1421947723  | Excelsior                 | 0         | 0.345133    | 0.022647  | 3         | 0.681602 | 0.103498  | 8.66289 | 0.0593634   | 3         | 14.37   | 23.0295    | 2         | 34.5181    | 0.600075 | 0.039378295 | 0.285262444 | 0.408337879 | 2         | 61.8042    | 0.708713005 | 0.298006  | 1        | 0.177211394 | 0.082658671  | 0.098150925 | 4.33      | 0.0668 | 0.099550225 | 5           | 0.913832981 | 2        | 0.341243   | 0.373188      | 0.10792346  | 1037.63 | 2            | 0.024252157 | 0.158197011 | 0.182721359 | 0.05198835  | 0.666920711 | 0.300062604 | 0.030811944 | 0.463785079 | 0.294074417 | 23767.5 | 21733      | 1         | 2         | 29       | 
| 1421947723  | Financial District        | 0.0264466 | 0.674863    | 0.802687  | 1         | 0.746288 | 0.0927255 | 9.16533 | 0.0260546   | 1         | 42.1367 | 71.6257    | 5         | 282.401    | 0.718026 |             |             | 0.234240688 | 1         | 89.9397    | 0.867811159 | 0.931057  | 5        | 0.704989154 |              | 0.123644252 | 12.67     | 0.5104 | 0.293926247 | 1           | 0.918767507 | 2        | 0.289939   | 0.0252924     | 0.302292264 | 469.222 | 2            |             |             |             |             | 0.510744986 |             | NULL        | 0.342406877 | 0.553724928 | 9940.64 | 113954     | 1         | 1         | 31       | 
| 1421947723  | Golden Gate Park          | 0.0225869 | 0           | 0.0580895 |           | 0.146719 | 0.476875  | 8.36935 | 0           |           | 23.0307 | 21.6098    |           | 1134.5     | 0        |             |             |             |           | 59.5537    |             | 0.179979  |          |             |              |             | 66.67     | 0.0023 |             |             |             |          | 23.3918    | 3.36984       |             | 689.443 |              |             |             |             |             |             |             | NULL        |             |             | 101.464 | 704.313    |           |           |          | 
```