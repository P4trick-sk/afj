# Redukcia automatov III: korektnosť a optimálnosť (optimalnost, kurz A, poradie 5)
Zdroj: Afja05_redukcia_optim_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

theorem | Lema 5.1: korektnosť rozkladu na k-ekvivalentné stavy |  | p002-p003 [proof]
theorem | Lema 5.2: algoritmus rozkladu sa vždy zastaví |  | p004-p005 [proof] => thm.lema-5-2-zastavenie-rozkladu
theorem | Lema 5.3: výstup algoritmu je rozklad na plne ekvivalentné stavy |  | p006-p008 [proof] => thm.lema-5-3-korektnost-rozkladu
theorem | Veta 5.4: automat po odstránení ekvivalentných stavov je ekvivalentný s pôvodným |  | p009-p010 [proof] => thm.veta-5-4-redukcia-zachovava-ekvivalenciu
definition | Izomorfizmus automatov [isomorphism of automata] | bijekcia stavov zachovávajúca počiatočný stav, f aj g | p011 => dfn.izomorfizmus-automatov
theorem | Veta 5.5: ekvivalentné automaty bez nedosiahnuteľných a ekvivalentných stavov sú izomorfné |  | p011-p015 [proof] => thm.veta-5-5-izomorfizmus
theorem | Dôsledok 5.6: automat bez nedosiahnuteľných a ekvivalentných stavov je optimálny |  | p016 [proof] => thm.dosledok-5-6-optimalnost
algorithm | Testovanie ekvivalencie dvoch automatov | disjunktné zjednotenie a rozklad | p017 [proof: generated] => alg.test-ekvivalencie-automatov

USES (defined elsewhere)
- dfn.k-ekvivalentne-stavy — k-ekvivalentné stavy [k-equivalent states] (téma ekv-stavy)
- thm.veta-4-3-rekurzia-k-ekvivalencie — Veta 4.3: (k+1)-ekvivalencia pomocou k-ekvivalencie a nasledovníkov (téma ekv-stavy)
- thm.lema-4-2-monotonnost — Lema 4.2: monotónnosť k-ekvivalencie a charakterizácia ekvivalencie (téma ekv-stavy)
- alg.rozklad-ekvivalentnych-stavov — Rozklad na triedy ekvivalentných stavov [partition refinement] (téma ekv-stavy)
- alg.odstranenie-ekvivalentnych-stavov — Odstraňovanie ekvivalentných stavov (téma ekv-stavy)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
