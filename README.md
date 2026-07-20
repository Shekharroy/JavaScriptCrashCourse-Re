# JavaScript Fundamentals
# NOTE - JavaScript is the default scripting language in HTML, so the type="text/javascript" attribute is no longer necessary in '<script>' tags. Older examples might still include it, but it can be omitted without affecting functionality.

# JavaScript Functions and Events - A JavaScript function is a block of JavaScript code, that can be executed when "called" for. For example, a function can be called when an event occurs, like when the user clicks a button.
# Explanation -  A JavaScript function is a reusable block of code that performs a specific task. It can be defined once and then executed multiple times throughout your program. Functions help organize your code, make it more modular, and improve readability.

 -- Here's a breakdown of key aspects:

Definition: You define a function using the function keyword, followed by a name, a list of parameters in parentheses, and the code to be executed within curly braces.

javascript
function greet(name) {
  return "Hello, " + name + "!";
}
Calling/Invoking: To execute a function, you "call" or "invoke" it by using its name followed by parentheses, passing any required arguments.

javascript

greet("Alice"); // This would return "Hello, Alice!"
Parameters and Arguments:

Parameters are placeholders for values that a function expects to receive when it's called (e.g., name in the greet example).
Arguments are the actual values passed to the function when it's invoked (e.g., "Alice" in the greet("Alice") example).
Return Value: Functions can optionally return a value using the return keyword. If no return statement is present, the function implicitly returns undefined.

Event Handling: As your example states, functions are often used as event handlers. This means they are executed when a specific event occurs, such as a user clicking a button, a page loading, or a form being submitted.

javascript
<button onclick="myFunction()">Click me</button>

<script>
function myFunction() {
  alert("Button clicked!");
}
</script>

# Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display.

# Use innerHTML when you want to change an HTML element.

# Use innerText when you only want to change the plain text.
# Using document.write() after an HTML document is loaded, will delete all existing HTML: --> The document.write() method should only be used for testing.
# window.alert():->
# You can skip the window keyword.
# In JavaScript, the window object is the global scope object. 
# This means that variables, properties, and methods by default belong to the window object. 
# This also means that specifying the window keyword is optional:
# For debugging purposes, you can call the console.log() method in the browser to display data.
# JavaScript does not have any print object or print methods.
# You cannot access output devices from JavaScript.
# The only exception is that you can call the window.print() method in the browser to print the content of the current window.

# Syntax Rule: -
# 1. How to declear variables: --> let x=5; and let y=6;
# 2. How to compute values: --> let z = x+y;

# JavaScript Values:
# Javascript syntax defines two types of values: 1. Literals(Fixed Valuies), 2. Variables (Variables values)
  # Note:- Numbers can be written with or without decimals. e.g. 10 or 10.50 <-- Example of Literals(Fixed Values)
  # JavaScript String: -> Strings are text, written within double or single quotes:

  # JavaScript Keywords
  # JavaScript keywords are used to defines actions to be performed.

  # The let and const keywords create variables:-->  let x = 5; const fname = "John";

  # JavaScript keywords are case-sensitive.

  # JavaScript does not interpret LET or Let as the keyword let.(JavaScript, LET या Let को 'let' कीवर्ड के तौर पर नहीं समझता है। Because JavaScript कीवर्ड केस-सेंसिटिव होते हैं।)

  # JavaScript Variables:- Variables are containers for storing data values. Variables must be identified with unique names. (JavaScript वेरिएबल्स:- वेरिएबल्स डेटा वैल्यूज़ को स्टोर करने के लिए कंटेनर होते हैं। वेरिएबल्स की पहचान यूनिक नामों से की जानी चाहिए।)

  # JavaScript Identifiers
  # An identifier is the name you give to a variable.

  # Rules for identifiers:

  # Must start with a letter, _, or $
  # Can contain digits after the first character
  # Cannot be a reserved keyword (let, const, if, etc.)
  # Are case-sensitive
