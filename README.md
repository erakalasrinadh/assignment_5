# assignment_5
# task 1
student_marks = {
    "Alice": 85,
    "Bob": 90,
    "Charlie": 78,
    "David": 92
}

name = input("Enter the student's name: ")
if name in student_marks:
    print(f"{name}'s marks are:", student_marks[name])
else:
    print("Student not found in the record.")
# output:
Enter the student's name: Alice
Alice's marks are: 85
Enter the student's name: john
Student not found in the record.
# task 2
numbers = list(range(1, 11))
first_five = numbers[:5]
reversed_list = first_five[::-1]
print("Original list:", numbers)
print("First five elements:", first_five)
print("Reversed first five elements:", reversed_list)
# output:
Original list: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
First five elements: [1, 2, 3, 4, 5]
Reversed first five elements: [5, 4, 3, 2, 1]
