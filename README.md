

### `#add_element_to_end_of_array`

This method takes in two arguments, an array and the element we want to add to it. Use the `<<` (shovel) method or the `#push` method to add that element to the end of the new array.

### `#add_element_to_start_of_array`

This method takes in two arguments, an array and the element we want to add to it. Use the `#unshift` method to add that element to the start of that array.

### `#remove_element_from_end_of_array`

This method takes in one argument, the array on which we want to operate. Use the `#pop` method to remove the last item from the array.

### `#remove_element_from_start_of_array`

This method takes in one argument, the array on which we want to operate. Use the `#shift` method to remove the first item from the array.

### `#retrieve_element_from_index`

This method takes in two arguments, an array and the index number whose element we want to retrieve. Use the `[]`, bracket method, to return the element stored at that index number of the given array.

### `#retrieve_first_element_from_array`

This method takes in one argument, the array from which we want to retrieve an element. Use `[]` notation to return the value stored at the first index of the array. Remember that arrays are zero-indexed. This means that the first index number is `0` and it counts up from there. So, the first element of an array is stored at index `0`.

### `#retrieve_last_element_from_array`

This method takes in one argument, the array from which we want to retrieve an element. There are a number of ways to do this, but we recommend using the `[]` method with the following hint:

The last element of an array is considered to be stored at an index of `-1`.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/array-CRUD-lab' title='Array Lab: Create, Retrieve, Update, Delete'>Array Lab: Create, Retrieve, Update, Delete</a> on Learn.co and start learning to code for free.</p>
def create_an_empty_array
  []
end 