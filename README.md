# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 02/21/2024
# Description: Project 7a

# Define a function named square_list that takes a list of numbers as a parameter.
def square_list(nums):
    # Iterate through the elements of the list using a loop.
    for i in range(len(nums)):
        # Replace each element with its square.
        nums[i] = nums[i] ** 2

# Example usage:
if __name__ == "__main__":
    # Create a list of numbers.
    nums = [7, -3, 12, 9]

    # Call the square_list function to mutate the list by squaring its elements.
    square_list(nums)

    # Print the modified list, which now contains the squares of the original values.
    print(nums)
