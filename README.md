# heap-stack-diagram-epam-task

1. String ref name created in stack , String obj "Kevin" created in heap.
2. List<String> ref list created in stack , ArrayList obj created in heap.
3. int times = 10 created in stack
4. println() func call
5. fill(Collection<String> collection, String str, int times) call, String ref str created in stack , ref list passed by value as collection argument , String obj "KevinKevin" created in heap , times passed by value.
6. String ref shrunk created in stack , shrink(String str) called , ref str passed by value.
7. int newLength = 5 created in stack.
8. char[] ref char created in stack , char[] {0, 0, 0, 0, 0} created in heap.
9. char = {K, v, n, e, i}. 
10. String "Kvnei" created in heap, assigned to ref shrunk
11. times = 14.
12. in for loop, dividing times by 2, times = 7
13. creating 3 new objects in heap, assigning their references to ArrayList obj
14. returning times = 7
15. printing 17
