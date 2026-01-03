# **Post-Class: Mastering the Engine**

Congratulations on completing Lesson 1.6\! NumPy is a skill that rewards practice.

## **1\. Deferred Theory: Memory Layout**

In class, we mentioned NumPy is fast. This is because it uses **Contiguous Memory**. In a Python list, your data might be scattered all over your RAM (like a scavenger hunt). In NumPy, it is one solid block. This allows your CPU to use "SIMD" (Single Instruction, Multiple Data) to process it.

## **2\. Additional Practice**

**Challenge 1: The Identity Matrix** Look up the function `np.eye()`. Create a 5x5 identity matrix and multiply it by a random 5x5 matrix (`np.random.randn(5, 5)`). What happens?

**Challenge 2: Data Normalization** Given an array `arr = np.array([10, 20, 30, 40, 50])`, calculate the "Z-score" for each element. *Formula:* `(x - mean) / standard_deviation` *Hint:* Use `arr.mean()` and `arr.std()`.

## **3\. Recommended Reading**

* [NumPy Illustrated: A Visual Guide](https://medium.com/better-programming/numpy-illustrated-the-visual-guide-to-numpy-3b1d4976de1d) \- Excellent for visual learners.  
* [Official NumPy Quickstart](https://numpy.org/doc/stable/user/quickstart.html)

**Next Lesson:** 1.7 Introduction to Pandas. We will take these NumPy arrays and turn them into powerful DataFrames with labels\!
