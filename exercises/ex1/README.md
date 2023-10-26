# Exercise 1 - Create Situation Object

## Exercise 1.1 - Provide General Information for Situation Object

1. Open the Manage Situation Objects (F5609) app.

![Alt text](/exercises/ex1/images/mso_app.png)

2. Click on 'Create' button on list page.Enter Object ID as 'PROJECT_DEMAND_XX'(replace XX with you initial Ex. Michael Jack : PROJECT_DEMAND_MJ). Click on 'Create' button on pop-up.

![Alt text](/exercises/ex1/images/obj_cre_pop_up.png)

3.	On the General Information tab, enter/choose the following information:

<br>•	Name : 'PROJECT_DEMAND_XX'  (replace XX with you initial Ex. Michael Jack : PROJECT_DEMAND_XX).
<br>•	SAP Object Type : 'Project Demand (ProjectDemand)'

![Alt text](/exercises/ex1/images/obj_details.png)

## Summary
You've now entered object general information

## Exercise 1.2 - Provide Structure Information 

1. Click on Structure tab and click on create. Enter Structure ID 'PROJECT_DEMAND_CDS'.

<br>![](/exercises/ex1/images/stru_pop_up.png)

2.	On the General Information tab, enter/choose the following information:

<br>•	Structure Type : 'CDS'
<br>•	Structure Name : 'Z_I_PROJDMNDRSCEASSGMTDI'
<br>•	Description : 'Project Demand'
<br>•	SAP Object Node Type : 'Demand Resource Assignment (DemandResourceAssignment)'

<br>![](/exercises/ex1/images/stru_details.png)


## Exercise 1.2.1 - Create Semantic Key

1. Click on Semantic Key tab and click on create. From the pop-up select below values and click 'OK' button. 

<br>•	PROJECTDEMANDUUID

<br>![](/exercises/ex1/images/semantic_key.png)

2. Click on back 

<br>![](/exercises/ex1/images/stru_back.png)

## Summary
You've now created structure.

## Exercise 1.3 - Provide Navigation Target Information 

1. Click on Navigation Target tab and click on 'Create'. Enter Navigation ID 'PROJECT_DEMAND_NAV_01'.

<br>![](/exercises/ex1/images/nav_target_pop_up.png)

2.	On the General Information tab, enter the following information:

<br>•	Semantic Object : 'ProfessionalServicesProject'
<br>•	Semantic Object Action : 'displayFactsheet'

<br>![](/exercises/ex1/images/nav_tar_details.png)

2.	Click on 'back'.

## Summary
You've now created navigation target.

## Exercise 1.4 - Provide End-User Action Information 

1. Click on End-User Action tab and click on create. Enter Action ID 'PROJECT_DEMAND_ACT_01'.

<br>![](/exercises/ex1/images/end_user_act_pop_up.png)

2.	On the General Information tab, enter/choose the following information:

<br>•	Action Type : 'Navigation Action'
<br>•	Button Name : 'Project Control - Prof. Services Project'
<br>•	Button Description : 'Display projects and manage resource staffing'
<br>•	Navigation ID : 'PROJECT_DEMAND_NAV_01'

<br>![](/exercises/ex1/images/end_user_act_details.png)

3.	Click on'back'.

4. Click on 'Create'.

<br>![](/exercises/ex1/images/cre_obj.png)

## Summary

You've now created navigation target and situation object.

Continue to - [Exercise 2 - Create Situation Scenario  ](../ex2/README.md)




