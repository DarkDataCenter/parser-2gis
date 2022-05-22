# Parser2GIS
Парсер сайта [2GIS](https://2gis.ru/) с помощью браузера [Google Chrome](https://google.com/chrome).

![main](assets/screenshots/main_and_settings.png)

## Описание
Парсер для автоматического сбора базы адресов и контактов предприятий, которые работают на территории
России 🇷🇺, Казахстана 🇰🇿, Украины 🇺🇦, Беларуси 🇧🇾,
Азербайджана 🇦🇿, Киргизии 🇰🇬, Узбекистана 🇺🇿, Чехии 🇨🇿, Египта 🇪🇬, Италии 🇮🇹, Саудовской Аравии 🇸🇦, Кипра 🇨🇾, Объединенных Арабских Эмиратов 🇦🇪, Чили 🇨🇱, Катара 🇶🇦, Омана 🇴🇲, Бахрейна 🇧🇭.

## Установка
> Для работы парсера необходимо установить браузер [Google Chrome](https://google.com/chrome).

- Скачать [релиз](https://github.com/interlark/parser-2gis/releases/latest) и запустить.

- Установка из PyPI:
```bash
# CLI
pip install parser-2gis
# CLI + GUI
pip install parser-2gis[gui]
```

- Установка из репозитория:
```bash
git clone https://github.com/interlark/parser-2gis
cd parser-2gis

python -m venv venv

# Windows
.\venv\Scripts\activate
# Linux, MacOS
. venv/bin/active.bat

# CLI
pip install .
# CLI + GUI
pip install .[gui]
```

## Документация
Описание работы доступно на [вики](https://github.com/interlark/parser-2gis/wiki).
