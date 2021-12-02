# ZivGlobalTrader
Website for Trading business.
Below are the instructions for the assignment.

INFO151 Homework Assignment 3
* Homework Assignment is to be completed individually.
All homework assignments in this course will gradually help you develop and enrich a website of a
business (e.g. company/organization/creative contents display etc.) that you dream to build and
present, which can provide information and services. (e.g. eCommerce, school, personal site, … use
your imagination, and any humor is also appreciated)
In this third homework assignment, let’s create a tiny website by expanding your “About”
webpage!
Based upon your previously enhanced “About” webpage, after practicing the skills and syntaxes you’ve
learned for web development in one single webpage, now it’s time to expand the contents you want to
deliver into more webpages and compose a website.
Please freely make your own creative ideas to show off any relative contents and style!
Requirements Overview:
In the design and implementation of this website, utilize the correct syntaxes that we’ve learned
so far including:
• Website composition
• File organization
• Semantic Elements
• External CSS
• External JS
• float, clear, display
• Box model
• iframe
• Validation/Debug
You must use all the above items, but you can utilize more than one of each of those
elements, and in any order as you wish, to construct the your webpages, and with proper
comments.
Assignment itemized requirements:
Following requirements must be fulfilled:
Website organization:
Create a new subfolder locally and remotely (e.g. …/HW3/) dedicated to this assignment 3 to host
your website related html files as well as corresponding files (e.g. image files, .css files, .js files etc.)
This website of yours should contain AT LEAST 2 html files, 1 css file, and 1 js file. Of course, you are
free to design more.
• Among the html files:
o one should be your previous enhanced “about” html document,
o you will create at least one another html document to serve as the “home”(index)
webpage.
o You are welcomed to design and create additional more webpages for the website
of your business.
Users should be able to browse your website through the “home” webpage as the enter
point, and get navigated to all your other webpages through navigation bar (links).
• For the external css and js files: you should create AT LEAST ONE for each of the css and js.
Remember to use correct syntax for document comments respectively in html, css, and js
file on top of the file providing the document information/description such as project
purpose, author, date, etc…
• You can organize your all files for your website in a dedicated folder (the root folder for the
website) in different ways. From "placing all type of files in the root folder without any
subfolders", to "group different type of files in different subfolders under the root folder.
Either way, make sure the relative path is composed correctly, such as using "../" to go one
level upper to the parent folder.
File naming:
• ALL file names should have your Drexel ID abc123 as postfix, For example :
▪ index_abc123.html
▪ about_abc123.html
▪ contact_abc123.html
▪ survey_abc123.html
▪ …
▪ style_abc123.css
▪ …
▪ functions_abc123.js
▪ …
• EACH webpage should show, when being rendered/displayed, a title in the web browser’s
tab (use the <title> tag) with your Drexel ID abc123 as postfix, For example:
▪ index_abc123
▪ about_abc123
▪ …
File uploading:
After finishing your webpage development locally, you will upload all files to your account in the Tux
server and submit the webpage URL to Bblearn course shell.
• Create a new subfolder in your remote Tux server for this assignment under the
"public_html" folder.
• Upload ALL your files into that subfolder, and submit the corresponding URL to Bblearn.
Upload each file respectively or upload the whole folder at once, would require different
parameter for the command scp.
• IF the local folder you created to develop the website is “…/HW3/” and which host all
your related files as the root folder,
and your remote folder on Tux server is “…/public_html/INFO151/HW3”,
then to upload each of your local files in local HW3 folder to the remote
INFO151/HW3 folder, you will use following command.
So afterwards you will have the remote URL, for example, for ***\HW3\xxx.html as
***/INFO151/HW3/xxx.html
scp C:\***\HW3\xxx.html abc123@tux.cs.drexel.edu:public_html/INFO151/HW3
• IF you want to instead upload the whole “…/HW3/” local folder at once, then, you will
use the following command with the parameter -r, to upload local HW3 folder as a
whole, but should be upload to the remote /INFO151 folder instead of the
INFO151/HW3 folder.
So afterwards you will have the remote URL for, for example, xxx.html as
***/INFO151/HW3/xxx.html
scp -r C:\***\HW3 abc123@tux.cs.drexel.edu:public_html/INFO151
• Otherwise if you use following scp command, it will upload local HW3 folder under the
remote /INFO151/HW3 folder.
So afterwards you will have the remote URL for, for example, xxx.html as
***/INFO151/HW3/HW3/xxx.html Be Careful !
scp -r C:\***\HW3 abc123@tux.cs.drexel.edu:public_html/INFO151/HW3
URL submitting:
o IF the name of your new subfolder hosting your website inside "public_html" is
"subfolder_a/ subfolder_b", and the html file you uploaded into subfolder_b is
"webpage.html", then, the URL (that can be visited on the Web) to be submitted to
Bblearn will be
"https://www.cs.drexel.edu/~abc123/subfolder_a/ subfolder_b/webpage.html"
o For example, if your Drexel ID is "abc123", and the path of the subfolder in Tux
that you created for this assignment is "public_html/INFO151/HW3", and the
filename of the “home” html you uploaded to the subfolder in Tux is "
index_abc123.html", then, the URL you want to submit should be:
"https://www.cs.drexel.edu/~abc123/INFO151/HW3/index_abc123.html"
▪ Don’t miss the tilde symbol in front of your ID "~";
▪ Match the letter capitalization in the URL carefully to the capitalization
of the name of subfolders that you actual created in the Tux server.

