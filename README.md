# Викторина в VK и Telegram

## Вопросы викторины
Создайте папку `quiz-questions` и разместите в ней файлы викторины

***

## Зависимости
Установите зависимости командой:  
```sh
pip install -r requirements.txt
```

***

## Переменные окружения
### Как получить
Чтобы определить переменные окружения, создайте файл `.env` в корневой папке и запишите туда данные в формате:  
`ПЕРЕМЕННАЯ=значение`.

#### Обязательные переменные:  

| Переменная           | Описание                                                                                     |
|:---------------------|:---------------------------------------------------------------------------------------------|
| TG_TOKEN             | токен от API [Telegram ](https://telegram.me/BotFather "получить токен от API Telegram Bot") | 
| VK_TOKEN             | токен от API VK                                                                    |
| REDIS_HOST             | хост от сервиса Redis                                                                        |
| REDIS_PORT             | порт от сервиса Redis                                                                        |
| REDIS_PASSWORD             | пароль от сервиса Redis                                                                      |

***

## Запуск
Запустите программу командой
```sh
python tg.py
python vk.py
```

***

## Ссылки
| Ссылка                                             |
|:---------------------------------------------------|
| [Моя викторина в VK](https://vk.com/club225809840) |
| [Моя викторина в TG](https://t.me/k1_quiz_bot)     |