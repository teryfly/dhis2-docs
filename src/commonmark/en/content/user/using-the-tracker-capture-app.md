# Using the Tracker Capture app

<!--DHIS2-SECTION-ID:tracker_capture_app-->

## About the Tracker Capture app

<!--DHIS2-SECTION-ID:about_tracker_capture_app-->

![](resources/images/tracker_capture/tracker-capture-tei-list.png)

The **Tracker Capture** app is an advanced version of the **Event
Capture** app.

  - **Event Capture**: handles single events *without* registration

  - **Tracker Capture**: handles multiple events (including single
    event) *with* registration.

  - You capture event data for a registered tracked entity instance
    (TEI).

  - You only see programs associated with the organisation unit you've
    selected and programs you've access to view through your user role.

  - The options you see in the search and register functions depend on
    the program you've selected. The program attributes control these
    options. The attributes also decide the columns names in the TEI
    list.
    
    If you don't select a program, the system picks default attributes.

  - Both skip-logic and validation error/warning messages are supported
    during registration.

  - When you close an organisation unit, you can't register or edit
    events to this organisation unit in the **Tracker Capture** app. You
    can still search for TEIs and filter the search results. You can
    also view the dashboard of a particular TEI.

## About tracked entity instance (TEI) dashboards

<!--DHIS2-SECTION-ID:about_tracked_entity_instance_dashboard-->

![](resources/images/tracker_capture/tei_dashboard.png)

You manage a TEI from the TEI's dashboard in the **Tracker Capture**app.

  - The dashboard consist of widgets. Drag and drop the widgets to place
    them in the order and in the position you want.

  - Click the pin icon to stick the right column of widgets to a fix
    position. This is useful especially during data entry.
    
    If you have many data elements or big form to fill in, stick the
    right widget column. Then all the widgets you've placed in the right
    column remain visible while you scroll in the data entry part.

  - Any indicator defined for the program you've selected will have its
    value calculated and displayed in the **Indicators** widget.

  - Navigation:
    
      - **Back**: takes you back to the search and registration page
    
      - Previous and next buttons: takes you to the previous or next TEI
        dashboard in the TEI search results list
    
    <!-- end list -->
    
      - **Other programs** field: if the TEI is enrolled in other
        programs, they're listed here. Click a program to change the
        program for which you enter data for the selected TEI. When you
        change programs, the content in the widgets change too.

## Workflow

<!--DHIS2-SECTION-ID:workflow_tracker_capture-->

Working process of Mother and child health
program

![](resources/images/patients_programs/name_based_information_tracking_process.png)

1.  Create new or find existing TEI.
    
    You can search on defined attributes, for example name or address.

2.  Enroll TEI in a program.

3.  Based on the services of the program by the time, the app creates an
    activity plan for the TEI.

4.  The TEI is provided with various services depending on the program.
    All services are recorded.

5.  Use information about the individual cases to create reports.

## Create a TEI

<!--DHIS2-SECTION-ID:create_tracked_entity_instance-->

1.  Open the **Tracker Capture** app.

2.  In the organisation unit tree in the left hand pane, select an
    organisation unit.

3.  Verify that the **Program** field is empty.

4.  Click **Register**.

5.  Select an entity type.

6.  Fill in the required information.

7.  Click **Save and continue** or **Save and add new**.
    
      - **Save and continue**: completes the registration and opens the
        registered TEI's dashboard
    
      - **Save and add new**: completes the registration but stays on
        the same page. Use this option when you want to register one TEI
        after another without enrollment to a program.

> **Note**
> 
> For unique tracked entity attributes the system can automatically
> generate and assign numeric IDs. When registering tracked entity
> instances on web, the registration form will then automatically be
> populated with a number in the given pattern. On Android, the ID
> generation is used to reserve a series of IDs for each Android device.
> This allows offline registration of tracked entity instances without
> risking duplicate IDs when syncing with the server.
> 
> You configure automated IDs in the **Maintenance** app: **Tracker** \>
> **Tracked entity attribute**.

## Create a TEI and enroll it in a program

<!--DHIS2-SECTION-ID:create_and_enroll_tracked_entity_instance-->

You can create a TEI and enroll that TEI to a program in one operation:

1.  Open the **Tracker Capture** app.

2.  In the organisation unit tree in the left hand pane, select an
    organisation unit.

3.  Select a program.

4.  Click **Register**.

5.  Fill in the required information.

