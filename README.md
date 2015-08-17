# SalesforceReportTypes

Series of custom report types with fields broken into sections to match the standard reports for increased usability.

Report Types include Enterprise Territory Management, Collaborative Forecasting, and Ideas so far.
SF Collaborative Forecasting reports include report types both qualtity and amount, quantity only, and amount only.

Each report type has a custom fields section for each object to move custom fields into.

##Report List##
###General###
Contacts (Contacts, Account)<br>
Contacts with/without Accounts (Contacts, Account)<br>
Contacts with/without Activities (Contacts, Account, Activities)<br>
Dashboards (Dashboard, Dashboard Components)<br>
Leads with/without Campaign & Member History (Lead, Campaign History, Campaign Member)<br>
Accounts with/without Activities (Account, Activities)<br>
Accounts with/without Assigned_Territories (Account, AccountTerritoryAssociation, Territory, Territory Type)
<br><br>
###Forecasting###
ForecastItems (Forecast Item, Item Owner) <br>
ForecastItems with/without Opportunity with/without Activities (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Activities)<br>
ForecastItems with/without Opportunity with/without Contact (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account, Contacts w/ Opp Contact Role)<br>
ForecastItems with/without Opportunity with/without Team(Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account, Opp Team Users)<br>
ForecastItemsWithOpportunityDetailsAmountQuantity (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account)<br>
ForecastItems with/without Opportunities w/ TM fields (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account)<br>
ForecastItems with/without Opportunities (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account)<br>
ForecastItems with/without Opportunity Splits (Forecast Item, Item Owner, Opportunity Split)<br>
ForecastItems with/without Opps with/without LineItemsAmtQty (Forecast Item, Item Owner, Opportunity, Opportunity Owner, Account, Opp Line Items)<br>
ForecastItems with/without Products (Forecast Items, Owner, Opp Products)<br>
ForecastItems with/without Products w/ PriceBook  (Forecast Items, Owner, Opp Product, Pice book, Product)
ForecastQuotas (Forecast Quota, Owner)<br>
ForecastQuotas with/without Opportunities  (Forecast Quota, Owner, Opportunity, Owner, Account)<br>
ForecastQuotas with/without Opportunities  with/without Products (Forecast Quota, Owmer, Opportunity, Owner, Opp Product)<br>
ForecastQuotas with/without Product (Forecast Quota, Ower, Product)<br><br>

###Ideas###
Ideas (Ideas)<br>
Ideas with/without Votes (Ideas, Votes)<br>
Ideas with/without Comments (Ideas, Comments)<br>

###Enterprise Territory Management###
Accounts with/without Territory (Account, AccountTerritoryAssociation, Territory, Territory Type, Territory User)<br>
Territories with/without Assigned_Records (Territory Model, Territory2, Territory Type)<br>
Territory Models with/without Territories Rules (Territory Model, Territory2, Territory Type with/without Territories (Territory Model, Territory2, Territory Type)<br>
Territory w/ Parent_GP_GGP_Territory_Details (Territory Model, Territory2, Territory Type, Territory2Parent, Territory2ParentParent, Territory2ParentParentParent)<br>
Territory  with/without Rules (Territory Model, Territory2, Territory2 Type, RuleItem)<br>
Territory w/ Parent_Territory (Territory Model, Territory, Territory Type, Territory2Parent)<br>
Territory with/without Users (Territory Model, Territory, Territory Type, Territory User)<br>
Territory with/without Users_Admin (Territory Model, Territory, Territory Type, Territory User)<br>
Users with/without Territories (User, Territory2, Territory Type)<br>
Users with/without Territories_Admin (User, Territory2, Territory Type)
