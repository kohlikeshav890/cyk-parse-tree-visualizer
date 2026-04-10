📌 CYK Parse Tree Visualizer

A visual learning tool for parsing Context-Free Grammars (CFG) using the CYK Algorithm, featuring CNF conversion, step-by-step table animation, and parse tree generation.

Features
Convert CFG → CNF (Chomsky Normal Form)
Run CYK Algorithm (Dynamic Programming)
Step-by-step animation of table filling
Generate parse trees
Detect ambiguity (multiple parse trees)
Display complexity and statistics


How It Works
Input Grammar
Define non-terminals, terminals, start symbol, and productions
Convert to CNF
Eliminates ε-productions, unit productions, and useless symbols
Converts rules into standard CNF format
Run CYK Algorithm
Builds a triangular table using dynamic programming
Determines whether the string is accepted
Visualize Parsing
Animate how each cell in the CYK table is filled
Generate Parse Trees
Reconstruct all valid parse trees
Detect ambiguity if multiple trees exist


🧪 Example

Grammar:
E → E + E | E * E | id

Input String:
id + id * id

Output:

Accepted by grammar
2 parse trees generated
Grammar is ambiguous
Project Structure
├── grammar        → CFG data structure
├── cnf_converter  → CNF transformation logic
├── cyk_engine     → CYK algorithm implementation
├── tree_builder   → Parse tree reconstruction
├── visualization  → UI, animation, and rendering
⚙️ Tech Stack
HTML
CSS
JavaScript

 Use Cases
Theory of Computation learning
Understanding CYK algorithm visually
Demonstrating ambiguity in CFGs
Academic presentations & projects


 Authors
Your Name
Teammate Name


 Conclusion

This project transforms abstract parsing concepts into an interactive and visual experience, making it easier to understand CYK parsing, CNF conversion, and grammar ambiguity.