6.  Click **Save and continue** or **Save and add new**.
    
      - **Save and continue**: completes the registration and opens the
        registered TEI's dashboard
    
      - **Save and add new**: completes the registration but stays on
        the same page. Use this option when you want to register and
        enroll one TEI after another without enter data.

## Open an existing TEI dashboard

<!--DHIS2-SECTION-ID:open_existing_tracked_entity_instance_dashboard-->

There are two ways to find a TEI: simple and advanced search. You can
also modify the search results list's layout and download the search
results list in several formats.

![](resources/images/tracker_capture/search_register.png)

### Simple TEI search

<!--DHIS2-SECTION-ID:simple_tracked_entity_instance_search-->

1.  Open the **Tracker Capture** app.

2.  (Optional) In the organisation unit tree in the left hand pane,
    select an organisation unit, then a program.

3.  In the right hand search field, type your search criteria.
    
    The search criteria could for example be a last name. You can search
    on all TEI attributes.

4.  Click the **Search** icon.
    
    A list of TEIs that match your search criteria displays.

5.  If you have selected a program, you can filter the search results
    based on enrollment status:
    
      - **Only those with active enrollment**
    
      - **Only those with completed enrollment**
    
      - **Only those with cancelled enrollment**

6.  Click a TEI.
    
    The TEI dashboard opens.

### Advanced TEI search

<!--DHIS2-SECTION-ID:advanced_tracked_entity_instance_search-->

Advanced search is conducted for the organisation units you select in
the organisation tree inside the **Advanced search** window. The
left-hand side organisation tree is generated based on your assigned
organisation units. So in the **Advanced search** window you can select
organisation units outside your own organisation unit.

1.  Open the **Tracker Capture** app.

2.  (Optional) In the organisation unit tree in the left hand pane,
    select an organisation unit, then a program.
    
    If a program is selected, advanced search allows you to search on
    the incident date if the program has one.

3.  In the right hand search field, click the **Advanced search** arrow.
    
    An expanded search form opens.

4.  Enter your search criteria(s).
    
      - **Organisation unit**: The tree displayed here depends on your
        user role. If the you have role "Search Tracked Entity Instance
        in All Org Units" or "ALL", a tree with all available
        organisation units is provided. Otherwise the tree displayed in
        advanced search is the same as the one on the left-hand side.
    
      - You can select the scope of the organisation unit search. In the
        **Organisation unit scope** section select **Selected**,
        **Immediate children** or **All children**.
    
      - **Date or enrollment**: appears if you have selected a program

5.  Click **Search**.
    
    A list of TEIs that match your search criteria(s) displays.

6.  If you have selected a program, you can filter the search results
    based on enrollment status:
    
      - **Only those with active enrollment**
    
      - **Only those with completed enrollment**
    
      - **Only those with cancelled enrollment**

7.  Click a TEI.
    
    The TEI dashboard
opens.

### Find a TEI outside your organisation unit

<!--DHIS2-SECTION-ID:find_tracked_entity_instance_outside_your_organisation_unit-->

You can search for a TEI from another organisation unit, outside your
assigned organisation units. To do this:

  - Your user role must have "Search Tracked Entity Instance in All Org
    Units" or "ALL" assigned to it.

  - You must select another organisation unit than your own in the
    organisation unit tree in the **Advanced search** window.

### Download TEI search results list

<!--DHIS2-SECTION-ID:download_tracked_entity_instance_search_result-->

1.  Create a TEI search results list.

2.  Click **Download as** and select a
format:
    
      - XML
    
      - JSON
    
      - CSV

### Modify TEI search results list's layout

<!--DHIS2-SECTION-ID:modify_tracked_entity_instance_search_result_layout-->

You can select which columns to show or hide in a TEI search result
list. Once you've modified the layout, it's saved on your user profile.
You can have different layouts for different programs.

1.  Create a TEI search results list.

2.  Click **Show/hide columns**.

3.  Select the columns you want to display and click
**Close**.

## Enroll an existing TEI in a program

<!--DHIS2-SECTION-ID:enroll_existing_tracked_entity_instance_in_program-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  Select a program.

4.  In the **Enrollment** widget, click **Add new**.

5.  Fill in the required information and click **Enroll**.

## Enter event data for a TEI

<!--DHIS2-SECTION-ID:enter_event_data_for_tracked_entity_instance-->

In a TEI dashboard, you enter event data in the **Timeline Data entry**
or **Tabular data entry** widgets.

