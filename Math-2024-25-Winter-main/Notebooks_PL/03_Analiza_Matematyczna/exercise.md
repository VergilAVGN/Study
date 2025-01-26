## Functions

1. Draw in a single Geogebra notebook the following functions:

   - $f(x) = x^2$
   - $g(x) = \sqrt{x}$
   - $h(x) = \frac{1}{x}$
   - $j(x) = \sin(x)$

Find value of all the above functions at $x = 2$.
(Найти значения всех этих функций при x= 2)

 - $$f(x) = x^2$$
- $$f(2) = 4$$

---

- $$g(x) = \sqrt{x}$$
- $$g(2) = 1.4142135623731$$
---
- $$h(x) = \frac{1}{x}$$
- $$h(2) = \frac{1}{2} = 0.5$$
---
- $$j(x) = \sin(x)$$
- $$j(2) = 0.9092974268257$$

[link geogebra](https://www.geogebra.org/m/s3vef8hf)


1. Let $f(x) = 3x - 1$ and $g(x) = \sqrt{x}$. Find:
   - $f(g(x))$
   - $g(f(x))$
   - $f(f(x))$
   - $g(g(x))$

and visualize functions in a single Geogebra notebook.

- $$(x) = 3x - 1$$
---
- $$g(x) = \sqrt{x}$$
---
- $$f(g(x)) = 3\sqrt{x} - 1$$
- $$g(f(x)) = \sqrt{3x-1}$$
- $$f(f(x)) = 3(3x-1)-1$$
- $$g(g(x)) = \sqrt{\sqrt{x}}$$

[link geogebra](https://www.geogebra.org/m/hgdh3z34) 

3. Let $f(x) = e^x$ and $g(x) = \ln(x)$. Check: $f(g(x))$ and $g(f(x))$. What do you notice?

- g(f(x)) определена для всех значений x (g(f(x)) jest zdefiniowane dla wszystkich wartości x)
---
- f(g(x))=x для $𝑥>0$ (f(g(x))=x dla $𝑥>0$)
- f(g(x)) не существует при  $𝑥≤0$ (f(g(x)) nie istnieje dla $𝑥≤0$)

[Link geogebra](https://www.geogebra.org/m/trkm49u5)

4. We have function $f=\{(1,7), (2,9), (3,11)\}$. Give inverse function $f^{-1}$.


$$f = \{(1, 7), (2, 9), (3, 11)\}.$$

$$f(x) = ax + b.$$

- подставляем точки $(1,7),(2,9)$ (zamień punkty $(1,7),(2,9)$)

$$a \cdot 1 + b = 7.$$

$$a + b = 7$$

---

$$a \cdot 2 + b = 9$$

$$2a + b =9 $$

---

$$\begin{cases}
a + b = 7, \\
2a + b = 9.
\end{cases}$$

$$(2a + b) - (a + b) = 9 - 7, \quad a = 2$$

подставляем $a=2$ в перове уровнение $a+b = 7$ (podstawiamy $a=2$ na pierwszym poziomie $a+b = 7$)

$$2+b=7,  \quad b=5$$

--------
$$f(x) = 2x+5$$

- Найдём обратную функцию $(f^{-1}(x))$ (Znajdźmy funkcję odwrotną $(f^{-1}(x))$)

$$y = 2x+5$$

$$x = 2y+5$$

$$2y+5 = x$$

$$2y = 5-x$$

$$y = \frac{x - 5}{2}$$
----
Точки обратной функции (Punkty funkcji odwrotnej)
- $$( f(1) = 7 ), ( f^{-1}(7) = 1 ).$$
- $$( f(2) = 9 ),( f^{-1}(9) = 2 ).$$
- $$( f(3) = 11 ),( f^{-1}(11) = 3 ).$$

Точки функции $(f^{-1}(x)):$ (Punkty funkcji $(f^{-1}(x)):$)

$$
f^{-1} = \{(7, 1), (9, 2), (11, 3)\}.
$$

[Link geogebra](https://www.geogebra.org/m/peyx4a9m)


5. We have function $f=\{(1,7), (2,7), (3,11)\}$. Give inverse function $f^{-1}$.

$$f = {(1, 7), (2, 7), (3, 11)}$$

$$f(x) =
\begin{cases}
7, & x = 1 \text{ или } x = 2, \\
11, & x = 3.
\end{cases}$$

----
Точки обратной функции (Punkty funkcji odwrotnej)
- $$( f(1) = 7 ), ( f^{-1}(7) = 1 ).$$
- $$( f(2) = 7 ),( f^{-1}(7) = 2 ).$$
- $$( f(3) = 11 ),( f^{-1}(11) = 3 ).$$

Точки функции $(f^{-1}(x)):$ (Punkty funkcji $(f^{-1}(x)):$)

$$
f^{-1} = \{(7, 1), (7, 2), (11, 3)\}.
$$

$$
f^{-1}(x) =
\begin{cases}
1 \text{ или } 2, & x = 7, \\
3, & x = 11.
\end{cases}
$$

6. We have function $f(x)= x-1$. Give inverse function $f^{-1}$. Show both functions on the same Geogebra notebook.

$$f(x) = x-1$$

- Находим обратную функцию $(f^{-1})$ (Znajdujemy funkcję odwrotną $(f^{-1})$)

$$y = x-1$$

$$x = y-1$$

$$y = x+1$$

$$f^{-1}(x) = x+1$$

[Link geogebra](https://www.geogebra.org/m/ggw9vqpe)

# Limits of Sequences

1. Calculate:
   - $\displaystyle \lim_{n \to \infty} \frac{n^2 + 3n}{2 n^2 - 2n}$

   - $\displaystyle \lim_{n \to \infty} \frac{(2n+3)^3}{n^3-1}$


---

$
\lim_{n \to \infty} \frac{n^2 + 3n}{2n^2 - 2n}.
$


- Разделим числитель и знаменатель на высшую степень $( n )$ --- $( n^2)$: (Podziel licznik i mianownik przez największą potęgę $( n )$ --- $( n^2)$:)

   $$
   \frac{n^2 + 3n}{2n^2 - 2n} = \frac{\frac{n^2}{n^2} + \frac{3n}{n^2}}{\frac{2n^2}{n^2} - \frac{2n}{n^2}} = \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}}.
   $$

- Теперь при $( n \to \infty )$, выражения с $ \frac{1}{n} $ стремятся к нулю, и получаем:(Teraz dla $( n \to \infty )$ wyrażenia z $ \frac{1}{n} $ dążą do zera i otrzymujemy:)

   $$
   \lim_{n \to \infty} \frac{1 + \frac{3}{n}}{2 - \frac{2}{n}} = \frac{1 + 0}{2 - 0} = \frac{1}{2}.
   $$

**Ответ:(Odpowiedź:)** $$\frac{1}{2}$$

---
$$
\lim_{n \to \infty} \frac{(2n + 3)^3}{n^3 - 1}.
$$


- Разделим числитель и знаменатель на высшую степень $(n^3)$:(Podziel licznik i mianownik przez największą potęgę $(n^3)$:)

   $$
   \frac{(2n + 3)^3}{n^3 - 1} = \frac{\left( 2 + \frac{3}{n} \right)^3}{1 - \frac{1}{n^3}}.
   $$

- Теперь при $ n \to \infty $, выражения с $ \frac{1}{n} $ и $ \frac{1}{n^3} $ стремятся к нулю:(Teraz dla $ n \to \infty $ wyrażenia z $ \frac{1}{n} $ i $ \frac{1}{n^3} $ mają tendencję do zera:)

   $$
   \lim_{n \to \infty} \frac{\left( 2 + \frac{3}{n} \right)^3}{1 - \frac{1}{n^3}} = \frac{2^3}{1} = 8.
   $$

**Ответ(Odpowiedź:):** $$8$$

2. Prove using the squeeze theorem:
   - $\displaystyle\lim_{n \to \infty} \frac{\sin(n)}{n}$
---
$$
\lim_{n \to \infty} \frac{\sin(n)}{n}.
$$


1. Заметим, что функция $ \sin(n) $ всегда ограничена, то есть для всех $ n $ выполняется неравенство:(Zauważ, że funkcja $ \sin(n) $ jest zawsze ograniczona, to znaczy dla wszystkich $ n $ zachodzi nierówność:)

   $$
   -1 \leq \sin(n) \leq 1.
   $$

2. Разделим все части неравенства на $ n $ (при $ n > 0 $):(Podzielmy wszystkie części nierówności przez $ n $ (jeśli $ n > 0 $))

   $$
   \frac{-1}{n} \leq \frac{\sin(n)}{n} \leq \frac{1}{n}.
   $$

3. Теперь вычислим пределы левых и правых частей:(Teraz obliczmy granice lewej i prawej części:)

   $$
   \lim_{n \to \infty} \frac{-1}{n} = 0, \quad \lim_{n \to \infty} \frac{1}{n} = 0.
   $$

4. По теореме о промежуточном пределе (среднее значение для ограниченной функции), мы можем заключить, что:(Zgodnie z pośrednim twierdzeniem granicznym (wartość średnia dla funkcji ograniczonej) możemy stwierdzić, że:)

   $$
   \lim_{n \to \infty} \frac{\sin(n)}{n} = 0.
   $$

**Ответ:(Odpowiedź:)** $$0$$

 3. Find the limit of the sequence:
   - $a_n = (1+\frac{1}{n})^n$

---
$$
a_n = \left(1 + \frac{1}{n}\right)^n.
$$

Возьмём логарифм от $a_n$, чтобы упростить выражение. Пусть:
(Aby uprościć wyrażenie, weźmy logarytm $a_n$. Pozwalać:)


$$
\ln(a_n) = n \ln\left(1 + \frac{1}{n}\right).
$$

Теперь нужно найти предел для:(Teraz musisz znaleźć granicę dla:)

$$
\ln(a_n) = n \ln\left(1 + \frac{1}{n}\right).
$$

Для малых $ x $ известно, что: (Dla małych $ x $ wiadomo, że:)
$$
\ln(1 + x) \approx x - \frac{x^2}{2} + \dots
$$
Для $ x = \frac{1}{n} $, имеем:(Dla $ x = \frac{1}{n} $ mamy:)
$$
\ln\left(1 + \frac{1}{n}\right) \approx \frac{1}{n} - \frac{1}{2n^2}.
$$

Подставляем это в выражение для $ \ln(a_n) $:(Zastępujemy to w wyrażeniu $ \ln(a_n) $:)
$$
\ln(a_n) \approx n \left(\frac{1}{n} - \frac{1}{2n^2}\right).
$$

Упрощаем:(Uprośćmy)
$$
\ln(a_n) \approx 1 - \frac{1}{2n}.
$$


Когда $ n \to \infty $: (Kiedy $ n \to \infty $)
$$
\ln(a_n) \to 1.
$$
$ a_n $ стремится к:($ a_n $ ma tendencję do:)
$$
a_n = e^{\ln(a_n)} = e^1 = e.
$$


### Ответ:(Odpowiedź:) ###
$$
\lim_{n \to \infty} \left(1 + \frac{1}{n}\right)^n = e.
$$

## Limits of Real Functions

1. Compute:
   - $\displaystyle\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}$
---
$$
\lim_{x \to \infty} \frac{x^3 + 2x^2}{x^4 - 3x^3}
$$

Разделим числитель и знаменатель на $x^4$(Podzielmy licznik i mianownik przez $x^4$)

$$
\frac{x^3 + 2x^2}{x^4 - 3x^3} = \frac{\frac{x^3}{x^4} + \frac{2x^2}{x^4}}{\frac{x^4}{x^4} - \frac{3x^3}{x^4}}
$$
$$
= \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}}
$$

