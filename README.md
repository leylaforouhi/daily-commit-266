
def calculate_running_totals(numbers):
    totals = []
    current = 0

    for number in numbers:
        current += number
        totals.append(current)

    return totals


if __name__ == "__main__":
    values = [4, 7, -2, 5, 3]

    print("Values:", values)
    print("Running totals:", calculate_running_totals(values))
