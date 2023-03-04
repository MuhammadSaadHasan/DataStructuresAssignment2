# Compiler built in C++

## Parsing the File

The file will be in txt format, and stack is used to read the file. There will be different tags in file, each tag have specific meaning like 
Start, head, paragraph, pre_exp, sol_exp,  post_exp, function, and read_image. 
Every tag has a syntax for open and closing like start tag will be start with |start| and end on |\start|. Same syntax will be followed for the other tags.

### Tag explanation:

* Start→ Indicates the starting and ending of document.
* Head→ Indicates the section header, you have to print it on the top.
* Tab→ insert tab.
* Priority→ This tag contains the document priority.
* Paragraph→ Contain the text that is printed, but there can be multiple tags inside the paragraph.
* Pre_exp→ There will be infix expression inside the tag and that expresion is converted into prefix form and printed on the place of infix expression.
* Post_exp→ There will be infix expression inside the tag and that expresion is converted into postfix expression and printed on the place of infix expression.
* Sol_exp→ There will be an expression inside the tag and is evaluated and that statement is printed on the place of infix expression.
* Function→ This tag contains the function. This fucntion is compiled and the output is shown.
* Read_image→ This tag will contain the image source path and that image is read. The image is compiled and finds the 
objects in region, it also save the new images generated by the algorithms.


