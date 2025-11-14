This document outlines general process regarding estimation within the Engineering Department

# 1.Task Handling

Sales representatives can utilize the Engineering Department to create estimations for bid projects. When engaged for these tasks, the main tool for tracking the tasks is Q360. 

# Task Logging

The **Comments** section of the Engineering/Estimation funnel item (and other funnel items) should be used to add **(logs)** for documentation of things that have occurred durring the process of the estimation request. Logs should include:
- current short date
- short name of person making the log
- information regarding the log entry

# Time billing
time spent working on the task should be billed to the opportunity. Notes regarding what was worked on durring the timebill are encouraged but not expressly required.

# Sales Request of Estimation Task

- Sales representative creates the Opp (Most details for this is outside the scope of the engineering department)
- Sales rep to make sure the follwing items are set properly on the Engineering/Estimation task.
    - Set **Assignee** to be the engineering manager.
    - Set **Scheduled Start Date** to be the time it should show in the engineering manager's task list.
    - Set **Scheduled End Date** to be the time they are expecting the estimation to be returned to them for review.
    - Set **Status** to be **DEMAND**
    - Populate **Comments** accordingly
        - The first text in this field needs to be populated by the sales representative. 
        - This text needs to explain what it is the sales representative wants the engineering department to do. This should be rather short.
        - For tasks that require more detail, reference to external documents should be used. 
            - location of referred documents should always be detailed. Default location is Opp Documents attachments in Q360.
        - This text is what the engineering manager will use to evaluate if the task has been complete. 
            - If this text does not accurately reflect the desired task or this text is not provided, then there is nothing to evaluate.
            - If this text is unclear, the engineering manager needs to reach out to the sales representative for clarification which will delay the process and cause confusion.

# Engineering Manager Assignment

- When the engineering manager receives the request (shows up in taks list) he will review the task details and if everything checks out, he will assign the task to a capable, available member of the engineering department.
- The engineering manager should get the assignment made within 24 hours of receiving the request.
- To assign an engineering team member to the task, the engineering manager does the following:
    - Sets the **Assignee** of the Engineering/Estimation funnel item to the assigned engineering team member.
    - Sends a teams message to the assigned engineering team member letting them know they have a new opp task assignment.
        - Message will include the **Opportunity No.** and the **Opp Title**.
    - Append text to **Comments** to document assignment
- When tasked with doing an estimate, the engineering manager will set the assigned engineering team member as the assignee of the Engineering/Estimation funnel item.
    - This will cause the Opp task to show in the assignee's task list.
    - The scheduled end date field will show when the estimation is due to be completed.
    - The Comments on the Engineering/Estimation funnel item should contain directive of the task.
        - This will also contain manually added log items regarding the estimation.

# Estimation Task Completion Process

- Initial Evaluation
    - Estimator should start by evaluating the task.
        - Verify that due date is possible
        - Verify that directive (**Comments** of Engineering/Estimation funnel item) Make sense and are achievable.
        - Verify that the documents required are available and are referrenced in the **Comments**.
        - If any these things do not check out, reach out to **Sales Representative** to resolve or direct to resolution immediately. 
            - If **Sales Representative** is not responsive, forward issue to **Engineering Manager**
        - Once the task passes the evaluation, the estimation can begin.
- Create entity for the estimation in Pro-Est
    - Login to Pro-Est, then go to the Estimation Center on the left navigation bar.
    - Click **Add new estimate** button on the top bar.
    - Set **Description** to be Opportunity Number | Opportunity Title
        - Example: 90536127 | Utah Air National Guard Kitchen and Auditorium AV
    - Set **Estimation Type** to match vertical market or other as applicable.
    - Set **Estimate Status** to be **Active (Estimation)**
    - Set **Due Date** to match Engineering/Estimation funnel item
    - Set **Office** to match office that is doing estimation
    - Click **Save** to create the estimate
- Review Project
    - Review task and project documents to develop an understanding of the project and what is being asked to do with the project.
- Create Drawings and/or Specifications subset(s) if applicable
    - Include **ALL** applicable AV drawings and spec sheets
        - Can use microsoft print to PDF to do this.
            - This can take some time to do.
            - Make sure to check the **Choose paper source by PDF page size** option.
            - Be careful to make sure it prints in proper orientation
    - Set name of file(s) to be OP# AV Only Drawings/Specifications
    - Add new files to documents of the Opp
        - Set **Category** to **DESIGN** and **Sub Category** to **DRAWING** or **PROJ SPEC**
- Add Drawings to Pro-Est
    - Go to **Documents** in ProEst
    - Click **Add New File**
        - Select file
    - Set **Type** 
    - Click 💾 on the record for the drawings (right side)
- Set **Sort Types**
    - Goto **Sort Types** in estimate    
    - Set Systems
        - Expand **Systems** header
        - Click **Add New Value** to add entries for all systems to be included in the bid
            - This should match the design drawings 1:1, unless very good reason to deviate
    - Set Area/Phases
        - Expand **Area/Phase** header
        - Click Add New Value to add entries for all areas/phases that are part of the project.
            - This is a bit of a dynamic parameter that varies intent from project to project.
                - Depending on the project, this could be used to group items together in areas like 1A (Area A on the first floor) or could be used to track items between phases like Phase 1 (maybe done 2025) and Phase 2 (maybe done 2026).
            - At a minimum, there should be a phase for the floor of the building that the system will be installed within.
- Do TakeOffs for estimate
    - Click to **TakeOff** section
    - Add items to takeoff "Pallett"
        - On top of screen, click into and type item information
        - If item exists in db, select it from the popup to add
    - Modify properties
        - on "Item Pallett" hover over the item and click **Properties**
        - Add **Sort Types** as needed including, but not limited to: Type, Followup, System, Area/Phase
        [Todo] Add details for each of these properties intents.
        - Click **Save**
    - Add items to db that don't exist
        - make sure items exist in Q360 before adding
        - if they do not, contact db admin (Linzee) to add
        - go to database on sidebar of ProEst
        - locate and manufacturer folder
        - if applicable, open category subfolder
        - click **Add New Item**
        - Add **Description**
            - Set to be *Q360 Master Number* | *Description from Q360*
        - Set Part#
            - Under Cost -> Material
                -Set Part# Column to match **Q360 Master Number EXACTLY**
        - Set **Unit** to **EA**
        - Set **Sort Types**
            - At minimum, set **Type**
            - Set others as applicable
        


# Estimate Notes
Durring Estimate, take notes of any deviations, followups, ect.
- Create note "Container" in OneNote
    - In Q360 Cloud OneNote, create **New Page** Under **Estimates** section
    - Set Page tile to match exactly the Estimate Title in ProEst Ex: (90536127 | Utah Air National Guard Kitchen and Auditorium AV)

# Estimate Drawings
Durring Estimate, track progress, deviations and other things on another set of the drawings.
- Suggest using AutoDesk Design Review for simplicity but this is software agnostic as long as the end result is a set of drawings that illustrates what was done on the estimate.
- Drawings should be understandable to other team members
    - For example, if you mark on the drawings with a green higlighter items that have been added to the pallett, include that "key" description in the drawings.


        
    



    



    









        
