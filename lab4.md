My Markdown repository link: https://github.com/JeryKinson/Markdown-parse

The reviewed Markdown repository link: https://github.com/Combobyte/markdown-parser

My test cases code:

<img width="930" alt="Screen Shot 2022-05-30 at 20 54 18" src="https://user-images.githubusercontent.com/46670042/171090136-f01b4cde-aef6-48fc-a4eb-966597f4a51c.png">

My test results:

The second test passed!!!
<img width="1014" alt="Screen Shot 2022-05-30 at 21 24 45" src="https://user-images.githubusercontent.com/46670042/171092545-2c76b948-a428-4a26-8c25-1b9cb1b903ec.png">


<img width="813" alt="Screen Shot 2022-05-30 at 21 02 19" src="https://user-images.githubusercontent.com/46670042/171090410-3a75117c-616e-4f86-bafc-40a443797f45.png">

<img width="1476" alt="Screen Shot 2022-05-30 at 20 57 30" src="https://user-images.githubusercontent.com/46670042/171090231-a19ce496-ed72-4210-9e60-7cb0ee816a0c.png">


The review test cases code:

<img width="1258" alt="Screen Shot 2022-05-30 at 20 55 41" src="https://user-images.githubusercontent.com/46670042/171090145-6bc6e65c-6ff4-4779-8ff4-005ac5ebe303.png">

The review test results:

<img width="920" alt="Screen Shot 2022-05-30 at 20 57 05" src="https://user-images.githubusercontent.com/46670042/171090213-a8da75c4-71c4-4244-9cfd-e550e227352e.png">

<img width="813" alt="Screen Shot 2022-05-30 at 21 02 13" src="https://user-images.githubusercontent.com/46670042/171090404-c64efbf9-5eff-4a93-809f-97ad01717d4b.png">

The results we want to get should be:

<img width="575" alt="Screen Shot 2022-05-30 at 21 09 17" src="https://user-images.githubusercontent.com/46670042/171091114-127573d6-7e84-4ea7-8f1b-5ec72d1579fc.png">


Question:

1. Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.

Snippet 1 requires very complex changes to debug because " " is a big problem to distinguish between code and plain text comments in snippets. To fix this bug, we need to implement another special helper method to handle the relationship between between " " and the bracket parentheses, because it has higher priority than the other two

2. Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.

Yes, snippet 2 can be solved with a simple change where we set a temporary integer variable for the open parentheses and the close parentheses and compare them and if the two integers are not equal, the code should continue searching

3. Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

Yes, snippet 3 should be easy to fix. The main problem is just the newline format. To check if there is blank space and/or newlines between the open and close bracket, then skip to the next "(" and ignore this current link if there is it.

For my second test which is passed, just set a temporary integer variable for the open parentheses and the close parentheses and compare them and if the two integers are not equal, the code should continue searching
