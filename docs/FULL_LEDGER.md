# Full closed-claims table (56)

Author: Benjamin Stanley Frohman (@BenFrohman)
Copyright (c) 2026 Benjamin Stanley Frohman. Apache-2.0.
CSV: tables/full_ledger.csv

Closed means computed or classified on disk. Term A and Term B are not rows.
Novelty grades: **new-here** (this program locked the integer or the distinction), **classical** (standard theorem applied), **hygiene** (correct statement of what is not proved).

## How to read novelty

The scientific payload of the program is classification of one invertible chain atom
W = u^5 v + v^6 and its three-block sum F = W ⊕ W ⊕ W, which defines the locked
sextic fourfold X = V(F) ⊂ P^5. Almost every closed claim is bookkeeping of that
atom so that |det A| = 30 is never again called μ, so that 31/35 are never again
called μ, and so that [Π] and [S] are never again called a Hodge miss.
Nothing in the table is a Clay close.

## A. Atom W and W^T (1–18)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 1 | ǀdet Aǁ = ǀAut(W)ǁ = 30, not μ | Diagonal symmetry of W = u^5v+v^6 | Stops calling the group order a Jacobian dimension | new-here as a locked split; Aut order itself is classical for invertible germs | det of exponent matrix A = [[5,1],[0,6]] | BHK dual group, FJRW state-space rank, Gepner/LG orbifolds |
| 2 | μ(W) = 25 = dim Jac(W) | Isolated plane-curve germ | Input rank of FJRW / Jacobian ring of one block | classical Milnor; locked here after the v^{11} trap | weights (1,1), deg 6: (6-1)^2; Groebner LTs v^6,u^5,u^4v; 4·6+1 monomials | FJRW of the chain; Thom–Sebastiani cubes |
| 3 | μ(W^T) = 26 | Transpose germ u^5+uv^6 | Dual Jacobian rank; Fan–Shen other side | classical Milnor–Orlik; locked here | weights (3,2), deg 15: 4·(13/2); LTs u^4,uv^5,v^{11} | Krawitz FJRW(W,Aut) ≅ Jac(W^T) |
| 4 | LTs of W: v^6, u^5, u^4v | Groebner / standard monomials of W | Makes the 25-count reproducible | new-here as an explicit list | grlex/grevlex of ∂W; Euler puts v^6 in the ideal | Any computer-algebra walk of this germ |
| 5 | LTs of W^T: u^4, uv^5, v^{11} | Groebner of ∂W^T | Third LT is the missing wall | new-here emphasis | identity v^5(5u^4+v^6)-5u^3(uv^5)=v^{11} | Prevents unbounded walks in v |
| 6 | That v^{11} identity | Ideal membership, order-independent | Proves v^{11} is in (∂W^T) without trusting one Groebner print | new-here as the written identity | polynomial arithmetic | Explains why grlex hides a power of v |
| 7 | 25 standard monomials of W | Jac(W) basis | Explicit vector-space basis | classical count; listed here | {1,u,u^2,u^3}×{1..v^5} ∪ {u^4} | Residue pairing, 42 triples |
| 8 | 26 standard monomials of W^T | Jac(W^T) basis | Dual basis | classical; listed here | {v^0..v^{10}} ∪ {u,u^2,u^3}×{v^0..v^4} | Krawitz target |
| 9 | ĉ(W)=ĉ(W^T)=4/3 | LG central charge | BHK invariant that *is* preserved | classical for invertible polynomials | weighted degree formula | CY condition for three-block F (ĉ=4) |
| 10 | Inner modality 6 (W) and 5 (W^T) | Arnold classification | Shows the germ is not simple | computed here from weighted Jacobian degrees ≥ d | monomials of weight ≥ 6 (W) / ≥ 15 (W^T) | Deformation theory; not ADE |
| 11 | Six lines; moduli 6-3=3 | W=v(u^5+v^5) ⊂ C^2 | Geometric picture of μ=25 | classical for line arrangements; recorded | six distinct linear factors | Link is six unknots in S^3; monodromy Δ_W |
| 12 | Not ADE | Arnold simple list μ≤8, modality 0 | Blocks a false ADE label | hygiene | compare μ and modality to ADE table | Strange duality / simple singularities do not apply raw |
| 13 | BHK keeps Aut and ĉ, not μ or modality | Transpose W ↔ W^T | Tells what mirror symmetry of this pair actually preserves | classification | compare the two columns of the μ/Aut/ĉ table | LG/CY, FJRW dual, not FM partner Y |
| 14 | F=+1 is W→W^T (μ:25→26) | Direction of BHK arrow | Names one reading of “F=+1” | hygiene | transpose of exponent matrix | Dual LG model |
| 15 | F=-1 is reverse arrow and fiber W=-1 (25 circles) | Milnor fibration | Names the other reading; sign of the polynomial does not change μ | hygiene | definition of Milnor fiber | Bouquet of μ circles; suspension W+z^2 |
| 16 | Spectrum of W, multiplicities 1,2,3,4,5,4,3,2,1 | Steenbrink numbers k/6 | Input to monodromy characteristic polynomial | computed here from weights | spectral numbers of the 25 monomials | Δ_W, tt* charges, FJRW ages |
| 17 | Δ_W(t)=(t-1)^5(t+1)^4(t^2+t+1)^4(t^2-t+1)^4 and ζ̃_W | Monodromy on H_1 of the fiber | Explicit zeta of this atom | computed here from the spectrum | product over exp(2πiα) | EGZ duality is *named*, not identified for this pair |
| 18 | 26 spectral numbers of W^T; 31/35 excluded | Dual spectrum; incomplete box walks | Locks μ=26; archives the trap | new-here as a ban | full LT list vs cutoff J+15 | Reproducibility of computer-algebra labs |

