Путешествие по россии.
Описание проекта: Проектная работа № 3 - адаптивная верстка.
В проекте реализованы инструменты Грид, медиа запросы и тд.
Ссылка на гит (https://github.com/Magomedovv/Magomedovv---russian-travel)


Замечания 


* 		На десктопных разрешениях (1000px +) страница прокручивается по горизонтали.
Чтобы локализовать причину возникновения горизонтального скролла, можно воспользоваться свойством outline и применить его глобально:
* { outline: 1px solid white; }
Все элементы на странице будут обведены линией, и можно быстро определить, какой из элементов выходит за рамки.

Ответ:
Выходил за рамки Хедер - поменял в медиа запросе максимальный размер на 1120, скролл удалил. 


* 		Некорректно подключен шрифт.
Файлы шрифтов необходимо скачать и подключить к проекту. В макете используются шрифты Inter с насыщенностью 400, 700 и 900. Это Inter-Regular, Inter-Bold и Inter-Black.

Исправлено, подключил шрифты.


* 		Один или несколько блоков неверно отображаются в Firefox, Google Chrome или Yandex Browser

Изображение в блоке cover не отображается, а в консоли ошибка: https://disk.yandex.ru/i/TegmpHHS8VmuxQ

Ответ - проверил все три браузера отлично отображают изображение в блоке cover


* 		Есть ошибки в структуре БЭМ. Воспользуйтесь валидатором для проверки: https://nglazov.github.io/bem-validator-page/

Ответ: ошибки были в Хедер и в Футер - исправлено!


* 		Эффект изменения прозрачности при наведении должен срабатывать на любом участке блока cover, в том числе и при наведении указателя мыши на текст. При этом затемняться должен только фон, а текст всегда должен быть без затемнения.
 - Исправлено!

* 		На мобильных разрешениях экрана страница прокручивается по горизонтали, необходимо это исправить.
       Прокрутка минимальная - исправлено 

* 		Сейчас размеры и положение некоторых элементов отличаются от макета. По чек-листу размеры элементов и отступы могут отличаются от макета не больше, чем на 30px на разрешении 1280px и 1024px. На разрешении 768px и 320px отклонение от макета должно быть не более 10px.


Ответ: все отступы установлены в соответствии с макетом, я нижний марджин у всех обнулял а верхним марджином менял отступ