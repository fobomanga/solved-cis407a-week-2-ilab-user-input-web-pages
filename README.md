Download Link: https://assignmentchef.com/product/solved-cis407a-week-2-ilab-user-input-web-pages
<br>
<header class="entry-header"></header>

5/5 - (1 vote)

In this lab, we will demonstrate how to create an ASP.NET web application having a single form with five text boxes and a Submit button. We will use the form to send information to a second form where data from the first form will be displayed. We will also add a main navigation page with two different ways of linking to other pages. INCLUDE A SCREENSHOT OF THE ASSIGNMENT SUCCESSFULLY RUNNING TO RECEIVE CREDIT

<strong>Deliverables</strong>All files are located in the subdirectory of the website. The website should function as follows: When you run the website, you will be presented with a page (frmMain) that allows you to go to the different parts of the website you are developing. You will be able to go to the annual salary calculator we added last week and to the data entry form for personnel this week. When you go to the personnel data entry page you should be able to enter data in the frmPersonnel form and have it displayed in the frmPersonnelVerified form. Your salary calculator will also be available from the main page and will calculate properly when you enter data. Each page should link back to the main page via the CoolBiz logo hyperlink. Once you have verified it works, save your website, zip up all files, and submit in the Dropbox. Each page (except frmMain) will include the CoolBiz logo that is hyperlinked back to frmMain.

<strong>iLAB STEPS</strong><strong>STEP 1:</strong> frmPersonnel (10 points)1. Open the payroll system website from Lab 1.2. Create a new form called frmPersonnel. To do this, pull down the website menu, select “Add New Item,” then type frmPersonnel.aspx for the name.3. Click here for text description of this image.4. Go to the Design mode of the form by clicking the Design tab (as opposed to the Source tab).5. Copy/paste this text for the CoolBiz Productions, Inc. logo onto the form at the very top. Set the alignment to center by highlighting the text then clicking Format, Justify, Center. You can switch to Source view and add the following HTML to create the logo:<span style="color: black; font-size: small;"><strong>&lt;fontcolor=”blue” face=”Comic Sans MS” size=”4″&gt;Cool&lt;/fontcolor=”blue”&gt;</strong></span><strong><span style="color: #ff6600; font-family: 'Comic Sans MS'; font-size: large;">Biz</span><span style="font-family: 'Comic Sans MS'; font-size: large;"> &lt;fontcolor=”#993366″&gt;Productions&lt;/fontcolor=”#993366″&gt;</span>, Inc.</strong>6. From the ToolBox, drag-and-drop a Panel control underneath the logo text.7. Click the A/Z button in the Properties dialog so that all the properties are sorted alphabetically.8. Change the height property of the Panel to 250px and the width to 300px. To do this, select the Panel, then go to the Properties pane (usually in the lower right corner of the Visual Studio.NET Design view; if you don’t see it, click View Properties Window OR press the F4 key). Scroll down the list, then type the value in for each property.9. Change the panel’s HorizontalAlign property to left.10. Save your work!11. From the ToolBox, drag-and-drop five Labels and five TextBoxes onto the Panel. To make each Label/TextBox pair appear on a separate line, put the cursor after each TextBox then press the [ENTER] key (much like you would with a word processing program).12. From the ToolBox, drag-and-drop two buttons onto the Panel below the last Label and TextBox.13. Save your work! INCLUDE A SCREENSHOT OF THE ASSIGNMENT SUCCESSFULLY RUNNING TO RECEIVE CREDIT14. Click here for text description of this image.15. Test your web page. Press F5, or click the Start Debugging (Citrix users, press “Start Without Debugging”) button on the toolbar, or pull down the Debug menu and select Start Debugging.NOTE: To execute the application, you have these options:A. If you are using Citrix, press CTRL + F5 to Start Without Debugging. You will not be deducted points for this part.B. If you are using a standalone version, press F5 to Start with Debugging, or you can press CTRL + F5 to Start Without Debugging16. Rename the Label’s properties as defined below. You can do this by selecting each Label, scrolling to the property, and then typing in the value.

17. Rename each TextBox’s property as defined below. You can do this by selecting each TextBox, scrolling to the property, and then typing in the value.

18. Click on image to enlarge.Changing Text Box ID19. Click here for text description of this image.20. Change each button’s ID and Text properties as defined below. You can do this by selecting each button, scrolling to the property, and then typing in the value.

21. In order to format the TextBoxes and Labels, we will make them the same size. Bring up the Layout Toolbar by clicking View, Toolbars, Layout.22. Highlight each Label by pressing and holding the keyboard Ctrl button and then clicking each Label. Make sure you click on the longest Label last.23. Click the icon “Make Same Width” on the Layout Toolbar. (You may also select Format and then Make Same Size and then select width).24. Save your work!25. Test your work by running it (press F5 or click the Start Debugging button, or click Debug, Start Debugging).

<strong>STEP 2:</strong> frmPersonalVerified (5 points)22. Create a new web form called frmPersonalVerified.aspx23. Click the Design tab for the frmPersonalVerified.aspx and add a Label and a TextBox. Set the properties as follows:

24. Double-click anywhere on a blank part of the web page to open the code portion. The cursor should be in the protected void Page_Load (object sender, EventArgs) function. Enter the following information:

