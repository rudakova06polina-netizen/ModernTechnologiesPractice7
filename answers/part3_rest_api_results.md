# Часть 3: REST CRUD

Запишите ответы и HTTP-коды.

| Запрос |    HTTP-код | Тело ответа / заметки                     |
|---|------------:|-------------------------------------------|
| POST `/api/students` | 201 Created | {"id":1,"name":"Ali","surname":"Hasan"}   |
| GET `/api/students` |      200 OK | [{"id":1,"name":"Ali","surname":"Hasan"}] |
| GET `/api/students/1` |   200 OK          | {"id":1,"name":"Ali","surname":"Hasan"}   |
| PUT `/api/students/1` |    200 OK         | {"id":1,"name":"Ivan","surname":"Petrov"} |
| DELETE `/api/students/1` |    204 No Content         | ничего                                    |
