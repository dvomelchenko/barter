# barter
Проект для безналичного расчета между пользователями


### Описание API  сервера

~~Авторизация(запрос):~~

Описание | Значение
------------ | -------------
*url*  | http://domain.net/api/v1/user
*login* | string
*password* | string
*app_version* | string (пример 1.2.300)
*os* | string (android/ios)
*device* | string
*lat* | string
*lng* | string


Авторизация(ответ):

Описание | Значение
------------ | -------------
*status* | string (success/error)
*code* | int (400,401 etc.)
*error_description* | string  (текст ошибки)
*token* | string 
*user_name* | string
*age* | int
*еще какая-то дополнительная информация* | string

Данные о пользователе(запрос):

Описание | Значение
------------ | -------------
*id_user* | int
*token* | string


Данные о пользователе(ответ):

Описание | Значение
------------ | -------------
*name* | string
*age* | int
*rating* | float
*location*  | string
*photo* | string (ссылка на картинку)













