# City Store - The Official Store of the City of New York

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-store-the-official-store-of-the-city-of-new-york) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mqdy-gu73) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mqdy-gu73/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mqdy-gu73/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mqdy-gu73 |
| Name | City Store - The Official Store of the City of New York |
| Attribution | Department of Citywide Administrative Services (DCAS) |
| Category | City Government |
| Created | 2015-05-07T14:03:53Z |
| Publication Date | 2017-04-20T20:00:28Z |

## Description

Information on City Store ? the Official Story of the City of New York

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| No       | time           | :updated_at         | updated_at          | meta_data | meta_data   |
| Yes      | series tag     | item_number         | Item Number         | text      | text        |
| Yes      | series tag     | product_name        | Product Name        | text      | text        |
| Yes      | series tag     | citystore_exclusive | CityStore Exclusive | text      | text        |
| Yes      | numeric metric | unit_price          | Unit Price          | money     | money       |
| Yes      | series tag     | color               | Color               | text      | text        |
| Yes      | series tag     | size                | Size                | text      | text        |
| Yes      | series tag     | style               | Style               | text      | text        |
| Yes      | series tag     | category_name       | Category Name       | text      | text        |
| Yes      | series tag     | description         | Description         | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:mqdy-gu73 d:2017-04-20T20:00:19.000Z t:item_number=06079 t:category_name="Married in New York" t:description="Nothing better than waking up to a mug that reminds you of your wedding day! 8  oz. Dishwasher and microwavable safe." t:product_name="'We Do' Mug: Man & Woman" t:citystore_exclusive=No m:unit_price=14

series e:mqdy-gu73 d:2017-04-20T20:00:19.000Z t:item_number=06091 t:category_name="Married in New York" t:style="Women in Dresses" t:description="Nothing better than waking up to a mug that reminds you of your special day! 8  oz. Dishwasher and microwave safe." t:product_name="'We Do' Mug: Women" t:citystore_exclusive=No m:unit_price=14

series e:mqdy-gu73 d:2017-04-20T20:00:19.000Z t:item_number=04096 t:category_name="NYC Subway" t:description="Keep your MetroCard safe and sound with this convenient holder! Includes a Manhattan subway map (below 86th street) on the reverse side. Durable hard plastic for ultimate protection." t:product_name="MetroCard MetroCard Holder" t:citystore_exclusive=No m:unit_price=3
```

## Meta Commands

```ls
metric m:unit_price p:integer l:"Unit Price" t:dataTypeName=money

entity e:mqdy-gu73 l:"City Store - The Official Store of the City of New York" t:attribution="Department of Citywide Administrative Services (DCAS)" t:url=https://data.cityofnewyork.us/api/views/mqdy-gu73

property e:mqdy-gu73 t:meta.view v:id=mqdy-gu73 v:category="City Government" v:averageRating=0 v:name="City Store - The Official Store of the City of New York" v:attribution="Department of Citywide Administrative Services (DCAS)"

property e:mqdy-gu73 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mqdy-gu73 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | item_number | product_name                                               | citystore_exclusive | unit_price | color | size | style            | category_name             | description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| =========== | =========== | ========================================================== | =================== | ========== | ===== | ==== | ================ | ========================= | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1492718419  | 06079       | 'We Do' Mug: Man & Woman                                   | No                  | 14         |       |      |                  | Married in New York       | Nothing better than waking up to a mug that reminds you of your wedding day! 8 oz. Dishwasher and microwavable safe.                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| 1492718419  | 06091       | 'We Do' Mug: Women                                         | No                  | 14         |       |      | Women in Dresses | Married in New York       | Nothing better than waking up to a mug that reminds you of your special day! 8 oz. Dishwasher and microwave safe.                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1492718419  | 04096       | MetroCard MetroCard Holder                               | No                  | 3          |       |      |                  | NYC Subway                | Keep your MetroCard safe and sound with this convenient holder! Includes a Manhattan subway map (below 86th street) on the reverse side. Durable hard plastic for ultimate protection.                                                                                                                                                                                                                                                                                                                                                      | 
| 1492718419  | 06081       | We Do Mug: Men                                           | No                  | 14         |       |      |                  | Married in New York       | Nothing better than waking up to a mug that reminds you of your special day! 8 oz. Dishwasher and microwave safe.                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 1492718419  | 23019       | 100% cotton NYC Dish Towel                                 | No                  | 20         |       |      |                  | Home Accents              | Makes drying dishes fun! New York City silk screened and framed with a hand embroidered border on a 100% cotton dish towel. The original art celebrates Little Italy, the Garment district, Chelsea, Soho, Nolita, Harlem, etc... Three stripes down both sides and hand dyed ric-rac top and bottom add a charming touch. Machine wash and dry. 100% Cotton. 21 x 30 inches.                                                                                                                                                               | 
| 1492718419  | 09343       | 123 New York                                               | No                  | 8          |       |      |                  | City Kids                 | Making basic numbers fun to learn, this board book has the young reader count from 1 to 10 using some of New York s most famous symbols. The Statue of Liberty, the Brooklyn Bridge, the Empire State Building, apples, subway cars, yellow taxis, and more are all depicted here using beautiful illustrations, vivid colors, and detailed design. The book also includes a complete bilingual location list in both English and Spanish. Baby-Preschool. By Puck (Author), Kevin Somers (Illustrator). 22 pages 6 x 6 inches. Board Book. | 
| 1492718419  | 16046       | Replica Subway Map Poster / Wrap                           | No                  | 6          |       |      |                  | NYC Subway                | Trying to pick out places you know? It so interesting and pretty you won t know whether to frame it or use it! This vintage Hagstrom subway map has been reproduced on quality thick Cavallini paper and can be used as wrap or wall decoration. It your choice! 19 x 28 inches.                                                                                                                                                                                                                                                            | 
| 1492718419  | 16046       | Replica Subway Map Poster / Wrap                           | No                  | 6          |       |      |                  | Posters, Prints and Signs | Trying to pick out places you know? It so interesting and pretty you won t know whether to frame it or use it! This vintage Hagstrom subway map has been reproduced on quality thick Cavallini paper and can be used as wrap or wall decoration. It your choice! 19 x 28 inches.                                                                                                                                                                                                                                                            | 
| 1492718419  | 0410        | 1938 Building Code, Edited and Amended to December 6, 1968 | No                  | 5          |       |      |                  | Rules & Regulations       | Building Laws relating to buildings built before December 6,1968. 182 pages. 11 x 8 1/2 . Soft cover.                                                                                                                                                                                                                                                                                                                                                                                                                                       | 
| 1492718419  | 10064       | 1968 Building Code of the City of New York - Update Set #1 | Yes                 | 15         |       |      |                  | Rules & Regulations       | This is update set # 1 to the 1968 Building Code of the City of New York with amendments to October 2003. This update includes amendments through October 2004. Included in the set are instructions on how to add, discard and replace pages. NOTE: Update set #1 is included in 1968 Building Code of the City of New York with 2 updates (item #10127)                                                                                                                                                                                   | 
```