<table>
<caption>Data entry widgets in the Tracker Capture app</caption>
<colgroup>
<col width="31%" />
<col width="68%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Widget name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Timeline Data entry</strong></p></td>
<td><p>For data entry using either default or custom forms.</p>
<p>Depending on program definition, in particular program stages, events will be displayed in a timely fashion. Clicking on any of them displays the corresponding data entry. If a stage needs new event, a plus icon is displayed for new event creation. To proceed with data entry, it is mandatory to have event date. Once an event date is specified it is not possible to change due date. The assumption is that by specifying event date, the event has already taken place. If the event hasn't occurred yet, it is possible to change due date - this is effectively doing nothing but rescheduling. The buttons at the bottom help to change the status of a selected event.</p>
<p>Another key feature from this widget is addition of multiple notes for an event. Normally data recording is through data elements, however there are cases where it is necessary to record additional information or comments. This is where the notes section comes handy. However it is not possible to delete a note. The idea is notes are more like log books. Both skip-logic and validation error/warning messages are supported during data entry.</p>
<p>Also included in the Timeline Data entry is the option to compare your data entry to previous entries. This can be enabled by clicking the &quot;Switch to compare form&quot; button (Two sheets of paper) in the top right corner of the Timeline Data entry widget.</p></td>
</tr>
<tr class="even">
<td><p><strong>Tabular data entry</strong></p></td>
<td><p>For tabular-style data entry.</p>
<p>The widget displays the list of program stages as left-hand side labels. Events will be listed in table for repeatable program stage, and allows for in-line edits of event data values.</p></td>
</tr>
</tbody>
</table>

## Manage a TEI's enrollments

<!--DHIS2-SECTION-ID:manage_tracked_entity_instance_enrollment-->

### Deactivate a TEI's enrollment

<!--DHIS2-SECTION-ID:deactivate_tracked_entity_instance_enrollment-->

If you deactivate a TEI dashboard, the TEI becomes 'read-only'. You
can't enter data, enroll the TEI or edit the TEI's profile.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Enrollment** widget, click **Deactivate**.

4.  Click **Yes** to confirm.

### Activate a TEI's enrollment

<!--DHIS2-SECTION-ID:activate_tracked_entity_instance_enrollment-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Enrollment** widget, click **Activate**.

4.  Click **Yes** to
confirm.

### Mark TEI's enrollment as complete

<!--DHIS2-SECTION-ID:mark_tracked_entity_instance_enrollment_complete-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Enrollment** widget, click **Complete**.

4.  Click **Yes** to
confirm.

### Reopen completed enrollment

<!--DHIS2-SECTION-ID:reopen_complete_tracked_entity_instance_enrollment-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Enrollment** widget, click **Reopen**.

4.  Click **Yes** to
confirm.

### Display TEI's enrollment history

<!--DHIS2-SECTION-ID:display_tracked_entity_instance_enrollment_history-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Profile** widget, click the **Audit history** icon.

### Create a TEI enrollment note

<!--DHIS2-SECTION-ID:create_tracked_entity_instance_enrollment_note-->

An enrollment note is useful to record information about for example why
an enrollment was cancelled.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Notes** widget, type your note and click **Add**.

## Send a message to a TEI

<!--DHIS2-SECTION-ID:send_message_to_tracked_entity_instance-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Messaging** widget and select **SMS** or **E-mail**.

4.  Enter the required contact information.
    
    If the TEI's profile contains an e-mail address or a phone number,
    these fields are filled in automatically.

5.  Type a message.

6.  Click **Send**.

## Mark a TEI for follow-up

<!--DHIS2-SECTION-ID:mark_tracked_entity_instance_for_follow_up-->

You can use mark a TEI's enrollment for follow-up and then use this
status as a filter when you create **Upcoming events** and **Overdue
events** reports. This can be useful for example to monitor high-risk
cases during a pregnancy program.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Enrollment** widget, click the **Mark for follow-up** icon.

## Edit a TEI's profile

<!--DHIS2-SECTION-ID:edit_tracked_entity_instance_profile-->

You edit a TEI's profile or tracked entity attributes in the **Profile**
widget.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Profile** widget, click **Edit**.

4.  Modify the profile and click **Save**.

## Add a relationship to a TEI

<!--DHIS2-SECTION-ID:add_relationship_to_tracked_entity_instance-->

You can create a relationship from one TEI to another, for example
linking a mother and a child together or a husband and a wife. Depending
on how the relationship type is configured, the relative can inherit
attributes.

