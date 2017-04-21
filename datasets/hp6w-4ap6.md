# YRBS State Tobacco Variables 2013 - v2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/yrbs-state-tobacco-variables-2013-v2) |
| Metadata | [Link](https://data.cdc.gov/api/views/hp6w-4ap6) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/hp6w-4ap6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/hp6w-4ap6/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | hp6w-4ap6 |
| Name | YRBS State Tobacco Variables 2013 - v2 |
| Attribution | Division of Adolescent and School Health |
| Tags | youth risk behavior risk surveillance school-based surveillance |
| Created | 2014-07-14T19:05:04Z |
| Publication Date | 2015-06-08T21:00:12Z |

## Description

The Youth Risk Behavior Surveillance System (YRBSS) monitors six types of health-risk behaviors that contribute to the leading causes of death and disability among youth and adults. This file contains state-level results for 13 tobacco-use variables by sex and grade for 2013.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | time           | surveyyear         | SurveyYear         | number    | number      |
| Yes      | series tag     | statecode          | StateCode          | text      | text        |
| Yes      | series tag     | statename          | StateName          | text      | text        |
| Yes      | numeric metric | evertrycigt        | EverTryCigT        | number    | number      |
| Yes      | numeric metric | evertrycigf        | EverTryCigF        | number    | number      |
| Yes      | numeric metric | evertrycigm        | EverTryCigM        | number    | number      |
| Yes      | numeric metric | evertryciggr9      | EverTryCigGr9      | number    | number      |
| Yes      | numeric metric | evertryciggr10     | EverTryCigGr10     | number    | number      |
| Yes      | numeric metric | evertryciggr11     | EverTryCigGr11     | number    | number      |
| Yes      | numeric metric | evertryciggr12     | EverTryCigGr12     | number    | number      |
| Yes      | numeric metric | cigbefore13t       | CigBefore13T       | number    | number      |
| Yes      | numeric metric | cigbefore13f       | CigBefore13F       | number    | number      |
| Yes      | numeric metric | cigbefore13m       | CigBefore13M       | number    | number      |
| Yes      | numeric metric | currentcigt        | CurrentCigT        | number    | number      |
| Yes      | numeric metric | currentcigf        | CurrentCigF        | number    | number      |
| Yes      | numeric metric | currentcigm        | CurrentCigM        | number    | number      |
| Yes      | numeric metric | currentciggr9      | CurrentCigGr9      | number    | number      |
| Yes      | numeric metric | currentciggr10     | CurrentCigGr10     | number    | number      |
| Yes      | numeric metric | currentciggr11     | CurrentCigGr11     | number    | number      |
| Yes      | numeric metric | currentciggr12     | CurrentCigGr12     | number    | number      |
| Yes      | numeric metric | frequentcigt       | FrequentCigT       | number    | number      |
| Yes      | numeric metric | frequentcigf       | FrequentCigF       | number    | number      |
| Yes      | numeric metric | frequentcigm       | FrequentCigM       | number    | number      |
| Yes      | numeric metric | tencigdayt         | TenCigDayT         | number    | number      |
| Yes      | numeric metric | tencigdayf         | TenCigDayF         | number    | number      |
| Yes      | numeric metric | tencigdaym         | TenCigDayM         | number    | number      |
| Yes      | numeric metric | nottryquitt        | NotTryQuitT        | number    | number      |
| Yes      | numeric metric | nottryquitf        | NotTryQuitF        | number    | number      |
| Yes      | numeric metric | nottryquitm        | NotTryQuitM        | number    | number      |
| Yes      | numeric metric | cigatschoolt       | CigAtSchoolT       | number    | number      |
| Yes      | numeric metric | cigatschoolf       | CigAtSchoolF       | number    | number      |
| Yes      | numeric metric | cigatschoolm       | CigAtSchoolM       | number    | number      |
| Yes      | numeric metric | buycigatstoret     | BuyCigAtStoreT     | number    | number      |
| Yes      | numeric metric | buycigatstoref     | BuyCigAtStoreF     | number    | number      |
| Yes      | numeric metric | buycigatstorem     | BuyCigAtStoreM     | number    | number      |
| Yes      | numeric metric | evercigdailyt      | EverCigDailyT      | number    | number      |
| Yes      | numeric metric | evercigdailyf      | EverCigDailyF      | number    | number      |
| Yes      | numeric metric | evercigdailym      | EverCigDailyM      | number    | number      |
| Yes      | numeric metric | cigall30dayst      | CigAll30DaysT      | number    | number      |
| Yes      | numeric metric | cigall30daysf      | CigAll30DaysF      | number    | number      |
| Yes      | numeric metric | cigall30daysm      | CigAll30DaysM      | number    | number      |
| Yes      | numeric metric | currentsmokelesst  | CurrentSmokelessT  | number    | number      |
| Yes      | numeric metric | currentsmokelessf  | CurrentSmokelessF  | number    | number      |
| Yes      | numeric metric | currentsmokelessm  | CurrentSmokelessM  | number    | number      |
| Yes      | numeric metric | currentcigart      | CurrentCigarT      | number    | number      |
| Yes      | numeric metric | currentcigarf      | CurrentCigarF      | number    | number      |
| Yes      | numeric metric | currentcigarm      | CurrentCigarM      | number    | number      |
| Yes      | numeric metric | currentanytobaccot | CurrentAnyTobaccoT | number    | number      |
| Yes      | numeric metric | currentanytobaccof | CurrentAnyTobaccoF | number    | number      |
| Yes      | numeric metric | currentanytobaccom | CurrentAnyTobaccoM | number    | number      |
```

## Time Field

```ls
Value = surveyyear
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hp6w-4ap6 d:2011-01-01T00:00:00.000Z t:statecode=AK t:statename=Alaska m:currentciggr9=9.55 m:cigall30daysf=3 m:currentsmokelesst=8.36 m:evertrycigt=44.28 m:cigbefore13f=10.23 m:cigatschoolm=3.77 m:tencigdayf=-2 m:nottryquitt=31.99 m:frequentcigt=5.15 m:cigall30daysm=4.25 m:evertryciggr10=43.97 m:evertryciggr11=44.88 m:cigatschoolt=3.86 m:nottryquitm=-2 m:cigbefore13m=11.65 m:evertrycigf=42.37 m:currentcigt=14.13 m:cigbefore13t=11.06 m:evertryciggr12=52.72 m:nottryquitf=-2 m:tencigdayt=5.66 m:currentcigm=13.53 m:evertrycigm=46.09 m:buycigatstoret=3.94 m:tencigdaym=-2 m:buycigatstorem=-2 m:evertryciggr9=36.47 m:currentanytobaccom=21.94 m:currentcigf=14.69 m:evercigdailyt=9.1 m:currentcigarf=6.06 m:evercigdailyf=9.62 m:buycigatstoref=-2 m:currentanytobaccof=17.95 m:evercigdailym=8.4 m:currentcigarm=14.21 m:currentsmokelessf=4.29 m:frequentcigm=5.35 m:currentsmokelessm=12.08 m:frequentcigf=4.89 m:currentciggr10=14.71 m:currentciggr11=15.26 m:currentanytobaccot=20 m:currentciggr12=17.84 m:cigall30dayst=3.67 m:cigatschoolf=3.93 m:currentcigart=10.28

series e:hp6w-4ap6 d:2013-01-01T00:00:00.000Z t:statecode=AK t:statename=Alaska m:currentciggr9=6.73 m:cigall30daysf=2.1 m:currentsmokelesst=9.12 m:evertrycigt=35.68 m:cigbefore13f=9.12 m:cigatschoolm=2.45 m:tencigdayf=-2 m:nottryquitt=32.85 m:frequentcigt=3.92 m:cigall30daysm=2.27 m:evertryciggr10=37.23 m:evertryciggr11=32.87 m:cigatschoolt=2.67 m:nottryquitm=-2 m:cigbefore13m=9.23 m:evertrycigf=35.37 m:currentcigt=10.56 m:cigbefore13t=9.38 m:evertryciggr12=44.2 m:nottryquitf=-2 m:tencigdayt=2.45 m:currentcigm=12.47 m:evertrycigm=35.93 m:buycigatstoret=-2 m:tencigdaym=-2 m:buycigatstorem=-2 m:evertryciggr9=29.07 m:currentanytobaccom=20.98 m:currentcigf=8.2 m:evercigdailyt=7.15 m:currentcigarf=4.56 m:evercigdailyf=6.73 m:buycigatstoref=-2 m:currentanytobaccof=12.65 m:evercigdailym=7.59 m:currentcigarm=9.23 m:currentsmokelessf=4.99 m:frequentcigm=4.2 m:currentsmokelessm=12.71 m:frequentcigf=3.66 m:currentciggr10=12.48 m:currentciggr11=9.47 m:currentanytobaccot=17.06 m:currentciggr12=13.61 m:cigall30dayst=2.18 m:cigatschoolf=2.35 m:currentcigart=7.3

series e:hp6w-4ap6 d:2011-01-01T00:00:00.000Z t:statecode=AL t:statename=Alabama m:currentciggr9=18.73 m:cigall30daysf=5.98 m:currentsmokelesst=9.77 m:evertrycigt=50.39 m:cigbefore13f=10.29 m:cigatschoolm=7.07 m:tencigdayf=7.15 m:nottryquitt=54.3 m:frequentcigt=9.47 m:cigall30daysm=9.6 m:evertryciggr10=50.14 m:evertryciggr11=49.16 m:cigatschoolt=6.12 m:nottryquitm=55.85 m:cigbefore13m=16.7 m:evertrycigf=47.65 m:currentcigt=22.87 m:cigbefore13t=13.64 m:evertryciggr12=58.28 m:nottryquitf=53.14 m:tencigdayt=9.15 m:currentcigm=26.45 m:evertrycigm=52.88 m:buycigatstoret=15.03 m:tencigdaym=10.72 m:buycigatstorem=17.84 m:evertryciggr9=44.54 m:currentanytobaccom=33.12 m:currentcigf=19.02 m:evercigdailyt=13.47 m:currentcigarf=12.09 m:evercigdailyf=11.47 m:buycigatstoref=11.77 m:currentanytobaccof=22.61 m:evercigdailym=15.47 m:currentcigarm=19.41 m:currentsmokelessf=1.85 m:frequentcigm=10.9 m:currentsmokelessm=17.48 m:frequentcigf=8.06 m:currentciggr10=24.39 m:currentciggr11=18.3 m:currentanytobaccot=28 m:currentciggr12=30.48 m:cigall30dayst=7.78 m:cigatschoolf=4.86 m:currentcigart=15.78
```

## Meta Commands

```ls
metric m:evertrycigt p:float l:EverTryCigT t:dataTypeName=number

metric m:evertrycigf p:float l:EverTryCigF t:dataTypeName=number

metric m:evertrycigm p:float l:EverTryCigM t:dataTypeName=number

metric m:evertryciggr9 p:float l:EverTryCigGr9 t:dataTypeName=number

metric m:evertryciggr10 p:float l:EverTryCigGr10 t:dataTypeName=number

metric m:evertryciggr11 p:float l:EverTryCigGr11 t:dataTypeName=number

metric m:evertryciggr12 p:float l:EverTryCigGr12 t:dataTypeName=number

metric m:cigbefore13t p:float l:CigBefore13T t:dataTypeName=number

metric m:cigbefore13f p:float l:CigBefore13F t:dataTypeName=number

metric m:cigbefore13m p:float l:CigBefore13M t:dataTypeName=number

metric m:currentcigt p:float l:CurrentCigT t:dataTypeName=number

metric m:currentcigf p:float l:CurrentCigF t:dataTypeName=number

metric m:currentcigm p:float l:CurrentCigM t:dataTypeName=number

metric m:currentciggr9 p:float l:CurrentCigGr9 t:dataTypeName=number

metric m:currentciggr10 p:float l:CurrentCigGr10 t:dataTypeName=number

metric m:currentciggr11 p:float l:CurrentCigGr11 t:dataTypeName=number

metric m:currentciggr12 p:float l:CurrentCigGr12 t:dataTypeName=number

metric m:frequentcigt p:float l:FrequentCigT t:dataTypeName=number

metric m:frequentcigf p:float l:FrequentCigF t:dataTypeName=number

metric m:frequentcigm p:float l:FrequentCigM t:dataTypeName=number

metric m:tencigdayt p:float l:TenCigDayT t:dataTypeName=number

metric m:tencigdayf p:float l:TenCigDayF t:dataTypeName=number

metric m:tencigdaym p:float l:TenCigDayM t:dataTypeName=number

metric m:nottryquitt p:float l:NotTryQuitT t:dataTypeName=number

metric m:nottryquitf p:float l:NotTryQuitF t:dataTypeName=number

metric m:nottryquitm p:float l:NotTryQuitM t:dataTypeName=number

metric m:cigatschoolt p:float l:CigAtSchoolT t:dataTypeName=number

metric m:cigatschoolf p:float l:CigAtSchoolF t:dataTypeName=number

metric m:cigatschoolm p:float l:CigAtSchoolM t:dataTypeName=number

metric m:buycigatstoret p:float l:BuyCigAtStoreT t:dataTypeName=number

metric m:buycigatstoref p:float l:BuyCigAtStoreF t:dataTypeName=number

metric m:buycigatstorem p:float l:BuyCigAtStoreM t:dataTypeName=number

metric m:evercigdailyt p:float l:EverCigDailyT t:dataTypeName=number

metric m:evercigdailyf p:float l:EverCigDailyF t:dataTypeName=number

metric m:evercigdailym p:float l:EverCigDailyM t:dataTypeName=number

metric m:cigall30dayst p:float l:CigAll30DaysT t:dataTypeName=number

metric m:cigall30daysf p:float l:CigAll30DaysF t:dataTypeName=number

metric m:cigall30daysm p:float l:CigAll30DaysM t:dataTypeName=number

metric m:currentsmokelesst p:float l:CurrentSmokelessT t:dataTypeName=number

metric m:currentsmokelessf p:float l:CurrentSmokelessF t:dataTypeName=number

metric m:currentsmokelessm p:float l:CurrentSmokelessM t:dataTypeName=number

metric m:currentcigart p:float l:CurrentCigarT t:dataTypeName=number

metric m:currentcigarf p:float l:CurrentCigarF t:dataTypeName=number

metric m:currentcigarm p:float l:CurrentCigarM t:dataTypeName=number

metric m:currentanytobaccot p:float l:CurrentAnyTobaccoT t:dataTypeName=number

metric m:currentanytobaccof p:float l:CurrentAnyTobaccoF t:dataTypeName=number

metric m:currentanytobaccom p:float l:CurrentAnyTobaccoM t:dataTypeName=number

entity e:hp6w-4ap6 l:"YRBS State Tobacco Variables  2013 - v2" t:attribution="Division of Adolescent and School Health" t:url=https://data.cdc.gov/api/views/hp6w-4ap6

property e:hp6w-4ap6 t:meta.view v:id=hp6w-4ap6 v:averageRating=0 v:name="YRBS State Tobacco Variables  2013 - v2" v:attribution="Division of Adolescent and School Health"

property e:hp6w-4ap6 t:meta.view.license v:name="Public Domain"

property e:hp6w-4ap6 t:meta.view.owner v:id=dkcy-nncv v:screenName="Steve Kinchen" v:displayName="Steve Kinchen"

property e:hp6w-4ap6 t:meta.view.tableauthor v:id=dkcy-nncv v:screenName="Steve Kinchen" v:roleName=editor v:displayName="Steve Kinchen"

property e:hp6w-4ap6 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| surveyyear | statecode | statename    | evertrycigt | evertrycigf | evertrycigm | evertryciggr9 | evertryciggr10 | evertryciggr11 | evertryciggr12 | cigbefore13t | cigbefore13f | cigbefore13m | currentcigt | currentcigf | currentcigm | currentciggr9 | currentciggr10 | currentciggr11 | currentciggr12 | frequentcigt | frequentcigf | frequentcigm | tencigdayt | tencigdayf | tencigdaym | nottryquitt | nottryquitf | nottryquitm | cigatschoolt | cigatschoolf | cigatschoolm | buycigatstoret | buycigatstoref | buycigatstorem | evercigdailyt | evercigdailyf | evercigdailym | cigall30dayst | cigall30daysf | cigall30daysm | currentsmokelesst | currentsmokelessf | currentsmokelessm | currentcigart | currentcigarf | currentcigarm | currentanytobaccot | currentanytobaccof | currentanytobaccom | 
| ========== | ========= | ============ | =========== | =========== | =========== | ============= | ============== | ============== | ============== | ============ | ============ | ============ | =========== | =========== | =========== | ============= | ============== | ============== | ============== | ============ | ============ | ============ | ========== | ========== | ========== | =========== | =========== | =========== | ============ | ============ | ============ | ============== | ============== | ============== | ============= | ============= | ============= | ============= | ============= | ============= | ================= | ================= | ================= | ============= | ============= | ============= | ================== | ================== | ================== | 
| 2011       | AK        | Alaska       | 44.28       | 42.37       | 46.09       | 36.47         | 43.97          | 44.88          | 52.72          | 11.06        | 10.23        | 11.65        | 14.13       | 14.69       | 13.53       | 9.55          | 14.71          | 15.26          | 17.84          | 5.15         | 4.89         | 5.35         | 5.66       | -2.00      | -2.00      | 31.99       | -2.00       | -2.00       | 3.86         | 3.93         | 3.77         | 3.94           | -2.00          | -2.00          | 9.10          | 9.62          | 8.40          | 3.67          | 3.00          | 4.25          | 8.36              | 4.29              | 12.08             | 10.28         | 6.06          | 14.21         | 20.00              | 17.95              | 21.94              | 
| 2013       | AK        | Alaska       | 35.68       | 35.37       | 35.93       | 29.07         | 37.23          | 32.87          | 44.20          | 9.38         | 9.12         | 9.23         | 10.56       | 8.20        | 12.47       | 6.73          | 12.48          | 9.47           | 13.61          | 3.92         | 3.66         | 4.20         | 2.45       | -2.00      | -2.00      | 32.85       | -2.00       | -2.00       | 2.67         | 2.35         | 2.45         | -2.00          | -2.00          | -2.00          | 7.15          | 6.73          | 7.59          | 2.18          | 2.10          | 2.27          | 9.12              | 4.99              | 12.71             | 7.30          | 4.56          | 9.23          | 17.06              | 12.65              | 20.98              | 
| 2011       | AL        | Alabama      | 50.39       | 47.65       | 52.88       | 44.54         | 50.14          | 49.16          | 58.28          | 13.64        | 10.29        | 16.70        | 22.87       | 19.02       | 26.45       | 18.73         | 24.39          | 18.30          | 30.48          | 9.47         | 8.06         | 10.90        | 9.15       | 7.15       | 10.72      | 54.30       | 53.14       | 55.85       | 6.12         | 4.86         | 7.07         | 15.03          | 11.77          | 17.84          | 13.47         | 11.47         | 15.47         | 7.78          | 5.98          | 9.60          | 9.77              | 1.85              | 17.48             | 15.78         | 12.09         | 19.41         | 28.00              | 22.61              | 33.12              | 
| 2013       | AL        | Alabama      | 45.59       | 42.79       | 48.18       | 40.79         | 39.06          | 45.58          | 58.40          | 11.58        | 9.42         | 13.12        | 18.01       | 14.25       | 21.50       | 13.09         | 18.24          | 17.21          | 24.98          | 6.65         | 5.39         | 7.97         | 12.00      | 8.29       | 14.46      | 49.12       | 48.36       | 49.25       | 3.56         | 1.99         | 4.89         | 10.48          | -2.00          | 14.40          | 11.84         | 8.77          | 14.81         | 4.53          | 3.57          | 5.53          | 14.66             | 5.19              | 23.09             | 16.47         | 10.78         | 21.32         | 27.79              | 18.95              | 36.50              | 
| 2011       | AR        | Arkansas     | 50.99       | 48.03       | 54.11       | 40.67         | 50.35          | 55.95          | 58.34          | 14.37        | 12.22        | 16.23        | 18.18       | 15.10       | 21.09       | 14.28         | 19.02          | 20.10          | 19.18          | 7.47         | 6.30         | 8.74         | 7.77       | -2.00      | 8.79       | 47.23       | -2.00       | 49.36       | 4.34         | 1.75         | 6.56         | 16.15          | -2.00          | 21.92          | 11.81         | 9.27          | 14.44         | 5.38          | 4.73          | 6.09          | 11.60             | 2.64              | 20.33             | 14.44         | 7.45          | 21.09         | 24.87              | 17.16              | 32.86              | 
| 2013       | AR        | Arkansas     | 52.08       | 48.83       | 55.17       | 46.85         | 52.15          | 50.21          | 59.95          | 15.56        | 12.80        | 18.02        | 19.13       | 16.09       | 22.16       | 15.39         | 18.45          | 17.75          | 25.42          | 7.61         | 6.02         | 9.03         | 11.23      | 2.47       | 17.43      | 51.17       | 51.49       | 50.56       | 4.58         | 2.11         | 7.03         | 12.22          | -2.00          | 13.73          | 12.63         | 10.52         | 14.43         | 5.86          | 4.28          | 7.47          | 14.79             | 4.54              | 24.16             | 17.12         | 10.18         | 23.42         | 26.50              | 19.16              | 34.13              | 
| 2011       | AZ        | Arizona      | 46.47       | 45.78       | 47.20       | 39.93         | 43.85          | 47.21          | 51.56          | 11.21        | 8.68         | 13.37        | 17.41       | 14.70       | 19.96       | 12.48         | 16.69          | 15.89          | 24.42          | 5.79         | 4.15         | 7.50         | 7.42       | 4.63       | 9.62       | 53.24       | 49.68       | 55.47       | 4.16         | 3.26         | 4.77         | 15.08          | 8.26           | 21.64          | -1.00         | -1.00         | -1.00         | 3.74          | 2.53          | 5.00          | 7.10              | 3.47              | 10.42             | 15.85         | 10.35         | 21.15         | 21.82              | 17.60              | 26.03              | 
| 2013       | AZ        | Arizona      | 43.88       | 39.92       | 47.85       | 37.05         | 43.51          | 44.13          | 50.65          | 8.40         | 7.15         | 9.57         | 14.07       | 11.63       | 16.37       | 9.06          | 13.64          | 15.51          | 17.40          | 4.58         | 4.25         | 4.95         | 8.26       | -2.00      | 8.87       | 50.69       | -2.00       | 49.46       | 3.15         | 3.15         | 3.18         | 8.56           | -2.00          | -2.00          | -1.00         | -1.00         | -1.00         | 3.39          | 3.10          | 3.72          | 6.64              | 3.79              | 9.05              | 11.80         | 7.70          | 15.46         | 19.47              | 14.92              | 23.73              | 
| 2011       | CO        | Colorado     | -1.00       | -1.00       | -1.00       | -1.00         | -1.00          | -1.00          | -1.00          | 8.92         | 6.36         | 11.16        | 15.68       | 13.98       | 17.00       | 11.85         | 14.12          | 13.92          | 22.22          | 5.32         | 5.22         | 5.16         | -1.00      | -1.00      | -1.00      | -1.00       | -1.00       | -1.00       | -1.00        | -1.00        | -1.00        | 11.17          | -2.00          | -2.00          | -1.00         | -1.00         | -1.00         | 3.74          | 3.60          | 3.83          | 6.98              | 1.79              | 11.15             | -1.00         | -1.00         | -1.00         | -1.00              | -1.00              | -1.00              | 
| 2011       | CT        | Connecticut  | -1.00       | -1.00       | -1.00       | -1.00         | -1.00          | -1.00          | -1.00          | -1.00        | -1.00        | -1.00        | 15.87       | 14.37       | 17.30       | 13.26         | 9.98           | 19.74          | 21.21          | 5.44         | 4.67         | 6.22         | -1.00      | -1.00      | -1.00      | -1.00       | -1.00       | -1.00       | -1.00        | -1.00        | -1.00        | -1.00          | -1.00          | -1.00          | -1.00         | -1.00         | -1.00         | 3.84          | 3.52          | 4.17          | -1.00             | -1.00             | -1.00             | -1.00         | -1.00         | -1.00         | -1.00              | -1.00              | -1.00              | 
```