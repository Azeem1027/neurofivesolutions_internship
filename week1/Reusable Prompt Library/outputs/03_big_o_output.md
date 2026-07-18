- **Core Mechanism**: **Big O Notation** is a mathematical notation used to analyze and classify the **asymptotic time complexity** of an algorithm. It calculates the upper bound of execution time by tracking how the total number of operations grows relative to an input size $N$ approaching infinity.
- **Key Takeaways**:
  * It measures the **worst-case scenario** execution path of the code structure.
  * It completely discards **constant factors** and lower-order terms (e.g., $O(N^2 + N)$ simplifies to $O(N^2)$).
- **Analogy**: Sending a physical hard drive via an airplane takes the same execution time whether it holds 1 GB or 10 TB, scaling as constant time $O(1)$. Downloading that same data online scales linearly as $O(N)$, taking significantly longer as data grows.