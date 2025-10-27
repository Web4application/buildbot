FROM python:3.12-slim
LABEL maintainer="Chromium Infra + Kubu Lee"
WORKDIR /app
COPY . .
RUN pip install --upgrade pip && pip install -r requirements.txt
CMD ["python", "infra_virtualenv/bootstrap.py"]
