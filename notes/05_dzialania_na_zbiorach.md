# Działania na zbiorach

## Podstawowe działania

Niech $X$ i $Y$ będą zbiorami.

### Suma zbiorów

**Sumą zbiorów** $X$ i $Y$ nazywamy zbiór zawierający wszystkie elementy, które należą do zbioru $X$ lub do zbioru $Y$.

Symbolicznie:

$$
x\in X\cup Y
\iff
(x\in X\lor x\in Y).
$$

Równoważnie, w zapisie opisującym elementy zbioru:

$$
X\cup Y=\{x:x\in X\lor x\in Y\}.
$$

Symbol $\lor$ oznacza logiczne „lub”. Element należący do obu zbiorów zapisujemy w sumie tylko raz.

---

### Iloczyn (przekrój) zbiorów

**Iloczynem** lub **przekrojem zbiorów** $X$ i $Y$ nazywamy zbiór zawierający wszystkie elementy, które należą jednocześnie do $X$ i do $Y$.

Symbolicznie:

$$
x\in X\cap Y
\iff
(x\in X\land x\in Y).
$$

Równoważnie:

$$
X\cap Y=\{x:x\in X\land x\in Y\}.
$$

Symbol $\land$ oznacza logiczne „i”.

---

### Różnica zbiorów

**Różnicą zbiorów** $X$ i $Y$ nazywamy zbiór zawierający elementy, które należą do $X$, ale nie należą do $Y$.

Symbolicznie:

$$
x\in X\setminus Y
\iff
(x\in X\land x\notin Y).
$$

Równoważnie:

$$
X\setminus Y=\{x:x\in X\land x\notin Y\}.
$$

Różnica nie jest przemienna:

$$
X\setminus Y\ne Y\setminus X
$$

w ogólnym przypadku.

---

### Dopełnienie zbioru

Ustalmy **zbiór pełny** (uniwersum) $I$. **Dopełnieniem zbioru** $X$ nazywamy zbiór wszystkich elementów uniwersum, które nie należą do $X$.

Na fotografii dopełnienie oznaczono symbolem $X'$.

Symbolicznie:

$$
x\in X'
\iff
x\notin X.
$$

Równoważnie:

$$
X'=\{x:x\notin X\}.
$$

Dokładniej, z jawnym wskazaniem uniwersum:

$$
X'=I\setminus X
=\{x\in I:x\notin X\}.
$$

Dopełnienie zawsze zależy od wybranego zbioru pełnego $I$.

## Zestawienie oznaczeń

| Działanie | Oznaczenie | Warunek przynależności |
|---|---|---|
| suma | $X\cup Y$ | $x\in X$ lub $x\in Y$ |
| iloczyn / przekrój | $X\cap Y$ | $x\in X$ i $x\in Y$ |
| różnica | $X\setminus Y$ | $x\in X$ i $x\notin Y$ |
| dopełnienie | $X'$ | $x\notin X$ w ustalonym uniwersum |

## Przykłady dla zbiorów skończonych

Niech

$$
X=\{1,2,3,5\},
\qquad
Y=\{1,3,4,7\}.
$$

### Suma

Zbieramy wszystkie elementy występujące w co najmniej jednym zbiorze:

$$
X\cup Y
=\{1,2,3,5\}\cup\{1,3,4,7\}
=\{1,2,3,4,5,7\}.
$$

### Iloczyn

Wybieramy elementy wspólne dla obu zbiorów:

$$
X\cap Y
=\{1,2,3,5\}\cap\{1,3,4,7\}
=\{1,3\}.
$$

### Różnica

Usuwamy ze zbioru $X$ wszystkie elementy należące do $Y$:

$$
X\setminus Y
=\{1,2,3,5\}\setminus\{1,3,4,7\}
=\{2,5\}.
$$

Dla porównania:

$$
Y\setminus X=\{4,7\}.
$$

Widać więc, że kolejność w różnicy zbiorów ma znaczenie.

## Przykłady dla przedziałów

Niech

$$
A=\{x:0<x<7\},
\qquad
B=\{x:2<x<10\}.
$$

W zapisie przedziałowym:

$$
A=(0,7),
\qquad
B=(2,10).
$$

### Suma przedziałów

$$
A\cup B
=\{x:0<x<10\}
=(0,10).
$$

Przedziały nachodzą na siebie, dlatego ich suma tworzy jeden większy przedział.

### Iloczyn przedziałów

$$
A\cap B
=\{x:2<x<7\}
=(2,7).
$$

Są to liczby należące jednocześnie do obu przedziałów.

### Różnica przedziałów

$$
A\setminus B
=\{x:0<x\le2\}
=(0,2].
$$

Liczba $2$ należy do wyniku, ponieważ należy do $A$, ale nie należy do otwartego przedziału $B=(2,10)$.

## Przykłady dopełnień

Przyjmujemy, że uniwersum stanowi zbiór liczb rzeczywistych $\mathbb R$.

### Dopełnienie dodatnich liczb rzeczywistych

$$
\{x:x>0\}'
=\{x:x\le0\}
=(-\infty,0].
$$

### Dopełnienie przedziału $(0,7)$

$$
\{x:0<x<7\}'
=\{x:x\le0\lor x\ge7\}.
$$

W zapisie przedziałowym:

$$
(0,7)'
=(-\infty,0]\cup[7,\infty).
$$

Końce $0$ i $7$ należą do dopełnienia, ponieważ nie należą do otwartego przedziału $(0,7)$.

## Interpretacja na diagramie Venna

Dwa zachodzące na siebie koła reprezentują zbiory $A$ i $B$:

- $A\cup B$ — cały obszar obu kół;
- $A\cap B$ — część wspólna kół;
- $A\setminus B$ — część koła $A$ leżąca poza $B$;
- $B\setminus A$ — część koła $B$ leżąca poza $A$;
- $A'$ — cały obszar uniwersum poza kołem $A$.

## Najważniejsze uwagi

1. W sumie wystarczy przynależność do przynajmniej jednego zbioru.
2. W iloczynie wymagana jest jednoczesna przynależność do obu zbiorów.
3. W różnicy kolejność zbiorów ma znaczenie.
4. Dopełnienie można określić dopiero po ustaleniu zbioru pełnego.
5. Nawias okrągły oznacza, że koniec przedziału nie należy do zbioru, a nawias kwadratowy — że należy.
