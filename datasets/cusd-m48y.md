# Utility Payment Methods

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/utility-payment-methods) |
| Metadata | [Link](https://data.austintexas.gov/api/views/cusd-m48y) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/cusd-m48y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/cusd-m48y/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | cusd-m48y |
| Name | Utility Payment Methods |
| Attribution | City of Austin |
| Category | Financial |
| Created | 2011-12-16T13:45:46Z |
| Publication Date | 2016-11-14T15:31:51Z |

## Description

Austin Energy provides various payment options for our customers? convenience. View the percentage of customers using each payment method. Visit austinenergy.com/go/paymentoptions to learn more about the bill payment options.

## Columns

```ls
| Included | Schema Type    | Field Name                                                                            | Name                                                                                       | Data Type     | Render Type   |
| ======== | ============== | ===================================================================================== | ========================================================================================== | ============= | ============= |
| Yes      | time           | fiscal_year                                                                           | Fiscal Year                                                                                | calendar_date | calendar_date |
| Yes      | numeric metric | authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_ | Authorized Pay Stations via Western Union (ex. ACE cash Express, HEB, Money Box, Randalls) | percent       | percent       |
| Yes      | numeric metric | online_banking_via_customers_bank_                                                    | Online Banking (via customers bank)                                                        | percent       | percent       |
| Yes      | numeric metric | bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_                  | Bill Matrix (via phone or Austin Energy Website) (credit, debit, e-check)                  | percent       | percent       |
| Yes      | numeric metric | austin_energy_website_registered_with_online_customer_care_e_check_                   | Austin Energy Website (registered with Online Customer Care) (e-check)                     | percent       | percent       |
| Yes      | numeric metric | electronic_fund_transfer_draft_by_ae_                                                 | Electronic Fund Transfer (draft by AE)                                                     | percent       | percent       |
| Yes      | numeric metric | misc_ex_collections_irs_                                                              | Misc. (ex. Collections, IRS)                                                               | percent       | percent       |
| Yes      | numeric metric | walk_in_payment_centers                                                               | Walk-in Payment Centers                                                                    | percent       | percent       |
| Yes      | numeric metric | mail                                                                                  | Mail                                                                                       | percent       | percent       |
| Yes      | numeric metric | manual_payments                                                                       | % Manual Payments                                                                          | percent       | percent       |
| Yes      | numeric metric | electronic_payments                                                                   | % Electronic Payments                                                                      | percent       | percent       |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:cusd-m48y d:2016-01-01T00:00:00.000Z m:mail=19.01 m:authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_=9.56 m:misc_ex_collections_irs_=0.09 m:online_banking_via_customers_bank_=17.05 m:electronic_fund_transfer_draft_by_ae_=19.73 m:bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_=6.61 m:manual_payments=22.69 m:electronic_payments=77.31 m:walk_in_payment_centers=3.68 m:austin_energy_website_registered_with_online_customer_care_e_check_=24.27

series e:cusd-m48y d:2015-01-01T00:00:00.000Z m:mail=21.24 m:authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_=10.74 m:misc_ex_collections_irs_=0.11 m:online_banking_via_customers_bank_=19.14 m:electronic_fund_transfer_draft_by_ae_=15.72 m:bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_=6.64 m:manual_payments=25.01 m:electronic_payments=74.99 m:walk_in_payment_centers=3.77 m:austin_energy_website_registered_with_online_customer_care_e_check_=22.64

series e:cusd-m48y d:2014-01-01T00:00:00.000Z m:mail=24.11 m:authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_=11.56 m:misc_ex_collections_irs_=0.03 m:online_banking_via_customers_bank_=19.92 m:electronic_fund_transfer_draft_by_ae_=12.72 m:bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_=5.42 m:manual_payments=27.45 m:electronic_payments=72.55 m:walk_in_payment_centers=3.34 m:austin_energy_website_registered_with_online_customer_care_e_check_=22.9
```

## Meta Commands

```ls
metric m:authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_ p:float l:"Authorized Pay Stations via Western Union (ex. ACE cash Express, HEB, Money Box, Randalls)" t:dataTypeName=percent

metric m:online_banking_via_customers_bank_ p:float l:"Online Banking (via customers bank)" t:dataTypeName=percent

metric m:bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_ p:float l:"Bill Matrix (via phone or Austin Energy Website) (credit, debit, e-check)" t:dataTypeName=percent

metric m:austin_energy_website_registered_with_online_customer_care_e_check_ p:float l:"Austin Energy Website (registered with Online Customer Care) (e-check)" t:dataTypeName=percent

metric m:electronic_fund_transfer_draft_by_ae_ p:float l:"Electronic Fund Transfer (draft by AE)" t:dataTypeName=percent

metric m:misc_ex_collections_irs_ p:float l:"Misc. (ex. Collections, IRS)" t:dataTypeName=percent

metric m:walk_in_payment_centers p:float l:"Walk-in Payment Centers" t:dataTypeName=percent

metric m:mail p:float l:Mail t:dataTypeName=percent

metric m:manual_payments p:float l:"% Manual Payments" t:dataTypeName=percent

metric m:electronic_payments p:float l:"% Electronic Payments" t:dataTypeName=percent

entity e:cusd-m48y l:"Utility Payment Methods" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/cusd-m48y

property e:cusd-m48y t:meta.view v:id=cusd-m48y v:category=Financial v:averageRating=0 v:name="Utility Payment Methods" v:attribution="City of Austin"

property e:cusd-m48y t:meta.view.owner v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:displayName="Shannon Wisner"

property e:cusd-m48y t:meta.view.tableauthor v:id=fxfz-wsmq v:profileImageUrlMedium=/api/users/fxfz-wsmq/profile_images/THUMB v:profileImageUrlLarge=/api/users/fxfz-wsmq/profile_images/LARGE v:screenName="Shannon Wisner" v:profileImageUrlSmall=/api/users/fxfz-wsmq/profile_images/TINY v:roleName=publisher v:displayName="Shannon Wisner"
```

## Top Records

```ls
| fiscal_year         | authorized_pay_stations_via_western_union_ex_ace_cash_express_heb_money_box_randalls_ | online_banking_via_customers_bank_ | bill_matrix_via_phone_or_austin_energy_website_credit_debit_e_check_ | austin_energy_website_registered_with_online_customer_care_e_check_ | electronic_fund_transfer_draft_by_ae_ | misc_ex_collections_irs_ | walk_in_payment_centers | mail  | manual_payments | electronic_payments | 
| =================== | ===================================================================================== | ================================== | ==================================================================== | =================================================================== | ===================================== | ======================== | ======================= | ===== | =============== | =================== | 
| 2016-01-01T00:00:00 | 9.56                                                                                  | 17.05                              | 6.61                                                                 | 24.27                                                               | 19.73                                 | 0.09                     | 3.68                    | 19.01 | 22.69           | 77.31               | 
| 2015-01-01T00:00:00 | 10.74                                                                                 | 19.14                              | 6.64                                                                 | 22.64                                                               | 15.72                                 | 0.11                     | 3.77                    | 21.24 | 25.01           | 74.99               | 
| 2014-01-01T00:00:00 | 11.56                                                                                 | 19.92                              | 5.42                                                                 | 22.90                                                               | 12.72                                 | 0.03                     | 3.34                    | 24.11 | 27.45           | 72.55               | 
| 2013-01-01T00:00:00 | 12.24                                                                                 | 22.01                              | 4.34                                                                 | 19.80                                                               | 11.72                                 | 0.01                     | 2.63                    | 27.25 | 29.59           | 70.41               | 
| 2012-01-01T00:00:00 | 10.94                                                                                 | 18.16                              | 3.87                                                                 | 11.59                                                               | 8.27                                  | 0.27                     | 2.02                    | 44.88 | 46.90           | 53.10               | 
| 2011-01-01T00:00:00 | 4.78                                                                                  | 22.26                              | 13.21                                                                | 14.29                                                               | 6.60                                  | 0.36                     | 2.73                    | 35.77 | 38.50           | 61.50               | 
| 2010-01-01T00:00:00 | 13.05                                                                                 | 16.87                              | 4.79                                                                 | 9.59                                                                | 5.54                                  | 0.32                     | 1.24                    | 48.59 | 49.83           | 50.17               | 
| 2009-01-01T00:00:00 | 12.83                                                                                 | 15.26                              | 4.24                                                                 | 7.94                                                                | 4.60                                  | 0.34                     | 1.36                    | 53.43 | 54.79           | 45.21               | 
| 2008-01-01T00:00:00 | 12.57                                                                                 | 13.90                              | 3.89                                                                 | 5.82                                                                | 4.21                                  | 0.34                     | 1.38                    | 57.89 | 59.27           | 40.73               | 
| 2007-01-01T00:00:00 | 11.99                                                                                 | 12.25                              | 3.47                                                                 | 3.37                                                                | 3.76                                  | 0.41                     | 1.36                    | 63.40 | 64.76           | 35.24               | 
```