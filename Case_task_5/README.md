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


## Анализ выполнения задачи
* Разработка классов: Были созданы классы Task и TaskList для представления задач и управления списком задач. 
Класс Task включает описание задачи и её статус выполнения.
* Функционал добавления задач: Реализована возможность добавления новых задач в список, что позволяет 
пользователю наращивать количество задач для выполнения.
* Функционал удаления задач: Добавлена функция удаления задач по индексу, чтобы пользователь мог избавиться от 
выполненных или неактуальных задач.
* Отображение задач: Реализовано отображение всех задач и выполненных задач, что даёт пользователю возможность 
отслеживать статус выполнения.
* Отметка о выполнении задач: Задачи могут быть помечены как выполненные, что добавляет интерактивности и позволяет 
отделить выполненные задачи от активных.
* Сохранение и загрузка из файла: Список задач может быть сохранён и загружен из файла, что обеспечивает сохранность 
данных между сессиями и гибкость использования приложения.
* Обработка ошибок: Добавлена базовая обработка ошибок при работе с индексами и файлами для улучшения пользовательского
опыта и предотвращения критических сбоев.

## Рекомендации по устранению выявленных ошибок
* Улучшение обработки индексов: Добавить более подробные сообщения об ошибках при вводе неправильных индексов, 
чтобы пользователь понимал, что необходимо делать.
* Проверка ввода пользователя: Добавить валидацию ввода пользователя для предотвращения некорректных данных и сбоев 
приложения.
* Оптимизация работы с файлами: Добавить проверку на наличие файла при загрузке задач, чтобы избежать ошибок при 
отсутствии файла.
* Разделение логики: Разделить логику сохранения задач и завершения работы приложения, чтобы пользователь мог 
сохранять задачи по своему усмотрению в любой момент.
* Интерфейс пользователя: Улучшить консольный интерфейс для более удобного взаимодействия (например, добавление меню
для возврата к предыдущим действиям).
* Многопользовательская поддержка: Реализовать поддержку нескольких пользователей, чтобы каждый пользователь имел 
свой отдельный список задач.
* Тестирование и обработка исключений: Добавить тестирование и улучшить обработку исключений для повышения 
стабильности приложения.
