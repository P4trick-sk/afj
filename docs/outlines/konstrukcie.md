# Ďalšie konštrukcie a uzavretosť regulárnych jazykov (konstrukcie, kurz A, poradie 13)
Zdroj: Afja13_konstrukcie_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

concept | Konverzie medzi reprezentáciami regulárnych jazykov | diagram: ε-akceptory, NFA, DFA, gramatiky, výrazy | p002 => def.konverzie-reprezentacii
example | Prevod regulárnej gramatiky na regulárny výraz | S=(a+b)*a(...) | p003
concept | Prehľad uzavretosti regulárnych jazykov na operácie [closure properties] | doplnok, prienik, zjednotenie, rozdiel, zreťazenie, iterácia, zrkadlo, homomorfizmus | p004 => def.uzavretost-regularnych
definition | Zrkadlový obraz jazyka [reversal of a language] | L^R | p004 => dfn.zrkadlovy-obraz
definition | Homomorfizmus a inverzný homomorfizmus [homomorphism, inverse homomorphism] | h:Σ1*→Σ2*, h(L1), h⁻¹(L2) | p010 => dfn.homomorfizmus
theorem | Veta 13.1: uzavretosť na zreťazenie a iteráciu |  | p005 [proof] => thm.uzavretost-zretazenie-iteracia
algorithm | Priamočiara konštrukcia zreťazenia a iterácie pre akceptory | ε-prechody z koncových do počiatočného, nový stav X | p006-p007 [proof: generated] => alg.konstrukcia-zretazenia-iteracie
theorem | Veta 13.2: uzavretosť na zrkadlový obraz |  | p008 [proof] => thm.uzavretost-zrkadlo
algorithm | Konštrukcia akceptora pre zrkadlový obraz | otočenie hrán, nový počiatočný stav X | p009 [proof: generated]
theorem | Veta 13.3: uzavretosť na homomorfizmus a inverzný homomorfizmus |  | p011 [proof] => thm.uzavretost-homomorfizmus
example | Homomorfný obraz a inverzný homomorfný obraz konkrétneho jazyka |  | p012
theorem | Veta 13.4: a^n b^n je bezkontextový, ale nie regulárny |  | p013 [proof] => thm.veta-13-4-anbn-nie-je-regularny

USES (defined elsewhere)
- dfn.regularny-jazyk — Regulárny jazyk [regular language] (téma operacie)
- dfn.eps-akceptor — ε-akceptor [epsilon-NFA, NFA with epsilon transitions] (téma eps-akceptory)
- thm.veta-8-1-nfa-na-dfa — Veta 8.1: každý NFA sa dá nahradiť ekvivalentným DFA (téma nedeterminizmus)
- thm.veta-9-1-eps-na-nfa — Veta 9.1: každý ε-akceptor sa dá nahradiť NFA (téma eps-akceptory)
- thm.veta-10-1-dfa-na-gramatiku — Veta 10.1: každý DFA sa dá nahradiť regulárnou gramatikou (téma reg-gramatiky)
- thm.veta-10-2-gramatika-na-eps-akceptor — Veta 10.2: rozšírená regulárna gramatika sa dá nahradiť ε-akceptorom (téma reg-gramatiky)
- thm.veta-11-1-vyraz-na-eps-akceptor — Veta 11.1: každý regulárny výraz sa dá nahradiť ε-akceptorom (téma reg-vyrazy)
- thm.veta-12-3-dfa-na-vyraz — Veta 12.3: každý DFA sa dá nahradiť regulárnym výrazom (téma reg-rovnice)
- thm.uzavretost-doplnok — Veta 7.1: regulárne jazyky sú uzavreté na doplnok (téma operacie)
- thm.uzavretost-prienik — Veta 7.2: regulárne jazyky sú uzavreté na prienik (téma operacie)
- thm.uzavretost-zjednotenie-rozdiel — Veta 7.3: uzavretosť na zjednotenie, rozdiel, symetrický rozdiel (téma operacie)
- def.holubnikovy-princip — Holubníkový princíp [pigeonhole principle] (téma gramatiky)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
