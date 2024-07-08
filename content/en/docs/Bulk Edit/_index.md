---
title: "Bulk Edit"
linkTitle: "Bulk Edit"
date: 2024-07-08
weight: 550
---

**This section of the documentation contains links to external sites. Please be advised that these external sites are not maintained by the FOLIO Documentation Group and may be aligned with a different FOLIO release.**


The Bulk Edit app allows a user to apply changes to multiple FOLIO records simultaneously. 

Bulk edit can apply changes to these **record types**:

- [**Inventory - holdings**](#inventory---holdings)
- [**Inventory - instances**](#inventory---instances)
- [**Inventory - items**](#inventory---items)
- [**Users**](#users)

For more information about record types in the Inventory app, see [Metadata \> Inventory](../metadata/inventory/_index.md).

For more information about User records, see [Users \> View a user record](../users/_index.md#view-a-user-record).

## Permissions

The permissions listed below allow you to interact with the Bulk Edit app and determine what you can or cannot do within the app. Bulk edit permissions, combined with other functional app permissions, allow a user to access specific areas of the Bulk Edit app. Depending on how your library runs bulk edit jobs, users may also need permissions in other modules, such as Export Manager, Inventory, Users, and Settings. 

Permissions are assigned to users in the Users app. If none of the Bulk edit permissions are assigned to a user, they are unable to see the Bulk Edit app or any related information. 
See [Users \> Assign or unassign permissions](../users/#assign-or-unassign-permissions) for more information. 

The following are the permissions for the Bulk edit app:

- **Bulk edit: Can build query**: This permission allows the user to build and test a query, and preview matched records in the Bulk edit app. 
- **Bulk edit: Can view logs** This permission allows the user to download and view logs in the Bulk Edit app.
- **Bulk edit: In app - Edit inventory records** This permission allows the user to edit a field in multiple inventory records in the Bulk Edit app.
- **Bulk edit: In app - View inventory records** This permission allows the user to view a list of identified inventory records in the Bulk Edit app. 
- **Bulk edit: Local - Edit user records** This permission allows the user to edit a field in multiple identified user records in the Bulk Edit app by uploading a .csv file.
- **Bulk edit: Local - View user records** This permission allows the user to view a list of identified user records in Bulk Edit by uploading a .csv file.


## Identify records for bulk edit

The Bulk edit app provides two methods for identifying records: **Identifier** and **Query**. 

### Identifier

The **Identifier** approach allows the user to set criteria for the bulk edit by uploading a list of record identifiers from a .csv file. Only .csv files containing one column of record identifiers are accepted for upload in the Bulk edit app. If the .csv file contains more than one column, the upload will not be successful and a *Something went wrong* message displays. 

To set criteria for bulk edit using **Identifier**, follow these steps: 

1. In the **Set Criteria** pane, select the **Identifier** button.
2. Select the **Record type**.
3. Select the **Record identifier** from the **Select record identifier** drop-down menu. Record identifiers available for selection are based on the Record type.
4. **Drag and drop** your .csv file into the **Select a file with record identifiers** box, or click **or choose file** to upload the .csv file from your computer.

### Query

The **Query** function in the Bulk Edit app allows the user to build a query to identify records for bulk edit. 

To set criteria for bulk edit using **Query**, follow these steps: 

1. In the **Set Criteria** pane, click on the **Query** tab.
2. Select the **Record type**.
3. Click the **Build query** button to open the **Build query** modal.
4. Select a **Field** from the *Select field* drop-down menu or filter the selection by typing the field in the *Filter options list* text box.
5. Select an **Operator** from the *Select operator* drop-down list. The operators available for selection are based on the **Field**. 

   - ==: Field equals selected or input Value.
   - !=:  Field does not equal selected or input Value.
   - Contains: Field appears in selected or input Value.
   - Starts: Field starts with selected or input Value.
   - \>: Field is greater than the selected or input Value.
   - <: Field is less than the selected or input Value.
   - \>=: Field is greater than or equal to the selected or input Value.
   - <=: Field is less than or equal to the selected or input Value.
   - Is null/empty: Field is blank; it contains no data.

6. Select a **Value** from the *Select value* drop-down list or type the value in the text box.  The values available for selection are based on the **Field** and **Operator**.
7. Click on the **+ icon** to add additional lines to the query or click on the **trash can icon** to delete a line from the query.
8. Once a query is built, it must be tested before the query can be run and saved. Click the **Test query** button to run the query and display a preview of matched records. The query string can be edited in the **Query string** field. If edited, another Test query must be done.
9. If the Test query is successful, click the **Run query** button to run the query and preview the matched records in the **Bulk edit query** modal.

## Preview matched records

If the **Identifier** method is used to identify records for bulk edit, the number of records matched and the filename display at the top of the **Bulk edit** modal. 

If the **Query** method is used to identify records for bulk edit, a **Test query** displays the query string and number of matched records at the top of the **Build query** modal. 

If the query is run, the **Query** and a preview of matched records display in the **Bulk edit query** modal. 

To add or remove record identifier columns in the preview pane, click the **Actions** button. 

   - In the **Show columns** section of the Actions menu, check the box next to the name of the record identifier to include as a column in the preview.
   - Uncheck the box next to the name of the record identifier to remove the column from the preview.

## Download matched records

If desired, download the matched records as a .csv file:
   
   - In the **Preview** pane, click **Actions** and select **Download matched records (CSV)**.
   - Depending on the web browser settings, the .csv file may be opened and/or saved. 

## Download errors

If there are errors in the matched records, a message indicating the filename, number of entries, number of records matched, and number of errors displays in a two-column table in the **Errors** section. 

- **Record identifier.** The record identifier for the records that produced the error.
- **Reason for error.** The reason why the error was produced.

To download the list of errors as a .csv file, follow these steps:

1. In the **Preview** pane, select **Actions > Download errors (CSV)**.
2. Depending on the web browser settings, the .csv file may be opened and/or saved. 

## Bulk edit by record type

### Inventory - holdings

In the Bulk edit app, the **fields** that can be changed in Holdings records include:

- [**Administrative note**](#administrative-note)
- [**Electronic access**](#electronic-access)
- [**Holdings location**](#holdings-location)
- [**Holdings notes**](#holdings-notes)
- [**Suppress from discovery**](#suppress-from-discovery).

To identify **Holdings** records for bulk edit, follow these steps:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory - holdings**.
2. [Identify holdings records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matched holdings records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched holdings records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in matched holdings records](#download-errors) as a .csv file.

To start a bulk edit on the matched **Holdings** records, follow these steps: 

1. Click the **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the holdings records. Actions available for selection are based on the field selected for bulk edit.
4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
8. To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
9. To run the bulk edit job, click **Save & close**. The window closes and the banner at the top of the **Bulk edit** pane displays the number of records successfully changed.
10. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device. 


#### Administrative note

To bulk edit the **Administrative note** in the matched holdings records, follow these steps:

1. Under **Options**, select **Administrative note** from the drop-down list.
2. Click **Actions** to select the action you want to apply from the drop-down list:

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type.
   - **Find (full field search).** Input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Remove all.** Delete all administrative notes in the matched holdings records.

3. Click **Confirm changes**. The selected action will be applied to the matched holdings records.
The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
4. Click **Commit changes** to save the changes to the matched holdings records.

#### Electronic access

To bulk edit the **Electronic access** in the matched holdings records, follow these steps:

1. In the **Bulk edit** window, select the appropriate **Electronic access** field from the **Select option** drop-down list. 

   - **Link text**
   - **Materials specified**
   - **URI**
   - **URL public note**
   - **URL Relationship**.

2. Click **Actions** to select the action you want to apply from the drop-down list: 

   - **Clear field.** Removes the data in the selected field of the matched holdings records.
   - **Find (full field search).** Input the text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **URL Relationship.** Select **No display constant generated**, **No information provided**, **Related resource**, **Resource**, or **Version of resource**.
   - **Replace with.** Replaces the text in the matched holdings records with the new text.
   - **URL Relationship.** Select **No display constant generated**, **No information provided**, **Related resource**, **Resource**, or **Version of resource**.

3. Click **Confirm changes**. The selected action will be applied to the matched holdings records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to save the changes to the matched holdings records. 


#### Holdings location

To bulk edit the **Holdings location** in the matched holdings records, follow these steps:

1. In the **Bulk edit** window, select the appropriate location from the **Select option** drop-down list. The following holdings locations may be changed in the Bulk edit app:

   - **Permanent location**
   - **Temporary location**.

2. Click **Actions** to select the action you want to apply from the drop-down list.

   - **Clear field.** Removes the data in the location field.
   - **Replace with.** Replaces the location field in the matched holdings records with the location selected in the **Select location** drop-down list or the **Location look-up**.

3. Click **Confirm changes**. The selected action will be applied to the matched holdings records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to save the changes to the matched holdings records.  

#### Holdings notes

To bulk edit a **holdings note** in the matched holdings records, follow these steps:

1. In the **Bulk edit** window, select the appropriate holdings note from the **Select option** drop-down list: 

   - **Action note**
   - **Binding**
   - **Copy note**
   - **Electronic bookplate**
   - **Note**
   - **Provenance**
   - **Reproduction**

2. Click **Actions** to select the action you want to apply from the drop-down list: 

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type you want.
   - **Find (full field search).** Input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Mark as staff only.** Marks the holdings note as viewable by staff only.
   - **Remove all**. Delete all check in notes in the matched holdings records.
   - **Remove mark as staff only**. Removes the staff only designation from the matched holdings note.

3. Click **Confirm changes**. The selected action will be applied to the matched holdings records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to save the changes to the matched holdings records. 

#### Suppress from discovery

To suppress the matched holdings records from discovery in the Bulk edit app, follow these steps:

1. In the **Bulk edit** window, select **Suppress from discovery** from the **Select option** drop-down list.
2. Select the appropriate **Action** from the **Select action** drop-down list.

   - **Set true**: Suppresses the matched holdings records from discovery.
   - **Set false**: Unsuppresses the matched holdings records from discovery.

3. Once an action is selected, the **Data** defaults to apply the same **Set true** or **Set false** action to all matched holdings and item records. Click the appropriate checkbox(es) if you do not want the selected action to be applied to the holdings records.
4. Click **Confirm changes** to apply the changes to the matched holdings records. An *Are you sure?* message appears in a new window with a **Preview of records to be changed**. An alert appears at the top of the window: *(Number of) records will be changed if the Commit changes button is clicked.*
5. Click **Keep editing** to return to the Bulk edits window, **Download preview** to preview the changes before saving, or **Commit changes** to run the bulk edit.
6. Click **Commit changes** to perform the bulk edit and save the changes to the matched holdings records. 


## Inventory - instances

In the Bulk edit app, the fields that can be changed in **Instance** records include:

   - [**Staff suppress**](#staff-suppress)
   - [**Suppress from discovery**](#suppress-from-discovery-1)

To identify **Instance** records for bulk edit, follow these steps:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory - instances**.
2. [Identify instance records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matched instance records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched instance records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in matched instance records](#download-errors) as a .csv file.

To start a bulk edit on the matched **Instance** records, follow these steps:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the holdings records. Actions available for selection are based on the field selected for bulk edit.

   - To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
   - To remove a field, click the **trash can icon** at the end of the row you want to remove.
     
4. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
5. To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
6. To preview the entire list of records, click **Download preview**. A .csv file is downloaded to your local device.
7. To run the bulk edit job, click **Save & close**. The window closes and the banner at the top of the **Bulk edit** pane displays the number of records successfully changed.
8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device. 

#### Staff suppress

To suppress the matched **Instance** records from staff view in the Bulk edit app, follow these steps:

1. In the **Bulk edit** window, select **Staff suppress** from the **Select option** drop-down list.
2. Select the appropriate **Action** from the **Select action** drop-down list.

   - **Set true**: Suppresses the matched instance records from staff view.
   - **Set false**: Unsuppresses the matched instance records from staff view.

3. Click **Confirm changes**to apply the changes to the matched instance records.
   - An *Are you sure?* message displays in a new window with a **Preview of records to be changed**.
   - An alert displays at the top of the window: *(Number of) records will be changed if the **Commit changes** button is clicked.
   - Click **Download preview** to review all changes prior to saving.
   - Click **Keep editing** to return to the **Bulk edit** window.
7. Click **Commit changes** to run the bulk edit and save the changes to the matched Instance records.

#### Suppress from discovery

To suppress the matched instance records from discovery in the Bulk edit app, follow these steps:

1. In the **Bulk edit** window, select **Suppress from discovery** from the **Select option** drop-down list.
2. Select the appropriate **Action** from the **Select action** drop-down list.

   - **Set true**: Suppresses the matched instance records from discovery.
   - **Set false**: Unsuppresses the matched instance records from discovery.

3. Once an action is selected, the **Data** defaults to apply the same **Set true** or **Set false** action to **all holdings records** and **all items records**. Click the appropriate checkbox(es) if you do not want the selected action to be applied to the holdings records and/or item records.
4. Click **Confirm changes** to apply the changes to the matched instance records.

   - An *Are you sure?* message appears in a new window with a **Preview of records to be changed**. 
   - An alert appears at the top of the window: *(Number of) records will be changed if the Commit changes button is clicked.*
   - Choose **Download preview** to review all changes prior to saving.
   - Click **Keep editing** to return to the **Bulk edit** window or **Download preview** to preview the changes before saving.

5. Click **Commit changes** to run the bulk edit and save the changes to the matched instance records.

## Inventory - items

To identify **Item** records for bulk edit, follow these steps:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory - items**.
2. [Identify item records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matching item records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched item records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in the matched item records](#download-errors) as a .csv file.

In the Bulk edit app, the fields that can be changed in **Item records** include:

- [**Administrative note**](#administrative-note)
- [**Check in note**](#check-in-note)
- [**Check out note**](#check-out-note)
- [**Item note**](#item-notes)
- [**Item status**](#item-status)
- [**Loan type**](#loan-type)
- [Location](#location)
- [**Suppress from discovery**](#suppress-from-discovery-2)

To start a bulk edit on the matched item records, follow these steps:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. Actions available for selection are based on the field selected for bulk edit. 

   - To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
   - To remove a field, click the **trash can icon** at the end of the row you want to remove. 

4. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
5. To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
6. To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
7. To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the Bulk edit pane displays the number of records successfully changed.
8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Administrative note

To bulk edit the **Administrative note** in the matched item records, follow these steps:

1. Under **Options**, select **Administrative note** from the drop-down list.
2. Click **Actions** to select the action you want to apply from the drop-down list:

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type.
   - **Find (full field search).** Input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Remove all.** Delete administrative notes in the matched item records.

3. Click **Confirm changes**. The selected action will be applied to the matched item records.
4. The **Preview of records to be changed** will display with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to run the bulk edit and save the changes to the matched item records.

#### Check in note

To bulk edit the **Check in note** in the matched item records, follow these steps:

1. Under **Options**, select **Check in note** from the drop-down list.
2. Click **Actions** to select the action you want to apply from the drop-down list:

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type.
   - **Duplicate to.** Duplicates the note as a **Check out note**.
   - **Find (full field search).** input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Mark as staff only.** Marks the check in note as viewable by staff only.
   - **Remove all.** Deletes any check in notes from the matched item records.
   - **Remove mark as staff only.** Removes the staff only designation for the check in note.

3. Click **Confirm changes**. The selected action will be applied to the matched item records.
4. The **Preview of records to be changed** will display with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to run the bulk edit and save the changes to the matched Item records.

#### Check out note

To bulk edit the **Check out note** in the matched item records, follow these steps:

1. Under **Options**, select **Check out note** from the drop-down list.
2. Click **Actions** to select the action you want to apply from the drop-down list.

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type.
   - **Duplicate to.** Duplicates the note as a **Check in note**.
   - **Find (full field search).** Input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Mark as staff only.** Marks the check out note as viewable by staff only.
   - **Remove all.** Deletes all check out notes from the matched item records.
   - **Remove mark as staff only.** Removes the staff only designation for the check out note.
     
3. Click **Confirm changes**. The selected action will be applied to the matched Item records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to run bulk edit and save the changes to the matched Item records.

#### Item notes

To bulk edit an **item note** in the matched item records, follow these steps:

1. In the **Bulk edit** window, select the appropriate item note from the **Select option** drop-down list. The following types of item notes may be changed in the Bulk edit app:

   - **Action note**
   - **Binding**
   - **Copy note**
   - **Electronic bookplate**
   - **Note**
   - **Provenance**
   - **Reproduction**

2. Click **Actions** to select the action you want to apply from the drop-down list. Actions available in the Bulk edit app include:

   - **Add note.** Input note text you want added.
   - **Change note type.** Select the new note type you want.
   - **Find (full field search).** Input note text you want to find. Select **Replace with** and input new text or select **Remove** to remove the text.
   - **Mark as staff only.** Marks the item note as viewable by staff only.
   - **Remove all.** Deletes any item notes from the matched item records.
   - **Remove mark as staff only.** Removes the staff only designation for the item note.

3. Click **Confirm changes**. The selected action will be applied to the matched item records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
Click **Commit changes** to run bulk edit and save the changes to the matched item records.

#### Item status

To bulk edit the **item status** field in the matched records, follow these steps:

1. In the **Bulk edit** window, select **Item status** from the **Select option** drop-down list. For item status, the only **Action** allowed in the Bulk edit app is **Replace with**. This action is pre-selected by default.
2. Click **Select item status** to select the item status you want to apply from the drop-down list. See [Supported item records status changes](https://folio-org.atlassian.net/wiki/spaces/FOLIOtips/pages/5674323/Supported+item+records+status+changes) for a list of item status change options.
3. Click **Confirm changes**. The new Item status will be applied to the matched Item records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to run bulk edit and save the changes to the matched item records.

#### Loan type

To bulk edit the **Loan type** in the matched item records, follow these steps:

1. In the **Bulk edit** window, select the appropriate loan type from the **Select option** drop-down list. The following loan types may be changed in the Bulk edit app:

   - **Permanent loan type**
   - **Temporary loan type**.

2. Click **Actions** to select the action you want to apply from the drop-down list.
   
   - For **permanent loan type**, the only **Action** allowed in the Bulk edit app is **Replace with**. This action is pre-selected by default.
   - For **temporary loan type**, the actions available in the Bulk edit app include: 

      - **Clear field**. Removes the data in the loan type field of the matched item records.
      - **Replace with**. Replaces the loan type in the matched item records with the loan type selected in the **Select loan type** drop-down list or use the **Filter options list** to select the new loan type.

3. Click **Confirm changes**. The selected action will be applied to the matched item records.
4. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
5. Click **Commit changes** to run bulk edit and save the changes to the matched Item records. 

#### Location

To bulk edit the **Location** in the matched item records, follow these steps:

1. In the **Bulk edit** window, select the appropriate location from the **Select option** drop-down list. The following **Locations** may be changed in the Bulk edit app:

   - **Permanent location**
   - **Temporary location**

2. Click **Actions** to select the action you want to apply from the drop-down list.	

   - **Clear field.** Removes the data in the location field.
   - **Replace with.** Replaces the location field in the matched item records with the location selected in the **Select location** drop-down list or the **Location look-up**.

3. Click **Confirm changes**. The selected action will be applied to the matched item records.
The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
4. Click **Commit changes** to run bulk edit and save the changes to the matched Item records. 

#### Suppress from discovery

To suppress the matched item records from discovery in the Bulk edit app, follow these steps:

1. In the **Bulk edit** window, select **Suppress from discovery** from the **Select option** drop-down list.
2. Select the appropriate **Action** from the **Select action** drop-down list.

   - **Set true**: Suppresses the matched item records from discovery.
   - **Set false**: Unsuppresses the matched item records from discovery.

3. Click **Confirm changes** to apply the changes to the matched item records.

   - An *Are you sure?* message displays in a new window with a **Preview of records to be changed**.
   - An alert appears at the top of the window: *(Number of) records will be changed if the Commit changes button is clicked.*
   - **Download preview** to review all changes prior to saving;
   - Click **Keep editing** to return to the Bulk edits window;
   - **Download preview** to preview the changes before saving; or
   - **Commit changes** to run the bulk edit.

4. Click **Commit changes** to run bulk edit and save the changes to the matched Item records.

## Users

To identify **User** records for bulk edit, follow these steps:

1. In the **Set criteria** pane, ensure **Record types** is set to **Users**.
2. [Identify user records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.

   - The **Query** method allows only a preview of matched user records in the Bulk edit app. User records cannot be edited using the Query method.
   - The **Identifier** method allows bulk edit to be performed on all fields of a user record.

3. [Preview the list of matching user records](#preview-matched-records) in the **Preview of record matched** pane. The following information appears in the **Preview of record matched** pane:

   - **Username.** The username of the user.
   - **Barcode.** The barcode from the user record.
   - **Status.** The status of the user.
   - **Patron group.** The patron group assigned to the user.
   - **Last name.** The last name of the user.
   - **First name.** The first name of the user.

4. (Optional; Identifier method only): [Download the matched user records](#download-matched-records) as a .csv file.
5. (Optional; Identifier method only): [Download errors in matched user records](#download-errors) as a .csv file.

## Start bulk edit

The **Start bulk edit** approach allows bulk edit to change the **Email**, **Expiration Date**, and/or **Patron Group** fields in matching user records. Bulk edit may be performed on each of these fields individually or simultaneously. 

To perform bulk edit on matched **User records** using the **Start bulk edit** method, follow these steps:

1. In the **Preview** pane, click **Actions > Start bulk edit**. The number of matched user records and the filename of the .csv file display at the top of the **Bulk edit** window.
2. In the **Bulk edits** section, select the option from the **Select options** drop-down menu. To bulk edit all three fields simultaneously, click the **+ icon** at the end of the row to add another bulk edit option. 

   - **Email**: Bulk edit performs a find and replace in the email address field of the matched user records. Thus, the **Actions** available are **Find (full field search)** and **Replace with**. Type the current data (text) in the **Find (full field search)** box. Type the new data (text) in the **Replace with** box. 
   - **Expiration date**: Bulk edit replaces the data in the Expiration date of the matched user records. Thus, the **Actions** available are limited to **Replace with**.  Type the new expiration date in MM/DD/YYYY format in the **Data** box or use the **calendar icon** to select a date.
   - **Patron group**: Bulk edit replaces the Patron group data in the matched user records. Thus, the **Actions** available are limited to **Replace with**. Select the new Patron group from the **Data** drop-down menu. 

3. Click the **Confirm changes** button. The message *(Number of) records will be changed if the Commit changes button is clicked* displays in the **Are you sure?** modal.
   
   - Click **Keep editing** to return to the Bulk edit window.
   - Click **Download preview** to review all changes prior to saving.* A **Preview of records to be changed** is also displayed.
   - Click **Commit changes** to run bulk edit and save the changes to the matched user records.

4. When the bulk edit is complete, a confirmation message, *(Number of) records have been successfully changed*, appears in the **Bulk edit** window.
5. To change the column headings in the **Preview of record changed** table, click **Actions** and select or deselect the fields in the **Show columns** list as appropriate.
6. To download a .csv file of changed records, click **Actions > Download changed records (CSV)**. 


### Start bulk edit (Local)

The **Start bulk edit (Local)** function allows the user to perform a bulk edit on user records edited locally (external to FOLIO) by uploading a .csv file of the changed, or edited, user records. 

Any field in user records can be changed using the **Bulk edit (Local)** approach.

To perform bulk edit on user records using the **Start bulk edit (Local)** approach, follow these steps: 

1. In the **Set criteria** pane, select **Users** as the **Record type** and select the appropriate **Record identifier**: **User UUIDs**, **User barcodes**, **External IDs**, or **Usernames**.
2. Upload a .csv file with the selected Record identifier by either using the **Drag and drop** option or clicking the **Choose file** button.
3. Select **Actions \> Download matched records (CSV)** to download a .csv file of matched user records; or select **Actions \> Download errors (CSV)** to download a .csv file of records that did not match your selected record identifier.
4. Edit the downloaded .csv file and make changes to the user records in the file itself. Save the edited .csv file to your computer.
5. Select **Actions \> Start bulk edit (Local)**.
6. In the **Bulk edit** window, **Drag and drop** the .csv file into the **Upload CSV file with edited records** box, or click **or choose file** to upload the .csv file from your computer. If the .csv file is uploaded successfully, the confirmation message, *(Name of File).csv successfully uploaded*, displays in a new window.
7. Click **Next**. The warning message, *(Number of) records will be updated if the **Commit changes** button is clicked.* appears in a new window.
Click **Commit changes**. Bulk edit will apply and save the local changes to the matched user records in FOLIO.

## Logs

The Bulk edit app allows users to preview **bulk edit logs** based on set criteria and download a file associated with a bulk edit job. 

### Preview bulk edit logs

The options available for setting criteria include: **Statuses**, **Record types**, **Started**, **Ended**, and **User**.  

To set criteria and preview bulk edit logs, follow these steps:

1. Click on the **Logs** tab in the **Set criteria** pane.
2. Under the **Statuses** accordion, select the status for the bulk edit log by checking the appropriate box:  

   - **New**
   - **Retrieving records**
   - **Saving records**
   - **Data modification**
   - **Reviewing changes**
   - **Completed**
   - **Completed with errors**
   - **Failed**  

3. Under the **Record types** accordion, select the record type for the bulk edit log by checking the appropriate box: 

   - **Inventory - holdings**
   - **Inventory - instances**
   - **Inventory - items**
   - **Users**

4. In the **Started** accordion, use the **calendar icon** or type in the date using the YYYY-MM-DD format in the **From** and **To** fields to limit the preview by the start date of the bulk edit. Click **Apply**.
5. In the **Ended** accordion, use the **calendar icon** or type in the date using the YYYY-MM-DD format in the **From** and **To** fields to limit the preview by the end date of the bulk edit. Click **Apply**.
6. In the **Users** accordion, select the user, or FOLIO account, that ran the bulk edit job from the **Choose user** drop-down list.
7. A preview list of bulk edit logs displays in the **Bulk edit logs** pane. The number of bulk edit logs in the preview displays at the top of the pane as *(number of) records found*. The column headings display the following criteria for each bulk edit log: 

   - **Record type**: type of records changed in the bulk edit job
   - **Status**: status of the bulk edit job
   - **Editing**: method of bulk edit used
   - **# of records**: number of records retrieved for bulk edit job
   - **Processed**: number of records changed in bulk edit job
   - **Started**: start date and start time of bulk edit job
   - **Ended**: end date and end time of bulk edit job
   - **Run by**: user or FOLIO account used to run the bulk edit job
   - **ID**: system-generated number assigned to the bulk edit job

### Download a bulk edit log file

In the Bulk edit app, a file used to run a bulk edit job can be downloaded and saved from the **Bulk edit logs** pane.

To download a file associated with a bulk edit log, follow these steps:

1. In the **Bulk edit logs** pane, click on the **ellipses** in the **Actions** column next to the appropriate Bulk edit log.
2. Select the appropriate action from the **Download** drop-down list. The types of files available for download include: 

   - **File that was used to trigger the bulk edit**
   - **File with the matching records**
   - **File with errors encountered during the record matching**

Depending on the web browser settings, the file can be opened and/or saved to your computer. 

