# home_work1.1-java
# Отчёт о тестировании KeyValidator

## Краткое описание

11.09.2020 проведено функциональное тестирование приложения KeyValidator.

На тестирование затрачено: 6 часов

В результате тестирования выявлены следующие дефекты:
* https://github.com/Rimmkin/home_work1.1-java/issues/1#issue-699284778
* https://github.com/Rimmkin/home_work1.1-java/issues/2#issue-699293378
* https://github.com/Rimmkin/home_work1.1-java/issues/3#issue-699299187

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Инструкция по установке OpenJDK 11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)
* [Руководство использования приложения KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
* Баг-репорт

В качестве тестовых данных использовались данные из [Руководства использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):

Валидные ключи:
1. 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
2. 80b427f8-92cd-3aae-ba04-3927fbe17c6
3. b295bc63-9f03-3b4b-af80-969b39f8c262
4. 387eedc6-12e9-3b32-9881-63b6b5e85317
5. c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:
1. 18252235-78e0-44a5-8720-556f0c7da17a
2. e66075b6-ddad-445e-baf6-161b3289522b
3. b6d53250-f07e-4352-a293-6102ddf7f1ca
4. c2bc778a-1cb9-46c6-b435-0489649d2a42
5. 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Тестирование производилось в следующем окружении:
* Устройство: Asus N73S
* ОС: Windows 10 Pro-64 bit
* Java version: "11.0.8" 2020-07-14
