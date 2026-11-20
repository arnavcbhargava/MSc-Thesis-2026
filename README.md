
# Learning from Graph Circuit Lower Bounds

Read the full thesis [here](thesis.pdf).


My master's thesis, supervised by Bruno Cavalar and Rahul Santhanam, studies pseudorandomness for graph circuits  (FORMULA \circ G with G being one-sided communication-cost 1 functions studied in [Jukna12], [Tal16] for example) and its connection to meta-complexity through the CIKK framework. The main contributions are:

**Natural Properties from Graph Circuit Lower bounds.** Using known lower bounds (Lokam'09) I extracted a natural property useful against graph circuits . Herein, a sign-rank lower bound implies a depth-3 graph circuit lower bound. Via Forster ‘02, sign-rank can be lower bounded through the spectral norm, which is easy to compute even though sign-rank itself is NP-hard.

**PRGs based on graph circuit hardness.** I constructed new combinatorial designs that exploit the structure of graph circuits, with both probabilistic and constructive existence proofs, generalising the greedy and polynomial-over-finite-fields constructions. Adapting the Nisan-Wigderson reconstruction argument gives a graph circuit hardness-based generator with low truth-table complexity, as CIKK requires. The stretch is tight for this method which was also shown.

**Implications for MCSP.** I formalised the search-to-decision reduction implied by the CIKK framework (differently to Hirahara'18).
