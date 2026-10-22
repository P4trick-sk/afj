# Zásobníkové automaty a bezkontextové gramatiky (zas-bezgram, kurz B, poradie 17)
Zdroj: Afjb04_ZasAut-BezGram_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

theorem | Veta (CFG → PDA): ku každej CFG existuje PDA s akceptovaním prázdnym zásobníkom | konštrukcia z CNF, jeden stav; ošetrenie ε | p002-p005 [proof] => thm.bezgram-na-pda
algorithm | Konštrukcia PDA z gramatiky v CNF | inštrukcie (q,ε,A)→(q,BC) a (q,a,A)→(q,ε) | p003 [proof: generated] => alg.pda-z-gramatiky
theorem | Veta (PDA → CFG): ku každému PDA s akceptovaním prázdnym zásobníkom existuje CFG | trojicová konštrukcia [q,A,r], 4 typy pravidiel | p006-p012 [proof] => thm.pda-na-bezgram
algorithm | Trojicová konštrukcia gramatiky z PDA [triple construction] | neterminály [q,A,r] | p007 [proof: generated] => alg.trojicova-konstrukcia
definition | Bezkontextový jazyk a deterministický bezkontextový jazyk [context-free language, deterministic CFL] | trieda CFL = PDA; DCFL = DPDA | p013 => dfn.bezkontextovy-jazyk
theorem | Regulárne jazyky sú podmnožinou deterministických bezkontextových jazykov | akceptor ako DPDA | p014 [proof: generated] => thm.regularne-v-dcfl
example | DPDA pre a^n b^n |  | p015
theorem | Lema: a^n b^n je deterministický bezkontextový, ale nie regulárny |  | p015-p016 [proof] => thm.anbn-dcfl-nie-regularny

USES (defined elsewhere)
- dfn.zasobnikovy-automat — Zásobníkový automat [pushdown automaton, PDA] (téma zas-automaty)
- dfn.akceptovanie-pda — Akceptovanie koncovým stavom a prázdnym zásobníkom [acceptance by final state / empty stack] (téma zas-automaty)
- dfn.bezkontextova-gramatika — Bezkontextová gramatika [context-free grammar, CFG] (téma bezkontextove-gramatiky)
- dfn.chomskeho-normalny-tvar — Chomského normálny tvar [Chomsky normal form] (téma bezkontextove-gramatiky)
- thm.chomskeho-normalny-tvar — Veta: každú CFG možno nahradiť CFG v Chomského normálnom tvare (téma bezkontextove-gramatiky)
- thm.pda-zmena-o-jeden-symbol — Lema: zásobník sa mení najviac o jeden symbol (téma zas-automaty)
- dfn.dpda — Deterministický zásobníkový automat [deterministic pushdown automaton, DPDA] (téma det-zas-automaty)
- thm.veta-13-4-anbn-nie-je-regularny — Veta 13.4: a^n b^n je bezkontextový, ale nie regulárny (téma konstrukcie)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
- def.holubnikovy-princip — Holubníkový princíp [pigeonhole principle] (téma gramatiky)