При $x \to \infty$, дробные члены ($\frac{1}{x}$, $\frac{2}{x^2}$, $\frac{3}{x}$) стремятся к нулю:(Przy $x \to \infty$ wyrazy ułamkowe ($\frac{1}{x}$, $\frac{2}{x^2}$, $\frac{3}{x}$) dążą do zera :)

$$
\lim_{x \to \infty} \frac{\frac{1}{x} + \frac{2}{x^2}}{1 - \frac{3}{x}} = \frac{0 + 0}{1 - 0} = 0
$$

**Ответ:(Odpowiedź:)** $$0$$

2. Find:
   
   - $\displaystyle \lim_{x \to 0} \frac{\sin(3x)}{2x+1}$.
---
$$
\lim_{x \to 0} \frac{\sin(3x)}{2x + 1}
$$

Числитель $\sin(3x)$ стремится к нулю при $x \to 0$. Знаменатель $2x + 1$ стремится к $1$. Подставляем $x = 0$:(Licznik $\sin(3x)$ dąży do zera przy $x \to 0$. Mianownik $2x + 1$ ma tendencję do $1$. Zastąp $x = 0 $:)

$$
\frac{\sin(3x)}{2x + 1} \to \frac{\sin(0)}{2 \cdot 0 + 1} = \frac{0}{1} = 0
$$

