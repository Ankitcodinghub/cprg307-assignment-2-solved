# cprg307-assignment-2-solved
**TO GET THIS SOLUTION VISIT:** [CPRG307 Assignment 2 Solved](https://www.ankitcodinghub.com/product/cprg307-assignment-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95896&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CPRG307 Assignment 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This assignment is based on the We Keep It Storage (WKIS) Company’s system, an accounting system. Transactions (this is a double- entry accounting system) will be taken from a holding table (NEW_TRANSACTIONS) and inserted into the TRANSACTION_DETAIL and

TRANSACTION_HISTORY tables. At the same time, the appropriate account balance will be updated in the ACCOUNT table. This system follows a double entry accounting system with the accounting rules presented in class.

<ol>
<li>Ensure that you have created the WKIS database tables successfully. These files for this assignment are provided in Module 9 on D2L.</li>
<li>Design, write a PL/SQL program, and thoroughly test the coded solution using the information outlined above and the guidelines / restrictions below.
<ol>
<li>You can assume that every transaction number is unique (there will be no duplicates) for each “transaction”. Remember that a transaction is a unit – will be made up of more than one row. All rows that represent a single transaction will have the same transactional history information (TRANSACTION_NUMBER, TRANSACTION_DATE, DESCRIPTION).</li>
<li>Using two nested cursors would make this problem easier to solve. See Module 4 slides and the Module 4 exercise for an example. You do not have to use this method in your solution, this is simply a hint and suggestion for an easier solution.</li>
</ol>
</li>
</ol>
Database Programming and Testing CPRG 307 Page 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
c. Another hint, get the overall structure of your program working with clean data first. Then start adding error checking and functionality.

<ol start="4">
<li>As long as the debits equal the credits in each transaction, you can assume that the accounting equation for each transaction holds true. For this program, you do not have to validate the accounting equation.</li>
<li>After a transaction has been successfully processed, remove it from the

NEW_TRANSACTIONS table. Transactions that produce an error should remain in the NEW_TRANSACTIONS table.</li>
<li>An error in one transaction should not prevent the processing of other transactions (i.e. make sure you do not leave the main looping structure when an error occurs).</li>
<li>Only the first error in a transaction should be recorded in the error log table (i.e. a specific transaction number should only appear once in the error log table). If the error is a missing transaction number, a single entry can be recorded in the error log table for all rows missing a transaction number or can have an entry recorded for each row missing a transaction number.</li>
<li>When your instructor evaluates your program, only errors that appear in the error log table will be evaluated. If you only print the error to the screen, your instructor will consider this error as not being caught. For debugging you can have an error written to the error log table AND print to the screen, this is fine.</li>
<li>All required tables for this assignment, including the error log, are created with the provided scripts. Do not create any additional tables or modify the existing tables (structure or constraints).</li>
<li>Do not use a table of records, or any other type of array, in your solution to this problem. We do not cover these in this course so if you do not know what they are that is fine. Note: Record data structures are okay; a table of records is different.</li>
</ol>
Database Programming and Testing CPRG 307 Page 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="11">
<li>SELECT INTO cannot be performed against the NEW_TRANSACTIONS table. A SELECT on NEW_TRANSACTIONS can only be performed by an explicit cursor (use your cursor for any needed values from this table).</li>
<li>The solution must be done with one anonymous block (multiple embedded blocks are fine as these are not considered separate anonymous blocks). If multiple anonymous blocks are submitted, only the first one in the script will be evaluated by your instructor.</li>
<li>Stored programs cannot be used.</li>
<li>Do not use GOTOs, EXITs, or SAVEPOINTs. CONTINUEs can be used if done appropriately (do not use as you
would a break in Java).
</li>
<li>There should be no hard coding of values anywhere in your code except for the transaction type (‘C’, ‘D’) which
should be hard coded only in the DECLARE section.
</li>
</ol>
3. Your program should handle all exceptions and write the transactional history information of the transaction that caused the error as well as the error message to the WKIS_ERROR_LOG table.

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

</div>
<div class="column">
Error messages must be descriptive.

Specific errors that must be caught:

<ol>
<li>Missing transaction number (NULL transaction number)</li>
<li>Debits and credits are not equal</li>
<li>Invalid account number</li>
<li>Negative value given for a transaction amount</li>
<li>Invalid transaction type</li>
</ol>
All other errors (outside of those listed above) would be considered unanticipated errors. These should be caught as well

</div>
</div>
<div class="layoutArea">
<div class="column">
•

</div>
</div>
<div class="layoutArea">
<div class="column">
as we do not want our program to crash. o For these unanticipated errors:

Database Programming and Testing CPRG 307 Page 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
•

•

</div>
<div class="column">
The error message would be the system generated error message as we cannot provide a customized descriptive error for this type of problem.

For our purposes, testing does not need to be performed for this type of error. Your instructor will simply be looking for the code to exist that would handle unanticipated errors.

Your instructor will provide you with two testing data sets. o Clean data

o Mix of clean and erroneous data

Your instructor will evaluate your program with a different set of data. o This means that your program should be able to work with any data.

o Your instructor’s data set will be evaluating everything outlined in the evaluation section below, so there will be no surprises. Erroneous data will only be checking for those errors specified above.

o Do not code to the data sets, code to the problem. The test data is simply there to help you confirm your code is working as it should.

o It is highly recommended you also create additional test data to ensure your program works regardless of the data provided.

</div>
</div>
<div class="layoutArea">
<div class="column">
Database Programming and Testing CPRG 307 Page 4

</div>
</div>
</div>