## B. Three-block F (19–28)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 19 | μ(F)=25^3=15625 | Jac(F) of the locked sextic | Dimension of the B-model Jacobian | Thom–Sebastiani classical; cube locked here | product of Milnor numbers | Griffiths ring of V(F) |
| 20 | ǀAut(F)ǁ=30^3=27000 | Maximal diagonal group of F | Order of G_max | product of groups | Aut(W)^3 | Krawitz problem Aut, dim 17576 on the dual |
| 21 | ĉ(F)=4 | Three-block sum | CY fourfold charge | sum of charges | 4/3+4/3+4/3 | LG/CY of a Calabi–Yau fourfold, not heterotic c=9 |
| 22 | Jac(F) ≅ Jac(W)^{\otimes 3} | Algebra of F | Factors the Jacobian, not the FJRW virtual class | Thom–Sebastiani | tensor of Jacobian algebras | Identity-sector 3-points factor; correlators of F do not |
| 23 | 42 triples of W, values in {1,-6} | Residue pairing on Jac(W), socle u^3v^5 | Structure constants of one block | computed here | coeff of u^3v^5 in abc after u^5=-6v^5 | Seed of any reconstruction of the identity sector |
| 24 | Pure-tensor product formula | Identity-sector 3-points of Jac(F) | Multiplies the 42 across three blocks | algebra of a tensor product, not a theorem about spin moduli | ⟨a1⊗a2⊗a3,…⟩=∏ ⟨ak,bk,ck⟩_W | Does *not* give mixed-sector FJRW(F,⟨J⟩) |
| 25 | dim Jac(F)^J=2605, Hilbert (1,426,1751,426,1) | J_F-invariants in deg 0,6,12,18,24 | Size of the primitive B-model | arithmetic of this F | degree 0 mod 6 in Jac(W)^{\otimes 3} | Must match Griffiths diamond if F is a smooth sextic |
| 26 | Equals primitive Hodge of a smooth sextic fourfold | Any smooth X_6 ⊂ P^5 | Consistency check | classical Griffiths 1968–69; this lab only checks the dimensions match | residue isomorphism R_{6k} ≅ H^{4-k,k}_prim | Not an extra rational Hodge class |
| 27 | h^{2,2}=1752, b_4=2606 | Full Hodge numbers | +1 is ω^2, algebraic | classical; recorded | 1751+1 and 2605+1 | Lefschetz class, not a miss |
| 28 | Fan–Shen labels (p,q)=(5,6), gcd(4,6)=2 | Chain atom of type X^5Y+Y^6 | Places W in the non-coprime Fan–Shen case | citation | read p,q off the exponents | Ring comparison FJRW(W^T) vs Jac(W) is that paper, structure constants not expanded here |

