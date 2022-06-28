# stocks-analysis
### Overview 

In this module we are performing a refactor analysis on a VBA Challenge data to inorder understand the key parts of the coding process.

### Results

The results gathered while comparing the stock performance between 2017 and 2018 shows the execution times of the original script and refactored script.

### 2017 Stocks Analysis

The performance for the 2017 stocks had a great return year overall. Out of the 12 tickers, only 1 of them which was TERP, shows a negative return of 7.21%. The rest of the tickers had a postive return. We ran the original script for 2017 - I was able to get the code to run in 0.6328125 seconds as seen below. But when i ran the refactored script - it ran in 0.046875 seconds. The refactored scripted ran 10x seconds faster then the original script for 2017.


![image1](https://user-images.githubusercontent.com/100738128/176090831-7782bfe5-f30d-4229-96be-5031d09b30fe.png)

![image2](https://user-images.githubusercontent.com/100738128/176090923-1eca60cc-f8b1-421a-82ac-8715a087b562.png)

### 2018 Stocks Analysis

The performance of the 2018 stocks had a bad return year overall. Only 2 of the 12 tickers had a postive return, which were ENPH (+81.9% return) and RUN (+84% return).The rest of the tickers were negative. We do round two of running the original script for 2018 and got it running it in 0.6328125 seconds and when we run the refactored script after we see it was run in 0.46875 seconds. Again, its showing that it ran 10x seconds faster then the original script for 2018. 

![156954421-02a290ab-3496-4541-becc-189979cd6591](https://user-images.githubusercontent.com/100738128/176091031-e4945c3d-3ffd-49f5-a2b6-36e0f12b5654.png)

![156954423-6703012f-abce-48a4-bc2f-46509c5d8b60](https://user-images.githubusercontent.com/100738128/176091075-d542e5e8-204f-4a87-8cbb-603705b3c085.png)

### Final results

These results indicates that refactoring is a huge advantage for running code because this does not add new functionality but it is making the code for efficient since it is taking fewer steps and using less memory to complete the task.

The disadvantage it plays could be tranfering the code from the original script to the refactored script. It has proven to be difficult to make sure it all populates the correct data and runs properly. Trying to refactor and if done improperly can actually increase the time it takes to accomplish the task. Also if the original script is not noted properly, it can also be more time consuming to refactor the original script due to starting from scratch to understand how it operates.

Refactoring if done right has proven to be an amazing tool if mastered and has shown me that it is fundamental when coding.
