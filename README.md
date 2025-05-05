# iscg6421-assignment-2-towers-of-hanoi-solved
**TO GET THIS SOLUTION VISIT:** [ISCG6421 Assignment 2-Towers of Hanoi Solved](https://www.ankitcodinghub.com/product/iscg6421-assignment-2-towers-of-hanoi-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100510&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISCG6421 Assignment 2-Towers of Hanoi Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
The assignment is intended to help you gain experience with designing and building C# Windows applications and testing them with requirements-based testing.

<strong><u>&nbsp;</u></strong>

<strong>Problem statement </strong>

<strong>&nbsp;</strong>

The Towers of Hanoi game is a very old game where you have a board with three pegs on it. A set of differently sized disks are placed on the first peg with the disks being in order with the smallest on the top. The game is to transfer the disks from the first peg to the third by moving only one disk at a time, only taking disks from the top of any pile and never putting a larger disk on top of a smaller disk. The player tries to do this in as few moves as possible.

&nbsp;

<strong>Requirements</strong>

<strong>&nbsp;</strong>

You are provided with a C# starter project that you must use for this assignment. You are to complete the game so that it:

<ul>
<li>Uses four disks and three pegs and lets the user drag and drop disks from one peg to another.</li>
<li>Informs the user that the game is over when all of the disks have been transferred to the third peg.</li>
</ul>
<ul>
<li style="list-style-type: none;">
<ul>
<li>Informs the user whether or not the game has been completed in the minimum number of moves.</li>
</ul>
</li>
</ul>
<ul>
<li>Enforces the rules stated above.</li>
<li>Keeps count of the number of moves.</li>
<li>Allows the user to begin a new game.</li>
<li>Stores valid moves and moves target.</li>
<li>Allows games (complete or incomplete) to be stored.</li>
<li>Allows the running of stored (incomplete) games.</li>
<li>Allows a completed game to be played from a list of stored moves using animation controlled by a timer.</li>
<li>Uses the following classes:</li>
</ul>
<ul>
<li>A Disk class to store data about the disks</li>
<li>A Board class to control what happens to the disks</li>
<li>A DiskMove class for saving moves</li>
<li>A MainForm class to control the game</li>
</ul>
&nbsp;

<strong>Disk Class</strong>

&nbsp;

The disk class should store the disk’s diameter, colour, current level and current peg number. The disk class should have methods that allow access to the data items.

&nbsp;

<strong>Board Class</strong>

&nbsp;

The board class should have the following data storage and be responsible for the following operations:

&nbsp;

<u>Data</u>

<u>&nbsp;</u>

It stores the constants needed to handle the display of disks

It has a two dimensional array of Disk references that represents the board

It has a List for storing the moves made

It has a one dimensional array of 4 Disk references for the Disk objects used in the game.

&nbsp;

The <strong>constructor</strong> takes 4 disk references as parameters

public Board(Disk d1, Disk d2, Disk d3, Disk d4, int movesTarget)

The 4 Disk references in the constructor are to be used to fill the array of Disk objects belonging to the Board object. The integer parameter is set by the user to determine the number of moves they wish to complete the game in. The program should provide a default value.

&nbsp;

<u>Operations</u>

&nbsp;

The Board class can:

<ol>
<li>Reset the game to the beginning.</li>
<li>Allow the user to select a number of targeted moves at the beginning of a new game.</li>
<li>Check if it is valid to begin a move with a particular Disk (only the top Disk on a peg can move). <strong>public bool CanStartMove(Disk aDisk)</strong></li>
<li>Check if it is valid to drop a particular disk on a Peg (drops are only allowed for a Disk that is smaller than the top Disk on a peg or for an empty peg).</li>
</ol>
<strong>public bool CanDrop(Disk aDisk, int aPeg)</strong>

<ol>
<li>Move a disk to a new Peg.</li>
</ol>
<strong>public void Move(Disk aDisk, int newLevel)</strong>

<ol>
<li>Save a DiskMove object representing the latest move to the ArrayList of moves. This would be part of the Move() method.</li>
<li>Return a string giving the moves so far, one move per line.</li>
</ol>
<strong>public string AllMovesAsString()</strong>

<ol>
<li>Display the current position of the disks. This is done by changing the Top and Left properties of the disks which in turn changes where the labels show on the screen.</li>
</ol>
<strong>public void Display()&nbsp;&nbsp; </strong>

<ol>
<li>Get a reference to the disk that matches a label. This is to be used to find which disk object is being dragged on the form.</li>
</ol>
<strong>public Disk FindDisk(Label aLabel)</strong>

<ol>
<li>Check if the number of moves a user has made exceeds the set target. The program should change the colour scheme of the User Interface and show a (friendly) message.</li>
</ol>
<strong>public void SetGameTheme(bool hasExceededTarget)</strong>

&nbsp;

&nbsp;

<strong>&nbsp;</strong>

MainForm Class

&nbsp;

The MainForm class can:

<ol>
<li>Have private global references for a Board object, the Disk being dragged and the Peg that is the target of the drop.</li>
<li>Have a [Reset] button that creates 4 Disk objects matching the 4 labels and a Board object, and then position the Disks in the starting position.</li>
<li>Check (by asking the Board object) if a move can start when the user does a MouseDown on a disk label and give an error message if it cannot.</li>
<li>Check (by asking the Board object) if a drop can happen on a Peg and only show the AllowDrop cursor when the mouse is over a Peg if a drop is valid.</li>
<li>Display a count of the moves made and show the moves made in a textbox, one line per move.</li>
</ol>
&nbsp;

DiskMove Class

&nbsp;

The DiskMove class can:

<ul>
<li>Store the index of the disk making the move and the new Peg it is dropped on.</li>
<li>Have an AsText () method that gives this information as a string, e.g. “1,2” means that Disk 1 moved to peg 2.</li>
<li>Have two constructors, one that takes two integers (for disk index and peg) as parameters, the other takes a string in the form “2,1” as its parameter.</li>
</ul>
<strong>&nbsp;</strong>

<strong>Required Tests</strong>

&nbsp;

This is the minimum number of tests you need in your testing documentation:

&nbsp;

<ol>
<li>The program displays the message “You have successfully completed the game with the minimum number of moves” when all of the disks have been transferred to the third peg with the minimum number of moves.</li>
<li>Interface is displayed correctly when the program runs</li>
<li>Valid moves are stored</li>
<li>Uses four disks and three pegs and lets the user drag and drop disks from one peg to another.</li>
<li>Keeps count of the number of moves.</li>
<li>The program displays the message “You have successfully completed the game but not with the minimum number of moves” when all of the disks have been transferred to the third peg with more than the minimum number of moves.</li>
<li>Enforces the rules</li>
<li>Try moving more than one disk at a time</li>
<li>Try moving a disk at the bottom of a pile</li>
<li>Try moving a disk second from top of a pile</li>
<li>Try putting a larger disk on top of a smaller disk.</li>
<li>Begin a new game after a game has been started</li>
<li>Number of moves set to zero</li>
<li>Disks moved back to starting positions</li>
<li>Load an incomplete stored game and finish it.</li>
<li>Play a completed game from a list of stored moves using animation controlled by a timer.</li>
</ol>
&nbsp;

Please note that your tests can involve more than one step and <strong>must </strong>be reproducible (i.e. explicit test data and user actions) and independent of each other (i.e. please do not use the output of one test as the input to another test.)

&nbsp;

&nbsp;

<strong>Delivery</strong>

A soft copy must be uploaded onto <strong>Moodle </strong>as a single <strong>.zip</strong> file prior to the deadline and it must comprise:

<ul>
<li>The testing documentation.</li>
<li>ALL files needed to compile and run your application from the <strong>Visual Studio Community 2017</strong>. Please note that you must submit your assignment in <strong>Visual Studio Community 2017</strong>. 30 marks will be deducted if this is not done.</li>
</ul>
&nbsp;

Please note that it is important to upload the correct version of your assignment onto Moodle. If you submit the wrong version onto Moodle, please notify me by email before the deadline date or late penalties may be incurred.

&nbsp;

&nbsp;

<strong>Test Cases</strong>

<strong>&nbsp;</strong>

Please using the following format for your test cases

&nbsp;

<table width="689">
<tbody>
<tr>
<td width="219"><strong>Requirement to test</strong></td>
<td width="151"><strong>Test Data Input</strong></td>
<td width="172"><strong>Expected Outcomes</strong></td>
<td width="148"><strong>Actual Outcomes</strong></td>
</tr>
<tr>
<td width="219">&nbsp;</td>
<td width="151">&nbsp;</td>
<td width="172">&nbsp;</td>
<td width="148">&nbsp;</td>
</tr>
</tbody>
</table>
&nbsp;

&nbsp;

<h1><a name="_Toc46744155"></a><a name="_Toc46748674"></a>Save Points</h1>
<strong>&nbsp;</strong>

There is an expectation that you will have completed certain aspects of your assignment at each save point submission. If your submission does not meet the expectations of the save point, your overall mark for the final submission may be penalised.

<h3><a name="_Toc46744156"></a><a name="_Toc46748675"></a>Expectations:</h3>
<h6>Save Point 1:</h6>
<ul>
<li>Working Drag &amp; Drop functionality</li>
</ul>
<h6>Save Point 2:</h6>
<ul>
<li>Working file reading &amp; writing functionality</li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Deadline for questions</strong>

<strong>&nbsp;</strong>

Please note that there is a deadline for questions on the assignment at 8:30 a.m. on Tuesday 13<sup>th</sup> October 2020. Please make sure that you ask any questions regarding the assignment before this deadline.

<strong>&nbsp;</strong>

<strong>Marking</strong>

<strong>&nbsp;</strong>

<ul>
<li>Marks will be deducted for any requirement (or for multi-part requirements, or each part of a requirement) that is not fully implemented or has no or insufficient testing documentation.</li>
<li>In the <strong>interface behaviour and data processing</strong> section, marks will be deducted for any requirement (or for multi-part requirements, or each part of a requirement) that is not well covered in the test plan or is reported as working in the test plan but does not work when the assignment is marked. You are also expected to handle exceptions, using message boxes and “<strong>try and catch</strong>” blocks.</li>
<li>Check “Programming Standards for C Sharp Courses” on pages 7 and 8 of this document. The standards for C# programming in this document MUST be followed. In particular, this includes putting meaningful comments at the beginning of <strong>each and every</strong> method in the standard format as given in the document.</li>
</ul>
&nbsp;

<table width="624">
<tbody>
<tr>
<td width="480"><strong>Part</strong></td>
<td width="72"><strong>Marks</strong></td>
<td width="72"><strong>Actual</strong></td>
</tr>
<tr>
<td width="480">Interface behaviour, and data processing</td>
<td width="72">&nbsp;</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Interface set up correctly (matches screenshot – see page 8)</td>
<td width="72">10</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Uses four disks and three pegs and lets the user drag and drop disks from one peg to another.</td>
<td width="72">&nbsp;

8
</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Enforces the rules of the game</td>
<td width="72">15</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Keeps count of the number of moves.</td>
<td width="72">5</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Allows the user to begin a new game.</td>
<td width="72">5</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Allows the running of stored moves.</td>
<td width="72">5</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Allows the game to be played from a list of stored moves using animation controlled by a timer.</td>
<td width="72">10</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">·&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Uses the following classes:

<ul>
<li>A Disk class to store data about the disks.</li>
<li>A Board class to control what happens to the disks.</li>
<li>A DiskMove class for saving moves.</li>
<li>A MainForm class to control the game.</li>
</ul>
</td>
<td width="72">&nbsp;

&nbsp;

22
</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">Testing documentation</td>
<td width="72">16</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480">Naming conventions and correct internal documentation</td>
<td width="72">4</td>
<td width="72">&nbsp;</td>
</tr>
<tr>
<td width="480"><strong>Total:</strong></td>
<td width="72"><strong>100</strong></td>
<td width="72"><strong>&nbsp;</strong></td>
</tr>
</tbody>
</table>
&nbsp;

Do you want to do the best that you can do in this assignment and improve your grades?

You could:

<ul>
<li>Talk it over with your lecturer</li>
<li>Visit Te Pune Ako or Maia for learning advice and support</li>
<li>Visit the Centre for Pacific Development and Support</li>
<li>Contact the USU Advocate for independent advice</li>
<li>For contact details and more information, go to www.usu.co.nz</li>
</ul>
<strong><u>&nbsp;</u></strong>

&nbsp;

Assignment Delivery

&nbsp;

Electronic submission of all necessary files is required for ALL assignments and must be submitted prior to the due date and time.&nbsp; Assignments submitted after the due date and time without having received an extension through Affected Performance Consideration (APC) will be penalised according to the following:

<ul>
<li>10% of marks deducted if submitted within 24hrs of the deadline</li>
<li>20% of marks deducted if submitted after 24hrs and up to 48hrs of the deadline</li>
<li>30% of marks deducted if submitted after 48hrs and up to 72hrs of the deadline</li>
<li>No marks will be awarded for an assignment that is submitted later than 72hrs after the deadline.</li>
</ul>
&nbsp;

For the purposes of academic integrity, students who haven’t demonstrated progress work in the class time can be asked to demo/test their working code and explain logic to the lecturer individually after assignment submission.

&nbsp;

<h1><a name="_Toc46748699"></a>Affected Performance Consideration</h1>
&nbsp;

A student, who due to circumstances beyond his or her control, misses a test, final exam or an assignment deadline or considers his or her performance in a test, final exam or an assignment to have been adversely affected, should complete the Affected Performance Consideration (APC) form available from Student Central.

&nbsp;

When requesting an APC for an assignment, the APC application form must be submitted (along with work completed to-date) within the time frame of the extension requested; i.e. if the Doctor’s certificate is for one (1) day, then the APC application form and work completed must be submitted within one (1) day.

&nbsp;

<strong>&nbsp;</strong>

<h1><a name="_Toc46748700"></a>Assistance to other Students</h1>
&nbsp;

Students themselves can be an excellent resource to assist the learning of fellow students, but there are issues that arise in assessments that relate to the type and amount of assistance given by students to other students.&nbsp;&nbsp; It is important to recognise what types of assistance are beneficial to another’s learning and also what types of assistance are unacceptable in an assessment.

&nbsp;

<h1><a name="_Toc46748701"></a>Beneficial Assistance</h1>
&nbsp;

<ul>
<li>Study Groups.</li>
<li></li>
<li>Sharing reading material.</li>
<li>Testing another student’s programming work using the executable code and giving them the results of that testing.</li>
</ul>
<h1><a name="_Toc46748702"></a>Unacceptable Assistance</h1>
&nbsp;

<ul>
<li>Working together on one copy of the assessment and submitting it as own work.</li>
<li>Giving another student your work.</li>
<li>Copying someone else’s work. This includes work done by someone not on the course.</li>
<li>Changing or correcting another student’s work.</li>
<li>Copying from books, Internet etc. and submitting it as own work. Anything taken directly from another source must be acknowledged correctly: show the source alongside the quotation.</li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>For the purposes of academic integrity, students who haven’t demonstrated progress work in the class time (and/or no check point submission) can be asked to demo/test their working code and explain logic to the lecturer individually after assignment submission.</strong>

<strong><u>&nbsp;</u></strong>

<strong><u>&nbsp;</u></strong>

<strong>Programming Standards for C Sharp Courses</strong>

<strong><u>Internal Documentation</u></strong>

<strong><u>&nbsp;</u></strong>

<ul>
<li>Your code is such that other programmers can read it without struggling and your users are not left guessing as to what to do.</li>
</ul>
<ul>
<li>Each class file (including form classes) will begin with comments explaining the purpose of the class, the author and the date written.</li>
</ul>
<ul>
<li>Each method will start with comments that explain what the method does.</li>
<li>Any code which does not have an obvious meaning or which uses a specialized technique is to be commented. Use blank lines and further comments to identify where parts of a task begin within a method.</li>
<li>Code will use meaningful variable, class and method names. Components which have event handler code for any of their events must have meaningful names, Components which have properties assigned to in code must also have meaningful names. A naming convention that identifies the type of component involved is recommended. E.g. btnExit, txtStartDate, lblTotal</li>
</ul>
<strong>Layout</strong>

&nbsp;

<ul>
<li>Code will be laid out in the style of the example below, using indentation steps of 4 spaces. Blocks using { and } will use the layout shown here:</li>
</ul>
<strong>&nbsp;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ///&lt;Summary&gt; method : btnLeapYear_Click</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ///Check if a date falls in a leap year</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; ///&lt;/Summary&gt;</strong>

<strong>private</strong><strong> void btnLeapYear_Click(object sender, System.EventArgs e)</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; {</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; DateTime aDate = getDate();</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; if ( DateTime.IsLeapYear(aDate.Year) )</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; {</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; label6.Text = aDate.Year.ToString() + ” IS a leap year”;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; }</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; else</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; {</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; label6.Text = aDate.Year.ToString()&nbsp; </strong>

<strong>+ ” is NOT a leap year”;</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp; }</strong>

<strong>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; }</strong>

<strong>&nbsp;</strong>

<ul>
<li>Parentheses and spaces will be used to make the meaning clear in arithmetic expressions and conditions.</li>
</ul>
<strong>&nbsp;&nbsp;&nbsp; sum = (n1 / n2) + n3; </strong>

not

<strong>&nbsp;&nbsp;&nbsp; sum = n1 / n2 + n3; </strong>

nor

<strong>&nbsp;&nbsp;&nbsp; sum=n1/n2+n3;</strong>

<strong>&nbsp;</strong>

<ul>
<li>In general, each method will perform a single simple task.</li>
<li>In the final version of your project please delete all sections of code that has been ‘commented out’</li>
</ul>
&nbsp;

<strong>User Interface</strong>

&nbsp;

<ul>
<li>Always provide the user with clear instructions explaining what they should do. Areas used for input must be labelled to explain what input is required. Use <strong>hints </strong>or<strong> tool tips</strong> to explain interface features.</li>
</ul>
&nbsp;

<ul>
<li>The user must be prevented from entering values or taking actions that the program is unable to deal with. All input should be validated; any errors found should be reported back to the user with an error message which <u>clearly and politely</u> explains <u>how to correct the error</u>. The user should be unable to proceed without correcting invalid input.</li>
</ul>
&nbsp;

&nbsp;

<strong>Interface Design Basic Mock-up: Screenshot</strong>

&nbsp;

&nbsp;

&nbsp;

NOTE: This mock-up does not include all GUI elements necessary to complete the assignment. It represents a high-level suggestion of layout for the GUI, and not an exact requirement for your submission.
