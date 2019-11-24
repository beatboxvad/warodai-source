# Большой электронный японско-русский словарь WARODAI

## 1. ОБ ИСТОРИИ ПРОЕКТА
Проект по созданию настоящего словаря был начат группой энтузиастов в 2006 году с оцифровки словника Большого японско-русского словаря (БЯРС) под редакцией академика Н. И. Конрада, изданного в 1970 году издательством "Советская энциклопедия". Уже на этапе оцифровки БЯРС корпус словаря подвергся изменениям. В заголовках статей было добавлено написание каной, раскрыты все круглые и квадратные скобки, были выявлены опечатки, ошибки и неточности, добавлены альтернативные написания заголовочных слов. Выверка значений японских лексем, а также генерация написания каной производилась по современным словарям, вышедшим в Японии. Этап оцифровки словника БЯРС был завершен в 2008 году выпуском первой версией WARODAI под свободной лицензией Creative Commons «Attribution-NonCommercial-NoDerivs» («Атрибуция — Некоммерческое использование — Без производных произведений») 3.0 Непортированная.

В период с 2008 по 2019 год работа над словарем продолжалась по следующим направлениям:
- поиск и исправление опечаток и ошибок;
- накопление материалов для уточнения, расширения и исправления словника;
- сбор материала для дополнения словаря новыми словами, вариантами написания и перевода;
- повторная, более тщательная выверка заголовков словника по многочисленным японским изданиям словарей и справочников.

В 2019 году проект был переведен на платформу Github, где продолжается работа по внесению в корпус словаря многочисленных изменений, уточнений и дополнений, как накопленных за период 2008-2019 гг., так и выявляемых вновь.

В настоящий момент словарь содержит более 96 000 статей. Общее число японских лексем - около 121 000, русских переводов - около 151 000.

## 2. ЯЗЫК СЛОВАРЯ
Текст готовится

## 3. СТРУКТУРА И ОФОРМЛЕНИЕ СТАТЕЙ

### 3.1 СТРУКТУРА СЛОВАРНОЙ СТАТЬИ
Словарная статья следующюю структуру:

<pre>
Заголовок
  Общее уточнение
  Рубрика 1
    Перевод для рубрики 1
    Производные для рубрики 1
    Свободные словосочетания для рубрики 1
    Фразеологические словосочетания для рубрики 1
    Идиоматические выражения для рубрики 1
  Рубрика 2
    Перевод для рубрики 2
    Производные для рубрики 2
  ...
  Общие отсылки
</pre>

Разным рубрикам соответствуют разные значения (переводы) заглавного слова. Обязательными для статьи являются только заголовок и русский перевод для рубрики 1. В случае, если статья содержит только одну рубрику, то эта рубрика не нумеруется. Также в этом случае не может иметься общего уточнения и общих отсылок, поскольку они используются только в случае наличия в статье более одной рубрики.

<pre>
げきやく【激薬】(гэкияку)〔000-17-52〕  
<i>мед.</i> сильнодействующее средство.
</pre>

<pre>
なみあし【並足】(намиаси)〔006-80-80〕
нормальный шаг;
～で обычным шагом.
</pre>

В случае, если в статье имеется более одной рубрики, то их нумерация производится арабскими цифрами с точкой или со скобкой.

Нумерация арабскими цифрами с точкой производится в случае, если в разных рубриках имеются значения, передаваемые разными частями речи. Это явление встречается достаточно редко.

<pre>
にちや【日夜】(нития)〔001-15-91〕
<i>кн.</i>
1. день и ночь;
2. днём и ночью, круглые сутки; <i>перен.</i> постоянно, непрерывно.
</pre>

<pre>
にんちゅう【人中】(нинтю:)〔000-34-93〕
1. среди людей;
2. впадинка над верхней губой.
</pre>

В остальных случаях нумерация рубрик производится арабской цифрой со скобкой.

