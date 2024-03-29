## Мотивация

Целью метода фотографий есть решение разного рода уравнений и построение разного рода инвариантов.

Сформулируем утверждение. Пусть есть пять точек на плоскости, $\{a,b,c,d,e\}$. При этом $\{a,b,c,d\}$ и $\{a,b,c,e\}$ лежат на одной окружности, тогда если взять любую четверку из пяти, например $\{a,b,d,e\}$, $\{a,c,d,e\}$  или $\{a,b,c,e\}$ и т.д., то они все будут лежать на одной окружности.

Это утверждение не совсем верное, но оно почти верное. Вообще говоря, когда мы говорим про три точки которые лежат на одной окружности, то эта окружность может быть не единственной, если некоторые из этих точек совпадают. Тогда возникают некоторые трудности, такие как деление на ноль (или другие нетиривиальные вещи из алгебраической геометрии).

Предположим, что есть две точки $A,B$ и эти две точки имеют одинаковую вещественную часть. Предположим, что $B,C$ имеют одинаковую вещественную часть. Тогда $A,C$ имеют одинаковую вещественную часть. Эта тавтология имеет значение в группах кос.

Переформулируем утверждение. Имеются три точки и имеются вертикальные прямые. Если точки $1,2$ лежат на одной вертикальной прямой и если точки $1,3$ лежат на вертикальной прямой, то $2,3$ лежат на вертикальной прямой. Т.е. мы имеем дело с семейством вертикальных прямых.

Можно сформулировать такое же утверждение про тройки точек не про вертикальные прямые, а про произвольные прямые. Например предположим, что у нас есть 4 точки $A,B,C,D$ и предположим, что $A,B,C$ лежат на одной прямой (необязательно вертикальной) и $A,B,D$ лежат на одной прямой (необязательно вертикальной), тогда из этой четверки любая тройка лежит на одной прямой (необязательно вертикальной).

А что значит, что три точки лежат на одной прямой? Это значит, что обычное несложное отношение является вещественным. Т.е. это можно записать в виде уравнения.

> Например, можно сказать, что если $A,B,C$ лежат на одной прямой, то это значит, что $\frac{C-A}{C-B}$ является вещественным числом, или что то же самое, что если записывать это число в вещественных и мнимых координатах, то у этого комплексного числа комплексная координата равна нулю.

Т.е. первый шаг - это пары и вертикальные прямые, второй - это тройки и всевозможные прямые. Третий шаг - это четверки и окружности.

Пусть у нас имеются четыре точки $\{a,b,c,d\}$ и еще одна точка $e$. Предположим, что $\{a,b,c,d\}$ лежат на одной прямой или окружности и $\{a,b,c,e\}$ лежат на одной прямой или окружности, тогда из пятерки $\{a,b,c,d, e\}$ любая четверка лежит на одной прямой или окружности. 

## Двойное отношение

Пусть $A,B,C,D$ - комплексные числа, тогда:

$$
\frac{D-A}{C-A}\cdot \frac{C-B}{D-B}
$$
Это выражение может быть либо комплексным числом, либо бесконечностью. Утверждается, что двойное отношение является вещественным, т. и т. т. к. четыре точки лежат на одной окружности или прямой.

> Если предположить, что точки $A$ и $B$ лежат на одной прямой и $C$ тоже оказалась на этой же прямой, то тогда легко заметить, что если $D$ не попадает на прямую, то двойное отношение вещественным не будет. Но если $D$ попадает, то оно будет вещественным.

> Существуют т.н. дробно-линейное преобразование, которое позволяет перевести любые три точки в любые три точки и прямые или окружности в прямые или окружности. И эта группа сохраняет двойное отношение. Т.е. мы можем взять преобразование, три точки положить на прямую как хотим, а четвертая, если лежала на окружности или прямой, то она будет лежать на окружности или прямой `FIXME: переписать это предложение`.

Можно ли устроить иерархию из этих примеров и какого рода будет эта иерархия? Можно ли устроить 4, 5, 6, 7 и т.д., пример?

Можно рассматривать кривые старших порядков. Возможно можно говорить про кривые второго порядка...

