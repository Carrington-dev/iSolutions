def flatten(input, n):
    output = []
    if n == 0:
        return input
    
    for item in input:
        if isinstance(item, list):
            output.extend(flatten(item, n-1))
        else:
            output.append(item)

    return output


input = [1, 2, 3, [4, 5, 6], [7, 8, [9, 10, 11], 12], [13, 14, 15]] 
n = 1

result = flatten(input, n)
print(result)