**Ответ:(Odpowiedź:)** $$0$$

3. Find the asymptotes of the function:
  
   - $f(x) = \frac{x^2 - 1}{x^2 + 1}$
   - $g(x) = \frac{\sin(x)}{x^2+1}$
---
$$f(x) = \frac{x^2 - 1}{x^2 + 1}:$$



- **Горизонтальные асимптоты(Asymptoty poziome)**:

   Рассмотрим предел $\lim_{x \to \infty} f(x) $:
   
   (Rozważmy granicę $\lim_{x \to \infty} f(x) $:)

   $$
   f(x) = \frac{x^2 - 1}{x^2 + 1} = \frac{1 - \frac{1}{x^2}}{1 + \frac{1}{x^2}}.
   $$
   При $x \to \infty $, $\frac{1}{x^2} \to 0$, поэтому:(Dla $x \to \infty $, $\frac{1}{x^2} \to 0$ ,zatem:)

   $$
   \lim_{x \to \infty} f(x) = \frac{1 - 0}{1 + 0} = 1.
   $$

   Также для предела $ \lim_{x \to -\infty} f(x) $:(Również dla granicy $ \lim_{x \to -\infty} f(x) $:)

   $$
   \lim_{x \to -\infty} f(x) = \frac{1 - 0}{1 + 0} = 1.
   $$

   **Горизонтальная асимптота(Asymptota pozioma)**: $y = 1$.

