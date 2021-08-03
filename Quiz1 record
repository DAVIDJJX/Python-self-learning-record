Quiz1 record
```python=
def func_sum_all(nums) -> float:
    """
    A function that returns sum of all elements in nums list
    """
    res = 0
    res=sum(nums)
    return res

def func_product_all(nums) -> float:
    """
    A function that returns product of all elements in nums list
    """
    res = 1
    for value in nums:
        res *=value
    return res

def func_sum_all_even(nums) -> float:
    """
    A function that returns sum of all even elements in nums list
    """
    res = 0
    for value in nums:
        if value % 2 == 0:
            res += value
    return res

def func_sum_all_odd(nums) -> float:
    """
    A function that returns sum of all odd elements in nums list
    """
    res = 0
    for value in nums:
        if value % 2 == 1:
            res += value
    return res
def main() -> float:
    nums = list()
    result = 0
    cnt = 1

    # Take in numbers
    while True:
        entered = input(f"Enter the {cnt} number, or enter f when you are finished: ")
        cnt += 1

        if entered == 'f' or entered == '':
            break
        else:
            try:
                n = float(entered)
                nums.append(n)
            except ValueError:
                print("The input is not a valid float") 

    # List all nums
    print(nums)

    # Take in operations
    entered = input('Enter operation +, *, 1, 2: ')
    if entered == '+':   # A. Calculate sum of nums
        result = func_sum_all(nums)
    elif entered == '*': # B. Calculate product of nums
        result = func_product_all(nums)
    elif entered == '1': # C. Calculate sum of odd nums
        result = func_sum_all_odd(nums)
    elif entered == '2': # D. Calculate sum of even nums
        result = func_sum_all_even(nums)
    else:
        print("Not a valid operation")

    return result

if __name__ == "__main__":
    result = main()
    print('Result is ', result)
   ```
