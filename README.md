# Algorithms-in-c

    Here i will be uploading all the basic and maybe adanvanced algorithms in future 
    
   1 Selection sort : 
   
   Algorithm for this is -
 a) create an array or ask the user for it(for practice we're just using a simple integer array,in c++ we can even sort character arrays)
 b) use the concept of double pointers to traverse the list(array)
 c) assume the 1st pointer is pointing to the smallest element
 d) if yes then good if no then swap them 
 e) keep on doing this while keeping one poiter stable at the index where we want to fill the smallest
    or next smallest element and use the other pointer to traverse the list
    
   2 Bubble Sort:
   
   Algorithm for this-
    a) A pass is one full iteration of comparing two adjacent elements of the array once
    b) We've to keep on doing this untill the array is sorted
    c) We'll compare two elements and swap them if arr[i]>arr[j] where i was the minindex earlier
        THIS IS THE EXAMPLE OF 1 PASS:  
            ( 5 1 4 2 8 ) –> ( 1 5 4 2 8 )
            ( 1 5 4 2 8 ) –>  ( 1 4 5 2 8 )
            ( 1 4 5 2 8 ) –>  ( 1 4 2 5 8 )
            ( 1 4 2 5 8 ) –> ( 1 4 2 5 8 )
    d) We do this with the help of nested for loops(or we can also say double pointers)
    e)One key point to know about this algorithm is that in 1st pass itself we get the last element(biggest element) on place
    f)This happens because we're iterating the array from the beginning if we do it from the end and manupulate our double pointer (or the for loop conditionals) we can find the
        first element (smallest element) 1st.
