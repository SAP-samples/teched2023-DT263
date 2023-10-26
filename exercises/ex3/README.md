# Exercise 3 - Create Situation Template

## Exercise 3.1 - Provide General Information for Situation Template

1. Open the Manage Situation Types - Extended (F5437) app.

![Alt text](/exercises/ex3/images/mst_ext.png)

2. Click on 'Create->Create Situation Template' button on list page. Enter/choose below details

<br>• ID : 'PENDING_RESOURCE_ASSIGNMENT_XX'(replace XX with you initial Ex. Michael Jack : PENDING_RESOURCE_ASSIGNMENT_MJ).
<br>• Name: 'Pending Resource Assignment'.
<br>• Description: 'Inform project managers about project demands without assigned resources'.
<br>• Situation Scenario: 'YY1_PROJECT_DEMAND_STATUS_XX' (Scenario that was created in exercise 2).
3. Click on 'Create' button on pop-up.

![Alt text](/exercises/ex3/images/create_tmpl_pop_up.png)

## Exercise 3.2 - Add Situaton Trigger(Batch Based)
1. Click on 'Situation Triggers->Batch-Based Triggers' tab.
2. Click on 'Add'.
3. Select 'Unstaffed effort' from pop-up

![Alt text](/exercises/ex3/images/sit_trig_add.png)

## Exercise 3.2.1 - Add Condition Details
1. Click on 'Conditions' tab.
2. Click on 'edit' under filters.
3. Click on value help of 'Assignment Status'.
4. Select 'equal to' from drop down and set value 'N'.
5. Click 'OK'

![Alt text](/exercises/ex3/images/cond_set.png)

<br>6. Enter value 'Pending resource assignment' in Filter Description.

![Alt text](/exercises/ex3/images/conditions.png)

## Exercise 3.2.2 - Add Situation Display
1. Click on 'Situation Display' tab.
2. Select first entry from radio button of first entry.
3. Click on 'Edit'.

![Alt text](/exercises/ex3/images/sit_display.png)

4. Enter/choose below details on Add Situation Display pop-up
<br>• Title : 'Unstaffed resources in project {Anchor.PROJECT}'.
<br>• Description: 'There are project demands pending staffing in work package {Anchor.PROJECTELEMENT}'.
<br>• Aggregation: 'Aggregate by Field'.
<br>• Field: 'PROJECTELEMENT'.
<br>• Notification Title: 'Unstaffed resources in project {Anchor.PROJECT}'.
<br>• Notification Text: 'There are {SITUATION.COUNT} project demands pending staffing in work package {Anchor.PROJECTELEMENT}'.
<br>• Public Text : 'Resources have not been staffed yet'.

5. Click on 'OK'.
6. Click on 'back'.

![Alt text](/exercises/ex3/images/sit_display_details.png)

## Exercise 3.3 - Add Recipients
1. Click on 'Recipients' tab.
2. Click on 'Add' under facet 'Responsibility Rules'
3. Choose 'Notify Project Manager' from pop-up.

![Alt text](/exercises/ex3/images/team_cat.png)

4. Click on 'Create' and Save Situation Template.

![Alt text](/exercises/ex3/images/save_st_tmpl.png)

You've now created situation template.

Continue to - [Exercise 4 - Create Situation Type  ](../ex4/README.md)







