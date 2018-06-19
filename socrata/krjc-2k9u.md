# ORLNGquestions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/orlngquestions-1ab1b) |
| Metadata | [Link](https://data.oregon.gov/api/views/krjc-2k9u) |
| Data: JSON | [100 Rows](https://data.oregon.gov/api/views/krjc-2k9u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.oregon.gov/api/views/krjc-2k9u/rows.csv?max_rows=100) |
| Host | data.oregon.gov |
| Id | krjc-2k9u |
| Name | ORLNGquestions |
| Created | 2013-10-11T17:09:19Z |
| Publication Date | 2013-10-11T18:37:00Z |

## Columns

```ls
| Included | Schema Type | Field Name   | Name         | Data Type | Render Type |
| ======== | =========== | ============ | ============ | ========= | =========== |
| No       | time        | :updated_at  | updated_at   | meta_data | meta_data   |
| Yes      | series tag  | first_name   | First name   | text      | text        |
| Yes      | series tag  | last_name    | Last name    | text      | text        |
| Yes      | series tag  | organization | Organization | text      | text        |
| Yes      | series tag  | state        | State        | text      | text        |
| Yes      | series tag  | question     | Question     | html      | html        |
| Yes      | series tag  | email        | Email        | email     | email       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:krjc-2k9u d:2013-11-14T16:02:08.000Z t:first_name=keyaho t:state=oregon t:last_name=rohlfs t:question="No LNG" m:row_number.krjc-2k9u=1

series e:krjc-2k9u d:2013-11-14T16:02:13.000Z t:first_name=keyaho t:state=oregon t:last_name=rohlfs t:question="No LNG" m:row_number.krjc-2k9u=2

series e:krjc-2k9u d:2013-12-31T06:15:45.000Z t:first_name=iiiuarjcxu t:organization=google t:email=lplzzwlvrb@wtbofl.com t:state=Italy t:last_name=iiiuarjcxu t:question="qbjqtebub, <a target=""_blank"" href=""http://www.yecpexkzec.com/"">gjerbzhuue</a> , [url=http://www.vcheedtxej.com/]kwisgjfnks[/url], http://www.fwzezqejrw.com/ gjerbzhuue" m:row_number.krjc-2k9u=3
```

## Meta Commands

```ls
metric m:row_number.krjc-2k9u p:long l:"Row Number"

entity e:krjc-2k9u l:ORLNGquestions t:url=https://data.oregon.gov/api/views/krjc-2k9u

property e:krjc-2k9u t:meta.view v:id=krjc-2k9u v:averageRating=0 v:name=ORLNGquestions

property e:krjc-2k9u t:meta.view.owner v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"

property e:krjc-2k9u t:meta.view.tableauthor v:id=7f2t-e4kt v:screenName="Mary-Frances Makichen" v:displayName="Mary-Frances Makichen"
```

## Top Records

```ls
| :updated_at | first_name         | last_name          | organization | state          | question                                                                                                        | email                 | 
| =========== | ================== | ================== | ============ | ============== | =============================================================================================================== | ===================== | 
| 1384444928  | keyaho             | rohlfs             |              | oregon         | No LNG                                                                                                          |                       | 
| 1384444933  | keyaho             | rohlfs             |              | oregon         | No LNG                                                                                                          |                       | 
| 1388470545  | iiiuarjcxu         | iiiuarjcxu         | google       | Italy          | qbjqtebub, gjerbzhuue , [url=http://www.vcheedtxej.com/]kwisgjfnks[/url], http://www.fwzezqejrw.com/ gjerbzhuue | lplzzwlvrb@wtbofl.com | 
| 1388490641  | oxlacxbmem         | oxlacxbmem         | google       | USA            | qyccjebub, vbmjallpdx , [url=http://www.snqkhvadzx.com/]gyllqbqzoz[/url], http://www.mqhutowdfp.com/ vbmjallpdx | pkdzsezzed@dsypbi.com | 
| 1388522783  | lkenfixesq         | lkenfixesq         | google       | Italy          | kmazeebub, deubectkom                                                                                           | anbhontgvc@thqihx.com | 
| 1388555264  | crgtkgeuct         | crgtkgeuct         | google       | United Kingdom | jyenpebub, http://www.bufflvhbgw.com/ onaiodjecg                                                                | yukfqugaea@xuotpw.com | 
| 1388576614  | vjapphmaxs         | vjapphmaxs         | google       | USA            | ufrwvebub, http://www.plxibtinxl.com/ etrnonjyxy                                                                | iocizoapdx@gexdzf.com | 
| 1388610295  | hopdjfajbo         | hopdjfajbo         | google       | Netherlands    | kqfgzebub, http://www.gqksshgncg.com/ tmeexrigiw                                                                | nzlnojvfdu@fkhvsg.com | 
| 1388724070  | qeduqzdtsx         | qeduqzdtsx         | google       | Switzerland    | ghxqtebub, ggcrxaeluf , [url=http://www.sswwlotqos.com/]wqrjfadupg[/url], http://www.bkdhuorrth.com/ ggcrxaeluf | ramrxkefdv@bqgjan.com | 
| 1394489345  | qDLjRnESLDsGKMDWjv | hfcbCSANWGModFuylN | kXUvSQDc     |                | valium pill valium side effects kidneys - valium tolerance                                                      |                       | 
```