# ε-akceptory (eps-akceptory, kurz A, poradie 9)
Zdroj: Afja09_eps_akceptory_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | ε-akceptor [epsilon-NFA, NFA with epsilon transitions] | δ:Q×(Σ∪{ε})→2^Q, triviálne ε-prechody q→q | p002 => dfn.eps-akceptor
definition | Jazyk rozpoznávaný ε-akceptorom | rozklad slova na symboly a ε s postupnosťou stavov | p003 => dfn.jazyk-eps-akceptora
example | ε-akceptor a jeho výpočet na vstupe aba |  | p003
theorem | Pomocné tvrdenie: najkratšia postupnosť ε-prechodov má dĺžku najviac  | Q||P | p005 [proof: generated]
algorithm | Odstránenie ε-prechodov [epsilon elimination] | nové prechody po ε-ceste, nové koncové stavy | p004 [proof: generated] => alg.odstranenie-eps-prechodov
theorem | Veta 9.1: každý ε-akceptor sa dá nahradiť NFA |  | p004-p007 [proof] => thm.veta-9-1-eps-na-nfa
example | ε-akceptor pre zreťazenie blokov ab/abb a ab/aab a jeho prevody M', M'' |  | p008-p010

USES (defined elsewhere)
- dfn.nfa — Nedeterministický konečnostavový akceptor [nondeterministic finite automaton, NFA] (téma nedeterminizmus)
- dfn.jazyk-nfa — Jazyk rozpoznávaný NFA (téma nedeterminizmus)
- def.holubnikovy-princip — Holubníkový princíp [pigeonhole principle] (téma gramatiky)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
