---
title: Lernziele
subtitle: Endlose Schmerzen
author: Verzweifelte Studierende
date: 18. Dezember 2023
toc: true
lang: de-AT
font-family: sans-serif
latex-header:
   - \usepackage{pifont}% http://ctan.org/pkg/pifont
   - \usepackage{cancel}
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
   - \renewcommand{\equiv}{\leftrightarrow}
   - \newcommand{\Equiv}{\Leftrightarrow}
---

\newpage

# Aussagen- und Prädikatenlogik

- **Was versteht man unter Aussagen, Aussageformen, und wie können (einfache) Aussagen/Aussageformen zu komplexeren Aussagen/Aussageformen verknüpft werden?**

   1. Aussagen: Wahrheitsgehalt muss eindeutig zuordenbar sein. Entweder atomar oder durch Junktoren verknüpft.
      Zuordnung eines bestimmten Prädikats zu einem bestimmten Subjekt.
   2. Aussageform: Zuordnung eines bestimmten Prädikats zu einem variablen Subjekt.

- **Was versteht man unter einer logischen Implikation und einer logischen Äquivalenz? Wie können diese zur Überprüfung von Wahrheitsgehalten angewandt, bzw. selbst auf ihren Wahrheitsgehalt überprüft werden?**
  
   1. Logische Implikation: $p(x) \Implies q(x)$, wenn $p(x)$ wahr ist,
      muss auch $q(x)$ gelten. 
   2. Logische Äquivalenz: $p(x) \Equiv q(x)$, $p(x)$ und $q(x)$
      müssen für dieselben $x$ dieselben Werte ergeben. Die
      Wahrheitstabellen sind ident.

- **Welche Arten logischen Schlussfolgerns gibt es?**

   1. Modus Ponens
   2. Modus Tollens
   3. Syllogismus
   4. Beweis durch Widerspruch

- **Was ist ein Prädikat und Prädikatenlogik?**

   1. Prädikat: Eine Aussage die einem konkreten Subjekt zugeordnet.
      = Aussagenlogische Formel. Eine Funktion, die einem Subjekt $x$
      einen Wahrheitswert zuordnet.
   2. Prädikatenlogik: Lässt die Subjekte variable.

- **Was sind All- und Existenzquantoren? Welche Gesetzmäßigkeiten gelten hierfür?**

   1. Allquantor: $\forall x \in X: p(x)$, muss für alle möglichen $x$
                  aus der Grundmenge $X$ stimmen.
   2. Existenzquantor: $\exists x \in X: p(x)$, muss für mindestens ein $x$
                       aus der Grundmenge $X$ stimmen.

- **Welche Gesetze der Aussagen- und der Prädikatenlogik kennen Sie?**

   ![](aussagenlogische_gesetze.png){ height="20%" }

- **Was sind mathematische Definitionen und Sätze? Was versteht man unter einem Beweis?**

   1. Mathematische Definition: Man führt etwas neues ein und beweist
                                es mit bereits bestehenden Sätze.
   2. Mathematische Sätze: Gesetzmäßigkeiten von großer Relevanz.
   3. Beweis: Anhand von existenten Wissen mit klaren Techniken auf
              neues Wissen führen.