- **Вертикальных асимптот нет(Nie ma asymptot pionowych)**.

---
$$ g(x) = \frac{\sin(x)}{x+1}: $$

- **Горизонтальные асимптоты(Asymptoty poziome)**:

   Рассмотрим предел $ \lim_{x \to \infty} g(x) $:
   (Rozważmy granicę $ \lim_{x \to \infty} g(x) $:)

   $$
   g(x) = \frac{\sin(x)}{x+1}.
   $$

   Числитель, $\sin(x)$, ограничен (от $-1$ до $1$), а знаменатель $x + 1 \to \infty $. Поэтому:(Licznik $\sin(x)$ jest ograniczony (od $-1$ do $1$), a mianownik wynosi $x + 1 \to \infty $. Dlatego:)
   
   $$
   \lim_{x \to \infty} g(x) = 0.
   $$

   Также для предела $\lim_{x \to -\infty} g(x) $:(Również dla granicy $\lim_{x \to -\infty} g(x) $:)
   
   $$
   \lim_{x \to -\infty} g(x) = 0.
   $$

   **Горизонтальная асимптота(Asymptota pozioma)**: $y = 0$

- **Вертикальные асимптоты(Asymptoty pionowe)**:

   Вертикальные асимптоты возможны, если знаменатель $x + 1 = 0 $, то есть при $ x = -1 $.
   Проверим односторонние пределы в $x = -1 $:(Asymptoty pionowe są możliwe, jeśli mianownik $x + 1 = 0 $, czyli przy $ x = -1 $.
 Sprawdźmy jednostronne granice w $x = -1$:)
   $$
   \lim_{x \to -1^+} g(x) = \lim_{x \to -1^+} \frac{\sin(x)}{x+1} \to \pm\infty,
   $$
   $$
   \lim_{x \to -1^-} g(x) = \lim_{x \to -1^-} \frac{\sin(x)}{x+1} \to \pm\infty.
   $$

   Таким образом, при $x = -1 $ существует вертикальная асимптота.(Zatem przy $x = -1 $ istnieje asymptota pionowa.)

   **Вертикальная асимптота(Asymptota pionowa)**: $$ x = -1$$.

## Derivatives

1. Compute derivatives of functions:(Найти производные функций)
   * $y(x) = -3x+3$
   * $y(x) = \pi x + \sin(1)$
   * $y(x) = 4+\sin(2)$
   * $y(x) = 2x^3 - 3x^2 + 8x - 9$
   * $y(x) = 6 x^{1/3}$
   * $y(x) = \sqrt{x}$
   * $y(x) = \cos(x) + \sin(x)$
   * $y(x) = 2\sin(x) \cos(x)$
   * $y(x) = x\sin(x)$
   * $y(x) = (x+1)(x+1)$
   * $y(x) = \frac{x}{x+1}$
   * $y(x) = (x+1)\exp(x)$
   * $y(x) = \sin(x^2)$
   * $y(x) = \exp(-2x)$
   * $y(x) = \frac{1}{\sin(x+1)}$
   * $y(x) = \sqrt{2x+1}$
---

- $$ y(x) = - 3x + 3 $$

   $$
   y'(x) = -3.
   $$

