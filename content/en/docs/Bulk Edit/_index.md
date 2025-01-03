---
title: "Bulk Edit"
linkTitle: "Bulk Edit"
date: 2025-01-03
weight: 550
---

**This section of the documentation contains links to external sites. Please be advised that these external sites are not maintained by the FOLIO Documentation Group and may not be aligned with a different FOLIO release.**


The Bulk Edit app allows a user to apply changes to multiple Inventory or User records simultaneously. 


## Permissions

The permissions listed below allow you to interact with the Bulk Edit app and determine what you can or cannot do within the app. Bulk edit permissions, combined with other functional app permissions, allow a user to access specific areas of the Bulk Edit app. Depending on how your library runs bulk edit jobs, users may also need permissions in other modules, such as Export Manager, Inventory, Users, and Settings. 

Permissions are assigned to users in the Users app. If none of the Bulk edit permissions are assigned to a user, they are unable to see the Bulk Edit app or any related information. 
See [Users \> Assign or unassign permissions](../users/#assign-or-unassign-permissions) for more information. 

The following are the permissions for the Bulk edit app:

- **Bulk edit: Can build query**: This permission allows the user to build and test a query, and preview matched records in the Bulk edit app. 
- **Bulk edit: Can view logs** This permission allows the user to download and view logs in the Bulk Edit app.
- **Bulk edit: In app - Edit inventory records** This permission allows the user to edit a field in multiple inventory records in the Bulk Edit app.
- **Bulk edit: In app - Edit user records**. This permission allows the user to edit a field in multiple user records in the Bulk edit app. 
- **Bulk edit: In app - View inventory records** This permission allows the user to view a list of identified inventory records in the Bulk Edit app. 
- **Bulk edit: Local - Edit user records** This permission allows the user to edit a field in multiple identified user records in the Bulk Edit app by uploading a .csv file.
- **Bulk edit: Local - View user records** This permission allows the user to view a list of identified user records in Bulk Edit by uploading a .csv file.


## Identify records for bulk edit

The Bulk edit app provides two methods for setting criteria and identifying records for bulk edit: **Identifier** and **Query**.  In either method, the **Record identifiers** or **Fields** available for selection are based on the **Record type**.


### Identifier

The **Identifier** approach allows the user to set criteria for the bulk edit by uploading a list of record identifiers from a .csv file. Only .csv files containing one column of record identifiers are accepted for upload in the Bulk edit app. If the .csv file contains more than one column, the upload will not be successful and a *Something went wrong* message displays. 

To set criteria for bulk edit using **Identifier**, follow these steps: 

1. In the **Set Criteria** pane, select the **Identifier** button.
2. Select the **Record type**.
3. Select the **Record identifier** from the **Select record identifier** drop-down menu. Record identifiers available for selection are based on the Record type.
4. **Drag and drop** your .csv file into the **Select a file with record identifiers** box, or click **or choose file** to upload the .csv file from your computer.

#### Record identifiers by record type

In the **Identifier** method, the **Record identifiers** available for selection are based on the selected **Record type**. 

| Record Type | Record identifier | 
| :-----: | :-----: |  
| Inventory - holdings | Holdings UUIDs | 
| Inventory - holdings | Holdings HRIDs |
| Inventory - holdings | Instance HRIDs |
| Inventory - holdings | Item barcodes |
| Inventory - instances | Instance UUIDs |
| Inventory - instances | Instance HRIDs |
| Inventory - items | Item barcodes |
| Inventory - items | Item barcodes |
| Inventory - items | Item UUIDs |
| Inventory - items | Item HRIDs |
| Inventory - items | Item former identifiers |
| Inventory - items | Item accession numbers |
| Users | User UUIDs |
| Users | User barcodes |
| Users | External IDs |
| Users | Usernames |


#### Set criteria to identify records 

To set criteria and identify records for bulk edit using the **Identifier** method: 

1. In the **Set Criteria** pane, select the **Identifier** button. 
2. Select the **Record type**. The Bulk edit app allows changes to these record types:

   - Inventory - holdings
   - Inventory - instances
   - Inventory - items
   - Users

3. Select the **Record identifier** from the **Select record identifier** drop-down menu. Record identifiers available for selection are based on the **Record type**. See [Record identifiers by Record Type](#record-identifiers-by-record-type) for more information.
4. **Drag and drop** your .csv file into the **Select a file with record identifiers** box, or click **or choose file** to upload the .csv file from your computer.


### Query

The **Query** function in the Bulk Edit app allows the user to build a query to identify records for bulk edit. The **Fields** available for building a query are based on the selected **Record type**. 


#### Fields by Record Type 
(add table here)


#### Build a query to indentify records

To set criteria and identify records for bulk edit using the **Query** method: 

1. In the **Set Criteria** pane, click on the **Query** tab.
2. Select the **Record type**. The Bulk edit app allows changes to these **Record types**:
   
   - Inventory - holdings
   - Inventory - instances
   - Inventory - items
   - Users

3. Click the **Build query** button to open the **Build query** modal.
4. Select a **Field** from the *Select field* drop-down menu or filter the selection by typing the field in the *Filter options list* text box. The **Fields** available for selection are based on the **Record type**. See [Fields by Record Type](#fields-by-record-type) for more information.  

5. Select an **Operator** from the *Select operator* drop-down list. The operators available for selection are based on the **Field**. 

   - *equals* : Field equals selected or input value.
   - *not equal to* : Field does not equal selected or input value.
   - *contains* : Field appears in selected or input value.
   - *starts with* : Field starts with selected or input value.
   - *is greater than* : Field is greater than the selected or input value.
   - *is less than* : Field is less than the selected or input value.
   - *is greater than or equal to* : Field is greater than or equal to the selected or input value.
   - *is less than or equal to* : Field is less than or equal to the selected or input value.
   - *is null/empty*: Field is blank; the field does not contain any data.

6. Select a **Value** from the *Select value* drop-down list or type the value in the text box.  The values available for selection are based on the **Field** and **Operator**.
7. Click on the **+ icon** to add additional lines to the query or click on the **trash can icon** to delete a line from the query.
8. Once a query is built, it must be tested before the query can be run and saved. Click the **Test query** button to run the query and display a preview of matched records. The query string can be edited in the **Query string** field. If edited, another Test query must be done.
9. If the Test query is successful, click the **Run query** button to run the query and preview the matched records in the **Bulk edit query** modal.

### Preview matched records

If the **Identifier** method is used to identify records for bulk edit, the number of records matched and the filename display at the top of the **Bulk edit** modal. 

If the **Query** method is used to identify records for bulk edit, a **Test query** displays the query string and number of matched records at the top of the **Build query** modal. 

If the query is run, the **Query** and a preview of matched records display in the **Bulk edit query** modal. 

To add or remove record identifier columns in the preview pane, click the **Actions** button. 

   - In the **Show columns** section of the Actions menu, check the box next to the name of the record identifier to include as a column in the preview.
   - Uncheck the box next to the name of the record identifier to remove the column from the preview.

### Download matched records

If desired, download the matched records as a .csv file:
   
   - In the **Preview** pane, click **Actions** and select **Download matched records (CSV)**.
   - Depending on the web browser settings, the .csv file may be opened and/or saved. 

### Download errors

If there are errors in the matched records, a message indicating the filename, number of entries, number of records matched, and number of errors displays in a two-column table in the **Errors** section. 

- **Record identifier.** The record identifier for the records that produced the error.
- **Reason for error.** The reason why the error was produced.

To download the list of errors as a .csv file, follow these steps:

1. In the **Preview** pane, select **Actions > Download errors (CSV)**.
2. Depending on the web browser settings, the .csv file may be opened and/or saved. 

## Bulk edit by record type

### Inventory - holdings

In the Bulk edit app, the **Fields** that can be changed in Holdings records include:

- **Administrative note**
- **Electronic access**
- **Holdings location**
- **Holdings notes**
- **Suppress from discovery**.

To identify **Inventory-holdings** records for bulk edit, follow these steps:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory - holdings**.
2. [Identify holdings records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matched holdings records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched holdings records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in matched holdings records](#download-errors) as a .csv file.

Once **Inventory-holdings** records are identified, you can start a bulk edit on the matching records. The **Options** and **Actions** available to perform the bulk edit vary for each **Field**. 


#### Administrative note

To bulk edit the **Administrative note** in the matched **Inventory-holdings** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, select **Administrative note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **Administrative note** field:

| Actions | Data | Actions | Data |
| :-----: | :-----:| :-----: | :-----: |
| Add note | Text field | &nbsp; | &nbsp; |
| Change note type | Select note type | &nbsp; | &nbsp; |
| Find (full field search) | Input text | Remove |
| Find (full field search)  | Input text | Replace with | Input text |
| Find (full field search)  | Remove all | &nbsp; | &nbsp; | &nbsp; |
   
4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. Click **Commit changes** to save the changes to the matched **Inventory-holdings** records.

#### Electronic access

To bulk edit the **Electronic access** in the matched **Inventory-holdings** records:

1. Click the **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the **Field** you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the holdings records. The following **Options** and **Actions** are available to bulk edit the **Electronic access** field in the matching **Inventory-holdings** records:

| Option | Action | Data | Action | Data |
| :-----:| :-----:| :-----:| :-----:| :-----:|
| *Electronic access - Link text* | Clear field | &nbsp; | &nbsp; | &nbsp; |
| *Electronic access - Link text* | Find (full field search) | Text field | Remove | &nbsp; |
| *Electronic access - Link text* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - Link text* | Replace with | Text field | &nbsp; | &nbsp; |
| *Electronic access - Materials specified* | Clear field | &nbsp; | &nbsp; | &nbsp; |
| *Electronic access - Materials specified* | Find (full field search) | Text field | Remove | &nbsp; | &nbsp; |
| *Electronic access - Materials specified* | Find (full field search) | Text field | Replace with | Text field | 
| *Electronic access - Materials specified* | Replace with | Text field | &nbsp; | &nbsp; |
| *Electronic access - URI* | Clear field | &nbsp; | &nbsp: | &nbsp; |
| *Electronic access - URI* | Find (full field search) | Text field | Remove | &nbsp; | &nbsp; |
| *Electronic access - URI* | Find (full field search) | Text field | Replace with | Text field |
| *Electronic access - URI* | Replace with | Text field | &nbsp; | &nbsp; |
| *Electronic access - URL public note* | Clear field | &nbsp; | &nbsp; | &nbsp; |
| *Electronic access - URL public note* | Find (full field search) | Text field | Remove | &nbsp; | &nbsp; |
| *Electronic access - URL public note* | Find (full field search) | Text field | Replace with | Text field |
| *Electronic access - URL public note* | Replace with | Text field | &nbsp; | &nbsp; |
| *Electronic access - URL relationship* | Clear field | &nbsp; | &nbsp; | &nbsp; |
| *Electronic access - URL relationship* | Find (full field search) | Text field | Remove | &nbsp; | &nbsp; |
| *Electronic access - URL relationship* | Find (full field search) | Text field | Replace with | Text field |
| *Electronic access - URL relationship* | Replace with | Text field | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of *Keep editing*, *Download preview*, or *Commit changes*.
   
   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device. Click **Commit changes** to save the changes to the matched holdings records. 


#### Holdings location

To bulk edit the **Holdings-location** in the matched **Inventory-holdings** records:

1. Click the **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the **Field** you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the **Inventory-holdings** records. The following **Options** and **Actions** are available to bulk edit the **Holdings-location** field in the matching Holdings records:

| Option | Action | Data | Action | Data |
| :-----| :-----| :-----| :-----| :-----|
| *Holdings location - Permanent holdings location* | &nbsp; | Select location | &nbsp; | &nbsp;|
| *Holdings location - Temporary holdings location* | Clear field | &nbsp; | &nbsp; | &nbsp; |
| *Holdings location - Temporary holdings location* | Replace with | Select location | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.
8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device. 


#### Holdings notes

To bulk edit a **holdings note** in the matched **Inventory-holdings** records:

1. Click the **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the **Field** you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the holdings records. 

The following **Options** and **Actions** are available to bulk edit the **Holdings-notes** field in the matching Holdings records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| *Holdings notes - Access restrictions* | Add note | Text field, Staff only check box | & nbsp; | &nbsp; |
| *Holdings notes - Access restrictions* | Change note type | Select note type | &nbsp; | & nbsp; |
| *Holdings notes - Access restrictions* | Find (full field search) | Text field | Remove | &nbsp; |
| *Holdings notes - Access restrictions* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Access restrictions* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Access restrictions* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Access restrictions* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Binding* | Add note | Text field, Staff only check box | & nbsp; | &nbsp; |
| *Holdings notes - Binding* | Change note type | Select note type | &nbsp; | & nbsp; |
| *Holdings notes - Binding* | Find (full field search) | Text field | Remove | &nbsp; |
| *Holdings notes - Binding* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Binding* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Binding* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Binding* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Copy note* | Add note | Text field, Staff only check box | & nbsp; | &nbsp; |
| *Holdings notes - Copy note* | Change note type | Select note type | &nbsp; | & nbsp; |
| *Holdings notes - Copy note* | Find (full field search) | Text field | Remove | &nbsp; |
| *Holdings notes - Copy note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Copy note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Copy note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Copy note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Electronic bookplate* | Add note | Text field, Staff only check box | & nbsp; | &nbsp; |
| *Holdings notes - Electronic bookplate* | Change note type | Select note type | &nbsp; | & nbsp; |
| *Holdings notes - Electronic bookplate* | Find (full field search) | Text field | Remove | &nbsp; |
| *Holdings notes - Electronic bookplate* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Electronic bookplate* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Electronic bookplate* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Electronic bookplate* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Note* | Add note | Text field, Staff only check box | & nbsp; | &nbsp; |
| *Holdings notes - Note* | Change note type | Select note type | &nbsp; | & nbsp; |
| *Holdings notes - Note* | Find (full field search) | Text field | Remove | &nbsp; |
| *Holdings notes - Note* | Find (full field search) | Text field | Replace with | Text field |
| *Holdings notes - Note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Holdings notes - Note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will pop up with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to save the changes to the matched holdings records.
8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Suppress from discovery

To suppress the matched **Inventory-holdings** records from discovery in the Bulk edit app:

1. Click the **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the **Field** you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the **Inventory-holdings** records. The following **Options** and **Actions** are available to bulk edit the **Suppress from discovery** field in the matching **Inventory-holdings** records:

| Options | Actions | 
| :-----: | :-----: | 
| Suppress from discovery | Set false | 
| Suppress from discovery | Set true | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.
  
8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


### Inventory - instances

In the Bulk edit app, the **Fields** that can be changed in **Inventory-instance** records include:

- **Instances and Administrative data**
   - **Administrative note**
   - **Instance note**
   - **Staff suppress**
   - **Suppress from discovery**
- **Instances and with source MARC (POC)**
   - **5xx fields**
   - **9xx fields**

#### Instances and Administrative data

##### Administrative note

To perform a bulk edit on the **Administrative note** field: 

1. Click **Actions \> Start bulk edit \> Instances and Administrative data**.
2. Under **Options**, click the drop-down list and select the **Field** you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the instance records. The following **Options** and **Actions** are available to bulk edit the **Administrative** field in the matching **Inventory-instance** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| **Administrative note** | Add note | Input text | &nbsp; | &nbsp; |
| **Administrative note** | Change note type | Select value | &nbsp; | &nbsp; |
| **Administrative note** | Find (full field search) | Input text | Remove | &nbsp; |
| **Administrative note** | Find (full field search) | Input text | Replace with | Input text |
| **Administrative note** | Remove all | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

##### Instance note

To perform a bulk edit on the **Instance note** field in the matched **Inventory-instance** records:

1. Click **Actions \> Start bulk edit \> Instances and Administrative data**.
2. Under **Options**, select the **Instance note** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Instance note** field in the matching **Inventory-instance** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: |
| *Instance note* | Add note | Input text | &nbsp; | &nbsp; |
| *Instance note* | Change note type | Select value | &nbsp; | &nbsp; |
| *Instance note* | Find (full field search) | Input text | Remove | &nbsp; |
| *Instance note* | Find (full field search) | Input text | Replace with | Input text |
| *Instance note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Instance note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Instance note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

##### Staff suppress

To suppress the matched **Inventory-instance** records from staff view in the Bulk edit app:

1. Click **Actions \> Start bulk edit \> Instances and Administrative data**.
2. Under **Options**, select **Staff suppress** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Staff suppress** option in the matching **Inventory-instance** records:

| Options | Actions | 
| :-----: | :----- |
| *Staff suppress* | Set false | 
| *Staff suppress* | Set true | 

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

##### Suppress from discovery

To suppress the matched **Inventory-instance** records from discovery in the Bulk edit app:

To perform a bulk edit on the **Suppress from discovery** field in the matched **Inventory-instance** records:

1. Click **Actions \> Start bulk edit \> Instances and Administrative data**.
2. Under **Options**, select **Staff suppress** from the drop-down list.
3. Click **Actions** to select the action you want to apply from the drop-down list. The following **Options** and **Actions** are available to bulk edit the **Suppress from discovery** field in the matching **Inventory-instance** records:

| Options | Actions | 
| :-----: | :-----: |
|  *Suppress from discovery* | Set false | 
|  *Suppress from discovery* | Set true |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. The selected action will be applied to the matched instance records. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


#### Instances with source MARC (POC)

To perform a bulk edit on the **5xx** or **9xx** fields in the matched **Inventory-instance** records:

1. Click **Actions \> Start bulk edit \> Instances with source MARC (POC)**.
2. Input the MARC field tag **only 5xx and 9xx supported**
3. Change **indicators 1 and 2** as required.
Indicate **subfield**
Click **Actions** to select the action you want to apply from the drop-down list. The following **Actions** are available to bulk edit the **5xx** or **9xx** fields in the matching **Inventory-instance** records:

| Field | ln. 1 | ln. 2| Subfield | Actions | Data | Actions | Data | Subfield | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: | :-----: |
| Input text | Input text | Input text | Add | Input text | &nbsp; | &nbsp: | &nbsp; | &nbsp: |
 &nbsp; |
| Input text | Input text | Input text | Add | Input text | Additional subfield | &nbsp: | &nbsp; | &nbsp: |
 &nbsp; |
| Input text | Input text | Input text | Find (entire subfield search) | Input text | Append | Input text | Input text | &nbsp; | &nbsp: |
| Input text | Input text | Input text | Find (entire subfield search) | Input text | Remove field | &nbsp; | &nbsp: | &nbsp; | &nbsp: |
| Input text | Input text | Input text | Find (entire subfield search) | Input text | Remove subfield | &nbsp; | &nbsp: | &nbsp; | &nbsp: |
| Input text | Input text | Input text | Replace with | Input text | &nbsp; | &nbsp: | &nbsp; | &nbsp: |
 &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. The selected action will be applied to the matched instance records. A new window will appear with a preview of the first 10 records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.

   - To return to the bulk edit, click **Keep editing**. The modal will close and you can continue editing.
   - To preview the entire list of records, click [**Download preview**](#download-matched-records). A .csv file is downloaded to your local device.
   - Click **Commit changes** to apply the bulk edit changes to the matched holdings records. The modal closes and the message at the top of the **Bulk edit** pane displays the number of successfully changed records.

8. To download the list of changed records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


### Inventory - items

In the Bulk edit app, the **Fields** that can be changed in **Inventory-item** records include:

**Administrative note**
**Check in note**
**Check out note**
**Item notes**
**Item status**
**Loan type**
**Location**
**Suppress from discovery**

To identify **Inventory-item** records for bulk edit:

1. In the **Set criteria** pane, ensure **Record types** is set to **Inventory - items**.
2. [Identify item records for bulk edit](#identify-records-for-bulk-edit) by using the **Identifier** or **Query** method.
3. [Preview the list of matching item records](#preview-matched-records) in the **Preview of record matched** pane.
4. (Optional): [Download the matched item records](#download-matched-records) as a .csv file.
5. (Optional): [Download errors in the matched item records](#download-errors) as a .csv file.


#### Administrative note

To bulk edit the **Administrative note** in the matched **Inventory-items** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Administrative note** field in the matching **Inventory-item** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: | 
| *Administrative note* | Add note | Input text | &nbsp; | &nbsp; |
| *Administrative note* | Change note type | Select value | &nbsp; | &nbsp; |
| *Administrative note* | Find (full field search) | Input text | Remove | &nbsp; |
| *Administrative note* | Find (full field search) | Input text | Replace with | Input text |
| *Administrative note* | Remove all | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Check in note

To bulk edit the **Check in note** in the matched item records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Check in note** field in the matching **Inventory-item** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: | 
| *Check in note* | Add note | Input text; Staff only checkbox | &nbsp; | &nbsp; |
| *Check in note* | Change note type | Select value | &nbsp; | &nbsp; |
| *Check in note* | Duplicate to | &nbsp; | &nbsp; | &nbsp; |
| *Check in note* | Find (full field search) | Input text | Remove | &nbsp; |
| *Check in note* | Find (full field search) | Input text | Replace with | Input text |
| *Check in note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Check in note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Check in note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


#### Check out note

To bulk edit the **Check out note** in the matched **Inventory-item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Check out note** field in the matching **Inventory-item** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: | 
| *Check out note* | Add note | Input text; Staff only checkbox | &nbsp; | &nbsp; |
| *Check out note* | Change note type | Select value | &nbsp; | &nbsp; |
| *Check out note* | Duplicate to | &nbsp; | &nbsp; | &nbsp; |
| *Check out note* | Find (full field search) | Input text | Remove | &nbsp; |
| *Check out note* | Find (full field search) | Input text | Replace with | Input text |
| *Check out note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Check out note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Check out note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


#### Item notes

To bulk edit an **Item note** in the matched **Inventory-item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Item note** field in the matching **Inventory-item** records:

| Options | Actions | Data | Actions | Data |
| :-----: | :-----: | :-----: | :-----: | :-----: | 
| *Item note* | Add note | Input text; Staff only checkbox | &nbsp; | &nbsp; |
| *Item note* | Change note type | Select value | &nbsp; | &nbsp; |
| *Item note* | Duplicate to | &nbsp; | &nbsp; | &nbsp; |
| *Item note* | Find (full field search) | Input text | Remove | &nbsp; |
| *Item note* | Find (full field search) | Input text | Replace with | Input text |
| *Item note* | Mark as staff only | &nbsp; | &nbsp; | &nbsp; |
| *Item note* | Remove all | &nbsp; | &nbsp; | &nbsp; |
| *Item note* | Remove mark as staff only | &nbsp; | &nbsp; | &nbsp; |

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.


#### Item status

To bulk edit the **item status** field in the matched **Inventory-item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Item status** field in the matching **Inventory-item** records:

[Insert table here]

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Loan type

To bulk edit the **Loan type** in the matched **Inventory-item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Loan type** field in the matching **Inventory-item** records:

[Insert table here]

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Location

To bulk edit the **Location** in the matched **Inventory-item** records:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Location** field in the matching **Inventory-item** records:

[Insert table here]

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

#### Suppress from discovery

To suppress the matched **Inventory-item** records from discovery in the Bulk edit app:

1. Click **Actions \> Start bulk edit**.
2. Under **Options**, click the drop-down list and select the field you want to edit.
3. Under **Actions**, click **Select action** and select the action you want to apply to the item records. The following **Actions** are available to bulk edit the **Suppress from discovery** field in the matching **Inventory-item** records:

[Insert table here]

4. To edit an additional field during the same bulk edit job, click the **+ sign** near the end of the row. Another row will appear under the existing row(s).
5. To remove a field, click the **trash can icon** at the end of the row you want to remove.
6. Click **Confirm changes**. A new window will appear with a preview of the first 10 item records to be changed.
7. The **Preview of records to be changed** will appear in the *Are you sure?* modal with options of **Keep editing**, **Download preview**, or **Commit changes**.
   
   - To return to the bulk edit, click **Keep editing**. The window will close and you can continue editing.
   - To preview the entire list of matched item records, click **Download preview**. A .csv file is downloaded to your local device.
   - To run the bulk edit and save changes to the matched item records, click **Commit changes**. The window closes and the banner at top of the **Bulk edit** pane displays the number of records successfully changed.

8. To download the list of changed item records, click the **Actions** button at the top right of the pane. Select **Download changed records (CSV)**. The .csv file is downloaded to your local device.

## Users


In the Bulk edit app, the **Fields** that can be changed in **User** records include:

- **Patron group - Name**
- **Active** 
- **Barcode** 
- **Created by user UUID** 
- **Created date** 
- **Date of birth**
- **Department names** 
- **Email** 
- **Enrollment date** 
- **Expiration date** 
- **External system ID**
- **First name**
- **Last name**
- **Last name, first name** 
- **Middle name** 
- **Mobile phone** 
- **Phone** 
- **Preferred contact type** 
- **Preferred first name**
- **Type** 
- **Updated by user UUID** 
- **Updated date** 
- **User UUID**
- **Username** 

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

