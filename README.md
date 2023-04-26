# Selection-Sort  
Selection sort is a simple and efficient sorting algorithm that works by repeatedly selecting the smallest (or largest) element from the unsorted portion of the list and moving it to the sorted portion of the list.  
The algorithm repeatedly selects the smallest (or largest) element from the unsorted portion of the list and swaps it with the first element of the unsorted portion.  
This process is repeated for the remaining unsorted portion of the list until the entire list is sorted.  

#### Working of Selection Sort

1. Set the first element as minimum.  
![image](https://user-images.githubusercontent.com/91966613/234461609-531688f8-7ef2-4f7a-aa7e-2da1eabfc6a4.png)  

2.Compare minimum with the second element.  
If the second element is smaller than minimum, assign the second element as minimum.  
Compare minimum with the third element.  
Again, if the third element is smaller, then assign minimum to the third element otherwise do nothing.   
The process goes on until the last element.

![image](https://user-images.githubusercontent.com/91966613/234461754-380499c7-d9b2-4905-9513-36134f42b868.png)

3. After each iteration, minimum is placed in the front of the unsorted list.  
![image](https://user-images.githubusercontent.com/91966613/234461836-676d7eb2-0041-4e5e-9ab2-790284c366c7.png)

4.For each iteration, indexing starts from the first unsorted element.  
Step 1 to 3 are repeated until all the elements are placed at their correct positions.  

![image](https://user-images.githubusercontent.com/91966613/234462132-daf3228e-f999-4e9a-8c01-04523594893c.png)  
![image](https://user-images.githubusercontent.com/91966613/234462284-a4c7dd20-8ca7-43af-a580-8b7a466d6bee.png)  
![image](https://user-images.githubusercontent.com/91966613/234462379-cfb535d9-76af-4889-b561-03808d519f4d.png)  
![image](https://user-images.githubusercontent.com/91966613/234462436-515cd396-db39-4173-a99a-49bc812396fa.png)



