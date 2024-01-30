# Pagination Project

This README provides an overview of the tasks and the associated files for the Pagination project in the alx-backend repository.

## Tasks

### Task 0: Simple Helper Function

- File Name: `0-simple_helper_function.py`
- Description: Write a function named `index_range` that takes two integer arguments `page` and `page_size`. The function should return a tuple of size two containing a start index and an end index corresponding to the range of indexes to return in a list for those particular pagination parameters.

### Task 1: Simple Pagination

- File Name: `1-simple_pagination.py`
- Description: Implement a method named `get_page` that takes two integer arguments `page` with a default value of 1 and `page_size` with a default value of 10. Use this method to paginate a dataset from a CSV file and return the appropriate page of the dataset.

### Task 2: Hypermedia Pagination

- File Name: `2-hypermedia_pagination.py`
- Description: Replicate code from Task 1 and implement a `get_hyper` method that returns a dictionary containing information about the current page, page size, data, next page, previous page, and total pages for hypermedia pagination.

### Task 3: Deletion-Resilient Hypermedia Pagination

- File Name: `3-hypermedia_del_pagination.py`
- Description: Implement a `get_hyper_index` method that provides deletion-resilient hypermedia pagination. It should return a dictionary with information about the current index, next index, page size, and data, even if rows are removed from the dataset.
