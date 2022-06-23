![](./quickStartImages/fileviewer.png)
[Documentation](index.md)

# Knows Issue

## 0.15 - June 2022 Release

#### File Viewer List View Validation Issue
![FileViewer 11 Upgrade Issue](images/june22-knownissue-currency-validation.gif)

There is a validation issue with currency fields in the List View UI for the FileViewer Component. It will say that "The entry is not a valid increment" but it sill still save adn update. This validation can be ignored and will be fixed next release.

#### File Tagger Component Changes
![FileViewer 11 Upgrade Issue](images/fileviewer-11-upgrade-error.png)

- Moving forward the File Tagger is no longer able to be used in page layouts. If you experience the above error installing the new package you will need to do the following.

   - Remove any uses of the File Tag Launcher component from page layouts and Experiences. Republish any Experiences you removed uses from. 
   - Remove any uses of the File Tagger component from page layouts. They will need to recreated later as File Tag launcher buttons so keep track of your Design Settings, 
   - Remove from page layouts and delete any Custom Actions that reference the FileTaxonomy component.

- Once you install the new package you will need to recreate what you removed so please make sure to keep track of all of the use cases.

