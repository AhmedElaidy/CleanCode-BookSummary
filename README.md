<h2> What Is Clean Code </h2>
1- The code can be measured with either "good" or "bad" in the code review or by how many minutes it takes you to talk about it, so write clean code no matter how much time it takes time because in the future it will save your time whether by reducing bugs or by making it easy to fix bugs.<br><br>

2- A clean code should be elegant, efficient, readable, simple, without duplications, and well-written and function should be doing exact things and we can clean our code by minimizing big functions into small functions.

3- Clean code offers quality and understanding when we open a class.

4- It is necessary that your code is clean and readable for anyone to find and easily understand. Avoid wasting others' time.

5- When you write a code you should think first before writing any code that will make your code cleaner and of course save your time.

6- After writing a code, imagine yourself after 3 months at least from now, would you understand this code? if yes it is mostly a clean code, if not you should try to clean it.

7- Always Keep the code simple and stupid. Simpler is always better. Reduce complexity as much as possible.

8- Boy scout rule. Leave the campground cleaner than you found it.

<hr>
<h2> Naming </h2>

1- Don't use single-letter names in your code except in local variables inside short methods.

2- If a variable might be seen or used in multiple places in a body of code, it is imperative to give it a search-friendly name.

3- Avoid encoding, it just waste our time and there is enough encodings to deal with without adding more encoding.

4- Make meaningful distinction.

5- Use pronounceable and descriptive names so it doesn't cause errors when you try to call the name again and to facilitate communication.

6- Avoid acronyms and avoid confusing names, which may bring anyone who reads the code to the wrong conclusions.

7- Don't name a group of accounts as accountList except if the accounts type is a list.

<hr>
<h2> Functions </h2>

1- You should use names with words that say what it really does.

2- Try to make the method take fewer parameters so it can be easily understood.

3- The method should be easy to read and understand for you and every programmer coming after you.

4- Avoid making two methods that do the same thing (Avoid Duplication).

5- Parameters of the Boolean type as a parameter already clearly states that it does more than one thing so split the method.

6- The method should convey its intention to the reader.

7- Methods should only do one thing and they should do it well.

8- The methods should be small. Another rule for small methods is that they should be even lower than it is.

<hr>
<h2> Comments </h2>

1- A comment may be used to amplify the importance of something that may otherwise seem unimportant.

2- You should try to avoid writing comments because most programmers when updating the code they forget to update the comment or they ignore it.

3- If you wanted to write a comment then take your time to write it and make sure it is the best comment you can write. 

4- Avoid writing comments with redundant, useless, or false information.

5- Don't be afraid to remove useless comments because it just pollutes the code.

6- Try to explain what the code causes to happen.

7- Create method names and informative variables instead of explaining the code with comments.

8- Finally remember Comments do not save a bad code.

<hr>
<h2> Formatting </h2>

1- Formatting should tell us what is important in the function and make our eyes pay attention to it.

2- Try to make the class smaller to make it easy to read and understand.

3- Avoid horizontal alignment.

4- Try not to write over 120 chars per line so you won't have to scroll to see the rest of the line.

5- local variables should appear a the top of each function.

6- Try to make similar functions close to each other.

7- Use white space to associate related things and disassociate weakly related.

8- If one function calls another, they should be vertically close, and the caller should be above the callee.

<hr>
<h2> Objects and data structures </h2>

1- A data structure is a specialized format for organizing, processing, retrieving and storing data.

2- Objects hide the data and expose methods that operate the data.

3- Data structures expose your data and do not have significant methods.

4- Try to Hide internal structure.

5- Avoid hybrids structures by making half object and half data.

<hr>
<h2> Error Handling </h2>

1- Don't hide the error, Mention it and where it happens and what causes it

2- Try not to pass a Null in methods because it can generate NullPointerExceptions.

3- We should handle the error well and make it do the right thing.

4- Avoid returning a NULL in methods, preferably to return an empty object if there is no values.\

<hr>
<h2> Boundary </h2>

1- Read About API documentation well before using it.

2- Decide what specific features you need from the API.

3- Test API functionality from all sides.

4- Seperate API code from other functions to make boundaries to the API.

<hr>
<h2> Unit Tests </h2>

1- Unit tests allow you to be sure that every function does what is expected from it.

2- Try keeping your test code clean as much as possible.

3- If the test code is good you won't be fear to add a new test code.

4- Don't ignore the test code because it's important as the production code.

5- The test code should be readable, fast-running, repeatable in a lot of environments, and Independent of other code.

<hr>
<h2> Classes </h2>

1- Class name should tell us what is this class made for.

2- Class should do only one thing (have one responsibility) and do it well.

3- Separating classes reduces the opportunity of causing errors when adding new code (functions).

