# FastAPI Hello World با Docker Compose

این یک پروژه ساده Hello World با FastAPI است که در Docker Compose اجرا می‌شود.

## نحوه اجرا

1. اطمینان حاصل کنید که Docker و Docker Compose روی سیستم شما نصب شده‌اند.
2. در ترمینال، به دایرکتوری پروژه بروید.
3. دستور زیر را اجرا کنید:
   ```bash
   docker-compose up --build
   ```
4. به آدرس http://localhost:8000 در مرورگر خود بروید.

## API Endpoints

- `GET /`: پیام Hello World را برمی‌گرداند
- `GET /docs`: مستندات Swagger UI را نمایش می‌دهد 