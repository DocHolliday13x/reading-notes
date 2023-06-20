# Class 30 Reading: Hash Tables

## Resources

- [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- [What is a Hash Table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
- [Basics of a Hash Table](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- [Hash Table Wiki](https://en.wikipedia.org/wiki/Hash_table)

## Teaching Ideas

- Use an analogy
- Explain a detail in depth
- Use WHY, WHAT, HOW structure
- Tutorial / walk through an example
- Write a quiz
- Create a vocabulary/definition list
- Write a cheat sheet
- Create a diagram / visualization / cartoon of a topic
- Anthropomorphize the concepts, and write a conversation between them
- Build a map of the information
- Construct a fill-in-the-blank worksheet for the topic

## **Hash Table Tutorial**

### *Hash Tables in JavaScript*

JavaScript has a built in hash table implementation called `Map`. It is similar to a hash table, but there are some important differences. For example, the keys in a `Map` can be any data type, whereas in a hash table, they are usually strings. Also, `Map` is an iterable and hash tables are not.

### *What is a Hash Table?*

A hash table is a data structure that uses key value pairs to store data. They are like arrays, but the keys are not ordered. Unlike arrays, hash tables are fast for all of the following operations: finding values, adding new values, and removing values.

### *Hashing*

To implement a hash table, we'll be using an array. In order to look up values by key, we need a way to convert keys into valid array indices. A function that performs this task is called a hash function.

### *Hash Functions*

A hash function takes in a key and returns an index. The goal of a hash function is to minimize the number of collisions (more on this later). A hash function needs to be fast (i.e. constant time), distribute keys uniformly, and be deterministic (same input yields same output).

### *Dealing with Collisions*

Even with a large array and a great hash function, collisions are inevitable. There are many strategies for dealing with collisions, but we'll focus on two: separate chaining and linear probing.

#### *Separate Chaining*

With separate chaining, at each index in our array we store values using a more sophisticated data structure (e.g. an array or a linked list). This allows us to store multiple key-value pairs at the same index.

#### *Linear Probing*

With linear probing, when we find a collision, we search through the array to find the next empty slot. Unlike with separate chaining, this allows us to store a single key-value at each index.

### *Big O*

- Insert: O(1)
- Deletion: O(1)
- Access: O(1)

The Big O of hash tables is constant time! This is true even in the worst case scenario when we have collisions. We can achieve constant time because we don't have to iterate through anything to find the value we're looking for. We can just go straight to it.

### *Vocabulary*

| Term                            | Definition
| ------------------------------- | ---------
| Hash Table                      | A data structure that uses key value pairs to store data.
| Hashing                         | The process of converting a key into an index.
| Hash Function                   | A function that takes in a key and returns an index.
| Collisions                      | When two keys hash to the same index.
| Separate Chaining               | A strategy for dealing with collisions where we store multiple key-value pairs at the same index.
| Linear Probing                  | A strategy for dealing with collisions where we search through the array to find the next empty slot.

## **Thanks for Coming to My TED Talk**

![GIF](https://media.giphy.com/media/pj8zUmZogKUGA/giphy.gif)
