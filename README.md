# stackandqueue-output


** TESTING STACK OPERATIONS **
initial size of s1 is 0
initial size of s2 is 0

-> Pushing 4 values onto stack, s1 (of capacity 50) 
size of s1 (after pushing 4 values) is 4

-> Copying s1 into s3 (using copy constructor) 
size of s3 (same size as s1) is 4

-> Popping all values from s1 
popped 3 from s1
popped 2 from s1
popped 1 from s1
popped 0 from s1
size of s1 (after all values popped) is 0

-> Popping all values from s3 (same values as s1) 
popped 3 from s3
popped 2 from s3
popped 1 from s3
popped 0 from s3
size of s3 (after all values poppped) is 0

-> Pushing 5 values onto stack s2 (of capacity 3) 
size of s2 (after pushing 4 values) is 5

-> Copying s2 into s1 (using assignment operator) 
size of s1 (same size as s2) is 5

-> Popping all values from s2 
popped 4 from s2
popped 3 from s2
popped 2 from s2
popped 1 from s2
popped 0 from s2
size of s2 (after all values popped) is 0

-> Popping all values from s1 (same values as s2) 
popped 4 from s1
popped 3 from s1
popped 2 from s1
popped 1 from s1
popped 0 from s1
size of s1 (after all values popped) is 0


** TESTING QUEUE OPERATIONS **
initial size of q1 is 0
initial size of q2 is 0

-> Enqueuing 5 values to queue, q1
size of q1 (after pushing 5 values) is 5

-> Copying q1 into q3 (using copy constructor)
size of q3 (same size as q1) is 5

-> Emptying all values from q1
dequeued 3 from q1
dequeued 4 from q1
dequeued 5 from q1
dequeued 6 from q1
dequeued 7 from q1
size of q1 (after all values dequeued) is 0

-> Copying q3 into q2 (using assignment operator)
size of q2 (same size as q3) is 5

-> Emptying all values from q3
dequeued 3 from q3
dequeued 4 from q3
dequeued 5 from q3
dequeued 6 from q3
dequeued 7 from q3
size of q3 (after all values dequeued) is 0

-> Emptying all values from q2
dequeued 3 from q2
dequeued 4 from q2
dequeued 5 from q2
dequeued 6 from q2
dequeued 7 from q2
size of q2 (after all values dequeued) is 0