- $$ y(x) = \pi x + \sin(1) $$

   $$
   y'(x) = \pi.
   $$

- $$ y(x) = 4 + \sin(2) $$

   $$
   y'(x) = 0.
   $$

- $$ y(x) = 2x^2 - 3x^2 + 8x - 9 $$

   $$
   y'(x) = -2x + 8.
   $$

- $$ y(x) = 6x^{1/3} $$

   $$
   y'(x) = 2x^{-2/3}.
   $$

- $$ y(x) = \sqrt{x} $$

   $$
   y'(x) = \frac{1}{2\sqrt{x}}.
   $$

- $$y(x) = \cos(x) + \sin(x)$$

   $$
   y'(x) = -\sin(x) + \cos(x).
   $$

- $$y(x) = 2\sin(x)\cos(x)$$

   Используем формулу:(Używamy wzoru:)
   
   $$y'(x) = u'v + uv'$$

   $$
   y'(x) = 2(\cos(x) \cdot \cos(x) - \sin(x) \cdot \sin(x)) = 2\cos(2x).
   $$

- $$y(x) = \exp(x^2)$$

   $$y'(x) = \exp(x^2) \cdot 2x = 2x \exp(x^2)$$

- $$y(x) = \sqrt{x+1}$$

    $$
    y'(x) = \frac{1}{2\sqrt{x+1}}.
    $$
---
2. Prove:
   - $\frac{d}{dx} (\ln(\sin(x))) = \cot(x)$
---
 
Если функция имеет вид $y = \ln(u(x)) $, то производная равна:(Jeżeli funkcja ma postać $y = \ln(u(x)) $, to pochodna jest równa:)  

$$
\frac{d}{dx} \ln(u(x)) = \frac{u'(x)}{u(x)}.
$$


 
В нашем случае $u(x) = \sin(x)$.(W naszym przypadku $u(x) = \sin(x)$.)

$$
\frac{d}{dx} \ln(\sin(x)) = \frac{\frac{d}{dx} \sin(x)}{\sin(x)}.
$$



$$
\frac{d}{dx} \ln(\sin(x)) = \frac{\cos(x)}{\sin(x)}.
$$


 
Дробь(ułamek) $\frac{\cos(x)}{\sin(x)}$ = $\cot(x)$:

$$
\frac{d}{dx} \ln(\sin(x)) = \cot(x).
$$


### Ответ(Odpowiedź):  
$$
\frac{d}{dx} \ln(\sin(x)) = \cot(x).
$$

---
3. For $f(x) = \cos(x)$, verify that $f''(x) = -f(x)$.

Если $f(x) = \cos(x)$,первая производная равна(jeśli $f(x) = \cos(x)$, pierwsza pochodna jest równa:):

$$
f'(x) = \frac{d}{dx} \cos(x) = -\sin(x).
$$

Теперь берём производную от $f'(x) = -\sin(x)$ (Teraz bierzemy pochodną $f'(x) = -\sin(x)$ :) :

$$
f''(x) = \frac{d}{dx} \left( -\sin(x) \right) = -\cos(x).
$$

Мы видим, что:(Widzimy, że:)

$$
f''(x) = -\cos(x) \quad \text{и} \quad -f(x) = -\cos(x).
$$

равенство $f''(x) = -f(x) $ выполнено.

(równość $f''(x) = -f(x) $ jest spełniona.)

---

4. Using de l'Hospital's Rule, find the improper limits:
   - $\displaystyle \lim_{x\to 0} \frac{\sin{x}}{x}$

   - $\displaystyle \lim_{x\to \infty} \frac{\ln x}{x}$

   - $\displaystyle \lim_{x\to \infty} \frac{\exp(x)}{x}$

---
 1. $$\lim_{x \to 0} \frac{\sin(x)}{x}$$
 
Найдем производные числителя и знаменателя:(Znajdźmy pochodne licznika i mianownika:)
- $$ f'(x) = \cos(x), $$
- $$ g'(x) = 1 $$

Подставляем производные в предел:(Do limitu podstawiamy instrumenty pochodne:)

$$
\lim_{x \to 0} \frac{\sin(x)}{x} = \lim_{x \to 0} \frac{\cos(x)}{1} = \cos(0) = 1.
$$

**Ответ:(odpowiedź)**  
$$
\lim_{x \to 0} \frac{\sin(x)}{x} = 1.
$$



