# Quiz_Games_Project


# Simple Quiz Game in Python

score = 0

print("Welcome to the Quiz Game!")
print("--------------------------")

# Question 1
print("\n1. What is the capital of Pakistan?")
print("a) Lahore")
print("b) Islamabad")
print("c) Karachi")
answer = input("Enter your answer (a/b/c): ")

if answer.lower() == "b":
    print("Correct!")
    score += 1
else:
    print("Wrong! The correct answer is Islamabad.")

# Question 2
print("\n2. Which language is used for Python programming?")
print("a) Python")
print("b) Java")
print("c) C++")
answer = input("Enter your answer (a/b/c): ")

if answer.lower() == "a":
    print("Correct!")
    score += 1
else:
    print("Wrong! The correct answer is Python.")

# Question 3
print("\n3. How many days are there in a week?")
print("a) 5")
print("b) 6")
print("c) 7")
answer = input("Enter your answer (a/b/c): ")

if answer.lower() == "c":
    print("Correct!")
    score += 1
else:
    print("Wrong! The correct answer is 7.")

# Final Score
print("\nQuiz Finished!")
print("Your score:", score, "/ 3")

if score == 3:
    print("Excellent!")
elif score == 2:
    print("Good job!")
else:
    print("Keep practicing!")
