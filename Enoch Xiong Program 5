def main():
    budget = 0.0
    difference = 0.0
    spent = 1.0
    total = 0.0

    budget = float(input('Enter your budget: '))

    while spent != 0:
        spent = float(input("Enter an expense (0 to finish): "))
        total += spent

    difference = budget - total

    if difference >= 0:
        print("You are under budget by $", format(difference, ".2f"))
    else:
        print("You are over budget by $", format(abs(difference), ".2f"))

if __name__ == '__main__':
    main()
