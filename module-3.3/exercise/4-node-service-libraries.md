# Exercise 4: Node Service Libraries

## Objective
Explore node service libraries (sc_*) and understand their role in networking and node management.

## Instructions

1. For each of the following node service libraries, explain its main function:
   - `sc_service`: 
   - `sc_cli`: 
   - `sc_executor`: 
   - `sc_network`: 
   - `sc_consensus`: 

2. In a Substrate node project, create a simple Cargo.toml dependency section that includes essential node service libraries.

3. Explain the relationship between:
   - The node implementation
   - The runtime implementation
   - How they communicate with each other

4. If you were debugging issues with block production in your Substrate node, which node service libraries would you most likely need to investigate?

5. Why are node service libraries compiled to native code only, while runtime libraries are compiled to both native and Wasm? 