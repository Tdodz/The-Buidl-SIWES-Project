# What I have learned so far IN HTML
## Basics
In this section i learned about the some basic html5 tags,example;
- <!DOCTYPE html>: This tag specifies the file format of the webpage "usually line one".
- html: This is a tag used to contains every part of the web page which has to be closed"in the code, it was opened in line 2 and closed at the end of the code".
- head: this tag contains elements of the webpage that are not necessarily seen by the web page's user like the; meta, title, and some linking elements "opened in line 3 and closed in line 10".
- meta: this is used to hold some information that can not be expressed on the main webpage like; the author, the description, the character set used in the code and more "used in lines 4,5 and 6". 
- title: this contains the title of the webpage and it has to be closed"".
- link: This is used to import files within the folder of the web page "it was used to link the styling file in line 8 and also to set the icon in line 9" 
- body: This tag is used to contain all part of the web page viewed by the user "opened in line 11 and closed in line 129"
- headers: Creates headers from 1-6 which each page must have one h1.
- hr(horizontal rule)
- br(break): creates a block space
- p(paragraph): creates a new paragraph
- em(emphasis): Italicizes text to give emphasis
- strong: This is used to make text bold.
- abbr(abbreviation): Shown in line 51, this is used to give meaning to abbreviations used in the webpage.
- address: This is used in lines 63 and 65 to format addreses into the default html format.
- download:
- mail to: This is used to input an email
- lorem;: This is to create a paragraph of lorem text depending on the number of paragraphs you specify using "lorem asterisk n".
- &nbsp;: This is used to create horizontal space between text.
- &gt;: This is the greater than sign.
- &lt;: This is the less than sign.
- &copy;: This is the copyright sign.
-

## Lists
There are three types of list in html
- ol(ordered list): This creates a numbered list "opened in line 47 and closed in line 53".
- ul(unordered list): This creates a list with bullets "opened in line 62 and closed in line 67". 
*li: This is used to specify the listed items in ordered and unordered lists*
- dl(detailed list): This is used create lists which are detailed explanations/description enclosed by detailed text.
*dt(detailed text): This serves as a heading for text in a detailed list it contains the "dd" detailed description which explains the heading or elaborates on the detailes text*

## Importing Links
From the material used, in html there are three types of refernces in linking
- Absolute reference: This is entails importing links outside your server, from the web.
- Relative reference: This involves importing links within your server/ folder into your webpage.
- Internal reference: This is when you import sections of your webpage into the same webpage that is, after using the nav and section tags using hash.

## Importing images
In html we use the img tag to import images to the web page. The tag contains some information about the image being importedlike;
- src(source): This contains the image itself,the path "source" from the folder created for images.
- alt: contains description about the image in a case where it can not load.
- title: This contains the text shown when you hover around the image.
- width & height: This contains the dimension.
- loading: This specifies when the image should load wether eager"always" or lazy "when it beigng aproached".

*Note: The figure tag is used to encapsulate images to give them captions using a fig caption at the end of the image*

## Semantic tags
These are tags used to format the webpage 
- nav: This helps to group links which help navigate around a webpage. They can be multiple on a page but need to be identified using aria label "seen  opened on line 15 close on line 22". when it contains a header, it should be identified using the aria labelled by.
- section: this is used to create a section which contains various elements on the web page so it could be easily identified when being styled.
- article: This is like a section but, it defines an article on the web page. 
- h1: This is the main header of the web page and the boldest which can be identified using h1 id =.
- time datetime: this is used to input time into the web page.
- aside: This is like the side bar of the web page which contains texts that are not really important.  Details and summary work along side aside"seen from line 110 to line 115".
- mark: This is used to highlight text.

