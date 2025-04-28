# cmpt135-assignment-3--to-do-lists-solved
**TO GET THIS SOLUTION VISIT:** [CMPT135 Assignment 3- To-do Lists Solved](https://www.ankitcodinghub.com/product/cmpt135-assignment-3-to-do-lists-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120268&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPT135 Assignment 3- To-do Lists Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Getting Started

In this assignment we’re going to build a to-do list application using C++ classes. Don’t go on to the next step until you’ve got the current step working correctly.

Part 1: The Base Program

Step 1.1

In a3.cpp, write a program that prints “Welcome to assignment 3!”.

It should also #include the following:

“`cpp

include “cmpt_error.h” include include

“` cmpt_error.h contains the function cmpt::error(msg) which, when called, crashes your programs and prints msg on the screen.

Other #includes will be used later in the assignment. Only use the #includes specified in the steps! Don’t include any other files.

All the code you write for this assignment will be in a3.cpp.

Note Throughout this assignment, you do not need to check for invalid data. You can assume that your functions and methods will always be passed valid data. This is a simplification that isn’t acceptable in real life, but we will allow it for his assignment since we want to focus on objects and classes instead of error-checking.

“`cpp // …

include “Date_base.h”

public: // … }; “`

Test what you’ve done by adding this function to a3.cpp:

cout &lt;&lt; xmas.get_day() &lt;&lt; ” ” &lt;&lt; xmas.get_month() &lt;&lt; ” ”

&lt;&lt; xmas.get_year() &lt;&lt; ” “;

} “`

Call it in main() and compile and run your program to check the results:

“`cpp // …

int main() { cout &lt;&lt; “Welcome to assignment 3! “; step_2_1_test(); } “`

Step 2.2: Add an Assignment Operator

Note Don’t start this step until you’ve finished the previous one.

Uncomment the operator= method in Date_base.h. In it’s body, add code to assign the day, month, and year from the other object to the current object. Finally, return the current object using *this.

Test what you’ve done by adding this function to a3.cpp:

assert(a.get_day() == b.get_day()); assert(a.get_month() == b.get_month()); assert(a.get_year() == b.get_year());

assert(a.get_day() == b.get_day()); assert(a.get_month() == b.get_month()); assert(a.get_year() == b.get_year()); cout &lt;&lt; “All step_2_2 tests passed! “;

} “`

Call it in main() and compile and run your program to check the results:

“`cpp // …

int main() { cout &lt;&lt; “Welcome to assignment 3! “;

step_2_1_test(); step_2_2_test();

} “`

You should still call the previous test function, just in case you made a change that broke some previous code.

Step 2.3: Add to_string

Note Don’t start this step until you’ve finished the previous one.

Test what you’ve done by adding this function to a3.cpp:

} “`

Call it in main() and compile and run your program to check the results:

cpp int main() { cout &lt;&lt; “Welcome to assignment 3! “; step_2_1_test(); step_2_2_test(); step_2_3_test(); } Step 2.4: Add a Constructor from a String

Note Don’t start this step until you’ve finished the previous one.

Test what you’ve done by adding this function to a3.cpp:

assert(b.get_day() == 4); assert(b.get_month() == 19); assert(b.get_year() == 1999);

assert(c.get_day() == 1); assert(c.get_month() == 1); assert(c.get_year() == 0); cout &lt;&lt; “All step_2_4 tests passed! “;

} “`

Call it in main() and compile and run your program to check the results:

cpp int main() { cout &lt;&lt; “Welcome to assignment 3! “; step_2_1_test(); step_2_2_test(); step_2_3_test(); step_2_4_test(); }

Step 2.5: Add a Comparison Operator

Note Don’t start this step until you’ve finished the previous one.

Test what you’ve done by adding this function to a3.cpp:

assert(a &lt; b); assert(a &lt; c); assert(a &lt; d); assert(b &lt; c); assert(b &lt; d); assert(c &lt; d);

assert(!(a &lt; a)); assert(!(b &lt; a)); cout &lt;&lt; “All step_2_5 tests passed! “;

} “`

Call it in main() and compile and run your program to check the results:

cpp int main() { cout &lt;&lt; “Welcome to assignment 3! “; step_2_1_test(); step_2_2_test(); step_2_3_test(); step_2_4_test(); step_2_5_test(); }

Part 3: The Todo_item Class

Step 3.1: Create the Todo_item Class

“`cpp // a3.cpp

// …

include “Todo_item_base.h”

