# Deterministické bezkontextové jazyky (det-bezk, kurz B, poradie 22)
Zdroj: Afjb09_DetBezJazyky_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

theorem | Existuje bezkontextový jazyk, ktorý nie je deterministický bezkontextový | doplnok a^n b^n c^n; dôsledok uzavretosti DCFL na doplnok | p002-p003 [proof] => thm.cfl-nie-je-dcfl
theorem | DCFL nie sú uzavreté na prienik |  | p004 [proof] => thm.dcfl-nie-uzavrete-prienik
theorem | DCFL nie sú uzavreté na zjednotenie | zjednotenie doplnkov | p005-p006 [proof] => thm.dcfl-nie-uzavrete-zjednotenie
theorem | Prienik a zjednotenie DCFL s regulárnym jazykom je DCFL | súčin DPDA a DFA | p007-p008 [proof] => thm.dcfl-regularny-prienik-zjednotenie
concept | Prehľad uzavretosti: CFL, DCFL, regulárne jazyky | tabuľka | p009 => def.prehlad-uzavretosti-dcfl

USES (defined elsewhere)
- dfn.bezkontextovy-jazyk — Bezkontextový jazyk a deterministický bezkontextový jazyk [context-free language, deterministic CFL] (téma zas-bezgram)
- thm.dcfl-uzavrete-doplnok — Dôsledok: deterministické bezkontextové jazyky sú uzavreté na doplnok (téma doplnok-dbj)
- thm.anbncn-nie-je-bezkontextovy — a^n b^n c^n nie je bezkontextový jazyk (téma pumping2)
- thm.cfl-nie-uzavrete-doplnok — Bezkontextové jazyky nie sú uzavreté na doplnok (téma uzaver-bezk)
- thm.cfl-nie-uzavrete-prienik — Bezkontextové jazyky nie sú uzavreté na prienik (téma uzaver-bezk)
- thm.cfl-regularny-prienik — Prienik CFL s regulárnym jazykom je bezkontextový (téma uzaver-bezk)
- alg.sucin-pda-dfa — Súčinová konštrukcia PDA a DFA [product of a PDA and a DFA] (téma uzaver-bezk)
