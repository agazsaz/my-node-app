# my-node-app
Лабораторная работа: настройка пайплайна CI/CD для Node.js-приложения с использованием GitHub Actions и Docker.
## 1. Локальная сборка DockerПриложение успешно собирается и запускается в контейнере. Команда `docker run` выводит приветствие.
**<img width="375" height="78" alt="изображение" src="https://github.com/user-attachments/assets/b518942b-8093-4bbf-a8a8-41d3c99fd7d3" />
**
## 2. Успешный запуск пайплайна (GitHub Actions)Пайплайн тестирует приложение на трёх версиях Node.js (18, 20, 22) и собирает Docker-образ. Все этапы завершились успешно.
**<img width="1417" height="318" alt="изображение" src="https://github.com/user-attachments/assets/d69b6edb-c467-4d35-b51d-b76a07dbe8aa" />
**
## 3. Логи линтинга и тестированияВ джобе `Lint & Test` успешно пройдены проверки ESLint и тесты Jest.
**<img width="339" height="630" alt="изображение" src="https://github.com/user-attachments/assets/447d5958-a0d8-400e-abce-c2c0024e0ccf" />**

## 4. Логи сборки Docker-образаДжоб `Build Docker Image` успешно собрал образ приложения.
**<img width="362" height="434" alt="изображение" src="https://github.com/user-attachments/assets/26444216-4464-4c8b-b2c4-98d3bd0b3371" />
**

## ВыводНастроен полный цикл CI для Node.js-приложения. Автоматизированы линтинг, тестирование на разных версиях Node.js и сборка Docker-образа. Все задачи выполнены.
