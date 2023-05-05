Download Link: https://assignmentchef.com/product/solved-cse311-homework-2
<br>
1.     A Bit SameyProve the following assertions using logical equivalences.

(Feel free to use this web site to complete the problem. After creating an account, click on “CSE 311 HW1″ to create a new project that is preloaded with a file for each of the parts below. When you complete all three parts, click on the ” X ” to close the project, click on the ” … ” next to the project name, and select “Download” to save your solution as a zip file. You can submit that solution in canvas.)

(a)     p ∧ (p → q) ≡ p ∧ q.

(b)     ((p ∧ q) ∨ (p → (¬p ∧ r))) ∨ p ≡ T.

(c)     p → (q → r) ≡ q → (p → r).

2.     Two of a Kind(a) [2 Points] Translate the Boolean Algebra expression ((X0 +Y )·(Z0 +Y 0))0 +(Z0 +X0) to Propositional Logic. Use the variables p, q, and r to represent the propositions X = 1, Y = 1, and Z = 1, respectively. (b) [16 Points] Prove that your solution to (a) is a tautology using a chain of equivalences.

(Feel free to use this tool to check that your solution is correct. You can also take a screenshot of your completed solution in the tool and include it in your submission rather than writing out it by hand.) (c) [2 Points] Why do we know that the Boolean Algebra expression from part (a) is always 1? Explain.

3.     One-Two PunchIn lecture 4, we constructed a circuit to compute the number of classes (lectures or sections) remaining on a given day of the week. That circuit had four outputs (c0, c1, c2, c3) to indicate 0, 1, 2, or 3. In this problem, we construct a circuit that has only two outputs, (s1s0)2, that give the same output but as a binary number.

(a)      Write a table showing the values for s1 and s0 in each possible case of the input values

(d2,d1,d0,L).

(b)    Write s1 in either product-of-sums form or sum-of-products form. (Your choice.)

(c)     Write s0 in whichever form (product-of-sums or sum-of-products) you did not use in part (b).

4.     Pardon My FrenchLet the domain of discourse be people in France. Let’s define the predicates Francophone(x) and Anglophone(x) to mean that x is a French speaker or an English speaker, respectively. Define the predicates French(x), Parisian(x), and Tourist(x) to mean that x is French, lives in Paris, or is a tourist, respectively.

Translate each of the following logical statements into English. You should not simplify. However, you should use the techniques shown in lecture for producing more natural translations when restricting domains and for avoiding the introduction of variable names when not necessary.

(a)      ∀x(Parisian(x) → (French(x) ∨ Tourist(x)))

(b)     ∃x(Anglophone(x) ∧ Tourist(x) ∧ ¬Francophone(x))

(c)       (Parisian(x)∧¬Tourist(x)) → French            French(x) → (Parisian(x)∨Tourist

(d)      Tourist(x) ∧ ¬(Francophone(x) ∨ Anglophone  Parisian

5.     A Lot to Unpack ThereLet the domain of discourse be people on vacation and their belongings. We define the predicates Vacationer(x) and Belonging(x) to mean that x is a person on vacation or the belonging of some person, respectively. We also define the predicate Packed(x,y) to mean that x is a vacationer that packed belonging y to bring with them on vacation. Finally, we define a predicate Identical(x,y), which is true iff x and y are identical belongings. You can also assume an “=” operator that is true when x and y are the same people or same object. Translate each of the following English statements into predicate logic. Do not simplify.

(a)     Everything that was packed by someone is a belonging.

(b)     Kim packed two identical things but nothing Kanye packed is identical to either of those. (Use the constants “Kim” and “Kanye” to refer to those two vacationers.) (c) [4 Points] No two vacationers packed anything identical.

(d) Some vacationer packed only two things.

6.     Beyond CompareThe questions below consider the two propositions

∀x(P(x) → Q(x)) and (∀xP(x)) → (∀xQ(x))

where P and Q are predicates.

(a)     Give examples of predicates P and Q and a domain of discourse so that the two propositions are not equivalent.

(b)    Give examples of predicates P and Q and a domain of discourse so that they are equivalent.

(c)      Extra credit: What logical relationship holds between these two propositions? Explain.

7.     Extra Credit: Shiver Me TimbersFive pirates, called Ann, Brenda, Carla, Danielle and Emily, found a treasure of 100 gold coins. On their ship, they decide to split the coins using the following scheme:

•     The first pirate in alphabetical order becomes the chief pirate.

•     The chief proposes how to share the coins, and all other pirates (excluding the chief) vote for or against it.

•     If 50% or more of the pirates vote for it, then the coins will be shared that way.

•     Otherwise, the chief will be thrown overboard, and the process is repeated with the pirates that remain.

Thus, in the first round Ann is the chief: if her proposal is rejected, she is thrown overboard and Brenda becomes the chief, etc; if Ann, Brenda, Carla, and Danielle are thrown overboard, then Emily becomes the chief and keeps the entire treasure.

The pirates’ first priority is to stay alive: they will act in such a way as to avoid death. If they can stay alive, they want to get as many coins as possible. Finally, they are a blood-thirsty bunch, if a pirate would get the same number of coins if she voted for or against a proposal, she will vote against so that the pirate who proposed the plan will be thrown overboard.

Assuming that all 5 pirates are intelligent (and aware that all the other pirates are just as aware, intelligent, and bloodthirsty), what will happen? Your solution should indicate which pirates die, and how many coins each of the remaining pirates receives.