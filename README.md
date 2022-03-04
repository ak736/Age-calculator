# Python
AGE LEFT CALCULATOR USING PYTHON
age = input("What is your current age?\n")
new_age = int(age)
numberofyearsleft = 90 - new_age
numberofdaysleft = numberofyearsleft * 365
numberofweeksleft = numberofyearsleft * 52
numberofmonthsleft = numberofyearsleft * 12
print(f"You have {numberofdaysleft} days left, You have {numberofweeksleft} weeks left, You have {numberofmonthsleft} months left")
