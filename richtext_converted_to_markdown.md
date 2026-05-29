📘 While Loop & List Operations - Python Notes
==============================================

A simple Python example demonstrating the use of while loops, list operations, and basic data structure concepts.

💻 Code
-------

Plain textANTLR4BashCC#CSSCoffeeScriptCMakeDartDjangoDockerEJSErlangGitGoGraphQLGroovyHTMLJavaJavaScriptJSONJSXKotlinLaTeXLessLuaMakefileMarkdownMATLABMarkupObjective-CPerlPHPPowerShell.propertiesProtocol BuffersPythonRRubySass (Sass)Sass (Scss)SchemeSQLShellSwiftSVGTSXTypeScriptWebAssemblyYAMLXML`   counter = 1  while counter <= 10:      print(counter)      counter += 1  # If we did not include this, the program will print '1' continuously forever.  print(" ")  nums = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]  nums.remove(2)    print(nums)  print(" ")  num = 1  while num <= 1000:      print(num)      num *= 2    print(" ")  # .remove() is a method used with lists/sets to delete an item by value.  # .clear() removes all elements from a collection.  # a = [1, 2, 3]  # b = a  # a = []  # print(b)  # Output: [1, 2, 3] because b still points to the original list.  # deque (double-ended queue) is a data structure used for fast insertions/removals from both ends.  # Dictionaries and sets use { } but differ based on structure and key-value format.   `

🎯 Purpose
----------

*    Master and acquire proficiency in the while-loop concept
    
*    Understand real-world applications of the while-loop
    
*   Expand Python knowledge
    
*   Build consistency in coding practice
    

🎯 Contents
-----------

*   What is a while-loop
    
*   Syntax of while-loop
    
*   Examples and mini-projects
    
*   Some other extra functions
    

🚀 New functions to learn:
--------------------------

1.   .remove() is a method primarily used with sets and lists to delete a specific item by its value instead of its index.
    
2.  .clear() is used to remove all items/elements from a mutable collection
    
3.  In this case, the output will be \[1, 2, 3\] because only 'a' is reset to a new empty set, while 'b' still points to the original data.
    
4.  deque (pronounced 'deck') is short form for double-ended queue. We will study about this later, as this is complex.
    
5.  Dictionaries and sets are represented in '{ }', so we differentiate them using their content structure within the braces.
    

📈 Future Updates
-----------------

*   Add for loop examples for comparison
    
*   Include nested loops
    
*   Add more list methods (append, pop, extend)
    
*   Expand notes on deque, dictionaries, and sets with examples
    

⭐ Part of my Python learning notes repository.