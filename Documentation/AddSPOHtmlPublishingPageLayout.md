#Add-SPOHtmlPublishingPageLayout
Adds a HTML based publishing page layout
##Syntax
```powershell
Add-SPOHtmlPublishingPageLayout -SourceFilePath <String> -Title <String> -Description <String> -AssociatedContentTypeID <String> [-DestinationFolderHierarchy <String>] [-Web <WebPipeBind>]
```


##Parameters
Parameter|Type|Required|Description
---------|----|--------|-----------
|AssociatedContentTypeID|String|True|Associated content type ID|
|Description|String|True|Description for the page layout|
|DestinationFolderHierarchy|String|False|Folder hierarchy where the HTML page layouts will be deployed|
|SourceFilePath|String|True|Path to the file which will be uploaded|
|Title|String|True|Title for the page layout|
|Web|WebPipeBind|False|The web to apply the command to. Omit this parameter to use the current web.|
