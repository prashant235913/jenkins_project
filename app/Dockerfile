FROM python:3.8-slim

WORKDIR /app

COPY . /app

RUN pip install Flask==1.1.4 Werkzeug==0.16.1 Jinja2==2.11.3 MarkupSafe==1.1.1

EXPOSE 5000

CMD ["python", "app.py"]