<pre>
ぬう【縫う･繍う･繡う】(нуу)〔007-91-86〕
1) шить; прошивать; зашивать; вышивать;
彼女は一針二針縫っては窓からながめた сделав стежок, другой, она посматривала в окно;
2) <i>перен.</i> прорезывать;
空を縫う прорезать небо <i>(напр. о ракете)</i>;
人中を縫って歩く пробиваться через толпу;
路が田畑を縫う дорога ведёт через поля (вьётся между полями).
</pre>

Ниже представлены примеры статей с различной структурой

**Статья げきひょうか【劇評家】(гэкйхё:ка)〔009-10-26〕**
<table>
    <tr>
        <td>
            げきひょうか【劇評家】(гэкйхё:ка)〔009-10-26〕
        </td>
        <td>
            Заголовок
        </td>
    </tr>
    <tr>
        <td>
            театральный критик.
        </td>
        <td>
            Рубрика 1. Перевод
        </td>
    </tr>
</table>

**Статья げごく【下獄】(гэгоку)〔005-79-67〕**
<table>
    <tr>
        <td>
            げごく【下獄】(гэгоку)〔005-79-67〕 
        </td>
        <td>
            Заголовок
        </td>
    </tr>
    <tr>
        <td>
            : ～する попасть в тюрьму.
        </td>
        <td>
            Рубрика 1. Перевод
        </td>
    </tr>
</table>

**Статья てんじる【転じる】(тэндзиру)〔005-93-59〕**
<table>
    <tr>
        <td>
            てんじる【転じる】(тэндзиру)〔005-93-59〕 
        </td>
        <td colspan="2">
            Заголовок
        </td>
    </tr>
    <tr>
        <td>
            <i>кн.</i>
        </td>
        <td colspan="2">
            Общее уточнение.
        </td>
    </tr>
    <tr>
        <td>
            1) вертеться, вращаться; поворачиваться;
        </td>
        <td>
            Рубрика 1
        </td>
        <td>
            Перевод
        </td>
    </tr>
    <tr>
        <td>
            2) поворачивать, менять <i>(направление, курс)</i>;
        </td>
        <td rowspan="2">
            Рубрика 2
        </td>
        <td>
            Перевод
        </td>
    </tr>
    <tr>
        <td>
            歩を転じる направиться (повернуть) в другую сторону;<br/>
            道を転じる свернуть с дороги; изменить свой путь;
        </td>
        <td>
            Свободные словосочетания
        </td>
    </tr>
    <tr>
        <td>
            3) менять, изменять; обращаться, переходить <i>к чему-л.</i>;
        </td>
        <td rowspan="3">
            Рубрика 3
        </td>
        <td>
            Перевод
        </td>
    </tr>
    <tr>
        <td>
            気を転じる отвлекаться <i>от чего-л.</i>;<br/>
            心を勉強から他に転じる переключаться от занятий на <i>что-л.</i> другое;<br/>
            話頭が転じて労働問題に及んだ разговор перешёл на рабочий вопрос;<br/>
            敗を転じて勝となす превратить поражение в победу;<br/>
        </td>        
        <td>
            Свободные словосочетания
        </td>
    </tr>
    <tr>
        <td>
            禍が転じて福となった <i>погов.</i> не бывать бы счастью, да несчастье помогло (<i>букв.</i> беда превратилась в счастье);
        </td>        
        <td>
            Фразеологические словосочетания
        </td>
    </tr>
    <tr>
        <td>
            4) переезжать, перебираться; быть переведённым <i>(в другое место)</i>;
        </td>
        <td rowspan="2">
            Рубрика 4
        </td>
        <td>
            Перевод
        </td>
    </tr>
    <tr>
        <td>
            居を市ケ谷に転じる переехать в И́тигая.
        </td>
        <td>
            Свободные словосочетания
        </td>
    </tr>
</table>

**Статья わたくし【私】(ватакўси)〔008-28-35〕**
<table>
    <tr>
        <td>
            わたくし【私】(ватакўси)〔008-28-35〕 
        </td>
        <td colspan="2">
            Заголовок
        </td>
    </tr>
    <tr>
        <td>
            я;
        </td>
        <td>
            Рубрика 1
        </td>
        <td>
            Перевод
        </td>
    </tr>
    <tr>
        <td>
            ～の а) мой; б) частный; личный;
        </td>
        <td>
            Рубрика 1
        </td>
        <td>
            Производные
        </td>
    </tr>
    <tr>
        <td>
            ◇～[の]ある эгоистичный, себялюбивый; своекорыстный;<br/>
            ◇～する присваивать.
        </td>
        <td>
            Рубрика 1
        </td>
        <td>
            Идиоматические выражения
        </td>
    </tr>
