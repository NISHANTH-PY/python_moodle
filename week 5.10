def reverse_without_affecting_special(s):
    # Convert string to list for in-place modification
    s_list = list(s)
    left, right = 0, len(s) - 1

    while left < right:
        if not s_list[left].isalpha():
            left += 1
        elif not s_list[right].isalpha():
            right -= 1
        else:
            s_list[left], s_list[right] = s_list[right], s_list[left]
            left += 1
            right -= 1

    return ''.join(s_list)

# Example usage
input_string = input()
result = reverse_without_affecting_special(input_string)
print( result)
