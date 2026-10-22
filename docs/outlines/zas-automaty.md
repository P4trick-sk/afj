# Zásobníkové automaty (zas-automaty, kurz B, poradie 14)
Zdroj: Afjb01_ZasAutomat_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Zásobníkový automat [pushdown automaton, PDA] | M=(Q,Σ,Γ,δ,qI,zI,F), δ:Q×(Σ∪{ε})×Γ→2^(Q×Γ*) | p002-p004 => dfn.zasobnikovy-automat
concept | Inštrukcie PDA a ich účinok na zásobník | (q,a,A)→(q',B1…Bk), ε-inštrukcie, nedeterminizmus | p003-p004
definition | Konfigurácia a krok výpočtu [configuration] | (q, zvyšok vstupu, zásobník); zápis kroku ⊢ | p006-p007 => dfn.konfiguracia-pda
definition | Akceptovanie koncovým stavom a prázdnym zásobníkom [acceptance by final state / empty stack] | L(M), N(M) | p005, p008 => dfn.akceptovanie-pda
example | Jazyk wcw^Rc | kopírovanie do zásobníka, porovnávanie, dva prechody cez c | p009-p010
example | Jazyk ww^R a nedeterminizmus | ε-prechod do fázy porovnávania, vetvy "priskoro" a "primeskoro" | p011-p013
theorem | Lema: akceptovanie prázdnym zásobníkom možno nahradiť koncovými stavmi | konštrukcia M' s novým dnom z'I a stavom q'F, zachováva determinizmus | p014-p015 [proof: sketch] => thm.pda-prazdny-na-koncove
theorem | Lema: akceptovanie koncovými stavmi možno nahradiť prázdnym zásobníkom | konštrukcia s vyprázdňovaním, nezachováva determinizmus | p016-p017 [proof: sketch] => thm.pda-koncove-na-prazdny
theorem | Lema: zásobník sa mení najviac o jeden symbol | nahradenie dlhých zápisov postupnosťou krokov s novými stavmi | p018-p019 [proof: sketch] => thm.pda-zmena-o-jeden-symbol

USES (defined elsewhere)
- dfn.abeceda — Abeceda a symbol [alphabet, symbol] (téma gramatiky)
- dfn.slovo — Slovo a tranzitívny uzáver Σ* [word, string, Kleene closure] (téma gramatiky)
- dfn.jazyk — Jazyk [language] (téma gramatiky)
- dfn.konecnostavovy-akceptor — Konečnostavový akceptor [deterministic finite automaton, DFA] (téma akceptory)
- dfn.nfa — Nedeterministický konečnostavový akceptor [nondeterministic finite automaton, NFA] (téma nedeterminizmus)
