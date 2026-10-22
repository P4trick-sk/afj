# Redukcia automatov I: nedosiahnuteľné stavy (nedosiahnutelne, kurz A, poradie 3)
Zdroj: Afja03_redukcia_nedos_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Ekvivalentné automaty [equivalent automata] | rovnaké abecedy a rovnaký výstup na každom vstupe | p002 => dfn.ekvivalentne-automaty
definition | Minimálny (optimálny) automat [minimal automaton] | ekvivalentný automat s menším počtom stavov neexistuje | p002 => dfn.minimalny-automat
example | Neoptimálny automat M1 a jeho trojstavový ekvivalent M2 |  | p003
definition | Dosiahnuteľný stav [reachable state] | existuje vstup, ktorým sa doň dostaneme z qI | p004 => dfn.dosiahnutelny-stav
theorem | Lema 3.1: nasledovník dosiahnuteľného stavu je dosiahnuteľný |  | p004 [proof]
algorithm | Hľadanie dosiahnuteľných stavov | iterácia Q0⊆Q1⊆… do ustálenia | p005 [proof: generated] => alg.dosiahnutelne-stavy
algorithm | Odstránenie nedosiahnuteľných stavov | zúženie f a g na Q' | p005 [proof: generated] => alg.odstranenie-nedosiahnutelnych
example | Odstránenie nedosiahnuteľných stavov z M1 | výpočet Q0–Q3 | p006

USES (defined elsewhere)
- dfn.konecnostavovy-automat — Konečnostavový automat s výstupom [finite-state machine with output, Mealy machine] (téma automaty-vystup)
- dfn.rozsirene-funkcie — Zovšeobecnené funkcie f* a g* [extended transition and output function] (téma automaty-vystup)