</table>

#### 3.1.1 Заголовок статьи
Заголовок статьи имеет следующую структуру

<pre>написание каной 【иероглифическое написание】(транскрипция по системе Поливанова) [код корпуса]〔идентификатор карточки〕</pre>

Пример заголовка статьи

<pre>アゾレスしょとう【アゾレス諸島】(Адзорэсу-сёто:) [геогр.]〔002-16-83〕</pre>

##### 3.1.1.1 Написание каной
Данная часть заголовка является обязательной. Написание каной может быть дано хараганой 

<pre>こうあん【考案】(ко:ан)〔009-09-21〕</pre>

или (например, в случаях заимствованных слов) катаканой

<pre>スーツ(су:цу)〔009-44-99〕</pre>

в некоторых случаях - смешанно 

<pre>ボヘミアじん【ボヘミア人】(бохэмиадзин)〔009-33-63〕</pre>

Многоточие … (U+2026, Horizontal Ellipsis) в написании каной является показателем несамостоятельности слова. Если многоточие предшествует написанию, то
это постпозиционный компонент,

<pre>…わたし【…渡し】(…ватаси)〔007-02-09〕</pre>

если многоточие стоит после написания, то это препозиционный компонент

<pre>アンチ…, アンティ…(анти…)〔004-16-69〕</pre>

Следует обратить внимание, что указание на несамостоятельность слова с помощью троеточия следует не только в написании каной, но также в иероглифическом написании и транскрипции по системе Поливанова.

##### 3.1.1.2 Иероглифическое написание
Данная часть заголовка необязательна и может отсутствовать, если у заголовочного слова нет ни одного зафиксированного словарями варианта написания, не включающего какие-либо знаки, кроме хираганы или катаканы.

<pre>わた【綿･棉･草綿】(вата)〔009-48-96〕</pre>

<pre>ちかづきやすい【近付き易い】(тйкадзукиясуй)〔006-45-17〕</pre>

<pre>しっきりなしに(сиккиринасини)〔005-57-40〕</pre>

Если у слова имеется несколько вариантов иероглифического написания, то эти варианты разделяются символом ･ (U+FF65, Halfwidth Katakana Middle Dot).

<pre>しょしょ【処々･所々･諸所】(сёсё)〔2-061-2-37〕</pre>

<pre>しびれえい【痺れ鱏･痺れ鱝】(сибирээи)〔2-069-2-16〕</pre>

Если у слова, имеющего написание хираганой, помимо иероглифического написания имеется также часто употребляющееся написание катаканой, то написание катаканой вносится в качестве варианта иероглифического написания.

<pre>さんぱん【舢舨･舢板･三板･サンパン】(сампан)〔001-21-82〕</pre>

Если у слова есть вариант написания, включающий латинские буквы или состоящий только из них, то такой вариант написания фиксируется в качестве иероглифического. Особенно это характерно для аббревиатур.

<pre>エッキスせん, エッキスこうせん【X線, X光線】(эккйсўсэн, эккйсўко:сэн)〔002-99-75〕</pre>

<pre>アイシビエム【ICBM･I.C.B.M.】(айсибиэму)〔001-34-95〕</pre>

Римскими цифрами в иероглифическом написании обозначаются варианты, являющиеся полными омографами для слов,
входящих в заголовки других статей. 

<pre>
あおだいしょう【青大将II】(аодайсё:)〔006-19-66〕  
<i>прост.</i> неопытный полководец.
</pre>

<pre>
あおだいしょう【青大将I･黄頷蛇】(аодайсё:)〔009-07-76〕  
островной полоз, Elaphe clemacophora <i>Boie (змея)</i>.
</pre>

