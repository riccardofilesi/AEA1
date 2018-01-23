# Unconventional Monetary Policies and Inequality in the EU
| **Author**|Anr |
|	--	|	--|
|Riccardo Filesi | 460856|
 *Please find [here](https://github.com/riccardofilesi/AEA1/blob/master/Welcome%20file.md) the repository* 

## Research Question
Have the post-crisis unconventional monetary policies implemented by the ECB - namely [SMP](https://www.ecb.europa.eu/pub/pdf/other/mb201006_focus01.en.pdf?2b5c64d483a41a019fd461f595a36b46), [LTROs](https://www.ecb.europa.eu/press/pr/date/2011/html/pr111208_1.en.html), [OMT](https://www.ecb.europa.eu/press/pr/date/2012/html/pr120906_1.en.html) and [QE](https://www.ecb.europa.eu/explainers/show-me/html/app_infographic.en.html) -  increased income inequalities in the EU?

# Motivation

[![Demo Doccou alpha](https://j.gifs.com/mQ8V5n.gif)](https://www.youtube.com/watch?v=tB2CM2ngpQg)
>“Within our mandate, the ECB is ready to do *whatever it takes* to preserve the euro. And believe me, it will be enough.” - [Mario Draghi, UKTI's Global Investment Conference (26th July 2012)](https://www.youtube.com/watch?v=hMBI50FXDps&t=441s)
------
The ECB is one of the main players in the Eurosystem. During the last financial crisis, it had the hard task to preserve the existence of a single currency in the Eurozone, relying in some cases on extraordinary monetary policies. Since the Euro is still in use, we can assume that such instruments have been successful in reaching their goal. But we may further study at what price the Euro has been preserved. In this sense, it is interesting to analyse the redistributive effects of unconventional monetary policies implemented over the period 2010-2015: how have they affected income differences among the EU population?



# Method
The findings of [Jaumotte et al. (2008)](https://www.imf.org/external/pubs/ft/wp/2008/wp08185.pdf) suggest that the most significant variables for
explaining change in income inequality are credit to the private sector, the
ratio of inward FDI (Foreign Direct Investment) to GDP and the industrial
employment share. The first two variables have a positive correlation with
income inequality; that is, an increase in one of the two causes an increase
in Gini, while industrial employment share is negatively associated with Gini.
Furthermore, the export-to-GDP ratio is significantly negatively correlated with Gini, which suggests that trade
globalization is associated with lower income inequality (ibid.). I also take account of inflation. Hence, I first run run the following regression, including a first and second lag of the dependent variable to solve the likely presence of autocorrelation and accounting for Inflation:

![equation](http://latex.codecogs.com/gif.latex?Concentration%3D%5Cfrac%7BTotalTemplate%7D%7BTotalVolume%7D)  
![equation]($$ Gini_t = \alpha + \beta_1 Gini_{t-1} + \beta_2 Gini_{t-2} + \beta_3 \frac{Credit_{t}}{GDP_t}  + \beta_4 \frac{FDI_{t}}{GDP_t} + \beta_5 Industrial_{t} + \beta_6 \frac{Export_{t}}{GDP_t}  $$)

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files are listed in the file explorer. You can switch from one to another by clicking a file in the list.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

Publishing in StackEdit makes it simple for you to publish online your files. Once you're happy with a file, you can publish it to different hosting platforms like **Blogger**, **Dropbox**, **Gist**, **GitHub**, **Google Drive**, **WordPress** and **Zendesk**. With [Handlebars templates](http://handlebarsjs.com/), you have full control over what you export.

> Before starting to publish, you must link an account in the **Publish** sub-menu.

## Publish a File

You can publish your file by opening the **Publish** sub-menu and by clicking **Publish to**. For some locations, you can choose between the following formats:

- Markdown: publish the Markdown text on a website that can interpret it (**GitHub** for instance),
- HTML: publish the file converted to HTML via a Handlebars template (on a blog for example).

## Update a publication

After publishing, StackEdit keeps your file linked to that publication which makes it easy for you to re-publish it. Once you have modified your file and you want to update your publication, click on the **Publish now** button in the navigation bar.

> **Note:** The **Publish now** button is disabled if your file has not been published yet.

## Manage file publication

Since one file can be published to multiple locations, you can list and manage publish locations by clicking **File publication** in the **Publish** sub-menu. This allows you to list and remove publication locations that are linked to your file.


# Markdown extensions

StackEdit extends the standard Markdown syntax by adding extra **Markdown extensions**, providing you with some nice features.

> **ProTip:** You can disable any **Markdown extension** in the **File properties** dialog.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |ASCII                          |HTML                         |
|----------------|-------------------------------|-----------------------------|
|Single backticks|`'Isn't this fun?'`            |'Isn't this fun?'            |
|Quotes          |`"Isn't this fun?"`            |"Isn't this fun?"            |
|Dashes          |`-- is en-dash, --- is em-dash`|-- is en-dash, --- is em-dash|


## KaTeX

You can render LaTeX mathematical expressions using [KaTeX](https://khan.github.io/KaTeX/):

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> You can find more information about **LaTeX** mathematical expressions [here](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference).


## UML diagrams

You can render UML diagrams using [Mermaid](https://mermaidjs.github.io/). For example, this will produce a sequence diagram:

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTQ0NDQ2NDU1NV19
-->