# ( JavaScript आइडेंटिफ़ायर: - आइडेंटिफ़ायर वह नाम है जो आप किसी वेरिएबल को देते हैं।

 # आइडेंटिफ़ायर के नियम: 1. यह अक्षर (letter), _ या $ से शुरू होना चाहिए। पहले कैरेक्टर के बाद इसमें अंक (digits) हो सकते हैं। 2. यह कोई रिज़र्व्ड कीवर्ड (जैसे let, const, if, आदि) नहीं हो सकता। 3. ये केस-सेंसिटिव (case-sensitive) होते हैं। )

 # JavaScript Operators: 1. JavaScript assignment operators (=) assign values to variables. 2. JavaScript uses arithmetic operators ( + - * / ) to compute values.

 # JavaScript Expressions:- An expression is a combination of values, variables, and operators, which computes to a value. (एक्सप्रेशन, वैल्यूज़, वेरिएबल्स और ऑपरेटर्स का एक कॉम्बिनेशन होता है, जो कैलकुलेट होकर एक वैल्यू देता है।)

 # JavaScript Expressions:->> An expression is a combination of values, variables, and operators, which computes to a value.

 # BODMAS: - 

 # Example of BODMAS in ActionLet's solve the expression: 10 + 2 × (3 + 2)²Brackets first: Calculate (3 + 2)10 + 2 × (5)²Orders next: Calculate 5² (5 × 5 = 25)10 + 2 × 25Multiplication next: Calculate 2 × 2510 + 50Addition last: Calculate 10 + 50 = 60

 # Breaking Down the RuleWhen presented with a complex equation, operations cannot be solved simply from left to right. You must follow the BODMAS sequence strictly: 

 # 1. Brackets: Always clear the brackets first, solving them from the "inside out" (e.g., round (), curly {}, then square []). 

 # 2.Orders: Solve any exponents, powers, or square roots (e.g., 3²). 

 # 3.Division & Multiplication: These two have equal priority. Evaluate them from left to right as they appear in the equation.

 # 4.Addition & Subtraction: These operations also share the same priority. Like multiplication and division, solve them from left to right as they appear.

 # JavaScript and Camel Case: 
 # Historically, programmers have used different ways of joining multiple words into one variable name:

 # Hyphens: first-name, last-name, master-card, inter-city.

 # Hyphens are not allowed in JavaScript. They are reserved for subtractions.

 # Underscore: first_name, last_name, master_card, inter_city.

 # Upper Camel Case (Pascal Case): FirstName, LastName, MasterCard, InterCity.


 # Lower Camel Case: firstName, lastName, masterCard, interCity.

 # JavaScript programmers tend to use lower camel case.

 # JavaScript Statements:- 
  -- let x, y, z; // Statement1; 
  -- x = 5;       // statement2;
  -- y = 6;       // statement3;
  -- z = x+y;     // Statement4;

# ***** JavaScript Programs ****
   # A computer program is a list of "instructions" to be "executed" by a computer.
   # These programming instruction are called statements.
   # Most JavaScript programs contains many statements;
   # The statements are executed one by one, in the same order as they are written;
   # In HTML Javascript Prgrams are executed by the web browser.

# ***** JavaScript Statement *****
  # javascript statements are composed of:
  # 1. Values
  # 2. Operators
  # 3. Expressions
  # 4. Keywords, and 
  # 5. Comments

  # Semicolons separate JavaScript statements. Add a semicolon at the end of each executable statement: E.g:
   # let a, b, c;  // Declare 3 variables
   # a = 5;        // Assign the value 5 to a
   # b = 6;        // Assign the value 6 to b
   # c = a + b;    // Assign the sum of a and b to c

  # When separated by semicolons, multiple statements on one line are allowed: E.g: a = 5; b = 6; c = a + b;
  # On the web, you might see examples without semicolons. Ending statements with semicolon is not required, but highly recommended.

   # **** JavaScripr White Space ****
   # JavaScript ignores multiple spaces. You can add white space to your script to make it more readable.

   # The following lines are equivalent:
   # let person = "Hege";
   # let person="Hege";

   # A good practice is to put spaces around operators ( = + - * / ): E.g: let x = y + z;
   # JavaScript Line Length and Line Breaks: -For best readability, programmers often like to avoid code lines longer than 80 characters. If a JavaScript statement does not fit on one line, the best place to break it is after an operator: E.g:- document.getElementById("demo").innerHTML =
   # "Hello Dolly!";

   # JavaScript Code Blocks
   # JavaScript statements can be grouped together in code blocks, inside curly brackets {...}. The purpose of code blocks is to define statements to be executed together. ( JavaScript स्टेटमेंट्स को कर्ली ब्रैकेट्स {...} के अंदर कोड ब्लॉक्स में एक साथ रखा जा सकता है। कोड ब्लॉक्स का मकसद उन स्टेटमेंट्स को तय करना है जिन्हें एक साथ चलाया जाना है। )

   # JavaScript Variables:
   #  Variables = Data Containers
   # JavaScript variables are containers for data.
   # JavaScript variables can be declared in 4 ways: Modern JavaScript:- 1. Using let; 2. Using const; Older JavaScript: 3. Using var (Not Recommended); 4. Automatically (Not Recommended);

   # Variables are labels for data values.

   # Variables are containers for storing data.

   # JavaScript Identifiers:
   # Variables are identified with names called identifiers.
   # Names can be short like x, y, z.
   # Names can be descriptive like age, sum, carName.

   # The rules for constructing names (identifiers) are:

   . Names can contain letters, digits, underscores, and dollar signs.
   . Names must begin with a letter, a $ sign or an underscore (_).
   . Names are case sensitive (X is different from x).
   . Reserved words (JavaScript keywords) cannot be used as names.
  #  Numbers are not allowed as the first character in names.

  # This way JavaScript can easily distinguish identifiers from numbers.

  # A convention among professional programmers is to start a name with underscore for "private" variables.

  # Using the $ is not very common in JavaScript, but professional programmers often use it as an alias for the main function in JavaScript libraries.
  # JavaScript Dollar Sign $: - JavaScript also treats a dollar sign as a letter. Identifiers containing $ are valid variable names:

  # Declaring JavaScript Variables: Creating a variable in JavaScript is called declaring a variable. You declare a JavaScript variable with the let keyword or the const keyword.

  # Declaring a Variable Using let: e.g.: let carName; - After the declaration, the variable has no value (technically it is undefined).

 # To assign a value to the variable, use the equal sign: carName = "Volvo";

 # Always use const if the value should not be changed

 # When to Use var, let, or const?
  1. Always declare variables

  2. Always use const if the value should not be changed

  3. Always use const if the type should not be changed (Arrays and Objects)

  4. Only use let if you cannot use const

  5. Avoid using var.

