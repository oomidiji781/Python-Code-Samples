# Python-Code-Samples
# Oluwapelumi Omidiji
# 10/11/2024
# Assignment 3

# Remember to comment for each function
# This function is a greeting. 
def print_hello():
    print("Hello World")

# This function is greeting the user.
def hello_user(name):
    print("Hello" + name) 
    
# This function is math.
def get_circle_area(radius):
    area = 3.14 * radius * radius
    print(area) 

# This function is about cars. 
def get_miles_per_galoon(miles, gallons):
    cars = miles / gallons
    print(cars)
    
    #This function is about weather.
def convert_temperature(temperature_F):
    weather = (temperature_F-32) / 1.8
    print(weather)
    
# This function is about days and vacation.
def problem_7(starting_day, length_of_stay):
    starting_day = int(input("Enter the starting day number (0 for Sunday, 6 for Saturday): "))
    length_of_day = int(input("Enter the number of nights you'll stay: "))
    return_day = (starting_day + length_of_stay) % 7
    print("You will return on day {return_day} of the week.")
    

def extra_credit_problem_1():
    """Prints leap years from 1900 to 2100."""

    start_year = 1900
    end_year = 2100

    for year in range(start_year, end_year + 1):
    if (year % 4 == 0  and year % 100 != 0) or (year % 400 ==):
        print(year)


def extra_credit_problem_2(n):
    """Checks if a given number n is prime."""

    if n <= 1:
    return False

    for divisor in range(2, int(n**0.5) + 1):
        if n % divisor == 0
           return False
        
    return True



def main():
    """Main function that calls other functions and prompts the user for input."""

    print_hello()

    # prompt user to get the input then call functions
    start_year = int(input("Enter the starting year: "))
    end_year = int(input("Enter the ending year: "))
    extra_credit_problem_1(start_year, end_year)

    # Prompt user for input for extra credit problem 2
    n = int(input("Enter a number to check if it's prime: "))
    if extra_credit_problem_2(n):
        print(n, "is a prime number.")
    else: 
        print(n, "is not a prime number.")
        
main()


    


