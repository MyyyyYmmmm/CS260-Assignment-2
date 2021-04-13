# CS260-Assignment-2

Assignment 2 (C++ Programming)  
Yoshiko Murakami  
CS260  
April 12, 2021  





	
## **Assignment 2 (Design) details:**  

1.	**Do not implement any code this week!**  

2.	Based on what we know about linked lists, stacks, and queues, design a queue data structure:  
      1.	What functions are we likely to need for a queue to function like the one discussed in class?  
      2.	What values will we need to know about the structure for our queue to function properly?  
3.	Based on what we know about linked lists, design a list data structure that allows us to add (insert) or remove (delete) values at a given location in the list (instead of the top of a stack or the front or back of a queue):  
      1.	What functions are we likely to need for a list to function like this?  
      2.	What values will we need to know about the structure for our list to function properly?  
4.	Commit changes to your design into your git repo frequently while designing (in an obvious assignment2 folder or repo),  
5.	Submit a link to your git repo to Moodle to remind us to grade it.  










## **Assignment 2 (C++ Programming)**  
Container usage is part and parcel of every person’s life. Containers are used to store numerous things, not limited to cereals. Another most prominent example is a book, whereby the pages are placed inside a cover. It would be inconvenient reading a book whose pages haven’t been covered; there is also binding that makes pages stick together. One of the main roles of containers is to organize the items (Alex, 2020). Correspondingly, a container class is also utilized in the C++ programming language to organize numerous instances of a different class. There are numerous kinds of container classes with their benefits and drawbacks, including varying restrictions. Even though C++ has in-build array functionality, it is important to consider container classes for arrays due to their added advantages. Std::array is one of the array container classes that can be utilized. Some of the benefits associated with an array container class include dynamic resizing and bounds-checking (Alex, 2020). Hence, these classes are safer to use than built-in arrays in C++.   

In the C++ programming language, container classes can be put into practice as a class, alongside member functions. The following operations are linked to these container classes; add, delete, and items examination. 



## **The Bag Class Abstraction**  
Regarding the problem at hand, the marbles bag is the container class. In this class, every object can hold an assortment of items, for example, numbers. The most notable essential facet associated with a C++ class container is that the configuration for starting every single object is known (Raj et al., 2018). This is all about the initial state of a marble bag in a nutshell. In the beginning, the marble bag will be unoccupied. Afterward, a person can enter the numbers into the marble bag, and the program will use a fixed assortment of operations for the bag's manipulation. Numbers insertion is the first simple operation, and it facilitates the entrance of a new number in the marble bag. The second operation is to query the marble bag to determine whether it contains a number. This operation entails two methods, whereby one method is used to determine whether a certain number is in the marble bag.

In contrast, the latter method identifies the copies of a given number available in the marble bag. Moreover, the third method involves getting rid of a number, and the fourth operation is to get rid of every single number in the bag. The last operation computes the total numbers in the bag and its size. At this juncture, it is essential to note that a single number is inserted into the bag more than once. Class definition comprises headings and private and public member functions (Richmond et al., 2018). Sketchpad an online tool was utilized to draw the below diagram:
![Drawing2](https://user-images.githubusercontent.com/59652655/114497086-2c17dc80-9bd6-11eb-8e9a-e3f7bdd3b1fc.png)  


## **References**  
- Alex (2020). 16.6 — Container classes.  
	https://www.learncpp.com/cpp-tutorial/container-classes/    
- Raj, A. G. S., Naik, V., Patel, J. M., & Halverson, R. (2018, January). How to teach" modern 
C++" to someone who already knows programming?. *In Proceedings of the 20th Australasian Computing Education Conference* (pp. 97-104).  
- Richmond, D., Althoff, A., & Kastner, R. (2018). Synthesizable higher-order functions for 
*C++. IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems, 37(11)*, 2835-2844.  


