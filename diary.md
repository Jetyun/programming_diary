#What I found out today

######8/11/2023

1. I found out that multiplication is better than division in this tutorial in 2.28.34 timeStamp. This is answered and upvoted in [stackoverflow] (https://stackoverflow.com/questions/10535605/javascript-performance-divide-or-multiply-vs). |not tested|
The tutorial in 2.28.34 timeStamp also mentioned that when using for loop it is faster to use pre-incrementation(++i) than post-incrementation(I--)
2. I learn that there is a semi colon for every end of the line of a Javascript file, which is to tell the Javascript where the line ends. This doesn't related to the sucess of minifying Javascript file because the minifying tools |webpack, parcel, vite| will auto insert semi colon on each line before minifying code.
3. I learn that everyone has their own code style. |look at ESlint chapter in learnJavascript tomorrow|

######10/11/2023

1. I learn about big O notation in [freeCodeCamp] (https://youtu.be/Mo4vesaut8g?si=LzZP1XAvFJqoaH52). This is about analysing the effectiveness of our function if the input of the function is infinity (or the worst scenario of input ever).

2. In the [freeCodeCamp] (https://youtu.be/Mo4vesaut8g?si=LzZP1XAvFJqoaH52) they discussed about how sorting array by using midpoint (AKA binary search) has its time complexity of O(n log n), but I don't really understands how it occured yet eventhough I went through that part twice.

3. the same video also discuss about mergeSort function |function that seperate all the elements in the array into individual numbers, and compare the size of every two of them, and arrange the position of number| and how it is related to time complexity of O(n log n), but I don't really understands how it occured yet eventhough I went through that part twice.

4. the easiest to understand is the fibonacci function where it has the time complexity of O(2 n squared). the author of the video expanded the repetition of the function as in the picture below: 
![fibonacci_time_complexity](./pic/fibonacci_time_complexity.png "fibonacci time complexity"). 

5. Haven't finish the space complexity portion of the video yet



######11/11/2023

1. going through the tutorial of [freeCodeCamp] (https://youtu.be/RBSGKlAvoiM?si=8PpU-nCl0Pwrg_wm). Learned about the existence of Static and Dynamic Array, which is new to me since I never encounter these terms while learning Array in Javascript. Turns out that Static Array has a fix size of Array which you can only put a certain number of element before it is full. for Dynamic Array you can insert as many element in the array you need which is just like the usual array in Javascript.

