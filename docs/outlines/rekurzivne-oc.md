# Rekurzívne vyčísliteľné jazyky (rekurzivne-oc, kurz B, poradie 26)
Zdroj: Afjb13_RekOcisJ_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Frázová gramatika [unrestricted grammar, phrase-structure grammar] | ľavá strana obsahuje aspoň jeden neterminál | p002 => dfn.frazova-gramatika
theorem | Lema N (normálny tvar frázových gramatík) | pravidlá α→A a A→β s rozdelenými neterminálmi N1 a N2 | p002-p003 [proof] => thm.lema-n-normalny-tvar
definition | Turingov stroj [Turing machine] | M=(Q,Σ,Γ,qI,qF,⊢,#,H) | p004 => dfn.turingov-stroj
theorem | Veta (TS → frázová gramatika): ku každému nedeterministickému TS existuje frázová gramatika | hlavná myšlienka a stopy | p005-p008 [proof: generated] => thm.ts-na-frazovu
theorem | Veta (frázová gramatika → DTS): ku každej frázovej gramatike existuje deterministický TS | generovanie všetkých reťazcov, test jedného kroku odvodenia | p009-p014 [proof: generated] => thm.frazova-na-dts
algorithm | Generovanie všetkých reťazcov nad N∪T∪{$} | počítadlo v báze d=|N|+|T|+1 | p010 [proof: generated] => alg.generovanie-retazcov
algorithm | Test jedného kroku odvodenia u⇒v | pravidlá typov α→A a A→β | p011-p012 [proof: generated]
definition | Rekurzívne vyčísliteľný a rekurzívny jazyk [recursively enumerable and recursive language] | jazyk rozpoznávaný TS; rekurzívny ak TS vždy zastaví | p014 => dfn.rekurzivne-vycisliteny-jazyk
theorem | Rekurzívne vyčísliteľné jazyky sú uzavreté na prienik | dve stopy | p015-p016 [proof: generated] => thm.re-uzavrete-prienik
theorem | Uzavretosť RE na zjednotenie, zreťazenie, iteráciu a zrkadlový obraz | úprava gramatík so separátormi $ | p017-p019 [proof: generated] => thm.re-uzavrete-ostatne
concept | Prehľad uzavretosti všetkých tried jazykov | REL, CSL, DCSL, CFL, DCFL, REG | p020 => def.prehlad-uzavretosti-vsetkych

USES (defined elsewhere)
- dfn.gramatika — Gramatika [grammar] (téma gramatiky)
- dfn.odvodenie — Odvoditeľnosť [derivation] (téma gramatiky)
- dfn.lba — Nedeterministický lineárne ohraničený Turingov stroj [linear bounded automaton, LBA] (téma kontextove)
- thm.lba-na-kontextovu — Veta (LBA → CSG): ku každému LBA existuje kontextová gramatika (téma kontextove)
- thm.kontextova-na-lba — Veta (CSG → LBA): ku každej kontextovej gramatike existuje LBA (téma kontextove)
- dfn.bezkontextova-gramatika — Bezkontextová gramatika [context-free grammar, CFG] (téma bezkontextove-gramatiky)
- thm.cfl-uzavrete-zjednotenie-zretazenie-iteracia-zrkadlo — Uzavretosť CFL na zjednotenie, zreťazenie, iteráciu a zrkadlový obraz (téma uzaver-bezk)
