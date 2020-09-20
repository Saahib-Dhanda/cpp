# Bug 1

1. **The incorrect original code or code snippit that you wrote:**

``` cpp
//code with bugs or code snippet with bug goes here

//sample code

// Online C++ compiler to run C++ online.
// Write C++ code in this online editor and run it.

#include <iostream> 
using namespace std; 


int main () { 
    
int assingment_speed {20}; 
int assignment_time {10}; 


cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 




}
return 0; 

```

2. **What bug does the original code have?**
The Bug of the original code is that the strcuture of the C++ code is out of order. The "return 0;" is outside of the curley bracket. 

  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
When I first started programming on codelite  I thought that "return 0;" would be at the end of the code after the bracket since it tells our operating system that are code is running correctly.  
4. **How to correct the bug?**
To correct the bug you must insert the "return 0; at the end of the code within the curley brackets not outside of it. 
5. **The corresponding bug-free code or code snippet is:**

```
#include <iostream> 
using namespace std; 


int main () { 
    
int assingment_speed {20}; 
int assignment_time {10}; 


cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 



return 0; 
}

```

6. **What is the take-away message from this bug?**
The take-away message from this bug is to always have return0; at the end of your code within the curley brackets so your operating system will be able to understand the code you have written and run it. 
---

# Bug 2

1. **The incorrect original code or code snippit that you wrote:**

```
#include <iostream> 



int main () { 
    
int assingment_speed {20}; 
int assignment_time {10}; 


cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 



return 0; 
}

```

2. **What bug does the original code have?**
The Bug in the code is that there is something that is not declared in the current scope. The operating system does not know and therefore cannot preform the cout/cin operations.
  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**

At first when I was coding using cout/cin  I was using the std practice for example  std::cout << "Hello Testing!" << std:: endl; Then I realized that in some cases you can use the cout/cin functionalities without including the standard name space in each code. So I wrote the the code and tried to compile but had received and error.  

4. **How to correct the bug?**
To correct the bug I added the "The Using namepsace directive" and in this case was the  "using namespace std;" So the compiler would know which one to use based on the Using namespace directive.  

5. **The corresponding bug-free code or code snippet is:**

```
#include <iostream> 
using namespace std; 


int main () { 
    
int assingment_speed {20}; 
int assignment_time {10}; 


cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 



return 0; 
}


```

6. **What is the take-away message from this bug?**
The Take-away message from this bug is If we are not specifically telling the compiler using cin/cout with the standard name space we must add the namespace directive and in this case was using namespace std;     
---

# Bug 3

1. **The incorrect original code or code snippit that you wrote:**

```
#include <iostream> 
using namespace std; 


int main () { 
    
assingment_speed {20}; 
assignment_time {10}; 

cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 




return 0; 
}

```

2. **What bug does the original code have?**
The bug that the orginal code has is that the variables are not decalred. 

  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
I wrote out the variables and stored the values into them and tried to run the code. I received an error where the compiler informed me that the variables have not been decalred in the scope. 

4. **How to correct the bug?**
To correct the code I had to declare the variable and in this case I used the Int to use an integer.  
5. **The corresponding bug-free code or code snippet is:**

```
#include <iostream> 
using namespace std; 


int main () { 
    
int assingment_speed {20}; 
int assignment_time {10}; 

cout << assingment_speed * assignment_time << endl; 
cout << "The product of distance is " << assingment_speed * assignment_time << endl; 




return 0; 
}


```

6. **What is the take-away message from this bug?**
The take-away message from this bug is to always remember to declare the variable otherwise the compiler wont understand what to do with the variable. 
