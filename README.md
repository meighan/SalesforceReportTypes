# Salesforce Report Types
<a href="https://githubsfdeploy.herokuapp.com?owner=meighan&repo=SalesforceReportTypes">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/src/main/webapp/resources/img/deploy.png">
</a>
<br>
Series of custom report types with fields broken into sections to match the standard reports for increased usability.

Report Types include Enterprise Territory Management, Collaborative Forecasting, and Ideas so far.
SF Collaborative Forecasting reports include report types both quantity and amount, quantity only, and amount only.

Each report type has a custom fields section for each object to move custom fields into.

##Report List
###General

|**Report**|**Objects**|
|---------|----------|
|Contacts | Contacts, Account|
|Contacts w/ w/o Accounts | Contacts, Account|
|Contacts w/ w/o Activities | Contacts, Account, Activities |
|Dashboards | Dashboard, Dashboard Components |
|Leads w/ w/o Campaign & Member History | Lead, Campaign History, Campaign Member |
|Accounts w/ w/o Activities | Account, Activities |
|Accounts w/ w/o Assigned_Territories | Account, AccountTerritoryAssociation, Territory, Terr Type)

###Forecasting
You can [install the unmanaged package](https://test.salesforce.com/packaging/installPackage.apexp?p0=04t1a0000001vyN) into your sandbox using the app link.  

|**Report**|**Objects**|
|----------|------------|
|Items | Forecast Item, Item Owner |
|Items w/ Opp/ w/o Activities | Forecast Item, Item Owner, Opportunity, Opp Owner, Activities |
|Items w/ Opp/ w/o Contact |Forecast Item, Item Owner, Opportunity, Opp Owner, Account, Contacts w/ Opp Contact Role |
|Items w/ Opp/ w/o Team |Forecast Item, Item Owner, Opportunity, Opp Owner, Account, Opp Team Users |
|Items w/ Opp Details Amt&Qty |Forecast Item, Item Owner, Opportunity, Opp Owner, Account|
|Items w/ Opp w/ TM fields |Forecast Item, Item Owner, Opportunity, Opp Owner, Account|
|Items w/ Opp |Forecast Item, Item Owner, Opportunity, Opp Owner, Account|
|Items w/ w/o Opportunity Splits |Forecast Item, Item Owner, Opportunity Split |
|Items w/ Opp w/ w/o Line Items |Forecast Item, Item Owner, Opportunity, Opp Owner, Account, Opp Line Items |
|Items w/ w/o Products |Items, Owner, Opp Products |
|Items w/ w/o Products w/ Price Book|Items, Owner, Opp Product, Price book, Product |
|Quotas |Forecast Quota, Owner |
|Quotas w/ w/o Opportunities  |Forecast Quota, Owner, Opportunity, Owner, Account|
|Quotas w/ w/o Opportunities  w/ w/o Products |Forecast Quota, Owner, Opportunity, Owner, Opp Product |
|Quotas w/ w/o Product |Forecast Quota, Owner, Product |
Items = Items
Quotas = Forecast Quotas

###Ideas

|**Report**|**Objects**|
|----------|-----------|
|Ideas | Ideas |
|Ideas w/ w/o Votes | Ideas, Votes |
|Ideas w/ w/o Comments | Ideas, Comments |

###Enterprise Territory Management

|**Report**|**Objects**|
|----------|-----------|
|Accounts w/w/o Territories | Account, AcctTerritoryAssociation, Territory, Terr Type, Territory Users |
|Territories w/ w/o Assigned_Records  | Model, Territory, Terr Type |
|Territory Models w/ w/o Territories Rules | Model, Territory, Terr Type w/ w/o Territories Model, Territory, Terr Type |
|Territory w/ Parent_GP GGP Details | Model, Territory, Terr Type, Terr. Parent, Terr ParentParent, Territory Parent's Parent's Parent |
|Territory  w/ w/o Rules | Model, Territory, Terr Type, RuleItem|
|Territory w/ Parent | Model, Territory, Terr Type, Terr Parent |
|Territory w/ w/o Users | Model, Territory, Terr Type, Territory User |
|Territory w/ w/o Users_Admin | Model, Territory, Terr Type, Territory User |
|Users w/ w/o Territories | User, Territory, Terr Type |
|Users w/ w/o Territories Admin | User, Territory, Terr Type |
Model = Territory Model
