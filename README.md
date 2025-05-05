# comp-249---object-oriented-programming-ii-assignment-3-solved
**TO GET THIS SOLUTION VISIT:** [Comp 249 – Object-Oriented Programming II Assignment 3 Solved](https://www.ankitcodinghub.com/product/comp-249-object-oriented-programming-ii-assignment-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;10696&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp 249 – Object-Oriented Programming II  Assignment 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
<strong><u>Purpose:</u></strong> The purpose of this assignment is to allow you practice Exception Handling, and File I/O, as well as other previous object oriented concepts.

This assignment contains two parts. You need to complete part I before doing part II.

<h1>Part I</h1>
<strong>&nbsp;</strong>The <strong>Book</strong> class has the following attributes: an <em>ISBN</em> (long type), a <em>title</em> (String type), an <em>issue year</em> (int type), an <em>author(s) name</em> (String type), a <em>price</em> (double type) and a <em>number of pages</em> (int type). It is assumed that both the title and the author(s) name are recorded as a continuous string with “_” to separate the different words if any (i.e. a title can be Java_Applications_for_Engineers, and author name can be Mike_Westman_and_Jack_Bartlett).

&nbsp;

The file <strong><em>Initial_Book_Info.txt</em></strong>, which one of its versions is provided with this assignment, has the information of various books that a book store carries. However, this file is always created by the owner of the book store, who is not so careful, so errors in the ISBN numbers are expected to exist in this file. Specificaly, due to a cut-and-paste practice by the owner, some ISBN numbers of some books are usually re-recorded later in the file as the ISBN number of other following books in the file. Consequently, an ISBN can either appears once in the file, which is the correct case, or appears multiple times, in which case the second, and following, appearances are in error.

&nbsp;

You must notice that the file <em>Initial_Book_Info.txt </em>changes regularly, and it may have many records, or no records at all, depending on the current inventory of the store. The file provided with this assignment is only one of possible versions of the file, and must not be considered as the general case when writing your code.

&nbsp;

<u>For this part, you are required to:</u>

<ol>
<li>Write the implementation of the <strong>Book</strong> class according to the above given specification.</li>
<li>Write the implementation of an exception class called <strong>DuplicateISBNException</strong>, which extends the <strong>Exception</strong> Should a duplicate ISBN number is detected at any point, an object from this class will be thrown. More details will follow below.</li>
<li>Write the implementation of a public class, called <strong>BookInventory1</strong>, which will utilize the <strong>Book</strong> class and the <em>txt</em>, as explained below. The class has a static array of books, called <em>bkArr[]</em>, and few methods. Beside the main() method, the class must have the following methods:
<ul>
<li>A method called <strong><em>fixInventory()</em></strong>, which accepts two parameters, an input file stream name and an output file stream name. The first parameter is the stream related to the <em>txt</em>. The second parameter is related to an output file name, which will be entered by the user prior to calling this method (at the main() method). This output file will eventually store a correct version of the inventory. More information on this will follow below.</li>
<li>A method called <strong><em>displayFileContents()</em></strong>, which accepts an input file stream name, then displays the contents of this file to the standard output (the screen).</li>
<li>You can add any other methods to this class if you wish to.</li>
</ul>
</li>
</ol>
&nbsp;

&nbsp;

<u>Here are the details of how your program must behave:</u>

<ul>
<li>In the main() method, your program must prompt the user to enter the name of the output file that will be created to hold the modified/correct inventory. This output file is theoretically a copy of the <em>txt</em>, but with all the duplicate ISBN numbers corrected.</li>
<li>If the entered name by the user matches the name of an existing file, then the program must reject that name indicating to the user that a file with that name already exists, display the size of this existing file (in bytes) to the user, then prompt the user to enter a new name. This process would repeat <a href="https://www.google.com/search?hl=en&amp;rls=com.microsoft:en-us&amp;ei=q0V9S83MFYPElAftnuTNBQ&amp;sa=X&amp;oi=spell&amp;resnum=0&amp;ct=result&amp;cd=1&amp;ved=0CAQQBSgA&amp;q=define%3A+indefinitely&amp;spell=1">indefinitely,</a> until the user finally enters a name for a non-existing file. See Figure1 for illustration.</li>
<li>Once the user finally enters a correct name for the output file, the program will attempt to establish an input and output streams for the <em>txt </em>and that output file accordingly. This process may surely throw specific exceptions, and your program must handle all these exceptions properly.</li>
<li>The <em>fixInventory()</em> method (see details below) will utilize the <em>BkArr[]</em> array as follows: All book objects recorded in the <em>txt</em> file must first be copied into that array. All detections and corrections of ISBN numbers will be conducted on that array. Once the array has finally all correct information, the objects will be recorded to the output file. However since it always unknown at the time the program starts how many records are in the <em>Initial_Book_Info.txt</em> file, you must first find this information. You may, and should, add a private helping method to the <strong>BookInventory1</strong> class to do so. Once the number of records is know, the array must be set to that size.</li>
<li>If the number of records in the <em>txt </em>was detected to be zero or one; the case when the file is empty or has only one record, then the program must display a message indicating that, performs any needed operations (such as closing files), then exits since there is nothing to be fixed.</li>
<li>If the <em>txt </em>has more than one record, then finally the <em>fixInventory()</em> method will be called to create a the new output file with the correct information. The exact details of this method are as follows: o The method will accept two stream names for the input and output files, o The method must read each book record from the input file and creates a book object in the array <em>bkArr[]</em> based on that record,
<ul>
<li>Once the entire input file is read into the array (notice that the array has real book objects, and not just information), the method starts to trace that array from start to end looking for any ISBN duplicates,</li>
<li>If an ISBN duplicate is detected, then the method displays a message to the user indicating that, and prompt the user to enter a new ISBN number,</li>
<li>You should notice that this new number must not be a duplicate of any other existing record, and your program must guarantee that. Should the user enters an ISBN number that is still a duplicate, the program must throw a <strong>DuplicateISBNException</strong>, which must be catched to display a message indicating that, then user must be prompted again to enter a new ISBN. Further bad entries will result in the same action; that is throwing of the <strong>DuplicateISBNException </strong>object, catching it to display the message, and the user is prompted again. Effectively, this process will repeat indefinitely until the user enters a correct ISBN number. Again, you may, and should, create a private helping method to find if a duplicate exists in the array. See Figure 2 for illustration.</li>
<li>Finally, once all the duplicate ISBN numbers are removed, the new information of the objects in the <em>bkArr[]</em> must be copied to the output file. This output file has now the correct information.</li>
</ul>
</li>
</ul>
 Upon the return of the <em>fixInventory() </em>call in the main() method, the program must use the <em>displayFileContents()</em> method to display the information of both the <em>Initial_Book_Info.txt</em> file, as well as the created output file. See Figure 3 for illustration.

Hint: You must carefully keep track of the opening and closing of these files.

&nbsp;

&nbsp;

Below are sample snapshots of the program behavior for further illustrations:

&nbsp;

&nbsp;

&nbsp;

Figure 1: Detecting Existing Files

&nbsp;

&nbsp;

&nbsp;

&nbsp;

&nbsp;

Figure 2: Detecting Existing ISBN

&nbsp;

&nbsp;

Figure 3: Displaying File Contents

&nbsp;

<h1>Part II</h1>
<strong>&nbsp;</strong>

<em>&nbsp;</em>

For this second part, you will still use the same <strong>Book</strong> class from Part I (some little modifications may be needed, and you should find that out). Other code segments from Part I can still be used when appropriate.

Implement a public class called <strong>BookInventory2</strong>, which will utilize the <strong>Book</strong> class and the file called <em>Sorted_Book_Info.txt</em>. This file includes information about books inventory in a book store. The records in this file are sorted by ISBN, and the information in this file is assumed to always be correct.

The class has a static array of books, called <em>bkArr[]</em>, and few methods. Beside the main() method, the class must have the following methods:

<ul>
<li>A method called <strong><em>addRecords()</em></strong>, which accept one parameter: an output file stream name; further details of this method are given below.</li>
<li>A method called <strong><em>displayFileContents()</em></strong>, which accepts an input file stream name, then displays the contents of this file to the standard output (the screen). This method however must use the <strong>BufferedReader</strong> class to read the file.</li>
<li>A method called <strong><em>binaryBookSearch()</em></strong>, which accepts four parameters: any array of books, a start index, an end index, and an ISBN number. The method then uses <em>binary search</em> to search the array segment (from start index to end index) for that ISBN. The method must also keep track and display how many iterations it needed to perform the search.</li>
<li>A method called <strong><em>sequentialBookSearch()</em></strong>, which accepts four parameters: any array of books, a start index, an end index, and an ISBN number. The method would then search the array, using s<em>equential search</em>, for that ISBN. You must analysis the performance aspect of your solution. Hence, the method must also display how many iterations it needed to perform the search.</li>
<li>You can add any other methods to that class if you wish to.</li>
</ul>
&nbsp;

&nbsp;

<u>Here are the details of how your program must behave:</u>

<ul>
<li>In the <strong><em>main()</em></strong> method, your program must open the <em>txt </em>file to append few records to it.</li>
<li>Call the <em>addRecords()</em> method to add few records to the file. The information of each of the new records must be entered by the user. The user can add as many records as he/she wishes (you must surely allow the user to have a stopping condition limiting the numbers of records that can be added). To simplify your task, you can assume that the user will always keep the file sorted; that is, no new record will have an ISBN# that is smaller than any of the previous records in the file., in a nother way a reference of the last record is kept to accept or reject the record you want to add.</li>
<li>Call the <em>displayFileContents()</em> method to show the contents of the file after modifications.</li>
<li>Now, the array <em>bkArr[]</em> is going to be used in a similar fashion to Part I. So, you need to find out what is the current number of records in the <em>txt </em>file, and set the size of the array to that number. You may, and should, have a private helping method to do so.</li>
<li>After setting the array size properly, the program must read the contents of the file to the array objects. You can use a separate method to do so.</li>
<li>Once the array has the objects information from the file, prompt the user to enter and ISBN number then use <em>binaryBookSearch()</em> to search for that ISBN.</li>
<li>Repeat the same search using <em>sequentialBookSearch()</em>.
<ul>
<li>As an important exercise, you should run your code for different searches (i.e. attempt to find best and worst cases) of the two searches.</li>
</ul>
</li>
<li>Finally, store all the objects from the <em>bkArr[]</em> into a <u>binary file</u> called <strong><em>dat</em></strong>. You can have a separate method to do so. If writing to the binary file requires any specific modifications to your code, you must apply these modifications.
<ul>
<li>As always, you must handle all exceptions as needed and you must keep track of the opening and closing of your files.</li>
</ul>
</li>
</ul>
&nbsp;

&nbsp;
