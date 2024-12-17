# Increment-of-an-array-of-digits
simple adding a unit to a number represented by an array of digits

def add_one(digits):
    number = int(''.join(map(str, digits)))
    
    number += 1
    
    return [int(digit) for digit in str(number)]

result = add_one([5, 6, 7, 8])
print(result)