Assume there are two programs: Antenatal care for the mother and
Immunization for the child. If first name, last name and address
attributes are required for both programs, it is possible to configure
last name and address attributes as inheritable. Then during child
registration, there is no need to enter these inheritable attributes.
You can add them automatically based on the mother's value. If you want
to have a different value for the child, you can override the
automatically generated value.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the **Relationships** widget, and click **Add**.

4.  Select a relationship type.

5.  Search for the relative and select it.

6.  Click **Save**.

## Share a TEI dashboard

<!--DHIS2-SECTION-ID:share_tracked_entity_instance_dashboard-->

You can share a TEI dashboard via its web address.

1.  Open the **Tracker Capture** app.

2.  Open the dashboard you want to share.

3.  Copy the URL.
    
    Make sure that the URL contains "tei", "program" and "ou"
    (organisation unit) parameters.

4.  Paste the URL in the sharing method of your choice, for example an
    e-mail or a message within DHIS2.
    
    If you're not logged in to DHIS2 when you click the link, you'll be
    asked to do so and then taken to the dashboard.

## Deactivate a TEI

<!--DHIS2-SECTION-ID:deactivate_tracked_entity_instance-->

If you deactivate a TEI, the TEI becomes 'read-only'. Data associated
with the TEI is not deleted.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the top right corner, click the
    ![](resources/images/tracker_capture/tc_tei_red_icon.png) button \>
    **Deactivate**.

4.  Click **Yes** to confirm.

## Activate a TEI

<!--DHIS2-SECTION-ID:activate_tracked_entity_instance-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the upper top corner, click the
    ![](resources/images/tracker_capture/tc_tei_red_icon.png) button \>
    **Activate**.

4.  Click **Yes** to confirm.

## Delete a TEI

<!--DHIS2-SECTION-ID:delete_tracked_entity_instance-->

> **Warning**
> 
> When you delete a TEI, you delete all data associated with the TEI.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  In the top right corner, click the
    ![](resources/images/tracker_capture/tc_tei_red_icon.png) button \>
    **Delete**.

4.  Click **Yes** to
confirm.

## Configure the TEI dashboard

<!--DHIS2-SECTION-ID:configure_tracked_entity_instance_dashboard-->

### Show or hide widgets

<!--DHIS2-SECTION-ID:tracked_entity_instance_dashboard_show_hide_widget-->

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  Click the **Settings** icon, and select **Show/hide widgets**.

4.  Select the widgets you want to show or hide.

5.  Click **Close**.

### Save the dashboard's layout as default

<!--DHIS2-SECTION-ID:tracked_entity_instance_dashboard_save_layout-->

You can save the dashboard's layout as default for a program.

1.  Open the **Tracker Capture** app.

2.  Open an existing TEI dashboard.

3.  Click the **Settings** icon, and select **Save dashboard layout as
    default**.

## Create reports

<!--DHIS2-SECTION-ID:create_report_tracker_capture-->

1.  Open the **Tracker Capture** app.

2.  Click **Reports**.

3.  Select a report type.
    
    <table>
    <caption>Report types in the Tracker Capture app</caption>
    <colgroup>
    <col width="50%" />
    <col width="50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th>Report type</th>
    <th>Description</th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Program summary</p></td>
    <td><p>A summary report for a particular program, organisation unit and time frame. The report consist of a list of TEIs and their records organised based on program stages.</p></td>
    </tr>
    <tr class="even">
    <td><p>Program statistics</p></td>
    <td><p>A statistics report for a particular program. The report provides for example an overview of drop-outs or completion rates in a given time frame at a particular organisation unit.</p></td>
    </tr>
    <tr class="odd">
    <td><p>Upcoming events</p></td>
    <td><p>A tabular report showing tracked entity instances and their upcoming events for a selected program and time. You can sort the columns and search the values. Show/hide operations are possible on the columns. You can also export the table to Microsoft Excel.</p></td>
    </tr>
    <tr class="even">
    <td><p>Overdue events</p></td>
    <td><p>A list of events for a selected program. The report displays a list of TEIs and their events that are not completed on time. You can sort the columns and search the values You can also export the table to Microsoft Excel.</p></td>
    </tr>
    </tbody>
    </table>

![](resources/images/tracker_capture/program_summary_report.png)

The summary report displays a list of TEIs and their records for
"MNCH/PNC (Adult Woman)" program. The records are organized in the form
of tabs where each tab is a program stage. The columns in the table are
data elements which are configured to be displayed in reports under
program stage definition.

