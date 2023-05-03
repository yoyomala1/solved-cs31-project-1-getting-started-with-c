Download Link: https://assignmentchef.com/product/solved-cs31-project-1-getting-started-with-c
<br>
5/5 - (1 vote)

<span class="">The purpose of this assignment is to have you start learning how to use the Visual C++ and either Xcode or g++ environments and understand a variety of programming errors.</span>

<span class="">Here’s what you are to do:</span>

<ol>

 <li><span class="">(optional) Obtain a copy of </span><a href="https://ccle.ucla.edu/mod/page/view.php?id=2992515"><span class="">Visual C++</span></a><span class=""> and install it. You don’t need to do this if you prefer to do your Visual C++ work on the SEASnet computers (in the lab or remotely). If you will be using another development environment (such as </span><a href="https://ccle.ucla.edu/mod/page/view.php?id=2992516"><span class="">Xcode on a Mac</span></a><span class="">), use this project to get comfortable using it as well as Visual C++.</span></li>

 <li><span class="">Enter </span><a href="https://ccle.ucla.edu/mod/assign/view.php?id=2992559#program"><span class="">this C++ program</span></a><span class=""> into your development environment. Do not change the program.</span></li>

 <li><span class="">Build the executable from the program. (Fix any typos you may have made when entering the program.)</span></li>

 <li><span class="">Execute the program with a variety of reasonable input integers to see if it runs as one would expect from reading the source code. (If the Visual C++ console window disappears when your program finishes executing, before you have a chance to see the output, you probably forgot to do step 4 from the </span><a href="https://ccle.ucla.edu/mod/page/view.php?id=2992515"><span class="">Visual C++ 2019 writeup</span></a><span class="">, or you started execution by selecting the Start Debugging item from the Debug menu or by double-clicking on the .exe file. What you want to do is select the Start Without Debugging item from the Debug menu; if there is no such menu item, fix it as directed in step 7 of the writeup.)</span></li>

 <li><span class="">Using the program as given, run it with input integers that cause it to produce incorrect, unusual, or nonsensical results. (Notice we’re saying to try input </span><em><span class="">integers</span></em><span class="">, not input like </span><code><span class="">124765.23</span></code><span class=""> or </span><code><span class="">strawberry</span></code><span class="">.)</span></li>

 <li><span class="">Starting from the program as given, introduce into the source code at least one error that someone might make that, while not preventing a successful build, causes the program when it runs to produce incorrect results from reasonable input.</span></li>

 <li><span class="">Again starting from the program as given, introduce at least two distinct types of mistakes that someone might make, each of which would cause the program to fail to compile correctly.</span></li>

</ol>

<span class="">You should create a separate project for each of steps 2, 6, and 7, since you’re not allowed to have multiple files in the same project if more than one has a main routine.</span>

<span class="">In addition to running the programs under Visual C++, run them using clang++ or g++ (perhaps using </span><a href="https://ccle.ucla.edu/mod/page/view.php?id=2992516"><span class="">Xcode on a Mac</span></a><span class=""> or </span><a href="https://ccle.ucla.edu/mod/page/view.php?id=2992520"><span class="">g++ with Linux</span></a><span class="">).</span>

<span class="">What you will turn in for this assignment is a compressed file in zip format containing exactly four files:</span>

<ol>

 <li><span class="">A file named </span><strong><span class="">original.cpp</span></strong><span class=""> that contains the program as given.</span></li>

 <li><span class="">A file named </span><strong><span class="">logic_error.cpp</span></strong><span class=""> with the program you produced in step 6.</span></li>

 <li><span class="">A file named </span><strong><span class="">compile_error.cpp</span></strong><span class=""> with the program you produced in step 7.</span></li>

 <li><span class="">A file named </span><strong><span class="">report.doc</span></strong><span class=""> or </span><strong><span class="">report.docx</span></strong><span class=""> (in Microsoft Word format) or </span><strong><span class="">report.txt</span></strong><span class=""> (an ordinary text file) that describes the input you provided in step 5 and each of the errors you introduced into the logic_error.cpp and compile_error.cpp programs. Briefly discuss any error messages the compiler reported, and incorrect, unusual, or nonsensical results. This report may well end up being much less than a page long.  Please be sure to include your </span><b><span class="">name</span></b><span class=""> and your </span><b><span class="">UCLA Id number</span></b><span class=""> in this document.</span></li>

