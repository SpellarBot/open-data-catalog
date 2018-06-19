# Statistical Summary Period Attendance Reporting (PAR)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/statistical-summary-period-attendance-reporting-par) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/hrsu-3w2q) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/hrsu-3w2q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/hrsu-3w2q/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | hrsu-3w2q |
| Name | Statistical Summary Period Attendance Reporting (PAR) |
| Attribution | Department of Education (DOE) |
| Category | Education |
| Tags | school, attendance, education, doe, enrollment |
| Created | 2015-09-28T14:53:50Z |
| Publication Date | 2016-03-08T21:14:14Z |

## Description

Statistical report on attendance by borough, grade. Alternate views of same data by grade level and enrollment (register). All students including YABC, adults, LYFE babies and charters, home instruction, home/hospital, CBO UPK.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at           | meta_data | meta_data   |
| Yes      | series tag     | boro                 | BORO                 | text      | text        |
| Yes      | series tag     | year                 | YEAR                 | text      | text        |
| Yes      | numeric metric | period               | PERIOD               | number    | number      |
| Yes      | series tag     | district             | DISTRICT             | text      | number      |
| Yes      | numeric metric | level                | LEVEL                | number    | number      |
| Yes      | numeric metric | school               | SCHOOL               | number    | number      |
| Yes      | series tag     | grade_code           | GRADE_CODE           | text      | number      |
| Yes      | numeric metric | instruction_days     | INSTRUCTION_DAYS     | number    | number      |
| Yes      | numeric metric | religious_holydays   | RELIGIOUS_HOLYDAYS   | number    | number      |
| Yes      | numeric metric | classes              | CLASSES              | number    | number      |
| Yes      | numeric metric | register_last_report | REGISTER_LAST_REPORT | number    | number      |
| Yes      | numeric metric | admissions           | ADMISSIONS           | number    | number      |
| Yes      | numeric metric | transfers_in         | TRANSFERS_IN         | number    | number      |
| Yes      | numeric metric | discharges           | DISCHARGES           | number    | number      |
| Yes      | numeric metric | transfers_out        | TRANSFERS_OUT        | number    | number      |
| Yes      | numeric metric | present_register     | PRESENT_REGISTER     | number    | number      |
| Yes      | numeric metric | aggregate_register   | AGGREGATE_REGISTER   | number    | number      |
| Yes      | numeric metric | aggregate_attendance | AGGREGATE_ATTENDANCE | number    | number      |
| Yes      | numeric metric | lta                  | LTA                  | number    | number      |
| Yes      | numeric metric | ltb                  | LTB                  | number    | number      |
| Yes      | numeric metric | holyday_counter      | HOLYDAY_COUNTER      | number    | number      |
| Yes      | numeric metric | register_01          | REGISTER_01          | number    | number      |
| Yes      | numeric metric | attendance_01        | ATTENDANCE_01        | number    | number      |
| Yes      | numeric metric | register_02          | REGISTER_02          | number    | number      |
| Yes      | numeric metric | attendance_02        | ATTENDANCE_02        | number    | number      |
| Yes      | numeric metric | register_03          | REGISTER_03          | number    | number      |
| Yes      | numeric metric | attendance_03        | ATTENDANCE_03        | number    | number      |
| Yes      | numeric metric | register_04          | REGISTER_04          | number    | number      |
| Yes      | numeric metric | attendance_04        | ATTENDANCE_04        | number    | number      |
| Yes      | numeric metric | register_05          | REGISTER_05          | number    | number      |
| Yes      | numeric metric | attendance_05        | ATTENDANCE_05        | number    | number      |
| Yes      | numeric metric | register_06          | REGISTER_06          | number    | number      |
| Yes      | numeric metric | attendance_06        | ATTENDANCE_06        | number    | number      |
| Yes      | numeric metric | register_07          | REGISTER_07          | number    | number      |
| Yes      | numeric metric | attendance_07        | ATTENDANCE_07        | number    | number      |
| Yes      | numeric metric | register_08          | REGISTER_08          | number    | number      |
| Yes      | numeric metric | attendance_08        | ATTENDANCE_08        | number    | number      |
| Yes      | numeric metric | register_09          | REGISTER_09          | number    | number      |
| Yes      | numeric metric | attendance_09        | ATTENDANCE_09        | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:hrsu-3w2q d:2016-03-08T13:09:36.000Z t:boro=M t:grade_code=0 t:year=2015-2016 t:district=1 m:register_last_report=152 m:register_09=0 m:transfers_in=46 m:register_08=0 m:religious_holydays=4 m:register_07=0 m:register_06=0 m:register_05=0 m:register_04=175 m:attendance_04=171 m:attendance_05=0 m:attendance_02=157 m:level=110 m:attendance_03=171 m:instruction_days=12 m:attendance_08=0 m:attendance_09=0 m:attendance_06=0 m:attendance_07=0 m:aggregate_attendance=1956 m:attendance_01=160 m:discharges=28 m:classes=130 m:transfers_out=45 m:admissions=50 m:period=1 m:holyday_counter=4 m:register_01=172 m:present_register=175 m:register_02=175 m:school=15 m:register_03=175 m:aggregate_register=2084

