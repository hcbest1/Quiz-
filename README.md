# Quiz-

def filter_even_numbers(numbers):
    """주어진 리스트에서 짝수만을 필터링하여 출력하는 함수"""
    result = [num for num in numbers if num % 2 == 0]
    print("Even numbers:", result)

# 함수 테스트
numbers = [111, 26, 37, 48]
filter_even_numbers(numbers)



def filter_numbers(numbers):
    """주어진 리스트에서 짝수만을 필터링하여 출력하는 함수"""
    result = list(filter(lambda x: x % 2 == 0, numbers))
    print("numbers:", result)

# 함수 테스트
numbers = [111, 26, 37, 48]
filter_numbers(numbers)
