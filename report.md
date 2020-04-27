# Отчёт о тестировании KeyValidator

## Краткое описание

c 27.04.2020 по 27.04.2020 было проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 0,5 часа

В результате тестирования выявлены следующие дефекты:
* [issue 1](https://github.com/Dolmatov-vs/KeyValidator/issues/4)
* [issue 2](https://github.com/Dolmatov-vs/KeyValidator/issues/5)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md) 
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* [Форма отчетности](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/report.md)

*Примечание\*: не указывайте артефакты "для галочки". Если вы сюда напишите **тест-план**, то мы попросим вас его показать (а если не покажете - то отправим работу на доработку). Пишите только то, что реально существует и требуется в задании.*

В качестве тестовых данных использовались данные из "[Руководства использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)"
 
Валидные ключи:
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998: OK
* b295bc63-9f03-3b4b-af80-969b39f8c262: OK
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180: OK

Невалидные ключи:
* 8252235-78e0-44a5-8720-556f0c7da17a: FAIL
* e66075b6-ddad-445e-baf6-161b3289522b: FAIL
* b6d53250-f07e-4352-a293-6102ddf7f1ca: FAIL
* c2bc778a-1cb9-46c6-b435-0489649d2a42: FAIL

Тестирование производилось в следующем окружении:
* Ubuntu 20.04 LTS 64-бит
* OpenJDK 64-Bit Server VM (build 11.0.7 10-post-Ubuntu-3ubuntu1, mixed mode, sharing)
* javac 11.0.7