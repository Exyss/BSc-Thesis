# 🎓 Bachelor's Thesis in Computer Science

My Bachelor's Degree Thesis in Computer Science at Sapienza Università di Roma, entitled ___"Efficient Parity Decision Trees and Their Connections to Logical Proofs and Total Search Problems in NP"___.

[Download the Thesis](https://raw.githubusercontent.com/exyss/bsc-thesis/main/src/Thesis.pdf)

## Abstract
In computability theory, a _search problem_ is a type of computational problem based on finding a specific property, object or structure in a given instance of a particular entity. Search problems describe any input-output-based problem, even everyday problems, ranging from number factorization to complex graph theory questions. For a given instance, some problems may even take the age of the universe to be solved by a machine. Complexity theory studies computational resources to identify what can and cannot be computed in a reasonable amount of time.

In recent years, the interest in _total search problem_, i.e. search problems that have at least one solution for all possible instances of the problem, has grown. Extensive study of these problems has shown that it is sufficient to restrict our interest to a small set of problems, each corresponding to a basic combinatorial principle, defining what is now referred to as the $\mathsf{TFNP}$ hierarchy. This hierarchy has been shown to be deeply linked with other complexity theory branches, such as logical proofs, circuits and protocols. These connections inspired researchers to extend the known results in hope of achieving an _universal theory_.

The thesis has two main goals: to summarize the main results in the $\mathsf{TFNP}$ world and to show new ones obtained through the introduction of _Parity Decision Trees_, an extension of the decision tree computational model based on linear forms in $\mathbb{F}_2$.

In the first chapter, we discuss the origins of computability theory, the basic concepts of computational complexity and the reasons behind the study of such concepts.

In the second chapter, we discuss the differences between decision problems and search problems, while also defining the decision classes $\mathsf{P}$, $\mathsf{NP}$ and the functional classes $\mathsf{FP}, \mathsf{FNP}$ and $\mathsf{TFNP}$. Then, we explain reductions between problems, how they lead to the concept of completeness and how they apply to total search problems, giving birth to the $\mathsf{TFNP}$ hierarchy.

In the third chapter, we focus on the black-box version of the $\mathsf{TFNP}$ hierarchy. We discuss how this model characterizes relativization through oracles and how this translates to the use of decision trees. Then, we explain how the connections between decision trees and proof complexity give an alternative lens under which this model can be studied.

In the final chapter, we introduce the concept of parity in the black-box model through the use of parity decision trees. We show how parity defines a computational model stronger than the traditional one, introducing a new class $\mathsf{FP}^{pdt}$, i.e. the class of $\mathsf{TFNP}$ problems efficiently solvable by a PDT. Then, we show that this class is characterized by the Tree-like Linear Resolution over $\mathbb{F}_2$ proof system, proving that the complexity of PDTs is equivalent to the complexity of proofs in this system. Finally, we show that short proofs in \mathsf{TreeRes}$_\oplus$ can be converted into short proofs in the Nullstellensatz proof system, which characterizes all problems reducible to the Polynomial Parity Argument (PPA) principle. These results define new relations between our new class $\mathsf{FP}^{pdt}$ and the already known classes, in particular the inclusions $\mathsf{FP}^{dt} \subsetneq \mathsf{FP}^{pdt} \subseteq \mathsf{PPA}^{dt}$ and the non-inclusion $\mathsf{PLS}^{dt} \not\subseteq \mathsf{FP}^{dt}$.