Но на данный момент метод не сформулирован, **сформулированы** несколько очевидных **утверждений** и для этих утверждений **сформулированы** некоторые **формулы**. Например, взять формулу двойного отношения. Если у нас есть пять точек $A,B,C,D,E$, то можно написать двойное отношение для $A,B,C,D$, а можно для $A,B,C,E$. Если два числа вещественные, то три других будут вещественные. Но для этого нужно знать, что такое двойное соотношение.

## Основная идея метода фотографий

Второй пример. Рассмотрим 6 точек в трехмерном пространстве $A,B,C,D,E,F$. Через 4 точки можно провести сферу, а через 5 - уже нельзя. Пусть $A,B,C,D,E$ на одной сфере, $A,B,C,D,F$ на одной сфере, тогда из этой шестерки любая пятерка лежит на одной сфере. При этом мы предполагаем, что если $A,B,C,D,E,F$ и уж через $A,B,C,D$ сферу можно провести единственную `FIXME: переписать предложение`. И раз она единственная, то она будет единственной и для $A,B,C,D,E$ и для $A,B,C,D,F$ и вообще для любой пятерки.

Но почему она единственная? Что если 4 точки окажутся на одной окружности? Тогда сфер может быть много, и это плохо.

Тем не менее возникает некоторый метод, который поволяет много чего **угадывать**.

> Тот факт, что 4 точки хорошие, т.е. лежат на одной окружности можно записать уравнением. А раз это можно записать уравнением, то можно сказать, что у нас есть два уравнения, и если эти два уравнения выполняются, то три остальных уравнения тоже выполянются.

Записав такую вещь, мы можем "забыть" про геометрическую интерпретацию и получить одно алгебраическое утверждение, второе алгебраическое утверждение и это позволит нам найти явное доказательство чего-то методом перебора`FIXME: данную фразу надо уточнить`.

Найдя такое доказательство, можно будет считать, что наши величины ничего общего с геометрией не имеют. Т.е. мы ***угадывем что-то из геометрии, потом мы получаем утверждение, переписываем его алгебраически, оно оказывается верным, а если оно верно, то мы можем получить алгебраическое доказательство***.

Это и есть одна из составных часте метода фотографий.

## Идея, которая почти верна

Пусть имеются пятерки и четверки. Пусть имеется утверждение того, что есть пятерка объектов, и пусть у нее есть четверки (например, это точки). Предположим, что есть интересное свойство, такое что, если оно верно для **пары четверок**, то оно верно для всех четверок. Если мы нашли такое свойство, тогда этого уже ***почти*** достаточно для того, чтобы получать инварианты трехмерных многообразий.

То же самое верно и для пятерок и шестерок. Пусть у нас есть шестерки чего-нибудь и у этих шестерок имеются пятерки. Пусть эти пятерки в каком-то смысле могут быть хорошими. Тогда ***можно придумать свойство***, что если две пятерки хорошие, то из этого следует, что остальные четыре хорошие. И этого будет почти достаточно для инвариантов четырехмерных многообразий.

На практике мы будем иметь дело с точками в эвклидовых пространствах и длинами между ними. Мы будем говорить, что между точками существуют дины и мы имеем какой-то закон преобразования и этот закон преобразования что-то делает с длинами. Но можно работать и с площадью, с углами, двугранными углами, но есть еще одно направление, а именно это могут быть какие-то множества не из геометрии.

## Пятиугольник

У треугольника без дополнительных вершин существует ровно одна триангуляция (сам треугольник). У четырехугольника существует две триангуляции, которые отличаются флипом. У пятиугольника существует пять триангуляций. У $n$-угольника существует чило Каталана триангуляций (что то же самое, что количество способов расстановки пар скобок).

> Если есть пара скобок, то ее можно расставить одним способом: $()$. Если есть две пары скобок, то их можно расставить двумя способами: $()()$, $(())$. Три пары скобки можно расставить $5$ способами.

За всеми числами Каталана стоят топологические объекты. Можно придумать многогранники, которые отображают возможные триангуляции $n$-угольника. Можно сказать, что у такого многогранника вершина отвечает триангуляции, а две вершины соединены ребром, если между ними флип. Далее можно сказать в каком случае вершины соединены гранью.

Оказывается, что для пятиугольника имеется 5 триангуляций и они получаются друг из друга и они получаются флипами. Это двумерный многогранник, пятиугольник.

*В математике один и тот же объект называется разными именами и открывается разными людьми в разные времена.*

