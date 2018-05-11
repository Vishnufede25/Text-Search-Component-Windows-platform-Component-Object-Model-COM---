# Text-Search-Component-Windows-platform-Component-Object-Model-COM
 A text search component that accepts a fully qualified file name and regular-expression text pattern. If the file matches the text pattern in one or more locations, it returns a list of line numbers where the matches occur. If no matches occur, it returns an empty list. 
 
A FileMgr component that finds the fully qualified names of all files residing in a directory tree rooted at a specified path and matching one or more of the filename patterns. It exposes these results by providing a get(...) method that retrieves each result from an internal thread-safe blocking queue, and returns the result with a success code of true. When its search has ended, the get(...) method returns a success code with value false. 

Powershell script is used to run the code
