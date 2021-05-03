**1. What is wrong with this Python loop:**
        n = 5
while n > 0 :
        print n
print 'All done'

1) This loop will run forever **This**
2) There should be no colon on the while statement
3) The print 'All done' statement should be indented four spaces
4) while is not a Python reserved word


**2. What does the break statement do?**
1) Jumps to the "top" of the loop and starts the next iteration
2) Resets the iteration variable to its initial value
3) Exits the currently executing loop **This**
4) Exits the program


**3. What does the continue statement do?**
1) Resets the iteration variable to its initial value
2) Exits the currently executing loop
3) Jumps to the "top" of the loop and starts the next iteration **This**
4) Exits the program


**4. What does the following Python program print out?**
tot = 0 
for i in [5, 4, 3, 2, 1] :
        tot = tot + 1
print tot

1) 0
2) 5 **This**
3) 10
4) 15


**5. What is the iteration variable in the following Python code:**
        friends = ['Joseph', 'Glenn', 'Sally']
for friend in friends : 
        print 'Happy New Year:',  friend
print 'Done!'

1) friend **This**
2) friends
3) Sally
4) Joseph


**6. What is a good description of the following bit of Python code?**
zork = 0
for thing in [9, 41, 12, 3, 74, 15] :
        zork = zork + thing
print 'After', zork

1) Sum all the elements of a list **This**
2) Find the smallest item in a list
3) Count all of the elements in a list
4) Compute the average of the elements in a list


**7. What will the following code print out?**
smallest_so_far = -1
for the_num in [9, 41, 12, 3, 74, 15] :
        if the_num < smallest_so_far :
        smallest_so_far = the_num
print smallest_so_far
**Hint: This is a trick question and most would say this code has a bug - so read carefully**

1) -1 **This**
2) 3
3) 74
4) 42


**8. What is a good statement to describe the is operator as used in the following if statement:**
        if smallest is None : 
        smallest = value

1) The if statement is a syntax error
2) matches both type and value **This**
3) Is true if the smallest variable has a value of -1
4) Looks up 'None' in the smallest variable if it is a string


**9. Which reserved word indicates the start of an "indefinite" loop in Python?**
1) while **This**
2) def
3) break
4) for
5) indef


**10. How many times will the body of the following loop be executed?**
n = 0
while n > 0 :
        print 'Lather'
print 'Rinse'
print 'Dry off!'

1) 1
2) 0 **This**
3) 5
4) This in an infinite loop