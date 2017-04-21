# Somerville Middle School YRBS Raw Data 2003-2015

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/somerville-middle-school-yrbs-raw-data-2003-2015) |
| Metadata | [Link](https://data.somervillema.gov/api/views/v6hb-z5zm) |
| Data: JSON | [100 Rows](https://data.somervillema.gov/api/views/v6hb-z5zm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.somervillema.gov/api/views/v6hb-z5zm/rows.csv?max_rows=100) |
| Host | data.somervillema.gov |
| Id | v6hb-z5zm |
| Name | Somerville Middle School YRBS Raw Data 2003-2015 |
| Attribution | City of Somerville Health & Human Services Department |
| Category | Public Health |
| Tags | hhs, yrbs, schools |
| Created | 2016-02-03T18:46:13Z |
| Publication Date | 2016-02-04T14:20:59Z |

## Description

The City of Somerville conducts the Youth Risk Behavior Survey each year to gather data about students' risk behaviors. On an annual basis, Health & Human Services staff coordinate a survey with either High School or Middle School students in alternating years.

The data presented in this table is from middle school students from 2003 through 2015 and includes questions about tobacco use, alcohol and other drug use, sexual behaviors that might lead to unintended pregnancy or sexually transmitted disease, dietary behaviors, physical activity, and behaviors associated with intentional or unintentional injuries. Data from the YRBS provide accurate estimates of the prevalence of risk behaviors among public school students in the City, and are important for planning health education and risk prevention programs.

Attached is the questionnaire used in the survey which includes information regarding the variables used in the dataset.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| No       |                | year                   | year                   | number        | number        |
| Yes      | series tag     | school                 | school                 | text          | text          |
| Yes      | numeric metric | version                | version                | number        | number        |
| Yes      | series tag     | gender                 | gender                 | text          | text          |
| Yes      | series tag     | grade                  | grade                  | text          | text          |
| Yes      | series tag     | age                    | age                    | text          | text          |
| Yes      | series tag     | race                   | race                   | text          | text          |
| Yes      | series tag     | language               | language               | text          | text          |
| Yes      | series tag     | live_us                | live_us                | text          | text          |
| Yes      | series tag     | parents                | parents                | text          | text          |
| Yes      | series tag     | edplans                | edplans                | text          | text          |
| Yes      | series tag     | doct_12                | doct_12                | text          | text          |
| Yes      | series tag     | dent_12                | dent_12                | text          | text          |
| Yes      | series tag     | fail_12                | fail_12                | text          | text          |
| Yes      | series tag     | drupr_12               | drupr_12               | text          | text          |
| Yes      | series tag     | famdr_12               | famdr_12               | text          | text          |
| Yes      | series tag     | divor_12               | divor_12               | text          | text          |
| Yes      | series tag     | moved_12               | moved_12               | text          | text          |
| Yes      | series tag     | ran_12                 | ran_12                 | text          | text          |
| Yes      | series tag     | died_12                | died_12                | text          | text          |
| Yes      | series tag     | gang_12                | gang_12                | text          | text          |
| Yes      | series tag     | wor_heal               | wor_heal               | text          | text          |
| Yes      | series tag     | wor_weig               | wor_weig               | text          | text          |
| Yes      | series tag     | wor_abus               | wor_abus               | text          | text          |
| Yes      | series tag     | wor_fail               | wor_fail               | text          | text          |
| Yes      | series tag     | wor_f_dr               | wor_f_dr               | text          | text          |
| Yes      | series tag     | wor_y_dr               | wor_y_dr               | text          | text          |
| Yes      | series tag     | wor_h_ft               | wor_h_ft               | text          | text          |
| Yes      | series tag     | wor_s_ft               | wor_s_ft               | text          | text          |
| Yes      | series tag     | wor_disc               | wor_disc               | text          | text          |
| Yes      | series tag     | wor_bul                | WOR_BUL                | text          | text          |
| Yes      | series tag     | wor_gang               | wor_gang               | text          | text          |
| Yes      | series tag     | adu_skl                | adu_skl                | text          | text          |
| Yes      | series tag     | friends                | friends                | text          | text          |
| Yes      | series tag     | hurtself               | hurtself               | text          | text          |
| Yes      | series tag     | consider               | consider               | text          | text          |
| Yes      | series tag     | plan                   | plan                   | text          | text          |
| Yes      | series tag     | attempt                | attempt                | text          | text          |
| Yes      | series tag     | vio_12                 | vio_12                 | text          | text          |
| Yes      | series tag     | f_hur_12               | f_hur_12               | text          | text          |
| Yes      | series tag     | o_hur_12               | o_hur_12               | text          | text          |
| Yes      | series tag     | fite_skl               | fite_skl               | text          | text          |
| Yes      | series tag     | fite_out               | fite_out               | text          | text          |
| Yes      | series tag     | bulli_12               | bulli_12               | text          | text          |
| Yes      | numeric metric | nothing                | NOTHING                | number        | number        |
| Yes      | numeric metric | trystop                | TRYSTOP                | number        | number        |
| Yes      | numeric metric | teltea                 | TELTEA                 | number        | number        |
| Yes      | numeric metric | telpar                 | TELPAR                 | number        | number        |
| Yes      | numeric metric | telfri                 | TELFRI                 | number        | number        |
| Yes      | series tag     | saw_bul                | SAW_BUL                | text          | text          |
| Yes      | numeric metric | tookpart               | TOOKPART               | number        | number        |
| Yes      | numeric metric | justsaw                | JUSTSAW                | number        | number        |
| Yes      | numeric metric | intervene              | INTERVENE              | number        | number        |
| Yes      | numeric metric | toldtea                | TOLDTEA                | number        | number        |
| Yes      | series tag     | bull_out               | bull_out               | text          | text          |
| Yes      | series tag     | bull_elec              | BULL_ELEC              | text          | text          |
| Yes      | series tag     | edu_reso               | edu_reso               | text          | text          |
| Yes      | series tag     | stayhome               | stayhome               | text          | text          |
| Yes      | series tag     | weap_skl               | weap_skl               | text          | text          |
| Yes      | series tag     | weap_out               | weap_out               | text          | text          |
| Yes      | series tag     | seatbelt               | seatbelt               | text          | text          |
| Yes      | series tag     | helmet                 | helmet                 | text          | text          |
| Yes      | series tag     | cig_lif                | cig_lif                | text          | text          |
| Yes      | series tag     | cigs_old               | cigs_old               | text          | text          |
| Yes      | series tag     | cigs_30                | cigs_30                | text          | text          |
| Yes      | series tag     | cig_day                | cig_day                | text          | text          |
| Yes      | series tag     | cigs_get               | cigs_get               | text          | text          |
| Yes      | series tag     | edu_tob                | edu_tob                | text          | text          |
| Yes      | series tag     | tob_talk               | tob_talk               | text          | text          |
| Yes      | series tag     | alc_age                | alc_age                | text          | text          |
| Yes      | series tag     | alc_30                 | alc_30                 | text          | text          |
| Yes      | series tag     | alc5_30                | alc5_30                | text          | text          |
| Yes      | series tag     | alc_get                | alc_get                | text          | text          |
| Yes      | series tag     | alc_rid                | alc_rid                | text          | text          |
| Yes      | series tag     | pot_age                | pot_age                | text          | text          |
| Yes      | series tag     | pot_30                 | pot_30                 | text          | text          |
| Yes      | series tag     | glu_age                | glu_age                | text          | text          |
| Yes      | series tag     | glu_30                 | glu_30                 | text          | text          |
| Yes      | series tag     | ster_lif               | ster_lif               | text          | text          |
| Yes      | series tag     | ster_30                | ster_30                | text          | text          |
| Yes      | series tag     | cok_age                | cok_age                | text          | text          |
| Yes      | series tag     | cok_30                 | cok_30                 | text          | text          |
| Yes      | series tag     | her_age                | her_age                | text          | text          |
| Yes      | series tag     | her_30                 | her_30                 | text          | text          |
| Yes      | series tag     | x_age                  | x_age                  | text          | text          |
| Yes      | series tag     | x_30                   | x_30                   | text          | text          |
| Yes      | series tag     | oxy_age                | oxy_age                | text          | text          |
| Yes      | series tag     | oxy_30                 | oxy_30                 | text          | text          |
| Yes      | series tag     | oth_age                | oth_age                | text          | text          |
| Yes      | series tag     | other_30               | other_30               | text          | text          |
| Yes      | series tag     | beforskl               | beforskl               | text          | text          |
| Yes      | series tag     | edu_dru                | edu_dru                | text          | text          |
| Yes      | series tag     | dru_talk               | dru_talk               | text          | text          |
| Yes      | series tag     | edu_pres               | edu_pres               | text          | text          |
| Yes      | series tag     | off_skl                | off_skl                | text          | text          |
| Yes      | series tag     | cig_harm               | cig_harm               | text          | text          |
| Yes      | series tag     | alc_harm               | alc_harm               | text          | text          |
| Yes      | series tag     | pot_harm               | pot_harm               | text          | text          |
| Yes      | series tag     | oth_harm               | oth_harm               | text          | text          |
| Yes      | series tag     | fr_smok                | fr_smok                | text          | text          |
| Yes      | series tag     | fr_alc                 | fr_alc                 | text          | text          |
| Yes      | series tag     | fr_pot                 | fr_pot                 | text          | text          |
| Yes      | series tag     | fr_oth                 | fr_oth                 | text          | text          |
| Yes      | series tag     | pa_smok                | pa_smok                | text          | text          |
| Yes      | series tag     | pa_alc                 | pa_alc                 | text          | text          |
| Yes      | series tag     | pa_pot                 | pa_pot                 | text          | text          |
| Yes      | series tag     | pa_oth                 | pa_oth                 | text          | text          |
| Yes      | series tag     | famsmok                | famsmok                | text          | text          |
| Yes      | series tag     | famalc                 | famalc                 | text          | text          |
| Yes      | series tag     | fampot                 | fampot                 | text          | text          |
| Yes      | series tag     | famoth                 | famoth                 | text          | text          |
| Yes      | series tag     | hiv_skl                | hiv_skl                | text          | text          |
| Yes      | series tag     | hiv_par                | hiv_par                | text          | text          |
| Yes      | series tag     | sex_talk               | sex_talk               | text          | text          |
| Yes      | series tag     | sex_had                | sex_had                | text          | text          |
| Yes      | series tag     | rude_12                | rude_12                | text          | text          |
| Yes      | series tag     | touch_12               | touch_12               | text          | text          |
| Yes      | series tag     | force_12               | force_12               | text          | text          |
| Yes      | series tag     | edu_nutr               | edu_nutr               | text          | text          |
| Yes      | series tag     | nutr_tlk               | nutr_tlk               | text          | text          |
| Yes      | series tag     | exer_60                | EXER_60                | text          | text          |
| Yes      | series tag     | see_self               | see_self               | text          | text          |
| Yes      | series tag     | trying                 | trying                 | text          | text          |
| Yes      | series tag     | less_12                | less_12                | text          | text          |
| Yes      | series tag     | fast_12                | fast_12                | text          | text          |
| Yes      | series tag     | diet_12                | diet_12                | text          | text          |
| Yes      | series tag     | breakfst               | breakfst               | text          | text          |
| Yes      | series tag     | juice                  | juice                  | text          | text          |
| Yes      | series tag     | fruit                  | fruit                  | text          | text          |
| Yes      | series tag     | veggies                | veggies                | text          | text          |
| Yes      | series tag     | soda                   | soda                   | text          | text          |
| Yes      | series tag     | sweets                 | sweets                 | text          | text          |
| Yes      | series tag     | dairy                  | dairy                  | text          | text          |
| Yes      | series tag     | sweat                  | sweat                  | text          | text          |
| Yes      | series tag     | transskl               | transskl               | text          | text          |
| Yes      | series tag     | read_7                 | read_7                 | text          | text          |
| Yes      | series tag     | music_7                | music_7                | text          | text          |
| Yes      | series tag     | sports_7               | sports_7               | text          | text          |
| Yes      | series tag     | clubs_7                | clubs_7                | text          | text          |
| Yes      | series tag     | volun_7                | volun_7                | text          | text          |
| Yes      | series tag     | commu_7                | commu_7                | text          | text          |
| Yes      | series tag     | tv_room                | tv_room                | text          | text          |
| Yes      | series tag     | tv_av                  | tv_av                  | text          | text          |
| Yes      | series tag     | alone_av               | alone_av               | text          | text          |
| Yes      | series tag     | study_av               | study_av               | text          | text          |
| Yes      | series tag     | comp_av                | comp_av                | text          | text          |
| Yes      | series tag     | sleep                  | SLEEP                  | text          | text          |
| Yes      | numeric metric | omit                   | OMIT                   | number        | number        |
| Yes      | series tag     | sch_thre               | sch_thre               | text          | text          |
| Yes      | series tag     | out_thre               | out_thre               | text          | text          |
| Yes      | series tag     | nosweat                | nosweat                | text          | text          |
| Yes      | series tag     | past60mn               | past60mn               | text          | text          |
| Yes      | series tag     | typ60mn                | typ60mn                | text          | text          |
| Yes      | series tag     | aft_play               | aft_play               | text          | text          |
| Yes      | series tag     | aft_park               | aft_park               | text          | text          |
| Yes      | series tag     | aft_yard               | aft_yard               | text          | text          |
| Yes      | series tag     | aft_fiel               | aft_fiel               | text          | text          |
| Yes      | series tag     | aft_cntr               | aft_cntr               | text          | text          |
| Yes      | series tag     | aft_path               | aft_path               | text          | text          |
| Yes      | series tag     | aft_prog               | aft_prog               | text          | text          |
| Yes      | series tag     | enc_aft                | enc_aft                | text          | text          |
| Yes      | series tag     | enc_gym                | enc_gym                | text          | text          |
| Yes      | series tag     | enc_rec                | enc_rec                | text          | text          |
| Yes      | series tag     | enc_home               | enc_home               | text          | text          |
| Yes      | series tag     | enc_skl                | enc_skl                | text          | text          |
| Yes      | numeric metric | count_miss             | COUNT_MISS             | number        | number        |
| Yes      | time           | age2_sub               | AGE2_SUB               | calendar_date | calendar_date |
| No       |                | cigs_old2              | CIGS_OLD2              | calendar_date | calendar_date |
| No       |                | alc_age2               | ALC_AGE2               | calendar_date | calendar_date |
| No       |                | pot_age2               | POT_AGE2               | calendar_date | calendar_date |
| No       |                | cok_age2               | COK_AGE2               | calendar_date | calendar_date |
| Yes      | numeric metric | ster_lif2              | STER_LIF2              | number        | number        |
| Yes      | numeric metric | her_age2               | HER_AGE2               | number        | number        |
| Yes      | numeric metric | x_age2                 | X_AGE2                 | number        | number        |
| Yes      | numeric metric | oxy_age2               | OXY_AGE2               | number        | number        |
| No       |                | oth_age2               | OTH_AGE2               | calendar_date | calendar_date |
| Yes      | numeric metric | screen_missing         | SCREEN_MISSING         | number        | number        |
| Yes      | numeric metric | screen_lifedrug        | SCREEN_LIFEDRUG        | number        | number        |
| Yes      | numeric metric | screen_drugage         | SCREEN_DRUGAGE         | number        | number        |
| Yes      | numeric metric | screen_druglifeextreme | SCREEN_DRUGLIFEEXTREME | number        | number        |
| Yes      | numeric metric | screen_drug30extreme   | SCREEN_DRUG30EXTREME   | number        | number        |
| Yes      | numeric metric | screen_other           | SCREEN_OTHER           | number        | number        |
| Yes      | numeric metric | screen_sex             | SCREEN_SEX             | number        | number        |
| Yes      | numeric metric | eye_12                 | eye_12                 | number        | number        |
| Yes      | numeric metric | couns_12               | couns_12               | number        | number        |
| Yes      | numeric metric | scnur_12               | scnur_12               | number        | number        |
| Yes      | numeric metric | talk_par               | talk_par               | number        | number        |
| Yes      | numeric metric | talk_fam               | talk_fam               | number        | number        |
| Yes      | numeric metric | talk_tea               | talk_tea               | number        | number        |
| Yes      | numeric metric | talk_nur               | talk_nur               | number        | number        |
| Yes      | numeric metric | talk_coa               | talk_coa               | number        | number        |
| Yes      | numeric metric | talk_adu               | talk_adu               | number        | number        |
| Yes      | numeric metric | talk_fre               | talk_fre               | number        | number        |
| Yes      | series tag     | talk_no                | talk_no                | text          | number        |
| Yes      | numeric metric | talk_oth               | talk_oth               | number        | number        |
| Yes      | numeric metric | wor_depr               | wor_depr               | number        | number        |
| Yes      | numeric metric | thret_12               | thret_12               | number        | number        |
| Yes      | numeric metric | cig_age                | cig_age                | number        | number        |
| Yes      | numeric metric | cig_30                 | cig_30                 | number        | number        |
| Yes      | numeric metric | cig_get                | cig_get                | number        | number        |
| Yes      | numeric metric | chew_30                | chew_30                | number        | number        |
| Yes      | numeric metric | alc_12                 | alc_12                 | number        | number        |
| Yes      | numeric metric | edu_alc                | edu_alc                | number        | number        |
| Yes      | numeric metric | dru_age                | dru_age                | number        | number        |
| Yes      | numeric metric | pot_12                 | pot_12                 | number        | number        |
| Yes      | numeric metric | cok_12                 | cok_12                 | number        | number        |
| Yes      | numeric metric | oth_30                 | oth_30                 | number        | number        |
| Yes      | numeric metric | oth_12                 | oth_12                 | number        | number        |
| Yes      | numeric metric | glu_12                 | glu_12                 | number        | number        |
| Yes      | numeric metric | fr_cigoc               | fr_cigoc               | number        | number        |
| Yes      | numeric metric | fr_cigre               | fr_cigre               | number        | number        |
| Yes      | numeric metric | fr_alcoc               | fr_alcoc               | number        | number        |
| Yes      | numeric metric | fr_alcre               | fr_alcre               | number        | number        |
| Yes      | numeric metric | fr_pottr               | fr_pottr               | number        | number        |
| Yes      | numeric metric | fr_potoc               | fr_potoc               | number        | number        |
| Yes      | numeric metric | fr_potre               | fr_potre               | number        | number        |
| Yes      | numeric metric | pa_cigoc               | pa_cigoc               | number        | number        |
| Yes      | numeric metric | pa_cigre               | pa_cigre               | number        | number        |
| Yes      | numeric metric | pa_alcoc               | pa_alcoc               | number        | number        |
| Yes      | numeric metric | pa_alcre               | pa_alcre               | number        | number        |
| Yes      | numeric metric | pa_pottr               | pa_pottr               | number        | number        |
| Yes      | numeric metric | pa_potoc               | pa_potoc               | number        | number        |
| Yes      | numeric metric | pa_potre               | pa_potre               | number        | number        |
| Yes      | numeric metric | sch_prop               | sch_prop               | number        | number        |
| Yes      | numeric metric | fit_12                 | fit_12                 | number        | number        |
| Yes      | numeric metric | weap_30                | weap_30                | number        | number        |
| Yes      | numeric metric | exer_12                | exer_12                | number        | number        |
| Yes      | numeric metric | smok_12                | smok_12                | number        | number        |
| Yes      | numeric metric | pills_12               | pills_12               | number        | number        |
| Yes      | numeric metric | lax_12                 | lax_12                 | number        | number        |
| Yes      | numeric metric | few_12                 | few_12                 | number        | number        |
| Yes      | numeric metric | vomit_12               | vomit_12               | number        | number        |
| Yes      | numeric metric | fried_12               | fried_12               | number        | number        |
```

## Time Field

```ls
Value = age2_sub
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = cigs_old2,alc_age2,pot_age2,cok_age2,oth_age2,year
```

## Data Commands

```ls
series e:v6hb-z5zm d:2016-02-03T10:46:41.000Z t:rude_12=No t:pa_alc="Very Wrong" t:less_12=No t:fite_out=No t:hurtself=No t:volun_7=No t:alc_harm="Moderate Risk" t:bull_out=No t:fite_skl=No t:sports_7=No t:tob_talk=Yes t:dent_12=Yes t:juice="5 times" t:fail_12=No t:famalc=No t:study_av="2 hours" t:ran_12=No t:pa_smok="Very Wrong" t:x_age="I have never used ecstasy (E, X, MDMA)" t:hiv_skl=No t:dru_talk=Yes t:oth_age="I have never used any other type of illegal drug" t:edplans="Finish college" t:force_12=No t:dairy="5 times" t:sleep="10 or more hours" t:pot_age="I have never tried marijuana" t:edu_nutr=Yes t:her_age="I have never used heroin" t:alc_rid=No t:died_12=Yes t:music_7=No t:pot_30="0 times" t:other_30=No t:cok_30=No t:edu_pres=No t:language=English t:her_30=No t:sweat="All 7 days" t:comp_av="Less than 1 hour" t:wor_f_dr=No t:nutr_tlk="I'm not sure" t:divor_12=Yes t:glu_30="0 times" t:trying="Stay the same weight" t:seatbelt=Always t:read_7=Yes t:fr_pot="Very Wrong" t:consider=No t:wor_h_ft=No t:grade="6th grade" t:cig_lif=No t:moved_12=No t:edu_tob=No t:doct_12=Yes t:fr_smok="Very Wrong" t:x_30=No t:cigs_get="I did not smoke cigarettes in the past 30 days" t:wor_weig=No t:pa_pot="Very Wrong" t:sweets="2 times" t:bull_elec=No t:cigs_old="I have never smoked a whole cigarette" t:beforskl="0 days" t:tv_av="2 hours" t:veggies="5 times" t:sex_talk="Very helpful" t:soda="0 times" t:fr_alc="Very Wrong" t:saw_bul=No t:gang_12=No t:f_hur_12=No t:hiv_par=No t:wor_disc=No t:wor_gang=No t:fampot=No t:pot_harm="Moderate Risk" t:edu_dru="I'm not sure" t:drupr_12=No t:ster_lif=No t:helmet="Always wore a helmet" t:race=White t:alc_get="I did not drink alcohol in the last 30 days" t:friends="5 or more" t:alc_age="I have never had a drink of alcohol other than a few sips" t:edu_reso=Yes t:age="11 years old" t:stayhome="0 days" t:glu_age="I have never sniffed or huffed fumes to get high" t:gender=Male t:cig_day="I did not smoke cigarettes during the past 30 days" t:alone_av="4 or more hours" t:weap_out="0 days" t:fruit="5 times" t:sex_had=No t:alc_30="0 days" t:vio_12=No t:cok_age="I have never tried cocaine" t:breakfst="All 7 days" t:see_self="About the right weight" t:wor_heal=No t:live_us="I have always lived in the United States" t:famsmok=No t:bulli_12=No t:weap_skl="0 days" t:exer_60="All 7 days" t:attempt=No t:parents="My father only" t:fast_12=No t:touch_12=No t:fr_oth="Very Wrong" t:adu_skl=Yes t:clubs_7=No t:oxy_30=No t:commu_7=No t:wor_bul=Yes t:cig_harm="Great Risk" t:oth_harm="Great Risk" t:diet_12=No t:cigs_30="0 days" t:tv_room=No t:wor_fail=No t:wor_y_dr=No t:wor_abus=No t:off_skl=No t:famoth=No t:alc5_30=No t:oxy_age="I have never used oxycontin without a doctor's prescription" t:school="Argenziano (LP)" t:plan=No t:ster_30=No t:transskl=Walk t:pa_oth="Very Wrong" t:wor_s_ft=No t:o_hur_12=No t:famdr_12=No m:version=500

series e:v6hb-z5zm d:2016-02-03T10:46:41.000Z t:rude_12=No t:pa_alc="Very Wrong" t:less_12=No t:fite_out=No t:hurtself=No t:volun_7=No t:alc_harm="Slight Risk" t:bull_out=Yes t:fite_skl=No t:sports_7=No t:tob_talk=Yes t:dent_12=Yes t:juice="0 times" t:fail_12=No t:famalc=No t:study_av="1 hour" t:ran_12=No t:pa_smok="Very Wrong" t:x_age="I have never used ecstasy (E, X, MDMA)" t:hiv_skl=No t:dru_talk=Yes t:oth_age="I have never used any other type of illegal drug" t:edplans="Finish college" t:force_12=No t:dairy="2 times" t:sleep="7 hours" t:pot_age="I have never tried marijuana" t:edu_nutr=Yes t:her_age="I have never used heroin" t:alc_rid=No t:died_12=Yes t:music_7=Yes t:pot_30="0 times" t:other_30=No t:cok_30=No t:edu_pres=No t:language=English t:her_30=No t:sweat="1 day" t:comp_av="3 hours" t:wor_f_dr=No t:nutr_tlk=Yes t:divor_12=No t:glu_30="0 times" t:trying="Stay the same weight" t:seatbelt=Always t:read_7=No t:fr_pot="Very Wrong" t:consider=No t:wor_h_ft=No t:grade="6th grade" t:cig_lif=No t:moved_12=No t:edu_tob=No t:doct_12=Yes t:fr_smok="Very Wrong" t:x_30=No t:cigs_get="I did not smoke cigarettes in the past 30 days" t:wor_weig=No t:pa_pot="Very Wrong" t:sweets="1 time" t:bull_elec=No t:cigs_old="I have never smoked a whole cigarette" t:beforskl="0 days" t:tv_av="2 hours" t:veggies="0 times" t:sex_talk="Somewhat helpful" t:soda="0 times" t:fr_alc="Very Wrong" t:saw_bul=Yes t:gang_12=No t:f_hur_12=No t:hiv_par=No t:wor_disc=No t:wor_gang=No t:fampot=No t:pot_harm="Moderate Risk" t:edu_dru="I'm not sure" t:drupr_12=No t:ster_lif=No t:helmet="Most of the time wore a helmet" t:race=White t:alc_get="I did not drink alcohol in the last 30 days" t:friends="1 or 2" t:alc_age="I have never had a drink of alcohol other than a few sips" t:edu_reso=No t:age="12 years old" t:stayhome="0 days" t:glu_age="I have never sniffed or huffed fumes to get high" t:gender=Female t:cig_day="I did not smoke cigarettes during the past 30 days" t:alone_av="Less than 1 hour" t:weap_out="0 days" t:fruit="0 times" t:sex_had=No t:alc_30="0 days" t:vio_12=No t:cok_age="I have never tried cocaine" t:breakfst="2 days" t:see_self="About the right weight" t:wor_heal=No t:live_us="I have always lived in the United States" t:famsmok=No t:bulli_12=No t:weap_skl="0 days" t:exer_60="4 days" t:attempt=No t:parents="My mother and my father" t:fast_12=No t:touch_12=No t:fr_oth="Very Wrong" t:adu_skl=Yes t:clubs_7=No t:oxy_30=No t:commu_7=Yes t:wor_bul=Yes t:cig_harm="Slight Risk" t:oth_harm="Slight Risk" t:diet_12=Yes t:cigs_30="0 days" t:tv_room=Yes t:wor_fail=No t:wor_y_dr=No t:wor_abus=No t:off_skl=No t:famoth=No t:alc5_30=No t:oxy_age="I have never used oxycontin without a doctor's prescription" t:school="Argenziano (LP)" t:plan=No t:ster_30=No t:transskl=Walk t:pa_oth="Very Wrong" t:wor_s_ft=No t:o_hur_12=No t:famdr_12=No m:version=501

series e:v6hb-z5zm d:2016-02-03T10:46:41.000Z t:rude_12=No t:pa_alc="Very Wrong" t:less_12=No t:fite_out=No t:hurtself=No t:volun_7=No t:alc_harm="Moderate Risk" t:bull_out=No t:fite_skl=No t:sports_7=Yes t:tob_talk="I'm not sure" t:dent_12=Yes t:juice="2 times" t:fail_12=No t:famalc=No t:study_av="2 hours" t:ran_12=No t:pa_smok="Very Wrong" t:x_age="I have never used ecstasy (E, X, MDMA)" t:hiv_skl=No t:dru_talk=No t:oth_age="I have never used any other type of illegal drug" t:edplans="Finish college" t:force_12=No t:dairy="3 times" t:sleep="9 hours" t:pot_age="I have never tried marijuana" t:edu_nutr=Yes t:her_age="I have never used heroin" t:alc_rid=No t:died_12=No t:music_7=Yes t:pot_30="0 times" t:other_30=No t:cok_30=No t:edu_pres=Yes t:language=English t:her_30=No t:sweat="4 days" t:comp_av="Less than 1 hour" t:wor_f_dr=No t:nutr_tlk=Yes t:divor_12=No t:glu_30="0 times" t:trying="Stay the same weight" t:seatbelt=Always t:fr_pot="Very Wrong" t:consider=No t:wor_h_ft=No t:grade="6th grade" t:edu_tob="I'm not sure" t:moved_12=No t:cig_lif=No t:doct_12=Yes t:fr_smok="Very Wrong" t:x_30=No t:cigs_get="I did not smoke cigarettes in the past 30 days" t:wor_weig=No t:pa_pot="Very Wrong" t:sweets="1 time" t:bull_elec=No t:cigs_old="I have never smoked a whole cigarette" t:beforskl="0 days" t:tv_av="1 hour" t:sex_talk="We didn't talk about sex during the last 12 months" t:soda="3 times" t:fr_alc="Very Wrong" t:saw_bul=No t:gang_12=No t:f_hur_12=No t:hiv_par=No t:wor_disc=No t:wor_gang=No t:fampot=No t:pot_harm="Moderate Risk" t:edu_dru="I'm not sure" t:drupr_12=No t:ster_lif=No t:helmet="Always wore a helmet" t:race=White t:alc_get="I did not drink alcohol in the last 30 days" t:friends="5 or more" t:alc_age="I have never had a drink of alcohol other than a few sips" t:edu_reso=Yes t:age="11 years old" t:stayhome="0 days" t:glu_age="I have never sniffed or huffed fumes to get high" t:gender=Male t:cig_day="I did not smoke cigarettes during the past 30 days" t:alone_av=None t:weap_out="0 days" t:sex_had=No t:alc_30="0 days" t:vio_12=No t:cok_age="I have never tried cocaine" t:breakfst="4 days" t:see_self="About the right weight" t:wor_heal=No t:live_us="I have always lived in the United States" t:famsmok=No t:bulli_12=No t:weap_skl="0 days" t:exer_60="5 days" t:attempt=No t:parents="My mother and my father" t:fast_12=No t:touch_12=No t:fr_oth="Very Wrong" t:adu_skl="I'm not sure" t:oxy_30=No t:commu_7=No t:wor_bul=No t:cig_harm="Great Risk" t:oth_harm="Moderate Risk" t:diet_12=No t:cigs_30="0 days" t:tv_room=No t:wor_fail=No t:wor_y_dr=No t:wor_abus=No t:off_skl=No t:famoth=No t:alc5_30=No t:oxy_age="I have never used oxycontin without a doctor's prescription" t:school="Argenziano (LP)" t:plan=No t:ster_30=No t:transskl="Get a ride" t:pa_oth="Very Wrong" t:wor_s_ft=No t:o_hur_12=No t:famdr_12=No m:version=502
```

## Meta Commands

```ls
metric m:version p:integer l:version t:dataTypeName=number

metric m:nothing p:long l:NOTHING t:dataTypeName=number

metric m:trystop p:long l:TRYSTOP t:dataTypeName=number

metric m:teltea p:long l:TELTEA t:dataTypeName=number

metric m:telpar p:long l:TELPAR t:dataTypeName=number

metric m:telfri p:long l:TELFRI t:dataTypeName=number

metric m:tookpart p:long l:TOOKPART t:dataTypeName=number

metric m:justsaw p:long l:JUSTSAW t:dataTypeName=number

metric m:intervene p:long l:INTERVENE t:dataTypeName=number

metric m:toldtea p:long l:TOLDTEA t:dataTypeName=number

metric m:omit p:long l:OMIT t:dataTypeName=number

metric m:count_miss p:integer l:COUNT_MISS t:dataTypeName=number

metric m:ster_lif2 p:long l:STER_LIF2 t:dataTypeName=number

metric m:her_age2 p:long l:HER_AGE2 t:dataTypeName=number

metric m:x_age2 p:long l:X_AGE2 t:dataTypeName=number

metric m:oxy_age2 p:long l:OXY_AGE2 t:dataTypeName=number

metric m:screen_missing p:integer l:SCREEN_MISSING t:dataTypeName=number

metric m:screen_lifedrug p:integer l:SCREEN_LIFEDRUG t:dataTypeName=number

metric m:screen_drugage p:integer l:SCREEN_DRUGAGE t:dataTypeName=number

metric m:screen_druglifeextreme p:integer l:SCREEN_DRUGLIFEEXTREME t:dataTypeName=number

metric m:screen_drug30extreme p:integer l:SCREEN_DRUG30EXTREME t:dataTypeName=number

metric m:screen_other p:integer l:SCREEN_OTHER t:dataTypeName=number

metric m:screen_sex p:integer l:SCREEN_SEX t:dataTypeName=number

metric m:eye_12 p:long l:eye_12 t:dataTypeName=number

metric m:couns_12 p:long l:couns_12 t:dataTypeName=number

metric m:scnur_12 p:long l:scnur_12 t:dataTypeName=number

metric m:talk_par p:long l:talk_par t:dataTypeName=number

metric m:talk_fam p:long l:talk_fam t:dataTypeName=number

metric m:talk_tea p:long l:talk_tea t:dataTypeName=number

metric m:talk_nur p:long l:talk_nur t:dataTypeName=number

metric m:talk_coa p:long l:talk_coa t:dataTypeName=number

metric m:talk_adu p:long l:talk_adu t:dataTypeName=number

metric m:talk_fre p:long l:talk_fre t:dataTypeName=number

metric m:talk_oth p:long l:talk_oth t:dataTypeName=number

metric m:wor_depr p:long l:wor_depr t:dataTypeName=number

metric m:thret_12 p:long l:thret_12 t:dataTypeName=number

metric m:cig_age p:long l:cig_age t:dataTypeName=number

metric m:cig_30 p:long l:cig_30 t:dataTypeName=number

metric m:cig_get p:long l:cig_get t:dataTypeName=number

metric m:chew_30 p:long l:chew_30 t:dataTypeName=number

metric m:alc_12 p:long l:alc_12 t:dataTypeName=number

metric m:edu_alc p:long l:edu_alc t:dataTypeName=number

metric m:dru_age p:long l:dru_age t:dataTypeName=number

metric m:pot_12 p:long l:pot_12 t:dataTypeName=number

metric m:cok_12 p:long l:cok_12 t:dataTypeName=number

metric m:oth_30 p:long l:oth_30 t:dataTypeName=number

metric m:oth_12 p:long l:oth_12 t:dataTypeName=number

metric m:glu_12 p:long l:glu_12 t:dataTypeName=number

metric m:fr_cigoc p:long l:fr_cigoc t:dataTypeName=number

metric m:fr_cigre p:long l:fr_cigre t:dataTypeName=number

metric m:fr_alcoc p:long l:fr_alcoc t:dataTypeName=number

metric m:fr_alcre p:long l:fr_alcre t:dataTypeName=number

metric m:fr_pottr p:long l:fr_pottr t:dataTypeName=number

metric m:fr_potoc p:long l:fr_potoc t:dataTypeName=number

metric m:fr_potre p:long l:fr_potre t:dataTypeName=number

metric m:pa_cigoc p:long l:pa_cigoc t:dataTypeName=number

metric m:pa_cigre p:long l:pa_cigre t:dataTypeName=number

metric m:pa_alcoc p:long l:pa_alcoc t:dataTypeName=number

metric m:pa_alcre p:long l:pa_alcre t:dataTypeName=number

metric m:pa_pottr p:long l:pa_pottr t:dataTypeName=number

metric m:pa_potoc p:long l:pa_potoc t:dataTypeName=number

metric m:pa_potre p:long l:pa_potre t:dataTypeName=number

metric m:sch_prop p:long l:sch_prop t:dataTypeName=number

metric m:fit_12 p:long l:fit_12 t:dataTypeName=number

metric m:weap_30 p:long l:weap_30 t:dataTypeName=number

metric m:exer_12 p:long l:exer_12 t:dataTypeName=number

metric m:smok_12 p:long l:smok_12 t:dataTypeName=number

metric m:pills_12 p:long l:pills_12 t:dataTypeName=number

metric m:lax_12 p:long l:lax_12 t:dataTypeName=number

metric m:few_12 p:long l:few_12 t:dataTypeName=number

metric m:vomit_12 p:long l:vomit_12 t:dataTypeName=number

metric m:fried_12 p:long l:fried_12 t:dataTypeName=number

entity e:v6hb-z5zm l:"Somerville Middle School YRBS Raw Data 2003-2015" t:attribution="City of Somerville Health & Human Services Department" t:url=https://data.somervillema.gov/api/views/v6hb-z5zm

property e:v6hb-z5zm t:meta.view v:id=v6hb-z5zm v:category="Public Health" v:attributionLink=http://www.somervillema.gov/departments/health/office-of-prevention v:averageRating=0 v:name="Somerville Middle School YRBS Raw Data 2003-2015" v:attribution="City of Somerville Health & Human Services Department"

property e:v6hb-z5zm t:meta.view.license v:name="Open Data Commons Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:v6hb-z5zm t:meta.view.owner v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:displayName="Michael Mastrobuoni"

property e:v6hb-z5zm t:meta.view.tableauthor v:id=j34k-s96t v:screenName="Michael Mastrobuoni" v:roleName=administrator v:displayName="Michael Mastrobuoni"
```

## Top Records

```ls
| year | school          | version | gender | grade     | age          | race                   | language         | live_us                                  | parents                     | edplans           | doct_12 | dent_12 | fail_12 | drupr_12 | famdr_12 | divor_12 | moved_12 | ran_12 | died_12 | gang_12 | wor_heal | wor_weig | wor_abus | wor_fail | wor_f_dr | wor_y_dr | wor_h_ft | wor_s_ft | wor_disc | wor_bul | wor_gang | adu_skl      | friends   | hurtself | consider | plan | attempt | vio_12 | f_hur_12 | o_hur_12 | fite_skl | fite_out | bulli_12 | nothing | trystop | teltea | telpar | telfri | saw_bul | tookpart | justsaw | intervene | toldtea | bull_out | bull_elec | edu_reso | stayhome | weap_skl | weap_out    | seatbelt         | helmet                         | cig_lif | cigs_old                              | cigs_30     | cig_day                                            | cigs_get                                       | edu_tob      | tob_talk     | alc_age                                                   | alc_30 | alc5_30 | alc_get                                     | alc_rid | pot_age                      | pot_30  | glu_age                                          | glu_30       | ster_lif | ster_30 | cok_age                    | cok_30 | her_age                  | her_30 | x_age                                  | x_30 | oxy_age                                                     | oxy_30 | oth_age                                          | other_30 | beforskl | edu_dru      | dru_talk | edu_pres     | off_skl      | cig_harm      | alc_harm      | pot_harm      | oth_harm      | fr_smok            | fr_alc           | fr_pot           | fr_oth           | pa_smok    | pa_alc             | pa_pot     | pa_oth     | famsmok | famalc | fampot | famoth | hiv_skl | hiv_par      | sex_talk                                           | sex_had | rude_12 | touch_12 | force_12 | edu_nutr | nutr_tlk     | exer_60    | see_self               | trying                                         | less_12 | fast_12 | diet_12 | breakfst   | juice   | fruit   | veggies | soda    | sweets  | dairy   | sweat      | transskl   | read_7 | music_7 | sports_7 | clubs_7 | volun_7 | commu_7 | tv_room | tv_av            | alone_av         | study_av         | comp_av          | sleep            | omit | sch_thre | out_thre | nosweat | past60mn | typ60mn | aft_play | aft_park | aft_yard | aft_fiel | aft_cntr | aft_path | aft_prog | enc_aft | enc_gym | enc_rec | enc_home | enc_skl | count_miss | age2_sub | cigs_old2 | alc_age2 | pot_age2 | cok_age2 | ster_lif2 | her_age2 | x_age2 | oxy_age2 | oth_age2 | screen_missing | screen_lifedrug | screen_drugage | screen_druglifeextreme | screen_drug30extreme | screen_other | screen_sex | eye_12 | couns_12 | scnur_12 | talk_par | talk_fam | talk_tea | talk_nur | talk_coa | talk_adu | talk_fre | talk_no | talk_oth | wor_depr | thret_12 | cig_age | cig_30 | cig_get | chew_30 | alc_12 | edu_alc | dru_age | pot_12 | cok_12 | oth_30 | oth_12 | glu_12 | fr_cigoc | fr_cigre | fr_alcoc | fr_alcre | fr_pottr | fr_potoc | fr_potre | pa_cigoc | pa_cigre | pa_alcoc | pa_alcre | pa_pottr | pa_potoc | pa_potre | sch_prop | fit_12 | weap_30 | exer_12 | smok_12 | pills_12 | lax_12 | few_12 | vomit_12 | fried_12 | 
| ==== | =============== | ======= | ====== | ========= | ============ | ====================== | ================ | ======================================== | =========================== | ================= | ======= | ======= | ======= | ======== | ======== | ======== | ======== | ====== | ======= | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ============ | ========= | ======== | ======== | ==== | ======= | ====== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ====== | ====== | ====== | ======= | ======== | ======= | ========= | ======= | ======== | ========= | ======== | ======== | ======== | =========== | ================ | ============================== | ======= | ===================================== | =========== | ================================================== | ============================================== | ============ | ============ | ========================================================= | ====== | ======= | =========================================== | ======= | ============================ | ======= | ================================================ | ============ | ======== | ======= | ========================== | ====== | ======================== | ====== | ====================================== | ==== | =========================================================== | ====== | ================================================ | ======== | ======== | ============ | ======== | ============ | ============ | ============= | ============= | ============= | ============= | ================== | ================ | ================ | ================ | ========== | ================== | ========== | ========== | ======= | ====== | ====== | ====== | ======= | ============ | ================================================== | ======= | ======= | ======== | ======== | ======== | ============ | ========== | ====================== | ============================================== | ======= | ======= | ======= | ========== | ======= | ======= | ======= | ======= | ======= | ======= | ========== | ========== | ====== | ======= | ======== | ======= | ======= | ======= | ======= | ================ | ================ | ================ | ================ | ================ | ==== | ======== | ======== | ======= | ======== | ======= | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======= | ======= | ======== | ======= | ========== | ======== | ========= | ======== | ======== | ======== | ========= | ======== | ====== | ======== | ======== | ============== | =============== | ============== | ====================== | ==================== | ============ | ========== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======= | ======== | ======== | ======== | ======= | ====== | ======= | ======= | ====== | ======= | ======= | ====== | ====== | ====== | ====== | ====== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ======== | ====== | ======= | ======= | ======= | ======== | ====== | ====== | ======== | ======== | 
| 2015 | Argenziano (LP) | 500     | Male   | 6th grade | 11 years old | White                  | English          | I have always lived in the United States | My father only              | Finish college    | Yes     | Yes     | No      | No       | No       | Yes      | No       | No     | Yes     | No      | No       | No       | No       | No       | No       | No       | No       | No       | No       | Yes     | No       | Yes          | 5 or more | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | No      |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 0 days      | Always           | Always wore a helmet           | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | No           | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | Yes      | No           | No           | Great Risk    | Moderate Risk | Moderate Risk | Great Risk    | Very Wrong         | Very Wrong       | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | No      | No     | No     | No     | No      | No           | Very helpful                                       | No      | No      | No       | No       | Yes      | I'm not sure | All 7 days | About the right weight | Stay the same weight                           | No      | No      | No      | All 7 days | 5 times | 5 times | 5 times | 0 times | 2 times | 5 times | All 7 days | Walk       | Yes    | No      | No       | No      | No      | No      | No      | 2 hours          | 4 or more hours  | 2 hours          | Less than 1 hour | 10 or more hours |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 501     | Female | 6th grade | 12 years old | White                  | English          | I have always lived in the United States | My mother and my father     | Finish college    | Yes     | Yes     | No      | No       | No       | No       | No       | No     | Yes     | No      | No       | No       | No       | No       | No       | No       | No       | No       | No       | Yes     | No       | Yes          | 1 or 2    | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | Yes     |          |         |           |         | Yes      | No        | No       | 0 days   | 0 days   | 0 days      | Always           | Most of the time wore a helmet | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | No           | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | Yes      | No           | No           | Slight Risk   | Slight Risk   | Moderate Risk | Slight Risk   | Very Wrong         | Very Wrong       | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | No      | No     | No     | No     | No      | No           | Somewhat helpful                                   | No      | No      | No       | No       | Yes      | Yes          | 4 days     | About the right weight | Stay the same weight                           | No      | No      | Yes     | 2 days     | 0 times | 0 times | 0 times | 0 times | 1 time  | 2 times | 1 day      | Walk       | No     | Yes     | No       | No      | No      | Yes     | Yes     | 2 hours          | Less than 1 hour | 1 hour           | 3 hours          | 7 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 502     | Male   | 6th grade | 11 years old | White                  | English          | I have always lived in the United States | My mother and my father     | Finish college    | Yes     | Yes     | No      | No       | No       | No       | No       | No     | No      | No      | No       | No       | No       | No       | No       | No       | No       | No       | No       | No      | No       | I'm not sure | 5 or more | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | No      |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 0 days      | Always           | Always wore a helmet           | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | I'm not sure | I'm not sure | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | No       | Yes          | No           | Great Risk    | Moderate Risk | Moderate Risk | Moderate Risk | Very Wrong         | Very Wrong       | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | No      | No     | No     | No     | No      | No           | We didn't talk about sex during the last 12 months | No      | No      | No       | No       | Yes      | Yes          | 5 days     | About the right weight | Stay the same weight                           | No      | No      | No      | 4 days     | 2 times |         |         | 3 times | 1 time  | 3 times | 4 days     | Get a ride |        | Yes     | Yes      |         | No      | No      | No      | 1 hour           | None             | 2 hours          | Less than 1 hour | 9 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 503     | Female | 6th grade | 11 years old | White                  | English          | I have always lived in the United States | My mother and my father     | More than college | Yes     | Yes     | No      | No       | No       | No       | No       | Yes    | No      | No      | No       | No       | No       | No       | Yes      | No       | No       | Yes      | No       | Yes     | No       | I'm not sure | None      | Yes      | Yes      | Yes  | No      | No     | No       | Yes      | No       | No       | Yes      |         |         |        |        |        | Yes     |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 2 or 3 days | Most of the time | Always wore a helmet           | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | I'm not sure | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | Yes     | I have never tried marijuana | 0 times | 8 years old or younger                           | 1 to 2 times | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | Yes      | Yes          | No           | Great Risk    | Moderate Risk | Great Risk    | Great Risk    | Very Wrong         | Wrong            | Very Wrong       | Very Wrong       | Very Wrong | A Little Bit Wrong | Very Wrong | Very Wrong | No      | Yes    | No     | No     | No      | I'm not sure | Somewhat helpful                                   | No      | Yes     | Yes      | No       | Yes      | Yes          | 4 days     | Slightly overweight    | Lose weight                                    | Yes     | Yes     | No      | 3 days     | 1 time  | 4 times | 2 times | 0 times | 1 time  | 0 times | All 7 days | Walk       | Yes    | Yes     | No       | No      | Yes     | No      | No      | 1 hour           | None             | 3 hours          | Less than 1 hour | 5 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 504     | Male   | 6th grade | 11 years old | White                  | English          | I have always lived in the United States | My mother and a step-parent | Finish college    |         |         | Yes     | No       | No       | No       | No       | No     | No      | No      |          |          | No       | No       | No       | No       |          | No       | No       | No      | No       | Yes          | 5 or more | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | Yes     |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 0 days      |                  | Always wore a helmet           | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | Yes          | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | No       | No           | No           |               |               |               |               |                    |                  |                  |                  |            |                    |            |            | Yes     | No     | No     | No     | No      | No           | We didn't talk about sex during the last 12 months | No      |         |          |          | Yes      | Yes          | All 7 days | Slightly overweight    | Lose weight                                    | No      | No      | No      | All 7 days | 5 times | 4 times | 2 times | 3 times | 4 times | 5 times | All 7 days | Get a ride | No     | Yes     | Yes      | Yes     | No      | Yes     | Yes     |                  |                  | Less than 1 hour | None             | 9 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 505     | Female | 7th grade | 13 years old | Black                  | English          | I have always lived in the United States |                             | Finish college    | No      | Yes     | Yes     | No       | No       | No       | Yes      | No     | No      | No      | Yes      | Yes      | No       | Yes      | No       | No       | No       | No       | No       | Yes     | No       | I'm not sure | 1 or 2    | Yes      | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | Yes     |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 0 days      | Most of the time | Never wore a helmet            | Yes     | 11 or 12 years old                    | 1 or 2 days | Less than 1 cigarette per day                      | I got them some other way                      | Yes          |              | 13 or 14 years old                                        | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | Yes          |          | Yes          | No           | Moderate Risk | Moderate Risk | Great Risk    | Great Risk    | A Little Bit Wrong | Very Wrong       | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | Yes     | No     | No     | No     | Yes     |              | We didn't talk about sex during the last 12 months | No      | No      | No       | No       | Yes      | Yes          | 3 days     | Slightly overweight    | Lose weight                                    | Yes     | No      | Yes     | 0 days     | 1 time  | 0 times | 1 time  | 3 times | 1 time  | 2 times | 1 day      | Walk       | No     | Yes     | Yes      | Yes     | No      | No      | No      | 3 hours          | 4 or more hours  | 2 hours          | None             | 6 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 506     | Female | 7th grade | 13 years old | Hispanic or Latino     | Spanish          | I have always lived in the United States | My mother only              | I don't know      | Yes     | Yes     | No      | No       | No       | Yes      | Yes      | No     | Yes     |         | Yes      | Yes      | No       | Yes      | No       | No       | No       | No       | No       | Yes     | No       | Yes          | 1 or 2    | No       | Yes      | Yes  | No      | No     | No       | No       | No       | No       | Yes      |         |         |        |        |        | No      |          |         |           |         | Yes      |           | Yes      | 0 days   | 0 days   | 0 days      | Most of the time | Always wore a helmet           | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | I'm not sure | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     |                                                  | No       | 0 days   | I'm not sure |          | I'm not sure |              | Great Risk    | Slight Risk   | Great Risk    | Great Risk    | Very Wrong         | Very Wrong       | Very Wrong       | Very Wrong       |            |                    |            |            |         |        |        |        |         |              |                                                    |         |         |          |          | Yes      | Yes          | 3 days     | Slightly overweight    | Lose weight                                    | Yes     | No      | Yes     | 2 days     |         |         |         |         |         |         | 3 days     |            | Yes    | Yes     | Yes      | Yes     | Yes     | Yes     | No      | Less than 1 hour | 2 hours          | 3 hours          | 2 hours          | 7 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 507     | Female | 7th grade | 13 years old | Other                  | English          | I have always lived in the United States | My mother and my father     | More than college | Yes     | No      | No      | No       | Yes      | No       | No       | No     | Yes     | No      | No       | No       | No       | No       | Yes      | No       | No       | No       | No       | No      | No       | Yes          | 5 or more | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | No      |          |         |           |         | No       | No        | Yes      | 0 days   | 0 days   | 0 days      | Most of the time | I didn't ride any of those     | Yes     | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | Yes          | Yes          | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | Yes          | Yes      | Yes          | No           | Great Risk    | Great Risk    | Great Risk    | Great Risk    | Very Wrong         | Very Wrong       | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | Yes     | No     | No     | Yes    | Yes     | I'm not sure | We didn't talk about sex during the last 12 months | No      | No      | No       | No       | Yes      | Yes          | All 7 days | About the right weight | I am not trying to do anything about my weight | No      | No      | No      | 2 days     | 0 times | 0 times | 0 times | 1 time  | 5 times | 1 time  | 4 days     | Take a bus | Yes    | Yes     | No       | Yes     | No      | Yes     | Yes     | 4 or more hours  | 4 or more hours  | 3 hours          | 4 or more hours  | 6 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 508     | Female | 7th grade | 12 years old | White                  | Another language | I have always lived in the United States | My mother and my father     | Finish college    | Yes     | Yes     | Yes     | No       | No       | No       | No       | No     | No      | No      | No       | No       | No       | Yes      | No       | No       | No       | No       | No       | No      | No       | No           | 3 or 4    | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | No      |          |         |           |         | No       | No        | No       | 0 days   | 0 days   | 0 days      | Never            | Never wore a helmet            | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days | No           | No           | I have never had a drink of alcohol other than a few sips | 0 days | No      | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | I'm not sure | No       | No           | I'm not sure | No Risk       | No Risk       | No Risk       | No Risk       | Wrong              | Wrong            | Very Wrong       | Very Wrong       | Very Wrong | Very Wrong         | Very Wrong | Very Wrong | No      | No     | No     | No     | Yes     | No           | We didn't talk about sex during the last 12 months | No      | No      | No       | No       | Yes      | Yes          | 2 days     | Slightly overweight    | Lose weight                                    | Yes     | Yes     | Yes     | 4 days     | 1 time  | 2 times | 1 time  | 0 times | 1 time  | 2 times | 1 day      | Get a ride | No     | No      | No       | No      | No      | No      | Yes     | Less than 1 hour | None             | 1 hour           | 3 hours          | 5 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
| 2015 | Argenziano (LP) | 509     | Male   | 7th grade | 13 years old | Asian/Pacific Islander | Another language | I have always lived in the United States |                             | More than college | Yes     | Yes     | Yes     | No       | No       | No       | No       | No     | No      | No      | No       | No       | No       | No       | No       | No       | No       | No       | No       | No      | No       | Yes          | 3 or 4    | No       | No       | No   | No      | No     | No       | No       | No       | No       | No       |         |         |        |        |        | No      |          |         |           |         | No       |           |          |          |          |             |                  | Never wore a helmet            | No      | I have never smoked a whole cigarette | 0 days      | I did not smoke cigarettes during the past 30 days | I did not smoke cigarettes in the past 30 days |              | No           |                                                           |        |         | I did not drink alcohol in the last 30 days | No      | I have never tried marijuana | 0 times | I have never sniffed or huffed fumes to get high | 0 times      | No       | No      | I have never tried cocaine | No     | I have never used heroin | No     | I have never used ecstasy (E, X, MDMA) | No   | I have never used oxycontin without a doctor's prescription | No     | I have never used any other type of illegal drug | No       | 0 days   | No           | No       | No           | No           | No Risk       | No Risk       | No Risk       | No Risk       | Not Wrong at All   | Not Wrong at All | Not Wrong at All | Not Wrong at All | Very Wrong | Very Wrong         | Very Wrong | Very Wrong |         |        |        |        | Yes     | Yes          | Very helpful                                       | Yes     | No      | No       | No       |          |              |            | Slightly underweight   | Gain weight                                    |         |         |         |            |         |         |         |         |         |         | All 7 days | Get a ride | No     | No      | Yes      | No      | No      | No      | No      | None             | Less than 1 hour |                  | 4 or more hours  | 8 hours          |      |          |          |         |          |         |          |          |          |          |          |          |          |         |         |         |          |         |            |          |           |          |          |          |           |          |        |          |          |                |                 |                |                        |                      |              |            |        |          |          |          |          |          |          |          |          |          |         |          |          |          |         |        |         |         |        |         |         |        |        |        |        |        |          |          |          |          |          |          |          |          |          |          |          |          |          |          |          |        |         |         |         |          |        |        |          |          | 
```