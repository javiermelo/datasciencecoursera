
###Getting and Cleaning Data Project | Coursera
#==============================================


The purpose of this 

----------


##Study Design
#------------

The purpose of this data collection and cleaning data project is to create a summarized data set based on the "Human Activity Recognition Using SmartPhones Dataset Version 1.0" (Anguita et al., 2012).  This [dataset] is available at:

(https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)

And a [full description of data] at:

(http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

The data set result was generated trough the creation of one R script called run_analysis.R that does the following: 
1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement. 
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive variable names. 
5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

> **NOTE:**
> 
> - StackEdit is accessible offline after the application has been loaded for the first time.
> - Your local documents are not shared between different browsers or computers.
> - Clearing your browser's data may **delete all your local documents!** Make sure your documents are backed up using **Google Drive** or **Dropbox** synchronization (see [<i class="icon-share"></i> Synchronization](#synchronization) section).

#### <i class="icon-file"></i> Create a document

You can create a new document by clicking the <i class="icon-file"></i> button in the navigation bar. It will switch from the current document to the new one.

#### <i class="icon-folder-open"></i> Switch to another document

You can list all your local documents and switch from one to another by clicking the <i class="icon-folder-open"></i> button in the navigation bar.

#### <i class="icon-pencil"></i> Rename a document

You can rename the current document by clicking the document title in the navigation bar.

#### <i class="icon-trash"></i> Delete a document

You can delete the current document by clicking the <i class="icon-trash"></i> button in the navigation bar.

#### <i class="icon-hdd"></i> Save a document

You can save the current document to a file using the <i class="icon-hdd"></i> `Save as...` sub-menu from the <i class="icon-provider-stackedit"></i> menu.

> **Tip:** See [<i class="icon-share"></i> Publish a document](#publish-a-document) section for a description of the different output formats.


----------


Synchronization
---------------

**StackEdit** can be combined with **Google Drive** and **Dropbox** to have your documents centralized in the *Cloud*. The synchronization mechanism will take care of uploading your modifications or downloading the latest version of your documents.

> **NOTE:**
> 
> - Full access to **Google Drive** or **Dropbox** is required to be able to import any document in StackEdit.
> - Imported documents are downloaded in your browser and are not transmitted to a server.
> - If you experience problems exporting documents to Google Drive, check and optionally disable browser extensions, such as Disconnect.

#### <i class="icon-download"></i> Import a document

You can import a document from the *Cloud* by going to the <i class="icon-provider-gdrive"></i> `Google Drive` or the <i class="icon-provider-dropbox"></i> `Dropbox` sub-menu and by clicking `Import from...`. Once imported, your document will be automatically synchronized with the **Google Drive** / **Dropbox** file.

#### <i class="icon-upload"></i> Export a document

You can export any document by going to the <i class="icon-provider-gdrive"></i> `Google Drive` or the <i class="icon-provider-dropbox"></i> `Dropbox` sub-menu and by clicking `Export to...`. Even if your document is already synchronized with **Google Drive** or **Dropbox**, you can export it to a another location. **StackEdit** can synchronize one document with multiple locations.

> **Tip:** Using **Google Drive**, you can create collaborative documents to work in real time with other users. Just check the box `Create a real time collaborative document` in the dialog options when exporting to Google Drive.

#### <i class="icon-refresh"></i> Synchronize a document

Once your document is linked to a **Google Drive** or a **Dropbox** file, **StackEdit** will periodically (every 3 minutes) synchronize it by downloading/uploading any modification. Any conflict will be detected, and a local copy of your document will be created as a backup if necessary.

If you just have modified your document and you want to force the synchronization, click the <i class="icon-refresh"></i> button in the navigation bar.

> **NOTE:** The <i class="icon-refresh"></i> button is disabled when you have no document to synchronize.

#### <i class="icon-refresh"></i> Manage document synchronization

Since one document can be synchronized with multiple locations, you can list and manage synchronized locations by clicking <i class="icon-refresh"></i> `Manage synchronization` in the <i class="icon-provider-stackedit"></i> menu. This will open a dialog box allowing you to add or remove synchronization links that are associated to your document.

> **NOTE:** If you delete the file from **Google Drive** or from **Dropbox**, the document will no longer be synchronized with that location.

----------


Publication
-----------

Once you are happy with your document, you can publish it on different websites directly from **StackEdit**. As for now, **StackEdit** can publish on **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **Tumblr**, **WordPress** and on any SSH server.

#### <i class="icon-share"></i> Publish a document

You can publish your document by going to the <i class="icon-share"></i> `Publish on` sub-menu and by choosing a website. In the dialog box, you can choose the publication format:

- Markdown, to publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML, to publish the document converted into HTML (on a blog for instance),
- Template, to have a full control of the output.

> **NOTE:** The default template is a simple webpage wrapping your document in HTML format. You can customize it in the `Services` tab of the <i class="icon-cog"></i> `Settings` dialog.

#### <i class="icon-share"></i> Update a publication

After publishing, **StackEdit** will keep your document linked to that publish location so that you can update it easily. Once you have modified your document and you want to update your publication, click on the <i class="icon-share"></i> button in the navigation bar.

> **NOTE:** The <i class="icon-share"></i> button is disabled when the document has not been published yet.

#### <i class="icon-share"></i> Manage document publication

Since one document can be published on multiple locations, you can list and manage publish locations by clicking <i class="icon-share"></i> `Manage publication` in the <i class="icon-provider-stackedit"></i> menu. This will open a dialog box allowing you to remove publication links that are associated to your document.

> **NOTE:** In some cases, if the file has been removed from the website or the blog, the document will no longer be published on that location.

----------


Markdown Extra
--------------

**StackEdit** supports **Markdown Extra**, which extends **Markdown** syntax with some nice features.

> **Tip:** You can disable any **Markdown Extra** feature in the `Extensions` tab of the <i class="icon-cog"></i> `Settings` dialog.


### Tables

**Markdown Extra** has a special syntax for tables:

Variable  | Position | Description                    
--------- | :--:  | -----
**activity**   |      1  |Activity performed by the volunteer|
|              |         | Values:
|              |         | WALKING
|              |         |WALKING UPSTAIRS
|              |         |WALKING DOWNSTAIRS
|              |         |SITTING
|              |         |STANDING
|              |         |LAYING
**subjectId**  |      2 |Sequential identinfying the volunteer
|              |         | Values:
|              |         | (1<= subjectId <= 30)
**tBodyAccMeanX**|      3 |Average of  time domain horizontal body acceleration
**tBodyAccMeanY**|      4 |Average of  time domain vertical body acceleration
**tBodyAccMeanZ**|      5 |Average of  time domain transverse body acceleration
**tBodyAccStdX**|      6 |Standard deviation of  time domain horizontal body acceleration
**tBodyAccStdY**|      7 |Standard deviation of  time domain vertical body acceleration
**tBodyAccStdZ**|      8 |Standard deviation of  time domain transverse body acceleration
**tGravityAccMeanX**|      9 |Average of  time domain horizontal gravity acceleration
**tGravityAccMeanY**|      10 |Average of  time domain vertical gravity acceleration
**tGravityAccMeanZ**|      11 |Average of  time domain transverse gravity acceleration
**tGravityAccStdX**|     12 |Standard deviation of  time domain horizontal gravity acceleration
**tGravityAccStdY**|     13 |Standard deviation of  time domain vertical gravity acceleration
**tGravityAccStdZ**|      14 |Standard deviation of  time domain transverse gravity acceleration
**tBodyAccJerkMeanX**|  15 |Average of  time domain horizontal body jerk 
**tBodyAccJerkMeanY**|  16 |Average of  time domain vertical body jerk
**tBodyAccJerkMeanZ**|  17 |Average of  time domain transverse body jerk
**tBodyAccJerkStdX**|     18 |Standard deviation of  time domain horizontal body jerk
**tBodyAccJerkStdY**|     19 |Standard deviation of  time domain vertical body jerk
**tBodyAccJerkStdZ**|     20 |Standard deviation of  time domain transverse body jerk
**tBodyGyroMeanX**|     21 |Average of  time domain horizontal body angular velocity
**tBodyGyroMeanY**|     22 |Average of  time domain vertical body acceleration
**tBodyGyroMeanZ**|     23 |Average of  time domain transverse body acceleration
**tBodyGyroStdX**|     24 |Standard deviation of time domain horizontal body angular velocity
**tBodyGyroStdY**|     25 |Standard deviation of  time domain vertical body angular velocity
**tBodyGyroStdZ**|     26 |Standard deviation of  time domain transverse body angular velocity
**tBodyGyroJerkMeanX**|     27 |Average of  time domain horizontal body angular jerk
**tBodyGyroJerkMeanY**|     28 |Average of  time domain vertical body angular jerk
**tBodyGyroJerkMeanZ**|     29 |Average of  time domain transverse body angular jerk
**tBodyGyroJerkStdX**|     30 |Standard deviation of time domain horizontal body angular jerk
**tBodyGyroJerkStdY**|     31 |Standard deviation of  time domain vertical body angular jerk
**tBodyGyroJerkStdZ**|     32 |Standard deviation of  time domain 
**tBodyAccMagMean**|     33 |Average of  time domain vector magnitude body acceleration 
**tBodyAccMagStd**|     34 |Standard deviation of  time domain vector magnitude body acceleration 
**tGravityAccMagMean**|     35 |Average of  time domain gravity acceleration vector magnitude 
**tGravityAccMagStd**|     36 |Standard deviation of time domain gravity acceleration vector magnitude
**tBodyAccJerkMagMean**|     37 |Average of  time domain body acceleration jerk vector magnitude 
**tBodyAccJerkMagStd**|     38 |Standard deviation of  time domain body acceleration jerk vector magnitude 
**tBodyGyroMagMean**|     39 |Average of time domain angular velocity vector magnitude 
**tBodyGyroMagStd**|     40 |Standard deviation of time domain angular velocity vector magnitude
**tBodyGyroJerkMagMean**|     41 |Average of time domain body angular jerk vector magnitude 
**tBodyGyroJerkMagStd**|     42 |Standard deviation of  time domain body angular jerk vector magnitude 
**fBodyAccMeanX**|     43 |Average of  frequency domain horizontal body acceleration
**fBodyAccMeanY**|     44 |Average of  frequency domain vertical body acceleration
**fBodyAccMeanZ**|     45 |Average of  frequency domain transverse body acceleration
**fBodyAccStdX**|     46 |Standard deviation of  frequency domain horizontal body acceleration
**fBodyAccStdY**|     47 |Standard deviation of  frequency domain vertical body acceleration
**fBodyAccStdZ**|     48 |Standard deviation of  frequency domain transverse body acceleration
**fBodyAccJerkMeanX**|  49 |Average of  frequency domain horizontal body jerk 
**fBodyAccJerkMeanY**|  50 |Average of  frequency domain vertical body jerk
**fBodyAccJerkMeanZ**|  51 |Average of  frequency domain transverse body jerk
**fBodyAccJerkStdX**|     52 |Standard deviation of  frequency domain horizontal body jerk
**fBodyAccJerkStdY**|     53 |Standard deviation of  frequency domain vertical body jerk
**fBodyAccJerkStdZ**|     54 |Standard deviation of  frequency domain transverse body jerk
**fBodyGyroMeanX**|     55 |Average of  frequency domain horizontal body angular velocity
**fBodyGyroMeanY**|     56 |Average of  frequency domain vertical body acceleration
**fBodyGyroMeanZ**|     57 |Average of  frequency domain transverse body acceleration
**fBodyGyroStdX**|     58 |Standard deviation of frequency domain horizontal body angular velocity
**fBodyGyroStdY**|     59 |Standard deviation of  frequency domain vertical body angular velocity
**fBodyGyroStdZ**|     60 |Standard deviation of  frequency domain transverse body angular velocity
**fBodyAccMagMean**|    61 |Average of  frequency domain vector magnitude body acceleration 
**fBodyAccMagStd**|     62 |Standard deviation of  frequency domain vector magnitude body acceleration 
**fBodyAccJerkMagMean**|     63 |Average of  frequency domain body acceleration jerk vector magnitude 
**fBodyAccJerkMagStd**|     64 |Standard deviation of  frequency domain body acceleration jerk vector magnitude 
**fBodyGyroMagMean**|     65 |Average of frequency domain angular velocity vector magnitude 
**fBodyGyroMagStd**|     66 |Standard deviation of frequency domain angular velocity vector magnitude
**fBodyGyroJerkMagMean**|     67 |Average of frequency domain body angular jerk vector magnitude 
**fBodyGyroJerkMagStd**|     68 |Standard deviation of  frequency domain body angular jerk vector magnitude 
|**Note 1: Variables from postion 3 to 68 are normalized and bounded within [-1,1]**| |
|**Note 2: Values of the variables are actually averages of the calculated features for each activity performed by each volunteer





You can specify column alignment with one or two colons:

| Item      |    Value | Qty  |
| :-------- | --------:| :--: |
| Computer  | 1600 USD |  5   |
| Phone     |   12 USD |  12  |
| Pipe      |    1 USD | 234  |


### Definition Lists

**Markdown Extra** has a special syntax for definition lists too:

Term 1
Term 2
:   Definition A
:   Definition B

Term 3

:   Definition C

:   Definition D

	> part of definition D


### Fenced code blocks

GitHub's fenced code blocks[^gfm] are also supported with **Prettify** syntax highlighting:

```
// Foo
var bar = 0;
```

> **Tip:** To use **Highlight.js** instead of **Prettify**, just configure the `Markdown Extra` extension in the <i class="icon-cog"></i> `Settings` dialog.


### Footnotes

You can create footnotes like this[^footnote].

  [^footnote]: Here is the *text* of the **footnote**.


### SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                  | ASCII                                    | HTML                                |
 ------------------|------------------------------------------|-------------------------------------
| Single backticks | `'Isn't this fun?'`                      | &#8216;Isn&#8217;t this fun?&#8217; |
| Quotes           | `"Isn't this fun?"`                      | &#8220;Isn&#8217;t this fun?&#8221; |
| Dashes           | `-- is an en-dash and --- is an em-dash` | &#8211; is an en-dash and &#8212; is an em-dash |