# JavaScript Data Types: JavaScript variables can hold 8 datatypes.
# The Assignment Operator: In JavaScript, the equal sign (=) is an assignment operator, not an equal to operator. This is different from algebra. The following does not make sense in algebra: e.g: x = x + 5;
   In JavaScript, however, it makes perfect sense: it assigns the value of x + 5 to x.

  (It calculates the value of x + 5 and puts the result into x. The value of x is incremented by 5.)


# NOTE: --> The equal to operator is written like == in JavaScript.
# If you put a number in quotes, the rest of the numbers will be treated as strings, and concatenated.

# Let Hoisting: --> Variables defined with var are hoisted to the top and can be initialized at any time. Meaning: You can use the variable before it is declared:

# If you want to learn more about hoisting, study the chapter JavaScript Hoisting.

# Variables defined with let are also hoisted to the top of the block, but not initialized.

# Meaning: Using a let variable before it is declared will result in a "ReferenceError":

# Hoisting: --> Variables defined with var are hoisted to the top and can be initialized at any time. Meaning: You can use the variable before it is declared:

e.g:- <p id="demo"></p>

  <script>
  carName = "Volvo";
  document.getElementById("demo").innerHTML = carName;
  var carName;
  </script>

# Did You Know?
 # 1. JavaScript and Java are two completely different languages, both in concept and design.

 # 2. JavaScript was invented by Brendan Eich in 1995, and became an ECMA standard in 1997.

 # 3. ECMA-262 is the official name of the standard. ECMAScript is the official name of the language.

 # Question - What is JavaScript ?

 # Answer - A JavaScript is a high level (often) just in time compiled programming language that conforms to the ECMAScript sepecification

 # प्रश्न - जावास्क्रिप्ट क्या है?

 # उत्तर - जावास्क्रिप्ट एक उच्च स्तरीय (अक्सर) जस्ट इन टाइम संकलित प्रोग्रामिंग भाषा है जो ECMAScript विनिर्देश के अनुरूप है

 # JavaScript, alongside  HTML and CSS is one of the core technologies of the world wide web.

 # JavaScript is also used in mobile app development to cross platform app that can run on both iOS and android.

 # JavaScript is also used to create desktop application.

 # JavaScript is most popular programming language according to the 2021 Stack Overflow developer servey.

 # HTML और CSS के साथ जावास्क्रिप्ट वर्ल्ड वाइड वेब की मुख्य तकनीकों में से एक है।

 # जावास्क्रिप्ट का उपयोग मोबाइल ऐप डेवलपमेंट में क्रॉस प्लेटफ़ॉर्म ऐप के लिए भी किया जाता है जो iOS और Android दोनों पर चल सकता है।

 # जावास्क्रिप्ट का उपयोग डेस्कटॉप एप्लिकेशन बनाने के लिए भी किया जाता है।

 # 2021 स्टैक ओवरफ़्लो डेवलपर सर्वे के अनुसार जावास्क्रिप्ट सबसे लोकप्रिय प्रोग्रामिंग भाषा है।


 ## Q: - How to run the JavaScript Code ?
 # Answer -  1. Browser. 2. Node.js run time

 # Question - What is variable?
 # Answer - Variable are use to stored information.

 # प्रश्न - चर क्या है?
