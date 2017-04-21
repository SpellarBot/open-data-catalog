# 2011 SFO Customer Survey Data Set + Dictionary

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/sfo-2011-customer-survey-data-set-887b0) |
| Metadata | [Link](https://data.sfgov.org/api/views/v94x-pf9r) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/v94x-pf9r/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/v94x-pf9r/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | v94x-pf9r |
| Name | 2011 SFO Customer Survey Data Set + Dictionary |
| Attribution | San Francisco International Airport |
| Category | Transportation |
| Tags | sfo, airport, customer, survey |
| Created | 2012-01-10T23:01:25Z |
| Publication Date | 2013-02-02T00:07:49Z |

## Description

SFO conducts a yearly comprehensive survey of our guests to gauge satisfaction with our facilities, services, and amenities.  SFO compares results to previous surveys to look for areas of improvement and discover elements of the guest experience that are not satisfactory.

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| Yes      | series tag     | runid                   | RUNID                   | text      | number      |
| Yes      | numeric metric | respnum                 | RESPNUM                 | number    | number      |
| Yes      | series tag     | ccgid                   | CCGID                   | text      | number      |
| Yes      | numeric metric | on_time_staus_of_flight | On-Time Staus of Flight | number    | number      |
| Yes      | numeric metric | destmark                | DESTMARK                | number    | number      |
| Yes      | numeric metric | destgeo                 | DESTGEO                 | number    | number      |
| Yes      | numeric metric | term                    | TERM                    | number    | number      |
| Yes      | numeric metric | strata                  | STRATA                  | number    | number      |
| Yes      | series tag     | atype                   | ATYPE                   | text      | number      |
| Yes      | numeric metric | airline                 | AIRLINE                 | number    | number      |
| Yes      | series tag     | dest                    | DEST                    | text      | text        |
| Yes      | numeric metric | gate                    | GATE                    | number    | number      |
| Yes      | numeric metric | intdate                 | INTDATE                 | number    | number      |
| No       |                | q1                      | Q1                      | number    | number      |
| Yes      | numeric metric | q1a                     | Q1A                     | number    | number      |
| Yes      | series tag     | q1mil                   | Q1MIL                   | text      | text        |
| Yes      | series tag     | deptime                 | DEPTIME                 | text      | text        |
| Yes      | series tag     | passtime                | PASSTIME                | text      | text        |
| Yes      | numeric metric | passmin                 | PASSMIN                 | number    | number      |
| Yes      | numeric metric | q2_1                    | Q2_1                    | number    | number      |
| Yes      | numeric metric | q3_1                    | Q3_1                    | number    | number      |
| Yes      | numeric metric | q4a                     | Q4A                     | number    | number      |
| Yes      | numeric metric | q4b                     | Q4B                     | number    | number      |
| Yes      | numeric metric | q4c                     | Q4C                     | number    | number      |
| No       |                | q5                      | Q5                      | number    | number      |
| No       |                | q6                      | Q6                      | number    | number      |
| No       |                | q7                      | Q7                      | number    | number      |
| Yes      | numeric metric | saq                     | SAQ                     | number    | number      |
| Yes      | numeric metric | q8a                     | Q8A                     | number    | number      |
| Yes      | numeric metric | q8b                     | Q8B                     | number    | number      |
| Yes      | numeric metric | q8c                     | Q8C                     | number    | number      |
| Yes      | numeric metric | q8d                     | Q8D                     | number    | number      |
| Yes      | numeric metric | q8e                     | Q8E                     | number    | number      |
| Yes      | numeric metric | q8f                     | Q8F                     | number    | number      |
| Yes      | numeric metric | q8g                     | Q8G                     | number    | number      |
| Yes      | numeric metric | q8h                     | Q8H                     | number    | number      |
| Yes      | numeric metric | q8i                     | Q8I                     | number    | number      |
| Yes      | numeric metric | q8j                     | Q8J                     | number    | number      |
| Yes      | numeric metric | q8k                     | Q8K                     | number    | number      |
| Yes      | numeric metric | q8l                     | Q8L                     | number    | number      |
| Yes      | numeric metric | q8m                     | Q8M                     | number    | number      |
| Yes      | numeric metric | q8n                     | Q8N                     | number    | number      |
| Yes      | numeric metric | q10a                    | Q10A                    | number    | number      |
| Yes      | numeric metric | q10b                    | Q10B                    | number    | number      |
| Yes      | numeric metric | q10c                    | Q10C                    | number    | number      |
| Yes      | numeric metric | q10d                    | Q10D                    | number    | number      |
| Yes      | numeric metric | q10e                    | Q10E                    | number    | number      |
| Yes      | numeric metric | q10f                    | Q10F                    | number    | number      |
| Yes      | numeric metric | q11                     | Q11                     | number    | number      |
| Yes      | numeric metric | q12                     | Q12                     | number    | number      |
| Yes      | numeric metric | q13                     | Q13                     | number    | number      |
| Yes      | numeric metric | q13a1                   | Q13A1                   | number    | number      |
| Yes      | numeric metric | q13a2                   | Q13A2                   | number    | number      |
| Yes      | numeric metric | q13a3                   | Q13A3                   | number    | number      |
| Yes      | numeric metric | q14                     | Q14                     | number    | number      |
| Yes      | numeric metric | q15a                    | Q15A                    | number    | number      |
| Yes      | numeric metric | q15b                    | Q15B                    | number    | number      |
| Yes      | numeric metric | q16                     | Q16                     | number    | number      |
| Yes      | numeric metric | q17                     | Q17                     | number    | number      |
| Yes      | series tag     | q18state                | Q18STATE                | text      | text        |
| Yes      | series tag     | q18zip                  | Q18ZIP                  | text      | number      |
| Yes      | series tag     | q18country              | Q18COUNTRY              | text      | text        |
| Yes      | numeric metric | home                    | HOME                    | number    | number      |
| Yes      | numeric metric | q19                     | Q19                     | number    | number      |
| Yes      | numeric metric | q20                     | Q20                     | number    | number      |
| Yes      | numeric metric | q21                     | Q21                     | number    | number      |
| Yes      | numeric metric | mail                    | MAIL                    | number    | number      |
| Yes      | numeric metric | lang                    | LANG                    | number    | number      |
```

## Time Field

```ls
Value = 2011
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = q1,q5,q6,q7
```

## Data Commands

```ls
series e:v94x-pf9r d:2011-01-01T00:00:00.000Z t:q1mil=8:56 t:atype=1 t:dest="LAS VEGAS" t:passtime=01:29 t:q18state=CA t:q18zip=94115 t:deptime=10:25 t:ccgid=1 t:q18country=US t:runid=1 m:respnum=440 m:q10a=4 m:q10c=6 m:q10b=4 m:q10e=4 m:q10d=6 m:q10f=4 m:passmin=89 m:q3_1=1 m:on_time_staus_of_flight=2 m:q15b=5 m:gate=25 m:q1a=1 m:q15a=5 m:saq=1 m:intdate=2 m:strata=1 m:destgeo=1 m:q2_1=2 m:home=1 m:q4c=1 m:lang=1 m:q20=1 m:q8j=5 m:q21=3 m:q8i=4 m:q8h=6 m:q8g=6 m:q8n=4 m:q8m=6 m:q8l=5 m:q8k=6 m:airline=25 m:mail=1 m:q8a=4 m:q8b=4 m:q8c=4 m:q8d=4 m:q8e=4 m:q8f=5 m:q12=2 m:destmark=4 m:q11=5 m:q4b=1 m:q16=2 m:term=1 m:q4a=2 m:q17=1 m:q14=5 m:q19=5

series e:v94x-pf9r d:2011-01-01T00:00:00.000Z t:q1mil=8:45 t:atype=1 t:dest="LAS VEGAS" t:passtime=01:40 t:q18state=CA t:q18zip=94402 t:deptime=10:25 t:ccgid=2 t:q18country=US t:runid=1 m:respnum=441 m:q10a=5 m:q10c=5 m:q10b=6 m:q10e=5 m:q10d=6 m:q10f=5 m:passmin=100 m:q3_1=5 m:on_time_staus_of_flight=2 m:q15b=5 m:gate=25 m:q1a=1 m:q15a=4 m:saq=1 m:intdate=2 m:strata=1 m:destgeo=1 m:q2_1=3 m:home=2 m:q4c=1 m:lang=1 m:q20=1 m:q8j=3 m:q21=1 m:q8i=5 m:q8h=2 m:q8g=4 m:q8n=4 m:q8m=6 m:q8l=6 m:q8k=5 m:airline=25 m:mail=1 m:q8a=6 m:q8b=4 m:q8c=6 m:q8d=4 m:q8e=5 m:q8f=3 m:q12=2 m:destmark=4 m:q11=2 m:q4b=2 m:q16=2 m:term=1 m:q4a=2 m:q17=1 m:q14=6 m:q19=2

series e:v94x-pf9r d:2011-01-01T00:00:00.000Z t:q1mil=8:15 t:atype=1 t:dest="LAS VEGAS" t:passtime=02:10 t:q18state=ID t:q18zip=83860 t:deptime=10:25 t:ccgid=3 t:q18country=US t:runid=1 m:respnum=442 m:q10a=3 m:q10c=6 m:q10b=6 m:q10e=6 m:q10d=6 m:q10f=6 m:passmin=130 m:q3_1=2 m:on_time_staus_of_flight=2 m:q15b=5 m:gate=25 m:q1a=1 m:q15a=5 m:saq=1 m:intdate=2 m:strata=1 m:destgeo=1 m:q2_1=2 m:home=10 m:q4c=2 m:lang=1 m:q20=2 m:q8j=6 m:q21=0 m:q8i=2 m:q8h=3 m:q8g=6 m:q8n=3 m:q8m=6 m:q8l=6 m:q8k=6 m:airline=25 m:mail=1 m:q8a=6 m:q8b=6 m:q8c=3 m:q8d=4 m:q8e=3 m:q8f=6 m:q12=2 m:destmark=4 m:q11=4 m:q4b=2 m:q16=2 m:term=1 m:q4a=3 m:q17=3 m:q14=7 m:q19=7
```

## Meta Commands

```ls
metric m:respnum p:integer l:RESPNUM t:dataTypeName=number

metric m:on_time_staus_of_flight p:integer l:"On-Time Staus of Flight" t:dataTypeName=number

metric m:destmark p:integer l:DESTMARK t:dataTypeName=number

metric m:destgeo p:integer l:DESTGEO t:dataTypeName=number

metric m:term p:integer l:TERM t:dataTypeName=number

metric m:strata p:integer l:STRATA t:dataTypeName=number

metric m:airline p:integer l:AIRLINE t:dataTypeName=number

metric m:gate p:integer l:GATE t:dataTypeName=number

metric m:intdate p:integer l:INTDATE t:dataTypeName=number

metric m:q1a p:integer l:Q1A t:dataTypeName=number

metric m:passmin p:integer l:PASSMIN t:dataTypeName=number

metric m:q2_1 p:integer l:Q2_1 t:dataTypeName=number

metric m:q3_1 p:integer l:Q3_1 t:dataTypeName=number

metric m:q4a p:integer l:Q4A t:dataTypeName=number

metric m:q4b p:integer l:Q4B t:dataTypeName=number

metric m:q4c p:integer l:Q4C t:dataTypeName=number

metric m:saq p:integer l:SAQ t:dataTypeName=number

metric m:q8a p:integer l:Q8A t:dataTypeName=number

metric m:q8b p:integer l:Q8B t:dataTypeName=number

metric m:q8c p:integer l:Q8C t:dataTypeName=number

metric m:q8d p:integer l:Q8D t:dataTypeName=number

metric m:q8e p:integer l:Q8E t:dataTypeName=number

metric m:q8f p:integer l:Q8F t:dataTypeName=number

metric m:q8g p:integer l:Q8G t:dataTypeName=number

metric m:q8h p:integer l:Q8H t:dataTypeName=number

metric m:q8i p:integer l:Q8I t:dataTypeName=number

metric m:q8j p:integer l:Q8J t:dataTypeName=number

metric m:q8k p:integer l:Q8K t:dataTypeName=number

metric m:q8l p:integer l:Q8L t:dataTypeName=number

metric m:q8m p:integer l:Q8M t:dataTypeName=number

metric m:q8n p:integer l:Q8N t:dataTypeName=number

metric m:q10a p:integer l:Q10A t:dataTypeName=number

metric m:q10b p:integer l:Q10B t:dataTypeName=number

metric m:q10c p:integer l:Q10C t:dataTypeName=number

metric m:q10d p:integer l:Q10D t:dataTypeName=number

metric m:q10e p:integer l:Q10E t:dataTypeName=number

metric m:q10f p:integer l:Q10F t:dataTypeName=number

metric m:q11 p:integer l:Q11 t:dataTypeName=number

metric m:q12 p:integer l:Q12 t:dataTypeName=number

metric m:q13 p:integer l:Q13 t:dataTypeName=number

metric m:q13a1 p:integer l:Q13A1 t:dataTypeName=number

metric m:q13a2 p:integer l:Q13A2 t:dataTypeName=number

metric m:q13a3 p:integer l:Q13A3 t:dataTypeName=number

metric m:q14 p:integer l:Q14 t:dataTypeName=number

metric m:q15a p:integer l:Q15A t:dataTypeName=number

metric m:q15b p:integer l:Q15B t:dataTypeName=number

metric m:q16 p:integer l:Q16 t:dataTypeName=number

metric m:q17 p:integer l:Q17 t:dataTypeName=number

metric m:home p:integer l:HOME t:dataTypeName=number

metric m:q19 p:integer l:Q19 t:dataTypeName=number

metric m:q20 p:integer l:Q20 t:dataTypeName=number

metric m:q21 p:integer l:Q21 t:dataTypeName=number

metric m:mail p:integer l:MAIL t:dataTypeName=number

metric m:lang p:integer l:LANG t:dataTypeName=number

entity e:v94x-pf9r l:"2011 SFO Customer Survey Data Set + Dictionary" t:attribution="San Francisco International Airport" t:url=https://data.sfgov.org/api/views/v94x-pf9r

property e:v94x-pf9r t:meta.view v:id=v94x-pf9r v:category=Transportation v:attributionLink=http://www.flysfo.com v:averageRating=0 v:name="2011 SFO Customer Survey Data Set + Dictionary" v:attribution="San Francisco International Airport"

property e:v94x-pf9r t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:v94x-pf9r t:meta.view.owner v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:displayName=Chris

property e:v94x-pf9r t:meta.view.tableauthor v:id=mf3h-st4n v:profileImageUrlMedium=/api/users/mf3h-st4n/profile_images/THUMB v:profileImageUrlLarge=/api/users/mf3h-st4n/profile_images/LARGE v:screenName=Chris v:profileImageUrlSmall=/api/users/mf3h-st4n/profile_images/TINY v:roleName=editor v:displayName=Chris
```

## Top Records

```ls
| runid | respnum | ccgid | on_time_staus_of_flight | destmark | destgeo | term | strata | atype | airline | dest      | gate | intdate | q1    | q1a | q1mil | deptime | passtime | passmin | q2_1 | q3_1 | q4a | q4b | q4c | q5 | q6 | q7 | saq | q8a | q8b | q8c | q8d | q8e | q8f | q8g | q8h | q8i | q8j | q8k | q8l | q8m | q8n | q10a | q10b | q10c | q10d | q10e | q10f | q11 | q12 | q13 | q13a1 | q13a2 | q13a3 | q14 | q15a | q15b | q16 | q17 | q18state | q18zip | q18country | home | q19 | q20 | q21 | mail | lang | 
| ===== | ======= | ===== | ======================= | ======== | ======= | ==== | ====== | ===== | ======= | ========= | ==== | ======= | ===== | === | ===== | ======= | ======== | ======= | ==== | ==== | === | === | === | == | == | == | === | === | === | === | === | === | === | === | === | === | === | === | === | === | === | ==== | ==== | ==== | ==== | ==== | ==== | === | === | === | ===== | ===== | ===== | === | ==== | ==== | === | === | ======== | ====== | ========== | ==== | === | === | === | ==== | ==== | 
| 1     | 440     | 1     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 85600 | 1   | 8:56  | 10:25   | 01:29    | 89      | 2    | 1    | 2   | 1   | 1   | 2  | 2  | 2  | 1   | 4   | 4   | 4   | 4   | 4   | 5   | 6   | 6   | 4   | 5   | 6   | 5   | 6   | 4   | 4    | 4    | 6    | 6    | 4    | 4    | 5   | 2   |     |       |       |       | 5   | 5    | 5    | 2   | 1   | CA       | 94115  | US         | 1    | 5   | 1   | 3   | 1    | 1    | 
| 1     | 441     | 2     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 84500 | 1   | 8:45  | 10:25   | 01:40    | 100     | 3    | 5    | 2   | 2   | 1   | 2  | 2  | 1  | 1   | 6   | 4   | 6   | 4   | 5   | 3   | 4   | 2   | 5   | 3   | 5   | 6   | 6   | 4   | 5    | 6    | 5    | 6    | 5    | 5    | 2   | 2   |     |       |       |       | 6   | 4    | 5    | 2   | 1   | CA       | 94402  | US         | 2    | 2   | 1   | 1   | 1    | 1    | 
| 1     | 442     | 3     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 81500 | 1   | 8:15  | 10:25   | 02:10    | 130     | 2    | 2    | 3   | 2   | 2   | 1  | 1  | 1  | 1   | 6   | 6   | 3   | 4   | 3   | 6   | 6   | 3   | 2   | 6   | 6   | 6   | 6   | 3   | 3    | 6    | 6    | 6    | 6    | 6    | 4   | 2   |     |       |       |       | 7   | 5    | 5    | 2   | 3   | ID       | 83860  | US         | 10   | 7   | 2   | 0   | 1    | 1    | 
| 1     | 443     | 4     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 80000 | 1   | 8:00  | 10:25   | 02:25    | 145     | 1    | 4    | 1   | 2   | 1   | 2  | 2  | 1  | 1   | 5   | 4   | 4   | 4   | 6   | 6   | 6   | 6   | 5   | 6   | 6   | 6   | 6   | 5   | 5    | 5    | 6    | 6    | 5    | 6    | 5   | 2   |     |       |       |       | 5   | 5    | 4    | 2   | 3   | WA       | 98520  | US         | 10   | 2   | 2   | 1   | 1    | 1    | 
| 1     | 444     | 5     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 83000 | 1   | 8:30  | 10:25   | 01:55    | 115     | 2    | 2    | 1   | 1   | 1   | 2  | 2  | 3  | 2   | 5   | 3   | 3   | 4   | 4   | 4   | 6   | 6   | 4   | 4   | 4   | 4   | 4   | 4   | 5    | 6    | 4    | 4    | 4    | 4    | 5   | 1   | 4   |       |       |       | 6   | 5    | 5    | 2   | 1   | CA       | 94062  | US         | 2    | 5   | 2   | 0   | 1    | 1    | 
| 1     | 445     | 6     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 92000 | 1   | 9:20  | 10:25   | 01:05    | 65      | 3    | 2    | 1   | 2   | 2   | 2  | 2  | 2  | 2   | 3   | 4   | 4   | 4   | 3   | 4   | 4   | 4   | 3   | 3   | 2   | 6   | 2   | 3   | 2    | 6    | 3    | 0    | 3    | 3    | 4   | 2   |     |       |       |       | 6   | 4    | 1    | 1   | 3   | TX       | 77098  | US         | 11   | 6   | 2   | 3   | 1    | 1    | 
| 1     | 446     | 7     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 90000 | 1   | 9:00  | 10:25   | 01:25    | 85      | 3    | 6    | 1   | 2   | 1   | 2  | 2  | 2  | 2   | 3   | 3   | 4   | 5   | 0   | 5   | 4   | 4   | 0   | 0   | 6   | 6   | 6   | 4   | 4    | 6    | 6    | 6    | 4    | 5    | 5   | 2   |     |       |       |       | 5   | 5    | 5    | 2   | 3   |          |        | AUSTRALIA  | 19   | 4   | 1   | 2   | 1    | 1    | 
| 1     | 447     | 8     | 2                       | 4        | 1       | 1    | 1      | 1     | 25      | LAS VEGAS | 25   | 2       | 92500 | 1   | 9:25  | 10:25   | 01:00    | 60      | 3    | 2    | 1   | 0   | 0   | 2  | 2  | 2  | 2   | 6   | 6   | 5   | 5   | 5   | 6   | 6   | 6   | 5   | 6   | 6   | 6   | 6   | 5   | 5    | 6    | 6    | 6    | 6    | 5    | 5   | 2   |     |       |       |       | 5   | 5    | 5    | 2   | 1   | CA       | 94134  | US         | 1    | 5   | 1   | 2   | 1    | 1    | 
| 2     | 646     | 9     | 3                       | 4        | 1       | 1    | 2      | 1     | 25      | PHOENIX   | 23   | 2       | 90000 | 1   | 9:00  | 11:25   | 02:25    | 145     | 2    | 6    | 1   | 2   | 2   | 2  | 2  | 1  | 1   | 6   | 5   | 5   | 5   | 6   | 5   | 6   | 5   | 6   | 6   | 6   | 6   | 6   | 5   | 5    | 6    | 6    | 6    | 6    | 6    | 5   | 2   |     |       |       |       | 5   | 5    | 5    | 2   | 3   | AR       | 72022  | US         | 11   | 5   | 2   | 2   | 1    | 1    | 
| 2     | 647     | 10    | 3                       | 4        | 1       | 1    | 2      | 1     | 25      | PHOENIX   | 23   | 2       | 70000 | 1   | 7:00  | 11:25   | 04:25    | 265     | 3    | 3    | 1   | 1   | 1   | 2  | 2  | 2  | 1   | 4   | 3   | 3   | 5   | 5   | 5   | 6   | 5   | 6   | 6   | 6   | 6   | 6   | 4   | 3    | 6    | 5    | 6    | 3    | 3    | 5   | 1   | 5   | 4     | 8     |       | 11  | 5    | 5    | 2   | 4   | PA       | 15232  | US         | 12   | 2   | 2   | 1   | 1    | 1    | 
```