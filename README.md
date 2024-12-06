# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
      # Developed by: RavivarmanVV
      # Register No:24006127
      def max_marks(marks):
          marks.sort()
          large=marks[-1]
          return large



```

ii)	# To find the maximum marks using the list method max().
```Python
    # Developed by: RavivarmanVV
    # Register No:24006127
    def max_marks(marks):
      large=max(marks)
      return large

```

iii) # To find the maximum marks without using builtin functions.
```Python
      # Developed by: RavivarmanVV
      # Register No: 24006127
      def max_marks(marks):
          max_mark=0
          for i in marks:
              if i>max_mark:
                  max_mark=i
          return max_mark


```



## Output:
i)	# To find the maximum of marks using the list method sort.
![image](https://github.com/user-attachments/assets/afe3a000-3a23-4ed0-bc86-d218ef61bf5e)


ii)	# To find the maximum marks using the list method max().
![image](https://github.com/user-attachments/assets/030ef7dc-2bc8-4be8-b2c3-72a773025d2e)


iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/user-attachments/assets/f3543f98-ed7c-4795-af2f-93660981fdbe)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
