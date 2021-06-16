# Algorithm-A1
First try to implement sorting method for string in Python

I used a code I found (did not made myself) to imitate the Bubble sort algorithm for the list of numbers. That did work, however, the task was
to sort the name in alphabetic orded using Bubble sort algorithm. Only then I found out about built-in functions that help to sort string.
I used x to name my string 'Anna'- word I had to sort in alphabetic order. 
x='Anna'
Then I used built-in function of sort(x) to sort the letters in alphabetic order, but it gave me the result of letters being seperated (but in the right order), so I used function .join to make the results as a one word rather than seperated letters. The final code is:
x='Anna'
print(''.join(sort(x)))