## C. FJRW sectors (29–36)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 29 | ⟨J⟩ splits: broad 2605 + five narrow of dim 1 | FJRW(F,⟨J⟩) state space | Sector skeleton | computed from fixed loci of J^k | J scales all six coords by ζ_6; Fix(J^k)={0} unless 6∣k | Chiodo–Ruan LG/CY |
| 30 | Total 2610 = dim H^\u2022(V(F)) | State space vs cohomology | Dimension match | expected under LG/CY | 2605+5 and 1+1+2606+1+1 | Not a proof of Hodge |
| 31 | Five narrow states = Lefschetz line 1,ω,ω^2,ω^3,ω^4 | Narrow sectors J^k | They are algebraic; not a miss | identification, not a new class | age(J^k)=k ↔ ω^{k-1} | Rules out using e_k as Term B |
| 32 | Selection a+b+c ≡ 1 mod 6 | Primary genus-zero 3-points of (F,⟨J⟩) | Vanishing rule | standard FJRW decoration | decorations multiply to J | Cuts the table before any virtual-class integral |
| 33 | Narrow pairing/string; ∫ω^4=6 | Dual narrow sectors | Axiom-fixed numbers only | geometric degree of a sextic | string equation + Poincaré on P^5 | Not a Guéré integral |
| 34 | Krawitz is G_max: FJRW(W,Aut)≅Jac(W^T) dim 26; candidate for F dim 17576 | Maximal group | Names the other FJRW problem | citation | Krawitz 2009 | Separate from ⟨J⟩ |
| 35 | Guéré applies to the atom, not to F as a product | Chain Hodge integrals | Tells which formula can be run | reading of Guéré | N=2 chain a1=5,a2=6; F is three disjoint paths | Open: run the numbers; still not Term B |
| 36 | Aut(F) and ⟨J⟩ are two rings | Two admissible groups | Prevents mixing tables | hygiene | orders 27000 vs 6; dims 17576 vs 2610 | Two research problems, not one |

## D. Locked host X=V(F) (37–44)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 37 | X=V(F) named | Term B field 1 only | A concrete CY fourfold | the host of the program | F written as three chain blocks in P^5 | Hodge, derived partners, LG/CY |
| 38 | Residual cut Π ∪ S | Linear sections of X | Extra surfaces on a special host | geometry of this F | X ∩ L_{a,b,c} = Π ∪ S_{a,b,c} | Named-host algebraicity |
| 39 | [Π] and [S]=h^2-[Π] algebraic | Hdg^2(X) | They *hit* im(cl) | computed cycle classes | residual theorem + Lefschetz | Cannot be Term B |
| 40 | S has dim 2, not Y | Derived categories | Stops mistaking the residual quintic for a fourfold partner | hygiene | objectDim=2 vs hostDim=4 | Bondal–Orlov on S; D^b(X) still has no written Y |
| 41 | Bondal–Orlov reconstructs S | D^b(S) | No partner surface | classical; applied | K_S ≈ O_S(1) ample | Reconstruction vs partners |
| 42 | Partner fourfold allowed; none written | D^b(X), K_X trivial | Permission is not equations | hygiene | Bondal–Orlov fails when ω≈O | Six-field Y stays empty |
| 43 | F^T is a BHK string, not an FM kernel | Mirror candidate V(F^T)/G^T | Names the right mirror slot | classification | transpose of the three blocks | LG/CY and HMS of potentials, not Φ_E |
| 44 | Named-host sections finite, not ∀D | Hodge on a list | Honest scope of named_fourfolds | hygiene | finite conjunction | Row 6 / Term A still open |

