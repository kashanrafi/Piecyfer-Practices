

<!-- 1. Focus on code readability...
=> Readable code is easy to follow, optimizes space and time. Here are a few ways to achieve that:

1. Write as few lines as possible.
2. Use appropriate naming conventions.
3. Segment blocks of code in the same section into paragraphs.
4. Use indentation to marks the beginning and end of control structures. Clearly specify the code between them.
5. Don’t use lengthy functions. Ideally, a single function should carry out a single task.
6. Use the DRY (Don’t Repeat Yourself) principle. Automate repetitive tasks whenever necessary. The same piece of code should not be repeated in the script.
7. Avoid Deep Nesting. Too many nesting levels make code harder to read and follow.
8. Capitalize SQL special words and function names to distinguish them from table and column names.
9. Avoid long lines. It is easier for humans to read blocks of lines that are horizontally short and vertically long. -->

<!-- 2. Standardize headers for different modules...
=> It is easier to understand and maintain code when the headers of different modules align with a singular format. For example, each header should contain:

1. Module Name
2. Date of creation
3. Name of creator of module
4. History of modification
5. Summary of what the module does
6. Functions in that module
7. Variables accessed by the module -->

<!-- 3. Don’t use a single identifier for multiple purposes...
Naturally, a single variable can’t be assigned multiple values or used for numerous functions. This would confuse everyone reading the code and would make future enhancements more difficult to implement. Always assign unique variable names. -->

<!-- 4. Leave comments and prioritize documentation...
Don’t assume that just because everyone else viewing the code is a developer, they will instinctively understand it without clarification. Devs are human, and it is a lot easier for them to read comments describing code function rather than scanning the code and making speculations.

Take an extra minute to write a comment describing the code function at various points in the script. Ensure that the comments guide any readers through the algorithm and logic implemented. Of course, this is only required when the code’s purpose is not apparent. Don’t bother leaving comments on self-explanatory code. -->

<!-- 5. Try to formalize Exception Handling...

=> Exception’ refers to problems, issues, or uncommon events that occur when code is run and disrupt the normal flow of execution. This either pauses or terminates program execution, which is a scenario that must be avoided.

=> However, when they do occur, use the following techniques to minimize damage to overall execution in terms of both time and dev effort:

1. Keep the code in a try-catch block.
2. Ensure that auto recovery has been activated and can be used.
3. Consider that it might be an issue of software/network slowness. Wait a few seconds for the required elements to show up.
4. Use real-time log analysis. -->

<!-- 6. Sider...
Sider is an automated code review tool that analyzes your team’s pull requests on the fly to help ensure that your codebase is consistent. It can check for violations of style, as well as code quality, and it helps your team stay up to speed on best practices, as well as the rule-sets for each project.  -->


some changes appear's on line 50