# fundamentals of lattice-based cryptography

## what is a lattice?

An $n$-dimensional *lattice* $L$ is a discrete addictive subgroup of $\mathbb{R}^n$

- **discrete**: This means that every point $x \in L$ has some "neighborhood" in which $x$ is the only lattice point. That is, for every point $x$ there is "good" space around it

Below, we will see what a lattice is and what is not.

- The singleton set $\{0\} \in \mathbb{R}^n$ is a lattice(for any positive integer $n$). That is, the zero set in any dimension is a lattice.


    
![png](fundamentals%20copy_files/fundamentals%20copy_4_0.png)
    


- The integers $\mathbb{Z} \in \mathbb{R}$ form a 1-dimensional lattice


    
![png](fundamentals%20copy_files/fundamentals%20copy_6_0.png)
    



    
![png](fundamentals%20copy_files/fundamentals%20copy_6_1.png)
    


- The integer grid $\mathbb{Z}^n \in \mathbb{R}^n$ is an n-dimensional lattice


    
![png](fundamentals%20copy_files/fundamentals%20copy_8_0.png)
    


- The set $\{x ∈ \mathbb{Z}^n : \sum_{i=1}^nx_i ∈ 2\mathbb{Z}\}$ is a lattice; it is often called the “checkerboard” or “chessboard” lattice, especially in two dimensions. It contains all n-tuples of integers $x = (x_1, x_2,...,x_n) \in \mathbb{Z}$ such the sum of the components of $x$, i.e $\sum_{i = 1}^{x_i}$, is an even integer.

  **Example**: $(0,0),(1,1),(2,4),(−3,5),(−2,−2)$
  
  **Non-example**: $(1,0),(2,3),(−1,2)$

    100



    
![png](fundamentals%20copy_files/fundamentals%20copy_10_1.png)
    



    
![png](fundamentals%20copy_files/fundamentals%20copy_11_0.png)
    

