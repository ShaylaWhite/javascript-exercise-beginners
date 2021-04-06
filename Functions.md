Functions 

A javascript function is a block of code designed to perform a particular task.

A Javascript function is executed when "something" inokes it (calls it).

//defining a function/////

function <function-name>()
{
    // code to be executed
};

//calling a function
<function-name>();
----------------------------------------------------
///Function Parameter//
 a function parameter can have value of any data type.

//Function is aynomous whne it doesnt have a name.
---------------------------------------------------

//The Arguements Object///

An arguments object includes value of each parameter.

An arguments object is still valid even if function does not include any parameters.

function ShowMessage() {
    alert("Hello " + arguments[0] + " " + arguments[1]);
}



ShowMessage("Steve", "Jobs"); 

ShowMessage("Steve", "Jobs"); // display Hello Steve Jobs

----------------------------------------------------
