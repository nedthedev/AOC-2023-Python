# [Day 3](https://adventofcode.com/2023/day/3) - Initial Plan
Another case where the most obvious solution is to iterate through, look for a number, look around it for a non period character, then step through the digits and add it to a sum. I think the cleanest option, for separation of tasks between functions and readability, is to create a parallel array with 