class Todo_item : public Todo_item_base { private: // …

public: // … }; “`

Then add all the getters and setters, as listed in Todo_item_base.

Test what you’ve done by adding this function to a3.cpp:

assert(buy_gifts.get_description() == “Buy gifts”); assert(buy_gifts.get_due_date().get_day() == xmas.get_day()); assert(buy_gifts.get_due_date().get_month() == xmas.get_month()); assert(buy_gifts.get_due_date().get_year() == xmas.get_year()); assert(!buy_gifts.is_done());

buy_gifts.set_done(); assert(buy_gifts.is_done()); buy_gifts.set_not_done(); assert(!buy_gifts.is_done());

assert(buy_gifts.get_due_date().get_day() == earlier.get_day()); assert(buy_gifts.get_due_date().get_month() == earlier.get_month()); assert(buy_gifts.get_due_date().get_year() == earlier.get_year());

buy_gifts.set_description(“Buy gifts for family”); assert(buy_gifts.get_description() == “Buy gifts for family”); cout &lt;&lt; “All step_3_1 tests passed! “;

} “`

Call it in main() to check the results. Make sure to also call all previous tests in main().

Step 3.2: Add to_string

Test what you’ve done by adding this function to a3.cpp:

} “`

Call it in main() to check the results. Make sure to also call all previous tests in main().

Step 3.3: Add to_html

Uncomment the to_html method in Todo_item_base.h. In its body, write code that creates and returns a string that can be used as an item in an HTML. The returned string has one of these formats:

&lt;li&gt;dd/mm/yyyy description&lt;/li&gt; if the item is not done.

&lt;li&gt;&lt;del&gt;dd/mm/yyyy description&lt;/del&gt;&lt;/li&gt; if the item is done.

In both cases, the string is wrapped by &lt;li&gt; and &lt;/li&gt; tags. If the item is done, use &lt;del&gt;/&lt;/del&gt; tags to draw a line through the text when displayed in HTML. If the item is not done, then don’t use &lt;del&gt; tags.

Test what you’ve done by adding this function to a3.cpp:

} “`

Call it in main() to check the results. Make sure to also call all previous tests in main().

Step 3.4: Add operator&lt;

Test what you’ve done by adding this function to a3.cpp:

Todo_item carve_pumpkin(“Carve pumpkin”, halloween);

Todo_item buy_gifts(“Buy gifts”, xmas); Todo_item weave_basket(“Weave basket”, easter);

assert(carve_pumpkin &lt; buy_gifts); assert(buy_gifts &lt; weave_basket); assert(carve_pumpkin &lt; weave_basket); assert(!(carve_pumpkin &lt; carve_pumpkin));

assert(!(buy_gifts &lt; carve_pumpkin)); assert(!(weave_basket &lt; buy_gifts)); assert(!(weave_basket &lt; carve_pumpkin)); cout &lt;&lt; “All step_3_4 tests passed! “;

} “`

Call it in main() to check the results. Make sure to also call all previous tests in main().

Step 3.5: Add a Constructor from a String

Add another constructor to Todo_item that takes a string as input. The string is formatted exactly the same as the output of

Test what you’ve done by adding this function to a3.cpp:

“`cpp void step_3_5_test() { Todo_item a(“01/01/0000@ buy a hamster”); assert(a.get_description() == “buy a hamster”); assert(a.get_due_date().get_day() == 1); assert(a.get_due_date().get_month() == 1); assert(a.get_due_date().get_year() == 0); assert(a.is_done());

assert(a &lt; b); assert(!(b &lt; a)); cout &lt;&lt; “All step_3_5 tests passed! “;

} “`

Part 4: The Todo_list Class

Step 4.1: Create the Todo_list Class

In a3.cpp, write a class called Todo_list that inherits from the Todo_list_base class in Todo_list_base.h:

“`cpp // …

include “Todo_list_base.h”

class Todo_list : public Todo_list_base { private: // … public: // … }; “`

In the private part of Todo_list, add variables for storing 0 or more Todo_items. If you use a vector to do this, make sure to add #include &lt;vector&gt; to the list of includes at the top of the file.

In the public part of Todo_list, add a default constructor that creates a Todo_list with no items (size 0). Also, implement all the getters and setters listed in Todo_list_base.h.

Test what you’ve done by adding this function to a3.cpp:

Todo_item weave_basket(“Weave basket”, easter);

Todo_item carve_pumpkin(“Carve pumpkin”, halloween);

Todo_list list; assert(list.size() == 0);

list.add_item(weave_basket); assert(list.size() == 1);

