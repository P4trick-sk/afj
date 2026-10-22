# Doplnok deterministických bezkontextových jazykov (doplnok-dbj, kurz B, poradie 21)
Zdroj: Afjb08_DetBezDoplnok_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

concept | Nekonečné ε-výpočty DPDA a prečo prekážajú doplnku | M sa môže zacykliť uprostred vstupu | p003-p004 => def.nekonecne-eps-vypocty
theorem | Lema: viac ako m po sebe idúcich ε-prechodov znamená nekonečnú postupnosť | rozbor prípadov a, b, m=|Q|·|Γ|^k… | p006-p015 [proof] => thm.lema-nekonecna-eps-postupnost
definition | Funkcia h(p,A) s hodnotami ε, − a + | konečná, nekonečná bez koncového stavu, nekonečná cez koncový stav | p016 => dfn.funkcia-h
algorithm | Výpočet tabuľky h | simulácia prvých m krokov | p017 [proof: generated] => alg.vypocet-tabulky-h
algorithm | Konštrukcia DPDA M' zastavujúceho vždy [halting DPDA construction] | stavy q°, q−, q+, e−, e+, nové dno z'I, pravidlá 0–8 | p018-p029 [proof: generated] => alg.konstrukcia-zastavujuceho-dpda
theorem | Veta: každý DPDA sa dá nahradiť DPDA, ktorý vždy zastaví |  | p002, p018-p029 [proof] => thm.dpda-vzdy-zastavi
theorem | Dôsledok: deterministické bezkontextové jazyky sú uzavreté na doplnok | prehodenie F'=Q+∪{e+} a F''=Q−∪{e−} | p002, p029 [proof: generated] => thm.dcfl-uzavrete-doplnok

USES (defined elsewhere)
- dfn.dpda — Deterministický zásobníkový automat [deterministic pushdown automaton, DPDA] (téma det-zas-automaty)
- thm.pda-zmena-o-jeden-symbol — Lema: zásobník sa mení najviac o jeden symbol (téma zas-automaty)
- dfn.konfiguracia-pda — Konfigurácia a krok výpočtu [configuration] (téma zas-automaty)
- def.holubnikovy-princip — Holubníkový princíp [pigeonhole principle] (téma gramatiky)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
