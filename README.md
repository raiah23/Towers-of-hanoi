# Towers-of-Hanoi
Towers of Hanoi is an ancient mathematical puzzle that starts off with three stacks and many disks.

## Objective
**The objective of the game is to move the stack of disks from the leftmost stack to the rightmost stack.**
![towers-of-hanoi](https://user-images.githubusercontent.com/26908164/186515992-8489c8c0-4630-4ac6-a315-25e8a840707d.PNG)

The game follows three rules:
 - Only one disk can be moved at a time.
 - Each move consists of taking the upper disk from one of the stacks and placing it on top of another stack or on an empty rod.
 - No disk may be placed on top of a smaller disk.
In this project, I have used stacks to implement this game! 

## Play the game,
Download this repo or pull it. Then simply run the following,
```python3 towers_of_hanoi.py```
If you choose 3 then you may end up finishing the game with optimal moves like me,
```
Let's play Towers of Hanoi!!

How many disks do you want to play with?
3

The fastest you can solve this game is in 7 moves



...Current Stacks...
Left Stack: [3, 2, 1]
Middle Stack: []
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: [3, 2]
Middle Stack: []
Right Stack: [1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [3]
Middle Stack: [2]
Right Stack: [1]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
R

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
M



...Current Stacks...
Left Stack: [3]
Middle Stack: [2, 1]
Right Stack: []

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: []
Middle Stack: [2, 1]
Right Stack: [3]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
L



...Current Stacks...
Left Stack: [1]
Middle Stack: [2]
Right Stack: [3]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
M

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R



...Current Stacks...
Left Stack: [1]
Middle Stack: []
Right Stack: [3, 2]

Which stack do you want to move from?

Enter L for Left
Enter M for Middle
Enter R for Right
L

Which stack do you want to move to?

Enter L for Left
Enter M for Middle
Enter R for Right
R


You completed the game in 7 moves, and the optimal number of moves is 7

```