list.remove_item(0); assert(list.size() == 0); cout &lt;&lt; “All step_4_1 tests passed! “;

} “`

Step 4.2: Add Reading from a File

Uncomment the read_from_file method in Todo_list_base.h, and then implement it in a3.cpp. The method reads the contents of filename, adding each item to the list. If the file does not exist, it should do nothing and no change is made to the list.

Each line of filename is formatted exactly the same as the output of Todo_item::to_string. todo_example.txt is an example of such a file. It contains 11 Todo_items, and is used in the tests below.

Add #include &lt;fstream&gt; to the list of includes at the top of your a3.cpp.

Test what you’ve done by adding this function to a3.cpp:

“`cpp void step_4_2_test() { Todo_list list; list.read_from_file(“todo_example.txt”); assert(list.size() == 11);

} “`

Step 4.3: Add Writing to a File

The output of write_to_file should be formatted in exactly the same style as todo_example.txt. That way, you can read the file back in using read_from_file.

Add #include &lt;algorithm&gt; to the list of includes at the top of your a3.cpp so that you can use the standard C++ sort function.

Test what you’ve done by adding this function to a3.cpp:

“`cpp void step_4_3_test() { Todo_list list;

list.write_to_file(“step_4_3_output.txt”); list.write_to_html_file(“step_4_3_output.html”);

// read step_4_3_output.txt back in and compare to list Todo_list list2;

list2.read_from_file(“step_4_3_output.txt”); assert(list2.size() == 3); assert(list2.get_item(0).get_description() == “Weave basket”); assert(list2.get_item(1).get_description() == “Carve pumpkin”); assert(list2.get_item(2).get_description() == “Buy tinsel”);

assert(list2.get_item(0).is_done() == true); assert(list2.get_item(1).is_done() == false); assert(list2.get_item(2).is_done() == false); cout &lt;&lt; “All step_4_3 tests run: check the HTML results by hand! “;

} “`

Here are the output files created by the test: step_4_3.txt, step_4_3.html. Make sure to manually check that step_4_3.html looks correct.

Part 5: The Final Program

As a final test of your a3.cpp, write and test a void function called part5() that reads the file part5_todos.txt and then prints this:

Print the output exactly in this format.

In addition, make a file called final_output.txt created by a call to write_to_file. And make a file called final_output.html created by a call to write_to_html_file.

Submit Your Work

Please put all your code into a3.cpp, and submit it on Canvas. Implement all the methods and functions exactly as described, otherwise the marking software will probably give you 0!

The only file you submit is a3.cpp: don’t submit any other files. The marker will use the standard makefile to compile it, and copies of cmpt_error.h and Date_base.h, Todo_item_base.h, and Todo_list_base.h will be in the same folder as a3.cpp when it’s compiled and tested.

Basic Requirements

It must compile on Ubuntu Linux using the standard course makefile:

$ make a3 g++ -std=c++17 -Wall -Wextra -Werror -Wfatal-errors -Wno-sign-compare -Wnon-virtual-dtor -g a3.cpp o a3

If your program fails to compile, your mark for this assignment will be 0.

A copy of cmpt_error.h will be in the same folder as a3.cpp when it’s compiled, so your program can use cmpt::error if necessary.

It must have no memory leaks or memory errors, according to valgrind, e.g.:

“` $ valgrind ./a3

// … lots of output … “`

A program is considered to have no memory error if:

In the LEAK SUMMARY, definitely lost, indirectly lost, and possibly lost must all be 0.

The ERROR SUMMARY reports 0 errors.

It is usually okay if still reachable reports a non-zero number of bytes.

You must include the large comment section with student info and the statement of originality. If your submitted file does not have this, then we will assume your work is not original and it will not be marked.

If your program meets all these basic requirements, then it will graded using the marking scheme on Canvas.

Marking Scheme

All code is sensibly and consistently indented, and all lines are 100 characters in length, or less.

Whitespace is used to group related pieces of a code to make it easier for humans to read. All whitespace should have a purpose.

Variable and function names are self-descriptive.

Appropriate features of C++ are used, as discussed in class and in the notes. Note If you use a feature that we haven’t discussed in class, you must explain it in a comment, even if you think it’s obvious.

Comments are used when needed to explain chunks of code whose purpose is not obvious from the code itself. There should be no commented-out code from previous versions.

No unnecessary work is done.

No unnecessary memory is used.

1 mark for correct code for each of 2.1, 2.2, 2.3, 2.4, and 2.5

1 mark for correct code for each of 3.1, 3.2, 3.3, 3.4, and 3.5

1 mark for correct code for each of 4.1, 4.2, 4.3

Deductions
