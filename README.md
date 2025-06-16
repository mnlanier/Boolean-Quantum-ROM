Given a boolean function that takes as input length $n$ bit-strings, this code will output a circuit (with slightly more optimized ideas from "Select ROM") that gives $|x\rangle|f(x)\rangle$
when you input $|x\rangle|0\rangle$. The fact that $X^2=I$ lets us optimize the basic ideas from Select ROM. 

We ask for input from the user to define the $n$ bit boolean function by asking for $n$, the bit-string length, the number of elements in $\mathbb{F}_2^n$ that output $1$ and the bit-strings that result in $1$ from the function. These $3$ inputs completely determine our function $f$. Our code then runs off of these inputs and outputs a circuit that gives $|x\rangle|f(x)\rangle$.