Indentation and Comments:
The requirements on the code indentation and comments are the same as previous
assignment, which you can also refer to the Reference in the end of this instruction document.
Itemized requirements with inspiring example and suggestions:
1. Layout using HTML5 Semantic Elements
Utilize HTML5 Semantic Elements to arrange and implement the layouts of each of your
webpages.
(e.g., you will be able to later apply style rules to each semantic element block by selecting
them, instead selecting traditional div element blocks.)
2. External CSS for multiple webpages
Create at least one external css file to control the style of all your html documents.
(e.g., to unify the theme you designed for your website; one selector in the external CSS can
select and apply the same style rules on same elements selected from multiple different html
documents.)
You may also have additional css file(s) for a specific webpage, maybe to overwrite some styles
on certain element(s) according to the rule of cascading priorities.
3. Use float (and clear – if necessary) property for layout
Apply float (and clear - if necessary) property at least once for your layout design.
(e.g., to display block level elements in same line, or block of contents displayed in column side
by side..)
Remember to apply css comment with the itemized number (i.e. #3) above your codes fulfilling
this requirement in related css file(s).
4. Navigation bar in each webpage
Put a navigation bar in each of your webpage to link all of your webpages, so user can click and
access any webpage of your website.
(e.g. you can design the navigation bar in any place of the webpage, and e.g. displayed vertically,
or horizontally, on top, or on left/right side, or… )
Remember to apply html comment with the itemized number (i.e. #4) above your codes
fulfilling this requirement in each related html document.
5. Highlight links in navigation bar when hover the mouse
Make each link in the navigation bar being highlighted (style change) when user move and hold
the mouse on it.
(e.g. the highlight could be changes of: background color, or font size, or color, or emphasize …
or any combined changes )
Remember to apply css comment with the itemized number (i.e. #5) above your codes fulfilling
this requirement in related css file(s).
6. Change element block/inline level
Utilize the display property on at least one element to change the level of the element(s), from
the block-level to inline-level, or vice versa.
Especially when you have inline element structured as parent of block element as the child, you
need to change the level of one of the element.
Remember to apply css comment with the itemized number (i.e. #6) above your codes fulfilling
this requirement in related css file(s).
7. Change the element space with box model
Change the space of at least one element occupied in the webpage using box model.
(e.g. the size, or/and margin, or/and padding, or/and border, … of any or all of the four sides of
the box)
Remember to apply css comment with the itemized number (i.e. #7) above your codes fulfilling
this requirement in related css file(s).
8. Embed content of a webpage inside another webpage
Create additional webpage ( give any name you want to this html document) that can not be
reached through the navigation bar in your website, but whose content will be displayed inside
one of the webpage of your website. Adjust the iframe to a proper size, i.e. width and height.
(e.g. given your website has three webpage “index”, “about”, “help” that can be navigate
through the nav bar in each of these webpage. While the other webpages “contact”, and
“survey”, can not be accessed through navigation bar, display the contact.html content in the
about.html without need to open contact.html separately; another example could be show
content of survey.html inside help.html, etc.)
Remember to apply html comment with the itemized number (i.e. #8) above your codes
fulfilling this requirement in related html file(s).
9. External JavaScript
Create at least one external JavaScript file to control interactive response in at least two
webpages.
Define and call a custom function, and utilize built-in function in it, so when user click on a
certain element when browsing a webpage, shows a pop-up message box to display some text
message and the user can confirm on that message box to continue browsing.
(e.g. you can use any of the three basic built-in function of dialog box in JS to pop up the
message box; use the onclick event attribute on any element in html to trigger the pop-up
when user click on that element. )
Remember to apply js comment with the itemized number (i.e. #9) above your codes fulfilling
this requirement in related js and html file(s).
 Validation and Debug:
• Remember the conventional DOCTYPE declaration and lang attribute for html root tag.
• Debug your html code before uploading and submitting. You can use tool for validation
assistance.
If there are any questions, please ask me in class or through email.
