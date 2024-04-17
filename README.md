Дана таблица table:
  userId - идентификатор пользователя
  eventName - действия пользователя, может принимать несколько значений (
      'register'-пользователь зарегистрировлся в RuStore;
      'download'-пользователь скачал приложение;
      'buy'-пользователь сделал покупку в приложении;)
  time - время, в которое было совершено действие eventName
  product - идентификатор приложения.

Задачи:
1. Для каждой недельной когорты (столбей "week") вывести количество пользователей посетивших стор ("users") и конверсию в заргрузку приложения ("CR")
2. Написать задачу 1 на Pandas
3. Для каждой недельной когорты (столбей "week") вывести рейтинг ("rating") приложений ("product") по конверсии в покупку
