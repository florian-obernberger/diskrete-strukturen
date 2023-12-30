---
title: Prädikatenlogik
subtitle: Mehr endlose Schmerzen
author: Verzweifelte Studierende
date: 18. Dezember 2023
toc: true
lang: de-AT
font-family: sans-serif
latex-header:
   - \usepackage{pifont}% http://ctan.org/pkg/pifont
   - \usepackage{cancel,mathtools}
   - \newcommand{\Q}{\mathbb{Q}}
   - \newcommand{\N}{\mathbb{N}}
   - \newcommand{\Z}{\mathbb{Z}}
   - \newcommand{\R}{\mathbb{R}}
   - \newcommand{\f}{\text{f}}
   - \newcommand{\w}{\text{w}}
   - \newcommand{\hmd}[1]{\hlm{brown!50}{#1}}
   - \newcommand{\hmw}[1]{\hlm{white}{#1}}
   - \newcommand{\without}{~\backslash~}
   - \newcommand{\sel}{\text{sel}~}
   - \newcommand{\sol}[1]{\underline{\underline{#1}}}
   - \newcommand{\lxor}{\dot{\lor}}
   - '\renewcommand{\nmid}{\not|~}'
   - '\newcommand{\inv}[1]{#1^{-1}}'
   - '\newcommand{\hlm}[2]{\colorbox{#1}{$\displaystyle #2$}}'
   - \renewcommand{\implies}{\rightarrow}
   - \newcommand{\Implies}{\Rightarrow}
   - \newcommand{\limplies}{\Rightarrow}
   - \newcommand{\cmark}{\ding{51}}%
   - \newcommand{\xmark}{\ding{55}}%
   - \newcommand{\infix}{:\Leftrightarrow}
---

\newpage

# Einführung

- Aussagenlogik weist Prädikate einem bestimmten Subjekt zu.
- Lässt man das Subjekt hingegen offen ("variabel"), lässt es also beliebig aus
  einer Grundmenge wählbar, so erhält man eine Aussageform.
- Das Prädikat ist hierbei eine aussagenlogische Formel $p$, in welcher ein
  (oder mehrere) Teile stellvertretend durch eine Variable (z.B. $x$) ersetzt
  werden. Man schreibt hierfür $p(x)$, um die Abhängigkeit der aussagenlogischen
  Formel $p$ von der Variable $x$ explizit auszudrücken.

# Begriffe

Grundmenge
:   Die Menge $X$ an für $x$ möglichen Werte.
:   = "Aussageform über $X$"

Gültigkeitsbereich
:   Jene Werte $x = a$, für welche die Aussage $p(a)$ `wahr` ist, wird als
    Gültigkeitsbereich der Aussageform bezeichnet.

- $p(x), q(x) : p(x) \land q(x) \Leftrightarrow (p \land q)(x)
  \Leftrightarrow (p \circ q)(x)$

Aussageform
:   Aussage wo das Subjekt variabel gelassen wurde
:   Schreibweise: $p(x)$

All-Aussage
:   $\forall x \in \N: p(x)$
:   Negation:
    $\neg \forall x \in \N: p(x) \Leftrightarrow \exists x \in \N: \neg p(x)$

Existenz-Aussage
:   $\exists x \in \N: p(x)$
:   Negation:
    $\neg \exists x \in \N: p(x) \Leftrightarrow \forall x \in \N: \neg p(x)$

Gebundene Variablen
:   Sind teile eines All- oder Existenz Aussage ($\exists x$ / $\forall x$)

Freie Variablen
:   Alle anderen Variablen

(Gewöhnliche) Aussage
:   Alle Variablen einer Aussageform sind gebunden.
:   Daher ist der Wahrheitsgehalt wieder ohne Einsetzen eindeutig bestimmbar

# Variable Prädikate

$$
\forall x: p(x) \implies p(a)
$$

> *ist $p$ kein näher spezifiziertes Prädikat, und a keine näher spezifizierte
> Konstante, d.h. es handelt sich hierbei um eine prädikatenlogische Formel.
> Diese werden bisweilen mit griechischen Buchstaben notiert, etwa könnte
> $\psi(p, a)$ die obige Formel bezeichnen.*

# Mathematische Sätze

Mathematischer Satz
:   Eine Deifinition von mathematischem Interesse, von der man weiß, dass sie für einen bestimmten Bereich gültig ist

Logisch Implikation
:   $p(x) \Rightarrow q(x)$ für jedes $p(x)$ da `wahr` ist muss $q(x)$ auch
    `wahr` sein.
:   Ist eine Meta-Aussage

Logische Äquivalenz
:   $p(x) \Leftrightarrow q(x)$ wenn $p$ und $q$ für jede Belegung $x$ aus $X$
    denselben Wert haben.


# (Mathematische) Definition

Eine Definition ist eine vereinbarte logische Äquivalenz von definierten neuen
Begriffen und den definierenden, bereits bekannten, Begriffen oder Eigenschaften.

Symbol für Definition logischer Formeln
:    $\infix$, gelesen als "definiert logisch äquivalent zu".

Symbol für Definition von Termen
:   $\coloneqq$, gelesen als "definiert als"

