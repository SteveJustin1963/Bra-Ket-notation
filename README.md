# Bra–ket notation 
is a notation used in quantum mechanics to represent quantum states. It is used to describe the state of a quantum system, as well as to describe operations on quantum states. 

## ket |ψ>
In the notation, a ket |ψ> represents a state of a quantum system. The ket is written as a column vector, and its complex coefficients represent the amplitudes of the various states that make up the quantum state. For example, the state |ψ> = α|0> + β|1> represents a superposition of the |0> and |1> states, with complex coefficients α and β representing the amplitudes of the |0> and |1> states, respectively.

## bra <ψ|
The corresponding dual state, or "bra," is written as a row vector with complex conjugate coefficients and is denoted as <ψ|. The inner product between a ket and a bra is denoted as <ψ|φ>, and it represents the probability of measuring the quantum system in state |φ>.  In other words, the inner product is a scalar value that describes the "overlap" between the states represented by the ket and bra.

The inner product is a scalar value that describes the "overlap" between the states represented by the ket and bra.
In the context of an inner product space V, the inner product between two vectors |φ> and |ψ> can be written as <φ|ψ>. This inner product allows us to define a corresponding linear form, or linear functional, on V through the identification (|φ>, |ψ>) = <φ|ψ>. The linear form <φ| is then a covector, or dual vector, to the vector |φ>, and the set of all covectors forms a subspace of the dual vector space V^(vee).
The purpose of the linear form <φ| is to make projections onto the state |φ> and find how linearly dependent two states are. 

kets can be identified with column vectors and bras with row vectors when the vector space is C^(n), the space of n-dimensional complex vectors. In this case, the inner product between two vectors |φ> and |ψ> can be written as <φ|ψ>, where the inner product is defined as (|φ>, |ψ>) = |φ>^(dagger)|ψ>, where ^(dagger) denotes the conjugate transpose of a matrix. Under this identification, the identification of kets and bras and vice versa provided by the inner product is taking the conjugate transpose, which is also known as the Hermitian conjugate. This allows us to use matrix multiplication to interpret combinations of bras, kets, and linear operators in bra-ket notation.

it is common to suppress the vector or linear form and only use a label inside the typography for the bra or ket. This allows us to use a compact notation to represent quantum states and operations. For example, in the case of a two-dimensional space of spinors, the spin operator may have eigenvalues +1/2 and -1/2, with corresponding eigenspinors |+> and |->. In this case, we can represent the eigenspinors in bra-ket notation as |+> and |->, respectively. Kets and bras with the same label are interpreted as kets and bras corresponding to each other through the inner product, and when also identified with row and column vectors, kets and bras with the same label are identified with the conjugate transpose of the corresponding row and column vectors.


## Quantum state: 
## eg1
Consider a qubit in the state |ψ> = α|0> + β|1>, where |0> and |1> are the computational basis states and α and β are complex coefficients. In this case, |ψ> represents a quantum state that is a superposition of the |0> and |1> states.
## eg2
Consider a three-qubit system in the state |ψ> = (|001> + |110> + |101>)/sqrt(3), where |0> and |1> are the computational basis states. In this case, |ψ> represents a quantum state that is a superposition of the |001>, |110>, and |101> states.


## Quantum operation: 
## eg1
Consider a quantum operation represented by a unitary matrix U that acts on a qubit in the state |ψ>. In bra-ket notation, this operation can be written as |φ> = U|ψ>.
## eg1
Consider a quantum operation represented by a matrix M that acts on a qubit in the state |ψ>. In bra-ket notation, this operation can be written as |φ> = M|ψ>.

## Measurement: 
## eg1
Consider a measurement of a qubit in the state |ψ> in the computational basis. The probability of measuring the qubit in the |0> state is given by P(|0>) = |<0|ψ>|^2, and the probability of measuring the qubit in the |1> state is given by P(|1>) = |<1|ψ>|^2.
## eg2
Consider a measurement of a two-qubit system in the state |ψ> in the computational basis. The probability of measuring the first qubit in the |0> state and the second qubit in the |1> state is given by P(|01>) = |<01|ψ>|^2.



## Ref
- https://en.wikipedia.org/wiki/Bra%E2%80%93ket_notation
