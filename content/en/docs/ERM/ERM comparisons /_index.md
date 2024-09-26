---
title: "ERM comparisons"
linkTitle: "??"
date: 2024-09-26
weight: ??
tags: ["??"]
---

The ERM comparisons app compares the contents of two diferent packages or agreements with each other to check whether there are any overlaps in content.

Definition of terms related to the ERM comparisons app:

* **Comparison.** A record that compares the content of two collections of e-resources (agreements or packages) and as a result shows, which titles are contained in which set and whether titles in the collections overlap or not.
* **Package.** A collection of e-resource titles bundled together as a unit and distributed by a provider
* **Agreement.** An agreement outlines the content your library can access.

## Permissions

The permissions listed below allow you to interact with the ERM comparisons app and determine what you can or cannot do within the app. You can assign permissions to users in the Users app. If none of these permissions are assigned to a user, they are unable to see the ERM comparisons app or any related information.

The following are all the ERM comparisons permissions:

* **ERM Comparisons: View jobs.** This permission allows the user to view existing comparisons. It also allows the user to see and access the ERM Comparisons App in the FOLIO interface.
* **ERM Comparisons: Create jobs.** This permission allows the user to create a new comparison in the ERM Comparisons App. This does not include the permission to view existing packages in the internal KB or agreements in the agreements app.
* **ERM Comparisons: Delete jobs.** This permission allows the user to delete an existing ERM comparison.

The following permissions are also needed to create a comparison:

* **Agreements: Search & view agreements.** This permission allows the user to search and view existing agreements. It also allows the user to see and access the Agreement app in the FOLIO interface.
* **Agreements: Search & view e-resources.** This permission allows the user to search and view e-resources (packages and titles in those packages) in the internal KB. This includes the permission to see and access the Agreements app in the FOLIO interface.

## Creating a comparison

1. In the **ERM comparisons** pane, click **New**.
2. Select a name.
3. Add as a first comparison point either a package or an agreement to the comparison.
4. Select a date. All titles that where an active component of the collection on this date are included in the comparison. The current day is preset by default.
5. Add as a second comparison point either a package or an agreement to the comparison.
6. Select a date. All titles that were an active component of the collection on this date are included in the comparison. The current day is preset by default.
7. Once you have included all of the information you want about the comparison, click **Save & close**. A confirmation message appears, and the comparison is saved and appears in the comparison pane. The comparison will start automatically.

## Searching for a comparison

You can search for a comparison in the **Search & filter** pane. Ti search for comparisons, enter your search terms in the search box and click **Search**. The search bos searched the name of the comparison.

You can also search for comparisons by selscting any of the filters in the **Search & filter** pane. Additionally, you can apply the filters after you perform a search to limit your results. See the sections below for more information.

###  Running status

To filter comparisons by their status, select one of the following:

* **Ended.** The comparison of the two e-resource collections is finished. The outcome/result can be checked.
* **In progress.** The comparison of the two e-resource collections is running right now.
* **Queued.** The comparison of the two e-resource collections has not started yet. It will be automatically started at somd point.

### Result

To filter comparisons by their result, select one of the following:

* **Failure.** The comparison of the two e-resource collections was not successful. The comparison report is empty.
* **Interrupted.** ????
* **Partial success.** ????
* **Success.** The comparison of the two e-resource collections was successful. A comparison report can be viewed. The report only contains titles if at least one of the two e-resource collections contained titles.

### Comparison point 1 & 2

To filter for comparisons that contain specific packages or components of a specific agreement, select one or both of the following:

* **Select agreement.** Select an existing agreement from the Agreements app.
* **Select package.** Select a package from the internal KB.

## Viewing a comparison

Once you search for a comparison, the following information apprear in the ERM comparisons pane:

* **Name.** The name of the comparison.
* **Running status.** The running status of the comparison.
* **Outcome.** The outcome of the comparison as soon as the running status is set to *ended*

In the search results, click a comparison to view it. The comparisons details pane displays the following additional information:

* **Started.** The time and date the comparison process started.
* **Ended.** The time and date the comparison process ended.
* **Errors.** The number of errors that occured during the comparison.
* **Comparison report.** The listing of the compared titles with the information in which e-resource collection the titles are and whether they overlap or not.
* **Comparison points.** The listing of the e-resouce collections (agreements and/or packages) that were being compared.
* **Error log.** ???
* **Info log.** ???

## Viewing a comparison report

To view a comparison report, click ob the comparison whose report you would like to view. In the cmoparisons details pane, click **View comparisons report**. The report displays the following information.

* **Title.** The title of each e-resource that is whether in one or the other or both packages, shown in alphabetical order.
* **Available via.** ???
* **Coverage.** ???
* **Agreement/Package #1 on MM/DD/YYYY.** ???
* **Agreement/Package #2 on MM/DD/YYYY.** ???
* **Overlap.** ???
  * **None.** ???
  * **Full.** ???
  * **???** ???

## Deleting a comparison

1. Find the comparison you want to delete.
2. In the **comparisons details** pane, click **Actions > Delete**.
3. In the **Delete comparison** dialog, click **Delete**. A confirmation message appears and the comparison is deleted.
