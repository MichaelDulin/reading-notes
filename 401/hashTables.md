# Hash Tables

[Back to main](https://michaeldulin.github.io/reading-notes)

**Trees Resources**
- [Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)
- [what is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)
- [basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)
- [hash table wiki](https://en.wikipedia.org/wiki/Hash_table)

****

## Common Terminology
**Hash**
  - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

**Bucket**
  - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

**Collisions**
  - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

**Basic Concept**
- A data strcture which utilizes key value pairs.
- Used to hold unique values, dictionaries or libraries.
- Provides us with the ablitity to store keys within the structure for easily allowcation.
- Utilizes arrays read access O(1).
- Runs in real time.
- Uses num/int as key to quickly retrieve data and write to array, hence the quickness.

****

## Structure
**Creating a Hash**
- The hashtable is created from an array, and turns keys into numeric values to assign/retrieve data:
  1. Add or multiply all the ASCII values together.
  2. Multiply it by a prime number such as 599.
  3. Use modulo to get the remainder of the result, when divided by the total size of the array.
  4. Insert into the array at that index.

**Buckets**
- Each index of the array contains buckets, which hol one key/value pair combination
- When no entry is present in a bucket, it is assigned null
- All buckets start at null and are overwritten as the table is made.

**collisions**
- Occurs when more than one key hashes to the same index in an array.
- Collisions are handled by either creating a new index and assigning it
- A better way is to initialize a linkedlist into each bucket, which allows each indexed key/value pair to be logged

****

## Methods

**set()**
- When adding a new ky/value pair to a hashtable:
  1. send the key to the hash() method.
  2. Once you determine the index of where it should be placed, go to that index
  3. Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
  4. If something does exist, add the new key/value pair to the data structure within that bucket.

**get()**
- The get() method takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

**has()**
- The has() method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the hash() method and check the hashtable if the key exists in the table given the index returned.

**keys()**
- The keys() method returns a collection (array) of unique hash keys.

**hash()**
- The hash() method will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.






















