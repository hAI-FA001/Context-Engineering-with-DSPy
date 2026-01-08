# Context-Engineering

<a href="https://www.youtube.com/watch?v=5Bym0ffALaU">Reference</a>

"...the delicate art and science of filling the context window with just the right information..." ~ Andrej Karpathy

What it is:

- Fitting information into LLM's context
- Multi-interaction prompts instead of a single prompt
- Multiple agents working on subproblems
- Information sources
- Guardrails, validations, evals, etc

LLMs have large context windows, so why not fit everything? <br>
=> <b>Context Rot</b>

- Context Poisoning - Hallucinations in the context
- Context Distraction - Context overwhelms the training
- Context Clash - Parts of the context disagree
- Context Confusion - Influence of superfluous context
  <br>
  <br>
- How to fix:
  - RAG - Relevant info
  - Context Quarantine - Isolate subtask contexts
  - Context Summarization - Turn accumulated context into a summary
  - Tool Loadout - Relevant tool definitions
  - Context Pruning - Remove irrelevant info
  - Context Offloading - Store outside the context

<b>DSPy</b> - A prompt programming framework

<br>
Content:

- Prompt Engineering
  - Atomic Prompts
  - Constraints and Context
  - Few-Shotting
  - Chain-of-Thought
  - DSPy
- Multi-Agent Interactions
  - Sequential Flows
  - Iterative Refinement
  - Conditional Branching
  - Parallel Generation
  - Reflection
- Evals, Guardrails, Monitoring
  - Evals
  - MLFlow
  - Hyperparameters
  - LLMs as a Judge
  - ELO
- Tool Calls and ReAct
  - Tools as Python Functions
  - Web Search
  - ReAct
  - File I/O
  - Scratchpad
  - MCP
- RAG and Memory
  - Embeddings vs BM25
  - Reciprocal Rank Fusion
  - HyDE - Hypothetical Queries
  - Multi-Hop Search
  - Memory Systems
  - Mem0
