# 2015 Street Tree Census - Blockface Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2015-street-tree-census-blockface-data-16559) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ju3b-rwpy) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ju3b-rwpy/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ju3b-rwpy/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ju3b-rwpy |
| Name | 2015 Street Tree Census - Blockface Data |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Environment |
| Tags | parks, trees, treescount, census, dpr |
| Created | 2016-06-03T12:02:27Z |
| Publication Date | 2017-01-27T14:59:58Z |

## Description

Blockface data from the TreesCount! 2015 Street Tree Census, conducted by volunteers and staff organized by NYC Parks & Recreation and partner organizations. Blockface data includes tree counts and data collection status by block. Accompanying street tree data is available, indicating tree-level details such as tree species, size and other characteristics.

## Columns

```ls
| Included | Schema Type    | Field Name | Name       | Data Type     | Render Type   |
| ======== | ============== | ========== | ========== | ============= | ============= |
| Yes      | series tag     | block_id   | block_id   | text          | number        |
| Yes      | series tag     | block_stat | block_stat | text          | text          |
| Yes      | numeric metric | trees      | trees      | number        | number        |
| Yes      | time           | surv_date  | surv_date  | calendar_date | calendar_date |
| Yes      | series tag     | group_name | group_name | text          | text          |
| Yes      | series tag     | cb_num     | cb_num     | text          | number        |
| Yes      | series tag     | borocode   | borocode   | text          | number        |
| Yes      | series tag     | boroname   | boroname   | text          | text          |
| Yes      | numeric metric | cncldist   | cncldist   | number        | number        |
| Yes      | numeric metric | st_assem   | st_assem   | number        | number        |
| Yes      | numeric metric | st_senate  | st_senate  | number        | number        |
| Yes      | series tag     | nta        | nta        | text          | text          |
| Yes      | series tag     | nta_name   | nta_name   | text          | text          |
| Yes      | numeric metric | boro_ct    | boro_ct    | number        | number        |
| Yes      | series tag     | zipcode    | zipcode    | text          | text          |
| Yes      | series tag     | zip_city   | zip_city   | text          | text          |
| Yes      | series tag     | state      | state      | text          | text          |
| Yes      | numeric metric | start_x_sp | start_x_sp | number        | number        |
| Yes      | numeric metric | start_y_sp | start_y_sp | number        | number        |
| Yes      | numeric metric | mid_x_sp   | mid_x_sp   | number        | number        |
| Yes      | numeric metric | mid_y_sp   | mid_y_sp   | number        | number        |
| Yes      | numeric metric | end_x_sp   | end_x_sp   | number        | number        |
| Yes      | numeric metric | end_y_sp   | end_y_sp   | number        | number        |
| No       |                | start_lat  | start_lat  | number        | number        |
| No       |                | start_long | start_long | number        | number        |
| No       |                | mid_lat    | mid_lat    | number        | number        |
| No       |                | mid_long   | mid_long   | number        | number        |
| No       |                | end_lat    | end_lat    | number        | number        |
| No       |                | end_long   | end_long   | number        | number        |
| Yes      | numeric metric | shape_leng | SHAPE_Leng | number        | number        |
```

## Time Field

```ls
Value = surv_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = start_lat,start_long,mid_lat,mid_long,end_lat,end_long
```

## Data Commands

