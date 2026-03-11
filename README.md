
# List ADT using Array - Student Record System

students = []

n = int(raw_input("Enter number of students: "))

for i in range(n):
    name = raw_input("Enter student name: ")
    mark = int(raw_input("Enter student mark: "))
    students.append([name, mark])

print "\nStudent Records:"
for i in students:
    print "Name:", i[0], "Mark:", i[1]


OUTPUT 

Enter number of students: 2
Enter student name: Ravi
Enter student mark: 85
Enter student name: Anu
Enter student mark: 90

Student Records:
Name: Ravi Mark: 85
Name: Anu Mark: 90
