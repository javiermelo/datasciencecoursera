Welcome to StackEdit!	{#welcome}
=====================
hhhh

Hello, I am your first Markdown document within **StackEdit**[^stackedit]. Don't delete me, I can be helpful. I can be recovered anyway in the `Utils` tab of the <i class="icon-cog"></i> `Settings` dialog.

----------


Documents
---------

**StackEdit** stores your documents in your browser, which means all your documents are automatically saved locally and are accessible **offline!**

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
Where is extra?
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
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**tBodyAccMeanY**|      4 |Average of  time domain vertical body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tBodyAccMeanZ**|      5 |Average of  time domain transverse body acceleration
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**tBodyAccStdX**|      6 |Standard deviation of  time domain horizontal body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tBodyAccStdY**|      7 |Standard deviation of  time domain vertical body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tBodyAccStdZ**|      8 |Standard deviation of  time domain transverse body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tGravityAccMeanX**|      9 |Average of  time domain horizontal gravity acceleration
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**tGravityAccMeanY**|      10 |Average of  time domain vertical gravity acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tGravityAccMeanZ**|      11 |Average of  time domain transverse gravity acceleration
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**tGravityAccStdX**|     12 |Standard deviation of  time domain horizontal gravity acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tGravityAccStdY**|     13 |Standard deviation of  time domain vertical gravity acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tGravityAccStdZ**|      14 |Standard deviation of  time domain transverse gravity acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**tBodyAccJerkMeanX**|  15 |Average of  time domain horizontal body jerk 
|                |         | Units:
|             |         |   [$g_0/s$]
**tBodyAccJerkMeanY**|  16 |Average of  time domain vertical body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**tBodyAccJerkMeanZ**|  17 |Average of  time domain transverse body jerk
|                |         | Units:
|             |         |   [$g_0/s$]
**tBodyAccJerkStdX**|     18 |Standard deviation of  time domain horizontal body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**tBodyAccJerkStdY**|     19 |Standard deviation of  time domain vertical body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**tBodyAccJerkStdZ**|     20 |Standard deviation of  time domain transverse body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**tBodyGyroMeanX**|     21 |Average of  time domain horizontal body angular velocity
|                |         | Units:
|             |         |   [$radian/s$]
**tBodyGyroMeanY**|     22 |Average of  time domain vertical body acceleration
|                |         | Units:
|             |         |    [$radian/s$]
**tBodyGyroMeanZ**|     23 |Average of  time domain transverse body acceleration
|                |         | Units:
|             |         | [$radian/s$]
**tBodyGyroStdX**|     24 |Standard deviation of time domain horizontal body angular velocity
|                |         | Units:
|             |         |   [$radian/s$]
**tBodyGyroStdY**|     25 |Standard deviation of  time domain vertical body angular velocity
|                |         | Units:
|             |         |    [$radian/s$]
**tBodyGyroStdZ**|     26 |Standard deviation of  time domain transverse body angular velocity
|                |         | Units:
|             |         |  [$radian/s$]
**tBodyGyroJerkMeanX**|     27 |Average of  time domain horizontal body angular jerk
|                |         | Units:
|             |         |   [$radian/s^3$]
**tBodyGyroJerkMeanY**|     28 |Average of  time domain vertical body angular jerk
|                |         | Units:
|             |         |    [$radian/s^3$]
**tBodyGyroJerkMeanZ**|     29 |Average of  time domain transverse body angular jerk
|                |         | Units:
|             |         | standard gravity  [$radian/s^3$]
**tBodyGyroJerkStdX**|     30 |Standard deviation of time domain horizontal body angular jerk
|                |         | Units:
|             |         |   [$radian/s^3$]
**tBodyGyroJerkStdY**|     31 |Standard deviation of  time domain vertical body angular jerk
|                |         | Units:
|             |         |    [$radian/s^3$]
**tBodyGyroJerkStdZ**|     32 |Standard deviation of  time domain transverse body angular jerk
|                |         | Units:
|             |         |  [$radian/s^3$]
**tBodyAccMagMean**|     33 |Average of  time domain vector magnitude body acceleration 
|                |         | Units:
|             |         |  standard gravity unit  [$g_0$]
**tBodyAccMagStd**|     34 |Standard deviation of  time domain vector magnitude body acceleration 
|                |         | Units:
|             |         |   standard gravity unit  [$g_0$]
**tGravityAccMagMean**|     35 |Average of  time domain gravity acceleration vector magnitude 
|                |         | Units:
|             |         | standard gravity unit  [$g_0$]
**tGravityAccMagStd**|     36 |Standard deviation of time domain gravity acceleration vector magnitude
|                |         | Units:
|             |         |  standard gravity unit  [$g_0$]
**tBodyAccJerkMagMean**|     37 |Average of  time domain body acceleration jerk vector magnitude 
|                |         | Units:
|             |         |    [$g_0/s$]
**tBodyAccJerkMagStd**|     38 |Standard deviation of  time domain body acceleration jerk vector magnitude 
|                |         | Units:
|             |         |  [$g_0/s$]
**tBodyGyroMagMean**|     39 |Average of time domain angular velocity vector magnitude 
|                |         | Units:
|             |         |  [$radian/s$]
**tBodyGyroMagStd**|     40 |Standard deviation of time domain angular velocity vector magnitude
|                |         | Units:
|             |         |   [$radian/s$]
**tBodyGyroJerkMagMean**|     41 |Average of time domain body angular jerk vector magnitude 
|                |         | Units:
|             |         |    [$radian/s^3$]
**tBodyGyroJerkMagStd**|     42 |Standard deviation of  time domain body angular jerk vector magnitude 
|                |         | Units:
|             |         |  [$radian/s^3$]
**fBodyAccMeanX**|     43 |Average of  frequency domain horizontal body acceleration
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**fBodyAccMeanY**|     44 |Average of  frequency domain vertical body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**fBodyAccMeanZ**|     45 |Average of  frequency domain transverse body acceleration
|                |         | Units:
|             |         | standard gravity unit [$g_0$]
**fBodyAccStdX**|     46 |Standard deviation of  frequency domain horizontal body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**fBodyAccStdY**|     47 |Standard deviation of  frequency domain vertical body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**fBodyAccStdZ**|     48 |Standard deviation of  frequency domain transverse body acceleration
|                |         | Units:
|             |         |  standard gravity unit [$g_0$]
**fBodyAccJerkMeanX**|  49 |Average of  frequency domain horizontal body jerk 
|                |         | Units:
|             |         |   [$g_0/s$]
**fBodyAccJerkMeanY**|  50 |Average of  frequency domain vertical body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**fBodyAccJerkMeanZ**|  51 |Average of  frequency domain transverse body jerk
|                |         | Units:
|             |         |   [$g_0/s$]
**fBodyAccJerkStdX**|     52 |Standard deviation of  frequency domain horizontal body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**fBodyAccJerkStdY**|     53 |Standard deviation of  frequency domain vertical body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**fBodyAccJerkStdZ**|     54 |Standard deviation of  frequency domain transverse body jerk
|                |         | Units:
|             |         |    [$g_0/s$]
**fBodyGyroMeanX**|     55 |Average of  frequency domain horizontal body angular velocity
|                |         | Units:
|             |         |   [$radian/s$]
**fBodyGyroMeanY**|     56 |Average of  frequency domain vertical body acceleration
|                |         | Units:
|             |         |    [$radian/s$]
**fBodyGyroMeanZ**|     57 |Average of  frequency domain transverse body acceleration
|                |         | Units:
|             |         | [$radian/s$]
**fBodyGyroStdX**|     58 |Standard deviation of frequency domain horizontal body angular velocity
|                |         | Units:
|             |         |   [$radian/s$]
**fBodyGyroStdY**|     59 |Standard deviation of  frequency domain vertical body angular velocity
|                |         | Units:
|             |         |    [$radian/s$]
**fBodyGyroStdZ**|     60 |Standard deviation of  frequency domain transverse body angular velocity
|                |         | Units:
|             |         |  [$radian/s$]
**fBodyAccMagMean**|    61 |Average of  frequency domain vector magnitude body acceleration 
|                |         | Units:
|             |         |  standard gravity unit  [$g_0$]
**fBodyAccMagStd**|     62 |Standard deviation of  frequency domain vector magnitude body acceleration 
|                |         | Units:
|             |         |   standard gravity unit  [$g_0$]
**fBodyAccJerkMagMean**|     63 |Average of  frequency domain body acceleration jerk vector magnitude 
|                |         | Units:
|             |         |    [$g_0/s$]
**fBodyAccJerkMagStd**|     64 |Standard deviation of  frequency domain body acceleration jerk vector magnitude 
|                |         | Units:
|             |         |  [$g_0/s$]
**fBodyGyroMagMean**|     65 |Average of frequency domain angular velocity vector magnitude 
|                |         | Units:
|             |         |  [$radian/s$]
**fBodyGyroMagStd**|     66 |Standard deviation of frequency domain angular velocity vector magnitude
|                |         | Units:
|             |         |   [$radian/s$]
**fBodyGyroJerkMagMean**|     67 |Average of frequency domain body angular jerk vector magnitude 
|                |         | Units:
|             |         |    [$radian/s^3$]
**fBodyGyroJerkMagStd**|     68 |Standard deviation of  frequency domain body angular jerk vector magnitude 
|                |         | Units:
|             |         |  [$radian/s^3$]





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


### Table of contents

You can insert a table of contents using the marker `[TOC]`:

[TOC]


### Comments

Usually, comments in Markdown are just standard HTML comments. <!-- like this -->
**StackEdit** extends HTML comments in order to produce useful, highlighted comments in the preview but not in your exported documents. <!--- This is very useful for collecting feedback in a collaborative document. -->


### MathJax
 
You can render *LaTeX* mathematical expressions using **MathJax**, as on [math.stackexchange.com][1]:

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall
n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> **Tip:** Make sure you include MathJax into your publications to render mathematical expression correctly. Your page/template should include something like: 

```
<script type="text/javascript" src="https://stackedit.io/libs/MathJax/MathJax.js?config=TeX-AMS_HTML"></script>
```

> **NOTE:** You can find more information:
>
> - about **Markdown** syntax [here][2],
> - about **Markdown Extra** extension [here][3],
> - about **LaTeX** mathematical expressions [here][4],
> - about **Prettify** syntax highlighting [here][5],
> - about **Highlight.js** syntax highlighting [here][6].

  [^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.

  [^gfm]: **GitHub Flavored Markdown** (GFM) is supported by StackEdit.


  [1]: http://math.stackexchange.com/
  [2]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [3]: https://github.com/jmcmanus/pagedown-extra "Pagedown Extra"
  [4]: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
  [5]: https://code.google.com/p/google-code-prettify/
  [6]: http://highlightjs.org/
