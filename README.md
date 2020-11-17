# nested_list_indexing
Python functions that index nested lists / extract from nested lists using a list of indices

## nested_list_search
Given a nested list and a string, the function will return the first instance of the string occurring in the nested list.

## nested_list_rough_search
Given a nested list and a string, the function will return all instances of strings within the nested list that contain the desired string, as well as a list of these strings. E.g. searching 'hi' within the list ['hi', 'hello', 'hiya', 'thing'] would return the list ['hi', 'hiya', 'thing'] as well as the indices for all these within the original nested list.

## index_using_list
Using a list of numbers that refer to the index of a particular string within a nested list, this fuction will return the string at this location within the list.