series e:hrsu-3w2q d:2016-03-08T13:09:36.000Z t:boro=M t:grade_code=0 t:year=2015-2016 t:district=1 m:register_last_report=231 m:register_09=0 m:register_08=0 m:religious_holydays=4 m:register_07=0 m:register_06=0 m:register_05=0 m:register_04=266 m:attendance_04=253 m:attendance_05=0 m:attendance_02=228 m:level=110 m:attendance_03=257 m:instruction_days=12 m:attendance_08=0 m:attendance_09=0 m:attendance_06=0 m:attendance_07=0 m:aggregate_attendance=2988 m:attendance_01=256 m:discharges=20 m:classes=220 m:transfers_out=11 m:admissions=55 m:period=1 m:holyday_counter=4 m:register_01=263 m:present_register=266 m:register_02=263 m:school=19 m:register_03=266 m:aggregate_register=3157

series e:hrsu-3w2q d:2016-03-08T13:09:36.000Z t:boro=M t:grade_code=0 t:year=2015-2016 t:district=1 m:register_last_report=573 m:register_09=0 m:register_08=0 m:religious_holydays=4 m:register_07=0 m:register_06=0 m:register_05=0 m:register_04=590 m:attendance_04=561 m:attendance_05=0 m:attendance_02=540 m:level=110 m:attendance_03=564 m:instruction_days=12 m:attendance_08=0 m:attendance_09=0 m:attendance_06=0 m:attendance_07=0 m:aggregate_attendance=6771 m:attendance_01=572 m:discharges=64 m:classes=280 m:admissions=82 m:period=1 m:holyday_counter=4 m:register_01=595 m:present_register=591 m:register_02=589 m:school=20 m:register_03=590 m:aggregate_register=7119
```

## Meta Commands

```ls
metric m:period p:integer l:PERIOD t:dataTypeName=number

metric m:level p:integer l:LEVEL t:dataTypeName=number

metric m:school p:integer l:SCHOOL t:dataTypeName=number

metric m:instruction_days p:integer l:INSTRUCTION_DAYS t:dataTypeName=number

metric m:religious_holydays p:integer l:RELIGIOUS_HOLYDAYS t:dataTypeName=number

metric m:classes p:integer l:CLASSES t:dataTypeName=number

metric m:register_last_report p:integer l:REGISTER_LAST_REPORT t:dataTypeName=number

metric m:admissions p:integer l:ADMISSIONS t:dataTypeName=number

metric m:transfers_in p:integer l:TRANSFERS_IN t:dataTypeName=number

metric m:discharges p:integer l:DISCHARGES t:dataTypeName=number

metric m:transfers_out p:integer l:TRANSFERS_OUT t:dataTypeName=number

metric m:present_register p:integer l:PRESENT_REGISTER t:dataTypeName=number

metric m:aggregate_register p:integer l:AGGREGATE_REGISTER t:dataTypeName=number

metric m:aggregate_attendance p:integer l:AGGREGATE_ATTENDANCE t:dataTypeName=number

metric m:lta p:integer l:LTA t:dataTypeName=number

metric m:ltb p:integer l:LTB t:dataTypeName=number

metric m:holyday_counter p:integer l:HOLYDAY_COUNTER t:dataTypeName=number

metric m:register_01 p:integer l:REGISTER_01 t:dataTypeName=number

metric m:attendance_01 p:integer l:ATTENDANCE_01 t:dataTypeName=number

metric m:register_02 p:integer l:REGISTER_02 t:dataTypeName=number

metric m:attendance_02 p:integer l:ATTENDANCE_02 t:dataTypeName=number

metric m:register_03 p:integer l:REGISTER_03 t:dataTypeName=number

metric m:attendance_03 p:integer l:ATTENDANCE_03 t:dataTypeName=number

metric m:register_04 p:integer l:REGISTER_04 t:dataTypeName=number

metric m:attendance_04 p:integer l:ATTENDANCE_04 t:dataTypeName=number

metric m:register_05 p:integer l:REGISTER_05 t:dataTypeName=number