##### 3.1.1.3 Транскрипция по системе Поливанова
Данная часть заголовка является обязательной и передает транскрипцию слова в системе Е. Д. Поливанова. 

Долгота гласных обозначается двоеточием после буквы, например, もう мо:, ゆう ю:, かあ ка:.

Буквы *ん* и *ン*, обычно транскрибируемые *н*, перед *м*, *б*, *п* произносятся и передаются через *м*.

<pre>きんむ【勤務】(кимму)〔008-32-51〕</pre>

<pre>アンパイア(ампайа)〔004-93-18〕</pre>

Однако если к самостоятельному слову, кончающемуся на *ん* или *ン*, присоединяется суффиксальный компонент, начинающийся с букв *ま–も (マ–モ), ば–ぼ(バ–ボ), ぱ–ぽ (パ–ポ)*, в таком производном слове в транскрипции сохраняется буква *н*. 

<pre>
おんせんば【温泉場】(онсэнба)〔007-31-65〕  

温泉 + 場
</pre>

Аналогично в транскрипции сохраняется буква *н* и в тех случаях, когда к префиксальному компоненту, кончающемуся на *ん* и *ン*, присоединяется самостоятельное слово, начинающееся на буквы *ま–も (マ–モ), ば–ぼ(バ–ボ), ぱ–ぽ (パ–ポ)*.

<pre>
じゅんぶんがく【純文学】(дзюнбунгаку)〔005-90-05〕  

純 + 文学
</pre>

Из этого следует, что способ транскрипции *ん* и *ン* перед *ま–も (マ–モ), ば–ぼ(バ–ボ), ぱ–ぽ (パ–ポ)* косвенно указывает на состав сложных слов с суффиксальными и префиксальными компонентами. Так например

<pre>
だいじんぶつ【大人物】(дайдзимбуцу)〔000-48-60〕
</pre>

свидетельствует о том, что это слово имеет словообразовательную структуру *大+人物*, а не *大人+物*.

В ограниченных пределах, знаками *ў* (U+045E, Cyrillic Small Letter Short U) и *й*, обозначается редукция:

а) *у* и *и*, наблюдающаяся в позициях между двумя из следующих согласных: *к, с, т, ц, ф, п, х*:

<pre>
すこし【少し】(сўкоси)〔009-15-41〕
</pre>

>ひと【人】(хйто)〔000-43-39〕
</pre>

<pre>
こくさい【国祭】(кокўсай)〔000-83-95〕
</pre>

б) в словах, где *у* перед *м* фактически обозначает долготу этого м: 

<pre>
うま【馬】(ўма)〔004-06-90〕
</pre>

<pre>
うまい【旨い】(ўмай)〔007-12-17〕
</pre>

<pre>
うまる【埋まる】(ўмару)〔005-24-65〕
</pre>

в) *у* в заимствованных словах, при транскрипции тех слов, в которых буквой *ウ* транскрибировано английское *w*. 

<pre>
ウェーブ, ウェーヴ(ўэ:бу, ўуэ:ву)〔003-08-75〕
</pre>

г) *у* в словах, образованных от отрицательной формы глаголов на *-ну*, где происходит редукция, часто передающаяся на письме буквой *ん*　на месте *ぬ*. В этом случае *ў* заключается в транскрипции в квадратные скобки.

<pre>
いいしれぬ【言い知れぬ】(иисирэн[ў])〔001-86-73〕
</pre>

<pre>
いらぬ【要らぬ】(иран[ў])〔004-16-26〕
</pre>

Простые и производные, как чисто японские слова, так и китайские заимствования (канго), пишутся слитно.
В многосложных словах те их компоненты, которые являются полнозначными самостоятельными словами, отделяются в транскрипции дефисом.

<pre>
ろうどうくみあい【労働組合】(ро:до:-кумиаи)〔000-14-62〕  
профессиональный союз, профсоюз.

самостоятельное слово 労働 ро:до: "труд" + самостоятельное слово 組合 кумиаи "союз; ассоциация; артель"
</pre>

При этом те компоненты, которые самостоятельными словами не являются, в транскрипции дефисом не отделяются:

