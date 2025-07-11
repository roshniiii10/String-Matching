# String-Matching
This repository contains a project implementation related to String Matching Algorithms, used for efficiently finding occurrences of a pattern within a text.
## Files in the Repository
1. `Finite-Automaton.c` :
- This is the implementation file for the Finite Automaton String Matching Algorithm.
- It builds a finite automaton for the given pattern and uses it to scan the text in a single pass, providing efficient pattern matching.
2. `Knuth-Morris-Pratt.c` :
- This is the implementation file for the Knuth-Morris-Pratt(KMP) String Matching Algorithm.
- It preprocesses the pattern to create a longest prefix suffix array, which helps to avoid unnecessary character comparisons during the search phase.
- This improves the overall efficiency by ensuring the text is scanned only once without backtracking.
3. `Naive-String-Matcher.c` :
- This is the implementation file for the Naive String Matching Algorithm.
- It compares the pattern with the text character by character at every possible position in the text.
- Although simple and easy to implement, this algorithm has a higher time complexity in the worst case compared to optimized string matching algorithms like KMP and Finite Automaton.
4. `Rabin-Karp-Algorithm.c` :
- This is the implementation file for the Rabin-Karp String Matching Algorithm.
- It uses a hashing technique to compare the hash value of the pattern with the hash values of substrings of the text.
- This algorithm is particularly efficient for detecting multiple pattern occurrences in a text.
5. `String-Matching-Algorithms.pptx` :
- This presentation provides an overview of various string matching algorithms, including Naive, Rabin-Karp, Finite Automaton, Knuth-Morris-Pratt (KMP), and Suffix Trees.
- It covers their problem statements, working principles, time complexities, and illustrative examples.
6. `Suffix-Trees.cpp` :
- This is the implementation file for constructing a naive Suffix Tree for a given string.
- This suffix tree allows efficient pattern matching and substring operations once fully built.
## Real-Life Applications
- **Plagiarism Detection :** Comparing documents to find matching sequences of words or phrases.
- **DNA Sequence Analysis :** In bioinformatics, string matching is crucial for identifying specific gene sequences or patterns within long DNA strings.
## Credits :
- Chaitanya Nemmani
- Potla Naga Sai Prajith
- Kagita Meenakshi
- Reddy Roshni  
This project was completed as part of a team assignment in the course **MA2233 Data Structures and Applications Lab** under the guidance of **Prof. Vikas Krishnamurthy**.
