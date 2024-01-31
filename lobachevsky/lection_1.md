Здравствуйте! 

Настоящая лекция представляет собой лекцию номер один курса геометрии Лобачевского для начинающих.

Ее цель – обсудить пятый постулат Евклида и сумму углов треугольника.
Давайте обсудим теорему о том, что сумма углов треугольника в евклидовой геометрии равна 180 градусам или, если говорить в радианах, она равна  $\pi$ .
$$
Т:    \sum углов \bigtriangleup = \pi
$$

Обычно, когда школьников или даже студентов младших курсов спрашивают, как эту теорему доказать, многие считают ее либо аксиомой, либо доказывают следующим образом.
Рассмотрим треугольник ABC и обозначим его углы через α, β и γ.

![[lobachevsky/images/lection_01_01.png]]


Тогда можно рассмотреть накрест лежащие углы и увидеть, что они равны β и γ.
И в этом случае мы имеем сумму трех углов, которые дают вместе развернутый угол, и, соответственно, сумма α, β и γ равна  $\pi$ .
$$
\alpha + \beta + \gamma = \pi
$$
Отсюда возникает вопрос, а вот накрест лежащие углы, они равны по какой причине?
Многие говорят, это аксиома. На самом деле это не аксиома, это теорема.
И вот сейчас я хотел бы заострить ваше внимание на том, что есть аксиомы и есть теоремы.

И что на самом деле эта игра, которую придумал Эвклид и в которую люди играли 2000 лет, в конце концов привела к тому, что люди смогли найти не-Эвклидову геометрию.
Итак, давайте я, прежде чем перейти к обсуждению аксиомы Эвклида и, в частности, пятого постулата, замечу, что имеют место три утверждения.
Вот это утверждение, сумма углов равна  $\pi$ , мы уже назвали.

**Второе утверждение,** давайте его отметим, состоит в том, что накрест лежащие углы равны.


![[lobachevsky/images/lection_01_02.png]]
И **третье утверждение** состоит в том, что если имеется треугольник, то у него внешний угол, к примеру z, равен сумме двух внутренних углов, несмежных с ним.
z в данном случае равен α плюс β.
![[lobachevsky/images/lection_01_03.png]]
 
$$
\zeta=\alpha + \beta 
$$
 
Утверждение 1 и утверждение 3 очевидным образом эквивалентны, потому что просто здесь мы можем взять z и увидеть, что z плюс γ равно в сумме  $\pi$ .
Вот отсюда, из второго утверждения мы первое доказали. Также  из первого следует второе.
Но я отмечу, что ни одно из этих утверждений, 1, 2 и 3, само по себе аксиомой не является.

Итак, перейдем теперь к обсуждению аксиом.

На самом деле, Евклид сформулировал в своих началах пять аксиом. Пятую из них я сейчас сформулирую точно:
> Какова бы ни была прямая, и если имеется точка вне этой прямой, то найдется ровно одна прямая M, параллельная данной и проходящая через точку А.**

![[lobachevsky/images/lection_01_04.png]]
$$
\forall l \quad \forall A \notin l \quad \exists! m : (m \in A)
\& (m \parallel l)
$$
$\forall$- обозначает квантор всеобщности ("для всех"), $\exists$ - обозначает квантор существования ("существует"), $\in$ - обозначает отношение "принадлежит"

Значит, для каждого  l и для каждой точки А, не принадлежащей прямой l, существует и   единственная прямая m, такая, что m содержит точку А и m параллельно l.

Итак, мы имеем пятый постулат Евклид. Теперь по поводу первых четырех аксиом. Евклид записал четыре аксиомы, но потом, когда люди стали на них смотреть, то они поняли, что с логической точки зрения эти аксиомы небезупречны. Например, одна из аксиом была связана с тем, что имеются меры длин, меры углов. И  если мы говорим про меры, то мы предполагаем, что  имеем понятие вещественных чисел. А вещественные числа сами по себе являются объектом, требующим аксиом, и на определение корректное того, что такое вещественные числа, может уйти целый курс. На самом деле это не единственное место, и существует очень много разных аксиоматик : Аксиоматика Гильберта, аксиоматика Пеано.

Очень много есть аксиоматик в советской школе. В частности, много поколений советской школы пользовалось аксиомами из учебников в аксиоматике Погорелова. На самом деле существует очень много аксиоматик.

