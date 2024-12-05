java c
Phi 012/Intro to Symbolic Logic
Writing proofs in Carnap
Three pieces of advice on writing proofs in Carnap:
1. Entering proofs into Carnap can definitely be tricky. If you’re having difficulty have a read through the instructions and have a go at the examples here: https://carnap.io/assignments/UC%20Davis%20PHI012%20Fall%202024/Practice%20Problems%20IV.md
2. In Carnap a line will get a + next to it once you have entered a correct justification. If the justification is incorrect, you’ll get a ? (or a ! in a triangle) or a ✗. Carnap will try to tell you what’s wrong: hover the cursor over the ? or ✗ to see a hint.
3. Remember Carnap is a mindless machine, and so you need to be very explicit about why each step in your derivation is justified. So remember your rules, and make sure that when you try to apply them that you’ve got the correct premises/subproofs etc for a correct rule application.
Some common problems you may encounter while writing proofs are the following:
(a) Adding assumptions (including initial ass代 写Phi 012/Intro to Symbolic LogicSQL
代做程序编程语言umptions when you are proving that some sentence is a theorem): when you add an additional assumption, you have to start a new subproof. In Carnap, you start a new subproof by indenting the lines that make up the subproof (you can either use the tab key or the space bar for this):

(b) Sometimes, you will have to make additional assumptions inside a subproof, which means you will have nested subproofs. Whenever this happens, you just have to indent the lines of the new subproof:

(c) In some cases, you will have two consecutive subproofs, in particular when you are using ∨-Elimination or ↔-Introduction. To tell Carnap where one subproof ends and the next one starts, type -- on a line by itself. The -- should be indented the same amount as the sentences in the surrounding (sub)proof:

(d) Notice that when you are justifying a line using some rule, there must be no space between the colon ‘:’ and the rule cited. If you leave a space, Carnap won’t recognize the rule:




         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
