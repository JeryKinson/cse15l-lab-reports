CSE 15L Lab Report 5

I noticed that the test case 201 and test case 489 both are different when I run my code to test it and the given code to test it, then I decide to use vimdiff to make sure if my code passed these two tests or not. 

For the test case 489 should work fine for my code because I encountered a similar tester case before, which also has NewLine problems. 

For test case 201, it seems that "()" sorting cause problems because my code only detects the content between "(). In this 201.md, the space between the name and the link will be the key to make my code not work correctly. 

<img width="417" alt="Screen Shot 2022-06-05 at 15 40 32" src="https://user-images.githubusercontent.com/46670042/172073811-4975b978-38a2-4ece-8cbb-26966a650317.png">

201.md: https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/201.md
<img width="1092" alt="Screen Shot 2022-06-05 at 15 39 37" src="https://user-images.githubusercontent.com/46670042/172073842-a5b611bb-5b10-42a3-ab01-3c94158e4d5a.png">


489.md: https://github.com/nidhidhamnani/markdown-parser/blob/main/test-files/489.md
<img width="1091" alt="Screen Shot 2022-06-05 at 15 39 16" src="https://user-images.githubusercontent.com/46670042/172073845-088c148c-4839-47e5-8654-f9184215c8e6.png">

