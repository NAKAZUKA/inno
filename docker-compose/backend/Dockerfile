FROM python:3.9-slim

WORKDIR /app

# Копируем requirements.txt и устанавливаем зависимости
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Копируем весь код в контейнер
COPY . .

# Указываем команду для запуска Python-скрипта
CMD ["python", "main.py"]