2. $$ \lim_{x \to \infty} \frac{\ln(x)}{x} $$

 
Найдем производные числителя и знаменателя:(Znajdźmy pochodne licznika i mianownika:)
- $$ f'(x) = \frac{1}{x}, $$
- $$ g'(x) = 1 $$

Подставляем производные в предел:(Do limitu podstawiamy instrumenty pochodne:)

$$
\lim_{x \to \infty} \frac{\ln(x)}{x} = \lim_{x \to \infty} \frac{\frac{1}{x}}{1} = \lim_{x \to \infty} \frac{1}{x} = 0.
$$

**Ответ:(odpowiedź)**  
$$
\lim_{x \to \infty} \frac{\ln(x)}{x} = 0.
$$



3. $\lim_{x \to \infty} \frac{\exp(x)}{x}$


Найдем производные числителя и знаменателя: (Znajdźmy pochodne licznika i mianownika:)
- $$ f'(x) = \exp(x) ,$$
- $$ g'(x) = 1 $$

Подставляем производные в предел: (Do limitu podstawiamy instrumenty pochodne:)

$$
\lim_{x \to \infty} \frac{\exp(x)}{x} = \lim_{x \to \infty} \frac{\exp(x)}{1} = \infty.
$$

**Ответ:(odpowiedź)**  
$$
\lim_{x \to \infty} \frac{\exp(x)}{x} = \infty.
$$

---

5. In physics, the position of a particle is given by $x(t) = 3t^2 - 6t + 1$. Find the velocity $V(t)=x'(t)$ and acceleration $a(t)=V'(t)=x''(t)$ of the particle at time $t = 2$.

(В физике положение частицы определяется выражением $x(t) = 3t^2 - 6t + 1$. Найдите скорость $V(t)=x'(t)$ и ускорение $a(t)=V'(t)=x''(t)$ частицы в момент времени $t = 2$.)

находим первую производную(Скорость $V(t)$): (znajdujemy pierwszą pochodną (Prędkość $V(t)$):)

$$V(t)=x'(t) = 6t - 6$$

находим вторую производную(ускорение $a(t)$): (znajdujemy drugą pochodną (przyspieszenie $a(t)$):)

 $$a(t)=V''(t)=x''(t) = 6$$

подставляем $t=2$: (substytut $t=2$:)

$$V(2) = 6 \cdot 2 - 6 = 12 - 6 = 6$$

$$a(2) = 6$$

### Ответ(odpowiedź): 
$$V(2) =  6$$

$$a(2) = 6$$

## Integrals

1. Compute:
   - $\int 1 dx$
   - $\int (x^2 +2) dx$
   - $\int 2\sin(x) dx$
   - $\int \frac{3}{x} dx$
   - $\int \frac{1}{x^2} dx$
   - $\int \left( \frac{1}{3}x^4 - 5 \right) \, dx$
   - $\int (\sin^2 x + \cos^2 x) \, dx$
   - $\int (5 \sin x + 3e^x) \, dx$
   - $\int \sqrt[3]{x} \, dx$
   - $\int \sqrt{10x} \, dx$
   - $\int \cos\left(\frac{5}{2}x + 3\right) \, dx$
   - $\int \frac{\cos(\ln(x))}{x} \, dx$
   - $\int x \ln(x) \, dx$
   - $\int x e^x \, dx$
---
### 1. $\int 1 \, dx$
Интегрируем:(całkujemy:)
$$
\int 1 \, dx = x + C,
$$

---

### 2. $\int (x^2 + 2) \, dx$
интегрируем по частям:(całkujemy przez części:)
$$
\int x^2 \, dx = \frac{x^3}{3}, \quad \int 2 \, dx = 2x.
$$
соединяем:(łączymy:)
$$
\int (x^2 + 2) \, dx = \frac{x^3}{3} + 2x + C.
$$

---

### 3. $\int 2\sin(x) \, dx$
интегрируем:(całkujemy:)
$$
\int 2\sin(x) \, dx = -2\cos(x) + C.
$$

---

### 4. $\int \frac{3}{x} \, dx$
Интегрируем:(całkujemy:)
$$
\int \frac{3}{x} \, dx = 3\ln|x| + C.
$$

---

### 5. $\int \frac{1}{x^2} \, dx$
Перепишем:(Przepiszmy:) $$\frac{1}{x^2} = x^{-2}$$
Интегрируем:(całkujemy:)
$$
\int x^{-2} \, dx = \frac{x^{-1}}{-1} = -\frac{1}{x} + C.
$$

---

