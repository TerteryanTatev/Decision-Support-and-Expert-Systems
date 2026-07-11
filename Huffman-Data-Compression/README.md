# Huffman Coding for Data Compression

This folder contains a custom Python implementation of the Huffman Coding algorithm, a foundational greedy optimization method used for lossless data compression and prefix-free variable-length code generation.

##  Implemented Methodology
* **Frequency Distribution Mapping:** Leveraging standard collections (`Counter`) to analyze individual character frequencies within arbitrary text payloads.
* **Priority Queue Tree Construction:** Utilizing min-heap structures (`heapq`) to recursively merge the lowest-frequency node leaf nodes into a unified binary tree.
* **Prefix-Free Binary Coding:** Traversing the generated tree to assign unique variable-length binary strings, ensuring more frequent characters receive shorter codes.
* **Efficiency Analysis:** Computationally evaluating the performance by measuring Shannon Entropy against the average computed codeword length ($H \le L < H + 1$).
* **Tree Visualization:** Plotting the hierarchical tree architecture dynamically using `matplotlib`.

##  Technologies Used
* **Python 3**
* **Heapq & Collections:** For optimal priority queue tracking and token counting.
* **Matplotlib:** For programmatic plotting and tree structural figure rendering.
