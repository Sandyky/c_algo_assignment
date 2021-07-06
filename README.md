# c_algo_assignment
# To run do the following steps:
  1. intall the gcc compiler
  2. install the code blocks ide
  3. clone the repository
  4. Start code blocks then select open the existing project option and browse the directory and select the algo.cbp
 
 # Algorithm 
 This approach uses hash table datastructure to solve the problem
 
 Hash Table is a datastructure which uses the hash function for indexing and store the data as {key:value} pair.
 
 The hash function calculate the hash for indexing.
 
 There is a possibility that for two different values the hash code will be same, this will leads the problem of collision.
 To solve this there are many approaches but these two mostly used:
 
  1.Use linked list to stroe the values
  
      Linked list uses extra memory to stroe the values and traversing linked list is relatively slow. 
      
  2.Use linear probing
  
      Linear probing is simple and fast.If try to insert the element but that there already element exist then move to next slot.If next slot is full too then move along again,         until find an empty one, wrapping arround to the beginning if hit the end of the array.

 The problem is to find the frequencies of each element of the Array of string
 The complexity of this approach is O(n)
 
 Start.
 
 Step 1. Create a container data structure hash table in c language which has key:value pair as element: frequency
 
 Step 2. Read the elements of Array
 
 Step 3. if element not found in the hash table store the element as {element:frequency} and frequency = 1
 
 Step 4. if element found in the hash table then update the frequency as frquency=frequency+1
 
 Step 5. Print the elements and its frequency
 
 End.
 