Возьмем ассоциаэдр, многогранник Сташефа и решетку Тамари.

Ассоциаэдр можно понимать как произведение букв $A,B,C,D,...$ и это произведение не ассоциативное. Не-ассоциативность означает, что результат произведения зависит от того, как вы расставите скобки: $(AB)C \ne A(BC)$. Количество таких произведений связано с количеством расстановок скобок (поэтому и ассоциаэдр). 

## Уравнение пятиугольника

Представим, что у нас есть триангуляция пятиугольника и пусть у нас есть некоторые данные, соответствующие этой триангуляции. Кроме того, пусть у нас имеется **закон преобразования данных.**

> Такой закон может выглядеть как преобразование одного четырехугольника с диагональю в другой четырехугольник с другой диагональю (т.е. имеется в виду, что закон преобразования данных - это есть флип)
> ![[photography_method/images/lect_01_01.png]]

Но что есть данные в этом случае? **Данные - это некоторая комбинаторная информация, которая сопоставляется триангуляции.**

**Уравнение пентагона состоит в том, что если мы пять раз преобразуем данные согласно нашему правилу преобразования данных, то мы возвращаемся в исходную картинку.**

![[photography_method/images/lect_01_02.png]]

## Движения Пахнера

Есть движение Пахнера, движения Пергалини, движение пентагона (и т.д., можно найти еще другие объекты из других областей).

> Вообще говоря, мы будем всегда подразумевать, что у нас есть какой-то объект, у которого мы хотим определить какие-то состояния (например у триангулированного многообразия, состоянием будет триангуляция). И мы будем рассматривать движения, т.е. мы будем преобразовывать состояния, переходить из одного состояния к другому. Интерес вызывает то, как что-то меняется. И это изменение будет описываться каким-то уравнением.

Самое фундаментальное - это движение Пахнера.

Многообразия можно рассматривать как классы эквивалентности триангуляций.

> Триангуляция не является клеточным разбиением у которого все клетки являются симплексами. Кроме этого нужно добавлять дополнительное условие, например, условие того, что два симплекса должны пересекаться либо по пустому множеству, либо по симплексу меньшей размерности.


**Движения Пахнера** - это движения, которые преобразуют триангуляции одного и того же многообразия.

> Т.е. мы говорим, что у нас есть многообразие, потом мы берем одну его триангуляцию, берем другую триангуляцию и по аналогии с движениями Рейдемейстера говорим, что две триангуляции задают одно и то же многообразие, если ли и только если, они получаются друг из друга конечной последовательностью движений Пахнера.

Они позволяют в итоге нам сказать, что многообразия есть классы эквивалентности чего-то. Например, как узлы являются классами эквивалентности диаграмм `FIXME: проверить это предложение`.

### В размерности 2

В размерности 2 у нас есть движение 1-3 и 2-2. Движение 1-3 состоит в том, что мы берем двумерный тетраэдр (треугольник) и разбиваем его на 3 части. А движение 2-2 состоит в том, что мы берем 2 соседних треугольника, которые образуют четырехугольник и устраиваем флип.

![[photography_method/images/lect_01_03.png]]

### В размерности 3

В размерности 3 у нас есть движение 1-4 и движение 2-3. 

Движение 1-4 состоит в том, что у нас есть трехмерный тетраэдр и мы его разбиваем на 4 куска и эти 4 куска представляют 4 маленьких тетраэдра.

В движении 2-3 берем два тетраэдра, которые прилегают друг к другу (между ними имеется перемычка-диск). Мы убираем перемычку, добавляем ребро и на ребро натягиваем 3 тетраедра.

![[photography_method/images/lect_01_04.png]]

`FIXME: нужно найти более подходящие картинки`

В общем случае, в размерности $k$, движения Пахнера будут $p-q$, где $p+q=k+2$.

Есть понятие **join** - это когда есть два пространства и мы соединяем все точки первого пространства со всеми точками на второго.

> Например, если взять одно пространство - это нульмерная сфера, т.е. две точки, а другое пространство - одномерная сфера, т.е. окружность, то джоин нульмерной сферы и одномерной сферы даст двумерную сверу (северный и южный полюс соединяем с экватором).

Движение Пахнера в каком-то смысле можно проинтерпретировать, как джоин одномерной и нульмерной сферы. И вообще движения Пахнера все связаны с джойнами.

