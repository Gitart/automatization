# 19 Useful Google Apps Scripts to Automate Google Drive

By [Ashutosh KS](https://www.hongkiat.com/blog/author/ashutosh_ks/) in [Internet](https://www.hongkiat.com/blog/category/internet/). Updated on August 14, 2020.

Google Drive offers great features for storing and working with different types of files but it does lack some features that are crucial for your work. Google Apps Scripts is an easy\-to\-use scripting language to **get things done**, which are otherwise not available in Drive.

There are scripts that can let you read/extract text from images, convert files, auto\-backup social photos or store Gmail attachments. Most scripts let you automate these services as well.

Let’s check out how to make use of Google Apps Scripts to **fill the missing holes** in Google Drive and do many more things without third\-party tools.

[5 Best Free Android Apps to Help Automate Tasks](https://www.hongkiat.com/blog/apps-to-automate-android/ "Read More: 5 Best Free Android Apps to Help Automate Tasks")

#### 5 Best Free Android Apps to Help Automate Tasks

One thing most people love about Android is the freedom to create that is open source identity affords... Read more

#### How to Run Google Apps Scripts

To create and run a script in Drive, follow these steps:

1.  Create/open a Google Doc or Sheet. From **Tools** menu, select **Script editor**.
2.  Remove existing code and add your code. Go to **File** > **Save** > add script name > Click **OK**.
3.  To execute, click ►, or from the **Run** menu, select a function. If running the script for first time, it will ask for your authentication. Check the required permissions and click *Allow*.
4.  A yellow bar will appear at the centre\-top, to indicate that the script is running.

Please note these steps are for general scripts and certain scripts may require specific additional instructions to run.

##### 1\. [Convert and Email Google Sheets](https://ctrlq.org/code/19869-email-google-spreadsheets-pdf)

**What it does:**

*   Converts **Google Sheets to** PDF and **mails them** using your Gmail account
*   Lets you **convert and send just one sheet** using its sheet id.
*   Send the PDF to **multiple persons** by adding their addresses, separated by commas.

**Use Case Scenario:**

It’s helpful in scenarios like when you wish to send marketing data to a third party but don’t want to share the whole spreadsheet. You can use this script to send a PDF version. This way required data is shared without compromising your whole spreadsheet’s info.

##### 2\. [Convert Images to Text using OCR](https://gist.github.com/tagplus5/07dde5ca61fe8f42045d)

**What it does:**

*   **Converts images to text** documents using the OCR technology; saves them in your drive.

**Use Case Scenario:**

This script proves beneficial in situations when you need to edit text in imges or do research on a large number of images. It makes the converted images editable and searchable. It saves your time and efforts and gives trustworthy text output as it uses the Google’s native OCR technology.

##### 3\. [Track File Editors in Google Drive](https://ctrlq.org/code/20060-monitor-file-changes-in-drive)

**What it does:**

*   Finds out which user made changes to your Google Drive’s native files.
*   Displays the dates and times when the file was modified **along with the name and email address** of users who made the changes to your shared documents/files.

**Use Case Scenario:**

This script is useful for tracking the modifications made in your drive, including Sheets, Documents, Presentations and other Google Drive formats.

##### 4\. [Save a Webpage to Google Drive](https://github.com/hijonathan/google-scripts/blob/master/backup-url.js)

**What it does:**

*   **Saves or backs up webpage** on any URL to Google Drive.
*   Fetches the web page and **saves the same as HTML** file (by default) or your configured extension.
*   Maintains a nice **folder structure** for storing multiple web pages or their copies.

**Use Case Scenario:**

This script is most helpful for researchers, scholars, bloggers and such who need to research lots of websites and might need to save them for future reference. Do remember to change the *RESOURCE\_URL* in the snippet to the link you wish to download.

##### 5\. [Send a Google Doc via Email](https://gist.github.com/erickoledadevrel/11143648)

**What it does:**

*   Sends a Google Doc through email to anyone and places the **doc’s content as the email’s body** (rather than an attachment).
*   Converts the **doc to HTML** and sends the same via email

**Use Case Scenario:**

If you want to send something not as an attachment but as part of the email, this is the that gets the job done. Do note you must change *documentId, recipient, subject* to their actual values in the 4th line.

##### 6\. [Host a Website on Google Drive](http://www.labnol.org/internet/host-website-on-google-drive/28178/)

**What it does:**

*   **Host any static website** including files like HTML, CSS, JS, image, podcast, etc on Google Drive. (Drive can’t be used to serve dynamic sites like those using PHP or Java backends.)

**Use Case Scenario:**

This script is useful when you don’t wish to buy a hosting plan or domain for your site. It’s completely free of charge and Google’s servers are a lot faster than many hosting providers in the world.

##### 7\. [Download Instagram Photos to Drive](https://sites.google.com/site/appsscripttutorial/home/downloading-instagram-photos-to-your-google-drive-using-google-apps-script)

**What it does:**

*   Downloads **multiple Instagram photos** and save them to your drive automatically.
*   **Download photos using certain tags** or from any specific Instagram URL.
*   Images are kept in a separate folder in Drive for easy maintenance.

**Use Case Scenario:**

It’s helpful for Instagram fans, collectors and researchers who maintain data backups in Drive.

##### 8\. [Convert a](https://github.com/mangini/gdocs2md) [Google Doc](https://github.com/mangini/gdocs2md) [to Markdown](https://github.com/mangini/gdocs2md)

**What it does:**

*   Converts a Google Doc to the **markdown (.md) format**.
*   It mails you the converted document along with images automatically. (Note it may get into problems with data using complex formatting.)

**Use Case Scenario:**

It’s useful for bloggers and publishers who regularly use the markdown format for publishing online. Using this, they can avoid manual work of converting their content for every draft.

##### 9\. [Set Auto\-Expiry for Shared Data](http://www.labnol.org/internet/auto-expire-google-drive-links/27509/)

**What it does:**

*   **Sets an auto\-expiry** interval on the shared files and folders in Drive
*   Automatically **removes access to other users** after the certain period (of auto\-expiry).

**Use Case Scenario:**

This script is useful for allowing limited access to your drive’s data and relieves you from worrying about forgetting to unshare data. This feature is already available for *Google Apps for Work* users, but if you’re free user, then it’s for you.

##### 10\. [Save Gmail Attachments in Drive](http://www.googleappsscript.org/home/fetch-gmail-attachment-to-google-drive-using-google-apps-script)

**What it does:**

*   Extracts and **saves all Gmail attachments to a particular folder** in your drive.
*   **Notify progress** of fetched attachments, via email but requires setting up notification preferences.

**Use Case Scenario:**

If you prefer to store attachments into cloud storages like Drive, then this is the script to get.

##### 11\. [Search All Files in Google Drive](https://www.labnol.org/code/19982-search-files-in-google-drive)

**What it does:**

*   **Searches all your files** in the drive and displays the results in simple\-to\-digest style in a Google Sheet.
*   Supports docs, sheets, presentations and few other text formats.

**Use Case Scenario:**

Search through your files and piles of data quickly with this.

##### 12\. [List Directory in Google Drive](https://gist.github.com/mesgarpour/07317e81e9ee2b3f1699)

**What it does:**

*   Lists all **files and folders** of a Google Drive’s **directory** recursively
*   Write this data in easy\-to\-see format in a spreadsheet.

**Use Case Scenario:**

Good for making sense of all the data in your Drive, and for file management purposes. Do note that for this script to work, you must set the *folderId* first in the code. A folder id is everything after the Ã¢Â€Â˜*folders/*‘ portion of a folder’s address.

##### 13\. [Convert Google Docs to HTML](https://gist.github.com/soundTricker/4688073)

**What it does:**

*   Converts **Google Docs to HTML format** for easy sharing or using in web pages or source code editors.
*   Supports various basic HTML tags or formatting options but do understand it doesn’t work very well for complex text formatting.

**Use Case Scenario:**

Helpful mostly for writers, bloggers and publishers seeking posts for HTML\-ready tools. Do remember to set the *KEY and FILE\_ID* variables in the code.

##### 14\. [Combine Data from Multiple Sheets](https://gist.github.com/mhawksey/2252211)

**What it does:**

*   Merges data from **multiple sheets of a particular spreadsheet** into a single sheet in the current spreadsheet.

**Use Case Scenario:**

This script is helpful in situations wherein you have got multiple sheets of common data (including common headers and structure) and you wish to combine them into one large sheet of data.

##### 15\. [Export Google Sheets to CSV Files](https://gist.github.com/mderazon/9655893)

**What it does:**

*   Exports sheets in the current spreadsheet as **individual CSV files** in Drive.

**Use Case Scenario:**

It’s helpful for people who regularly use Sheets for managing and storing data and require data in CSV format for sharing or use in other apps. Without this, Google Sheets only convert and download one sheet at a time.

After copying code into the Script Editor, re\-open that spreadsheet and check the **Add\-ons** menu.

##### 16\. [Convert a Google Sheet to PDF Invoice](https://gist.github.com/gregorynicholas/9008572)

**What it does:**

*   Converts any particular sheet to a **PDF invoice** and save to your Drive.

**Use Case Scenario:**

Good for users who regularly use the Google Apps ecosystem as their work tool and have to deal with product invoices and such.

##### 17\. [Upload a URL directly to Google Drive](https://gist.github.com/denilsonsa/8134679)

**What it does:**

*   **Uploads any individual file** (or multiple files) **from a specific URL** to your drive automatically.
*   **Files are saved in a specific folder** in the drive and it can easily upload multiple files from multiple links provided it’s given one at a time.

**Use Case Scenario:**

For people who like to keep data from the Web in Drive. All it needs is the link of the page you need. To use, copy code into the Script Editor and go to **Publish** > **Deploy as web app…**

##### 18\. [Download Google+ Profiles to Google Sheets](https://gist.github.com/printminion/1919613)

**What it does:**

*   **Fetches publicly available Google+ profiles’ data** to a Google Sheet. The fetched data includes **name, work info, profile picture** and more.
*   The only input it requires is the profile id of the person you wish to get data about and this works for multiple profiles.

**Use Case Scenario:**

This is extremely helpful for data entry and social media analysts for data collection.

##### 19\. [Convert PDF Attachments to Plain Text](https://gist.github.com/mogsdad/e6795e438615d252584f)

**What it does:**

*   Converts all **PDF** attachments from Gmail to **plain text format** for easy sharing/storing
*   You can **specify the PDF’s original language** (for extracting the text) and **save the output plain text files** along with the **original PDF** files in Google Drive.

**Use Case Scenario:**

You regularly receive PDFs via mails and want to save them in Drive in original or plain text form. It does the job in batches.

How did you find this list? Do you know any more Google Apps Scripts which help ease life of a Drive user? Please let us know using the comments section below.