### 6. $\int \left(\frac{1}{3}x^4 - 5\right) \, dx$
интегрируем по частям:(całkujemy przez części:)
$$
\int \frac{1}{3}x^4 \, dx = \frac{1}{15}x^5, \quad \int -5 \, dx = -5x.
$$
соединяем:(łączymy:)
$$
\int \left(\frac{1}{3}x^4 - 5\right) \, dx = \frac{1}{15}x^5 - 5x + C.
$$

---

### 7. $\int (\sin^2 x + \cos^2 x) \, dx$
По тригонометрической тождественности:(Na podstawie tożsamości trygonometrycznej:)
 $$\sin^2x + \cos^2x = 1$$
Интегрируем:(całkujemy:)
$$
\int (\sin^2 x + \cos^2 x) \, dx = \int 1 \, dx = x + C.
$$

---

### 8. $\int (5 \sin x + 3e^x) \, dx$
интегрируем по частям:(całkujemy przez części:)
$$
\int 5\sin x \, dx = -5\cos x, \quad \int 3e^x \, dx = 3e^x.
$$
Соединяем:(łączymy:)
$$
\int (5 \sin x + 3e^x) \, dx = -5\cos x + 3e^x + C.
$$

---

### 9. $\int \sqrt[3]{x} \, dx$
Перепишем:(Przepiszmy:) $$\sqrt[3]{x} = x^{1/3}$$
Интегрируем:(całkujemy:)
$$
\int x^{1/3} \, dx = \frac{x^{4/3}}{4/3} = \frac{3x^{4/3}}{4} + C.
$$

---

### 10. $\int \sqrt{10x} \, dx$
Перепишем:(Przepiszmy:) $$\sqrt{10x} = (10x)^{1/2}$$
интегрируем:(całkujemy:)
$$
\int (10x)^{1/2} \, dx = \sqrt{10} \int x^{1/2} \, dx = \sqrt{10} \cdot \frac{x^{3/2}}{3/2} = \frac{2\sqrt{10}}{3}x^{3/2} + C.
$$

---
### 11. $\int \cos\left(\frac{5}{2}x + 3\right) \, dx$

Пусть(Niech)

$$
t = \frac{5}{2}x + 3, \quad \text{тогда(zatem)} \quad \frac{dt}{dx} = \frac{5}{2}, \quad \text{,} \quad dx = \frac{2}{5} \, dt.
$$

Подставим это в интеграл:(Podstawmy to do całki)

$$
 \int \cos(t) \cdot \frac{2}{5} \, dt.
$$

Вынесем константу перед интегралом:(Usuńmy stałą przed całką)

$$
\frac{2}{5} \int \cos(t) \, dt.
$$

Интегрируем:(całkujemy:)

$$
\frac{2}{5} \int \cos(u) \, du = \frac{2}{5} \sin(u) + C,
$$


Подставляем(Podstawiamy) $t = \frac{5}{2}x + 3$:

$$
\frac{2}{5} \sin\left(\frac{5}{2}x + 3\right) + C.
$$
---
### 12. $\int \frac{\cos(\ln(x))}{x} \, dx$

Пусть(Niech)

$$
t = \ln(x), \quad \text{тогда(zatem)} \quad \frac{dt}{dx} = \frac{1}{x}, \quad \text{,} \quad dx = x \, dt.
$$

Подставим это в интеграл:(Podstawmy to do całki)

$$
 \int \cos(t) \, dt.
$$

Интегрируем:(całkujemy:)

$$
\int \cos(t) \, dt = \sin(t) + C,
$$



подставляем(Podstawiamy) $t = \ln(x)$:

$$
 \sin(\ln(x)) + C
$$

---

2. Calculate integrals over the interval $[0, \pi]$ and visualize them in Geogebra:
   - $f(x)=2x+1$
   - $g(x)=x^2$
   ---
### 1. $f(x)=2x+1$

$$\int_{0}^{\pi} (2x + 1) \, dx$$

Интегрируем:(całkujemy:)
$$\left[ x^2 + x \right]_{0}^{\pi}$$
Подставляем сначала $\pi$ вместо $x$ потом 0 вместо $x$(Najpierw podstawiamy $\pi$ zamiast $x$, następnie 0 zamiast $x$)
$$= (\pi^2 + \pi) - (0^2 + 0) = \pi^2 + \pi$$

**Ответ:(odpowiedź)** 
$$\pi^2 + \pi$$

