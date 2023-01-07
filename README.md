# Task-25.5.1

Задание 25.5.1.

- В написанном тесте (проверка карточек питомцев) добавьте неявные ожидания всех элементов (фото, имя питомца, его возраст).
- В написанном тесте (проверка таблицы питомцев) добавьте явные ожидания элементов страницы.

Чеклист для самопроверки:
- В тестах используется настройка implicitly-wait веб-драйвера.
  - /test_show_pet_friends.py
- В тестах используются элементы класса WebDriverWait.
  - /


ЗАДАНИЕ 25.5.1 (HW-04)

Загрузите код на GitHub и отправьте ссылку на проверку.


Задание 25.3.1

Написать тест, который проверяет, что на странице https://petfriends.skillfactory.ru/my_pets со списком питомцев пользователя:

 1. Присутствуют все питомцы;
 2. Хотя бы у половины питомцев есть фото;
 3. У всех питомцев есть имя, возраст и порода;
 4. У всех питомцев разные имена;
 5. В списке нет повторяющихся питомцев. (Сложное задание).

Подсказки для решения
 1. Количество питомцев взято из статистики пользователя;
 2. Количество питомцев с фото тоже можно посчитать, взяв статистику пользователя;
 3. Необходимо собрать в массив имена питомцев;
 4. Повторяющиеся питомцы — это питомцы, у которых одинаковое имя, порода и возраст.
