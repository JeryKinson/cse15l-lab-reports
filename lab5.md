CSE 15L Lab Report 5

I noticed that the test case 201 and test case 489 both are different when I run my code to test it and the given code to test it, then I decide to use vimdiff to make sure if my code passed these two tests or not. 

For the test case 489 should work fine for my code because I encountered a similar tester case before, which also has NewLine problems. 

For test case 201, it seems that "()" sorting cause problems because my code only detects the content between "(). In this 201.md, the space between the name and the link will be the key to make my code not work correctly. 

<img width="417" alt="Screen Shot 2022-06-05 at 15 40 32" src="https://user-images.githubusercontent.com/46670042/172073811-4975b978-38a2-4ece-8cbb-26966a650317.png">
<br><br>

201.md: https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md
<img width="1092" alt="Screen Shot 2022-06-05 at 15 39 37" src="https://user-images.githubusercontent.com/46670042/172073842-a5b611bb-5b10-42a3-ab01-3c94158e4d5a.png">
For this case, the correct output should be the empty one. The key is that the order of the two () and the []. But my code just combine the first line's second () with the second line's []. That caused we got a wrong link. To fix that, we just need to simply write an if statement to set a condition to check is the ( exactly one index after the ]. If that is true, just do the common step as usual. Otherwise, we can skip it and continue to next [.

How to fix it:

<img width="290" alt="Screen Shot 2022-06-05 at 16 22 42" src="https://user-images.githubusercontent.com/46670042/172074808-77f6a97c-2b30-4421-82e7-9758a1a385bc.png">
<br><br>

489.md: https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/489.md
<img width="1091" alt="Screen Shot 2022-06-05 at 15 39 16" src="https://user-images.githubusercontent.com/46670042/172073845-088c148c-4839-47e5-8654-f9184215c8e6.png">
The reason for my code failed the tester case #489 is because there is a line change in the middle of the url link. However my algorithm just check the content between the "()" and "[]" and do not care the link's completion. The solution is to when the link has newliner inside the "()" or "[]", ignore the current link and skip to the next "(".

How to fix it:

<img width="292" alt="Screen Shot 2022-06-05 at 16 21 01" src="https://user-images.githubusercontent.com/46670042/172074770-e89c32be-c6d7-4d61-addb-2bff527dee00.png">