```ls
series e:ju3b-rwpy d:2015-10-05T00:00:00.000Z t:group_name="Not in a group territory" t:borocode=1 t:nta_name="Battery Park City-Lower Manhattan" t:nta=MN25 t:boroname=Manhattan t:block_stat=Complete t:zipcode=10280 t:cb_num=101 t:zip_city="New York" t:state="New York" t:block_id=100185 m:boro_ct=1031704 m:end_x_sp=979513.968122 m:shape_leng=222.358941595 m:start_y_sp=196800.2262 m:cncldist=1 m:trees=4 m:end_y_sp=196994.403633 m:mid_y_sp=196897.314917 m:st_senate=26 m:mid_x_sp=979459.795658 m:st_assem=65 m:start_x_sp=979405.623194

series e:ju3b-rwpy d:2015-06-20T00:00:00.000Z t:group_name="NYC Parks" t:borocode=1 t:nta_name="SoHo-TriBeCa-Civic Center-Little Italy" t:nta=MN24 t:boroname=Manhattan t:block_stat=Complete t:zipcode=10013 t:cb_num=101 t:zip_city="New York" t:state="New York" t:block_id=100685 m:boro_ct=1003300 m:end_x_sp=982810.363432 m:shape_leng=338.017770787 m:start_y_sp=200779.438058 m:cncldist=1 m:trees=0 m:end_y_sp=200954.943284 m:mid_y_sp=200867.190671 m:st_senate=26 m:mid_x_sp=982954.8054 m:st_assem=66 m:start_x_sp=983099.247368

series e:ju3b-rwpy d:2015-07-23T00:00:00.000Z t:group_name="Not in a group territory" t:borocode=1 t:nta_name="SoHo-TriBeCa-Civic Center-Little Italy" t:nta=MN24 t:boroname=Manhattan t:block_stat=Complete t:zipcode=10013 t:cb_num=101 t:zip_city="New York" t:state="New York" t:block_id=100778 m:boro_ct=1003300 m:end_x_sp=982720.505344 m:shape_leng=244.25646862 m:start_y_sp=201951.065964 m:cncldist=1 m:trees=0 m:end_y_sp=201720.964062 m:mid_y_sp=201829.090109 m:st_senate=26 m:mid_x_sp=982772.527703 m:st_assem=66 m:start_x_sp=982766.428808
```

## Meta Commands