<pre>
ひぐんじか【非軍事化】(хигундзика)〔006-66-63〕
демилитаризация;
～する демилитаризовать.

префиксальный компонент 非 хи "не-, де-, анти-" + самостоятельное слово 軍事 гундзи "военное дело" + суффиксальный 化 ка "-изация, -ние".
</pre>

<pre>
いっぱんくみあいいんたいしゅう【一般組合員大衆】(иппан-кумиаиин-тайсю:)〔004-16-77〕
профсоюзные массы, рядовые члены профсоюзов.

самостоятельное слово 一般 иппан "общий" + самостоятельное слово 組合員 кумиаиин "член союза" + самостоятельное слово 大衆 тайсю: "народ". При этом 組合員 составлен в свою очередь из 組合+員, где 員 ин "член" рассматривается как несамостоятельный суффиксальный компонент.
</pre>

Для заимствованных слов принята орфография, в которой, в частности, сохранен знак ヴ для передачи европейского v (такое написание в соответствующих словах дано и в словаре 広辞苑 издательства Сайнсэйдо). Поэтому в данном словаре даются ссылки с транскрипции начального *v* через *б* на транскрипцию через *в*

<pre>
バイオリン(байорин)〔003-66-38〕
см. ヴァイオリン.
</pre>

Таблица соответствия русской транскрипции по системе Поливанова знакам каны  
Символом * отмечены слоги, использующиеся только в заимствованных словах.

