# Backend Engineer Assignment - JAVA


## Problem Statement
Build a caching library to store values in memory , just like any in-memory store like caffeine ,Guava. The library should support following operations- 

1. Get any key value
2. Add a new key value pair 
3. Delete any key .
4. Fetch the current cache size.
4. Support for different eviction policies like First In First Out, Last In First Out , Least Recently Used , Least Frequently Used.To be used when the cache size is full . 
5. Support for having Time To Live for each key , post expiry of the time the keys should automatically be evicted from the cache.
6. Exception handling wherever needed.
7. The library should be configurable in terms of the size of the cache, TTL value and the eviction strategy to be used.

## Good to Have:
1. Support for additional strategies like Most Recently Used, Random Replacement.
2. Adding unit test cases covering the basic test cases.
3. Support for time based eviction for TTL such as - 
    1. Expire after access - the key is expired after TTL is passed since the last read or write occurs on the key .
    2. Expire after write  - the key expired after TTL is passed since the last write operation on the key .

## You will be evaluated based on:

1. Correct and functional code.
2. Code should be modular and readable. Clean and professional level code.
3. Code should be easily extensible and scalable.
4. Use of OOPS design patterns wherever relevant.
5. Code should be optimized in terms of space and time complexity.


## To complete your assignment, please fork this repo and commit your work to your fork. When you are ready for us to look at it, give us access to your fork so we can review and run it. Only commits before the due date would be considered.
