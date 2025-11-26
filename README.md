I cannot directly create or upload a downloadable .doc or .docx file for you. However, I have formatted the entire set of questions and answers below into a clean, copy-paste friendly format.
You can copy the text between the horizontal lines below and paste it directly into Microsoft Word or Google Docs to save it as your study material file.

Unit II: Relations and Counting Principles - Question Bank Solutions
Section 1: Theoretical Concepts (2 Marks)
Q1: Define Reflexive, Symmetric, and Transitive relations with examples.
Reflexive Relation: A relation $R$ on a set $A$ is reflexive if every element is related to itself.
Mathematical Condition: $(a, a) \in R$ for all $a \in A$.
Example: On set $A=\{1, 2\}$, $R = \{(1,1), (2,2), (1,2)\}$ is reflexive because $(1,1)$ and $(2,2)$ are present1111.
Symmetric Relation: A relation is symmetric if for every pair $(a,b)$ in the relation, the reverse pair $(b,a)$ is also present.
Mathematical Condition: If $(a, b) \in R$, then $(b, a) \in R$.
Example: $R = \{(1,2), (2,1)\}$ is symmetric222.
Transitive Relation: A relation is transitive if a connection from $a$ to $b$ and $b$ to $c$ implies a connection from $a$ to $c$.
Mathematical Condition: If $(a, b) \in R$ and $(b, c) \in R$, then $(a, c) \in R$.
Example: If $a$ is taller than $b$, and $b$ is taller than $c$, then $a$ is taller than $c$333.
Q2: Define a symmetric relation.
A binary relation $R$ on a set $A$ is called symmetric if the relationship applies in both directions. Mathematically, for all elements $a, b \in A$, if $aRb$ holds, then $bRa$ must also hold4.
Matrix Property: In terms of a relation matrix $M_R$, the relation is symmetric if the matrix equals its transpose ($M_R = M_R^T$)5.
Q3: What is the difference between a permutation and a combination?
Feature
Permutation
Combination
Concept
Arrangement / Ordering 6
Selection / Grouping 7
Order
Order matters (e.g., Rank, Positions)
Order doesn't matter (e.g., Teams)
Example
Password "123" $\neq$ "321"
Fruit salad "Apple, Banana" = "Banana, Apple"
Formula
$P(n,r) = \frac{n!}{(n-r)!}$ 8
$C(n,r) = \frac{n!}{r!(n-r)!}$ 9

Q4: What is an Equivalence relation? Explain properties of binary relations.
Equivalence Relation: A relation is an equivalence relation if it satisfies three specific properties simultaneously: Reflexive, Symmetric, and Transitive10.
Properties of Binary Relations:
Reflexive: Every element relates to itself11.
Symmetric: Relations are bidirectional12.
Antisymmetric: If $aRb$ and $bRa$, then $a$ must equal $b$ (used in partial ordering)13.
Transitive: Relations chain together ($a \to b \to c \implies a \to c$)14.

Section 2: Analytical Questions (4 Marks)
Q5: Given the relation $R=\{(a,a), (b,b), (c,c), (d,d), (a,b), (b,d), (a,d), (d,b), (d,a)\}$. Draw the digraph of the relation.
To construct the graph:
Vertices: The set is $\{a, b, c, d\}$.
Self-Loops: Every vertex has a self-loop (e.g., $a \to a$, $b \to b$) because the relation is reflexive.
Connections:
$a$ connects to $b$ and $d$.
$b$ connects to $d$.
$d$ connects to $b$ and $a$.
$c$ is isolated (only connected to itself).
Visualization: Draw 4 circles labeled a-d. Add loops to all 4. Draw arrows according to the list above. Note that $a$ and $d$ share a two-way connection ($a \leftrightarrow d$), and $b$ and $d$ share a two-way connection ($b \leftrightarrow d$).
Q6: Let $R = \{(1,1), (1,2), (2,1), (2,2), (3,3)\}$ on $\{1, 2, 3\}$. Determine if R is reflexive, symmetric, and/or transitive.
Reflexive: Yes. The set contains $(1,1), (2,2), (3,3)$, covering all elements15.
Symmetric: Yes. We have $(1,2)$, and its reverse $(2,1)$ is present. The pairs $(1,1), (2,2), (3,3)$ are their own reverses16.
Transitive: Yes. We check the paths:
$(1,2)$ and $(2,1)$ $\to$ requires $(1,1)$ (Present).
$(2,1)$ and $(1,2)$ $\to$ requires $(2,2)$ (Present).
Conclusion: Since it is Reflexive, Symmetric, and Transitive, it is an Equivalence Relation17.
Q7: How many bit strings of length 8 bits can be constructed which will either start with '0' or end with '11'?
Use the Inclusion-Exclusion Principle: $|A \cup B| = |A| + |B| - [cite_start]|A \cap B|$18.
Starts with '0' (Set A): Format 0 _ _ _ _ _ _ _. 1 fixed bit, 7 free bits.
Count = $2^7 = 128$.
Ends with '11' (Set B): Format _ _ _ _ _ _ 1 1. 2 fixed bits, 6 free bits.
Count = $2^6 = 64$.
Starts with '0' AND Ends with '11' (Intersection): Format 0 _ _ _ _ _ 1 1. 3 fixed bits, 5 free bits.
Count = $2^5 = 32$.
Calculation: $128 + 64 - 32 = 160$.
Answer: 160 strings.
Q8: Which relations on integers contain the pairs (1,1), (1,2), (2,1), (1,-1), and (2,2)?
$R1 (a \le b)$: Contains $(1,2)$. Fails $(2,1)$19.
$R2 (a > b)$: Contains $(2,1)$. Fails $(1,2)$20.
$R3 (a = \pm b)$: Contains $(1,1), (2,2), (1,-1)$. Fails $(1,2)$21.
$R5 (a = b+1)$: Contains $(2,1)$. Fails $(1,1)$22.
$R6 (a+b \le 3)$: Contains $(1,1), (1,2), (2,1), (1,-1)$. Fails $(2,2)$ because $2+2=4 \not\le 3$23.
Conclusion: No single relation listed contains all pairs. $R6$ is the closest match (4 out of 5).
Q10: Find the number of permutations that can be made out of the letters:
Formula: $\frac{n!}{n_1! n_2! [cite_start]\dots}$ (Permutation with repetition)24.
i) Mississippi:
Total ($n$) = 11. Counts: M=1, I=4, S=4, P=2.
Calculation: $\frac{11!}{4! 4! [cite_start]2!} = \frac{39,916,800}{24 \times 24 \times 2} = \mathbf{34,650}$25252525.
ii) Assassination:
Total ($n$) = 13. Counts: A=3, S=4, I=2, N=2, T=1, O=1.
Calculation: $\frac{13!}{3! 4! 2! [cite_start]2!} = \frac{6,227,020,800}{6 \times 24 \times 2 \times 2} = \mathbf{10,810,800}$26.

