# 4-OPP
Задание
Напишите программу, которая будет получать информацию о вакансиях с разных платформ в России, сохранять ее в файл и позволять удобно работать с ней (добавлять, фильтровать, удалять).

Требования к реализации
Создать абстрактный класс для работы с API сайтов с вакансиями. Реализовать классы, наследующиеся от абстрактного класса, для работы с конкретными платформами. Классы должны уметь подключаться к API и получать вакансии.
Создать класс для работы с вакансиями. В этом классе самостоятельно определить атрибуты, такие как название вакансии, ссылка на вакансию, зарплата, краткое описание или требования и т. п. (не менее четырех) Класс должен поддерживать методы сравнения вакансий между собой по зарплате и валидировать данные, которыми инициализируются его атрибуты.
Определить абстрактный класс, который обязывает реализовать методы для добавления вакансий в файл, получения данных из файла по указанным критериям и удаления информации о вакансиях. Создать класс для сохранения информации о вакансиях в JSON-файл. Дополнительно, по желанию, можно реализовать классы для работы с другими форматами, например с CSV- или Excel-файлом, с TXT-файлом.
Создать функцию для взаимодействия с пользователем. Функция должна взаимодействовать с пользователем через консоль. Самостоятельно придумать сценарии и возможности взаимодействия с пользователем. Например, позволять пользователю указать, с каких платформ он хочет получить вакансии, ввести поисковый запрос, получить топ N вакансий по зарплате, получить вакансии в отсортированном виде, получить вакансии, в описании которых есть определенные ключевые слова, например "postgres" и т. п.
Объединить все классы и функции в единую программу.
Требования к реализации в парадигме ООП
Абстрактный класс и классы для работы с API сайтов с вакансиями должны быть реализованы в соответствии с принципом наследования.
Класс для работы с вакансиями должен быть реализован в соответствии с принципом инкапсуляции и поддерживать методы сравнения вакансий между собой по зарплате.
Классы и другие сущности в проекте должны удовлетворять минимум первым двум требованиям принципов SOLID.
Платформы для сбора вакансий
hh.ru (ссылка на API)
superjob.ru (ссылка на API)
Прежде чем начать использовать API от SuperJob, необходимо зарегистрироваться и получить токен для работы. Подробная инструкция дается по ссылке описания документации в разделе Getting started. При регистрации приложения можно указать произвольные данные.
Выходные данные
Информация о вакансиях, полученная с разных платформ, сохраненная в JSON-файл.
Отфильтрованные и отсортированные вакансии, выводимые пользователю через консоль.