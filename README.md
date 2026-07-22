def pair_numbers(numbers):
    pairs = []

    for index in range(0, len(numbers) - 1, 2):
        pairs.append((numbers[index], numbers[index + 1]))

    return pairs


if __name__ == "__main__":
    values = [10, 20, 30, 40, 50, 60]

    print(f"Values: {values}")
    print(f"Pairs: {pair_numbers(values)}")
