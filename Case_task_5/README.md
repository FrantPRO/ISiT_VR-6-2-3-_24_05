# Кейс-задача № 5

## Создание приложения для управления задачами
* Создайте консольное приложение на языке программирования по вашему выбору 
  (Java, C#, C++ или JavaScript).
* Разработайте классы для представления задач и списка задач.
* Реализуйте функционал добавления, удаления и отображения задач в списке.
* Добавьте возможность пометить задачу как выполненную и отображать список 
  выполненных задач.
* Реализуйте сохранение списка задач в файл и загрузку списка из файла
* Опишите подробный анализ по выполненной задаче (не менее 7 пунктов)
* Опишите рекомендации по устранению выявленных ошибок в ходе выполнения задачи


## Подробный анализ по выполненной задаче
1. Определение требований: Исходя из задачи, определены ключевые функции приложения: 
   создание, удаление, отображение задач, пометка выполнения и сохранение/загрузка из файла.
2. Выбор структуры данных: Для хранения задач выбрана структура std::vector, 
   так как она предоставляет удобный интерфейс для добавления и удаления элементов.
3. Модульность: Разработка разделена на два класса (Task и TaskList), что способствует 
   лучшему разделению ответственности и упрощает тестирование и расширение функционала.
4. Обработка ошибок: В функции удаления и пометки выполнения задач добавлены проверки 
   на корректность индекса, что предотвращает некорректное поведение программы.
5. Работа с файлами: Для сохранения и загрузки задач выбрана простая текстовая 
   структура с разделителем, что упрощает парсинг данных и сохраняет их человекочитаемость.
6. Расширяемость: Код легко расширить, добавив новые функции, такие как изменение 
   описания задачи или приоритет задач.
7. Тестирование: Базовая функциональность была протестирована, и выявлено, что 
   основные функции работают корректно, однако возможны ошибки при работе с 
   файлами (например, файл может отсутствовать).


## Рекомендации по устранению выявленных ошибок
1. Проверка наличия файла: Добавить проверку наличия файла перед его чтением, 
   чтобы предотвратить краш программы.
2. Обработка исключений: Реализовать обработку исключений при работе с файлами, 
   например, используя блоки try-catch.
3. Валидация ввода: Добавить проверки пользовательского ввода для предотвращения 
   ошибок, таких как ввод некорректного индекса задачи.
4. Тестирование на границах: Провести тестирование на крайних значениях, например, 
   добавление/удаление большого количества задач.
5. Кодировка файлов: Убедиться, что программа правильно обрабатывает кодировку файлов, 
   особенно если приложение будет использоваться в многоязычной среде.
6. Документация: Описать функционал каждой функции и класса, что упростит поддержку 
   и расширение программы.
7. Интерфейс: Добавить удобный текстовый интерфейс для взаимодействия с пользователем, 
   чтобы программа была более интуитивно понятной.
