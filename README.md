 # AppCalculaterPayVacansion
 Комититьс сюда!
# Имя проекта
Приложение состит из одного API: GET "/calculacte"
Приложение принимает среднюю зарплату за 12 месяцев и количество дней отпуска - отвечает суммой отпускных, которые придут сотруднику.
Также реализовано: подсчет отпускных по точным дням ухода в отпуск, с учётом праздников и выходных
# API requests
Простой запрос:
localhost:8091/calculacte?yearSalary=10000&vacationDays=10
Response: {3412.9692832764504}

Запрос с указанием точного дня ухода в отпуск:
localhost:8091/calculacte?yearSalary=10000&vacationDays=10
Response:{2389.078498293515}


## Postman

- Простой запрос:



- Запрос с указанием точного дня ухода в отпуск:

Формута взята из [статьи](https://journal.tinkoff.ru/guide/otpusk-stitaem/)