# उत्तर - चर का उपयोग सूचना संग्रहीत करने के लिए किया जाता है।

# Question - const declaration means ?
# Answer const declaration is must be initialized, and never changed or re-assigned.

# Question - let declaration means?
# Answer - let declartions are to initialized at the time of declartion, and if first declear the variable and then initialized the value when required.
# 2. if we wnat the chnage the value or re- assigned the value as per requirement we able to do using let keyword. 

# प्रश्न - const घोषणा का अर्थ है?
# उत्तर const घोषणा को आरंभीकृत किया जाना चाहिए, और इसे कभी भी बदला या पुनः असाइन नहीं किया जाना चाहिए।

# प्रश्न - let घोषणा का अर्थ है?
# उत्तर - let घोषणाओं को घोषणा के समय आरंभीकृत किया जाना चाहिए, और यदि पहले चर को घोषित किया जाता है और फिर आवश्यकता पड़ने पर मान आरंभीकृत किया जाता है।
# 2. यदि हम मान बदलना चाहते हैं या आवश्यकता के अनुसार मान को पुनः असाइन करना चाहते हैं तो हम let कीवर्ड का उपयोग करके ऐसा कर सकते हैं।

# Data Types:- 

# In javaScript there are two types of data-types - 
# 1. Primitive and 2. Non-Primitive

# Primitive Data Types
 # 1. String type
 # 2. Number types
 # 3. Boolean type
 # 4. Undefined type
 # 5. Null type
 # 6. BigInt type
 # 7. Symbol type

# Non - Primitive Data Type
 # 1. Objects

 # String - String is a sequence of characters that represents a text value. 
 # Note - In javaScript string is sorounded by "" (double qoutes), ''(signe qoutes), and  `` (backtick)

 # Number Data Type: 
  # Number Data type - Is a data type were we assign the value like numerical value like. 1, 2, 23, 8000, ... etc 

# Boolean Data Type

# Boolean - Boolean is run the code conditionaly either value is to be true / false;

# Undefined data type: 

# Undefined - The value of the variable is not defined, i.e. undefined.
 # using the let or var declear the the variable - In the case of undefined data type

# NULL Data type
# Null - It is a spacial value which represent empty or unknown value in javascript.

# NOTE - we expilicitly not defined the value undefined but in the case of null we are able to defined null value. It means the value is not defined. Means undefined is expacted output. And but the variable will assigned the value with null, it means null is output (empty or unknown) value of that varibale.

# नोट - हमने स्पष्ट रूप से मान को अपरिभाषित नहीं किया है, लेकिन शून्य के मामले में हम शून्य मान को परिभाषित करने में सक्षम हैं। इसका मतलब है कि मान परिभाषित नहीं है। इसका मतलब है कि अपरिभाषित अपेक्षित आउटपुट है। और लेकिन चर को शून्य के साथ मान असाइन किया जाएगा, इसका मतलब है कि शून्य उस चर का आउटपुट (खाली या अज्ञात) मान है।

# Note - As a beginer yet not required know the "Data type BigInt and Symbol". Right now do not worry about this.

# Non-Primitive Type: -

 # Non Primitive type is a collection of values.

 # Object - In JavaScript Object is a complex data type. An object contains key - value pairs
 # "Key" should be always string or symbol data types. But the "value" will any types.

 # Syntax is : - const person = {
 #   'firstName':'Bruce',
 # }

 # Array - Is a also object data type
 # Array declaration like this - const oddNumber = [1, 3, 5, 7, 9]
 # If you want to access the array value using Array[position], meas oddNumber[0].
 # In array if you not defined any value with particular postion and you want to print this value you get as output is - undefined

 # JavaScript is dynamically typed language. It means you do not need to specify the data type at the declaration.
 # in JavaScript according to the assignment of data it will automatically consider the data type according to the assigned value.

 # In JavaScript also automatically data type will be converted in a particular data type when we need.