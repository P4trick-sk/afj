# Deterministické zásobníkové automaty (det-zas-automaty, kurz B, poradie 15)
Zdroj: Afjb02_DetZasAutomat_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Deterministický zásobníkový automat [deterministic pushdown automaton, DPDA] | najviac jedna inštrukcia pre (q,a,A); varianty ε-prechodov | p002-p003 => dfn.dpda
concept | Else-ε-prechod [else epsilon transition] | ε-prechod uplatnený iba ak nie je definovaný prechod na vstupný symbol | p003 => def.else-eps-prechod
example | DPDA pre aritmetické výrazy | neterminály ako zásobníkové symboly, rozbor správneho a chybného vstupu | p004-p007 => ex.dpda-aritmeticke-vyrazy
theorem | Lema: DPDA možno upraviť bez else-ε-prechodov pre jazyk L$ | koncová značka $, pamätanie čítaného symbolu v stave | p008-p012 [proof: sketch] => thm.dpda-bez-else-eps

USES (defined elsewhere)
- dfn.zasobnikovy-automat — Zásobníkový automat [pushdown automaton, PDA] (téma zas-automaty)
- dfn.konfiguracia-pda — Konfigurácia a krok výpočtu [configuration] (téma zas-automaty)
- dfn.akceptovanie-pda — Akceptovanie koncovým stavom a prázdnym zásobníkom [acceptance by final state / empty stack] (téma zas-automaty)
