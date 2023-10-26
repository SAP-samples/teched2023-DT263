# Exercise 2 - Create Situation Scenario

## Exercise 2.1 - Provide General Information for Situation Scenario

1. Open the Manage Situation Scenario (F5698) app.

![Alt text](/exercises/ex2/images/mss.png)

2. Click on 'Create' button on list page. Enter/choose below details
<br>• ID : 'PROJECT_DEMAND_STATUS_XX'(replace XX with you initial Ex. Michael Jack : PROJECT_DEMAND_STATUS_MK).
<br>• Type: 'Object-Based'.
<br>• Object Structure Type: 'CDS'.

3. Click on 'Create' button on pop-up.

![Alt text](/exercises/ex2/images/create_pop_up.png)

3.	On the General Information tab, enter/choose the following information:

<br>• Scenario Name : 'PROJECT_DEMAND_STATUS_XX'  (replace XX with you initial Ex. Michael Jack : YY1_CC_BUDGET_MK).
<br>• Scenario Description : 'Project Demand Status'
<br>• Responsibility Context ID : 'YY1_PROJMGMT_CONTEXT_2'

![Alt text](/exercises/ex2/images/mss_header.png)

## Summary
You've now entered scenario general information

## Exercise 2.2 - Provide Anchor Object Information

1. On Anchor Object, enter/choose the following information:

<br>• Anchor Object ID : 'YY1_PROJECT_DEMAND_XX'(ID that was created in Manage Situation Object App in excerise 1)
<br>• Anchor Object Structure ID : 'PROJECT_DEMAND_CDS'
<br>• Anchor Object Key Field : 'PROJECTDEMANDUUID'

![Alt text](/exercises/ex2/images/anch_obj.png)

## Summary
You've now entered anchor object information

## Exercise 2.3 - Add Instance Key

<br>1. Click on 'Add' button
<br>2. Choose 'PROJECTDEMANDUUID' from pop-up
<br>3. Click 'OK'

![Alt text](/exercises/ex2/images/instance_key.png)

## Summary
You've now added instance key

## Exercise 2.4 - Add Situation Triggers and Enter General Information for Situation Trigger

<br>1. Click on 'Situation Triggers' tab
<br>2. Click on 'Add' button
<br>3. Enter General Information for Situation Trigger
<br>• Name : 'Unstaffed effort'
<br>• Description : 'Identify project demands for which staffing is not confirmed'
<br>• Trigger Type : 'Batch'

![Alt text](/exercises/ex2/images/trigger_header.png)

## Summary
You've now added situation trigger and provided general information

## Exercise 2.5 - Provide Trigger Object Information

On the Trigger Object Information, enter/choose the following information:

<br>• Trigger Object ID : 'YY1_PROJECT_DEMAND_XX' (ID that was created in Manage Situation Object App in excerise 1)
<br>• Trigger Object Structure ID : 'PROJECT_DEMAND_CDS'
<br>• Trigger Object Key Field : 'PROJECTDEMANDUUID'
<br>• Trigger Object Behavior : 'Add/Update'

![Alt text](/exercises/ex2/images/trigg_obj_detaails.png)

## Summary
You've now added Trigger object information

## Exercise 2.6.1- Add Situation Page Layout(Anchor Object)

<br>1. Click on 'Add' button
<br>2. Enter/choose the following information

<br>• Section Source : 'Anchor Object' 
<br>• Subsections : 'No'
<br>• Section Label : 'Work Package'
<br>• Maximum Field Length : '100'

<br>3. • Click on '>' button

![Alt text](/exercises/ex2/images/sit_page_layout_anch.png)


## Exercise 2.6.2 - Add Section Fields(Anchor)
<br>1. Click on 'Add' button
<br>2. Enter/choose the following information

<br>• PROJECTELEMENT
<br>• PROJECTELEMENTDESCRIPTION
<br>• PROJECTDEMANDSTARTDATE
<br>• PROJECTDEMANDENDDATE

![Alt text](/exercises/ex2/images/sec_fields_anch.png)

<br>3. Click on'back'.

## Exercise 2.6.3 - Add Situation Page Layout(Trigger Object)

<br>1. Click on 'Add' button
<br>2. Enter/choose the following information

<br>• Section Source : 'Anchor Object' 
<br>• Subsections : 'No'
<br>• Section Label : 'Work Package'
<br>• Maximum Field Length : '100'

<br>3. • Click on '>' button

![Alt text](/exercises/ex2/images/sit_page_layout_trig.png)


## Exercise 2.6.1 - Add Section Fields
<br>1. Click on 'Add' button
<br>2. Enter/choose the following information

<br>• ACTIVITYTYPE
<br>• PROJDMNDREQUESTEDDELIVERYORG
<br>• PROJECTELEMENTWORKITEM
<br>• PROJDMNDRSCEASSGMTDISTRQTY
<br>• PROJDMNDRSCEASSGMTDISTRQTYUNIT
<br>• PROJDMNDRSCEDISTRPERDAMT
<br>• PROJDMNDRSCEDISTRREVENUEAMT
<br>• PROJDMNDRSCEDISTRREVENUEAMTCUR
<br>• PROJDMNDBILLINGCONTROLCATEGORY


![Alt text](/exercises/ex2/images/sec_fields_trig.png)

<br>3. Click on'back'.

## Exercise 2.7 - Add Actions
<br>1. Click on 'Add' button
<br>2. Select 'PROJECT_DEMAND_ACT_01' from pop-up
<br>3. Click 'OK'

![Alt text](/exercises/ex2/images/act_pop_up.png)

## Exercise 2.8 - Save Scenario
<br>1. Click on'back'.
<br>2. Click on 'Create'

![Alt text](/exercises/ex2/images/save_sce.png)

You've now created situation scenario.

Continue to - [Exercise 3 - Create Situation Template  ](../ex3/README.md)
