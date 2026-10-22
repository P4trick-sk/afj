# Regulárne výrazy I: základné vlastnosti (reg-vyrazy, kurz A, poradie 11)
Zdroj: Afja11_reg_vyrazy_zakl_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Regulárny výraz [regular expression] | a, ε, Ø, α+β, αβ, α*, priorita operátorov | p002 => dfn.regularny-vyraz
definition | Jazyk označený regulárnym výrazom [language denoted by a regular expression] | L(α) | p002 => dfn.jazyk-vyrazu
example | Príklady regulárnych výrazov a ich jazykov |  | p003
algorithm | Konštrukcia ε-akceptora z regulárneho výrazu [Thompson construction] | elementárne výrazy a zložené výrazy, jeden počiatočný a jeden koncový stav | p004-p005 [proof: generated] => alg.thompsonova-konstrukcia
theorem | Veta 11.1: každý regulárny výraz sa dá nahradiť ε-akceptorom |  | p004-p005 [proof] => thm.veta-11-1-vyraz-na-eps-akceptor
example | ε-akceptor pre (aab+ca*c)*(c+ε) |  | p006

USES (defined elsewhere)
- dfn.abeceda — Abeceda a symbol [alphabet, symbol] (téma gramatiky)
- dfn.jazyk — Jazyk [language] (téma gramatiky)
- dfn.eps-akceptor — ε-akceptor [epsilon-NFA, NFA with epsilon transitions] (téma eps-akceptory)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
