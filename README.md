# Отчёт по лабораторной работе №2

## Тема

Автоматизация сборки и деплоя Python Docker-приложений через Jenkins с интеграцией GitHub.

## Цель работы

Освоить практические навыки автоматизации процесса непрерывной интеграции и развертывания (CI/CD) с использованием Jenkins — мощного инструмента автоматизации сборки, а также наладить взаимодействие с удалённым репозиторием GitHub посредством webhook, обеспечивающим мгновенный запуск сборки при каждом изменении кода.

В рамках работы создадим собственный Jenkins job, используя готовый Pipeline скрипт (Jenkinsfile), освоим управление параметрами сборки, настройку вебхуков для инициирования автоматических сборок, запустим тесты в изолированном Docker-контейнере и развернем приложение с учётом индивидуальных параметров (порт, имя студента).

## Ход выполнения работы

### 1. Настройка Jenkins pipeline

<img width="1229" height="527" alt="image" src="https://github.com/user-attachments/assets/0899fe6a-71e9-4d07-aca1-ceda88659873" />


### 2. Создание Webhook

<img width="1436" height="884" alt="image" src="https://github.com/user-attachments/assets/a0b368ce-feb4-47bb-be05-c862075ee8d2" />



### 3. Сборка

<img width="1821" height="918" alt="image" src="https://github.com/user-attachments/assets/9a3bc717-d691-469b-945a-9928d46aaa04" />



### 4. Страница

<img width="1855" height="923" alt="image" src="https://github.com/user-attachments/assets/7127e442-98fd-49da-8e14-3e25596f247e" />

