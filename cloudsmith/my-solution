def flatten(arr, n):
    if n == 0:
        return arr
    output = list()
    unused_input = []
    indexes = set()
    # do work here
    count = 0
    while count < n:
        unused_input = []
        for i in range(len(arr)):
            if isinstance(arr[i], int):
                output.append(arr[i])
            else:
                unused_input = unused_input + arr[i]
        arr = unused_input
        count += 1

    return output + unused_input


input = [1, 2, 3, [4, 5, 6], 16, [7, 8, [9, 10, 11], 12], 17, [13, 14, 15]] 
output = [1, 2, 3, 4, 5, 6, 16, 7, 8, 9, 10, 11, 12, 17, 13, 14, 15] 
n = 3

result = flatten(input, n)
print(result)
