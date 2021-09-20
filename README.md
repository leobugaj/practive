print("Welcome to Leo's Quiz! ")

playing = input("Do you want to play a Game? ").lower()

if playing != "yes":
    quit("Better Luck Next Time")

print("Ok let's play: ")
score = 0
answer = input("What state is El Reno in? ").lower()
if answer == "oklahoma":
    print("Correct! ")
    score += 1
else:
    print("Incorrect! ")
    score -= 1

answer = input("What year was MMV established? ")
if answer == "2012":
    print("Correct! ")
    score += 1
else:
    print("Incorrect! ")
answer = input("How many states are in United States? ")
if answer == "50":
    print("Correct! ")
    score += 1
else:
    print("Incorrect! ")
answer = input("What does mmv stand for? ").lower()
if answer == "mixmaster vapes":
    print("Correct! ")
    score += 1
else:
    print("Incorrect! ")

print("You got " + str(score) + " questions correct! ")
print("You got " + str((score / 4) * 100) + " % questions correct. ")

print("Thanks for playing Leo's Quiz ")
