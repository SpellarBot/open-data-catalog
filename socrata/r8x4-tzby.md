# Post Offices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/post-offices) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/r8x4-tzby) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/r8x4-tzby/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/r8x4-tzby/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | r8x4-tzby |
| Name | Post Offices |
| Attribution | Montgomery County, MD |
| Category | Community/Recreation |
| Tags | postal, mail, post office, stamps |
| Created | 2016-03-29T18:45:38Z |
| Publication Date | 2016-03-29T18:46:01Z |

## Description

A map of all Montgomery County Post Offices

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag  | category    | CATEGORY   | text      | text        |
| Yes      | series tag  | name        | NAME       | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | zipcode     | ZIPCODE    | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
| Yes      | series tag  | url         | URL        | text      | text        |
| Yes      | series tag  | data        | DATA       | text      | text        |
| No       |             | point_x     | POINT_X    | number    | number      |
| No       |             | point_y     | POINT_Y    | number    | number      |
| No       |             | latitude    | LATITUDE   | number    | number      |
| No       |             | longitude   | LONGITUDE  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,point_x,point_y,latitude,longitude
```

## Data Commands

```ls
series e:r8x4-tzby d:2016-03-29T18:45:38.000Z t:category="POST OFFICE" t:phone=301-253-3781 t:name="Damascus Post Office" t:zipcode=20872 t:objectid=1 t:url=http://www.usps.com t:city=Damascus m:row_number.r8x4-tzby=1

series e:r8x4-tzby d:2016-03-29T18:45:38.000Z t:category="POST OFFICE" t:phone=301-428-8243 t:name="Dickerson Post Office" t:zipcode=20842 t:objectid=2 t:url=http://www.usps.com t:city=Dickerson m:row_number.r8x4-tzby=2

series e:r8x4-tzby d:2016-03-29T18:45:38.000Z t:category="POST OFFICE" t:phone=301-972-8153 t:name="Barnesville Post Office" t:zipcode=20838 t:objectid=3 t:url=http://www.usps.com t:city=Barnesville m:row_number.r8x4-tzby=3
```

## Meta Commands

```ls
metric m:row_number.r8x4-tzby p:long l:"Row Number"

entity e:r8x4-tzby l:"Post Offices" t:attribution="Montgomery County, MD" t:url=https://data.montgomerycountymd.gov/api/views/r8x4-tzby

property e:r8x4-tzby t:meta.view v:id=r8x4-tzby v:category=Community/Recreation v:averageRating=0 v:name="Post Offices" v:attribution="Montgomery County, MD"

property e:r8x4-tzby t:meta.view.owner v:id=hesx-43k8 v:screenName=Dan v:displayName=Dan

property e:r8x4-tzby t:meta.view.tableauthor v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```

## Top Records

```ls
| :updated_at | objectid | category    | name                           | address                    | city               | zipcode | phone        | url                 | data | point_x                                  | point_y                                  | latitude                                           | longitude                                          | 
| =========== | ======== | =========== | ============================== | ========================== | ================== | ======= | ============ | =================== | ==== | ======================================== | ======================================== | ================================================== | ================================================== | 
| 0           | 1        | POST OFFICE | Damascus Post Office           | 26400 Woodfield Rd         | Damascus           | 20872   | 301-253-3781 | http://www.usps.com |      | 1254683.25000535999424755573272705078125 | 590538.74995987000875174999237060546875  | 39.287988519999998970888555049896240234375         | -77.203678929999995261823642067611217498779296875  | 
| 0           | 2        | POST OFFICE | Dickerson Post Office          | 22145 Dickerson Rd         | Dickerson          | 20842   | 301-428-8243 | http://www.usps.com |      | 1192108.62504198006354272365570068359375 | 565640.625010629999451339244842529296875 | 39.219039449999996804763213731348514556884765625   | -77.424345079999994823083397932350635528564453125  | 
| 0           | 3        | POST OFFICE | Barnesville Post Office        | 22110 Beallsville Rd       | Barnesville        | 20838   | 301-972-8153 | http://www.usps.com |      | 1205206.2500356100499629974365234375     | 565377.187466479954309761524200439453125 | 39.218474229999998215134837664663791656494140625   | -77.3781124199999936763560981489717960357666015625 | 
| 0           | 4        | POST OFFICE | Laytonsville Post Office       | 6830 Olney Laytonsville Rd | Laytonsville       | 20882   | 301-208-3736 | http://www.usps.com |      | 1272654.50004463992081582546234130859375 | 559785.000033920048736035823822021484375 | 39.203646120000001928929123096168041229248046875   | -77.140019609999995964244590140879154205322265625  | 
| 0           | 5        | POST OFFICE | Beallsville Post Office        | 19800 Darnestown Rd        | Beallsville        | 20839   | 301-349-2140 | http://www.usps.com |      | 1195203.2499631899408996105194091796875  | 551124.375001939944922924041748046875    | 39.179223489999998264465830288827419281005859375   | -77.4131905400000022154927137307822704315185546875 | 
| 0           | 6        | POST OFFICE | Boyds Post Office              | 15300 Barnsville Rd        | Boyds              | 20841   | 301-972-9527 | http://www.usps.com |      | 1222540.75003416999243199825286865234375 | 553418.937456990010105073451995849609375 | 39.18582344000000006190020940266549587249755859375 | -77.316783189999995329344528727233409881591796875  | 
| 0           | 7        | POST OFFICE | Brookeville Post Office        | 22311 Georgia Ave          | Brookeville        | 20833   | 301-260-2975 | http://www.usps.com |      | 1295564.37498686998151242733001708984375 | 566253.062546569970436394214630126953125 | 39.2214731899999975439641275443136692047119140625  | -77.0591895499999992580342222936451435089111328125 | 
| 0           | 8        | POST OFFICE | Germantown Post Office         | 12774 Wisteria Dr          | Germantown         | 20874   | 301-428-0460 | http://www.usps.com |      | 1236478.3750318600796163082122802734375  | 549274.750008270028047263622283935546875 | 39.17456776000000218118657357990741729736328125    | -77.267569489999999632345861755311489105224609375  | 
| 0           | 9        | POST OFFICE | Montgomery Village Post Office | 10079 Stedwick Rd          | Montgomery Village | 20886   | 301-208-3716 | http://www.usps.com |      | 1253307.999988730065524578094482421875   | 547901.187541970051825046539306640625    | 39.17091694999999873516571824438869953155517578125 | -77.20819414999999708015820942819118499755859375   | 
| 0           | 10       | POST OFFICE | Olney Post Office              | 3570 Olney Laytonsville Rd | Olney              | 20832   | 301-260-9013 | http://www.usps.com |      | 1292123.49998621991835534572601318359375 | 542117.687531149946153163909912109375    | 39.1552009400000002870001480914652347564697265625  | -77.07126832000000149491825141012668609619140625   | 
```