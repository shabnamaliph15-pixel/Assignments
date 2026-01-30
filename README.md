#Task 1: Create a Dictionary of Student Marks


students_marks = {
    "Alice": 85,
    "Neha": 92,
    "Rahul": 78,
    "Priya": 90
}
name = input("Enter the student's name: ")

if name in students_marks:
    print(f"{name}'s marks: students_marks[name]}")
else:
    print("Student not found.")





#Task 2: Demonstrate List Slicing 



numbers = list(range(1, 11))
first_five = numbers[:5]
reversed_first_five = first_five[::-1]
print("Original list :", numbers)
print("Extracted first five elements :", first_five)
print("Reversed extracted elements :", reversed_first_five)


