# Python PEP Parsing Project

## Парсер документов PEP на базе фреймворка Scrapy.

### Установка

```
git clone https://github.com/PavelFil98/scrapy_parser_pep.git
```

```
cd scrapy_parser_pep
```

```
python3 -m venv venv && source venv/bin/activate
```

```
pip install -r requirements.txt
```


### Запуск

Command to get all existing PEPs along with they actual statuses:

```
scrapy crawl pep
```
Результаты появятся в папке `results`

Автор: Павел Филипович
