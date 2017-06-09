# Somerville High School YRBS Raw Data 2002-2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/somerville-high-school-yrbs-raw-data-2006-2014) |
| Metadata | [Link](https://data.somervillema.gov/api/views/qvup-qejq) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/qvup-qejq/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/qvup-qejq/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | qvup-qejq |
| Name | Somerville High School YRBS Raw Data 2002-2014 |
| Attribution | City of Somerville Health & Human Services Department |
| Category | Public Health |
| Tags | hhs, yrbs, schools |
| Created | 2016-02-03T19:11:48Z |
| Publication Date | 2016-02-04T14:07:38Z |

## Description

The City of Somerville conducts the Youth Risk Behavior Survey each year to gather data about students' risk behaviors. On an annual basis, Health & Human Services staff coordinate a survey with either High School or Middle School students in alternating years.

The data presented in this table is from high school students from 2002 through 2014 and includes questions about tobacco use, alcohol and other drug use, sexual behaviors that might lead to unintended pregnancy or sexually transmitted disease, dietary behaviors, physical activity, and behaviors associated with intentional or unintentional injuries. Data from the YRBS provide accurate estimates of the prevalence of risk behaviors among public school students in the City, and are important for planning health education and risk prevention programs.

Attached is the questionnaire used in the survey which includes information regarding the variables used in the dataset.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type | Render Type |
| ======== | ============== | ========== | ========== | ========= | =========== |
| Yes      | series tag     | survey     | survey     | text      | text        |
| Yes      | time           | year       | year       | number    | number      |
| No       |                | id         | id         | text      | number      |
| Yes      | series tag     | age        | age        | text      | text        |
| Yes      | series tag     | gender     | GENDER     | text      | text        |
| Yes      | series tag     | grade      | grade      | text      | text        |
| Yes      | series tag     | race       | race       | text      | text        |
| Yes      | series tag     | language   | language   | text      | text        |
| Yes      | series tag     | live_us    | live_us    | text      | text        |
| Yes      | series tag     | parents    | parents    | text      | text        |
| Yes      | series tag     | home       | home       | text      | text        |
| Yes      | series tag     | skl_gra    | skl_gra    | text      | text        |
| Yes      | series tag     | fut_ed     | fut_ed     | text      | text        |
| Yes      | series tag     | witness    | witness    | text      | text        |
| Yes      | series tag     | emo_abus   | emo_abus   | text      | text        |
| Yes      | series tag     | mistreat   | mistreat   | text      | text        |
| Yes      | series tag     | harassed   | harassed   | text      | text        |
| Yes      | series tag     | hurtdate   | hurtdate   | text      | text        |
| Yes      | series tag     | gang       | gang       | text      | text        |
| Yes      | series tag     | bull_skl   | bull_skl   | text      | text        |
| Yes      | numeric metric | nothing    | nothing    | number    | number      |
| Yes      | numeric metric | trystop    | trystop    | number    | number      |
| Yes      | numeric metric | teltea     | teltea     | number    | number      |
| Yes      | numeric metric | telpar     | telpar     | number    | number      |
| Yes      | numeric metric | telfri     | telfri     | number    | number      |
| Yes      | series tag     | saw_bul    | saw_bul    | text      | text        |
| Yes      | numeric metric | tookpart   | tookpart   | number    | number      |
| Yes      | numeric metric | justsaw    | justsaw    | number    | number      |
| Yes      | numeric metric | intervene  | intervene  | number    | number      |
| Yes      | numeric metric | toldtea    | toldtea    | number    | number      |
| Yes      | series tag     | bull_out   | bull_out   | text      | text        |
| Yes      | series tag     | bull_elec  | bull_elec  | text      | text        |
| Yes      | series tag     | fit_skl    | fit_skl    | text      | text        |
| Yes      | series tag     | fit_out    | fit_out    | text      | text        |
| Yes      | series tag     | weap_skl   | weap_skl   | text      | text        |
| Yes      | series tag     | weap_out   | weap_out   | text      | text        |
| Yes      | series tag     | stayhome   | stayhome   | text      | text        |
| Yes      | series tag     | divorce    | divorce    | text      | text        |
| Yes      | series tag     | moved      | moved      | text      | text        |
| Yes      | series tag     | death      | death      | text      | text        |
| Yes      | series tag     | ran_away   | ran_away   | text      | text        |
| Yes      | series tag     | friends    | friends    | text      | text        |
| Yes      | series tag     | adu_skl    | adu_skl    | text      | text        |
| Yes      | series tag     | adu_oth    | adu_oth    | text      | text        |
| Yes      | series tag     | skl_wor    | skl_wor    | text      | text        |
| Yes      | series tag     | soc_wor    | soc_wor    | text      | text        |
| Yes      | series tag     | appe_wor   | appe_wor   | text      | text        |
| Yes      | series tag     | fam_wor    | fam_wor    | text      | text        |
| Yes      | series tag     | gang_wor   | gang_wor   | text      | text        |
| Yes      | series tag     | bul_wor    | BUL_WOR    | text      | text        |
| Yes      | series tag     | hurtself   | hurtself   | text      | text        |
| Yes      | series tag     | depress    | depress    | text      | text        |
| Yes      | series tag     | consider   | consider   | text      | text        |
| Yes      | series tag     | plan       | plan       | text      | text        |
| Yes      | series tag     | attempt    | attempt    | text      | text        |
| Yes      | series tag     | cig_lif    | cig_lif    | text      | text        |
| Yes      | series tag     | cig_age    | cig_age    | text      | text        |
| Yes      | series tag     | cig_30     | cig_30     | text      | text        |
| Yes      | series tag     | cig_day    | cig_day    | text      | text        |
| Yes      | series tag     | cig_get    | cig_get    | text      | text        |
| Yes      | series tag     | cigar_30   | cigar_30   | text      | text        |
| Yes      | series tag     | chew_30    | chew_30    | text      | text        |
| Yes      | series tag     | alc_age    | alc_age    | text      | text        |
| Yes      | series tag     | alc_30     | alc_30     | text      | text        |
| Yes      | series tag     | alc5_30    | alc5_30    | text      | text        |
| Yes      | series tag     | alc_get    | alc_get    | text      | text        |
| Yes      | series tag     | dwi_ride   | dwi_ride   | text      | text        |
| Yes      | series tag     | dwi_driv   | dwi_driv   | text      | text        |
| Yes      | series tag     | pot_age    | pot_age    | text      | text        |
| Yes      | series tag     | pot_30     | pot_30     | text      | text        |
| Yes      | series tag     | inha_age   | inha_age   | text      | text        |
| Yes      | series tag     | inha_30    | inha_30    | text      | text        |
| Yes      | series tag     | cok_age    | cok_age    | text      | text        |
| Yes      | series tag     | cok_30     | cok_30     | text      | text        |
| Yes      | series tag     | her_age    | her_age    | text      | text        |
| Yes      | series tag     | her_30     | her_30     | text      | text        |
| Yes      | series tag     | meth_age   | meth_age   | text      | text        |
| Yes      | series tag     | meth_30    | meth_30    | text      | text        |
| Yes      | series tag     | ster_age   | ster_age   | text      | text        |
| Yes      | series tag     | ster_30    | ster_30    | text      | text        |
| Yes      | series tag     | x_age      | x_age      | text      | text        |
| Yes      | series tag     | x_30       | x_30       | text      | text        |
| Yes      | series tag     | oxy_age    | oxy_age    | text      | text        |
| Yes      | series tag     | oxy_30     | oxy_30     | text      | text        |
| Yes      | series tag     | oth_age    | oth_age    | text      | text        |
| Yes      | series tag     | oth_30     | oth_30     | text      | text        |
| Yes      | series tag     | beforskl   | beforskl   | text      | text        |
| Yes      | series tag     | rx_high    | rx_high    | text      | text        |
| Yes      | series tag     | otc_high   | otc_high   | text      | text        |
| Yes      | series tag     | per_alc    | per_alc    | text      | text        |
| Yes      | series tag     | per_pot    | per_pot    | text      | text        |
| Yes      | series tag     | off_skl    | off_skl    | text      | text        |
| Yes      | series tag     | treated    | treated    | text      | text        |
| Yes      | series tag     | rsk_smok   | rsk_smok   | text      | text        |
| Yes      | series tag     | rsk_alc    | rsk_alc    | text      | text        |
| Yes      | series tag     | rsk_pott   | rsk_pott   | text      | text        |
| Yes      | series tag     | rsk_potr   | rsk_potr   | text      | text        |
| Yes      | series tag     | rsk_oth    | rsk_oth    | text      | text        |
| Yes      | series tag     | pa_smok    | pa_smok    | text      | text        |
| Yes      | series tag     | pa_alc     | pa_alc     | text      | text        |
| Yes      | series tag     | pa_pot     | pa_pot     | text      | text        |
| Yes      | series tag     | pa_oth     | pa_oth     | text      | text        |
| Yes      | series tag     | exp_tob    | exp_tob    | text      | text        |
| Yes      | series tag     | exp_alc    | exp_alc    | text      | text        |
| Yes      | series tag     | exp_pot    | exp_pot    | text      | text        |
| Yes      | series tag     | exp_oth    | exp_oth    | text      | text        |
| Yes      | series tag     | exp_gamb   | exp_gamb   | text      | text        |
| Yes      | series tag     | sex_ever   | sex_ever   | text      | text        |
| Yes      | series tag     | sex_age    | sex_age    | text      | text        |
| Yes      | series tag     | sex_num    | sex_num    | text      | text        |
| Yes      | series tag     | sex_aod    | sex_aod    | text      | text        |
| Yes      | series tag     | sex_cond   | sex_cond   | text      | text        |
| Yes      | series tag     | prevpreg   | PREVPREG   | text      | text        |
| Yes      | series tag     | samesex    | samesex    | text      | text        |
| Yes      | series tag     | orient     | orient     | text      | text        |
| Yes      | series tag     | pregnant   | pregnant   | text      | text        |
| Yes      | series tag     | forced     | forced     | text      | text        |
| Yes      | series tag     | had_std    | had_std    | text      | text        |
| Yes      | series tag     | hiv_skl    | hiv_skl    | text      | text        |
| Yes      | series tag     | hiv_par    | hiv_par    | text      | text        |
| Yes      | series tag     | see_self   | see_self   | text      | text        |
| Yes      | series tag     | trying     | trying     | text      | text        |
| Yes      | series tag     | fast_30    | fast_30    | text      | text        |
| Yes      | series tag     | pills_30   | pills_30   | text      | text        |
| Yes      | series tag     | vomit_30   | vomit_30   | text      | text        |
| Yes      | series tag     | fad_30     | fad_30     | text      | text        |
| Yes      | series tag     | juice      | juice      | text      | text        |
| Yes      | series tag     | fruit      | fruit      | text      | text        |
| Yes      | series tag     | veg        | veg        | text      | text        |
| Yes      | series tag     | soda       | soda       | text      | text        |
| Yes      | series tag     | sweets     | sweets     | text      | text        |
| Yes      | series tag     | dairy      | dairy      | text      | text        |
| Yes      | series tag     | brkfst_7   | brkfst_7   | text      | text        |
| Yes      | series tag     | exer_60    | exer_60    | text      | text        |
| Yes      | series tag     | tv_room    | tv_room    | text      | text        |
| Yes      | series tag     | tv_hours   | tv_hours   | text      | text        |
| Yes      | series tag     | comp_hrs   | comp_hrs   | text      | text        |
| Yes      | series tag     | sleep_hrs  | sleep_hrs  | text      | text        |
| Yes      | series tag     | exer_7     | exer_7     | text      | text        |
| Yes      | series tag     | gamble     | gamble     | text      | text        |
| Yes      | series tag     | clubs      | clubs      | text      | text        |
| Yes      | series tag     | sports     | sports     | text      | text        |
| Yes      | series tag     | music      | music      | text      | text        |
| Yes      | series tag     | stu_gov    | stu_gov    | text      | text        |
| Yes      | series tag     | com_ser    | com_ser    | text      | text        |
| Yes      | series tag     | com_groups | com_groups | text      | text        |
| Yes      | series tag     | hrs_work   | hrs_work   | text      | text        |
| Yes      | series tag     | transskl   | transskl   | text      | text        |
| Yes      | series tag     | school     | SCHOOL     | text      | text        |
| Yes      | series tag     | surlang    | SURLANG    | text      | text        |
| Yes      | series tag     | thr_skl    | thr_skl    | text      | text        |
| Yes      | series tag     | thr_out    | thr_out    | text      | text        |
| Yes      | series tag     | cope       | cope       | text      | text        |
| Yes      | series tag     | control    | control    | text      | text        |
| Yes      | series tag     | exer_30    | exer_30    | text      | text        |
| Yes      | series tag     | less_30    | less_30    | text      | text        |
| Yes      | series tag     | light_7    | light_7    | text      | text        |
| Yes      | series tag     | past60mn   | past60mn   | text      | text        |
| Yes      | series tag     | typ60mn    | typ60mn    | text      | text        |
| Yes      | series tag     | aft_play   | aft_play   | text      | text        |
| Yes      | series tag     | aft_park   | aft_park   | text      | text        |
| Yes      | series tag     | aft_yard   | aft_yard   | text      | text        |
| Yes      | series tag     | aft_fiel   | aft_fiel   | text      | text        |
| Yes      | series tag     | aft_cntr   | aft_cntr   | text      | text        |
| Yes      | series tag     | aft_path   | aft_path   | text      | text        |
| Yes      | series tag     | aft_prog   | aft_prog   | text      | text        |
| Yes      | series tag     | enc_aft    | enc_aft    | text      | text        |
| Yes      | series tag     | enc_gym    | enc_gym    | text      | text        |
| Yes      | series tag     | enc_rec    | enc_rec    | text      | text        |
| Yes      | series tag     | enc_home   | enc_home   | text      | text        |
| Yes      | series tag     | enc_skl    | enc_skl    | text      | text        |
| Yes      | series tag     | drunk_30   | drunk_30   | text      | text        |
| Yes      | numeric metric | family     | family     | number    | number      |
| Yes      | numeric metric | children   | children   | number    | number      |
| Yes      | numeric metric | resolve    | resolve    | number    | number      |
| Yes      | numeric metric | manage     | manage     | number    | number      |
| Yes      | numeric metric | inj_fit    | inj_fit    | number    | number      |
| Yes      | numeric metric | tense      | tense      | number    | number      |
| Yes      | numeric metric | heartrac   | heartrac   | number    | number      |
| Yes      | numeric metric | soc_fear   | soc_fear   | number    | number      |
| Yes      | numeric metric | repeat     | repeat     | number    | number      |
| Yes      | numeric metric | fear       | fear       | number    | number      |
| Yes      | numeric metric | cigarage   | cigarage   | number    | number      |
| Yes      | numeric metric | chew_age   | chew_age   | number    | number      |
| Yes      | numeric metric | fr_smok    | fr_smok    | number    | number      |
| Yes      | numeric metric | fr_alc     | fr_alc     | number    | number      |
| Yes      | numeric metric | fr_pot     | fr_pot     | number    | number      |
| Yes      | numeric metric | fr_oth     | fr_oth     | number    | number      |
| Yes      | numeric metric | talk_sex   | talk_sex   | number    | number      |
| Yes      | numeric metric | study_7    | study_7    | number    | number      |
| Yes      | numeric metric | read_7     | read_7     | number    | number      |
| Yes      | numeric metric | work_7     | work_7     | number    | number      |
| Yes      | numeric metric | stren_7    | stren_7    | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = id
```

## Data Commands

```ls
series e:qvup-qejq d:2002-01-01T00:00:00.000Z t:dwi_ride="0 times" t:cig_get="I gave someone else money to buy them for me" t:had_std=No t:thr_skl=No t:race=White t:sex_num="1 person" t:sex_ever=Yes t:skl_gra="Mostly A's" t:alc_age="13 or 14 years old" t:stayhome=9 t:age="16 years old" t:gender=Male t:divorce=No t:fast_30=No t:samesex=No t:alc_30="3 to 5 days" t:death=Yes t:hiv_skl=9 t:cig_30="All 30 days" t:see_self=9 t:emo_abus=Yes t:sex_age="16 years old or older" t:ster_age=9 t:pot_30="1 or 2 times" t:exer_7=9 t:fad_30=No t:pregnant=Yes t:harassed=No t:attempt=9 t:depress=9 t:home="Public housing (Section 8, the projects)" t:gamble=9 t:chew_30="0 days" t:less_30=No t:trying=9 t:witness=No t:ran_away=Yes t:inha_age=9 t:exer_30=No t:consider=9 t:hurtdate=9 t:pills_30=No t:grade="Sophomore - 10th" t:treated=No t:mistreat=No t:off_skl=9 t:fut_ed="Finish college" t:alc5_30="3 to 5 days" t:moved=No t:orient="Heterosexual (straight)" t:plan=9 t:hiv_par=9 t:exp_tob=Yes t:vomit_30=No m:read_7=9 m:stren_7=9 m:work_7=9 m:resolve=9 m:inj_fit=9 m:manage=9 m:study_7=9

series e:qvup-qejq d:2002-01-01T00:00:00.000Z t:dwi_ride=9 t:cig_get=9 t:had_std=9 t:thr_skl=No t:race="Hispanic or Latino" t:sex_num=9 t:skl_gra=9 t:alc_age=9 t:stayhome=9 t:age="17 years old" t:gender=Male t:divorce=No t:fast_30=No t:samesex=9 t:alc_30=9 t:death=No t:hiv_skl=9 t:cig_30=9 t:see_self=9 t:emo_abus=No t:sex_age=9 t:ster_age=9 t:pot_30=9 t:exer_7=9 t:fad_30=No t:pregnant=9 t:harassed=No t:attempt=9 t:depress=9 t:home="A house/condo/apartment owned/rented by my parent/guardian" t:gamble=9 t:chew_30=9 t:less_30=No t:trying=9 t:witness=No t:ran_away=No t:inha_age=9 t:exer_30=No t:consider=9 t:hurtdate=9 t:pills_30=No t:grade="Junior - 11th" t:treated=9 t:mistreat=No t:off_skl=9 t:fut_ed="Finish college" t:alc5_30=9 t:moved=No t:orient=9 t:plan=9 t:hiv_par=9 t:exp_tob=9 t:vomit_30=No m:read_7=9 m:stren_7=9 m:work_7=9 m:talk_sex=9 m:resolve=9 m:inj_fit=9 m:manage=9 m:study_7=9

series e:qvup-qejq d:2002-01-01T00:00:00.000Z t:dwi_ride="0 times" t:cig_get="I did not smoke cigarettes in the past 30 days" t:had_std=No t:thr_skl=No t:race=Black t:sex_num="I have never had sexual intercourse" t:sex_ever=No t:skl_gra="Mostly B's" t:alc_age="I have never had a drink of alcohol other than a few sips" t:stayhome=9 t:age=9 t:gender=Female t:divorce=No t:fast_30=No t:samesex=No t:alc_30="0 days" t:death=No t:hiv_skl=9 t:cig_30="0 days" t:see_self=9 t:emo_abus=No t:sex_age="I have never had sexual intercourse" t:ster_age=No t:pot_30="0 times" t:exer_7=9 t:fad_30=No t:pregnant="I have never had sexual intercourse" t:harassed=No t:attempt=9 t:depress=9 t:home="A house/condo/apartment owned/rented by my parent/guardian" t:gamble=9 t:chew_30="0 days" t:less_30=No t:trying=9 t:witness=No t:ran_away=No t:inha_age=No t:exer_30=No t:consider=9 t:hurtdate=9 t:pills_30=No t:grade="Senior - 12th" t:treated=No t:mistreat=No t:off_skl=9 t:fut_ed="More than college" t:alc5_30="0 days" t:moved=Yes t:orient="Heterosexual (straight)" t:plan=9 t:hiv_par=9 t:exp_tob=No t:vomit_30=No m:read_7=9 m:stren_7=9 m:work_7=9 m:resolve=9 m:inj_fit=9 m:manage=9 m:study_7=9
```

## Meta Commands

```ls
metric m:nothing p:long l:nothing t:dataTypeName=number

metric m:trystop p:long l:trystop t:dataTypeName=number

metric m:teltea p:long l:teltea t:dataTypeName=number

metric m:telpar p:long l:telpar t:dataTypeName=number

metric m:telfri p:long l:telfri t:dataTypeName=number

metric m:tookpart p:long l:tookpart t:dataTypeName=number

metric m:justsaw p:long l:justsaw t:dataTypeName=number

metric m:intervene p:long l:intervene t:dataTypeName=number

metric m:toldtea p:long l:toldtea t:dataTypeName=number

metric m:family p:long l:family t:dataTypeName=number

metric m:children p:integer l:children t:dataTypeName=number

metric m:resolve p:integer l:resolve t:dataTypeName=number

metric m:manage p:integer l:manage t:dataTypeName=number

metric m:inj_fit p:integer l:inj_fit t:dataTypeName=number

metric m:tense p:long l:tense t:dataTypeName=number

metric m:heartrac p:long l:heartrac t:dataTypeName=number

metric m:soc_fear p:long l:soc_fear t:dataTypeName=number

metric m:repeat p:long l:repeat t:dataTypeName=number

metric m:fear p:long l:fear t:dataTypeName=number

metric m:cigarage p:long l:cigarage t:dataTypeName=number

metric m:chew_age p:long l:chew_age t:dataTypeName=number

metric m:fr_smok p:long l:fr_smok t:dataTypeName=number

metric m:fr_alc p:long l:fr_alc t:dataTypeName=number

metric m:fr_pot p:long l:fr_pot t:dataTypeName=number

metric m:fr_oth p:long l:fr_oth t:dataTypeName=number

metric m:talk_sex p:integer l:talk_sex t:dataTypeName=number

metric m:study_7 p:integer l:study_7 t:dataTypeName=number

metric m:read_7 p:integer l:read_7 t:dataTypeName=number

metric m:work_7 p:integer l:work_7 t:dataTypeName=number

metric m:stren_7 p:integer l:stren_7 t:dataTypeName=number

entity e:qvup-qejq l:"Somerville High School YRBS Raw Data 2002-2014" t:attribution="City of Somerville Health & Human Services Department" t:url=https://data.somervillema.gov/api/views/qvup-qejq

property e:qvup-qejq t:meta.view d:2017-06-09T13:53:13.892Z v:id=qvup-qejq v:category="Public Health" v:attributionLink=http://www.somervillema.gov/departments/health/office-of-prevention v:averageRating=0 v:name="Somerville High School YRBS Raw Data 2002-2014" v:attribution="City of Somerville Health & Human Services Department"

property e:qvup-qejq t:meta.view.license d:2017-06-09T13:53:13.892Z v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:qvup-qejq t:meta.view.owner d:2017-06-09T13:53:13.892Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:qvup-qejq t:meta.view.tableauthor d:2017-06-09T13:53:13.892Z v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| survey | year | id | age                   | gender | grade            | race                            | language         | live_us                                  | parents                     | home                                                       | skl_gra    | fut_ed             | witness | emo_abus | mistreat | harassed | hurtdate | gang | bull_skl         | nothing | trystop | teltea | telpar | telfri | saw_bul          | tookpart | justsaw | intervene | toldtea | bull_out     | bull_elec    | fit_skl      | fit_out        | weap_skl       | weap_out       | stayhome | divorce | moved | death | ran_away | friends   | adu_skl  | adu_oth                                             | skl_wor      | soc_wor      | appe_wor     | fam_wor      | gang_wor     | bul_wor      | hurtself     | depress | consider | plan | attempt | cig_lif | cig_age                               | cig_30 | cig_day                                        | cig_get                                        | cigar_30 | chew_30     | alc_age                                                   | alc_30      | alc5_30 | alc_get                                             | dwi_ride        | dwi_driv       | pot_age                      | pot_30       | inha_age | inha_30 | cok_age                    | cok_30  | her_age                  | her_30  | meth_age                           | meth_30 | ster_age | ster_30        | x_age                                  | x_30    | oxy_age                                                     | oxy_30  | oth_age                                          | oth_30  | beforskl | rx_high | otc_high | per_alc    | per_pot     | off_skl | treated | rsk_smok      | rsk_alc       | rsk_pott      | rsk_potr      | rsk_oth       | pa_smok            | pa_alc             | pa_pot             | pa_oth     | exp_tob | exp_alc | exp_pot | exp_oth | exp_gamb | sex_ever | sex_age                             | sex_num                             | sex_aod                             | sex_cond                            | prevpreg                            | samesex      | orient                  | pregnant                            | forced | had_std | hiv_skl      | hiv_par      | see_self               | trying                                         | fast_30 | pills_30 | vomit_30 | fad_30 | juice   | fruit   | veg     | soda    | sweets  | dairy   | brkfst_7 | exer_60 | tv_room | tv_hours                                   | comp_hrs                                                   | sleep_hrs       | exer_7   | gamble                  | clubs | sports | music | stu_gov | com_ser | com_groups | hrs_work           | transskl     | school        | surlang | thr_skl | thr_out | cope | control | exer_30 | less_30 | light_7 | past60mn | typ60mn | aft_play | aft_park | aft_yard | aft_fiel | aft_cntr | aft_path | aft_prog | enc_aft | enc_gym | enc_rec | enc_home | enc_skl | drunk_30 | family | children | resolve | manage | inj_fit | tense | heartrac | soc_fear | repeat | fear | cigarage | chew_age | fr_smok | fr_alc | fr_pot | fr_oth | talk_sex | study_7 | read_7 | work_7 | stren_7 | 
| ====== | ==== | == | ===================== | ====== | ================ | =============================== | ================ | ======================================== | =========================== | ========================================================== | ========== | ================== | ======= | ======== | ======== | ======== | ======== | ==== | ================ | ======= | ======= | ====== | ====== | ====== | ================ | ======== | ======= | ========= | ======= | ============ | ============ | ============ | ============== | ============== | ============== | ======== | ======= | ===== | ===== | ======== | ========= | ======== | =================================================== | ============ | ============ | ============ | ============ | ============ | ============ | ============ | ======= | ======== | ==== | ======= | ======= | ===================================== | ====== | ============================================== | ============================================== | ======== | =========== | ========================================================= | =========== | ======= | =================================================== | =============== | ============== | ============================ | ============ | ======== | ======= | ========================== | ======= | ======================== | ======= | ================================== | ======= | ======== | ============== | ====================================== | ======= | =========================================================== | ======= | ================================================ | ======= | ======== | ======= | ======== | ========== | =========== | ======= | ======= | ============= | ============= | ============= | ============= | ============= | ================== | ================== | ================== | ========== | ======= | ======= | ======= | ======= | ======== | ======== | =================================== | =================================== | =================================== | =================================== | =================================== | ============ | ======================= | =================================== | ====== | ======= | ============ | ============ | ====================== | ============================================== | ======= | ======== | ======== | ====== | ======= | ======= | ======= | ======= | ======= | ======= | ======== | ======= | ======= | ========================================== | ========================================================== | =============== | ======== | ======================= | ===== | ====== | ===== | ======= | ======= | ========== | ================== | ============ | ============= | ======= | ======= | ======= | ==== | ======= | ======= | ======= | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======== | ======= | ======== | ====== | ======== | ======= | ====== | ======= | ===== | ======== | ======== | ====== | ==== | ======== | ======== | ======= | ====== | ====== | ====== | ======== | ======= | ====== | ====== | ======= | 
| SH14   | 2014 |    | 17 years old          | Male   | Senior - 12th    | Asian or other Pacific Islander | Another language | Between 4-6 years                        | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly B's | More than college  | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 3 or 4    | Yes      | Yes, both family and non-family adults              | Never        | Never        | Never        | Never        | Never        | Never        | 0 times      | No      | No       | No   | 0 times | Yes     | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 15 or 16 years old                                        | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 0 times         | 0 times        | I have never tried marijuana | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 1% to 10%  | 11% to 20%  | No      | No      | Great Risk    | Moderate Risk | Slight Risk   | Moderate Risk | Moderate Risk | Very Wrong         | Very Wrong         | Very Wrong         | Very Wrong | No      | No      | No      | No      | No       | No       | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | No           | Heterosexual (straight) | I have never had sexual intercourse | No     | No      | I'm not sure | No           | About the right weight | Stay the same weight                           | No      | No       | No       | No     | 2 times | 3 times | 2 times | 0 times | 1 time  | 2 times | 7 days   | 7 days  | No      | I do not watch TV on an average school day | Don't use the computer/play video games on avg. school day | 8 hours         | 7 days   | I have never gambled    | Yes   | Yes    | No    | No      | Yes     | Yes        | 21-25 hours        | Walk         | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 2  | 17 years old          | Male   | Senior - 12th    | Asian or other Pacific Islander | Another language | Between 4-6 years                        | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly B's | Finish college     | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | None      | Not sure | Yes, parent, guardian, or other adult family member | Almost Never | Almost Never | Sometimes    | Almost Never | Never        | Almost Never | 0 times      | No      | No       | No   | 0 times | No      | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | I have never had a drink of alcohol other than a few sips | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 0 times         | I do not drive | I have never tried marijuana | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 0%         | 0%          | No      | No      | Moderate Risk | Moderate Risk | Slight Risk   | Slight Risk   | Moderate Risk | A Little Bit Wrong | A Little Bit Wrong | A Little Bit Wrong | Wrong      | No      | No      | No      | No      | No       | No       | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | No           | Heterosexual (straight) | I have never had sexual intercourse | No     | No      | Yes          | I'm not sure | About the right weight | Stay the same weight                           | No      | No       | No       | No     | 2 times | 2 times | 1 time  | 0 times | 1 time  | 2 times | 7 days   | 4 days  | No      | 1 hour per day                             | 1 hour per day                                             | 7 hours         | 3-4 days | Once or twice per year  | Yes   | Yes    | No    | No      | No      | No         |                    | Walk         | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 3  | 18 years old or older | Male   | Senior - 12th    | Asian or other Pacific Islander | Another language | More than 6 years, but not my whole life | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly B's | Finish college     |         |          |          |          |          |      | 0 times          |         |         |        |        |        | 2 or 3 times     |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 5 or more | Yes      | Yes, parent, guardian, or other adult family member | Sometimes    | Sometimes    | Sometimes    | Never        | Never        | Almost Never | 0 times      | No      | No       | No   | 0 times | Yes     | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 17 years old or older                                     | 1 or 2 days | 0 days  | My parents/guardians bought it for or gave it to me | 0 times         | I do not drive | I have never tried marijuana | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 61% to 70% | 81% to 90%  | Yes     | No      | Great Risk    | Slight Risk   | No Risk       | Slight Risk   | Great Risk    | Very Wrong         | Very Wrong         | Very Wrong         | Very Wrong | No      | No      | No      | No      | No       | No       | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | No           | Heterosexual (straight) | I have never had sexual intercourse | No     | No      | Yes          | No           | Slightly overweight    | Gain weight                                    | No      | No       | No       | No     | 2 times | 4 times | 0 times | 2 times | 3 times | 2 times | 1 day    | 4 days  | Yes     | 3 hours per day                            | Less than 1 hour per day                                   | 7 hours         | 3-4 days | At least once per month | Yes   | Yes    | No    | No      | No      | No         | 26-30 hours        | Walk         | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 4  | 17 years old          | Male   | Sophomore - 10th | Hispanic or Latino              | English          | I have always lived in the United States | My mother and a step-parent | A house/condo/apartment owned/rented by my parent/guardian | Mostly C's | I don't know       | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 4 or 5 times     |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 1 day    | No      | No    | Yes   | No       | 3 or 4    | Yes      | Yes, both family and non-family adults              | Fairly Often | Fairly Often | Very Often   | Fairly Often | Almost Never | Never        | 1 or 2 times | No      | No       | No   | 0 times | No      | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 13 or 14 years old                                        | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 0 times         | I do not drive | I have never tried marijuana | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 61% to 70% | 71% to 80%  | Yes     | No      | Great Risk    | Moderate Risk | Moderate Risk | Moderate Risk | Great Risk    | Very Wrong         | Very Wrong         | Very Wrong         | Very Wrong | Yes     | No      | Yes     | No      | Yes      | Yes      | 14-15 years old                     | 3 people                            | No                                  | Yes                                 | Condoms                             | No           | Heterosexual (straight) | I don't know                        | No     | No      | Yes          | Yes          | About the right weight | Stay the same weight                           | No      | No       | No       | No     | 0 times | 0 times | 1 time  | 1 time  | 0 times | 2 times | 3 days   | 6 days  | Yes     | 2 hours per day                            | 3 hours per day                                            | 6 hours         | 5-6 days | I have never gambled    | No    | No     | No    | No      | No      | No         | 11-15 hours        | Get a ride   | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 5  | 16 years old          | Male   | Junior - 11th    | Hispanic or Latino              | Spanish          | More than 6 years, but not my whole life | My mother and a step-parent | A house/condo/apartment owned/rented by my parent/guardian | Mostly C's | Finish college     | Yes     | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | Yes   | No    | No       | 3 or 4    | No       | Yes, non-family adult                               | Sometimes    | Never        | Sometimes    | Sometimes    | Never        | Never        | 1 or 2 times | No      | No       | No   | 0 times | Yes     | 13 or 14 years old                    | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 9 or 10 years old                                         | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 6 or more times | 0 times        | 11 or 12 years old           | 1 or 2 times | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 1 day    | 0 times | 0 times  | 51% to 60% | 61% to 70%  | Yes     | No      | Great Risk    | No Risk       | No Risk       | No Risk       | Moderate Risk | Wrong              | A Little Bit Wrong | Very Wrong         | Very Wrong | Yes     | Yes     | Yes     | No      | No       | Yes      | 12-13 years old                     | 3 people                            | No                                  | No                                  |                                     | No           | Heterosexual (straight) | Yes                                 | No     | No      | I'm not sure | No           | About the right weight | Lose weight                                    | Yes     | No       | No       | No     | 1 time  | 5 times | 3 times | 1 time  | 1 time  | 3 times | 0 days   | 4 days  | Yes     | 1 hour per day                             | 2 hours per day                                            | 5 hours         | 3-4 days | I have never gambled    | No    | No     | No    | No      | No      | No         | 5 hours or less    | Walk         | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 6  | 18 years old or older | Male   | Senior - 12th    | Hispanic or Latino              |                  | More than 6 years, but not my whole life | My mother and a step-parent | A house/condo/apartment owned/rented by my parent/guardian | Mostly B's | Finish college     | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 5 or more | Not sure | Yes, parent, guardian, or other adult family member | Almost Never | Almost Never | Almost Never | Almost Never | Never        | Almost Never | 0 times      | No      | No       | No   | 0 times | No      | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | I have never had a drink of alcohol other than a few sips | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 0 times         | I do not drive | I have never tried marijuana | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 81% to 90% | 81% to 90%  | Yes     | No      | Moderate Risk | Moderate Risk | Moderate Risk | Moderate Risk | Moderate Risk | Very Wrong         | Very Wrong         | Very Wrong         | Very Wrong | No      | No      | No      | No      | No       | No       | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | No           | Heterosexual (straight) | I have never had sexual intercourse | No     | No      | No           | No           | About the right weight | Stay the same weight                           | No      | No       | No       | No     | 3 times | 3 times | 3 times | 3 times | 2 times | 1 time  | 7 days   | 2 days  | Yes     | 5 or more hours per day                    | 3 hours per day                                            | 4 hours or less | 7 days   | I have never gambled    | No    | No     | No    | No      | No      | No         | None               | Get a ride   | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 7  | 18 years old or older | Male   | Senior - 12th    | White                           | English          | I have always lived in the United States | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly A's | Finish high school | No      | No       | Yes      | Yes      | No       | Yes  | 12 or more times |         |         |        |        |        | 12 or more times |          |         |           |         | 0 times      | 0 times      | 4 or 5 times | 10 or 11 times | 6 or more days | 6 or more days | 0 days   | No      | No    | Yes   | No       | None      | No       | No                                                  | Never        | Never        | Never        | Never        | Never        | Never        | 0 times      | No      | Yes      | Yes  | 0 times | Yes     | 13 or 14 years old                    | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 6 to 9 days | 13 or 14 years old                                        | 3 to 5 days | 0 days  | I bought it from a liquor store                     | 0 times         | 0 times        | 11 or 12 years old           | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | 7        | 10 to 19 times | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 81% to 90% | 91% to 100% | Yes     | No      | No Risk       | No Risk       | No Risk       | No Risk       | No Risk       | Very Wrong         | Not Wrong at All   | Very Wrong         | Very Wrong | No      | No      | No      | No      | No       | Yes      | 14-15 years old                     | 3 people                            | No                                  | Yes                                 | Condoms                             | No           | Heterosexual (straight) | I don't know                        | No     | No      | Yes          | No           | Slightly overweight    | Lose weight                                    | No      | No       | No       | No     | 5 times | 3 times | 5 times | 2 times | 5 times | 5 times | 7 days   | 3 days  | Yes     | 3 hours per day                            | Don't use the computer/play video games on avg. school day | 4 hours or less | 3-4 days | Weekly                  | Yes   | Yes    | No    | No      | No      | Yes        | More than 30 hours | Drive myself | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 8  | 17 years old          | Male   | Junior - 11th    | Hispanic or Latino              | Portuguese       | More than 6 years, but not my whole life | My mother only              | A house/condo/apartment owned/rented by my parent/guardian | Mostly C's | Finish college     | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 4 or 5 times | 2 or 3 times | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 5 or more | Yes      | Yes, both family and non-family adults              | Fairly Often | Fairly Often | Very Often   | Almost Never | Almost Never | Never        | 0 times      | No      | No       | No   | 0 times | No      | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 15 or 16 years old                                        | 1 or 2 days | 0 days  | Someone less than 21 bought it for or gave it to me | 0 times         | I do not drive | 15 or 16 years old           | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 11% to 20% | 1% to 10%   | No      | No      | Great Risk    | Moderate Risk | No Risk       | Slight Risk   | Great Risk    | Very Wrong         | A Little Bit Wrong | Very Wrong         | Very Wrong | No      | No      | No      | No      | No       | Yes      | 12-13 years old                     | 2 people                            | No                                  | Yes                                 | Condoms                             | No           | Heterosexual (straight) | No                                  | No     | No      | Yes          | I'm not sure | Slightly overweight    | Lose weight                                    | No      | Yes      | No       | No     | 0 times | 2 times | 2 times | 0 times | 0 times | 3 times | 4 days   | 6 days  | Yes     | I do not watch TV on an average school day | 1 hour per day                                             | 6 hours         | 5-6 days | I have never gambled    | No    | Yes    | No    | No      | No      | No         | 11-15 hours        | Get a ride   | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 9  | 17 years old          | Male   | Senior - 12th    | White                           | Portuguese       | More than 6 years, but not my whole life | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly A's | Finish college     | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 0 times          |          |         |           |         | 0 times      | 0 times      | 0 times      | 0 times        | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 1 or 2    | Yes      | No                                                  | Very Often   | Sometimes    | Almost Never | Fairly Often | Never        | Never        | 0 times      | No      | No       | No   | 0 times | No      | I have never smoked a whole cigarette | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 15 or 16 years old                                        | 0 days      | 0 days  | I did not drink alcohol in the last 30 days         | 0 times         | I do not drive | 15 or 16 years old           | 1 or 2 times | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 51% to 60% | 51% to 60%  | No      | No      | Great Risk    | Moderate Risk | No Risk       | Slight Risk   | Great Risk    | Wrong              | Wrong              | Wrong              | Wrong      | No      | No      | Yes     | No      | No       | Yes      | 16 years old or older               | 2 people                            | No                                  | Yes                                 | Condoms                             | No           | Heterosexual (straight) | No                                  | No     | No      | Yes          | No           | About the right weight | I am not trying to do anything about my weight | No      | No       | No       | No     | 2 times | 1 time  | 0 times | 3 times | 2 times | 1 time  | 5 days   | 3 days  | Yes     | 1 hour per day                             | 3 hours per day                                            | 7 hours         | 1-2 days | I have never gambled    | Yes   | No     | No    | No      | No      | No         | More than 30 hours | Take a bus   | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
| SH14   | 2014 | 10 | 18 years old or older | Male   | Senior - 12th    | Hispanic or Latino              | Spanish          | I have always lived in the United States | My mother and my father     | A house/condo/apartment owned/rented by my parent/guardian | Mostly B's | Finish college     | No      | No       | No       | No       | No       | No   | 0 times          |         |         |        |        |        | 4 or 5 times     |          |         |           |         | 2 or 3 times | 0 times      | 2 or 3 times | 1 time         | 0 days         | 0 days         | 0 days   | No      | No    | No    | No       | 1 or 2    | No       | Yes, parent, guardian, or other adult family member | Fairly Often | Sometimes    | Very Often   | Fairly Often | Fairly Often | Almost Never | 0 times      | No      | No       | No   | 0 times | Yes     | 15 or 16 years old                    | 0 days | I did not smoke cigarettes in the past 30 days | I did not smoke cigarettes in the past 30 days | 0 days   | 0 days      | 11 or 12 years old                                        | 1 or 2 days | 0 days  | I did not drink alcohol in the last 30 days         | 1 time          | I do not drive | 13 or 14 years old           | 0 times      | No       | 0 times | I have never tried cocaine | 0 times | I have never used heroin | 0 times | I have never used methamphetamines | 0 times | No       | 0 times        | I have never used ecstasy (MDMA, E, X) | 0 times | I have never used oxycontin without a doctor's prescription | 0 times | I have never used any other type of illegal drug | 0 times | 0 days   | 0 times | 0 times  | 0%         | 0%          | No      | No      | Moderate Risk | Slight Risk   | Slight Risk   | Slight Risk   | Moderate Risk | Very Wrong         | A Little Bit Wrong | Wrong              | Very Wrong | No      | Yes     | No      | No      | Yes      | No       | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I have never had sexual intercourse | I'm not sure | Not sure                | I have never had sexual intercourse | No     | No      | No           | No           | Slightly overweight    | Lose weight                                    | No      | No       | No       | No     | 1 time  | 2 times | 3 times | 0 times | 1 time  | 3 times | 1 day    | 3 days  | Yes     | 2 hours per day                            | Don't use the computer/play video games on avg. school day | 7 hours         | 0 days   | I have never gambled    | No    | No     | No    | No      | No      | No         | None               | Walk         | Somerville HS | English |         |         |      |         |         |         |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |          |        |          |         |        |         |       |          |          |        |      |          |          |         |        |        |        |          |         |        |        |         | 
```