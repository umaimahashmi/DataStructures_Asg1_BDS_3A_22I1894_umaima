The provided code is a C++ program that simulates a simple social media feed system. It includes two main classes, Post and Feed, and several utility functions. The Post class represents individual posts, each with a unique ID, timestamp, and text content. The Feed class manages a linked list of Post objects, providing functionalities to insert, display, search, edit, and delete posts.

The substr_present function checks if a substring exists within a given string. It iterates through the main string and compares segments of it with the substring. If a match is found, it returns true; otherwise, it returns false.

The swap functions are overloaded to handle both string and int types. They swap the values of two variables using a temporary variable.

The Post class has a static member total_posts to keep track of the total number of posts created. Each Post object has a unique ID, a timestamp generated at the time of creation, and a text content. The class also includes methods to display the post, get and set the text, and update the timestamp.

The Feed class manages a linked list of Post objects. It includes methods to insert a post at the start, display posts in both latest and oldest order, delete a post by ID, search for posts containing a specific substring, and edit a post's text and timestamp. The edit_post method also reorders the posts based on their timestamps using a bubble sort algorithm.

The main function demonstrates the usage of the Feed class. It creates a Feed object and inserts several posts, some with user-provided text. It then displays the posts in oldest order, searches for posts containing specific substrings, edits a post, and deletes posts based on user input. Finally, it displays the posts in the latest order.
