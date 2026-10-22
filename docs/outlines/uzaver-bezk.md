# Uzáverové vlastnosti bezkontextových jazykov (uzaver-bezk, kurz B, poradie 20)
Zdroj: Afjb07_UzBezJazyky_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

example | DPDA pre jazyky a^n b^n c^k a a^k b^n c^n |  | p002-p003
theorem | Bezkontextové jazyky nie sú uzavreté na prienik | prienik je a^n b^n c^n | p002-p003 [proof] => thm.cfl-nie-uzavrete-prienik
theorem | Bezkontextové jazyky nie sú uzavreté na doplnok | doplnok jazyka a^n b^n c^n | p004-p007 [proof] => thm.cfl-nie-uzavrete-doplnok
example | Gramatika pre jazyk slov, ktoré nemajú tvar a^n b^n c^n |  | p005-p006
theorem | Uzavretosť CFL na zjednotenie, zreťazenie, iteráciu a zrkadlový obraz | konštrukcie gramatík | p008-p010 [proof] => thm.cfl-uzavrete-zjednotenie-zretazenie-iteracia-zrkadlo
theorem | Prienik CFL s regulárnym jazykom je bezkontextový | súčin PDA a DFA | p011-p013 [proof] => thm.cfl-regularny-prienik
algorithm | Súčinová konštrukcia PDA a DFA [product of a PDA and a DFA] | stavy Q1×Q2 | p011-p013 [proof: generated] => alg.sucin-pda-dfa
concept | Prehľad uzavretosti: bezkontextové a regulárne jazyky | tabuľka | p014 => def.prehlad-uzavretosti-cfl

USES (defined elsewhere)
- dfn.bezkontextova-gramatika — Bezkontextová gramatika [context-free grammar, CFG] (téma bezkontextove-gramatiky)
- dfn.dpda — Deterministický zásobníkový automat [deterministic pushdown automaton, DPDA] (téma det-zas-automaty)
- thm.anbncn-nie-je-bezkontextovy — a^n b^n c^n nie je bezkontextový jazyk (téma pumping2)
- alg.sucinova-konstrukcia — Súčinová konštrukcia akceptorov [product construction] (téma operacie)
- dfn.konecnostavovy-akceptor — Konečnostavový akceptor [deterministic finite automaton, DFA] (téma akceptory)
- dfn.zretazenie-slov — Dĺžka slova a zreťazenie [length, concatenation] (téma gramatiky)
- dfn.zrkadlovy-obraz — Zrkadlový obraz jazyka [reversal of a language] (téma konstrukcie)
- dfn.regularny-jazyk — Regulárny jazyk [regular language] (téma operacie)
