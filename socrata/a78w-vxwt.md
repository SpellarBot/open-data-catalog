# Schools served by 15 mph school zones

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/schools-served-by-15-mph-school-zones) |
| Metadata | [Link](https://data.sfgov.org/api/views/a78w-vxwt) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/a78w-vxwt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/a78w-vxwt/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | a78w-vxwt |
| Name | Schools served by 15 mph school zones |
| Category | Public Safety |
| Tags | school zones, 15mph |
| Created | 2016-08-19T00:11:27Z |
| Publication Date | 2016-11-04T18:03:52Z |

## Description

This dataset was created to show the schools served by street segments that are designated as 15 mph school zones.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | object_id          | Object ID          | text      | number      |
| Yes      | series tag     | street_name        | Street Name        | text      | text        |
| Yes      | series tag     | street_type        | Street Type        | text      | text        |
| Yes      | series tag     | grades             | Grades             | text      | text        |
| Yes      | series tag     | former_school_name | Former School Name | text      | text        |
| Yes      | series tag     | public_school      | Public School      | text      | text        |
| Yes      | series tag     | grade_label        | Grade Label        | text      | text        |
| Yes      | series tag     | status             | Status             | text      | text        |
| Yes      | series tag     | school_name        | School Name        | text      | text        |
| Yes      | series tag     | closed             | Closed             | text      | text        |
| Yes      | numeric metric | installded         | Installded         | number    | number      |
| No       |                | full_address       | Full Address       | text      | text        |
| Yes      | time           | last_edited_date   | Last Edited Date   | date      | date        |
| Yes      | series tag     | full_school_name   | Full School Name   | text      | text        |
| No       |                | geom               | Geom               | polygon   | polygon     |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = full_address,geom
```

## Data Commands

```ls
series e:a78w-vxwt d:2016-04-29T00:00:00.000Z t:school_name=Moscone t:object_id=1 t:street_name=HARRISON t:public_school=Public t:grade_label="Elementary School" t:grades="Elem. School" t:full_school_name="George Moscone" t:street_type=ST m:installded=1

series e:a78w-vxwt d:2016-04-29T00:00:00.000Z t:school_name="Star of the Sea" t:object_id=2 t:street_name=09TH t:public_school=Private t:grade_label="Elementary/Middle School" t:grades=K-8 t:full_school_name="Star of the Sea" t:street_type=AVE m:installded=1

series e:a78w-vxwt d:2016-04-29T00:00:00.000Z t:school_name="Holy Name" t:object_id=3 t:street_name=40TH t:public_school=Private t:grade_label="Elementary/Middle School" t:grades=K-8 t:full_school_name="Holy Name" t:street_type=AVE m:installded=1
```

## Meta Commands

```ls
metric m:installded p:long l:Installded t:dataTypeName=number

entity e:a78w-vxwt l:"Schools served by 15 mph school zones" t:url=https://data.sfgov.org/api/views/a78w-vxwt

property e:a78w-vxwt t:meta.view v:id=a78w-vxwt v:category="Public Safety" v:averageRating=0 v:name="Schools served by 15 mph school zones"

property e:a78w-vxwt t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:a78w-vxwt t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:a78w-vxwt t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | street_name | street_type | grades       | former_school_name | public_school | grade_label              | status | school_name        | closed  | installded | full_address   | last_edited_date | full_school_name     | geom                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| ========= | =========== | =========== | ============ | ================== | ============= | ======================== | ====== | ================== | ======= | ========== | ============== | ================ | ==================== | ============================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1         | HARRISON    | ST          | Elem. School |                    | Public        | Elementary School        |        | Moscone            |         | 1          | 2576 HARRISON  | 1461888000       | George Moscone       | POLYGON ((-122.41334821502618 37.757286944495654, -122.41250435021978 37.757337678780395, -122.41239175192884 37.75617782919083, -122.41281460803414 37.75615101204443, -122.4128931826031 37.75697255788667, -122.41330965059042 37.75694614419116, -122.41334821502618 37.757286944495654), (-122.41331558231394 37.756945768535374, -122.41330965059042 37.75694614419116, -122.41330904498652 37.75694079409907, -122.41331558231394 37.756945768535374))                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 2         | 09TH        | AVE         | K-8          |                    | Private       | Elementary/Middle School |        | Star of the Sea    |         | 1          | 370 09TH       | 1461888000       | Star of the Sea      | POLYGON ((-122.46692185725735 37.781352986684844, -122.4671291366858 37.78134362553363, -122.4673018712057 37.7813358250463, -122.46741414652398 37.78133075414358, -122.46746372913807 37.78201570278626, -122.46704919047619 37.78203476375529, -122.46705415216437 37.78210330872397, -122.46705914688717 37.7821723122738, -122.46706407556856 37.78224039955926, -122.4670739990095 37.78237749039049, -122.46666852025297 37.782396133365495, -122.46661244623658 37.781621405005865, -122.46694021505878 37.781606604284555, -122.46692185725735 37.781352986684844))                                                                                                                                                                                                                                                                                   | 
| 3         | 40TH        | AVE         | K-8          |                    | Private       | Elementary/Middle School |        | Holy Name          |         | 1          | 1560 40TH      | 1461888000       | Holy Name            | POLYGON ((-122.49870185038876 37.75766688009129, -122.4986630910032 37.757115433550396, -122.49884754928651 37.75710728284336, -122.49887311594975 37.757471027808286, -122.49915977863067 37.75745833659601, -122.49919244387803 37.757923026609085, -122.4987765778356 37.7579413898272, -122.49866778284364 37.75794619367142, -122.49864831664972 37.75766924289373, -122.49870185038876 37.75766688009129))                                                                                                                                                                                                                                                                                                                                                                                                                                               | 
| 4         | GREEN       | ST          | K-8          |                    | Private       | Elementary/Middle School |        | St Vincent De Paul |         | 1          | 2340 GREEN     | 1461888000       | St Vincent De Paul   | POLYGON ((-122.438227202854 37.79626923003224, -122.43811101494 37.796284014736514, -122.43799995337105 37.79629814665659, -122.4379116851899 37.79630937974012, -122.43782341584692 37.79632061095552, -122.43773528499774 37.796331825001005, -122.43764117275713 37.79634380056056, -122.43751302414609 37.79636010603229, -122.43742944281324 37.796370741017455, -122.43740108296278 37.796230706229785, -122.43741816979819 37.796228539458866, -122.43752411633001 37.79621510758698, -122.4374764084744 37.79597954885705, -122.43850502398513 37.79584913245577, -122.43851809245906 37.79591374298583, -122.43816440405615 37.795958749394394, -122.43819703885488 37.79612009110759, -122.43821212083921 37.79619466102182, -122.438227202854 37.79626923003224))                                                                                   | 
| 5         | CHURCH      | ST          | CDC          |                    | Public        | CDC                      |        | Mahler CDC         |         | 0          | 990 CHURCH     | 1461888000       | Mahler CDC           | POLYGON ((-122.4278587739696 37.75569372608973, -122.42776456077672 37.754943544969834, -122.42841157665063 37.75491317857192, -122.42850528347171 37.755643583899634, -122.4278587739696 37.75569372608973))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 6         | SLOAT       | BL          | 4-8          |                    | Private       | Elementary/Middle School |        | W. Portal Lutheran |         | 1          | 200 SLOAT      | 1461888000       | West Portal Lutheran | POLYGON ((-122.47308002741691 37.735290216866105, -122.47307425273601 37.73520518502676, -122.4730727654792 37.73518329640049, -122.47377793965052 37.73516468022908, -122.47378352706156 37.73524694160833, -122.47385270112437 37.73524511489491, -122.4739218388817 37.73524328995021, -122.4738957556992 37.73485924856802, -122.47393378104123 37.734858244389116, -122.47395557852997 37.73517917051089, -122.47410422615452 37.73517524534814, -122.47426324486922 37.73517104667405, -122.47428702281356 37.73552111308358, -122.47421961257685 37.73552289374032, -122.47387219018593 37.735532067033404, -122.47352649547923 37.73554119390965, -122.47309784045862 37.735552509178234, -122.4730973526734 37.73554531147385, -122.47309157681855 37.73546028054023, -122.47308580211083 37.73537524780296, -122.47308002741691 37.735290216866105)) | 
| 7         | DARIEN      | WY          | Elem. School |                    | Public        | Elementary School        |        | Sloat              |         | 1          | 50 DARIEN      | 1461888000       | Commodore Sloat      | POLYGON ((-122.47121807853007 37.731867149835345, -122.46973449655721 37.73180820330081, -122.4697608367743 37.731336062893426, -122.46977315942236 37.731172746599825, -122.46981369098471 37.73102659164056, -122.46987051429942 37.73086693837157, -122.47013717215115 37.73045690650149, -122.47128820232174 37.73095343580494, -122.47121807853007 37.731867149835345))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | 
| 8         | BUCHANAN    | ST          | High School  |                    | Private       | High School              |        | Open Book School   | CLOSED  | 0          | 1832 BUCHANAN  | 1461888000       | Open Book School     | POLYGON ((-122.43007260177234 37.78711424654462, -122.42964602710308 37.787152076826565, -122.42961858871739 37.786844054167425, -122.43000630884345 37.7868068615779, -122.43007260177234 37.78711424654462))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 9         | THOMAS MORE | WY          | K-8          |                    | Private       | Elementary/Middle School |        | St Thomas More     |         | 1          | 50 THOMAS MORE | 1461888000       | St Thomas More       | POLYGON ((-122.47293915579449 37.712746252826534, -122.47322313820355 37.71204573475995, -122.4742476059658 37.712353949525905, -122.47400343222021 37.71287690109681, -122.47293915579449 37.712746252826534))                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 
| 10        | FARALLONES  | ST          | K-8          |                    | Private       | Elementary/Middle School |        | St Michael         | closed? | 0          | 55 FARALLONES  | 1461888000       | St Michael           | POLYGON ((-122.45465001197304 37.71331718606665, -122.45527916154258 37.71331166550141, -122.4552842724387 37.71365493738649, -122.45527734859324 37.71365499806113, -122.45519092584547 37.713655756904856, -122.45501808147873 37.71365727350123, -122.45493165985978 37.71365803215486, -122.45493685689358 37.71400716752536, -122.45404150452198 37.71401338942323, -122.45371799881372 37.71401563535536, -122.45371386123384 37.71373737267982, -122.45371284049865 37.71366871811149, -122.45374740870277 37.713668415195215, -122.45374230602995 37.71332514324385, -122.45403123158825 37.7133226110223, -122.45465001197304 37.71331718606665))                                                                                                                                                                                                     | 
```