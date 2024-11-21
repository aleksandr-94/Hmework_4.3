# Hmework_4.3



def create_new_list(original_list):
    if len(original_list) < 3:
        return original_list  # Если меньше, возвращаем сам список
    return [original_list[0], original_list[2], original_list[-2]]

assert create_new_list([1, 2, 3, 4, 5, 6, 7, 9]) == [1, 3, 7], 'Test 1'
assert create_new_list([1, 1, 2, 1]) == [1, 2, 1], 'Test 2'
assert create_new_list([6, 7, 3]) == [6, 3, 7], 'Test 3'
assert create_new_list([1, 2]) == [1, 2], 'Test 4'
assert create_new_list([]) == [], 'Test 5'

print("Все тесты пройдены!")
