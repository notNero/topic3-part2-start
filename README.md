# Тема 3 Создание сложных приложений c Compose.
## Часть 2. Создание главного экрана

1.Сначала я ознакомился с задачей и понял, что мне предстоит создать сложный пользовательский интерфейс в Jetpack Compose.
2.Я начал с создания домашнего экрана с списком текущих сообщений, что является ключевой функцией приложения.
3.Затем я создал экран, на котором можно увидеть список любимых и недавно посещенных сабреддитов.
4.Я добавил Row() с двумя ArrowButtons и Text() между ними. Для каждого ArrowButton() я передал разные onClick() и векторные изображения. Это позволило мне установить разные изображения стрелок и обработчики, которые определяют, что происходит после нажатия кнопки.
5.Далее я добавил прокручиваемый столбец Column() в качестве корня, чтобы пользователь мог прокручивать по вертикали.
6.Затем я добавил Column() с заголовком вверху. Чтобы создать список сабреддитов с горизонтальной прокруткой, я использовал LazyRow() и передал уже подготовленный список SubredditModels в items().
7.Наконец, я добавил Communities() для отображения всех сообществ.
8.После завершения кодирования, я создал приложение и запустил его на своем устройстве.
9.Завершил проект

Запись приложения в последней лабораторной раздела