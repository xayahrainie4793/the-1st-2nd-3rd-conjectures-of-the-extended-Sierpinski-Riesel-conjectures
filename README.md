This research is from http://www.noprimeleftbehind.net/crus/Sierp-conjectures.htm and http://www.noprimeleftbehind.net/crus/Riesel-conjectures.htm, extended to the k such that gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not 1.

Sierpinski problem base b:
Finding and proving the smallest k such that gcd(k+1,b-1)=1 and k\*b^n+1 is not prime for all integers n>=1.

Riesel problem base b:
Finding and proving the smallest k such that gcd(k-1,b-1)=1 and k\*b^n-1 is not prime for all integers n>=1.

Extended Sierpinski problem base b:
Finding and proving the smallest k such that (k\*b^n+1)/gcd(k+1,b-1) is not prime for all integers n>=1.

Extended Riesel problem base b:
Finding and proving the smallest k such that (k\*b^n-1)/gcd(k-1,b-1) is not prime for all integers n>=1.

With this effort, we aim to prove many of the Riesel and Sierpinski conjectures for bases <= 32 and bases 64, 128, 256.

Project definition:

For every base (b) for the forms (k\*b^n+1)/gcd(k+1,b-1) and (k\*b^n-1)/gcd(k-1,b-1), there exists a unique value of k for each form that has been conjectured to be the 1st, 2nd, and 3rd lowest 'Sierpinski value' (+1 form) or 'Riesel value' (-1 form) that is composite for all values of n >= 1.

Goal:

Prove the conjectures by finding at least one (probable) prime (if only PRP, prove its primality) for all k lower than the 3rd lowest Sierpinski/Riesel value (except k equal to the 1st or 2nd Sierpinski/Riesel value). Many of the conjectures have already been proven but much more work is needed to prove additional bases. Proving them all is not possible but we aim to prove many of them.

* There are many conjectures where only ONE k needs a (probable) prime (and many more that need only two). If you find it, you could be the one to prove a conjecture! This is a big deal to us here.
* Algebraic factors have been found for many k's, which prove them composite for all n, allowing them to be removed from searches.

Notes:

All n must be >= 1.

k-values that make a full covering set with all or partial algebraic factors are excluded from the conjectures.

k-values that are a multiple of base (b) and where (k+-1)/gcd(k+-1,b-1) (+ for Sierpinski, - for Riesel) is not prime are included in the conjectures but excluded from testing.
Such k-values will have the same prime as k / b.

This project is to solve the 1st, 2nd, and 3rd Sierpinski/Riesel conjectures for bases b <= 32 and bases b = 64, 128, 256. (this project will be extended to bases b <= 1024 in future)