Вот несколько, как сейчас принято говорить, ключевых слов, отвечающих этим аксиомам.
Однако же я умышленно не хочу выписывать весь этот список. Иногда люди, чтобы сохранить цифру 4, говорят о 4 группах аксиом. Иногда этих групп оказывается не 4. В общем, тут ситуация довольно сложная.

Мы имеем прямую, проходящую через любые две точки.

![[lobachevsky/images/lection_01_05.png]]

То есть каковы бы ни были две точки, мы можем провести через них прямую, и это аксиомы такого существования.

Есть также аксиомы, связанные с понятием порядка.
Порядок означает, что если у нас есть три точки, то ровно одна из них лежит между и  если у нас есть три прямые, три луча, выходящие из точки, то можно сказать, что ровно один из них лежит  между.
![[lobachevsky/images/lection_01_06.png]] ![[lobachevsky/images/lection_01_07.png]]
Есть понятие меры. Мера отрезка и мера угла. Что у отрезков есть меры, и при этом эти меры аддитивные: то есть  мера длинного отрезка равна сумме мер его частей.

![[lobachevsky/images/lection_01_08.png]]
**АС=АВ+ВС**

И то же самое для угла: если один луч лежит между двумя лучами, то, соответственно,  гамма будет равен сумме альфа и бета.


![[lobachevsky/images/lection_01_09.png]]
И есть еще аксиомы, связанные с откладыванием:  если у нас есть прямая луч, то на этом луче можно отложить один отрезок любой наперед заданной длины.  И кроме того, если у нас есть прямая и выбрано одно из направлений полуплоскости, то можно в этой полуплоскости от какой-то точки и прямой отложить какой угодно угол.

На самом деле вот это слово **«откладывание»** связано с двумя крайне важными терминами, а именно с понятием «движение». То есть когда мы говорим, что мы совмещаем какие-то два объекта, например, два треугольника, то это означает, что имеется движение на плоскости, которое переводит один в другой. 

**Движение, транзитивность**  - любую точку можно перевести в любую.

**Однородность** означает, что пространство во всех точках одинаковое.

А теперь я хочу привести некоторый пример утверждений, которые мгновенно следуют из аксиом. Например, мы говорили про накрест лежащие углы, они равны. То, что они равны, это не мгновенное утверждение.

Вот, например, то, что вертикальные углы равны, это аксиома или теорема?  На самом деле это почти мгновенное следствие из аксиомы, а именно, что если у нас есть углы альфа и гамма, и они вертикальные, то альфа плюс бета равно гамма плюс бета, потому что и то, и другое равно развернутому углу. 
![[lobachevsky/images/lection_01_10.png]]
$$
\alpha + \beta = \gamma + \beta
$$
Значит, конечно, тут надо говорить и про аксиомы "лежать между", и про то, что имеется  некоторая мера у развернутого угла, но это практически мгновенно следует из аксиомы.

А теперь я хочу поговорить об очень важной лемме, а именно лемма, которая вытекает из абсолютной геометрии.

> **Лемма в абсолютной геометрии**: внешний угол треугольника строго больше внутреннего угла, несмежного с ним.

**Что значит, что эта лемма верна в абсолютной геометрии?**

Абсолютной называется геометрия, где первые четыре аксиомы верны, но по поводу пятой аксиомы, наличия параллельной, ровно одной, неизвестно. То есть в последнем случае через каждую точку, не лежащую на прямой, проходит, может быть, одна, а может быть и несколько параллельных прямых. Вот такая геометрия, где мы четыре группы аксиом принимаем, а пятую принимаем в ослабленном виде, называется абсолютной.

Докажем утверждение про внешний и внутренний угол. Будем его выводить из первых четырех аксиом, не будем пользоваться тем, что параллельная единственная. Делается это следующим образом:   Наша цель — доказать, что ζ больше, чем β. Мы делим треугольник ABC... сторону треугольника BC пополам. Получается некоторая точка D.

Откладываем  отрезок AD и продолжаем его, получая отрезок DА', соединяем точку А' с точками B и C, и получаем два равных треугольника. Равных, как учат в школе, или же, на самом деле, я еще упомяну такое понятие, конгруентных. 
![[lobachevsky/images/lection_01_11.png]]
Конгруентность означает то, что мы можем один объект с другим совместить после некоторого движения. Эти два треугольника тождественными друг другу не являются, они разные и лежат в разных местах.
![[lobachevsky/images/lection_01_12.png]]
Но один можно перевести в другой с помощью движения. Таким образом они являются конгруентными.  Итак,  эти два треугольника конгруентны **благодаря признаку равенства треугольников по двум сторонам и углу между ними**. 

