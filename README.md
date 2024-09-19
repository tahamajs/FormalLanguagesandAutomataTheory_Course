# Formal Languages and Automata Theory (FLAT) Exercises - University of Tehran

## Overview

This repository contains a collection of homework assignments for the **Formal Languages and Automata Theory (FLAT)** course at the **University of Tehran**. Each homework focuses on different aspects of formal languages, automata theory, Turing machines, and computational complexity. The exercises are designed to deepen your understanding of theoretical computer science concepts through practical application.

---

## Repository Structure

- **HW01**: [Regular Languages and Deterministic Finite Automata (DFAs)](#hw01---regular-languages-and-deterministic-finite-automata-dfas)
- **HW02**: [Regular Expressions and Automata](#hw02---regular-expressions-and-automata)
- **HW03**: [Non-Regular Languages and the Pumping Lemma](#hw03---non-regular-languages-and-the-pumping-lemma)
- **HW04**: [Context-Free Grammars (CFGs) and Pushdown Automata (PDAs)](#hw04---context-free-grammars-cfgs-and-pushdown-automata-pdas)
- **HW05**: [Chomsky Normal Form (CNF) and Grammar Transformations](#hw05---chomsky-normal-form-cnf-and-grammar-transformations)
- **HW06**: [Decidability and Turing Machines](#hw06---decidability-and-turing-machines)
- **HW07**: [Pumping Lemma for Context-Free Languages](#hw07---pumping-lemma-for-context-free-languages)
- **HW08**: [Advanced Turing Machines and Computational Models](#hw08---advanced-turing-machines-and-computational-models)
- **HW09**: [Mapping Reducibility and Undecidability](#hw09---mapping-reducibility-and-undecidability)
- **HW10**: [Automata Complexity and State Minimization](#hw10---automata-complexity-and-state-minimization)
- **HW11**: [Palindromes and Decision Problems in Automata](#hw11---palindromes-and-decision-problems-in-automata)
- **HW12**: [Advanced Topics in Formal Language Theory](#hw12---advanced-topics-in-formal-language-theory)

---

## Assignment Descriptions

### HW01 - **Regular Languages and Deterministic Finite Automata (DFAs)**

#### Key Concepts

- **Regular Languages**: Languages that can be recognized by finite automata and described using regular expressions.
- **Deterministic Finite Automata (DFAs)**: Finite state machines where each state has exactly one transition for each input symbol.
- **Designing DFAs**: Constructing DFAs for specific language descriptions, recognizing strings over a given alphabet.

#### Objectives

- Understand the fundamental properties of regular languages.
- Practice designing DFAs for various regular languages.
- Explore how DFAs process input strings to accept or reject them based on defined transitions.

---

### HW02 - **Regular Expressions and Automata**

#### Key Concepts

- **Regular Expressions (REs)**: Symbolic notations used to represent regular languages.
- **Conversion from RE to DFA**: Translating regular expressions into equivalent DFAs.
- **Simplifying Automata**: Minimizing the number of states in automata without changing the language recognized.

#### Objectives

- Master the use of regular expressions in defining languages.
- Learn algorithms for converting regular expressions to finite automata.
- Apply state minimization techniques to simplify automata.

---

### HW03 - **Non-Regular Languages and the Pumping Lemma**

#### Key Concepts

- **Non-Regular Languages**: Languages that cannot be recognized by finite automata or described by regular expressions.
- **Pumping Lemma for Regular Languages**: A property that all regular languages satisfy, used to prove that certain languages are not regular.
- **Proof Techniques**: Using the pumping lemma to demonstrate non-regularity by contradiction.

#### Objectives

- Understand the limitations of regular languages and finite automata.
- Apply the pumping lemma in proving non-regularity.
- Develop skills in constructing formal proofs within language theory.

---

### HW04 - **Context-Free Grammars (CFGs) and Pushdown Automata (PDAs)**

#### Key Concepts

- **Context-Free Grammars (CFGs)**: Grammars where production rules replace a single non-terminal symbol with a string of terminals and non-terminals.
- **Pushdown Automata (PDAs)**: Automata equipped with a stack, capable of recognizing context-free languages.
- **Conversion between CFGs and PDAs**: Designing PDAs for specific CFGs and vice versa.

#### Objectives

- Understand the structure and usage of CFGs.
- Practice designing CFGs for given languages.
- Learn how to construct PDAs from CFGs.
- Explore the capabilities of PDAs in recognizing context-free languages.

---

### HW05 - **Chomsky Normal Form (CNF) and Grammar Transformations**

#### Key Concepts

- **Chomsky Normal Form (CNF)**: A simplified form of CFG where production rules are in a specific standard form.
- **Grammar Transformations**: Techniques for converting CFGs to CNF by removing useless symbols, ε-rules, and unit productions.
- **Simplification of Grammars**: Streamlining grammars without altering the language they generate.

#### Objectives

- Learn the process of converting CFGs into CNF.
- Understand the importance of CNF in parsing and theoretical proofs.
- Apply grammar simplification techniques effectively.

---

### HW06 - **Decidability and Turing Machines**

#### Key Concepts

- **Turing Machines (TMs)**: Abstract computational models that can simulate any algorithm.
- **Decidable and Undecidable Languages**: Languages for which a Turing machine can or cannot decide acceptance or rejection.
- **Halting Problem**: Demonstrating the existence of undecidable problems through the classic halting problem.

#### Objectives

- Explore Turing machines as a model of computation.
- Understand the concept of decidability in computational theory.
- Examine undecidable problems and their implications.
- Construct Turing machines for specific computational tasks.

---

### HW07 - **Pumping Lemma for Context-Free Languages**

#### Key Concepts

- **Context-Free Language (CFL) Pumping Lemma**: A property that all CFLs satisfy, used to prove that certain languages are not context-free.
- **Non-Context-Free Languages**: Identifying languages that cannot be generated by any CFG.
- **Proof Techniques**: Applying the CFL pumping lemma to demonstrate non-context-freeness.

#### Objectives

- Understand the limitations of context-free languages.
- Use the pumping lemma for CFLs in formal proofs.
- Differentiate between context-free and non-context-free languages.

---

### HW08 - **Advanced Turing Machines and Computational Models**

#### Key Concepts

- **Turing Machine Variants**: Exploring multi-tape, non-deterministic, and other variants of Turing machines.
- **Computational Universality**: Understanding that different Turing machine models are equivalent in computational power.
- **Decidability and Recognizability**: Deepening knowledge of problems that are decidable, semi-decidable, or undecidable.

#### Objectives

- Study advanced Turing machine models and their properties.
- Understand equivalence between various computational models.
- Design Turing machines for complex computational tasks.

---

### HW09 - **Mapping Reducibility and Undecidability**

#### Key Concepts

- **Mapping Reducibility**: Proving undecidability by reducing one problem to another known undecidable problem.
- **Undecidable Languages**: Further exploration of languages and problems that are undecidable.
- **Reduction Techniques**: Utilizing reductions to demonstrate the undecidability of certain problems.

#### Objectives

- Learn to use mapping reducibility in undecidability proofs.
- Understand relationships between different undecidable problems.
- Practice constructing reductions between problems.

---

### HW10 - **Automata Complexity and State Minimization**

#### Key Concepts

- **State Complexity**: Analyzing the number of states required in automata to recognize specific languages.
- **Automata Minimization**: Techniques for reducing states in DFAs while preserving language recognition.
- **Equivalence of Automata**: Determining when two automata are equivalent in terms of the languages they recognize.

#### Objectives

- Study complexity considerations in automata design.
- Apply algorithms for minimizing finite automata.
- Compare automata and prove their equivalence.

---

### HW11 - **Palindromes and Decision Problems in Automata**

#### Key Concepts

- **Palindromes**: Strings that read the same forwards and backwards.
- **Recognizing Palindromes**: Investigating the capabilities of automata in recognizing palindromic languages.
- **Decision Problems**: Exploring the decidability of various language properties and automata behaviors.

#### Objectives

- Understand challenges in recognizing palindromic languages with automata.
- Explore decision problems related to automata theory.
- Design automata or prove the impossibility of recognition for certain languages.

---

### HW12 - **Advanced Topics in Formal Language Theory**

#### Key Concepts

- **Closure Properties**: Studying how language classes are closed under operations like union, intersection, and concatenation.
- **Cross-Product Languages**: Analyzing languages formed by combining two or more languages.
- **Automata-Based Proofs**: Using automata constructions to prove language properties and closure under operations.

#### Objectives

- Explore advanced concepts in formal languages.
- Understand the effects of language operations on language classes.
- Use automata to construct formal proofs of language properties.

---

## References

The exercises are based on foundational texts in automata theory and formal languages:

- **Michael Sipser**: *Introduction to the Theory of Computation*
- **John E. Hopcroft, Rajeev Motwani, Jeffrey D. Ullman**: *Introduction to Automata Theory, Languages, and Computation*
- **Peter Linz**: *An Introduction to Formal Languages and Automata*
- **Course Lecture Notes**: Provided by the instructors.

---

## How to Use This Repository

Each homework assignment is contained within its own directory (e.g., `HW01/`, `HW02/`, etc.). Within each directory, you will find:

- **Assignment Description**: Detailed problems and questions to solve.
- **Solutions**: Written solutions, proofs, and diagrams where applicable.
- **Supplementary Materials**: Any additional resources or references.

To maximize your learning:

1. **Review the Key Concepts**: Ensure you understand the theoretical background before attempting the assignments.
2. **Attempt Problems Independently**: Try solving the problems on your own first.
3. **Consult Solutions**: Use the provided solutions to check your work and understand any mistakes.
4. **Engage with Supplementary Materials**: Deepen your understanding by reviewing additional resources.

---

## Prerequisites

- **Mathematical Foundations**: Familiarity with discrete mathematics, logic, and proof techniques.
- **Basic Understanding of Automata Theory**: Prior exposure to finite automata and formal languages is helpful.

---

## License

This repository is intended for educational purposes. **All rights to the content are reserved by the University of Tehran and the course instructors.** Unauthorized distribution or commercial use is prohibited.

---

## Acknowledgements

- **Course**: Formal Languages and Automata Theory
- **University**: University of Tehran
- **Instructors**: Dr Hossein Hojjat
- **Department**: Computer Engineering / Computer Science

---

## Contact

For questions or suggestions, please open an issue or contact the repository maintainer.

---

Feel free to explore each homework directory for detailed problems and solutions. This repository aims to support your learning journey in formal languages and automata theory by providing comprehensive exercises and explanations.
