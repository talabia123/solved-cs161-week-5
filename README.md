Download Link: https://assignmentchef.com/product/solved-cs161-week-5
<br>
<h1>Project 5.a</h1>

Write a class called Box that has three double fields called height, width and length. The class should have set methods for each field.  It should have a three-parameter constructor that takes three doubles and passes them to the set methods to initialize the fields of the Box.  It should have a default constructor that uses the set methods to initialize each field to 1.  It should have a method that calculates and returns the volume of the Box and a method that calculates and returns the surface area of the Box.

The class declaration (interface) and the function definitions (implementation) must be in separate files – the interface or “header” file has a .hpp extension and the implementation has a .cpp extension.  All data members should be private.

Your functions should have the following names:

<ul>

 <li>setHeight</li>

 <li>setWidth</li>

 <li>setLength</li>

 <li>getVolume</li>

 <li>getSurfaceArea</li>

</ul>

The files must be named: ​<strong>Box.hpp</strong>​ and ​<strong>Box.cpp </strong>About using multiple files:

<ol>

 <li>Make sure you’ve read and understood section 7.11.</li>

 <li>hpp should have “include guards” as discussed on page 447 (use “BOX_HPP”).</li>

 <li>cpp needs to #include Box.hpp. When you include your own .hpp files (header files), put double quotes around them instead of angled brackets.</li>

</ol>

(You should only #include .hpp files, ​<strong>not</strong>​ .cpp files.)

<ol start="4">

 <li>When testing your program with your own main method, put it in a separate file (this is the “client” code) and give it a name with a .cpp extension.</li>

 <li>Your main method also needs to #include Box.hpp.</li>

 <li>If you named the file with your main method “boxMain.cpp”, then you can compile your program with “g++ Box.cpp boxMain.cpp -o box”.</li>

</ol>




<h1>Project 5.b</h1>

Write a class called BankAccount that has a string data member called customerName, a string data member called customerID, and a double data member called customerBalance.  The class should have a constructor that takes two strings and a double (name, ID, balance) and uses them to initialize the data members.  The data members of this class do not need to be set after they are initialized, so this class doesn’t need any set methods – therefore the constructor will directly assign values to the data members instead of calling set methods to do it.  The class should have a get method for each data member.  It should have a method called withdraw that takes a

double parameter and deducts it from the current balance (the balance is allowed to be negative).  It should have a method called deposit that takes a double parameter and adds it to the current balance.

Your functions should have the following names:

<ul>

 <li>getCustomerName</li>

 <li>getCustomerID</li>

 <li>getCustomerBalance</li>

 <li>withdraw</li>

 <li>deposit</li>

</ul>

<h1>The files must be named: ​BankAccount.hpp​ and ​BankAccount.cpp</h1>





