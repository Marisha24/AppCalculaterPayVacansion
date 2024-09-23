# Имя проекта
Приложение состит из одного API: GET "/calculacte"
Приложение принимает среднюю зарплату за 12 месяцев и количество дней отпуска - отвечает суммой отпускных, которые придут сотруднику.
Также реализовано: подсчет отпускных по точным дням ухода в отпуск, с учётом праздников и выходных
# API requests
Простой запрос:
localhost:8092/calculacte?yearSalary=10000&vacationDays=10
Response: {3412.9692832764504}

Запрос с указанием точного дня ухода в отпуск:
localhost:8092/calculacte?yearSalary=10000&vacationDays=10
Response:{2389.078498293515}


## Postman

- Простой запрос:


![image](https://github.com/user-attachments/assets/240261d4-2e9c-4e39-b6b1-76a668ae6984)



- Запрос с указанием точного дня ухода в отпуск:


 ![image](https://github.com/user-attachments/assets/95b4c79d-3ec8-458e-a42a-76202526bf46)


Формута взята из [статьи](https://journal.tinkoff.ru/guide/otpusk-stitaem/)


