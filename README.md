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