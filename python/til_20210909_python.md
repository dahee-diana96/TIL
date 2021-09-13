# Today I Learned... 20210909

# 함수와 클래스

# 1. 함수(Function)
## Structure of a function
    ```
    def func_nm (parameter) :
    code
    code
    return return_variable
    ```
    * Example 1.
    ```
    def person(name, age):
        print(f'my name is {name} and I am {age}-years-old.')
    ```
    * Example 2.
    ```
    def print_sum(x):
        empty_list=[]
	for i in range(x):
	    input_val = int(input('Enter a number: '))
	    empty_list.append(input_val)
	print(sum(empty_list))
    ```
    ```
    print_sum(5)
    ```
    * Example 3. (Creating sum() function without using 'sum()')
    ```
    test_list = [1, 2, 3, 4, 5]
    def sum_sum(test_list):
        total = 0
	for i in range(len(test_list)):
	    total += test_list[i]
	return total

    sum_sum(test_list)
    ```
    ![example3_result]('/d/SSAC 캠퍼스/screenshot_01.JPG')

    * Example 4. (Creating max() function without using 'max()')
    ```
    def max_max(test_list):
        max_value = 0
	for i in range(len(test_list)):
	    if max_value < test_list[i]:
	        max_value = test_list[i]
	    else:
	        max_value = max_value
	return max_value
    max_max(test_list)
    ```

