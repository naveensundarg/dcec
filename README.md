Deontic Cognitive Event Calculus
====


DCEC is a quantified modal logic that builds upon on the first-order Event Calculus (EC). EC has been used quite successfully in modelling a wide range of phenomena, from those that are purely physical to narratives expressed in natural-language stories.

EC is also a natural platform to capture natural-language semantics, especially that of tense; see (?). EC has a shortcoming: it is fully extensional and hence, as explained above, has no support for capturing intensional concepts such as knowledge and belief without introducing unsoundness or inconsistencies. For example, consider the possibil- ity of modeling changing beliefs with fluents. We can posit a “belief” fluent belief(a,f) which says whether an agent a believes another fluent f. This approach quickly leads to serious problems, as one can substitute co-referring terms into the belief term, which leads to either unsoundness or an inconsistency (see Figure 3 in (?)). One can try to overcome this using more complex schemes of belief encoding in FOL, but they all seem to fail. A more detailed discussion of such schemes and how they fail can be found in the analysis in.

*Overview Paper* http://www.cs.rpi.edu/~govinn/dcec.pdf

**Prover** https://github.com/naveensundarg/ShadowProver

**Real-time Parser (Controlled English)** https://github.com/naveensundarg/Eng-DCEC
