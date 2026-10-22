# Regulárne výrazy II: rovnice (reg-rovnice, kurz A, poradie 12)
Zdroj: Afja12_reg_vyrazy_rovn_P.pdf

Formát: TYPE | názov [alt. pojem] | poznámka | strana [proof] => rezervované ID

definition | Rovnosť a usporiadanie regulárnych výrazov, mocnina [equality and inclusion of regular expressions] | α=β ak L(α)=L(β), α≤β ak L(α)⊆L(β), α^i | p002 => dfn.rovnost-vyrazov
theorem | Lema 12.1: algebraické vlastnosti regulárnych výrazov | asociativita, komutativita, distributivita, idempotencia, konštanty Ø a ε, iterácia, relácie | p003-p005 [proof: sketch] => thm.lema-12-1-algebra-vyrazov
theorem | Veta 12.2: minimálne riešenie rovnice x=αx+β je x=α*β [Arden's lemma] |  | p006-p007 [proof] => thm.veta-12-2-ardenovo-lemma
example | Riešenie sústavy dvoch regulárnych rovníc |  | p008
algorithm | Riešenie sústavy regulárnych rovníc [solving systems of regular equations] | postupné vylučovanie premenných od poslednej | p009 [proof: generated] => alg.riesenie-sustavy-rovnic
theorem | Veta 12.3: každý DFA sa dá nahradiť regulárnym výrazom |  | p010-p011 [proof] => thm.veta-12-3-dfa-na-vyraz
algorithm | Sústava rovníc z akceptora | jedna rovnica na stav, ε v koncových stavoch | p010-p011 [proof: generated]
example | Regulárny výraz pre akceptor s piatimi stavmi A–E | riešenie sústavy po krokoch | p012-p018

USES (defined elsewhere)
- dfn.regularny-vyraz — Regulárny výraz [regular expression] (téma reg-vyrazy)
- dfn.jazyk-vyrazu — Jazyk označený regulárnym výrazom [language denoted by a regular expression] (téma reg-vyrazy)
- dfn.konecnostavovy-akceptor — Konečnostavový akceptor [deterministic finite automaton, DFA] (téma akceptory)
- def.indukcia — Matematická indukcia [mathematical induction] (téma gramatiky)
