# BlumBotNebes


## Рекомендация перед использованием

# 🔥🔥 Используйте PYTHON версии 3.10 🔥🔥


## Функционал  
|                   Функционал                   | Поддерживается |
|:----------------------------------------------:|:--------------:|
|                Многопоточность                 |       ✅        | 
|            Привязка прокси к сессии            |       ✅        | 
| Авто-регистрация аккаунта по вашей реф. ссылке |       ✅        |
|     Авто игра с выбором рандомных поинтов      |       ✅        |
|          Поддержка pyrogram .session           |       ✅        |


## [Настройки]
|          Настройки          |                                      Описание                                       |
|:---------------------------:|:-----------------------------------------------------------------------------------:|
|    **API_ID / API_HASH**    | Данные платформы, с которой будет запущена сессия Telegram (по умолчанию - android) |
|       **PLAY_GAMES**        |            Играть в игры или просто запускать фарм (по умолчанию - True)            |
|         **POINTS**          |       Кол-во очков за игру (по умолчанию - [190, 230] ((Тоесть от 190 до 230)       |
|       **AUTO_TASKS**        |             Автоматически делать задания или нет (По умолчанию - True)              |
|     **TRIBE_CHAT_TAG**      |               Тег канала у которого есть клан в блуме (для автовхода)               |
| **USE_RANDOM_DELAY_IN_RUN** |                                 Имя говорит за себя                                 |
|   **RANDOM_DELAY_IN_RUN**   |            Рандомная задержка в секундах для ^^^ (по умолчанию - [5, 30]            |
|         **USE_REF**         |  Регистрировать ваши аккаунты по вашей реф. ссылке или нет (по умолчанию - False)   |
|         **REF_ID**          |       Ваш реферальный аргумент (идет после app/startapp? в вашей реф. ссылке)       |
|   **USE_PROXY_FROM_FILE**   |       Использовать ли прокси из файла `bot/config/proxies.txt` (True / False)       |

## Быстрый старт 📚

Для быстрой установки и последующего запуска - запустите файл run.bat на Windows или run.sh на Линукс

## Предварительные условия
Прежде чем начать, убедитесь, что у вас установлено следующее:
- [Python](https://www.python.org/downloads/) **версии 3.10**
- Не забудьте на против PATH во время установки поставить галочку


## Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**Репозиторий**](https://github.com/MorinCerber/BlumBotNebes) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/MorinCerber/BlumBotNebes.git
cd BlumBotNebes
```

Затем для автоматической установки введите:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
sudo sh install.sh
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Здесь вы обязательно должны указать ваши API_ID и API_HASH , остальное берется по умолчанию
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/BlumBotNebes >>> python3 main.py --action (1/2)
# Or
~/BlumBotNebes >>> python3 main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```


# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Указываете ваши API_ID и API_HASH, остальное берется по умолчанию
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/BlumBotNebes >>> python main.py --action (1/2)
# Или
~/BlumBotNebes >>> python main.py -a (1/2)

# 1 - Запускает кликер
# 2 - Создает сессию
```




### Контакты

