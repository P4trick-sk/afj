# Redukcia automatov II: ekvivalentné stavy (ekv-stavy, kurz A, poradie 4)
Zdroj: Afja04_redukcia_ekviv_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Ekvivalentné stavy [equivalent states] | rovnaký výstup na každom vstupnom slove | p002 => dfn.ekvivalentne-stavy
definition | k-ekvivalentné stavy [k-equivalent states] | rovnaký výstup na slovách dĺžky najviac k | p002 => dfn.k-ekvivalentne-stavy
concept | Prečo k-ekvivalencia | ekvivalenciu nemožno overiť priamo, k-ekvivalenciu áno | p003 [supplement] => def.motivacia-k-ekvivalencie
theorem | Lema 4.1: ekvivalencia a k-ekvivalencia sú ekvivalencie |  | p004 [proof] => thm.lema-4-1-ekvivalencie
theorem | Lema 4.2: monotónnosť k-ekvivalencie a charakterizácia ekvivalencie |  | p005 [proof] => thm.lema-4-2-monotonnost
theorem | Veta 4.3: (k+1)-ekvivalencia pomocou k-ekvivalencie a nasledovníkov |  | p006-p008 [proof] => thm.veta-4-3-rekurzia-k-ekvivalencie
definition | Rozklad stavov na triedy k-ekvivalencie [partition into k-equivalence classes] |  | p009-p010 => dfn.rozklad-stavov
algorithm | Rozklad na triedy ekvivalentných stavov [partition refinement] | krok 1 podľa výstupov, krok 2 podľa nasledovníkov, zastavenie pri zhode | p011 [proof: generated] => alg.rozklad-ekvivalentnych-stavov
algorithm | Odstraňovanie ekvivalentných stavov | reprezentanti tried, presmerovanie hrán | p012 [proof: generated] => alg.odstranenie-ekvivalentnych-stavov
example | Redukcia automatu: triedy 1-, 2- a 3-ekvivalencie |  | p013-p014

USES (defined elsewhere)
- dfn.konecnostavovy-automat — Konečnostavový automat s výstupom [finite-state machine with output, Mealy machine] (téma automaty-vystup)
- dfn.rozsirene-funkcie — Zovšeobecnené funkcie f* a g* [extended transition and output function] (téma automaty-vystup)
- def.ekvivalencia-rozklad — Ekvivalencia a rozklad množiny [equivalence relation, partition] (téma gramatiky)
- dfn.ekvivalentne-automaty — Ekvivalentné automaty [equivalent automata] (téma nedosiahnutelne)
