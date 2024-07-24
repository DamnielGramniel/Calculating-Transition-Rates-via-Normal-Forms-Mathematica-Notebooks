This is the Mathematica code used in my Master's thesis: Calculating Transition Rates via Quantum Normal Forms, completed at the University of Groningen, Faculty of Science and Engineering, van Swinderen Institute. The code was developed by Giovanni van Marion.

QNF Code: Program that puts the Hamiltonian, for any finite-dimensional mechanical system, in classical (or quantum) normal form.
          There is a version that (v1) that words near a minimum and one that that works near a saddle (v2).
          This second version of the program also computes the rate over the saddle by assuming that the minimum is completely harmonic (no interactions).
          It is also possible to use both program versions together to compute the rate for any system precisely.
          Utils.nb comprises the modules associated with calculating the normal form of the given Hamiltonian.

Adjustments made to the code include plot generation and all the specifics associated with that, as well as a quick fix to the v26 notebooks, that ensures the notebook runs for any even value of QNF order
(you will see "QNFOrd/2" in the code). AHO Modes was cloned from v26.2 just to have a separate notebook where one can test the effects of mode couplings.
