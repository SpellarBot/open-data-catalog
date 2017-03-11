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
| Rows Updated | 2016-02-04T13:53:31Z |

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

series e:qvup-qejq d:2002-01-01T00:00:00.000Z t:dwi_ride=9 t:cig_get=9 t:had_std=9 t:thr_skl=No t:race="Hispanic or Latino" t:sex_num=9 t:skl_gra=9 t:alc_age=9 t:stayhome=9 t:age="17 years old" t:gender=Male t:divorce=No t:fast_30=No t:samesex=9 t:alc_30=9 t:death=No t:hiv_skl=9 t:cig_30=9 t:see_self=9 t:emo_abus=No t:sex_age=9 t:ster_age=9 t:pot_30=9 t:exer_7=9 t:fad_30=No t:pregnant=9 t:harassed=No t:attempt=9 t:depress=9 t:home="A house/condo/apartment owned/rented by my parent/guardian" t:gamble=9 t:chew_30=9 t:less_30=No t:trying=9 t:witness=No t:ran_away=No t:inha_age=9 t:exer_30=No t:consider=9 t:hurtdate=9 t:pills_30=No t:grade="Junior - 11th" t:treated=9 t:mistreat=No t:off_skl=9 t:fut_ed="Finish college" t:alc5_30=9 t:moved=No t:orient=9 t:plan=9 t:hiv_par=9 t:exp_tob=9 t:vomit_30=No m:read_7=9 m:stren_7=9 m:talk_sex=9 m:work_7=9 m:resolve=9 m:inj_fit=9 m:manage=9 m:study_7=9

series e:qvup-qejq d:2002-01-01T00:00:00.000Z t:dwi_ride="0 times" t:cig_get="I did not smoke cigarettes in the past 30 days" t:had_std=No t:thr_skl=No t:race=Black t:sex_num="I have never had sexual intercourse" t:sex_ever=No t:skl_gra="Mostly B's" t:alc_age="I have never had a drink of alcohol other than a few sips" t:stayhome=9 t:age=9 t:gender=Female t:divorce=No t:fast_30=No t:samesex=No t:alc_30="0 days" t:death=No t:hiv_skl=9 t:cig_30="0 days" t:see_self=9 t:emo_abus=No t:sex_age="I have never had sexual intercourse" t:ster_age=No t:pot_30="0 times" t:exer_7=9 t:fad_30=No t:pregnant="I have never had sexual intercourse" t:harassed=No t:attempt=9 t:depress=9 t:home="A house/condo/apartment owned/rented by my parent/guardian" t:gamble=9 t:chew_30="0 days" t:less_30=No t:trying=9 t:witness=No t:ran_away=No t:inha_age=No t:exer_30=No t:consider=9 t:hurtdate=9 t:pills_30=No t:grade="Senior - 12th" t:treated=No t:mistreat=No t:off_skl=9 t:fut_ed="More than college" t:alc5_30="0 days" t:moved=Yes t:orient="Heterosexual (straight)" t:plan=9 t:hiv_par=9 t:exp_tob=No t:vomit_30=No m:read_7=9 m:stren_7=9 m:work_7=9 m:resolve=9 m:inj_fit=9 m:manage=9 m:study_7=9
```

## Meta Commands

```ls
metric m:nothing l:nothing t:dataTypeName=number

metric m:trystop l:trystop t:dataTypeName=number

metric m:teltea l:teltea t:dataTypeName=number

metric m:telpar l:telpar t:dataTypeName=number

metric m:telfri l:telfri t:dataTypeName=number

metric m:tookpart l:tookpart t:dataTypeName=number

metric m:justsaw l:justsaw t:dataTypeName=number

metric m:intervene l:intervene t:dataTypeName=number

metric m:toldtea l:toldtea t:dataTypeName=number

metric m:family l:family t:dataTypeName=number

metric m:children p:integer l:children t:dataTypeName=number

metric m:resolve p:integer l:resolve t:dataTypeName=number

metric m:manage p:integer l:manage t:dataTypeName=number

metric m:inj_fit p:integer l:inj_fit t:dataTypeName=number

metric m:tense l:tense t:dataTypeName=number

metric m:heartrac l:heartrac t:dataTypeName=number

metric m:soc_fear l:soc_fear t:dataTypeName=number

metric m:repeat l:repeat t:dataTypeName=number

metric m:fear l:fear t:dataTypeName=number

metric m:cigarage l:cigarage t:dataTypeName=number

metric m:chew_age l:chew_age t:dataTypeName=number

metric m:fr_smok l:fr_smok t:dataTypeName=number

metric m:fr_alc l:fr_alc t:dataTypeName=number

metric m:fr_pot l:fr_pot t:dataTypeName=number

metric m:fr_oth l:fr_oth t:dataTypeName=number

metric m:talk_sex p:integer l:talk_sex t:dataTypeName=number

metric m:study_7 p:integer l:study_7 t:dataTypeName=number

metric m:read_7 p:integer l:read_7 t:dataTypeName=number

metric m:work_7 p:integer l:work_7 t:dataTypeName=number

metric m:stren_7 p:integer l:stren_7 t:dataTypeName=number

entity e:qvup-qejq l:"Somerville High School YRBS Raw Data 2002-2014" t:attribution="City of Somerville Health & Human Services Department" t:url=https://data.somervillema.gov/api/views/qvup-qejq

property e:qvup-qejq t:meta.view v:id=qvup-qejq v:category="Public Health" v:attributionLink=http://www.somervillema.gov/departments/health/office-of-prevention v:averageRating=0 v:name="Somerville High School YRBS Raw Data 2002-2014" v:attribution="City of Somerville Health & Human Services Department"

property e:qvup-qejq t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:qvup-qejq t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"

property e:qvup-qejq t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```