```ls
metric m:trees p:integer l:trees t:dataTypeName=number

metric m:cncldist p:integer l:cncldist t:dataTypeName=number

metric m:st_assem p:integer l:st_assem t:dataTypeName=number

metric m:st_senate p:integer l:st_senate t:dataTypeName=number

metric m:boro_ct p:integer l:boro_ct t:dataTypeName=number

metric m:start_x_sp p:double l:start_x_sp t:dataTypeName=number

metric m:start_y_sp p:double l:start_y_sp t:dataTypeName=number

metric m:mid_x_sp p:double l:mid_x_sp t:dataTypeName=number

metric m:mid_y_sp p:double l:mid_y_sp t:dataTypeName=number

metric m:end_x_sp p:double l:end_x_sp t:dataTypeName=number

metric m:end_y_sp p:double l:end_y_sp t:dataTypeName=number

metric m:shape_leng p:double l:SHAPE_Leng t:dataTypeName=number

entity e:ju3b-rwpy l:"2015 Street Tree Census - Blockface Data" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/ju3b-rwpy

property e:ju3b-rwpy t:meta.view v:id=ju3b-rwpy v:category=Environment v:averageRating=0 v:name="2015 Street Tree Census - Blockface Data" v:attribution="Department of Parks and Recreation (DPR)"

property e:ju3b-rwpy t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ju3b-rwpy t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| block_id | block_stat | trees | surv_date           | group_name               | cb_num | borocode | boroname  | cncldist | st_assem | st_senate | nta  | nta_name                               | boro_ct | zipcode | zip_city | state    | start_x_sp         | start_y_sp         | mid_x_sp           | mid_y_sp           | end_x_sp           | end_y_sp           | start_lat      | start_long      | mid_lat        | mid_long        | end_lat        | end_long        | shape_leng      | 
| ======== | ========== | ===== | =================== | ======================== | ====== | ======== | ========= | ======== | ======== | ========= | ==== | ====================================== | ======= | ======= | ======== | ======== | ================== | ================== | ================== | ================== | ================== | ================== | ============== | =============== | ============== | =============== | ============== | =============== | =============== | 
| 100185   | Complete   | 4     | 2015-10-05T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 65       | 26        | MN25 | Battery Park City-Lower Manhattan      | 1031704 | 10280   | New York | New York | 979405.62319400000 | 196800.22620000000 | 979459.79565800000 | 196897.31491700000 | 979513.96812200000 | 196994.40363300000 | 40.70684655000 | -74.01747281000 | 40.70711307000 | -74.01727748000 | 40.70737958000 | -74.01708216000 | 222.35894159500 | 
| 100685   | Complete   | 0     | 2015-06-20T00:00:00 | NYC Parks                | 101    | 1        | Manhattan | 1        | 66       | 26        | MN24 | SoHo-TriBeCa-Civic Center-Little Italy | 1003300 | 10013   | New York | New York | 983099.24736800000 | 200779.43805800000 | 982954.80540000000 | 200867.19067100000 | 982810.36343200000 | 200954.94328400000 | 40.71776979000 | -74.00415124000 | 40.71801063000 | -74.00467232000 | 40.71825147000 | -74.00519340000 | 338.01777078700 | 
| 100778   | Complete   | 0     | 2015-07-23T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 66       | 26        | MN24 | SoHo-TriBeCa-Civic Center-Little Italy | 1003300 | 10013   | New York | New York | 982766.42880800000 | 201951.06596400000 | 982772.52770300000 | 201829.09010900000 | 982720.50534400000 | 201720.96406200000 | 40.72098558000 | -74.00535211000 | 40.72063844000 | -74.00532927000 | 40.72035400000 | -74.00551773000 | 244.25646862000 | 
| 100003   | Complete   | 14    | 2015-10-01T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 65       | 26        | MN25 | Battery Park City-Lower Manhattan      | 1000900 | 10004   | New York | New York | 980627.52724600000 | 195426.51995800000 | 980650.78474600000 | 195314.91634300000 | 980674.04224500000 | 195203.31272700000 | 40.70307664000 | -74.01306488000 | 40.70277032000 | -74.01298094000 | 40.70246401000 | -74.01289700000 | 228.00244073500 | 
| 100042   | Complete   | 7     | 2015-10-01T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 65       | 26        | MN25 | Battery Park City-Lower Manhattan      | 1000700 | 10005   | New York | New York | 982139.31818600000 | 195858.66213800000 | 982230.99024700000 | 195943.69855000000 | 982322.66230700000 | 196028.73496100000 | 40.70426326000 | -74.00761256000 | 40.70449668000 | -74.00728195000 | 40.70473011000 | -74.00695134000 | 250.07965105400 | 
| 100628   | Complete   | 0     | 2015-06-20T00:00:00 | NYC Parks                | 101    | 1        | Manhattan | 1        | 66       | 26        | MN24 | SoHo-TriBeCa-Civic Center-Little Italy | 1003300 | 10013   | New York | New York | 982797.74862800000 | 200931.60179600000 | 983021.44798300000 | 200796.77037200000 | 983245.14733900000 | 200661.93894900000 | 40.71818740000 | -74.00523890000 | 40.71781735000 | -74.00443190000 | 40.71744730000 | -74.00362490000 | 522.38267375500 | 
| 100703   | Complete   | 0     | 2015-09-17T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 66       | 26        | MN24 | SoHo-TriBeCa-Civic Center-Little Italy | 1003900 | 10013   | New York | New York | 981397.93253000000 | 201126.08434600000 | 981526.75330200000 | 201110.69855000000 | 981655.57407500000 | 201095.31275400000 | 40.71872087000 | -74.01028873000 | 40.71867868000 | -74.00982401000 | 40.71863649000 | -74.00935929000 | 259.47265102400 | 
| 100503   | Complete   | 13    | 2015-10-02T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 66       | 26        | MN25 | Battery Park City-Lower Manhattan      | 1031703 | 10007   | New York | New York | 979947.92591500000 | 199945.58309800000 | 980209.08975100000 | 199902.48683800000 | 980468.91437400000 | 199848.10494700000 | 40.71548009000 | -74.01551883000 | 40.71536208000 | -74.01457770000 | 40.71521277000 | -74.01363942000 | 530.90950204700 | 
| 100828   | Complete   | 10    | 2015-10-01T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 66       | 26        | MN24 | SoHo-TriBeCa-Civic Center-Little Italy | 1003900 | 10013   | New York | New York | 981977.38970400000 | 202569.73467400000 | 981785.28444500000 | 202594.59896200000 | 981593.17918600000 | 202619.46324900000 | 40.72268351000 | -74.00819885000 | 40.72275170000 | -74.00889191000 | 40.72281990000 | -74.00958498000 | 387.41534954100 | 
| 100217   | Complete   | 0     | 2015-10-05T00:00:00 | Not in a group territory | 101    | 1        | Manhattan | 1        | 65       | 26        | MN25 | Battery Park City-Lower Manhattan      | 1001300 | 10006   | New York | New York | 980402.94173700000 | 196911.69415300000 | 980448.75299700000 | 197051.41434600000 | 980494.56425700000 | 197191.13453900000 | 40.70715300000 | -74.01387572000 | 40.70753652000 | -74.01371056000 | 40.70792003000 | -74.01354541000 | 294.07756719500 | 
```