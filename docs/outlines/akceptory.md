# Deterministické konečnostavové akceptory (akceptory, kurz A, poradie 6)
Zdroj: Afja06_akceptory_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Konečnostavový akceptor [deterministic finite automaton, DFA] | M=(Q,Σ,qI,f,F) | p002 => dfn.konecnostavovy-akceptor
definition | Jazyk rozpoznávaný akceptorom [language recognized by an automaton] | L(M)={w : f*(qI,w)∈F} | p002 => dfn.jazyk-akceptora
example | Akceptor pre slová končiace na abb alebo obsahujúce abba |  | p003
definition | Ekvivalentné a k-ekvivalentné stavy akceptora [equivalent states of an acceptor] | 0-ekvivalencia podľa koncovosti | p004 => dfn.ekvivalentne-stavy-akceptora
theorem | Prenos tvrdení o ekvivalencii stavov na akceptory | lema 4.1, 4.2, veta 4.3 platia aj pre akceptory (k od 0) | p005 [proof: generated] => thm.ekvivalencia-stavov-akceptora
algorithm | Minimalizácia akceptora [DFA minimization] | začiatok rozkladu F a Q-F, potom ako pri automatoch s výstupom | p006 [proof: generated] => alg.minimalizacia-akceptora

USES (defined elsewhere)
- dfn.abeceda — Abeceda a symbol [alphabet, symbol] (téma gramatiky)
- dfn.jazyk — Jazyk [language] (téma gramatiky)
- dfn.rozsirene-funkcie — Zovšeobecnené funkcie f* a g* [extended transition and output function] (téma automaty-vystup)
- dfn.dosiahnutelny-stav — Dosiahnuteľný stav [reachable state] (téma nedosiahnutelne)
- dfn.ekvivalentne-stavy — Ekvivalentné stavy [equivalent states] (téma ekv-stavy)
- thm.lema-4-1-ekvivalencie — Lema 4.1: ekvivalencia a k-ekvivalencia sú ekvivalencie (téma ekv-stavy)
- thm.lema-4-2-monotonnost — Lema 4.2: monotónnosť k-ekvivalencie a charakterizácia ekvivalencie (téma ekv-stavy)
- thm.veta-4-3-rekurzia-k-ekvivalencie — Veta 4.3: (k+1)-ekvivalencia pomocou k-ekvivalencie a nasledovníkov (téma ekv-stavy)
- alg.rozklad-ekvivalentnych-stavov — Rozklad na triedy ekvivalentných stavov [partition refinement] (téma ekv-stavy)
- alg.odstranenie-nedosiahnutelnych — Odstránenie nedosiahnuteľných stavov (téma nedosiahnutelne)
