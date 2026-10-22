# Pumping lema pre bezkontextové jazyky II (pumping2, kurz B, poradie 19)
Zdroj: Afjb06_Pumping-II_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

concept | Schéma dôkazu nebezkontextovosti pomocou pumping lemy | voľba slova, rozbor prípadov rozloženia vxy, spor | — [supplement] => def.schema-pumping
theorem | a^n b^n c^n nie je bezkontextový jazyk | slovo a^{m+1}b^{m+1}c^{m+1}, tri prípady | p002-p006 [proof] => thm.anbncn-nie-je-bezkontextovy
theorem | Jazyk a^{n1}b^{n2}a^{n1}b^{n2} nie je bezkontextový | analogicky | p007 [proof] => thm.kopirovanie-nie-je-bezkontextove
theorem | Jazyk a^p, p prvočíslo, nie je bezkontextový | A+kB nie je prvočíslo; rozbor A≥2, A=1, A=0 | p008-p010 [proof] => thm.prvocisla-nie-su-bezkontextove

USES (defined elsewhere)
- thm.pumping-lema-bezkontextove — Pumping lema pre bezkontextové jazyky [pumping lemma for context-free languages] (téma pumping1)
- def.dokaz-sporom — Dôkaz sporom [proof by contradiction] (téma gramatiky)
