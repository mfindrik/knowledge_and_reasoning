# Logic and Reasoning

Mathematical logic has a strong influence on computer science and field of artifical intelligence called knowledge representation and reasoning. People realized that facts could be written in the computers and with a help of automated inference engines computers could draw conclusions and new knowledge based on these facts just has humans do. These systems with ability of deriving new knowledge and making decisions are called expert systems. An expert systems are basically thought to be consisting of following two components: the inference engine and the knowledge base. The knowledge base represents facts and rules, whereas the inference engine applies the rules to the known facts to deduce new facts. One very popular idea of using an "expert system" is the idea of Semantic Web proposed by Tim Berners-Lee, inventor of the World Wide Web in 2001. The Semantic Web seeks to add a layer of semantics (meaning) on top of the current Internet. Rather than indexing web sites and pages via keywords, the Semantic Web would create large ontologies (knowledge bases) thus making search more effective than traditional text only searches. The idea of Semantic Web is still far from delivering its promises, but W3C consortium who is working on it has relesed some usable standard such as RDF and OWL - languages for representing knowledge. 

Before digging further into expert systems and Semantic Web, let's explain some basics of mathematical logic that will give us an idea about how to formally express knowledge and reason over it. In the text below most common types of logic are are outline.

## Propositional logic
Aka boolean logic deals with propositions (statements) which can either be evaluted as true or false, such as "It's sunny outside right now.". Right, so besides propositions we need operators in order to build up logical expressions. Available operators in propositional logic are ARE, OR, NOT and IMPLICATION. How do we reason about logical expressions? Imagine, I say following statement: "If it is sunny outside, then I go for hiking.". So if I tell you that it is sunny outside, you can derive that I am hiking. That's pretty much reasoning in propositional logic. 

But how do we computationally come to conclusion that is implied by the logical expresson. There are actually two ways to do that, using truth tables or using rules of inteference. From propositional logic an interesting problem has emerged called satisficability problem that can be stated as follows: "Is there an assigment of true/false variables to predicates such that a logical expression is true?". It turns out this problem is NP-complete and takes exponential time to be solved.

## Description Logic

## First order logic

## Temporal logic

