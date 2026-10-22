# Konečnostavové automaty s výstupom (automaty-vystup, kurz A, poradie 2)
Zdroj: Afja02_automaty_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Konečnostavový automat s výstupom [finite-state machine with output, Mealy machine] | M=(Q,Σ,Δ,qI,f,g), q_{t+1}=f(q_t,a_{t+1}), b_{t+1}=g(q_t,a_{t+1}) | p002 => dfn.konecnostavovy-automat
example | Automat s mincami a lístkami | mince 1,2,5, lístky v hodnote 6; tabuľky f a g a priebeh výpočtu | p003-p004
definition | Grafická reprezentácia automatu [state diagram] | hrana a/b, šípka na počiatočný stav | p005 => dfn.stavovy-diagram
example | Automat lokalizujúci každý druhý výskyt reťazca 001 | stavy A–F; stavy môžu byť pomenované ľubovoľne | p006
definition | Zovšeobecnené funkcie f* a g* [extended transition and output function] | rekurzívna definícia na slovách | p007-p008 => dfn.rozsirene-funkcie
theorem | Lema 2.1: f* a g* na jednom symbole sa zhodujú s f a g |  | p008 [proof]
theorem | Lema 2.2: f* a g* na zreťazení slov |  | p009 [proof] => thm.lema-2-2-zretazenie

USES (defined elsewhere)
- dfn.abeceda — Abeceda a symbol [alphabet, symbol] (téma gramatiky)
- dfn.slovo — Slovo a tranzitívny uzáver Σ* [word, string, Kleene closure] (téma gramatiky)
- dfn.zretazenie-slov — Dĺžka slova a zreťazenie [length, concatenation] (téma gramatiky)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
