# Test-cases

![img](https://github.com/DariaStavytska/Test-cases/blob/main/testcase%20(1).jpg)

Тест-кейс – це професійна документація тестувальника, послідовність дій, спрямована на перевірку будь-якого функціоналу, що описує як прийти до очікуваного результату.
Під тест-кейсом також може матися на увазі відповідний документ, який являє собою формальний запис тест-кейса.

Також виділяють:

– високорівневий тест-кейс (high level test case) – тест-кейс без конкретних вхідних даних та очікуваних результатів.
Як правило, такий тест-кейс обмежується загальними ідеями та операціями, схожий за своєю суттю з докладно описаними пунктами чекліста. Досить часто зустрічається в інтеграційному і системному тестуванні, а також на рівні димового тестування. Може служити відправною точкою для проведення дослідного тестування або для створення низькорівневих тест-кейсів.

– низькорівневий тест-кейс (low level test case) – тест-кейс з конкретними вхідними даними та очікуваними результатами.  
Являє собою «повністю готовий до виконання» тест-кейс і є найбільш класичним видом тест-кейсів. Початківців тестувальників найчастіше вчать писати саме такі кейси, тому що прописати всі дані докладно набагато простіше, ніж зрозуміти, якою інформацією можна знехтувати, при цьому не знизивши цінність тест-кейса.

У тестуванні слово «кейс» слід перекладати як «ситуація» просто тому, що тест-кейс – це ситуація, яку потрібно створити для перевірки роботи однієї окремо взятої функціональності. Всі кроки, перераховані в кейсі, дають можливість перевірити лише одну тестову ситуацію, лише один сценарій використання ПЗ.

Тема кейса – описова назва тесту, яка спрощує його пошук та розуміння його змісту.

У темі тест-кейса не повинно бути:

1.Залежностей від інших тест-кейсів. Пов'язаний тест-кейс завжди може бути видалений через непотрібність або він може бути змінений, у цьому випадку стане незрозуміло, як виконати тест-кейс, в якому є посилання. Також, через залежність тест-кейсів, може виникнути відчуття, що тестований продукт вже приведений до потрібного стану завдяки виконанню пов'язаних тест-кейсів.

2.Нечітких формулювань. Якщо опис теми буде нечітким, то це, як мінімум, ускладнить проходження тест-кейса і сприйняття тест-сьюта в цілому.

При створенні теми тест-кейса потрібно пам'ятати:
-те, що очевидно для вас зараз, може стати абсолютно незрозумілим через декілька місяців.
Так, скорочення з нерозшифрованими абревіатурами, зрозумілими вам зараз, можуть згодом стати китайською грамотою для вас самих, тому простіше буде написати тест-кейс заново, ніж пробиратися через нетрі необачно зроблених скорочень, як у темі, так і всередині кейса;
-тест-кейс, тема якого не може бути зрозуміла і згодом виконана ніким, крім його автора, повинен бути публічно знищений.
Обгрунтування просте: автор кейса може захворіти, піти у відпустку, піти з компанії і т.д. Будь-який тест-кейс повинен створюватися з думкою про колегу, який одного разу візьме його в руки.

Приклад:
Якщо тема порожня або ж в ній просто надруковано «10», то кожна людина, виконуючий цей тест-кейс, кожен раз буде витрачати кілька хвилин свого часу і/або часу свого колеги на з'ясування того, що ж перевіряється цим тест-кейсом.

3.Зайвої деталізації. Надлишкова інформація лише ускладнює розуміння вкладеного в тему сенсу.
Тестувальник при виконанні тест-кейса спочатку прочитає тему, усвідомить її та вже приблизно уявить, що йому зараз потрібно буде виконати, і тільки після цього перейде до кроків.




