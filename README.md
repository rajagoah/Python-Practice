# Python-Practice
A collection of codes in Python

the following are the functinos written:
1. Printing inline
2. Developing triangle using python
3. email validation (with and without filter)
4. leap year function
5. Identifying runner up (or the second highest number in a list)

NOTES:
1. split() --> this function will allow to split a string in to it's individual elements based on a particular separator.
    syntax is: str.split(SEPARATOR, MAXSPLIT)
    SEPARATOR --> is the delimiter
    MAXSPLIT --> is the number of constituent parts we wish to split. default is unlimited. this argument is optional
 
 2. print(TEXT TO PRINT, end = '') --> The second argument allows us to print texts inline.
  
 3. map() --> This function allows applying functions to a list or other iterable.
     syntax is: map(FUNCTION, LIST)
     FUNCTION --> is any function like split() or a user defined function
     LIST --> is any iterable [1,2,3] or ('aakarsh','rajagopalan')
     
 4. sort() --> This function is used to sort the integer elements within a list
     syntax is: list.sort(reverse = True) 
     'reverse = True' --> allows us to get a list sorted in descending order.
   
 5. len() --> This function outputs the lenght of the list
     syntax is: len(list)
     
 6. max() or min() --> This function outputs the max value from a list of integers. Correspondingly, the min() outputs the min value from a list of integers.
     syntax is: max(list) or min(list)
     
 7. Removing duplicates from a list -->
    a. Declare an empty list.
    b. After initialising a loop, compare the values within the original list with the newly declared list.
    c. If the value is not present in the new list, then append in the new list. Else move to next element in the original list.
    
    example:
    duplicate_elements_list = [1,2,3,4,3,4,5]
    non_duplicate_list = []
    
    for i in duplicate_elements_list:
        if i not in non_duplicate_list:
            non_duplicate_list.append(i)
    
    print(non_duplicate_list)
    
  
  
