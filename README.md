### Всем привет 👋, меня зовут Дмитрий!

#### В этом репозитории предсталвена программа для работы с микроконтроллером семейства MSC51

Основной функцией программы является принятие информации об объекте управления от аналоговых и цифровых датчиков, вырабатывании управляющего воздействия в соответствии с заданным алгоритмом управления и подачи их на исполнительные механизмы.
Основная задача вызываемой программы обработка и сохранения сигналов АЦП в кольцевом буфере, а также реакция системы на асинхронные события.
Программа реализует следующие функции:

1. Инициализация системы в начальное состояние
2. Опрос клавиатуры
3. Обработка нажатия конкретной клавиши
4. Управление системой
