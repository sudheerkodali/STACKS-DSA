# STACKS-DSA
Stacks-java-script


| NO. | Questions                                                                                                                                                                  |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |   
|     |   Stacks-types                                                                                                                                                             |
|  1  | [what is stack](#)                                                                                                                                                         |
|  2  | [Using-stack-as-an-array](#)                                                                                                                                               |
|  3  | [Using-stack-as-a-linked-list](#)                                                                                                                                          |
|  4  | [Using-stack-as-a-linked-List-implementation](#)                                                                                                                           |

|  1  | [what is stack](#)  
# 1.1 what is stack
<p> Stack we called it has 'ADT' </p>
<P> ADT:  'Abstract Data Type </P>
<p> while implementing data types into 'Stack' we need to fallow this 4 points </p>
<p><li>  PUSH: Insert into stack
   <li>   POP: Pop from the stack
   <li>   TOP: Return TOP most element of the stack( top most means last element LIFO)
   <li>   SIZE: Return size of the stack </li></p>
   
  ![Image of Stack](./whatisStack/image1.png)


# 1.2 stack explanation
<p> For instance in Stack push[4] push[7] push[6] =>[4,7,6] </p>
<p> <li> Top () => 6 :Return TOP most element of the stack ( Top most means last element LIFO)</li>
    <li> Pop () => 6 :POP: Pop from the stack (Come out of the Stack)</li>
</p> 
<p> <li> Top () => 7 :Return TOP most element of the stack( top most means last element LIFO)</li>
    <li> Pop () => 7 :POP: Pop from the stack (Come out of the Stack) </p></li>
    <li> Top () => 4 :Returns Top most element is '4' </li></p>   

![Image of Stack](./whatisStack/image2.png)

# 1.3 stack : LIFO
<p> Stack Data types or elements comes as 'LIFO':LAST IN FIRST OUT' means LAST elemet comes out FIRST ,  as mentioned in the above diagram </p>

![Image of Stack](./whatisStack/image3.png)

|  2  | [Using-stack-as-an-array](#)   

# 2.1 stack as array
<p><li> what we are creating at the stack we are inserting at the end of the array 
<li> Similarly, when we are inserting at the end(top) and delection at end stack(pop) Top most element of an array we are inserted at the end of the array</li>
<p> Insertion at top = inserction at end of the Array </P>
<p> Delection at top = pop of operation of an Array </p>
<p> Top most element means last element of an array </p> 

![Image of stack as an array](./usingStackanArray/image1.png)

# 2.2 stack as array
<p> programming implementation on stack </p>
<ol>
    <li>let st = [];</li> 
   <br>
    <li> st.push(10);</li>
    <li> st.push(30);</li>
    <li> st.push(5); </li> 
   <br>
    <li> console.log('top element = ' + st[st.length - 1]);</li>
    <li> st.pop(); </li>
   <br>
    <li> console.log('top element = ' + st[st.length - 1]);</li>
    <li> st.pop(); </li>
   <br>
    <li> console.log('top element = ' + st[st.length - 1]);</li>
 </ol>
<p> out-put </p>
             : top element = 5  <br>
             : top element = 30 <br>
             : top element = 10 <br>
             
 ![Image of stack as an array](./usingStackanArray/image2.png)
 

|  3  | [Using-stack-as-a-linked-list](#)   

# 3.1 using as a linked list as a Stack
<p> Linked list Stack represents in big O(1) </p>
<li> O(1) <= push() <br>
<li> O(1) <= pop()  <br>
<li> O(1) <= Top()  <br>
</li> 
<p> Using Linked list in Stack to implent the elements <p>
   <li> HEAD: Null => Linked list as empty </li>
   <li> HEAD: 10 : Null => 10 push Linked list </li>
   <li> HEAD: 7 : 10 : Null => 7 push Linked list </li>
   <li> Head: 9 : 7 : 10 : Null => 9 push Linked list </li>
   
![using stack as a linked list](./StackasLinkedList/image1.png)

# 3.2 using as a linked list as a Stack
<p> Linked List as a stack using POP from end of the list </p>
<p> POP rom the list means comes out of the stack as LAST element </p> 
<li> last element is 9 means pop(9) => HEAD [9] : [7] : [10] => Null </li>
<li> last element is 7 means pop(7) =>  HEAD [] : [7] : [10] => Null </li>
<li> last element is 10 means pop(10) => HEAD [] : [] : [10] => Null </li>
<li> last element is   pop() => HEAD => Null </li>



![using stack as a linked list](./StackasLinkedList/image2.png)

| 4   |  [Using-stack-as-an-array](#)   

# 4.1 usingStackanArray
![Using-satckanarray](./usingStackanArray/image1.png)

# 4.2 usingSrackanArray
![Using-satckanarray](./usingStackanArray/image2.png)

