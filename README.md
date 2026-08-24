# Python

Simple Student Grade Manager using only Python standard features.

# Student Grade Manager

mark = int(input("Enter your mark (0-100): "))

if mark >= 90:
    grade = "A"
elif mark >= 80:
    grade = "B"
elif mark >= 70:
    grade = "C"
elif mark >= 60:
    grade = "D"
else:
    grade = "E"

print(f"Mark: {mark} -> Grade: {grade}")
Example output

If you enter 85:

Enter your mark (0-100): 85
Mark: 85 -> Grade: B
How it works
90–100 → A
80–89 → B
70–79 → C
60–69 → D
0–59 → E
Screenshot of the output
