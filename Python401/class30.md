# Hash Tables

## Important Terminology

- **Hash** - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
- **Buckets** - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
- **Collisions** - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## More Things About Hash Tables

- Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects.
- Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.
- The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value.
- A hash function is any function that can be used to map a data set of an arbitrary size to a data set of a fixed size, which falls into the hash table. The values returned by a hash function are called hash values, hash codes, hash sums, or simply hashes.
- The hash function takes a key and returns an integer.
- A hash code turns a key into an integer.
- Their output is determined only by their input
- The same key should always produce the same hash code.
- A collision occurs when more than one key hashes to the same index in an array.
- A “perfect hash” will never have any collision
- If a hash map has only a few buckets it will be densely full and have many collisions.
- If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.

### Resources

- https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html 
- https://www.youtube.com/watch?v=MfhjkfocRR0 
- https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/ 
- https://en.wikipedia.org/wiki/Hash_table 
