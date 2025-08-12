
#  Pointers in C++

##  Aim  
To study pointers and understand their usage in C++.

---

##  Tools  
- **IDE**: Visual Studio Code  
- **Compiler**: Any standard C++ compiler (e.g., g++, MSVC)  

---

##  Theory  
Pointers in C++ are variables that store **memory addresses** as their values.  
They enable **direct memory manipulation** and are essential for:  
- Dynamic memory allocation  
- Data structure implementation  
- Passing arguments by address  

### **Basic Concepts**
- `int* ptr;` → Declares a pointer to an integer.  
- `ptr = &x;` → Stores the address of variable `x` in `ptr`.  
- `*ptr` → Dereference operator; accesses the value stored at `ptr`.

**Pointer Size:**  
- **64-bit system** → 8 bytes  
- **32-bit system** → 4 bytes  
> Pointer size depends on **CPU architecture**, not the data type.

---

##  Uses of Pointers  
1. **Dynamic Memory Allocation** – Allocate memory at runtime (`new` and `delete`).  
2. **Data Structure Implementation** – Used in linked lists, trees, graphs, etc.  
3. **Pass Arguments by Pointer** – Modify original variables directly via their address.  

---

##  Algorithms  

### **1️ Incrementing Data Types Using Pointers**
1. Declare variables: `int a`, `float f`, `double d`, `char c`, `bool b`.  
2. Declare corresponding pointers and store their addresses.  
3. For each pointer:  
   - Print the initial address.  
   - Increment the pointer (`pointer++`).  
   - Print the new address.  

---

### **2️ Reversing an Array Using Pointers**
1. Initialize array `{10, 20, 30, 40, 50}`.  
2. Create a pointer to the last element (`arr + 4`).  
3. Loop from `i = 4` to `0`:  
   - Print value at pointer.  
   - Decrement pointer.  

---

### **3️ Finding Difference of Array Elements Using Pointers**
1. Initialize `A = {10, 20, 30, 40, 50}`.  
2. Set:  
   - `ap1` → 3rd element (`A[2]`).  
   - `ap2` → 5th element (`A[4]`).  
3. Calculate `diff = *ap2 - *ap1`.  
4. Print the result.  

---

### **4️ Reading & Printing a String Using a Pointer**
1. Declare `char str[20]`.  
2. Take input string from user.  
3. Initialize pointer `ptr` to `str`.  
4. While `*ptr != '\0'`:  
   - Print `*ptr`.  
   - Increment pointer.  

---

##  Conclusion  
We explored pointers in C++ and learned:  
- How they store memory addresses.  
- Their role in dynamic memory allocation.  
- How they help in efficient data manipulation and structure implementation.  

