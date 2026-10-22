# Zásobníkové automaty s výstupom (zas-prevodniky, kurz B, poradie 23)
Zdroj: Afjb10_ZasPrevodnik_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Deterministický zásobníkový prevodník [deterministic pushdown transducer] | M=(Q,Σ,Γ,Δ,δ,qI,zI,F), δ vracia aj výstupný reťazec | p002-p003 => dfn.zasobnikovy-prevodnik
concept | Zadný poľský zápis [reverse Polish notation, postfix notation] | operátor za operandmi | p004 => def.zadny-polsky-zapis
example | Preklad aritmetického výrazu do zadného poľského zápisu | a1*(a2+a3-a4) → a1 a2 a3 + a4 - *, výpočet krok za krokom, súvis s derivačným stromom | p004-p010 => ex.preklad-do-postfix

USES (defined elsewhere)
- dfn.dpda — Deterministický zásobníkový automat [deterministic pushdown automaton, DPDA] (téma det-zas-automaty)
- dfn.bezkontextova-gramatika — Bezkontextová gramatika [context-free grammar, CFG] (téma bezkontextove-gramatiky)
- dfn.derivacny-strom — Derivačný strom [derivation tree, parse tree] (téma bezkontextove-gramatiky)
