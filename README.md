This GAP code is prepared to construct Curtis-Tits and (pseudo) Phan systems for the groups of Lie type of odd characteristic. For a brief explanation of these systems, see “About_the_code.pdf” and the references in it for more detailed discussions.

In this GAP code, we consider black box groups encrypting one of the following classical groups defined over a field of odd characteristic with the size of the underlying field q > 5. In the items below, “…” means that all the intermediate subgroups and factor groups are considered. 

• PSL(n+1,q),…, SL(n+1,q) — group of type An, n>1.
• Sp(2n,q), PSp(2n,q) — group of type Cn, n>1.
• P(2n+1,q),…, SO(2n+1,q) — group of type Bn, n>1.
• P+(2n,q),…, SO+(2n,q) — group of type Dn, n>2.

Input: A list of generators of one of the groups of Lie type above and an exponent of the group. 

We use the order of the group for the exponent of the input.

Output: The output is the list of generators of subgroups isomorphic to (P)SL2 forming an extended Curtis-Phan-Tits system of the group.

The code can be run by the function call CPT("Generators of a group", "Exponent of the group").

For more information about the code, see “About_the_code.pdf”