Вы спросите, а этот признак, это аксиома или теорема? На самом деле, это мгновенное следствие аксиомы об откладывании. То есть, если у нас есть треугольник, если у нас есть некоторая другая прямая, мы можем отложить такую же по длине сторону, такую же по длине другую сторону и такой же по мере угол, и мы получим два одинаковых, то есть конгруентных треугольника.

Итак, вот эти два треугольника конгруентны, но я замечу, что я нигде здесь не произносил слова параллелограмм. Вообще говоря, в абсолютной геометрии никаких параллелограммов нет, а также накрест лежащих углов.

Давайте рассмотрим  угол гамма и  бета. Значит, угол DBA мы обозначили через бета, и, соответственно, равный ему угол, то есть соответствующий угол в конгруентном треугольнике DCА' тоже будет равен бета. А теперь, если мы продолжим вот эту прямую А'C, то мы здесь сможем получить вертикальный угол, который тоже будет равен бета, но который представляет собой часть угла Z,значит, Z строго больше, чем бета.

![[lobachevsky/images/lection_01_14.png]]
Таким образом, мы с вами доказали теорему о накрест лежащих углах. Если мы принимаем пятый постулат, то мы получаем, что сумма углов треугольника равна 180 градусов.

А вы можете спросить, а если мы не принимаем пятый постулат, то как тогда будет? Оказывается, что можно доказать, что сумма углов треугольника в этом случае не больше 180 градусов.

Но сейчас мне хочется обсудить вот что. Давайте мы с вами посмотрим на сумму углов треугольника и попробуем понять, какой эта сумма может быть. 

**Сумма углов треугольника и дефект.**
Давайте рассмотрим произвольный треугольник и введем такую величину: Пи минус сумма углов, измеренная в радианах. Значит, дефект треугольника ABC, это будет Пи минус сумма углов.
$$
d(ABC)=\pi -\sum углов 
$$
Конечно, если мы работаем в Евклидовой геометрии ,то тогда мы увидим, что это число всегда равно нулю. Но давайте мы посмотрим, какими свойствами может обладать это число, если мы вдруг не знаем, что оно равно нулю.

Например, давайте рассмотрим вот такой треугольник $ABC$. Проведем  медиану $D$ к стороне ВС, удвоим ее, поставим здесь точку А' и рассмотрим вместо треугольника $ABC$ треугольник $АА'С$. Эти два треугольника называются **равносоставленными**.

**Что значит равносоставленными?**

Это означает, что можно один из треугольников разрезать на конечное число частей, и из этих конечных частей составить другой. В данном случае возникает просто разделение на две части, и   этот красный треугольник $ABD$ мы переносим сюда $А'CD$.

