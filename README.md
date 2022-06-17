# KeyLogger-and-TelegramBot
KeyLogger связанный с телеграмм ботом

----------------------------Создание телеграмм бота ----------------------------

Найти в телеграмме @BotFather  и написать /newbot и придумать имя бота
![image](https://user-images.githubusercontent.com/81647057/174259900-f4fbd574-99de-4c40-bed5-fa7e19b9cee7.png)

Скопировать токен, который выслал бот и вставить в код

----------------------------Компеляция в .exe----------------------------

Установить pyinstaler командой pip install pyinstaller в терминале

![image](https://user-images.githubusercontent.com/81647057/174260721-1bd976a6-4f8f-4588-b8a0-4f6ac719a6df.png)

Запустить команду pyinstaller --onefile main.py в дериктории с файлом main.py

![image](https://user-images.githubusercontent.com/81647057/174261301-581676b6-afdd-4f53-8a5e-7e2660233030.png)

В папке с файлом main.py появится папка dist, где и лежит наш main.exe файл

![image](https://user-images.githubusercontent.com/81647057/174261611-c7105768-b97d-4760-8c25-c6de710a04b8.png)

Пишем боту(которого мы создали) /start и выбираем вариант логов: либо сообщениями в телеграмм, либо файлом (лучше сообщениями в телеграмм, так как сохранение в файл работает не всегда коректно)

![image](https://user-images.githubusercontent.com/81647057/174263293-566f454f-0e0a-4285-8b7b-389df715eb2e.png)

Время через которое бот отправляет сообщение можно изменить

![image](https://user-images.githubusercontent.com/81647057/174263383-002787ed-495d-4525-9a30-0420906bf108.png)

Лучше ставить более 10 секунд