4- Variables should be defined at the top of the class.

5- Class size must be commensurate with his responsibilities.

<hr>
<h2> Systems </h2>

1- You need clean code and refactoring your code to achieve TDD (Test Driven Development)

2- The first version of the system is very hard to be perfect, the system must be available first then refactored then expanded to continue implementing new stories.

3- System responsibilities should be organized and separated But it must also be coherent. 

<hr>
<h2> Emergence </h2>

1- Try to improve the design in refactoring by applying all the knowledge and also by separating responsibilities, reducing (coupling, methods, and classes), increasing cohesion, and taking your time to name methods or classes.

2- To express the intention of the programmer, use more expressive code to facilitate maintenance. Choosing good names for functions, classes, and tests shouldn’t be small and well-written.  

3- Avoid duplication because it only brings additional work to us.

4- Check that every function in the system doing what is supposed to do by making unit testing for each part of the system.

<hr>
<h2> JUnit Internals </h2>

1- Refactoring is a repeatable process full of trial and error, and it is so close to something that we feel is worthy of a professional.

2- Any code can be improved, and each of us has a responsibility to make the code a little better than we found it.

3- Each line of code should be tested and not every function.

<hr>
<h2> Refactoring </h2>

1- If the code needs to refactor that doesn't mean it is not clean but every code can be improved.

2- You should have tests on your project first, then you can refactor your project safely.

3- Most of the refactoring is renaming with more meaningful names, dividing class's responsibilities or function's responsibilities, and eliminating duplicates. 

<hr>
<h2> Smells and Heuristics </h2>
<h3>Comments</h3>

1- You should make sure that the comment is appropriate and it should be about technical notes about code and design.

2- If you find an obsolete cmment, it is best to update it or get rid of it as quickly as possible. 

3- Remove redundant comments, comments should say what the code can't say.

4- You should take your time in writing code and delete it if the code is commented out; if someone needs it, he will go back to the old version.

<h3>Functions</h3>

1- Reduce the number of arguments the function has as possible, no arguments in the best case.

2- Avoid boolean arguments because it means that the function does more than one thing.

3- If you don't use the function, just delete it.

<h3>General</h3>

1- The obvious behaviour should be implemented.

2- Make sure to write a test for every boundary, Don’t rely on your intuition that every thing will work well.

3- Don't override safeties like turning off compiler warnings and turning off failure tests and telling yourself you will get them to pass later.

4- Don't repeat yourself (Avoid duplications), use abstraction instead.

5- The fewer methods a class has, the better. The fewer variables a function knows about, the better. The fewer instance variables a class has, the better.

6- Dead code dosen't apply new rules when the system updates so when you find dead code, Delete it from the system.

7- Local variables should be declared just above their first usage and private functions should be defined just below their first usage.

8- Be careful with the rules you choose, and once chosen, be careful to continue to follow them.

9- In general it is better to have many functions than to pass some code into a function to select the behavior.

10- In general you should prefer nonstatic methods to static methods, If you really want a function to be static, make sure that there 
    is no chance that you’ll want it to behave polymorphically. 

11- Break the calculations up into intermediate values that are held in variables with meaningful names.

12- If you are joining a new project, Take your time to know how the code works before adding new methods to it.

13- Prefer polymorphism to IF/ELSE or SWITCH/CASE ( polymorphism is to use the same method name in every function with different implimation ).

14- Replace magic numbers with named constants.

15- Encapsulate if conditions and avoid negative conditionals.

16- Functions should do one thing.

17- Encapsulate  boundary conditions (Don't use (level + 1) define it in a variable called nextLevel)

18- We don’t want a single module to know much about its collaborators we don’t want modules that useA to know about C. 
    (For example, we don’t want a.getB().getC().doSomething();).
    
<h3>Java</h3>

1- Avoid long import lists by using wildcards.

2- Use an enum instead of an int.

<h3>Names</h3>

1- Choose descriptive names because names in software are 90 percent of what makes software readable.

2- The length of a name should be related to the length of the scope (names like i and j are just fine if their scope is five lines long).

3- Avoid Prefixes such as m_ or f while naming your variables.

4- Name should tell us the side-effects, getOos(); funtion it creates the “oos” if it hasn’t been created already. Thus, a better name might be createOrReturnOos.

<h3>Tests</h3>

1- The tests are insufficient so long as there are conditions that have not been explored by the tests or calculations that have not been validated.

2- Take special care to test boundary conditions. We often get the middle of an algorithm right but misjudge the boundaries.

3- Bugs tend to congregate. When you find a bug in a function, it is wise to do an exhaustive test of that function. You’ll probably find that the bug was not alone.

4- Keep your tests fast because a slow test is a test that won’t get run.
