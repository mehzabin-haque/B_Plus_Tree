# B+ Tree Dictionary


## Introduction

This GitHub repository contains an implementation of a B+ tree dictionary in C++. The B+ tree is a balanced tree data structure optimized for range queries and efficient data retrieval. The dictionary allows users to specify the fanout (degree) of the B+ tree and search for words in the dictionary, providing detailed information about the search process.

## Features

- B+ tree implementation for efficient dictionary operations.
- Customizable fanout to adjust tree structure based on memory and performance requirements.
- Ability to search for words in the dictionary and display the search process steps.
- Supports large datasets, with test data of approximately 18,000 words.
- Easily extendable to accommodate more data.

## How to Use

1. Clone the repository to your local machine:

```bash
git clone https://github.com/mehzabin-haque/B_Plus_Tree.git
```

2. Compile the source code:

```bash
g++ -o bpt.cpp
```

3. Run the program:

```bash
./bpt
```

4. Follow the on-screen instructions to provide the fanout and perform word searches in the dictionary.

## Sample Output

```
Enter the fanout of the B+ tree: 4

B+ Tree constructed with fanout 4.
Please enter the word you want to search: apple

Search Step 1: Searching in the root node.
Search Step 2: Found word in leaf node.

Word 'apple' is present in the dictionary.
Additional Information:
- Word frequency: 128
- Rank: 5
- Parent Node: [parent_node_address]
- Child Node: [child_node_address]
...
```

## Contributions

Contributions to this repository are welcome. If you find any issues or want to enhance the functionality of the B+ tree dictionary, feel free to open a pull request.

## Disclaimer

This B+ tree dictionary is designed for educational purposes and can serve as a foundation for more complex dictionary systems. Please use it responsibly and adapt it to your specific requirements if using it in production environments.