[link geogebra](https://www.geogebra.org/m/dbtngsxu)
---
### 2. $g(x)=x^2$

$$\int_{0}^{\pi} x^2 \, dx$$
Интегрируем:(całkujemy:)
$$\left[ \frac{x^3}{3} \right]_{0}^{\pi}$$
Подставляем сначала $\pi$ вместо $x$ потом 0 вместо $x$:(Najpierw podstawiamy $\pi$ zamiast $x$, następnie 0 zamiast $x$)
$$=(\frac{\pi^3}{3}) - (\frac{0^3}{3}) = \frac{\pi^3}{3}$$
**Ответ:(odpowiedź)** 
$$\frac{\pi^3}{3}$$

[link geogebra](https://www.geogebra.org/m/kfz9jjta)
---
3. Calculate the area of the region bounded by the lines:
$x = 1$, $x = 2$, $y = 0$, and $y = x^2 + 1$. Show it in Geogebra.
---
$$\int_1^2 x^2 + 1\, dx$$
Интегрируем:(całkujemy:)
$$= \left[ \frac{x^3}{3} + x\right]_{1}^{2}$$
Подставляем сначала 2 вместо $x$ потом 1 вместо $x$:(Najpierw podstawiamy 2 zamiast $x$, następnie 1 zamiast $x$:)
$$= \left( \frac{2^3}{3} + 2 \right) - \left( \frac{1^3}{3} + 1 \right)$$
Упрощаем:(Uprośćmy:)
$$= \left( \frac{8}{3} + 2 \right) - \left( \frac{1}{3} + 1 \right)= \left( \frac{8}{3} + \frac{6}{3} \right) - \left( \frac{1}{3} + \frac{3}{3} \right)= \frac{14}{3} - \frac{4}{3} = \frac{10}{3}$$
**Ответ:(odpowiedź)** 
$$\frac{10}{3}$$
[link geogebra](https://www.geogebra.org/m/by7z8ayc)
---
4. Calculate the area under the sine curve over the interval $[0, \pi]$, using:

$$P = \int_a^b f(x) \, dx = \int_0^\pi \sin(x) \, dx$$
---
$$P = \int_0^\pi \sin(x) \, dx$$
Интегрируем:(całkujemy:)
$$= \left[ -\cos(x) \right]_0^\pi$$
Подставляем сначала $\pi$ вместо $x$ потом 0 вместо $x$:(Najpierw podstawiamy $\pi$ zamiast $x$, następnie 0 zamiast $x$:)
$$= -\cos(\pi) + \cos(0)$$

Мы знаем что:(Wiemy, że:)
$$\cos(\pi) = -1 \quad \text{і} \quad \cos(0) = 1$$
Тогда:(Następnie:)
$$= -(-1) + 1 = 1 + 1 = 2$$
**Ответ:(odpowiedź)** 
$$P=2$$
---
6. Find the distance of the moving particle between time $t=0$ and $t=2$ for the following position function: $x(t) = 3t^2 - 6t + 1$.(Найдите расстояние движущейся частицы между моментами времени $t=0$ и $t=2$ для следующей функции положения: $x(t) = 3t^2 - 6t + 1$.)
---
$$x(t) = 3t^2 - 6t + 1$$

Найдем скорость v(t):(Znajdźmy prędkość v(t):)  
$$v(t) = \frac{d}{dt}(3t^2 - 6t + 1) = 6t - 6$$


Найдем момент, когда скорость равна нулю,приравниваем скорость к нулю:(Znajdźmy moment, w którym prędkość wynosi zero, przyrównajmy prędkość do zera:)

$$
6t - 6 = 0 \implies t = 1
$$

Вычислим интегралы.(Obliczmy całki.)

1. Для(Dla) $ t \in [0, 1] $:
   $$
   \int_0^1 (6t - 6) \, dt = \left[3t^2 - 6t  \right]_0^1 = (3 - 6) - (0 - 0) = -3
   $$

2. Для(Dla) $ t \in [1, 2] $:
   $$
   \int_1^2 (6t - 6) \, dt = \left[ 3t^2 - 6t \right]_1^2 = \left( 3(2)^2 - 6(2) \right) - \left( 3(1)^2 - 6(1) \right)
   $$
   $$
   = (12 - 12) - (3 - 6) = 0 - (-3) = 3
   $$


суммируем оба интеграла:(sumujemy obie całki:)
$$
3 +(- 3) = 3 - 3 = 0
$$

**Ответ:(odpowiedź)** $$0$$