# Bra-ket Notation for Dummies

PS: You are not dummy

Bra-Ket is a way of writing special vectors used in Quantum Physics. It was effectively established in 1939 by Paul Dirac, it is thus also known as Dirac notation. 

## Normal Vectors

To represent a point in 3D space, we use 3 coordinates namely x, y and z.   
For example, a point in complex plane, can be represented in vector form as   
`a i-axis + b j-axis + c k-axis` or as `(a,b,c)`.

```
vector V = 2i + 3j + 4k
         
         = 2 [1]     3 [0]    4 [0]
             [0]  +    [1]  +   [0]
             [0]       [0]      [1]
         
         =  [2]
            [3]   -> column matrix/vector
            [4]
``` 

## Quantum Mechanics Vectors

Normal vectors lie in 3D space. Vectors used in quantum mechanics lie in an abstract, mathematical, infinitely dimensional Hilbert Space.   
Hilbert Space is beyond our scope, but just remember the above point.   

In order to differentiate column and row vectors in quantum mechanics, we use ket and bra notations.  

```
Ket Notation
------------
| r ⟩  =  [ a ]
          [ b ] -> column vector
          [ c ]

Bra Notation
------------
⟨ r | = [e   f   g]  -> row vector
```

A bra notation can be converted to ket notation by taking conjugate transpose.<sup>[1]</sup>
+ conjugate: a−bi becomes a+bi
+ transpose: rows swap with columns
```
| r ⟩ = [2−3i]
        [6+4i]
        [3−1i]

⟨ r | = [2+3i   6−4i    3+i]
```

## Reading Bra-Ket Notation

```
Let us consider 2 qubits. They can be in superposition of 4 classical states. 
α1|00⟩ + α2|01⟩ + α3|10⟩ + α4|11⟩
The 'α' represents the magnitude of each state. 
```
```
( 1/√2 )( |HH⟩ + |TT⟩ )
Here, each state has magnitude of 1/√2
|HH⟩ and |TT⟩ represent the states of the qubits

Both the qubits can be in head state or both the qubits can be in tail state
```
## Born's Rule

Probability of each state is square of its magnitude. 
```
1/√2 |HH⟩ + 1/√2 |TT⟩ 
Here, each state has magnitude of 1/√2
So |HH⟩ and |TT⟩ has 1/2 (50%) probability each.

Both the coins land on heads -> 50%
Both the coins land on tails -> 50%
One coin on heads and another on tails -> 0% because there is no |HT⟩ or |TH⟩ state

Probablity of heads -> 50%
Probablity of tails -> 50%
```

```
√3/2 |HH⟩ + 1/2 |TT⟩
Here, one state has magnitude of √3/2 and another has magnitude of 1/2
So, |HH⟩ has probability of 3/4 (75%) and |TT⟩ has probability of 1/4 (25%).

Both the coins land on heads -> 75%
Both the coins land on tails -> 25%
One coin on heads and another on tails -> 0% because there is no |HT⟩ or |TH⟩ state

Probablity of heads -> 50%
Probablity of tails -> 50%
```

## References
1. https://www.mathsisfun.com/physics/bra-ket-notation.html
2. https://link.springer.com/chapter/10.1007/978-3-030-61601-4_7



