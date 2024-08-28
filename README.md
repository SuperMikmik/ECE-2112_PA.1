# PROGRAMMING ASSIGNMENT 1
Name: Miko Ksyle B. Cruz <br>
Section 2ECE-D <br>
Date 8/29/2024 <br>
# Documentation
<h3>ALPHABET SOUP PROBLEM</h3>
<h4>Create a function that takes a string and returns a string with its letters in alphabetical order.</h4>
For this problem, the .sort function comes to mind. After utilizing the .sort function, the immediate obstacle is that the .sort of the function's output is a list. So, it must be combined into one word to achieve the goal of the instructions. That is where the .join function comes to the rescue.<br>

![image](https://github.com/user-attachments/assets/4331c48a-016d-43ef-a10c-6a6d24b37c47)

<h3>EMOTICON PROBLEM</h3>
<h4>Create a function that changes specific words into emoticons. Given a sentence as a string, replace the words smile, grin, sad, and mad with their corresponding emoticon.</h4>
The function can be created in multiple ways. But the route I took is utilizing the .replace function. I overcomplicated the problem by adding an if and in function in the code, but in the end, the function only needs to replace all the keywords with their corresponding emoji, so only the .replace functions remain.<br>

![image](https://github.com/user-attachments/assets/1603f6de-66c2-422d-904a-41fd89704423)

<h3>UNPACKING LIST PROBLEM</h3>
<h4>Unpack the list writeyourcodehere into three variables, being first, middle, and last, with middle being everything in between the first and last element. Then print all three variables.</h4>
As always, I overcomplicated the problem by utilizing loops to gather the contents of the middle variable, but after experimenting with it, I can use the 0-based indexing to my advantage. The first and last variables were straightforward as it was always index[0] and index[-1], respectively. Then I remembered that I don't need a loop to check each item in a list; I can just use the [1:-1] index for that.<br>

![image](https://github.com/user-attachments/assets/43012cc1-fe6a-4c30-8402-6282df9c1a35)
