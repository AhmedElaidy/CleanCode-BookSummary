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

