# quiz-game
print("================================")
print("      Python Quiz Game")
print("================================")

score = 0

# Question 1
print("\n1. What does CPU stand for?")
print("A. Central Processing Unit")
print("B. Computer Personal Unit")
print("C. Central Power Unit")
print("D. Control Processing Unit")

answer = input("Enter your answer (A/B/C/D): ").upper()

if answer == "A":
    print("Correct!")
    score += 1
else:
    print("Wrong! Correct answer is A.")

# Question 2
print("\n2. Which language is this program written in?")
print("A. Java")
print("B. Python")
print("C. C")
print("D. JavaScript")

answer = input("Enter your answer (A/B/C/D): ").upper()

if answer == "B":
    print("Correct!")
    score += 1
else:
    print("Wrong! Correct answer is B.")

# Question 3
print("\n3. Which symbol is used for comments in Python?")
print("A. //")
print("B. <!-- -->")
print("C. #")
print("D. **")

answer = input("Enter your answer (A/B/C/D): ").upper()

if answer == "C":
    print("Correct!")
    score += 1
else:
    print("Wrong! Correct answer is C.")

# Question 4
print("\n4. Which function is used to display output?")
print("A. display()")
print("B. print()")
print("C. output()")
print("D. show()")

answer = input("Enter your answer (A/B/C/D): ").upper()

if answer == "B":
    print("Correct!")
    score += 1
else:
    print("Wrong! Correct answer is B.")

# Question 5
print("\n5. Which keyword is used to create a loop?")
print("A. repeat")
print("B. while")
print("C. loop")
print("D. goto")

answer = input("Enter your answer (A/B/C/D): ").upper()

if answer == "B":
    print("Correct!")
    score += 1
else:
    print("Wrong! Correct answer is B.")

print("\n================================")
print("Quiz Finished!")
print("Your Score:", score, "/5")

if score == 5:
    print("Excellent! 🎉")
elif score >= 3:
    print("Good Job! 👍")
else:
    print("Keep Practicing! 💪")