Section 3: Detailed Problem Solving (6 Marks)
Q9: Let $A=\{1,2,3,4\}$ and R be "$(a,b) \in R$ if a divides b". Write R and determine properties.
Set R: Check divisibility for all pairs.
$R = \{(1,1), (1,2), (1,3), (1,4), (2,2), (2,4), (3,3), (4,4)\}$27.
Property Checks:
Reflexive: Yes. Every number divides itself ($a|a$ holds for all)28.
Symmetric: No. 1 divides 2, but 2 does not divide 129.
Antisymmetric: Yes. If $a|b$ and $b|a$, then $a$ must be equal to $b$. No distinct pair reverses30.
Transitive: Yes. If $a|b$ and $b|c$, then $a|c$ (e.g., $1|2$ and $2|4 \implies 1|4$)31.
Conclusion: The relation is a Partial Order Relation (Poset)32.
Q11: In how many ways can a 5-card poker hand be dealt that contains exactly 3 aces?
Step 1: Choose 3 Aces from the 4 available.
$C(4, 3) = \frac{4!}{3!1!} = 4$ ways33.
Step 2: Choose the remaining 2 cards from the 48 non-ace cards.
$C(48, 2) = \frac{48 \times 47}{2} = 1,128$ ways34.
Step 3: Apply Product Rule.
Total = $4 \times 1,128 = \mathbf{4,512}$ ways35.
Q12: How many number plates can be formed by 4 digits (from 1-9) followed by 3 letters? (No repetition)
Step 1: Arrange 4 distinct digits from the set $\{1..9\}$ ($n=9$).
$P(9, 4) = 9 \times 8 \times 7 \times 6 = 3,024$36.
Step 2: Arrange 3 distinct letters from the alphabet ($n=26$).
$P(26, 3) = 26 \times 25 \times 24 = 15,600$37.
Step 3: Total Plates (Product Rule).
$3,024 \times 15,600 = \mathbf{47,174,400}$38.
Q13: Find the transitive closure of the relation (based on the diagram).
Assumption: The nodes $a, b, c, d$ form a connected cycle (e.g., $a \to b \to c \to d \to a$).
Logic: In a transitive closure, if you can travel from node $X$ to node $Y$ through any number of steps, the pair $(X, Y)$ is added39.
Result: In a cycle, every node can reach every other node. Thus, the transitive closure is the Universal Relation containing all 16 possible pairs:
$R^* = \{(a,a), (a,b), (a,c), (a,d), \dots, (d,d)\}$40.
Q14: Committee of 5 from 7 men and 6 women, with at least 3 men.
Sum of valid cases (Men $\ge$ 3)41:
3 Men, 2 Women: $C(7,3) \times C(6,2) = 35 \times 15 = 525$42.
4 Men, 1 Woman: $C(7,4) \times C(6,1) = 35 \times 6 = 210$43.
5 Men, 0 Women: $C(7,5) \times C(6,0) = 21 \times 1 = 21$44.
Total: $525 + 210 + 21 = \mathbf{756}$ ways45.
Q15: A team of four selected from 6 boys and 4 girls. How many ways if at least one boy must be there?
Use "Total minus Invalid" method46.
Step 1: Total teams of 4 from 10 people ($6+4$).
$C(10, 4) = \frac{10 \times 9 \times 8 \times 7}{24} = 210$47.
Step 2: Teams with NO boys (All 4 are girls).
$C(4, 4) = 1$.
Step 3: Valid Teams.
$210 - 1 = \mathbf{209}$ ways.

Would you like me to generate a Python script to convert this text into a real .docx file for you?

