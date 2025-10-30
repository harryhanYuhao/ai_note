# Reading Note

## Oct 27

### [A Theoretical Understanding of Chain-of-Thought: Coherent Reasoning and Error-Aware Demonstration, Oct 2024](https://arxiv.org/pdf/2410.16540)

Proposed a new algorithm for Chain-of-Thought (CoT) prompting. The algorithm is rather naive: just adding a new row in parameter holding past prompts. 

This article also have lengthy statistical analysis on the new prompting algorithms. Specifically, it calculated the best (that is, least) lost for coherent. (I am not sure if this is indeed the best.) The proof is naive. 

[An interesting assumption](https://arxiv.org/pdf/2305.18869) of mathematical models for prompting LLMs is cited in the paper.

## Oct 28 

### [Graph of Thoughts: Solving Elaborate Problems with Large Language Models, Feb 2024](https://arxiv.org/pdf/2308.09687)

Proposed graph of thoughts for LLM. It is a natural extension of chain of thoughts and tree of thoughts. (Recall tree is a minimal connected graph)
In graph of thoughts, node is the state of LLM, and a directed edge is a LLM deduction to arrive in a new state. 

## Oct 30 

### [The Origins of Representation Manifolds in Large Language Models](https://arxiv.org/pdf/2505.18235)

Very interesting idea to use metric space, topology, and geodesics to analyze behaviour of LLMs. However, they do not develop their idea fully.

1. They made some bold hypothesis on properties of manifolds wrt representation of LLLM as vector in high dimensional space.
1. Only proved a mild theorem with theire strong assumptions.
1. Did not suggest what LLM can do with their theory.
1. Did not utilize the rich theory of manifolds.

It seems like distance is very important in their attempted theory to explain manifolds. 
I presume we can do a lot with Reimannian geometry. 

## To Read

[Dissecting Chain-of-Thought: Compositionality through In-Context Filtering and Learning](https://arxiv.org/pdf/2305.18869) of mathematical models for prompting LLMs is cited in the paper.