## Движения Пергалини

Это ни что иное как двойственное к движениям Пахнера типа 2-3, но есть некоторое уточнение.

Когда мы говорим Движение Пахнера, то мы говорим триангуляция. А можно сказать разбиение на треугольники, что не одно и то же.

В движениях Матвеева-Пергалини также используются комплексы, т.н. **спайны**. И в этих движениях используются клетки 0, 1 и 2. Трехмерные клетки там не используются и предполагается, что трехмерную клетку можно доделать (дорастить), подобно тому, как мы можем вложить в графы двумерную поверхность `FIXME: проверить правильность`.;
![[knots/photography_method/images/lect_01_05.png]]

У нас было два тетраедра, у которого 4 вершины. Можем нарисовать на них 2 тетраедра, которые соединены гранью. Двойственная к этой грани - ребро. И мы можем получить движением три тетраедра из чего будет видно, что двоейственное движение Пахнера 2-3 будет двойственным движением Матвеева-Пергалини.

## Волшебный Пентагон

Если мы посмотрим на движения Пахнера, то слева имеется диагональ у которой есть две вершины. Вершины - это настоящие вершины, в которых сходится по 4 ребра.

В некотором смысле можно взять картинку и начать сканировать под уголом (сечь плоскостями). Что мы будем видеть плоскости? Видеть мы будем трехвалентный граф, который в критические моменты может стать трехвалентным, и это есть флип. Оказывается, что на срезе первой картинки будет 2 флипа, а на второй - 3 флипа.!

![[photography_method/images/lect_01_06.png]]

> Т.е. в каком-то смысле движение Матвеева-Пергалини, которое можно понимать как нечто соответствующее композиции двух флипов, дает то же самое, что нечто, соответствующее композиции трех флипов. А если повернуть назад, то получится, что нечто, соответствующее пяти флипам, дает тождественное преобразование.

Если нарисуем двойственный граф, получим такую картинку:

![[photography_method/images/lect_01_07.png]]

**Уравнение пентагона состоит в том, что композиция двух флипов равна композиуии трех флипов.**

В каком-то смысле все три движения говорят об одном и том же.

## Инварианты кос

Уравнение пентагона было давным-давно известно для построения инвариантов терхмерных многообразий. Но мы можем его использовать для построения диаграм кос.

Нарисуем крашеную косу. Но так, чтобы начальный и конечный набор точек не лежали на одной прямой, но были, так сказать, в общем положении. Это будет не сильно ограничивать общность, т.к. когда мы говорим про крашенные косы, то каждая коса - это элемент фундаментальной группы конфигурационного пространства и если мы выберем другую отмеченную точку, то мы просто сопряжем эти элементы фундаментальной группы.

Поэтому будем рассматривать косу у которой точки расположены в общем положении. От этого общего положения нам будет нужна триангуляция Делоне и диаграммы Вороного.

Предположим, что у нас есть набор точек $z_j$ и мы хотим разбить нашу плоскость на области т.о., чтобы область $U_j$ была ближе к $z_j$, чем к какой-либо другой точке.

$$
U_i =\{ z_i : |z-z_j| \le |z-z_i|\}
$$

Если у нас таких точек всего две, то разбиением Вороного будет прямая, если точек три, то разбиение будет тремя перпендикулярами, а в общем случае это будет некоторый трехвалентный граф у которого допускаются бесконечные ребра.

![[photography_method/images/lect_01_08.png]]

Но может случиться "плохая" ситуация под которой подразумевается, что 4 точки лежат на одной окружности и внутри этой окружности нет других точек.

Двойственным к разбиению Вороного называется триангуляция Делоне, для этого нужно соединить ребрами точки:

![[photography_method/images/lect_01_09.png]]

Предположим, что мы двигаем эти точки. В какой-то момент 4 точки вдруг оказались на одной окружности и в этот момент с триангуляциями Делоне и даграмой Вороного происходит флип, т.е. они перестраиваются следующим образом:

![[photography_method/images/lect_01_11.png]]

**Цель.** Сопостаивить с триангуляциями какие-то данные.

**Набору точек в общем положении на плоскости сопоставим данные.**

**Флипу сопоставим перестройку данных.**

Если есть крашенная коса, то ей будет соотвествовать преобразование данных от триангуляций к ней самой. 

