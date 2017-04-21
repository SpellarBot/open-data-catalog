# Juvenile Offense Referrals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/juvenile-offense-referrals) |
| Metadata | [Link](https://data.wa.gov/api/views/jwyj-mg7x) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/jwyj-mg7x/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/jwyj-mg7x/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | jwyj-mg7x |
| Name | Juvenile Offense Referrals |
| Attribution | DSHS Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice |
| Created | 2015-02-10T17:23:29Z |
| Publication Date | 2015-02-10T19:56:01Z |

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                  | Data Type | Render Type |
| ======== | ============== | ==================== | ===================== | ========= | =========== |
| No       | time           | :updated_at          | updated_at            | meta_data | meta_data   |
| Yes      | series tag     | county               | DecisionPoint         | text      | text        |
| Yes      | series tag     | group                | Group                 | text      | text        |
| Yes      | numeric metric | adams                | Adams                 | number    | number      |
| Yes      | numeric metric | asotin_garfield      | Asotin/Garfield       | number    | number      |
| Yes      | numeric metric | benton_franklin      | Benton/Franklin       | number    | number      |
| Yes      | numeric metric | chelan               | Chelan                | number    | number      |
| Yes      | numeric metric | clallam              | Clallam               | number    | number      |
| Yes      | numeric metric | clark                | Clark                 | number    | number      |
| Yes      | numeric metric | cowlitz              | Cowlitz               | number    | number      |
| Yes      | numeric metric | douglas              | Douglas               | number    | number      |
| Yes      | numeric metric | ferry                | Ferry                 | number    | number      |
| Yes      | numeric metric | grant                | Grant                 | number    | number      |
| Yes      | numeric metric | grays_harbor         | Grays Harbor          | number    | number      |
| Yes      | numeric metric | island               | Island                | number    | number      |
| Yes      | numeric metric | jefferson            | Jefferson             | number    | number      |
| Yes      | numeric metric | king                 | King                  | number    | number      |
| Yes      | numeric metric | kitsap               | Kitsap                | number    | number      |
| Yes      | numeric metric | kittitas             | Kittitas              | number    | number      |
| Yes      | numeric metric | klickitat            | Klickitat             | number    | number      |
| Yes      | numeric metric | lewis                | Lewis                 | number    | number      |
| Yes      | numeric metric | lincoln              | Lincoln               | number    | number      |
| Yes      | numeric metric | mason                | Mason                 | number    | number      |
| Yes      | numeric metric | okanogan             | Okanogan              | number    | number      |
| Yes      | numeric metric | pacific_wahkiakum    | Pacific /Wahkiakum    | number    | number      |
| Yes      | numeric metric | pend_oreille         | Pend Oreille          | number    | number      |
| Yes      | numeric metric | pierce               | Pierce                | number    | number      |
| Yes      | numeric metric | san_juan             | San Juan              | number    | number      |
| Yes      | numeric metric | skagit               | Skagit                | number    | number      |
| Yes      | numeric metric | skamania             | Skamania              | number    | number      |
| Yes      | numeric metric | snohomish            | Snohomish             | number    | number      |
| Yes      | numeric metric | spokane              | Spokane               | number    | number      |
| Yes      | numeric metric | stevens              | Stevens               | number    | number      |
| Yes      | numeric metric | thurston             | Thurston              | number    | number      |
| Yes      | numeric metric | walla_walla_columbia | Walla Walla /Columbia | number    | number      |
| Yes      | numeric metric | whatcom              | Whatcom               | number    | number      |
| Yes      | numeric metric | whitman              | Whitman               | number    | number      |
| Yes      | numeric metric | yakima               | Yakima                | number    | number      |
| Yes      | numeric metric | total                | Total                 | number    | number      |
| Yes      | series tag     | table                | Table                 | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jwyj-mg7x d:2015-02-10T09:57:26.000Z t:county="Referred to Juv. Dept." t:table="Table 67" t:group=All m:total=28947 m:asotin_garfield=225 m:pacific_wahkiakum=132 m:clark=2450 m:skagit=773 m:grant=802 m:kittitas=146 m:snohomish=2669 m:king=4151 m:island=184 m:thurston=1233 m:whitman=137 m:lewis=485 m:chelan=368 m:whatcom=841 m:klickitat=101 m:stevens=150 m:walla_walla_columbia=489 m:skamania=91 m:lincoln=43 m:pend_oreille=75 m:yakima=1419 m:jefferson=156 m:grays_harbor=421 m:san_juan=28 m:adams=211 m:pierce=3616 m:clallam=421 m:ferry=19 m:cowlitz=620 m:douglas=297 m:spokane=2192 m:okanogan=331 m:mason=245 m:kitsap=1230 m:benton_franklin=2196

series e:jwyj-mg7x d:2015-02-10T09:57:26.000Z t:county="Legal Cases Filed" t:table="Table 67" t:group=All m:total=14432 m:asotin_garfield=121 m:pacific_wahkiakum=63 m:clark=989 m:skagit=373 m:grant=349 m:kittitas=87 m:snohomish=1330 m:king=2257 m:island=114 m:thurston=832 m:whitman=43 m:lewis=214 m:chelan=226 m:whatcom=475 m:klickitat=44 m:stevens=93 m:walla_walla_columbia=257 m:skamania=44 m:lincoln=14 m:pend_oreille=29 m:yakima=817 m:jefferson=85 m:grays_harbor=184 m:san_juan=18 m:adams=49 m:pierce=1397 m:clallam=260 m:ferry=10 m:cowlitz=459 m:douglas=134 m:spokane=1012 m:okanogan=216 m:mason=152 m:kitsap=650 m:benton_franklin=1035

series e:jwyj-mg7x d:2015-02-10T09:57:26.000Z t:county="Diversions Filed" t:table="Table 67" t:group=All m:total=12695 m:asotin_garfield=88 m:pacific_wahkiakum=37 m:clark=1153 m:skagit=399 m:grant=291 m:kittitas=64 m:snohomish=1685 m:king=1695 m:island=80 m:thurston=357 m:whitman=38 m:lewis=147 m:chelan=124 m:whatcom=444 m:klickitat=61 m:stevens=58 m:walla_walla_columbia=157 m:skamania=39 m:lincoln=17 m:pend_oreille=37 m:yakima=618 m:jefferson=69 m:grays_harbor=184 m:san_juan=5 m:adams=82 m:pierce=1666 m:clallam=151 m:ferry=3 m:cowlitz=254 m:douglas=130 m:spokane=978 m:okanogan=93 m:mason=78 m:kitsap=450 m:benton_franklin=963
```

## Meta Commands

```ls
metric m:adams p:integer l:Adams t:dataTypeName=number

metric m:asotin_garfield p:integer l:Asotin/Garfield t:dataTypeName=number

metric m:benton_franklin p:integer l:Benton/Franklin t:dataTypeName=number

metric m:chelan p:integer l:Chelan t:dataTypeName=number

metric m:clallam p:integer l:Clallam t:dataTypeName=number

metric m:clark p:integer l:Clark t:dataTypeName=number

metric m:cowlitz p:integer l:Cowlitz t:dataTypeName=number

metric m:douglas p:integer l:Douglas t:dataTypeName=number

metric m:ferry p:integer l:Ferry t:dataTypeName=number

metric m:grant p:integer l:Grant t:dataTypeName=number

metric m:grays_harbor p:integer l:"Grays Harbor" t:dataTypeName=number

metric m:island p:integer l:Island t:dataTypeName=number

metric m:jefferson p:integer l:Jefferson t:dataTypeName=number

metric m:king p:integer l:King t:dataTypeName=number

metric m:kitsap p:integer l:Kitsap t:dataTypeName=number

metric m:kittitas p:integer l:Kittitas t:dataTypeName=number

metric m:klickitat p:integer l:Klickitat t:dataTypeName=number

metric m:lewis p:integer l:Lewis t:dataTypeName=number

metric m:lincoln p:integer l:Lincoln t:dataTypeName=number

metric m:mason p:integer l:Mason t:dataTypeName=number

metric m:okanogan p:integer l:Okanogan t:dataTypeName=number

metric m:pacific_wahkiakum p:integer l:"Pacific /Wahkiakum" t:dataTypeName=number

metric m:pend_oreille p:integer l:"Pend Oreille" t:dataTypeName=number

metric m:pierce p:integer l:Pierce t:dataTypeName=number

metric m:san_juan p:integer l:"San Juan" t:dataTypeName=number

metric m:skagit p:integer l:Skagit t:dataTypeName=number

metric m:skamania p:integer l:Skamania t:dataTypeName=number

metric m:snohomish p:integer l:Snohomish t:dataTypeName=number

metric m:spokane p:integer l:Spokane t:dataTypeName=number

metric m:stevens p:integer l:Stevens t:dataTypeName=number

metric m:thurston p:integer l:Thurston t:dataTypeName=number

metric m:walla_walla_columbia p:integer l:"Walla Walla /Columbia" t:dataTypeName=number

metric m:whatcom p:integer l:Whatcom t:dataTypeName=number

metric m:whitman p:integer l:Whitman t:dataTypeName=number

metric m:yakima p:integer l:Yakima t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:jwyj-mg7x l:"Juvenile Offense Referrals" t:attribution="DSHS Juvenile Justice" t:url=https://data.wa.gov/api/views/jwyj-mg7x

property e:jwyj-mg7x t:meta.view v:id=jwyj-mg7x v:category="Public Safety" v:averageRating=0 v:name="Juvenile Offense Referrals" v:attribution="DSHS Juvenile Justice"

property e:jwyj-mg7x t:meta.view.owner v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:displayName="OCIO-Will Saunders"

property e:jwyj-mg7x t:meta.view.tableauthor v:id=h2ue-vnnt v:profileImageUrlMedium=/api/users/h2ue-vnnt/profile_images/THUMB v:profileImageUrlLarge=/api/users/h2ue-vnnt/profile_images/LARGE v:screenName="OCIO-Will Saunders" v:profileImageUrlSmall=/api/users/h2ue-vnnt/profile_images/TINY v:roleName=publisher v:displayName="OCIO-Will Saunders"
```

## Top Records

```ls
| :updated_at | county                    | group | adams | asotin_garfield | benton_franklin | chelan | clallam | clark | cowlitz | douglas | ferry | grant | grays_harbor | island | jefferson | king | kitsap | kittitas | klickitat | lewis | lincoln | mason | okanogan | pacific_wahkiakum | pend_oreille | pierce | san_juan | skagit | skamania | snohomish | spokane | stevens | thurston | walla_walla_columbia | whatcom | whitman | yakima | total | table    | 
| =========== | ========================= | ===== | ===== | =============== | =============== | ====== | ======= | ===== | ======= | ======= | ===== | ===== | ============ | ====== | ========= | ==== | ====== | ======== | ========= | ===== | ======= | ===== | ======== | ================= | ============ | ====== | ======== | ====== | ======== | ========= | ======= | ======= | ======== | ==================== | ======= | ======= | ====== | ===== | ======== | 
| 1423562246  | Referred to Juv. Dept.    | All   | 211   | 225             | 2196            | 368    | 421     | 2450  | 620     | 297     | 19    | 802   | 421          | 184    | 156       | 4151 | 1230   | 146      | 101       | 485   | 43      | 245   | 331      | 132               | 75           | 3616   | 28       | 773    | 91       | 2669      | 2192    | 150     | 1233     | 489                  | 841     | 137     | 1419   | 28947 | Table 67 | 
| 1423562246  | Legal Cases Filed         | All   | 49    | 121             | 1035            | 226    | 260     | 989   | 459     | 134     | 10    | 349   | 184          | 114    | 85        | 2257 | 650    | 87       | 44        | 214   | 14      | 152   | 216      | 63                | 29           | 1397   | 18       | 373    | 44       | 1330      | 1012    | 93      | 832      | 257                  | 475     | 43      | 817    | 14432 | Table 67 | 
| 1423562246  | Diversions Filed          | All   | 82    | 88              | 963             | 124    | 151     | 1153  | 254     | 130     | 3     | 291   | 184          | 80     | 69        | 1695 | 450    | 64       | 61        | 147   | 17      | 78    | 93       | 37                | 37           | 1666   | 5        | 399    | 39       | 1685      | 978     | 58      | 357      | 157                  | 444     | 38      | 618    | 12695 | Table 67 | 
| 1423562246  | No Action* Taken          | All   | 45    | 9               | 220             | 24     | 58      | 204   | 17      | 11      | 0     | 173   | 8            | 7      | 0         | 1    | 213    | 7        | 0         | 78    | 0       | 28    | 49       | 14                | 5            | 636    | 0        | 40     | 10       | 74        | 194     | 1       | 2        | 1                    | 10      | 28      | 181    | 2348  | Table 67 | 
| 1423562246  | Informal Action Taken     | All   | 1     | 3               | 5               | 1      | 0       | 247   | 17      | 3       | 0     | 7     | 51           | 0      | 0         | 1    | 13     | 2        | 0         | 4     | 0       | 5     | 4        | 0                 | 1            | 202    | 0        | 8      | 2        | 5         | 43      | 2       | 0        | 1                    | 6       | 5       | 9      | 648   | Table 67 | 
| 1423562246  | Div Comp                  | All   | 21    | 27              | 196             | 38     | 27      | 601   | 83      | 38      | 0     | 87    | 39           | 22     | 23        | 384  | 232    | 8        | 15        | 67    | 4       | 25    | 30       | 8                 | 0            | 611    | 6        | 141    | 14       | 461       | 197     | 20      | 272      | 52                   | 197     | 12      | 300    | 4258  | Table 67 | 
| 1423562246  | Div. Counseled & Released | All   | 16    | 1               | 373             | 1      | 3       | 17    | 41      | 4       | 0     | 7     | 1            | 2      | 3         | 236  | 1      | 2        | 1         | 0     | 0       | 10    | 15       | 1                 | 0            | 10     | 0        | 92     | 0        | 189       | 88      | 1       | 4        | 0                    | 13      | 4       | 4      | 1140  | Table 67 | 
| 1423562246  | Div in Process            | All   | 73    | 53              | 297             | 80     | 100     | 555   | 63      | 85      | 3     | 193   | 125          | 67     | 47        | 652  | 294    | 17       | 44        | 109   | 13      | 51    | 43       | 48                | 30           | 873    | 7        | 223    | 25       | 368       | 383     | 46      | 449      | 121                  | 316     | 25      | 466    | 6344  | Table 67 | 
| 1423562246  | Total Div Not Compl       | All   | 0     | 1               | 147             | 2      | 45      | 105   | 39      | 0       | 0     | 6     | 19           | 1      | 14        | 84   | 98     | 8        | 1         | 22    | 0       | 26    | 14       | 12                | 0            | 422    | 0        | 59     | 1        | 549       | 269     | 3       | 100      | 22                   | 36      | 0       | 100    | 2205  | Table 67 | 
| 1423562246  | Div Reject by Div Unit    | All   | 0     | 1               | 102             | 1      | 39      | 85    | 37      | 0       | 0     | 4     | 15           | 0      | 13        | 84   | 45     | 7        | 0         | 13    | 0       | 19    | 10       | 7                 | 0            | 345    | 0        | 55     | 1        | 522       | 239     | 2       | 70       | 6                    | 21      | 0       | 55     | 1798  | Table 67 | 
```