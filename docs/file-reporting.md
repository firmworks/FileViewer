![](./quickStartImages/fileviewer.png)
[Documentation](index.md)

# File Reporting

## Configuration and Setup

All System Administrator based profiles can see the File Report tab after installation. To allow other users to see the tab you will need to assign them the **FileViewer Reporting** permission set. To assign a permission set please follow the documentation from Salesforce (https://help.salesforce.com/s/articleView?id=sf.perm_sets_assigning.htm).

## Using Quick Reports

Start off by clicking the Show Quick Reports toggle to see some out of box reports based on standard Sales Cloud objects (Accounts, Contacts, and Opportunities). 

![FileViewer Report Quick Reports](images/fileviewer-reporting-quick-reports1.png)

Once the Quick Reports UI is open click the eye icon to the left of a report to fill in the criteria in the sections below.

![FileViewer Report Quick Report Filters](images/fileviewer-reporting-quick-reports2.png)

Clicking Run Report will return results from your org based on the filters established by the Quick Report selected.

![FileViewer Report Quick Report Results](images/fileviewer-reporting-quick-reports3.png)

From here you can save reports, add/remove filters, change the record to return criteria, and interact with result records.

### Saving Reports
The button on the top right of the Quick Reports section will save the current filters of the report in to a new Quick Report. This will start a save event that will commit the report to the database and make it available in the Quick Reports menu.

Clicking the Save This Report button will prompt you to provide a Report Description. Once provided click save to proceed. The deployment will start and once completed it will show in the Quick Reports list.

![FileViewer Report Quick Report Saving](images/fileviewer-reporting-saving1.gif)

### Adding or Removing Filters

To add a filter to the Selected Object in Step 1, click on the Add a Filter For <Selected Object Label> button on the top right. Once the filter row has been added selected the field from the Field Name selection, choose an Evaluation criteria, and set a value. For more help on supported values click the question mark at the end of the row.

![FileViewer Reporting Filters](images/fileviewer-reporting-filters1.png)

You can also change the Selected Object by using the Selected Object drop down. This will remove all of the current filters, so make sure to save your changes before modifying the Selected Object.

To remove a filter click the trashcan next to the filter row you wish to remove. 

Follow the same steps above to add or remove a filter from the tagged documents section in Step 2.

### Record Return Criteria

![FileViewer Reporting Included Records](images/fileviewer-reporting-included-records1.png)

The buttons in Step 3 will allow you to change the returned record set. 

- **All Records** - This will return all records that fulfill the selected object criteria in Step 1.
- **Records With Documents** - This will return all records that fulfill the selected object criteria in Step 1 and have documents that meet the criteria in Step 2.
- **Records Without Documents** - This will return all records that fulfill the selected object criteria in Step 1 and do not have documents that meet the criteria in Step 2. 

### Results Buttons

![FileViewer Reporting Results](images/fileviewer-reporting-download1.png)

- **Run Report** -  This button will run the report. When clicked it will go retrieve the data set again and capture any new records that should be returned based on the criteria.
- **Download** - This button will download an Excel sheet with metadata on the Content Version records returned in the Results section.
- **Download Files** - This button will download a zip file containing all the documents returned in the Results section.
- **View Details** - This button will open a new window to that rows Selected Objects Salesforce Record.
## Creating Custom Reports

Instead of using Quick Reports, a custom report can be created to store reports for specific business needs. To create a new report choose an object from the Select Object section in Step 1. Next add filters to that object and the docmuents you want to see in Step 2 and Step 3, respectively. Then choose which results you want to return in Step 4 and click Run Report.

![FileViewer Reporting Custom Report Creation](images/fileviewer-reporting-custom-reports1.gif)

You can save this report for future use using the same steps in the [Saving Reports](#saving-reports) above.

___

[FileViewer FAQ](https://getfirmworks.com/#faq)

![](./quickStartImages/image1.jpeg)

For FileViewer Support, please contact <support@getfirmworks.com>
