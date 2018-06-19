# Clean Power Plan Feedback

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/clean-power-plan-feedback) |
| Metadata | [Link](https://data.wa.gov/api/views/387j-hdvk) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/387j-hdvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/387j-hdvk/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | 387j-hdvk |
| Name | Clean Power Plan Feedback |
| Category | Natural Resources & Environment |
| Tags | ecology, clean power |
| Created | 2015-08-25T20:42:52Z |
| Publication Date | 2016-02-04T23:55:39Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | name        | Name       | text      | text        |
| Yes      | series tag  | comment     | Comment    | html      | html        |
| Yes      | series tag  | attachment  | Attachment | document  | document    |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:387j-hdvk d:2015-09-01T13:41:44.000Z t:name="Test commen" t:comment="This is a test. Please delete." m:row_number.387j-hdvk=1

series e:387j-hdvk d:2015-09-04T15:04:39.000Z t:name="Stuart Simpson" t:comment="When and where is the next session where the pubic can participate?

Is there a schedule for the subsequent public involvement meetings?" m:row_number.387j-hdvk=2

series e:387j-hdvk d:2015-10-07T07:53:50.000Z t:name="Judy Bevington" t:comment="Clarify relation to the Clean Air Rule, please." m:row_number.387j-hdvk=3
```

## Meta Commands

```ls
metric m:row_number.387j-hdvk p:long l:"Row Number"

entity e:387j-hdvk l:"Clean Power Plan Feedback" t:url=https://data.wa.gov/api/views/387j-hdvk

property e:387j-hdvk t:meta.view v:id=387j-hdvk v:category="Natural Resources & Environment" v:averageRating=0 v:name="Clean Power Plan Feedback"

property e:387j-hdvk t:meta.view.owner v:id=us76-w9xc v:screenName="Tim Lewis" v:displayName="Tim Lewis"

property e:387j-hdvk t:meta.view.tableauthor v:id=us76-w9xc v:screenName="Tim Lewis" v:roleName=publisher v:displayName="Tim Lewis"
```

## Top Records

```ls
| :updated_at | name                        | comment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | attachment               | 
| =========== | =========================== | =================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ======================== | 
| 1441114904  | Test commen                 | This is a test. Please delete.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | [null, null, null, null] | 
| 1441379079  | Stuart Simpson              | When and where is the next session where the pubic can participate? Is there a schedule for the subsequent public involvement meetings?                                                                                                                                                                                                                                                                                                                                                                                                                                             | [null, null, null, null] | 
| 1444204430  | Judy Bevington              | Clarify relation to the Clean Air Rule, please.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null] | 
| 1444915224  | Gary Smith iba@isomedia.com | Recently a construction crew near my office hit a gas main while excavating. This was a large line and we cold here the roar of escaping natural gas (methane) for an hour or more. Since methane is 72 times potent as a greenhouse gas than is carbon dioxide and my estimate of the gas that escaped from this event was greater than 100,000 cubic feet or equivalent to 3500 metric tons of CO2 for this event alone. How often does this happen? What will be included in this plan to more quickly stop leaks like this? Who will be held responsible for a leak like this?? | [null, null, null, null] | 
| 1449241176  | Mike Ruby                   | mruby@envirometrics.com Would appreciate being added to the email list. Doesn't seem to be a way to do that on the Get Involved page. Thanks.                                                                                                                                                                                                                                                                                                                                                                                                                                       | [null, null, null, null] | 
| 1454412525  | Julia Criscuolo             | I am trying to find information on whether Washington has indicated how it will meet the CPP requirements (e.g. rate, mass, or mass + new approach). Also, has Washington decided whether it plans to request an extension until 2018 for SIP submittal? Thanks, Julia Criscuolo                                                                                                                                                                                                                                                                                                    | [null, null, null, null] | 
| 1454601219  | Test 2                      | Testing the new fields. Delete.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | [null, null, null, null] | 
| 1457202112  | acheter cialis              | prix cialis vente cialis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [null, null, null, null] | 
| 1457525185  | achat cialis                | vente cialis vente cialis commander cialis acheter cialis precio cialis comprar cialis generico cialis prezzo cialis                                                                                                                                                                                                                                                                                                                                                                                                                                                                | [null, null, null, null] | 
| 1459627331  | cialis                      | cialis acquistare cialis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | [null, null, null, null] | 
```