Так вот, я хочу сказать, что раз они равносоставленные, если у нас есть такое понятие, как площадь треугольника, тогда мы видим, что площади этих треугольников равны. 
$$
S(ABC)=S(AA'C)
$$
Площадь первого равна площади второго. Но у них и сумма углов равна, правильно?

Значит, пока что еще мы ничего не знаем про то, какие значения принимает дефект, но можно задать такой вопрос. Давайте предположим теперь, что один треугольник состоит из двух треугольников, и разбивается на них, на эти два треугольника, как говорят, апофемой.

**Апофема** — это от греческого глагола «откладывать в сторону».

То есть это может быть медиана, а может быть высота. Итак, есть апофема ABC, а это точка некоторая D. Рассмотрим сумму углов треугольника ABD плюс сумму углов треугольника BCD.

Ну, понятно, что при вершине B эти углы сложатся, а при вершинах A и C углы останутся,
но при вершине D два угла сложатся вместе в развернутый угол. То есть это будет  $\pi$  плюс сумма углов треугольника ABC.
$$
\sum(углов ABD) +\sum(углов BCD) =\pi + \sum(углов ABC) 
$$
Таким образом, если мы возьмем выражение  $\pi$  минус сумму углов треугольника, то тогда получится довольно интересная вещь. То есть если мы взяли  $\pi$  минус сумму углов, то тогда мы можем взять треугольник ABC и увидеть, что дефект треугольника ABC равен сумме дефектов ABD и ACD. То есть дефект, он, как говорят, аддитивен.

$$
\pi - \sum(\text{углов  треугольника}); d(ABC)=d(ABD)+d(ACD) 
$$
**Аддитивен** – это означает, что дефект целого равен сумме дефектов частей.

Теперь я хочу сказать буквально пару слов по поводу такого философского вопроса. А какой же мир на самом деле? То есть верны ли в нашей природе аксиомы Евклида и верен ли Пятый постулат?

Вроде бы кажется, что понятно, что Пятый постулат выполняется, и в связи с этим верны все утверждения про сумму углов треугольника и так далее. Но на самом деле давайте мы на секундочку встанем на точку зрения древних и вспомним, что древние думали, что Земля плоская.

То есть если мы говорим про двумерную поверхность, то вроде как естественно ее считать плоской, тем более если мы измеряем очень маленькие локальные расстояния, то они выглядят как плоскость. Ну давайте посмотрим на нашу Землю с реалистичной точки зрения, ее форма поверхности – это геоид, но это почти сфера. Чуть-чуть, правда, приплюснутая в плюсах.  Мы знаем, что на плоскости сумма углов треугольника равна $180$ градусов, если для этой плоскости выполняются аксиомы и Евклида. Но давайте мы сейчас посмотрим на вот эту сферу и рассмотрим на сфере вот такой треугольник. Давайте возьмем одну точку в северном полюсе и возьмем еще две точки на экваторе А и В, такие, чтобы угол между соответствующими меридианами был прямым. Давайте посмотрим на этот треугольник и на его углы.

Все углы этого треугольника прямые, то есть сумма углов в данном случае равна $3\pi$  пополам.

Получается, что она вообще больше, чем  $\pi$ . А я вроде как обещаю доказать вам в следующий раз, что эта сумма будет меньше или равна $\pi$. В чем же дело?

А дело в том, что на сфере не выполняется не только пятый постулат, но там не выполняются и очень многие другие положения из абсолютной геометрии. Например, там вообще нет такого понятия, чтобы две прямые были параллельны.  Там прямыми являются дуги больших кругов, а они всегда пересекаются.  То есть на самом деле мы здесь видим, что понятие аксиом очень и очень важное. 

С другой стороны, давайте посмотрим на секундочку, какая площадь у этого треугольника.
Легко заметить, что площадь этого треугольника АBN равно 1/8 площади сферы.
$$
 S(ABN)=\frac{1}{8} S(сферы)=\frac{1}{8}(4\pi)=\frac{\pi}{2}
$$
Если сфера у нас имеет радиус единицы, то это будет одна восьмая от четырех  $\pi$ , то есть  $\pi$ пополам.

А  $\pi$  пополам – это как раз разность между суммой углов и дефектом. То есть получается такая интересная вещь. Сумма углов в случае сферического треугольника, она больше, чем  $\pi$ .

И как мы в дальнейшем увидим, дефект – это всегда площадь, умноженная на число. Только это число может быть всегда равно нулю, как в случае Евклида. И в некоторых случаях это число может быть положительное, тогда мы берем его с одним знаком.

В некоторых случаях оно может быть отрицательным, тогда мы берем его с другим знаком. Таким образом мы видим, что если мы изменим нашу точку зрения на мир, то мы получим довольно интересные правила игры. А что касается доказательства, теорем, про сумму углов, про то, что дефект равен площади, то тут я доказывать буду не всё, но для мотивировки упомяну одну очень важную задачу. 

Задача состоит в следующем: давайте попробуем подумать, почему, если есть два треугольника, пусть у нас обычная евклидовая геометрия, где выполняются все пять постулатов,  имеют одинаковую площадь, то можно один из них разрезать на части на конечное число частей, переклеить и получить другой.

Вот если мы это докажем, то тогда, в общем-то, будет понятно, что площадь как-то с дефектом связана, потому что разрезать на части можно, и при разрезании на части дефект складывается, то есть ведет себя так же, как площадь.

А задача про равносоставленность — это очень интересная задача в трехмерном случае,
а в двумерном случае её решение положительное, то есть многоугольники, имеющие одинаковую площадь, являются равносоставными, а в трехмерном, как оказывается, нет.
Так что это еще одна задача, которая мотивирована тем, что мы имеем в случае абсолютной геометрии.

Итак, на следующей лекции я планирую рассказать про площади, дефекты и все, что отсюда следует.