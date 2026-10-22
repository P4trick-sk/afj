# Uzáverové vlastnosti kontextových jazykov (uzaver-kont, kurz B, poradie 25)
Zdroj: Afjb12_UzKontJazyky_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

theorem | Lema: LBA má akceptujúci výpočet vtedy a len vtedy, ak má akceptujúci výpočet kratší než d^n krokov | počet konfigurácií, opakovanie konfigurácie | p002-p006 [proof] => thm.lba-kratky-vypocet
theorem | Veta: každý LBA sa dá nahradiť LBA, ktorý vždy zastaví | počítadlo krokov v báze d, zachováva determinizmus | p007-p020 [proof] => thm.lba-vzdy-zastavi
algorithm | Konštrukcia vždy zastavujúceho LBA s počítadlom krokov | inicializácia, simulácia, zníženie počítadla, obnovenie | p008-p020 [proof: generated] => alg.lba-s-pocitadlom
theorem | Deterministické kontextové jazyky sú uzavreté na doplnok | prehodenie pF a pE | p021 [proof] => thm.dcsl-uzavrete-doplnok
theorem | Kontextové jazyky sú uzavreté na doplnok | špeciálny prípad Immermanovej–Szelepcsényiho vety; dôkaz na slajdoch len odkaz | p022 [proof: generated] => thm.csl-uzavrete-doplnok
theorem | Kontextové aj deterministické kontextové jazyky sú uzavreté na prienik a zjednotenie | dve stopy, simulácia M1 a potom M2 | p023-p028 [proof] => thm.csl-uzavrete-prienik-zjednotenie
theorem | Uzavretosť na zreťazenie, iteráciu a zrkadlový obraz | gramatiky pre CSL; pre deterministické LBA cyklus cez rozdelenie slova | p029-p030 [proof] => thm.csl-uzavrete-zretazenie-iteracia-zrkadlo
concept | Prehľad uzavretosti: CSL, DCSL, CFL, DCFL, REG | tabuľka | p031 => def.prehlad-uzavretosti-csl
problem | Otvorený problém: sú deterministické a nedeterministické kontextové jazyky rovnaké? | (LBA problem); Savitchova konštrukcia vyžaduje páskovú pamäť n^2 | p032 => prob.lba-problem

USES (defined elsewhere)
- dfn.lba — Nedeterministický lineárne ohraničený Turingov stroj [linear bounded automaton, LBA] (téma kontextove)
- dfn.akceptovanie-lba — Akceptovanie a odmietnutie LBA (téma kontextove)
- dfn.kontextovy-jazyk — Kontextový jazyk [context-sensitive language] (téma kontextove)
- thm.lba-na-kontextovu — Veta (LBA → CSG): ku každému LBA existuje kontextová gramatika (téma kontextove)
- thm.kontextova-na-lba — Veta (CSG → LBA): ku každej kontextovej gramatike existuje LBA (téma kontextove)
- def.holubnikovy-princip — Holubníkový princíp [pigeonhole principle] (téma gramatiky)
