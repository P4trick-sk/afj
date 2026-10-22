# Nedeterministické konečnostavové akceptory (nedeterminizmus, kurz A, poradie 8)
Zdroj: Afja08_ned_akceptory_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Nedeterministický konečnostavový akceptor [nondeterministic finite automaton, NFA] | M=(Q,Σ,qI,δ,F), δ:Q×Σ→2^Q | p002 => dfn.nfa
example | NFA s dvoma stavmi a jeho výpočet na vstupe abbab |  | p003-p004
definition | Zovšeobecnená prechodová funkcia δ* [extended transition function on sets] | δ*(A,ε)=A, δ*(A,wa)=zjednotenie δ(q,a) pre q v δ*(A,w) | p005-p006 => dfn.delta-hviezdicka
definition | Jazyk rozpoznávaný NFA | L(M)={w : δ*({qI},w)∩F≠Ø} | p007 => dfn.jazyk-nfa
algorithm | Podmnožinová konštrukcia [subset construction] | stavy DFA sú podmnožiny Q | p008 [proof: generated] => alg.podmnozinova-konstrukcia
theorem | Veta 8.1: každý NFA sa dá nahradiť ekvivalentným DFA |  | p008-p009 [proof] => thm.veta-8-1-nfa-na-dfa
example | Prevod NFA na DFA a následná minimalizácia | jazyk začínajúci aa | p010-p011

USES (defined elsewhere)
- dfn.konecnostavovy-akceptor — Konečnostavový akceptor [deterministic finite automaton, DFA] (téma akceptory)
- dfn.jazyk-akceptora — Jazyk rozpoznávaný akceptorom [language recognized by an automaton] (téma akceptory)
- def.mnozina-relacia-funkcia — Množina, relácia a funkcia [set, relation, function] (téma gramatiky)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
- alg.minimalizacia-akceptora — Minimalizácia akceptora [DFA minimization] (téma akceptory)
