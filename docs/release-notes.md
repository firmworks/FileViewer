![](./quickStartImages/fileviewer.png)
[Documentation](index.md)

# FileViewer Release Notes

## 0.24 August 

### What's Nww

- Bulk Upload Function for File Tagger Button for Upload - Normally Salesforce only allow you to upload 10 files at a time but with the new Bulk File Upload feature you can upload 100X that many in a single go. 

    NOTE: If you have clickjack protection turned on you will need to add a trusted site to enable Bulk file Upload. Click [here](troubleshooting.md) for more information.

- Download Record Files Component - If you have a lot fo files in your system use this Bulk Download feature to get a zip file of all your important documents.

- Public Link Generation - Wether you want to generate a password protected public link for a single file or bulk generated public links for all your files, we have you covered. The New tabs in the FileViewer UI will allow users to create public link quicker than ever.

- File Sharing Enhancement - Sharing  file with another record in Salesforce usually takes a lot of navigation. With the sharing tab in FileViewer users can share an existing files with any other object they have access to


### Enhancements

- FileViewer Interface Update - We cleaned up the gear menu in the FileViewer component to better organize the new features that have been added in this and previous releases.
- Component Name Changes - The names of your favorite FileViewer components have been update to be more helpful when designing lightning apps.
   - Content Viewer is now Single Content Record Viewer
   - File Tag Launcher is now File Tagger Button for Upload
   - Record Content Viewer is now Tabbed Display of Record Content
- Tabbed Display of Record Content - This component can now be filtered using a configuration and can support both horizontal and vertical tabs.

### Bug Fixes

- There was a validation issue with currency fields in the List View UI for the FileViewer Component. It will say that "The entry is not a valid increment" but it sill save and update.  This no longer happens and the issue has been resolved.

--------------------------------------------------

## 0.20 - June 2022

## 0.19 - June 2022

### What's New

- Content Viewer Control - Preview pdfs, documents, videos and audio directly in lightning layouts.
- Content Viewer List - Quickly enable your users by dropping this control on a record layout to visually tab through all of the files related to a record.
- File Report Result - Define a File Viewer Report to run and drop this result set anywhere to drive activities.
- File Record Report - Define a File Viewer Report and drop this component on a record to visually tell your users whether the record is in compliance or not with the attached records.
- Schedule Reports to run which generate File Viewer Report platform events to drive the behaviors required of your organization. Create Tasks, Chatter User and more!
- New Persona Support - data entry, configure your content versions to enable users to work through a queue of documents, tagging and building usable libraries quickly and easily within one screen.

### Enhanced File Previews Using Content Viewer Components

- Integrate your files directly into your work flow, no more navigating away to view file contents.
- View documents directly on record layouts
- View supported audio and video files directly within the lightning page.
- Enhanced File Previews directly integrated into the FileViewer search screen to allow for enhanced data entry, minimizing mistakes as users have direct context to the document being viewed.

### Data Entry from Files made Easy

- File Viewer list view user interface updated to support heavy data entry from Salesforce files for auditing file content.
- Auto-complete data in rows to more easily enter large amounts of data when using the File Viewer list.
- Pagination added to lists to allow for easy navigation over hundreds of files while maintaining changes on previous pages.

### Reporting

- Enhanced experience of working with, editing and saving reports.
- New Reporting control - Configure a report for your users and deploy it into lightning pages
- New Reporting control - Configure a report and drop a record report on a layout to let your users know if the record has the appropriate documents related or not.
- Schedule reports to run regularly that publish platform events allowing your implementors to create tasks, objects, drive activities and flows to close the gap in your document lifecycle.

### Enhancements

#### File Search

- List view is now editable to assist users in data entry directly in the file search.
- List View supports side by side content viewing to facilitate easier data entry from a document into Salesforce.

#### Reports

- Reports can be scheduled to run to produce platform event to drive business process
- hook into reports using a automation to provide you users insight into data that is out of compliance.

### Bug Fixes

- You will no longer see the follow error when editing a page with a File Viewer Component:

![FileViewer 11 Configuration Name Error](images/fileviewer-11-configuration-name-error.png)