25. Return to the frmPersonnel web page, click the btnSubmit button, go to the PostBackUrl property, and set it to frmPersonalVerified.aspx. To do this, you can click the ellipse to the right of this property to open a Browse dialog and click frmPersonalVerified.aspx there. This will insert the correct path into the PostBackUrl property.

<strong>STEP 3:</strong> Adding Navigation (5 points)26. Create a folder in Solution Explorer called images.27. Add a new web form called frmMain.A. Add the CoolBiz Logo to the top of the form (centered).B. Create links using a link button for each of the following items.Salary CalculatorAdd New EmployeeC. Create or find appropriate images for the Salary Calculator and New Employee links. Copy the images to the images folder created above.D. Add the images to the images folder by right-clicking on the images folder in Solution Explorer and selecting Add Existing Items. Select both images and Add to the images folder.E. Next to each link item, add an image button.F. Set each image button’s image to the appropriate image in the images folder.G. You may work with the format to make this page look nice by using tables or other HTML/CSS elements.H. Set the PostbackURL property to the appropriate page for each image and each link.28. On the frmPersonnel page, make the CoolBiz logo be a link that will take the user to the frmMain page. Use an ASP.Net Hyperlink control to do this.29. Update the frmPersonnel, frmPersonnelVerified, and frmSalaryCalculator to include the CoolBiz logo at the top of each page (centered) with the logo set as a hyperlink that will return to the frmMain page.30. On the frmPersonnel page, make it so that if the user presses the Cancel button then that user is taken back to the frmMain.

<strong>STEP 4:</strong> Verify and Submit (10 points)31. Save your work. Set the start page to frmMain and run the project. You should be able to go to both areas of your site and enter the information in the pages. Your calculator should properly calculate without errors, and then on the frmPersonel web page you can click the Submit button and have it display in the frmPersonalVerified web page. Once you have verified that it works, save your project, zip up all files, and submit in the Dropbox.Here are screen shots (Note: Your frmMain does not have to look exactly like this, as long as it functions.):frmMain:frmSalaryCalculator:frmPersonnel:frmPersonnelVerified:All Forms:

<strong>NOTE:</strong> Make sure you include comments in the C# code where specified (where the “//Your comments here” is mentioned), or else a 5 point deduction per item (form, class, function) will be made. This includes code you will be creating in the coming weeks. To comment on the code you basically put two forward slashes to start the comment; anything after the slashes on that line is disregarded by the compiler. Then type a brief statement on what is happening in the line under it. Comments show professionalism and are a must in systems. As a professional developer, comments will set you apart from others and make your life much easier if maintenance and debugging are needed.

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td class="code"></td>

  </tr>

 </tbody>

</table>

<code class="php plain">Property Value</code>

<code class="php plain">Label1 – Text First Name:</code>

<code class="php plain">Label2 – Text Last Name:</code>

<code class="php plain">Label3 – Text Pay Rate:</code>

<code class="php plain">Label4 – Text Start </code><code class="php functions">Date</code><code class="php plain">:</code>

<code class="php plain">Label5 – Text </code><code class="php functions">End</code> <code class="php functions">Date</code><code class="php plain">:</code>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td class="code"></td>

  </tr>

 </tbody>

</table>

<code class="php plain">Property Value</code>

<code class="php plain">TextBox1 – (ID) txtFirstName</code>

<code class="php plain">TextBox2 – (ID) txtLastName</code>

<code class="php plain">TextBox3 – (ID) txtPayRate</code>

<code class="php plain">TextBox4 – (ID) txtStartDate</code>

<code class="php plain">TextBox5 – (ID) txtEndDate</code>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td class="code"></td>

  </tr>

 </tbody>

</table>

<code class="php plain">Property Value</code>

<code class="php plain">Button1 – (ID) btnSubmit</code>

<code class="php plain">Button1 – Text Submit</code>

<code class="php plain">Button2 – (ID) btnCancel</code>

<code class="php plain">Button2 – Text Cancel</code>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td class="code"></td>

  </tr>

 </tbody>

</table>

<code class="php plain">Property Value</code>

<code class="php plain">Label – Text Information to submit</code>

<code class="php plain">Textbox – (ID) txtVerifiedInfo</code>

<code class="php plain">Textbox – Height 80px</code>

<code class="php plain">Textbox – Width 400px</code>

<code class="php plain">Textbox – TextMode Multiline</code>

<table border="0" cellspacing="0" cellpadding="0">

 <tbody>

  <tr>

   <td class="code"></td>

  </tr>

 </tbody>

</table>

<code class="php comments">//Add your comments here</code>

<code class="php plain">txtVerifiedInfo.Text = Request[</code><code class="php string">"txtFirstName"</code><code class="php plain">] +</code>

<code class="php string">"
"</code> <code class="php plain">+ Request[</code><code class="php string">"txtLastName"</code><code class="php plain">] +</code>

<code class="php string">"
"</code> <code class="php plain">+ Request[</code><code class="php string">"txtPayRate"</code><code class="php plain">] +</code>

<code class="php string">"
"</code> <code class="php plain">+ Request[</code><code class="php string">"txtStartDate"</code><code class="php plain">] +</code>