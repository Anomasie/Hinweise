---
title: "Serie 11"
date: 2026-06-24T16:36:00+01:00
draft: false
---

# Aufgabe 1

## (a): Charakterisierung Abgeschlossenheit

- Diese Aufgabe ist sehr wichtig und eine gute Übung. Es gibt verschiedene Lösungswege für die Aufgabe.

- **Nicht-Abgeschlossenheit bedeutet nicht Offenheit**. Mengen können sowohl abgeschlossen als auch offen sein (zum Beispiel $\emptyset$ oder der ganze Raum.) Oder gar nichts von beidem. (Zum Beispiel $[0, 1) \subseteq \mathbb R$.)

### $A$ ist abgeschlossen $\implies$ ... :

- {{< details >}} Ziel ist es, für eine solche Folge festzustellen, dass ihr Grenzwert nicht in $A^c$ liegen kann. {{</ details >}}

- {{< details >}} ... weil $A^c$ offen ist. {{</ details >}}

- {{< details >}} ... und die Folge dann irgendwann in $A^c$ liegen muss. {{</ details >}}

### ... $\implies$ $A$ ist abgeschlossen:

- {{< details >}} Ihr könnt zum Beispiel einen indirekten Beweis führen (das heißt, statt $a \implies b$ zeigt ihr $\neg b \implies \neg a$.){{</ details >}}

- {{< details >}} Wenn $A^c$ nicht offen ist, existiert ein $y$, sodass für alle $r > 0$ ... {{</ details >}}

- {{< details >}} Jetzt müsst ihr zeigen, dass die eine Folge $(x_n)$ in $A$ existiert, die gegen $y$ konvergiert. {{</ details >}}

## (b) Charakterisierung Abschluss

### $\bar A \supseteq$ (Grenzwerte in $A$):

- Das lässt sich aus (a) schlussfolgern.

- Wenn ihr das Gefühl habt, das gleiche wie in (a) aufzuschrieben, lohnt es sich, kurz zu überlegen und stattdessen die Aussage aus (a) zu verwenden.

### $\bar A \subseteq$ (Grenzwerte in $A$):

- {{< details >}} Die Menge der $x$ für die eine Folge in $A$ existiert, die gegen $x$ konvergiert, ist abgeschlossen, weil ... {{</ details >}}

- {{< details >}} ... das ist ein Diagonalfolgenargument und die Charakterisierung aus (a). {{</ details >}}

- {{< details >}} Die Menge der Grenzwerte aus $A$ enthält offensichtlich $A$ (weil für jedes $x \in A$ ...) {{</ details >}}

# Aufgabe 2: $\|A\|$

## (c) Stetigkeit linearer Abbildungen

- {{< details >}} Ihr könnt zeigen, dass $A$ Lipschitz-stetig ist. {{</ details >}}

- {{< details >}} Benutzt (b). {{</ details >}}

# Aufgabe 3: $f$ ist stetig genau dann, wenn alle $f_i$ stetig sind.

## Ist $f$ stetig, dann sind alle $f_i$ stetig:

- {{< details >}} Zum Beispiel könnt ihr zeigen, dass die Abbildungen $p_i \colon \R^m \to \R$, $p_i(x) = x_i$ stetig sind. {{</ details >}}

- {{< details >}} Dann ist $f_i$ eine Komposition zweier stetiger Funktionen. {{</ details >}}

## Sind alle $f_i$ stetig, dann ist $f$ auch stetig:

- {{< details >}} Betrachtet zum Beispiel $|f(x) - f(y)|^2$ für $x,y \in U$. {{</ details >}}

- {{< details >}} Alle $|f_i(x) - f_i(y)| \to 0$ für $x$ nahe $y$, $i \in \{1, \dots, n\}$. {{</ details >}}

# Aufgabe 4: Stetigkeit, Richtungsstetigkeit und partielle Stetigkeit

## (a) $f_1(x,y) = \frac{xy}{x^2+y^2}$ für $(x,y) \neq 0, f(0,0) = 0$

### Nicht-Richtungsstetigkeit

- {{< details >}} Wie könnt ihr $y$ in Abhängigkeit von $x$ wählen, sodass $f_1(x,y) \not \to 0$ für $x \to 0$? {{</ details >}}

- {{< details >}} Versucht einfach die einfachsten Möglichkeiten für $y$ aus. ($y = 0$ wird nicht funktionieren, weil $f_1$ partiell stetig ist.) {{</ details >}}

## (b) $f_2(x,y) = \frac {xy^2}{x^2+y^4}$

### Richtungsstetigkeit

- {{< details >}} Es reicht, $x = 0$ und $y = ax$ zu betrachten (für alle $a \in \R$). {{</ details >}}

### Nicht-Stetigkeit

- {{< details >}} Versucht, $x$ in Abhängigkeit von $y$ zu finden, sodass $f(x,y)$ nicht gegen $0$ konvergiert für $y \to 0$. {{</ details >}}

- {{< details >}} Tatsächlich könnt ihr $f(x(y),y) = 1$ für alle $y$ erreichen. {{</ details >}}

## (c) $f_3(x,y) = \frac{xy^2}{x^2+y^2}$

- {{< details >}} Es gilt $|y^2| \leq |(x,y)|^2$. {{</ details >}}
