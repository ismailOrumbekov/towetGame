Здравствуйте! Хотел реализовать бета-версию в виде тетриса, не зная о том, что дедлайн уже сегодня, не смог доработать за один день, так как суббота учебный день и также защита проекта.
Игра сырая, но в ней я постарался по максимуму продемонстрировать знания ООП. 
Немного о коде:
  -Первым был реализован enum Tower, цель которого была давать координаты боксов здания(идеей было сделать здания разных форм).
  -Далее класс Box, который служит дизайном зданий в виде белых кубов, в классе присваивается цвет и размер.
  -Класс Configurations с самыми часто используемыми константами
  -Класс Coordinates содержащий положение по оси “x” и “у”, а также метод для перемещения боксов(зданий)
  -класс mainWindow в котором происходит реализация основных методов, выведения всего на экран, Action, Key listeners. К классу был имплементирован           -интерфейс Runnable, для того чтобы избежать не до конца загруденного экрана после запуска
  -класс currentTower, который обрабатывает положение и проверяет упало ли здание и есть ли возможность падать, само передвижение тоже реализовано в нем.

	Описание функционала(хоть и скудного):
Изначально выходит бокс(здание) двигающееся по диагонали в ожидании нажатия пробела, для его падения, после чего он перестает двигаться из стороны в сторону и начинает падать вниз и появляется следующий бокс. Очень большую часть реализовать не успел, но уверенно заявляю, что способен это выполнить. Большой помехой послужила учеба (пятница и суббота - защита проектов)

