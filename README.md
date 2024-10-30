
# FastAPI User Management

Это простое веб-приложение на FastAPI для получения данных по btc_usd и eth_usd с криптобиржи Deribit.

## Требования

Для запуска приложения необходим Python 3.10. 
Зависимости вы можете установить, выполнив следующую команду:

```bash
pip install -r requirements.txt
```
Запуск приложения
Выполните следующую команду, чтобы запустить приложение с помощью Uvicorn
```bash
uvicorn main:app --reload
```
## API Endpoint можно протестировать через Swagger:

http://127.0.0.1:8000/docs

ticker `eth_usd` или `btc_usd`

date_from в формате `UNIX timestamp`