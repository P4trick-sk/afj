# Operácie s regulárnymi jazykmi (operacie, kurz A, poradie 7)
Zdroj: Afja07_operacie_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

concept | Uzavretosť triedy jazykov na operáciu [closure under an operation] | vysvetlenie pojmu | — [supplement] => def.uzavretost
definition | Regulárny jazyk [regular language] | jazyk rozpoznávaný nejakým akceptorom | p002 => dfn.regularny-jazyk
theorem | Veta 7.1: regulárne jazyky sú uzavreté na doplnok |  | p002 [proof] => thm.uzavretost-doplnok
example | Akceptor pre doplnok jazyka |  | p003
algorithm | Súčinová konštrukcia akceptorov [product construction] | paralelná simulácia M1 a M2 na Q1×Q2 | p004-p005 [proof: generated] => alg.sucinova-konstrukcia
theorem | Veta 7.2: regulárne jazyky sú uzavreté na prienik |  | p004-p005 [proof] => thm.uzavretost-prienik
example | Prienik a zjednotenie jazykov „končí na 01 alebo obsahuje 0110“ a „nepárny počet jednotiek“ |  | p006-p008
theorem | Veta 7.3: uzavretosť na zjednotenie, rozdiel, symetrický rozdiel |  | p007 [proof] => thm.uzavretost-zjednotenie-rozdiel
theorem | Lema 7.4: rozhodnuteľnosť L=Ø a L=Σ* |  | p009 [proof] => thm.rozhodnutelnost-prazdnosti
theorem | Veta 7.5: rozhodnuteľnosť inklúzie, rovnosti, disjunktnosti a pokrytia |  | p010-p011 [proof] => thm.rozhodnutelnost-inkluzie-rovnosti

USES (defined elsewhere)
- dfn.konecnostavovy-akceptor — Konečnostavový akceptor [deterministic finite automaton, DFA] (téma akceptory)
- dfn.jazyk-akceptora — Jazyk rozpoznávaný akceptorom [language recognized by an automaton] (téma akceptory)
- alg.dosiahnutelne-stavy — Hľadanie dosiahnuteľných stavov (téma nedosiahnutelne)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