## E. Hygiene (45–48)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 45 | Hodge is Π; missing B is not a proof of A | Clay problem type | Blocks a category error | hygiene | logic of ∀ vs ∃ | Term A / Term B |
| 46 | zeroCycle is a gadget, not Clay | Lean Datum with cl=0 on Rat | Blocks a fake kernel check | hygiene | type vs geometry | Formalization of Hodge |
| 47 | Leftover is Hdg^2=H^4 ∩ H^{2,2} | Fourfolds after Lefschetz (1,1) and Hard Lefschetz | Puts the open piece on the right space | classical reduction; recorded | primitive (2,2) ≅ remaining Hodge | Term A/B statements |
| 48 | Lean μ=25 and 26, no sorry | MilnorCount.lean | Kernel-checked monomial counts | certificate | native_decide on staircase lengths | Reproducible integers |

## F. Today (49–56)

| # | What it is | Where it applies | Usefulness | Novelty | Derived how | Ties into |
|---|---|---|---|---|---|---|
| 49 | Lean cubes, Hilbert sum, extras, 31/35/30 ≠ μ | LedgerIntegers.lean | Kernel-checked arithmetic of the diamond | certificate | native_decide | Same as 19–27, now machine-checked |
| 50 | Pairings 5,-20,25 | Intersection matrix of {h^2,[Π]} | Shows [S] is in the written span | computed on this host | expand [S]=h^2-[Π] | No new Hodge direction |
| 51 | Rank-2 algebraic span vs rank-1 general | Special vs very general sextic | Extra algebraicity, not extra miss | Noether–Lefschetz classical; rank 2 on this F recorded | plane on V(F) vs monodromy of a general sextic | Row 4 on this host still needs rk Hdg^2 |
| 52 | Rows 4 and 5 exclusive on this host | Hodge vs miss on V(F) | Logical lock | hygiene | L ⟷ Δ_miss=∅ | Cannot inhabit both |
| 53 | Rows 5 and 6 exclusive in mathematics | Term B vs Term A | Logical lock | hygiene | a statement and its negation | Clay |
| 54 | Sector chart 2605+5 Lefschetz | FJRW(F,⟨J⟩) | Visual of claim 29–31 | presentation | same as 29–31 | LG/CY |
| 55 | Narrow survivors and ∫ω^4=6 | Genus-zero narrow 3-points | Axiom-fixed slice | presentation | selection + degree of X | Not mixed-sector numbers |
| 56 | Mixed slots stay OPEN | Virtual class on F-spin moduli | Prevents fake 0/1/6 fills | hygiene | Guéré is one chain; Krawitz is G_max | The actual remaining FJRW computation |

## What this moves, and what it does not

Moves forward, in a bookkeeping sense:
- invertible-chain computer algebra (the v^{11} trap is now a written identity);
- FJRW setup for the exact Fan–Shen block (5,6) with gcd=2;
- a named CY fourfold whose Jacobian dimensions match the textbook sextic diamond;
- a clean split of two groups ⟨J⟩ vs Aut(F);
- a clean split of algebraic classes [Π],[S] from any miss class.

Does not close:
- Term A (Hodge as a theorem);
- Term B (Hodge as false);
- a Fourier–Mukai partner Y;
- Guéré numbers on this atom;
- mixed-sector 3-points of (F,⟨J⟩);
- Saito dual zeta as an identity;
- strange duality in six variables.
