---
title: "Serie 09"
date: 2026-06-13T7:53:00+01:00
draft: false
---

# Aufgabe 1: $\| \cdot\|_p$ ist eine Norm

- Ihr könnt auch nur Teile der Aufgabe bearbeiten.
- Vergesst nicht, $p=1$ zu erwähnen.

## (c)

- {{< details >}} Versucht, $\|x+y\|_p^p$ abzuschätzen. {{</ details >}}
- {{< details >}} Dazu bietet sich die Ungleichung aus der Aufgabenstellung an, $|a+b|^p = (|a| + |b|) |a+b|^{p-1}$. {{</ details >}}
- {{< details >}} Jetzt müsst ihr das Distributivgesetz anwenden. {{</ details >}}
- {{< details >}} *Danach* lässt sich auf zwei Terme die Hölder-Ungleichung anwenden. {{</ details >}}
- {{< details >}} Nach einer weiteren kleinen Umformung erhaltet ihr nun die Minkowski-Ungleichung. {{</ details >}}

# Aufgabe 2: $\lim_{p \to \infty} ||x||_p$

- {{< details >}} Ihr könnt zum Beispiel $\lim_{p \to \infty} ||x||_p \leq ||x|| {\infty}$ und $\cdots \geq \cdots$ zeigen. {{</ details >}}

- {{< details >}} Es ist $\lim_{p \to \infty} a^{\frac 1 p} = 1$ für alle $a \geq 0$. {{</ details >}}

- {{< details >}} Betrachtet das $i$ mit $x_i = \max_{k =1}^d |x_k|$. {{</ details >}}

- {{< details >}} Für eine Ungleichung könnt ihr alle anderen $x_k = 0$ setzen. Wie ändert sich die $p$-Norm in dem Fall? {{</ details >}}

- {{< details >}} Für die andere Ungleichung müsst ihr den anderen Extremfall betrachten. {{</ details >}}

# Aufgabe 3: Zweipunktvervollständigung

## (a)

- {{< details >}} Sowohl $\tan$ als auch $\arctan$ sind stetig. {{</ details >}}

- {{< details >}} Ihr könnt auch sehr viele Fallunterscheidungen machen, wenn ihr sichergehen wollt. {{</ details >}}

## (b)

- {{< details >}} Aus Analysis 1 wissen wir, dass eine Folge in $\mathbb R$ immer eine monotone Teilfolge hat. {{</ details >}}

- {{< details >}} Wenn ihr eine Teilfolge in $\mathbb R$ findet, seid ihr also fertig. (Denn dann gibt es eine monotone Teilfolge, und diese hat den Grenzwert ...) {{</ details >}}

- {{< details >}} Wenn es keine Teilfolge in $\mathbb R$ gibt, dann gibt es unendlich viele Folgenglieder, die ...  {{</ details >}}

# Aufgabe 4

## (a)

- {{< details >}} Alle Eigenschaften lassen sich recht leicht nachrechnen. Ihr könnt aber auch benutzen, dass $d_D$ eine Metrik ist. {{</ details >}}

## (b)

- {{< details >}} Nehmt an, ihr hättet eine Cauchy-Folge $(w_m)_m$. Zu finden ist ein Wort, gegen das diese Wörter konvergieren. {{</ details >}}

- {{< details >}} Ein Wort ist eine Abbildung $\mathbb N \to \mathcal A$, ihr müsst also für alle $n \in \mathbb N$ ein $a_n \in \mathbb N$ finden, sodass die Wörter $w_m$ an der Stelle $n$ gegen $a$ konvergieren, d.h. dass $\lim_{m \to \infty} w_m(n) = a_n$ gilt. {{</ details >}}

- {{< details >}} Betrachtet ein $n \in \mathbb N$ und versucht, das richtige $a_n$ zu finden. {{</ details >}}

- {{< details >}} Wenn ihr ein bestimmtes $\epsilon > 0$ betrachtet (siehe letzter Hinweis), könnt ihr sehen, dass $w_m(n)$ in $\mathcal A$ konvergieren muss. {{</ details >}}

- {{< details >}} Was bedeutet Konvergenz in $\mathcal A$? {{</ details >}}

- {{< details >}} Ab $\epsilon = \frac 1 {2^n}$ müssen die ersten $n$ Stellen der Wörter gleich sein. {{</ details >}}
