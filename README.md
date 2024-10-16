# Simple Social Media Feed System

The provided code is a C++ program that simulates a simple social media feed system. It includes two main classes, `Post` and `Feed`, and several utility functions.

## Classes

### Post Class

The `Post` class represents individual posts, each with a unique ID, timestamp, and text content. The class also includes methods to display the post, get and set the text, and update the timestamp. It has a static member `total_posts` to keep track of the total number of posts created.

### Feed Class

The `Feed` class manages a linked list of `Post` objects. It includes methods to:

- Insert a post at the start
- Display posts in both latest and oldest order
- Delete a post by ID
- Search for posts containing a specific substring
- Edit a post's text and timestamp

The `edit_post` method also reorders the posts based on their timestamps using a bubble sort algorithm.

## Utility Functions

### substr_present Function

The `substr_present` function checks if a substring exists within a given string. It iterates through the main string and compares segments of it with the substring. If a match is found, it returns true; otherwise, it returns false.

### swap Functions

The `swap` functions are overloaded to handle both `string` and `int` types. They swap the values of two variables using a temporary variable.

## Main Function

The `main` function demonstrates the usage of the `Feed` class. It creates a `Feed` object and inserts several posts, some with user-provided text. It then:

- Displays the posts in oldest order
- Searches for posts containing specific substrings
- Edits a post
- Deletes posts based on user input
- Finally, displays the posts in the latest order
