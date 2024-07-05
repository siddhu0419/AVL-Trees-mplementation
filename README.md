# AVL_Trees_implementation
An efficient data structure for storing data in a sorted manner and retrieving them.


AVL Tree is a **self-balancing** binary search tree which guarantees O(logN) time complexity for insertion, deletion, and look-up operations. 

This version is implemented in C++ language, and allows multiple elements with same values. It means the tree can be used as **multiset**.

#### How to use it:

The tree can store any type of data which has **greater than** (>) operator. Build-in types such as `int`, `long long`, and `std::string` are well-tested, however user-defined structures, even has > operator, may cause some exceptions.

#### How to compile and run the program:

For competitive programmers, **onefile.cpp** contains all functions in one. 

    g++ kod.cpp AVLTree.cpp AVLTreeNode.cpp -o kod -std=c++11
    ./kod

or

    g++ onefile.cpp -o kod -std=c++11
    ./kod

#### Performance Test: std::multiset against AVL Tree

It is well known that Red Black Trees (**RB Trees**) serve as the foundation for std::multiset in the standard template library (STL), and that insertion, deletion, and look-up are guaranteed to occur in O(logN) time for both AVL and RB trees. AVL Trees offer faster lookup, but because they are more strictly balanced, they require more rotations during insertion and deletion. Therefore, for **look-up** demanding activities, you are strongly encouraged to use AVL Trees; otherwise, RB Trees (also known as std::multiset) are more convenient. 

### Contact Details


Name  :   siddhivinayaka kanchumarthi   


Email : 20ee02006@iitbbs.ac.in
