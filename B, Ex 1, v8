import math
def calculate_equation():
    try:
        description = input("input value x: ")
        x = float(description)
        e = math.e

        y = (e**(-2 * x)) * (((x**2) + math.sqrt(x + 5)) / (2 * x - (math.sqrt(abs((e**x) - 2 * math.log(x))))))
        return f"answer is:  {round(y, 5)}"

    except ValueError:
        return ""
print(calculate_equation())