metric m:attendance_05 p:integer l:ATTENDANCE_05 t:dataTypeName=number

metric m:register_06 p:integer l:REGISTER_06 t:dataTypeName=number

metric m:attendance_06 p:integer l:ATTENDANCE_06 t:dataTypeName=number

metric m:register_07 p:integer l:REGISTER_07 t:dataTypeName=number

metric m:attendance_07 p:integer l:ATTENDANCE_07 t:dataTypeName=number

metric m:register_08 p:integer l:REGISTER_08 t:dataTypeName=number

metric m:attendance_08 p:integer l:ATTENDANCE_08 t:dataTypeName=number

metric m:register_09 p:integer l:REGISTER_09 t:dataTypeName=number

metric m:attendance_09 p:integer l:ATTENDANCE_09 t:dataTypeName=number

entity e:hrsu-3w2q l:"Statistical Summary Period Attendance Reporting (PAR)" t:attribution="Department of Education (DOE)" t:url=https://data.cityofnewyork.us/api/views/hrsu-3w2q

property e:hrsu-3w2q t:meta.view v:id=hrsu-3w2q v:category=Education v:averageRating=0 v:name="Statistical Summary Period Attendance Reporting (PAR)" v:attribution="Department of Education (DOE)"

property e:hrsu-3w2q t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:hrsu-3w2q t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | boro | year      | period | district | level | school | grade_code | instruction_days | religious_holydays | classes | register_last_report | admissions | transfers_in | discharges | transfers_out | present_register | aggregate_register | aggregate_attendance | lta | ltb | holyday_counter | register_01 | attendance_01 | register_02 | attendance_02 | register_03 | attendance_03 | register_04 | attendance_04 | register_05 | attendance_05 | register_06 | attendance_06 | register_07 | attendance_07 | register_08 | attendance_08 | register_09 | attendance_09 | 
| =========== | ==== | ========= | ====== | ======== | ===== | ====== | ========== | ================ | ================== | ======= | ==================== | ========== | ============ | ========== | ============= | ================ | ================== | ==================== | === | === | =============== | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | =========== | ============= | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 15     | 0          | 12               | 4                  | 130     | 152                  | 50         | 46           | 28         | 45            | 175              | 2084               | 1956                 |     |     | 4               | 172         | 160           | 175         | 157           | 175         | 171           | 175         | 171           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 19     | 0          | 12               | 4                  | 220     | 231                  | 55         |              | 20         | 11            | 266              | 3157               | 2988                 |     |     | 4               | 263         | 256           | 263         | 228           | 266         | 257           | 266         | 253           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 20     | 0          | 12               | 4                  | 280     | 573                  | 82         |              | 64         |               | 591              | 7119               | 6771                 |     |     | 4               | 595         | 572           | 589         | 540           | 590         | 564           | 590         | 561           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 34     | 0          | 12               | 4                  | 200     | 358                  | 49         |              | 23         |               | 384              | 4602               | 4349                 |     |     | 4               | 384         | 365           | 383         | 334           | 384         | 364           | 384         | 370           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 63     | 0          | 12               | 4                  | 110     | 183                  | 43         |              | 23         |               | 203              | 2411               | 2327                 |     |     | 4               | 201         | 197           | 202         | 185           | 202         | 197           | 203         | 199           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 64     | 0          | 12               | 4                  | 150     | 249                  | 32         |              | 22         |               | 259              | 3097               | 2923                 |     |     | 4               | 257         | 240           | 259         | 238           | 259         | 250           | 259         | 249           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 110    | 0          | 12               | 4                  | 190     | 366                  | 57         |              | 26         |               | 397              | 4738               | 4598                 |     |     | 4               | 396         | 384           | 397         | 375           | 397         | 387           | 397         | 387           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 134    | 0          | 12               | 4                  | 150     | 205                  | 73         |              | 15         |               | 263              | 3129               | 2941                 |     |     | 4               | 263         | 249           | 262         | 241           | 261         | 247           | 263         | 252           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 137    | 0          | 12               | 4                  | 100     | 155                  | 30         |              | 32         |               | 153              | 1829               | 1714                 |     |     | 4               | 153         | 144           | 152         | 138           | 154         | 149           | 154         | 144           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
| 1457442576  | M    | 2015-2016 | 1      | 1        | 110   | 140    | 0          | 12               | 4                  | 200     | 348                  | 51         | 12           | 23         | 12            | 376              | 4460               | 4258                 |     |     | 4               | 371         | 354           | 375         | 358           | 376         | 357           | 376         | 358           | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 0           | 0             | 
```