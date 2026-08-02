# ml-hw-current_season-current_year-python
def user_input():
    """Read N numbers and find the position of X."""

    N = int(input("Enter a positive integer N:\n"))

    numbers = []

    for i in range(N):
        number = int(input(f"Enter number {i + 1}:\n"))
        numbers.append(number)

    X = int(input("Enter integer X:\n"))

    if X in numbers:
        print(numbers.index(X) + 1)
    else:
        print(-1)


# Call the function
user_input()
