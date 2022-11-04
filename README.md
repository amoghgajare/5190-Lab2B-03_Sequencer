# ESE5190 Lab 2B Part 03 - Sequencer

## Lab 2B - Amogh Gajare worked with Saurabh Parulekar


In the Sequencer Code, we create a boolean array to record 1s (BOOT button pressed) and 0s (BOOT button not pressed) at a uniform delay of 5ms.
When the counter reaches the last element, it breaks out of the loop and starts array compression. For reducing delays in array processing especially in REPL, we have compressed the array using Run Line Encoding 
 For example, It converts array 0,0,0,1,1,0,0 to 3f2t2f where t stands for `True (1)` and f stands for `False (0)`. As it contains only two types of elements in alternate fashion, it compresses it further to f3,2,2 where f indicates that the sequence starts with False and alternates between true and false after that.
 
 We record the BOOT button presses here and then play it after recording completes. We have tried to record BOOT button presses in a rhythm similar to [link](https://www.youtube.com/watch?v=dQw4w9WgXcQ)
 
 

https://user-images.githubusercontent.com/38959831/199864197-85b0d4d8-afe2-4a03-8991-a3b8947090e9.mp4
