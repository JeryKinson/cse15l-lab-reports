<img width="1223" alt="Screen Shot 2022-05-02 at 22 01 47" src="https://user-images.githubusercontent.com/46670042/166406487-b3b85bb3-7c2b-46ae-a532-67c3b7c0c764.png">

[Link](https://github.com/JeryKinson/cse15l-lab-reports/blob/main/test-file4.md)

<img width="869" alt="Screen Shot 2022-05-02 at 22 28 16" src="https://user-images.githubusercontent.com/46670042/166408130-1fbb04eb-6be2-444c-8af8-3c70bc6ae04c.png">

The reason why we have this is because in the file we want to read, there is no enough element the compile can read. But in the while loop, we did not add any if statement or some other solutions to check if the file does not meet the requirement. That could be consider as an edge case. So at this time, we need some code to check and stop it when we test the file like test-file4.md

<br /><br /><br /><br />


<img width="1202" alt="Screen Shot 2022-05-02 at 22 01 16" src="https://user-images.githubusercontent.com/46670042/166406494-b65eb182-6e51-40a7-be9f-452a24f1ac51.png">

[Link](https://github.com/JeryKinson/cse15l-lab-reports/blob/main/test-file2.md)

<img width="742" alt="Screen Shot 2022-05-02 at 22 23 20" src="https://user-images.githubusercontent.com/46670042/166407759-bc748198-5c23-4548-9762-b63fe1e6bb22.png">

Since this is an infinity loop which means there is nothing to stop the loop. It will cause the program keeping running until running out of the memory. So we need to add some statements to stop the program

<br /><br /><br /><br />


<img width="1221" alt="Screen Shot 2022-05-02 at 22 00 50" src="https://user-images.githubusercontent.com/46670042/166406500-899033a4-617b-437d-b331-5ac6c798d113.png">

[Link](https://github.com/JeryKinson/cse15l-lab-reports/blob/main/test-file.md)

<img width="742" alt="Screen Shot 2022-05-02 at 22 17 23" src="https://user-images.githubusercontent.com/46670042/166407430-ceeb5753-cd59-46b3-aeda-9cbfbcc519a5.png">

The reason why we need to do this is because we need to first figure out why this bug happen. It is hard to find the problem directly looking up the code. But we can print the currentindex out each time so that we can easily find the problem