<table>
    <tr>
        <td>а</td><td>あ</td>
    </tr>
    <tr>
        <td>ба</td><td>ば</td>
    </tr>
    <tr>
        <td>бё</td><td>びょ</td>
    </tr>
    <tr>
        <td>би</td><td>び</td>
    </tr>
    <tr>
        <td>бо</td><td>ぼ</td>
    </tr>
    <tr>
        <td>бу</td><td> ぶ</td>
    </tr>
    <tr>
        <td>бэ</td><td>べ</td>
    </tr>
    <tr>
        <td>бю</td><td>びゅ</td>
    </tr>
    <tr>
        <td>бя</td><td>びゃ</td>
    </tr>
    <tr>
        <td>ва</td><td>わ</td>
    </tr>
    <tr>
        <td>ва</td><td>ヴァ*</td>
    </tr>
    <tr>
        <td>ви</td><td>ヴィ*</td>
    </tr>
    <tr>
        <td>во</td><td>ヴォ*</td>
    </tr>
    <tr>
        <td>вэ</td><td>ヴェ*</td>
    </tr>
    <tr>
        <td>га</td><td>が</td>
    </tr>
    <tr>
        <td>гё</td><td>ぎょ</td>
    </tr>
    <tr>
        <td>ги</td><td>ぎ</td>
    </tr>
    <tr>
        <td>го</td><td>ご</td>
    </tr>
    <tr>
        <td>гу</td><td>ぐ</td>
    </tr>
    <tr>
        <td>гэ</td><td>げ</td>
    </tr>
    <tr>
        <td>гю</td><td>ぎゅ</td>
    </tr>
    <tr>
        <td>гя</td><td>ぎゃ</td>
    </tr>
    <tr>
        <td>да</td><td>だ</td>
    </tr>
    <tr>
        <td>дза</td><td>ざ</td>
    </tr>
    <tr>
        <td>дзё</td><td>じょ、ぢょ</td>
    </tr>
    <tr>
        <td>дзе</td><td>ジェ*</td>
    </tr>
    <tr>
        <td>дзи</td><td>じ、ぢ</td>
    </tr>
    <tr>
        <td>дзо</td><td>ぞ</td>
    </tr>
    <tr>
        <td>дзу</td><td>ず、づ</td>
    </tr>
    <tr>
        <td>дзэ</td><td>ぜ</td>
    </tr>
    <tr>
        <td>дзю</td><td>じゅ、ぢゅ</td>
    </tr>
    <tr>
        <td>дзя</td><td>じゃ、ぢゃ</td>
    </tr>
    <tr>
        <td>(ди</td><td>ディ</td>
    </tr>
    <tr>
        <td>до</td><td>ど</td>
    </tr>
    <tr>
        <td>дэ</td><td>で</td>
    </tr>
    <tr>
        <td>дю</td><td>デュ*</td>
    </tr>
    <tr>
        <td>ё</td><td>よ</td>
    </tr>
    <tr>
        <td>и</td><td>い</td>
    </tr>
    <tr>
        <td>ка</td><td>か</td>
    </tr>
    <tr>
        <td>кё</td><td>きょ</td>
    </tr>
    <tr>
        <td>ки</td><td>き</td>
    </tr>
    <tr>
        <td>ко</td><td>こ</td>
    </tr>
    <tr>
        <td>ку</td><td>く</td>
    </tr>
    <tr>
        <td>кэ</td><td>け</td>
    </tr>
    <tr>
        <td>кю</td><td>きゅ</td>
    </tr>
    <tr>
        <td>кя</td><td>きゃ</td>
    </tr>
    <tr>
        <td>ма</td><td>ま</td>
    </tr>
    <tr>
        <td>мё</td><td>みょ</td>
    </tr>
    <tr>
        <td>ми</td><td>み</td>
    </tr>
    <tr>
        <td>мо</td><td>も</td>
    </tr>
    <tr>
        <td>му</td><td>む</td>
    </tr>
    <tr>
        <td>мэ</td><td>め</td>
    </tr>
    <tr>
        <td>мю</td><td>みゅ</td>
    </tr>
    <tr>
        <td>мя</td><td>みゃ</td>
    </tr>
    <tr>
        <td>на</td><td>な</td>
    </tr>
    <tr>
        <td>нё</td><td>にょ</td>
    </tr>
    <tr>
        <td>ни</td><td>に</td>
    </tr>
    <tr>
        <td>но</td><td>の</td>
    </tr>
    <tr>
        <td>ну</td><td>ぬ</td>
    </tr>
    <tr>
        <td>нэ</td><td>ね</td>
    </tr>
    <tr>
        <td>ню</td><td>にゅ</td>
    </tr>
    <tr>
        <td>ня</td><td>にゃ</td>
    </tr>
    <tr>
        <td>о</td><td>お</td>
    </tr>
    <tr>
        <td>па</td><td>ぱ</td>
    </tr>
    <tr>
        <td>пё</td><td>ぴょ</td>
    </tr>
    <tr>
        <td>пи</td><td>ぴ</td>
    </tr>
    <tr>
        <td>по</td><td>ぽ</td>
    </tr>
    <tr>
        <td>пу</td><td>ぷ</td>
    </tr>
    <tr>
        <td>пэ</td><td>ぺ</td>
    </tr>
    <tr>
        <td>пю</td><td>ぴゅ</td>
    </tr>
    <tr>
        <td>пя</td><td>ぴゃ</td>
    </tr>
    <tr>
        <td>ра</td><td>ら</td>
    </tr>
    <tr>
        <td>рё</td><td>りょ</td>
    </tr>
    <tr>
        <td>ри</td><td>り</td>
    </tr>
    <tr>
        <td>ро</td><td>ろ</td>
    </tr>
    <tr>
        <td>ру</td><td>る</td>
    </tr>
    <tr>
        <td>рэ</td><td>れ</td>
    </tr>
    <tr>
        <td>рю</td><td>りゅ</td>
    </tr>
    <tr>
        <td>ря</td><td>りゃ</td>
    </tr>
    <tr>
        <td>са</td><td>さ</td>
    </tr>
    <tr>
        <td>сё</td><td>しょ</td>
    </tr>
    <tr>
        <td>се</td><td>シェ*</td>
    </tr>
    <tr>
        <td>си</td><td>し</td>
    </tr>
    <tr>
        <td>со</td><td>そ</td>
    </tr>
    <tr>
        <td>су</td><td>す</td>
    </tr>
    <tr>
        <td>сэ</td><td>せ</td>
    </tr>
    <tr>
        <td>сю</td><td>しゅ</td>
    </tr>
    <tr>
        <td>ся</td><td>しゃ</td>
    </tr>
    <tr>
        <td>та</td><td>た</td>
    </tr>
    <tr>
        <td>тё</td><td>ちょ</td>
    </tr>
    <tr>
        <td>те</td><td>チェ*</td>
    </tr>
    <tr>
        <td>ти</td><td>ち</td>
    </tr>
    <tr>
        <td>ти</td><td>ティ*</td>
    </tr>
    <tr>
        <td>то</td><td>と</td>
    </tr>
    <tr>
        <td>тэ</td><td>て</td>
    </tr>
    <tr>
        <td>тю</td><td>ちゅ</td>
    </tr>
    <tr>
        <td>тя</td><td>ちゃ</td>
    </tr>
    <tr>
        <td>у</td><td>う</td>
    </tr>
    <tr>
        <td>фа</td><td>ファ*</td>
    </tr>
    <tr>
        <td>фи</td><td>フィ*</td>
    </tr>
    <tr>
        <td>фо</td><td>フォ*</td>
    </tr>
    <tr>
        <td>фу</td><td>ふ</td>
    </tr>
    <tr>
        <td>фэ</td><td>フェ*</td>
    </tr>
    <tr>
        <td>ха</td><td>は</td>
    </tr>
    <tr>
        <td>хё</td><td>ひょ</td>
    </tr>
    <tr>
        <td>хи</td><td>ひ</td>
    </tr>
    <tr>
        <td>хо</td><td>ほ</td>
    </tr>
    <tr>
        <td>хэ</td><td>へ</td>
    </tr>
    <tr>
        <td>хю</td><td>ひゅ</td>
    </tr>
    <tr>
        <td>хя</td><td>ひゃ</td>
    </tr>
    <tr>
        <td>ца</td><td>ツァ*</td>
    </tr>
    <tr>
        <td>цу</td><td>つ</td>
    </tr>
    <tr>
        <td>цэ</td><td>ツェ*</td>
    </tr>
    <tr>
        <td>э</td><td>え</td>
    </tr>
    <tr>
        <td>ю</td><td>ゆ</td>
    </tr>
    <tr>
        <td>я</td><td>や</td>
    </tr>
</table>

##### 3.1.1.4 Код корпуса
Данная часть заголовка является необязательной и опускается для всех статей, принадлежащих к основному корпусу словаря.

Помимо основного корпуса в словаре есть несколько специализированных тематических корпусов, полный список которых вместе с кодами представлен в таблице ниже.

<table>
    <tr>
        <td>Корпус</td>
        <td>Код</td>
    </tr>
    <tr>
        <td>Названия мер длины с указанием их эквивалентов в метрической системе</td>
        <td>[мера длины]</td>
    </tr>
    <tr>
        <td>Названия мер поверхности с указанием их эквивалентов в метрической системе</td>
        <td>[мера поверхности]</td>
    </tr>
    <tr>
        <td>Названия мер ёмкости с указанием их эквивалентов в метрической системе</td>
        <td>[мера ёмкости]</td>
    </tr>
    <tr>
        <td>Названия мер веса с указанием их эквивалентов в метрической системе</td>
        <td>[мера веса]</td>
    </tr>
    <tr>
        <td>Географические названия</td>
        <td>[геогр.]</td>
    </tr>
    <tr>
        <td>Названия районов (区) города Токио</td>
        <td>[г. Токио]</td>
    </tr>
    <tr>
        <td>Названия районов (区) города Осака</td>
        <td>[г. Осака]</td>
    </tr>
    <tr>
        <td>Названия годов правления по японской системе летосчисления</td>
        <td>[название годов правления]</td>
    </tr>
    <tr>
        <td>Названия годов правления императоров Северной династии в период Намбокутё</td>
        <td>[название годов правления; Северная династия]</td>
    </tr>
    <tr>
        <td>Название годов правления, которые не являются нэнго: (年号) в точном смысле слова, а представляют собой посмертное имя императора, царствовавшего в указанные годы, применяемое впоследствии для их обозначения</td>
        <td>[название годов правления; посмертное имя]</td>
    </tr>
</table>

#### 3.1.2 Русский перевод