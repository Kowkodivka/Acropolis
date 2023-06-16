# Acropolis
Mindustry бот написанный на Ruby + Java

# Установка
1. Зайти в папку MindustryAPI
2. Скомпилировать .jar файл с помощью `./gradlew jar` (Linux) `gradlew jar` (Windows)
3. Альтернативно можно скачать готовый .jar файл в разделе "Релизы"
4. Появившийся в /build/libs MindustryAPI.jar переместить в папку Acropolis-Bot
5. Заполнить конфиг config.yaml бота
6. Если планируется использовать эмодзи в схемах - зайти в src/utils.rb и выставить там нужные ID эмодзи
7. В консоли прописать `bundle install`
8. Запустить бота `bundle exec ruby main.rb`
9. При первом запуске программа скачает/сгенерирует недостающие файлы
10. Бот готов к использованию

# Что делает этот бот
На данный момент бот выполняет следующие функции:
1. Обработка схем/карт mindustry
2. Система предупреждений
3. Логирование сообщений в отдельный канал
4. Удаление большого количества сообщений за раз
5. Возможность отправлять эмбеды и сообщения от имени бота
