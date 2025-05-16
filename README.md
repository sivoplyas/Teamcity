# Teamcity
## 1 Создайте новый проект в teamcity на основе fork.
## 2 Сделайте autodetect конфигурации.
![4](https://github.com/user-attachments/assets/bb7a6426-2aa3-440c-86a6-41dacd899be2)
## 3 Сохраните необходимые шаги, запустите первую сборку master.
![5](https://github.com/user-attachments/assets/72a0c181-22d0-4b24-b753-7932c80b050e)
## 4 Поменяйте условия сборки: если сборка по ветке master (В github по умолчанию ветка main и я поменял условие), то должен происходит mvn clean deploy, иначе mvn clean test.
![9](https://github.com/user-attachments/assets/f35bf740-1ac2-4568-8a0a-fdc53a5ce7a5)
## 6 (settings.xml) и 7 (pom.xml)
https://github.com/sivoplyas/example-teamcity
## 7 Запустите сборку по master, убедитесь, что всё прошло успешно и артефакт появился в nexus.
![10](https://github.com/user-attachments/assets/5d754f0d-d7f6-43c5-a2ac-07385fa10348)
## 8 Мигрируйте build configuration в репозиторий.
![11](https://github.com/user-attachments/assets/96579aec-a2a8-4b09-8882-aa587f3ca44e)
## 9 Создайте отдельную ветку feature/add_reply в репозитории.
![333](https://github.com/user-attachments/assets/480f1168-7566-426a-a192-4830d52e6a2c)
## 10 Напишите новый метод для класса Welcomer: метод должен возвращать произвольную реплику, содержащую слово hunter.
![444](https://github.com/user-attachments/assets/eb32dde3-a91c-4d20-bf79-83e32871ab29)
![555](https://github.com/user-attachments/assets/f7f68963-5281-4e2f-abaf-9345e88e0ed8)
## 11 Дополните тест для нового метода на поиск слова hunter в новой реплике.
![666](https://github.com/user-attachments/assets/b4bb5725-fef7-4d8c-8286-a8586a9d42a8)
## 12, 13 Убедитесь, что сборка самостоятельно запустилась, тесты прошли успешно.
![12](https://github.com/user-attachments/assets/e386caa7-fc95-4dbc-bdfd-dcd1c65fe17c)
## 14, 15, 16,17,18 Проверьте, что конфигурация в репозитории содержит все настройки конфигурации из teamcity.
![13](https://github.com/user-attachments/assets/e1013253-4a02-4890-a7cc-43c9fdab9ed1)
![14](https://github.com/user-attachments/assets/ea9ce144-7317-4d09-839e-d2937d530a34)
![15](https://github.com/user-attachments/assets/5e014cc7-f292-4702-bb6b-674b7394f8f7)
![16](https://github.com/user-attachments/assets/fbb7ea57-0e2c-40ea-b628-acb4e8cd3b2b)
