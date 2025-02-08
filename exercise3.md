# Попарное тестирование
https://www.saucedemo.com/   
Поле "username" может принимать следующие значения:
- пустое значение
- standard_user
- locked_out_user
- problem_user
- performance_glitch_user
- некорректное значение (любое иное)

Поле "Password" может принимать следующие значения:
- пустое значение
- secret_sauce
- некорректное значение (любое иное)

|Тест-кейс| "Username"             | "Password"           |
|---------|------------------------|----------------------|
| 1       |пустое значение         |пустое значение       |
| 2       |пустое значение         |secret_sauce          |
| 3       |пустое значение         |некорректное значение |
| 4       |standard_user           |пустое значение       |
| 5       |standard_user           |secret_sauce          |
| 6       |standard_user           |некорректное значение |
| 7       |locked_out_user         |пустое значение       |
| 8       |locked_out_user         |secret_sauce          |
| 9       |locked_out_user         |некорректное значение |
| 10      |problem_user            |пустое значение       |
| 11      |problem_user            |secret_sauce          |
| 12      |problem_user            |некорректное значение |
| 13      |performance_glitch_user |пустое значение       |
| 14      |performance_glitch_user |secret_sauce          |
| 15      |performance_glitch_user |некорректное значение |
| 16      |некорректное значение   |пустое значение       |
| 17      |некорректное значение   |secret_sauce          |
| 18      |некорректное значение   |некорректное значение |

# Список тест-кейсов

## Тест-кейс №1 — "Username" пустое значение, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести пустое значение
    - в поле "Password" ввести пустое значение 
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №2 — "Username" пустое значение, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести пустое значение
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №3 — "Username" пустое значение, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести пустое значение
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №4 — "Username" standard_user, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести standard_user
    - в поле "Password" ввести пустое значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №5 — "Username" standard_user, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести standard_user
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - пользователь успешно авторизуется, переходит на главную страницу магазина
***
## Тест-кейс №6 — "Username" standard_user, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести standard_user
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №7 — "Username" locked_out_user, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести locked_out_user
    - в поле "Password" ввести пустое значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №8 — "Username" locked_out_user, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести locked_out_user
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Sorry, this user has been locked out."
***
## Тест-кейс №9 — "Username" locked_out_user, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести locked_out_user
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №10 — "Username" problem_user, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести problem_user
    - в поле "Password" ввести пустое значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №11 — "Username" problem_user, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести problem_user
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - пользователь успешно авторизуется, переходит на главную страницу магазина
***
## Тест-кейс №12 — "Username" problem_user, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести problem_user
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №13 — "Username" performance_glitch_user, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести performance_glitch_user
    - в поле "Password" ввести пустое значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №14 — "Username" performance_glitch_user, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести performance_glitch_user
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - пользователь успешно авторизуется, переходит на главную страницу магазина
***
## Тест-кейс №15 — "Username" performance_glitch_user, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести performance_glitch_user
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №16 — "Username" некорректное значение, "Password" пустое значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести некорректное значение
    - в поле "Password" ввести пустое значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №17 — "Username" некорректное значение, "Password" secret_sauce

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести некорректное значение
    - в поле "Password" ввести secret_sauce
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***
## Тест-кейс №18 — "Username" некорректное значение, "Password" некорректное значение

1. Предшествующие условия:
    - пользователь находится на странице авторизации 
2. Шаги:
    - в поле "Username" ввести некорректное значение
    - в поле "Password" ввести некорректное значение
    - нажать зеленую кнопку "Login"
3. Ожидаемый результат:
    - отображается ошибка "Epic sadface: Username and password do not match any user in this service"
***