> Т.е. имея триангуляцию и данные мы преобразовали данные для этой триангуляции.

**Косе мы будем сопоставлять преобразование данных на триангуляции.**

**Цель.** Хотим, чтобы это было инвариантно. Т.е. хотим, чтобы **изотопным косам соответствовали одинаковые преобразования данных.**

Поскольку косы образуют группу, то то, что мы хотим, можно проверить на тривиальных косах. Т.е. можем сказать, что мы хотим, чтобы любому представителю **тривиальной косы** соответствовало **тривиальное преобразование данных**.

А для этого нужно, чтобы **закон преобразования данных удовлетворял уравнению пентагона**!

Рассмотрим косу у которой много нитей, но пять точек почти что на одной окружности. Будем двигать эти пять точек, чтобы ни одна не обходила другой (т.е. почти в вершинах правильного пятиугольника). Тогда для этой косы триангуляция Делоне и диаграмма Вороного может меняться и может случиться, что она подвергнется пяти флипам, после чего вернется в начальное положение.

## Птолемей

Преобразование Птолемея состоит в том, что если у нас есть четырехугольник и у него есть четыре стороны $a,b,c,d$ и то $y=\frac{ac+bd}{y}$ `FIXME: проверить это`.

![[photography_method/images/lect_01_12.png]]

Из птолемея следует пентагон.

Идея этого состоит в том, что если имеется пятиугольник с длинами сторон $a,b,c,d,e$ и двуми диагоналями $x$ и $y$, то мы можем сделать флип и вместо $y$ поставить диагональ $z = \frac{bd+cx}{y}$.

Утверждение состоит в том, что после пяти преобразований мы вернемся в исходное положение.

Можно проверить брутфорсом, но на самом деле можно предугадать используя геометрию. И в каком-то смысле метод фотографий - это метод, который позволят **угадывать**, исходя из каких-то соображений, решения тех или иных уравнений.

## Тропическая геометрия

Тропическое полуполе - это полуполе в котором есть три операции:
1. тропическое умножение - это обычное сложение: $a \otimes b=a+b$
2. тропическое деление - это обычное вычитание: $a\oslash b = a-b$
3. тропическое сложение: $a\oplus b = max(a,b)$

Эти операции обладают очень многими аксиомами сложения/умножения, в частности дистрибутивностью. Но у сложения нет обратного, нет такого понятия как тропическое вычитание.

Оказывается, что если взять пятиугольник и к этому пятиугольнику
применять все эти операции по типу $\frac{ac+bd}{x}$, то у нас будут получаться отношения многочленов. Интерес в том, что мы получим многочлены Лорана и в знаменателе всегда будет моном (не может быть $x+y$, будет только $xy$). А в числителе все коэффициенты будут положительны. И т.о. это вычисление, которое можно проделать брутфорсом (применяя 5 раз операцию такую-то, такую-то и такую-то) - это утверждение о полиномах Лорана, в которых не учавствуют операции вычитания, а учавствуют только операции сложения, деления и умножения.

Это значит, что можно получить решение уравнения пентагона с помощью тропической операции Птолемея.

Т.е. вместо $y=\frac{ac+bd}{y}$ пишем $y=(a\otimes c\otimes b\otimes d)\oslash x = max(a+c-x, b+d-x)$.

И эта операция нам тоже даст инвариант кос. Т.е. оказывается, что у некоторых наук есть тропические аналоги и они дают инварианты.


> Мы можем что-то угадывать с помощью геометрии. Угадав с помощью геометрии, мы можем сказать, что что-то верно. Если какое-то утверждение про многочлены верно, то мы можем доказывать его с помощью алгебры.

## Задачи

1. Как от кос перейти к узлам? Каждой косе сопоставляем преобразование меток. После преобразования получаются многочлены Лорана или что-то в этом роде. А хочется, чтобы получился инвариант узлов или зацеплений. Нужно поработать с движением Маркова. Как правило, все, что в этом направлении не получается связано с делением на ноль.
2. Движение точек по двумерной поверхности - это динамическая система. А то, что вырисовывается - это спайн многообразия. Связь между инвариантами трехмерных многообразий с инвариантами кос есть связь спайнов с динамическими системами. Но далеко не каждый спайн отвечает динамической системе. Можно ли все спайны представить как динамические системы?

