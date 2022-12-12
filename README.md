# Hw_8
This is a group assignment. One submission per group. Both group members should work on it and decide on the last answer.
Create a compression(hash) function that intakes a hash code (as uint_64) and outputs the bucket(index) in which the data will be stored.
Add some values to a hash table using the hash function you created. You may use chaining, linear probing, or quadratic probing to avoid collisions.
Demonstrates your hash table with a case without collusion, and a case with collusion. Each case must have at least 11 distinct inputs.
Note: for this assignment, we are putting hash code itself as the “data” to be stored in the hash table. If you are using linear probing or quadratic probing, an int vector is sufficient to serve as a hash table. However, for chaining, you will also need a vector of int singly linked lists.