</ol>

<span class="">The zip file itself may be named whatever you like.</span>

<span class="">Do </span><strong><span class="">not</span></strong><span class=""> include anything else in the zip file. (Some Windows users seem not to be aware of Windows filename extensions, so end up putting the wrong files in their zip file.) To create a zip file on a SEASnet machine, you can select the four files you want to turn in, right click, and select “Send To / Compressed (zipped) Folder”. Under Mac OS X, copy the files into a new folder, select the folder in Finder, and select File / Compress “</span><em><span class="">folderName</span></em><span class="">“; make sure you </span><em><span class="">copied</span></em><span class=""> the files into the folder instead of creating aliases to the files.</span>

<span class="">We will be using software tools to help us grade your projects, so there are certain requirements you must meet for the tools to work: </span><strong><span class="">The zip file you turn in for this project must have </span><em><span class="">exactly</span></em><span class=""> four files in it, with </span><em><span class="">exactly</span></em><span class=""> the names indicated. If you do not follow these requirements, your score on this project will be </span><em><span class="">zero</span></em><span class="">.</span></strong><span class=""> “Do you mean that if I do everything right except misspell a file name or include an extra file, I’ll get no points whatsoever?” Yes. That seems harsh, but attention to detail is an important skill in this field. A draconian grading policy certainly encourages you to develop this skill.</span>

<span class="">The only exception to the requirement that the zip file contain exactly four files of the indicated names is that if you create the zip file under Mac OS X, it is acceptable if it contains the additional files that the Mac OS X zip utility sometimes introduces: </span><code><span class="">__MACOSX</span></code><span class="">, </span><code><span class="">.DS_Store</span></code><span class="">, and names starting with </span><code><span class="">._</span></code><span class=""> that contain your file names.</span>

<span class="">By June 29, there will be links on the class webpage that will enable you </span><span class="">to turn in your zip file electronically. Turn in the file by the due time above. Remember that most computing tasks take longer than expected; this applies especially to steps 1, 2, and 3 above. Start this assignment now!</span>

<span class="">Use this project as an opportunity to learn what happens when you make mistakes. After you’ve turned in what’s required for this project, play around. Introduce a mistake into the program and see what happens. Fix it. Introduce a different mistake and see what happens then. Fix it. Keep doing this so you can see the kinds of problems that might arise when you develop your own programs and what the compilers say for each particular problem (if they even detect them at all). See what happens if you make more than one mistake in the program. Will they all be detected? Will an earlier mistake interfere with the reporting of a later one?</span>

<a id="program"></a><span class="">Here is the C++ program:</span>

// Code for Project 1

// COVID-19 #include &lt;iostream&gt; <b>using</b> <b>namespace</b> std;   <i>/</i>/ pp. 37-38 in Savitch book explain this line <b>int</b> main() {     <b>int</b> totalTests;     <b>int</b> positives, falsePositives;     <b>int</b> negatives, falseNegatives;




cout &lt;&lt; “How many tests for COVID-19 were run? “;     cin &gt;&gt; totalTests;     cout &lt;&lt; “How many of these were positive for COVID-19? “;     cin &gt;&gt; positives;     cout &lt;&lt; “How many of these were false positives? “;     cin &gt;&gt; falsePositives;     cout &lt;&lt; “How many of these were negative for COVID-19? “;     cin &gt;&gt; negatives;     cout &lt;&lt; “How many of these were false negatives? “;     cin &gt;&gt; falseNegatives;

<b>double</b> pctPos = (1.0 * positives – falsePositives) / positives * 100.0;     <b>double</b> pctNeg = (1.0 * negatives – falseNegatives) / negatives * 100.0;

cout.setf(ios::fixed);  // see pp. 30-31 in Savitch book     cout.precision(1);

cout &lt;&lt; endl;     cout &lt;&lt; pctPos &lt;&lt; “% of the ” &lt;&lt; positives &lt;&lt; ” positive tests were actually positive.” &lt;&lt; endl;     cout &lt;&lt; pctNeg &lt;&lt; “% of the ” &lt;&lt; negatives &lt;&lt; ” negative tests were actually negative.” &lt;&lt; endl;     cout &lt;&lt; endl;

<b>if</b> (positives + negatives != totalTests)     {         cout &lt;&lt; “Looks like some of these data values don’t make sense.” &lt;&lt; endl;     }




<b>return</b>(0);




}


