# Quiz-

import matplotlib.pyplot as plt

def plot_even_numbers(numbers):
    """주어진 리스트에서 짝수만을 플로팅하고 결과를 출력하는 함수"""
    even_numbers = [num for num in numbers if num % 2 == 0]
    plt.plot(even_numbers, 'bo')
    plt.xlabel('Index')
    plt.ylabel('Even Numbers')
    plt.title('Plot of Even Numbers')
    plt.grid(True)
    plt.show()

# 함수 테스트
numbers = [ 111, 26, 37, 48 ]
plot_even_numbers(numbers)
