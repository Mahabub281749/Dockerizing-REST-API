FROM python:3
WORKDIR /Docker/web
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt
COPY . .
CMD ["python", "app_2.py"]
